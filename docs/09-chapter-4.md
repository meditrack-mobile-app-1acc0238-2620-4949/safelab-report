# **Chapter IV: Product Implementation & Validation**
## **4.1. Configuration Management Software**
### **4.1.1. Software Development Environment Configuration**
### **4.1.2. Source Code Management**
### **4.1.3. Source Code Style Guide & Conventions**
### **4.1.4. Software Deployment Configuration**
## **4.2. Landing Page & Mobile Application Implementation**
### **4.2.1. Sprint 1**
#### **4.2.1.1. Sprint Planning 1**
#### **4.2.1.2. Aspect Leaders and Collaborators**
#### **4.2.1.3. Sprint Backlog 1**
#### **4.2.1.4. Development Evidence for Sprint Review**

#### **4.2.1.5. Testing Suite Evidence for Sprint Review**

<p style="text-align: justify;">
  En esta sección se presenta el conjunto de pruebas automatizadas elaborado para los Web Services de la <i>SafeLab Platform API</i> relacionados con las User Stories del Sprint 1: <b>US60 - Proporcionar servicios de organización del monitoreo</b>, <b>US61 - Proporcionar servicios de monitoreo ambiental</b> y <b>US16 - Recolección automática de datos</b>. El conjunto incluye Unit Tests, Integration Tests y Acceptance Tests bajo el enfoque BDD, desarrollados con JUnit 5, Mockito, AssertJ, Spring Boot Test (MockMvc) y Cucumber 7.20.1. Las pruebas de integración y aceptación se ejecutan sobre una base de datos H2 en memoria con el perfil <code>test</code>, y cada caso inicia desde los datos semilla de la API para garantizar resultados reproducibles.
</p>

<p style="text-align: justify;">
  Los proyectos de testing se encuentran en el repositorio del backend <b>safelab-platform-api</b>, en las rutas <code>src/test/java/com/safelab/platform</code> (clases de prueba y Steps) y <code>src/test/resources/features</code> (archivos <code>.feature</code>).
</p>

<p align="center">
  <img src="../assets/09-chapter-4/testing-project-structure.png" alt="Estructura del proyecto de testing de la SafeLab Platform API." width="100%">
</p>

<p align="center"><i>Figura: Estructura del proyecto de testing de la SafeLab Platform API.</i></p>


##### **Unit Tests**

<p style="text-align: justify;">
  Los Unit Tests verifican de forma aislada el comportamiento de las clases que soportan los servicios del Sprint 1. Las dependencias de cada clase se reemplazan con <i>mocks</i> de Mockito, por lo que estas pruebas no levantan el servidor ni acceden a la base de datos. La siguiente tabla relaciona cada clase de prueba con la clase evaluada, los comportamientos verificados y las User Stories asociadas.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Test Class</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Clase evaluada</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Tests y comportamientos verificados</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">User Story</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align:center; vertical-align: top; padding:6px;">JsonCollectionServiceTest</td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>JsonCollectionService</code></td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>findByIdReturnsTheEquipmentWhenItExists</code>: retorna el equipo solicitado.<br><code>findByIdThrowsNotFoundWhenTheItemDoesNotExist</code>: responde 404 si el recurso no existe.<br><code>getThrowsNotFoundWhenTheCollectionDoesNotExist</code>: responde 404 si la colección no existe.<br><code>createGeneratesAPrefixedIdAndCreationDate</code>: genera el id con prefijo y la fecha de creación.<br><code>createKeepsTheIdSentByTheClient</code>: conserva el id enviado.<br><code>patchUpdatesOnlyTheSentFields</code>: actualiza solo los campos enviados.<br><code>deleteThrowsNotFoundWhenTheItemDoesNotExist</code>: no elimina ni guarda si el recurso no existe.<br><code>numberReturnsFallbackWhenTheValueIsNotNumeric</code>: interpreta lecturas numéricas y no numéricas.</td><td style="text-align:center; vertical-align: top; padding:6px;">US60, US61</td></tr>
    <tr><td style="text-align:center; vertical-align: top; padding:6px;">BusinessEventServiceTest</td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>BusinessEventService</code></td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>createAlertRegistersAnActiveAlert</code>: registra la alerta activa con severidad normalizada, notificación y entrada de auditoría.<br><code>createAlertUsesDefaultsWhenDataIsMissing</code>: aplica severidad <i>warning</i> y responsable por defecto.<br><code>auditUsesSystemAsActorWhenTheActorIsBlank</code>: registra la auditoría con actor <i>System</i>.<br><code>createIncidentFromAlertOpensALinkedIncident</code>: abre un incidente vinculado a la alerta, sensor y equipo.</td><td style="text-align:center; vertical-align: top; padding:6px;">US16</td></tr>
    <tr><td style="text-align:center; vertical-align: top; padding:6px;">SensorMonitoringControllerTest</td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>SensorMonitoringController</code></td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>recordReadingKeepsNormalStatusInsideTheRange</code>: registra la lectura sin generar alerta.<br><code>recordReadingCreatesACriticalAlertAboveTheMaximumTemperature</code>: genera alerta crítica por temperatura.<br><code>recordReadingDetectsValuesBelowTheMinimum</code>: detecta valores bajo el mínimo.<br><code>recordReadingCreatesAWarningAlertForHumidity</code>: genera alerta de advertencia por humedad.<br><code>disconnectMarksTheSensorOffline</code>: detecta la ausencia de datos y genera alerta de conectividad.<br><code>registerAppliesDefaultConnectionAndStatus</code>: registra el sensor en línea y en estado normal.</td><td style="text-align:center; vertical-align: top; padding:6px;">US16, US61</td></tr>
    <tr><td style="text-align:center; vertical-align: top; padding:6px;">AssetInventoryControllerTest</td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>AssetInventoryController</code></td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>createAssignsCompliantStatusByDefault</code>: registra el equipo con estado <i>compliant</i> y lo audita.<br><code>createKeepsTheStatusSentByTheClient</code>: conserva el estado enviado.<br><code>updateAuditsTheChangedEquipment</code>: actualiza el equipo y registra la auditoría.<br><code>deleteRemovesTheEquipmentAndNotifiesAWarning</code>: elimina el equipo y notifica el cambio.</td><td style="text-align:center; vertical-align: top; padding:6px;">US60</td></tr>
  </tbody>
</table>

<p align="center">
  <img src="../assets/09-chapter-4/testing-unit-tests-results.png" alt="Ejecución de los Unit Tests (22 tests aprobados)." width="100%">
</p>

<p align="center"><i>Figura: Ejecución de los Unit Tests (22 tests aprobados).</i></p>


##### **Integration Tests**

<p style="text-align: justify;">
  Los Integration Tests levantan el contexto completo de Spring Boot y consumen los endpoints de la RESTful API mediante MockMvc, verificando la interacción entre controladores, servicios y persistencia. Cada clase agrupa los escenarios de una User Story.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Test Class</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Endpoints evaluados</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Comportamientos verificados</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">User Story</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align:center; vertical-align: top; padding:6px;">MonitoringOrganizationIntegrationTest</td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>GET /api/v1/facilities</code><br><code>GET /api/v1/asset-inventory/assets</code><br><code>GET /api/v1/assets/{id}</code><br><code>POST /api/v1/asset-inventory/assets</code></td><td style="text-align: justify; vertical-align: top; padding:6px;">Lista los sitios de monitoreo registrados; lista todos los equipos; retorna un equipo por id; registra un nuevo equipo; responde 404 para un equipo inexistente y para un recurso no expuesto.</td><td style="text-align:center; vertical-align: top; padding:6px;">US60</td></tr>
    <tr><td style="text-align:center; vertical-align: top; padding:6px;">EnvironmentalMonitoringIntegrationTest</td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>GET /api/v1/sensors/{id}</code><br><code>GET /api/v1/sensor-monitoring/sensors</code></td><td style="text-align: justify; vertical-align: top; padding:6px;">Retorna la temperatura y la humedad del equipo; retorna el estado operativo de cada equipo (conexión y estado de lectura); responde 404 si el equipo de monitoreo no está registrado.</td><td style="text-align:center; vertical-align: top; padding:6px;">US61</td></tr>
    <tr><td style="text-align:center; vertical-align: top; padding:6px;">AutomaticDataCollectionIntegrationTest</td><td style="text-align: justify; vertical-align: top; padding:6px;"><code>PATCH /api/v1/sensor-monitoring/sensors/{id}/reading</code><br><code>POST /api/v1/sensor-monitoring/sensors/{id}/disconnect</code><br><code>GET /api/v1/alerts</code></td><td style="text-align: justify; vertical-align: top; padding:6px;">Registra automáticamente una nueva lectura asociada a su equipo; asocia lecturas de distintos equipos a cada uno; genera una alerta crítica ante una lectura fuera de rango; detecta que el equipo dejó de enviar datos; responde 404 si el sensor no existe.</td><td style="text-align:center; vertical-align: top; padding:6px;">US16</td></tr>
  </tbody>
</table>

<p align="center">
  <img src="../assets/09-chapter-4/testing-integration-tests-results.png" alt="Ejecución de los Integration Tests (15 tests aprobados)." width="100%">
</p>

<p align="center"><i>Figura: Ejecución de los Integration Tests (15 tests aprobados).</i></p>


##### **Acceptance Tests (BDD)**

<p style="text-align: justify;">
  Los Acceptance Tests se elaboraron bajo el enfoque BDD con Cucumber. Cada archivo <code>.feature</code> está escrito en lenguaje Gherkin a partir de los criterios de aceptación de la User Story correspondiente, y sus pasos se implementan en la clase de Steps <code>MonitoringApiSteps</code>, que ejecuta las solicitudes contra la RESTful API. La clase <code>CucumberAcceptanceTest</code> ejecuta los escenarios y <code>CucumberSpringConfiguration</code> inicia el contexto de Spring Boot para las pruebas.
</p>

<p style="text-align: justify;">
  <b>US60 - Proporcionar servicios de organización del monitoreo.</b> Verifica que la API proporcione las operaciones de sitios de monitoreo y de equipos, y que responda que el recurso no fue encontrado cuando este no existe. Archivo: <code>us60-monitoring-organization-services.feature</code>.
</p>

```gherkin
@US60
Feature: US60 - Provide monitoring organization services
  As a Developer
  I want the RESTful API to provide operations for monitoring sites, storage areas and equipment
  So that the SafeLab applications can use the monitoring organization information

  Scenario: Provide monitoring site operations
    Given the RESTful API has registered monitoring sites
    When a client requests the monitoring sites
    Then the service responds with status 200
    And the response contains the monitoring site "fac-central"

  Scenario: Provide equipment operations
    Given the equipment "asset-002" is registered
    When a client requests the equipment "asset-002"
    Then the service responds with status 200
    And the response field "name" is "PCR Reagent Rack"
    And the response field "facilityId" is "fac-central"

  Scenario: Non-existent monitoring organization resource
    Given the equipment "asset-999" is not registered
    When a client requests the equipment "asset-999"
    Then the service responds with status 404
```

<p style="text-align: justify;">
  <b>US61 - Proporcionar servicios de monitoreo ambiental.</b> Verifica que la API proporcione la temperatura, la humedad y el estado del equipo solicitado, y que responda que el equipo no fue encontrado cuando no está registrado. Archivo: <code>us61-environmental-monitoring-services.feature</code>.
</p>

```gherkin
@US61
Feature: US61 - Provide environmental monitoring services
  As a Developer
  I want the RESTful API to provide environmental monitoring data
  So that the SafeLab applications can consume temperature, humidity and equipment status information

  Scenario Outline: Provide temperature and humidity
    Given the sensor "<sensor>" is registered
    When a client requests the monitoring data of sensor "<sensor>"
    Then the service responds with status 200
    And the response field "type" is "<type>"
    And the response field "value" is "<value>"
    And the response field "assetId" is "<equipment>"

    Examples:
      | sensor  | type        | value | equipment |
      | sen-001 | temperature | 3.8   | asset-001 |
      | sen-002 | humidity    | 46    | asset-003 |

  Scenario: Provide equipment status
    Given the sensor "sen-009" is registered
    When a client requests the monitoring data of sensor "sen-009"
    Then the service responds with status 200
    And the response field "connection" is "offline"
    And the response field "status" is "invalid"

  Scenario: Non-existent monitoring equipment
    Given the sensor "sen-999" is not registered
    When a client requests the monitoring data of sensor "sen-999"
    Then the service responds with status 404
```

<p style="text-align: justify;">
  <b>US16 - Recolección automática de datos.</b> Verifica que una nueva lectura se registre automáticamente, que las lecturas de distintos equipos queden asociadas a su equipo correspondiente y que el sistema identifique cuando un equipo deja de proporcionar datos. Archivo: <code>us16-automatic-data-collection.feature</code>.
</p>

```gherkin
@US16
Feature: US16 - Automatic data collection
  As a hospital laboratory or pharmaceutical company staff member
  I want monitoring data to be collected automatically
  So that I do not have to register it manually

  Scenario: Automatically register a new reading
    Given the sensor "sen-001" is providing data
    When the system receives a reading of 5.2 for sensor "sen-001"
    Then the service responds with status 200
    And the response field "value" is "5.2"
    And the response field "status" is "normal"
    And the response field "assetId" is "asset-001"

  Scenario Outline: Register readings from different equipment
    Given the sensor "<sensor>" is providing data
    When the system receives a reading of <value> for sensor "<sensor>"
    Then the service responds with status 200
    And the response field "assetId" is "<equipment>"

    Examples:
      | sensor  | value | equipment |
      | sen-002 | 50.0  | asset-003 |
      | sen-005 | 4.5   | asset-005 |

  Scenario: Detect the absence of a new reading
    Given the sensor "sen-001" is providing data
    When the sensor "sen-001" stops providing data
    Then the service responds with status 200
    And the response field "connection" is "offline"
    And an alert of type "Connectivity" is registered for sensor "sen-001"
```

<p align="center">
  <img src="../assets/09-chapter-4/testing-acceptance-tests-results.png" alt="Ejecución de los Acceptance Tests BDD (11 escenarios aprobados)." width="100%">
</p>

<p align="center"><i>Figura: Ejecución de los Acceptance Tests BDD (11 escenarios aprobados).</i></p>

<p align="center">
  <img src="../assets/09-chapter-4/testing-cucumber-report.png" alt="Reporte de Cucumber con los escenarios de US16, US60 y US61." width="100%">
</p>

<p align="center"><i>Figura: Reporte de Cucumber con los escenarios de US16, US60 y US61.</i></p>


##### **Resultados**

<p style="text-align: justify;">
  La ejecución de la suite mediante <code>mvn test</code> finalizó con éxito: los 22 Unit Tests y los 15 Integration Tests se aprobaron sin fallos ni errores, y los 11 escenarios BDD de Cucumber se ejecutaron satisfactoriamente, según se muestra en el reporte de Cucumber. Con ello se valida el comportamiento de los Web Services asociados a las User Stories US16, US60 y US61 del Sprint 1.
</p>

<p align="center">
  <img src="../assets/09-chapter-4/testing-mvn-test-summary.png" alt="Resumen de la ejecución de la suite con Maven." width="100%">
</p>

<p align="center"><i>Figura: Resumen de la ejecución de la suite con Maven.</i></p>




#### **4.2.1.6. Execution Evidence for Sprint Review**
#### **4.2.1.7. Services Documentation Evidence for Sprint Review**
#### **4.2.1.8. Software Deployment Evidence for Sprint Review**
#### **4.2.1.9. Team Collaboration Insights during Sprint**
## **4.3. Validation Interviews**

<p style="text-align: justify;">
  En esta sección se registran y explican las entrevistas de validación, en las que usuarios de los dos segmentos objetivo interactúan con el Landing Page y la aplicación móvil de SafeLab para verificar si el producto les permite cumplir sus objetivos. La sección incluye el diseño de las sesiones, el registro de cada entrevista y la evaluación de los hallazgos según heurísticas de usabilidad, arquitectura de información y diseño inclusivo, siguiendo el formato de evaluación indicado para el proyecto.
</p>

### **4.3.1. Interview Design**
### **4.3.2. Interview Recording**
### **4.3.3. Evaluations Based on Heuristics**

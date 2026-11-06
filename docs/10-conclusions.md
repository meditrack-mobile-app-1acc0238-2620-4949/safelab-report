
# **Conclusions**

<div style="page-break-before: always;"></div>

## **Conclusions and Recommendations**

### **Conclusiones**

<ol style="text-align: justify; padding-left: 24px;">
  <li style="margin-bottom: 12px;">
    El proceso de investigación realizado durante la AV1 permitió identificar que los <b>Laboratorios de Hospitales</b> y las <b>Empresas Farmacéuticas</b> presentan dificultades relacionadas con el monitoreo manual de las condiciones de almacenamiento, la detección tardía de desviaciones de temperatura y humedad, y la consolidación de registros para auditorías. Estos hallazgos respaldan el <i>Problem Statement</i> planteado para SafeLab y justifican la necesidad de una solución que centralice el monitoreo ambiental.
  </li>
  <li style="margin-bottom: 12px;">
    Las entrevistas evidenciaron que los usuarios dependen principalmente de registros en papel, hojas de cálculo y <i>dataloggers</i> que requieren extracción manual. Esta situación genera pérdida de tiempo, información fragmentada y una capacidad limitada para responder oportunamente ante incidentes que puedan afectar medicamentos, reactivos y muestras biológicas.
  </li>
  <li style="margin-bottom: 12px;">
    Los supuestos formulados mediante <i>Lean UX</i> fueron contrastados inicialmente con las necesidades y experiencias de los segmentos objetivo. Los resultados permitieron identificar interés por una solución que centralice la información, facilite la consulta de condiciones ambientales, genere alertas oportunas y conserve registros confiables para los procesos de trazabilidad y auditoría.
  </li>
  <li style="margin-bottom: 12px;">
    La investigación permitió reconocer diferencias entre ambos segmentos. Los Laboratorios de Hospitales priorizan la simplicidad de uso, el funcionamiento ante una conectividad limitada y la escalación de alertas hacia los responsables. Por su parte, las Empresas Farmacéuticas requieren principalmente reportes regulatorios, integridad de los datos, trazabilidad histórica y mecanismos de mitigación frente a desviaciones críticas. Estas diferencias deben considerarse durante la implementación y validación de las funcionalidades de SafeLab.
  </li>
  <li style="margin-bottom: 12px;">
    Los artefactos de <i>Needfinding</i>, entre ellos <i>User Personas</i>, <i>User Task Matrix</i>, <i>User Journey Maps</i> y <i>Empathy Maps</i>, permitieron organizar los resultados de las entrevistas y representar las necesidades, frustraciones, tareas y expectativas de los usuarios. Asimismo, el <i>Impact Mapping</i> y las <i>User Stories</i> facilitaron la relación entre los objetivos del negocio y las funcionalidades propuestas, mientras que <i>Domain-Driven Design</i> permitió identificar los <i>Bounded Contexts</i> necesarios para organizar la solución.
  </li>
  <li style="margin-bottom: 12px;">
    La organización del <i>Product Backlog</i> permitió distribuir las 65 User Stories de SafeLab en cuatro Sprints, considerando sus prioridades, dependencias y estimaciones en Story Points. Esta planificación proporcionó una base para organizar el desarrollo incremental y mantener la trazabilidad entre los requisitos, las actividades y los entregables del proyecto.
  </li>
  <li style="margin-bottom: 12px;">
    Durante el primer incremento se desarrolló la estructura de navegación de la aplicación móvil y se implementaron pantallas correspondientes a siete <i>Bounded Contexts</i>, utilizando Kotlin, Jetpack Compose y datos locales de prueba. Paralelamente, se trabajó en la Landing Page y en los servicios RESTful del backend. La separación de estos productos permitió avanzar en sus funcionalidades de manera independiente, aunque la integración real entre la aplicación móvil y la API permanece como un aspecto que debe verificarse.
  </li>
  <li style="margin-bottom: 12px;">
    La planificación del Sprint 2 contempló 18 User Stories y 55 Story Points, con un alcance orientado a la configuración de límites ambientales, la gestión de alertas e incidentes, las notificaciones móviles y la consulta de información de sitios, áreas y equipos. La organización de estas funcionalidades permitió ampliar el alcance del monitoreo inicial y establecer las actividades necesarias para fortalecer la respuesta ante condiciones ambientales anormales.
  </li>
  <li style="margin-bottom: 12px;">
    Para la AV3, el Sprint 3 comprendió 16 User Stories y 57 Story Points, enfocándose en la visualización de datos históricos, la comparación de registros entre periodos, la generación y exportación de reportes y la consulta de indicadores y tendencias mediante el dashboard. Estas funcionalidades complementan el monitoreo ambiental al incorporar herramientas orientadas al análisis de la información y al seguimiento de las condiciones de almacenamiento a lo largo del tiempo.
  </li>
  <li style="margin-bottom: 12px;">
    La utilización de Git y GitHub, junto con la organización del código por <i>Bounded Contexts</i>, permitió mantener una estructura de trabajo adecuada para el desarrollo colaborativo. Asimismo, la documentación de los Sprints y el uso de Jira facilitaron la identificación de las User Stories, sus responsables y estimaciones. Sin embargo, resulta necesario mantener actualizados los estados de las actividades y contrastarlos con las funcionalidades y evidencias realmente disponibles.
  </li>
  <li style="margin-bottom: 12px;">
    Las pruebas documentadas para los servicios del primer Sprint constituyen un avance en la verificación técnica del backend. No obstante, la existencia de pantallas, servicios y actividades planificadas no demuestra por sí sola que todos los flujos de SafeLab funcionen de manera integrada. Por ello, las <i>Hypothesis Statements</i> y sus criterios de éxito requieren validaciones adicionales con los usuarios objetivo, así como pruebas funcionales que permitan comprobar el comportamiento de la solución en escenarios representativos.
  </li>
</ol>

### **Recomendaciones**

<ol style="text-align: justify; padding-left: 24px;">
  <li style="margin-bottom: 12px;">
    Continuar el desarrollo y la validación progresiva del <i>Minimum Viable Product</i> de SafeLab, priorizando la integración de las funcionalidades de monitoreo ambiental, gestión de alertas, consulta histórica y generación de reportes. Se recomienda comprobar que los flujos principales funcionen de manera conjunta antes de ampliar el alcance de la solución.
  </li>
  <li style="margin-bottom: 12px;">
    Realizar entrevistas y pruebas de usabilidad adicionales con representantes de Laboratorios de Hospitales y Empresas Farmacéuticas para evaluar las funcionalidades incorporadas durante los Sprints. Estas sesiones deben permitir comprobar las <i>Hypothesis Statements</i>, identificar dificultades de interacción y determinar si las características desarrolladas responden a las necesidades identificadas durante la investigación inicial.
  </li>
  <li style="margin-bottom: 12px;">
    Verificar la integración entre la aplicación móvil y SafeLab Platform API, reemplazando progresivamente los datos locales de prueba por información obtenida mediante servicios RESTful. Durante este proceso se recomienda validar las respuestas de los endpoints, el manejo de errores, la disponibilidad de los servicios y la consistencia de los datos mostrados en las pantallas.
  </li>
  <li style="margin-bottom: 12px;">
    Fortalecer la validación de las funcionalidades relacionadas con alertas e incidentes, comprobando la configuración de límites de temperatura y humedad, la clasificación por severidad, la confirmación de atención y la recepción de notificaciones móviles. También se recomienda evaluar el comportamiento del sistema cuando un sensor deja de enviar información o se produce una desviación crítica.
  </li>
  <li style="margin-bottom: 12px;">
    Incorporar pruebas específicas para las funcionalidades de consulta histórica, comparación de periodos, generación de reportes y visualización de tendencias correspondientes al Sprint 3. Estas pruebas deben verificar que los filtros por fecha y equipo produzcan resultados correctos, que los indicadores reflejen la información disponible y que los archivos descargados o exportados conserven la integridad de los registros.
  </li>
  <li style="margin-bottom: 12px;">
    Mantener actualizados el <i>Product Backlog</i>, los Sprint Backlogs y los estados de las User Stories en Jira, verificando su correspondencia con las implementaciones realizadas y las evidencias documentadas. Asimismo, se recomienda conservar la planificación de los cuatro Sprints y registrar las modificaciones de alcance o estimación cuando sean acordadas por el equipo.
  </li>
  <li style="margin-bottom: 12px;">
    Revisar periódicamente la arquitectura de la solución, los <i>Bounded Contexts</i>, la documentación técnica y las convenciones de los repositorios para asegurar que continúen reflejando la implementación real. También se recomienda mantener una estrategia de integración mediante ramas de desarrollo, revisiones de código y pruebas antes de consolidar nuevas versiones.
  </li>
  <li style="margin-bottom: 12px;">
    Evaluar los requisitos regulatorios aplicables al almacenamiento y trazabilidad de medicamentos, reactivos y muestras biológicas, considerando las disposiciones pertinentes de DIGEMID, DIGESA y DIRESA, así como la norma ISO 15189 y los principios ALCOA+. Esta revisión debe orientar la validación de los módulos de reportes, auditoría, conservación e integridad de datos antes de su utilización en entornos reales.
  </li>
  <li style="margin-bottom: 12px;">
    Considerar en el <i>Roadmap</i> mecanismos de funcionamiento ante conectividad limitada, respaldo energético, calibración de sensores, escalación de alertas y recuperación de información. Estos aspectos deben evaluarse de acuerdo con las necesidades de cada segmento objetivo, debido a su importancia para la continuidad del monitoreo y la confiabilidad de los registros.
  </li>
  <li style="margin-bottom: 12px;">
    Mantener la trazabilidad entre los hallazgos de las entrevistas, los artefactos de <i>Needfinding</i>, los requisitos funcionales, los criterios de aceptación y las funcionalidades implementadas. Para las próximas entregas se recomienda incorporar evidencias reales de ejecución, pruebas y validación que permitan distinguir claramente los resultados alcanzados de las actividades que continúan en desarrollo.
  </li>
</ol>

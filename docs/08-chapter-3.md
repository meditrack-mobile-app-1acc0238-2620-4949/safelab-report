# **Chapter III: Solution UI/UX Design**
## **3.1. Product design**
### **3.1.1. Style Guidelines**
#### **3.1.1.1. General Style Guidelines**
### **3.1.2. Information Architecture**
#### **3.1.2.1. Organization Systems**
#### **3.1.2.2. Labeling Systems**
#### **3.1.2.3. SEO Tags and Meta Tags**
#### **3.1.2.4. Searching Systems**

<p style="text-align: justify;">
  Los sistemas de búsqueda de SafeLab buscan que el personal de laboratorios hospitalarios y de empresas farmacéuticas encuentre rápidamente un equipo, una alerta o un registro histórico, aun cuando la cantidad de sitios, áreas, equipos y lecturas aumente con el uso del sistema. Las decisiones se basan en las User Stories de la sección 2.4.1 y en lo señalado en las entrevistas de la sección 2.2: los usuarios necesitan identificar qué equipo presenta un problema sin recorrer físicamente las instalaciones y revisar lo ocurrido en fechas anteriores sin buscar en distintos archivos.
</p>

<p style="text-align: justify;">
  El Landing Page no incorpora un buscador interno, ya que es una página informativa con contenido breve; el visitante accede a cada sección mediante la navegación descrita en la sección 3.1.2.5. En las aplicaciones móviles, la búsqueda se organiza por módulo. La siguiente tabla especifica las opciones de búsqueda, los filtros disponibles y la forma en que se presentan los resultados en cada caso.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Módulo</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Opción de búsqueda</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Filtros disponibles</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Presentación de los resultados</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">User Stories</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Equipos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Búsqueda por nombre del equipo mediante un campo de texto que muestra coincidencias parciales mientras el usuario escribe.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Sitio de monitoreo, área de almacenamiento, estado operativo, equipos sin datos recientes y equipos con alertas activas.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Lista de equipos en la que se muestran primero los que tienen alertas activas. Cada elemento indica el nombre, el área, la temperatura y la humedad actuales, el estado operativo y la hora de la última lectura.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US08, US11, US13, US14, US15, US46</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Alertas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Consulta de alertas mediante filtros rápidos.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Severidad (crítica o advertencia), variable (temperatura o humedad), estado (pendiente o atendida) y equipo.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Lista ordenada por severidad y, luego, por fecha más reciente. Cada alerta muestra la severidad, el equipo, el valor registrado frente al límite permitido, la fecha, la hora y el estado.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US18, US19, US20, US22, US23, US44</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Historial de lecturas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Selección de un equipo y de un rango de fechas, con accesos rápidos para el día actual, los últimos 7 días y los últimos 30 días.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Variable (temperatura o humedad) y valores fuera de rango.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Gráfico de la evolución de la variable en el tiempo, acompañado de una lista de lecturas con fecha y hora en la que se resaltan los valores fuera de rango.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US27, US28, US36</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Reportes</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Selección del equipo y del rango de fechas que se desea reportar.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Equipo y rango de fechas.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Vista previa del reporte con las opciones de descargarlo y exportar los datos.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US30, US31, US33</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Incidentes y mantenimiento</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Consulta del historial de un equipo.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Rango de fechas.</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Lista cronológica, de lo más reciente a lo más antiguo, con la fecha, la descripción del evento y el responsable del registro.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US32, US41</td></tr>
  </tbody>
</table>

<p style="text-align: justify;">
  Además, todas las búsquedas de las aplicaciones siguen los siguientes criterios:
</p>

- **Búsqueda tolerante:** las coincidencias no distinguen mayúsculas, minúsculas ni tildes, y se consideran coincidencias parciales.
- **Filtros visibles:** los filtros activos se muestran sobre la lista de resultados, junto con la cantidad de resultados obtenidos y una opción para limpiarlos.
- **Resultados vacíos:** cuando no existen coincidencias, se muestra un mensaje que lo indica y se sugiere revisar el texto ingresado o quitar filtros.
- **Contexto conservado:** al abrir un resultado y regresar a la lista, se mantienen el texto de búsqueda, los filtros aplicados y la posición en la lista.
- **Información sin conexión:** cuando no hay conexión, la búsqueda se realiza sobre la última información sincronizada en el dispositivo y se indica la fecha y hora de la última actualización (US65).
- **Accesibilidad:** el campo de búsqueda y los filtros cuentan con etiquetas descriptivas para lectores de pantalla, y el estado de cada equipo o alerta se comunica con texto además del color.

#### **3.1.2.5. Navigation Systems**

<p style="text-align: justify;">
  Los sistemas de navegación de SafeLab definen cómo los visitantes y usuarios recorren el Landing Page y las aplicaciones móviles para cumplir sus objetivos. Se consideró que el personal de laboratorios hospitalarios utiliza principalmente el celular durante sus rondas y que el personal de empresas farmacéuticas necesita pasar rápidamente de una vista general a la zona o equipo que presenta un problema.
</p>

##### **Landing Page**

- **Navegación global:** barra superior fija con el logotipo de SafeLab, que regresa al inicio de la página, y enlaces que desplazan al visitante hacia cada sección. En navegadores móviles, estos enlaces se agrupan en un menú desplegable.
- **Cambio de idioma:** selector ubicado en la barra superior que permite cambiar entre inglés y español sin perder la sección en la que se encuentra el visitante (US57).
- **Navegación secuencial:** el contenido se organiza en un recorrido vertical que lleva al visitante desde el problema que resuelve SafeLab hasta su propuesta de valor y la forma de comenzar a utilizarlo.
- **Llamadas a la acción:** botones ubicados en las secciones principales que guían al visitante hacia el siguiente paso, como conocer las aplicaciones o contactar al equipo.
- **Pie de página:** enlaces a los Términos y Condiciones del servicio (US58), a la información de contacto y a las redes sociales.

##### **Aplicaciones móviles**

<p style="text-align: justify;">
  La aplicación nativa y la aplicación multiplataforma comparten el mismo esquema de navegación. La navegación global se resuelve mediante una barra inferior con cinco destinos principales, visibles desde cualquier pantalla principal. Cada destino agrupa las funcionalidades de uno o más Bounded Contexts definidos en la sección 2.5.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Destino</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Contenido</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Bounded Context</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Dashboard</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Resumen general del monitoreo, alertas críticas y equipos con alertas activas.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Dashboard & Overview</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Equipos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Sitios de monitoreo, áreas de almacenamiento y equipos con sus lecturas actuales y su estado.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Monitoring Organization, Sensor Monitoring, Equipment Condition & Maintenance</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Alertas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Lista y detalle de las alertas generadas, y confirmación de su atención.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alerts & Incident Management</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Reportes</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Historial de lecturas, historial de incidentes, generación de reportes y exportación de datos.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Reporting & Compliance</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">Perfil</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Datos del usuario, gestión de roles y cierre de sesión.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Identity & Access Management</td></tr>
  </tbody>
</table>

<p style="text-align: justify;">
  Adicionalmente, las aplicaciones aplican las siguientes técnicas de navegación:
</p>

- **Indicador de alertas pendientes:** el destino de alertas muestra un contador con la cantidad de alertas que aún no han sido atendidas.
- **Navegación jerárquica:** el usuario avanza de lo general a lo específico, de sitio de monitoreo a área de almacenamiento, de área a equipo y de equipo a su detalle. La barra superior muestra el título de la pantalla y un botón para regresar al nivel anterior.
- **Navegación contextual:** las tarjetas del dashboard llevan a listas ya filtradas, como los equipos con alertas activas, y desde una alerta se puede acceder al detalle del equipo afectado.
- **Acceso desde notificaciones:** al tocar una notificación, la aplicación abre directamente el detalle de la alerta, con la opción de confirmar su atención; al regresar, se muestra la lista de alertas (US22, US24).
- **Flujos paso a paso:** los registros de sitios, áreas, equipos, límites de alerta y mantenimientos se presentan como formularios secuenciales, con la opción de cancelar y volver a la pantalla de origen (US01, US03, US05, US07, US25, US40).
- **Navegación según el rol:** las opciones de administración, como registrar sitios o equipos y asignar roles, solo se muestran a los usuarios con permisos de supervisión (US55).
- **Inicio y cierre de sesión:** después de autenticarse, el usuario llega directamente al dashboard (US51, US52); el cierre de sesión se encuentra en el perfil (US54).
- **Retroceso del dispositivo:** el botón de retroceso del sistema operativo respeta la misma jerarquía de navegación de la aplicación.


### **3.1.3. Landing Page UI Design**
#### **3.1.3.1. Landing Page Wireframe**
#### **3.1.3.2. Landing Page Mockup**
### **3.1.4. Mobile Applications UX/UI Design**

<p style="text-align: justify;">
  En esta sección se presenta el diseño de experiencia e interfaz de las aplicaciones móviles de SafeLab. El diseño parte de las funcionalidades de la aplicación web y las adapta al contexto móvil: se priorizan las tareas que el personal realiza durante sus rondas en el laboratorio, como atender alertas, revisar lecturas en tiempo real, reportar incidentes y consultar el estado de un equipo. Las pantallas se diseñaron para Android siguiendo la estructura de Material Design 3 y la guía de estilos definida en la sección 3.1.1.
</p>

#### **3.1.4.1. Mobile Applications Wireframes**
<p style="text-align: justify;">
  Los wireframes definen la estructura y la jerarquía de contenido de cada pantalla en baja fidelidad, sin colores de marca, para validar la organización antes del diseño visual. Las tablas de la aplicación web se transformaron en listas de tarjetas, la barra lateral en una barra de navegación inferior y los modales en bottom sheets. Además, se incluyeron desde esta etapa el uso de recursos del dispositivo, como la cámara para escanear códigos QR y adjuntar evidencias, y la autenticación biométrica, así como el guardado local de reportes cuando no hay conexión.
</p>

![Mobile Applications Wireframes 1](assets/08-chapter-3/wireframes/wireframe1.png)

![Mobile Applications Wireframes 2](assets/08-chapter-3/wireframes/wireframe2.png)

![Mobile Applications Wireframes 3](assets/08-chapter-3/wireframes/wireframe3.png)

#### **3.1.4.2. Mobile Applications Wireflow Diagrams**
<p style="text-align: justify;">
  Los wireflows muestran cómo cambian las pantallas a partir de las interacciones del usuario. Se elaboró un wireflow por cada user goal; en cada flecha se indica la acción que realiza el usuario para pasar a la siguiente pantalla.
</p>

<p style="text-align: justify;">
  <b>User goal 1:</b> Como técnico de laboratorio, quiero iniciar sesión de forma rápida y segura para acceder al monitoreo del laboratorio. El usuario ingresa sus credenciales o utiliza su huella digital y, al autenticarse, llega directamente al dashboard.
</p>

![Wireflow 1](assets/08-chapter-3/wireflows/wireflow1.png)

<p style="text-align: justify;">
  <b>User goal 2:</b> Como técnico de laboratorio, quiero atender una alerta crítica y actuar sobre el equipo afectado para proteger las muestras. Desde la lista de alertas abre el detalle, compara el valor registrado con el rango permitido y pasa al control remoto, donde confirma el comando mediante un bottom sheet que muestra el resultado de la validación de seguridad.
</p>

![Wireflow 2](assets/08-chapter-3/wireflows/wireflow2.png)

<p style="text-align: justify;">
  <b>User goal 3:</b> Como técnico de laboratorio, quiero reportar un incidente con evidencia fotográfica para dejar trazabilidad de la desviación. Desde el detalle de la alerta crea el incidente, adjunta fotografías con la cámara y lo envía; el nuevo incidente aparece en la lista de incidentes abiertos.
</p>

![Wireflow 3](assets/08-chapter-3/wireflows/wireflow3.png)

<p style="text-align: justify;">
  <b>User goal 4:</b> Como técnico de laboratorio, quiero identificar un equipo escaneando su código QR para ver su estado sin buscarlo manualmente. Desde los accesos rápidos abre la cámara, el código se reconoce automáticamente y se muestra la ficha del equipo, desde donde accede a las lecturas de su sensor.
</p>

![Wireflow 4](assets/08-chapter-3/wireflows/wireflow4.png)

<p style="text-align: justify;">
  <b>User goal 5:</b> Como jefa de laboratorio, quiero revisar las lecturas en tiempo real de un sensor para verificar que se mantiene dentro del rango permitido. Desde el dashboard abre las lecturas en vivo, filtra por tipo de sensor y entra al detalle, donde revisa la tendencia y las estadísticas del periodo.
</p>

![Wireflow 5](assets/08-chapter-3/wireflows/wireflow5.png)
#### **3.1.4.3. Mobile Applications Mock-ups**
<p style="text-align: justify;">
  Los mock-ups presentan el diseño en alta fidelidad de las pantallas, aplicando la guía de estilos de SafeLab: color primario #4F35E8, color de acento #14B8A6, fondos #F4F7FB y la tipografía Inter. Los estados de severidad (crítico, advertencia, normal e informativo) usan colores semánticos y siempre se acompañan de una etiqueta de texto, para no depender únicamente del color. Los textos de la interfaz están en inglés, idioma por defecto de la aplicación.
</p>

![Mobile Applications Mock-ups 1](assets/08-chapter-3/mockups/mockup1.png)

![Mobile Applications Mock-ups 2](assets/08-chapter-3/mockups/mockup2.png)

![Mobile Applications Mock-ups 3](assets/08-chapter-3/mockups/mockup3.png)

#### **3.1.4.4. Mobile Applications User Flow Diagrams**
<p style="text-align: justify;">
  Los user flows representan el recorrido completo que sigue el usuario para cumplir cada user goal, utilizando los mock-ups. En cada diagrama se distingue el happy path (línea verde continua), en el que el usuario completa su objetivo sin inconvenientes, de los unhappy paths (línea roja discontinua), que muestran cómo responde la aplicación ante errores o situaciones alternativas. Los rombos representan los puntos de decisión.
</p>

<p style="text-align: justify;">
  <b>User goal 1:</b> Como técnico de laboratorio, quiero iniciar sesión de forma rápida y segura para acceder al monitoreo del laboratorio. En el happy path, las credenciales son válidas y el usuario llega al dashboard. En el unhappy path, las credenciales son incorrectas: la aplicación muestra un mensaje de error junto al formulario, conserva el correo ingresado y el usuario vuelve a intentarlo.
</p>

![User Flow 1](assets/08-chapter-3/userflows/userflow1.png)

<p style="text-align: justify;">
  <b>User goal 2:</b> Como técnico de laboratorio, quiero atender una alerta crítica y actuar sobre el equipo afectado para proteger las muestras. En el happy path, la validación de seguridad aprueba el comando y el estado del equipo se actualiza. En el unhappy path, el comando es bloqueado (por ejemplo, porque la puerta del equipo está abierta); la aplicación muestra el motivo y el usuario registra un incidente.
</p>

![User Flow 2](assets/08-chapter-3/userflows/userflow2.png)

<p style="text-align: justify;">
  <b>User goal 3:</b> Como técnico de laboratorio, quiero reportar un incidente con evidencia fotográfica para dejar trazabilidad de la desviación. En el happy path, el formulario está completo, el dispositivo tiene conexión y el incidente queda registrado. Se contemplan dos unhappy paths: si faltan campos obligatorios, se muestran errores de validación junto a cada campo; si no hay conexión, el reporte se guarda en el dispositivo y se envía automáticamente al recuperarla.
</p>

![User Flow 3](assets/08-chapter-3/userflows/userflow3.png)

<p style="text-align: justify;">
  <b>User goal 4:</b> Como técnico de laboratorio, quiero identificar un equipo escaneando su código QR para ver su estado sin buscarlo manualmente. En el happy path, el código se reconoce y se abre la ficha del equipo. En el unhappy path, el código no es legible y el usuario ingresa manualmente el código del equipo para llegar a la misma ficha.
</p>

![User Flow 4](assets/08-chapter-3/userflows/userflow4.png)

<p style="text-align: justify;">
  <b>User goal 5:</b> Como jefa de laboratorio, quiero revisar las lecturas en tiempo real de un sensor para verificar que se mantiene dentro del rango permitido. En el happy path, el valor se encuentra dentro del rango y el monitoreo continúa. En el unhappy path, el valor está fuera del rango y la aplicación lleva al detalle de la alerta generada, desde donde continúa el flujo del user goal 2.
</p>

![User Flow 5](assets/08-chapter-3/userflows/userflow5.png)
#### **3.1.4.5. Mobile Applications Prototyping**

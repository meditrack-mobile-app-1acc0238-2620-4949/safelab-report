# **Chapter II: Requirements Development and Software Solution Design**

## **2.1. Competitors**

### **2.1.1. Competitive Analysis**

<p style="text-align: justify;">
  <b>¿Por qué realizar este análisis?</b>
</p>

<p style="text-align: justify;">
  Identificar las barreras de entrada, tanto tecnológicas como económicas, impuestas por los líderes globales de monitoreo IoT, con el fin de validar la existencia de un nicho desatendido en instituciones de salud medianas y pequeñas. Este análisis permitirá posicionar a SafeLab como una alternativa ágil, clínicamente específica y económicamente accesible.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Atributo</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">SafeLab</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">SmartSense</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">SenseAnywhere</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Monnit</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Descripción general</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Startup B2B SaaS enfocada en erradicar el desperdicio biológico mediante automatización ágil y accesible.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Plataforma IoT corporativa de alto nivel para trazabilidad y cumplimiento normativo en redes hospitalarias y farmacéuticas.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Sistema europeo de monitoreo en la nube enfocado en hardware de alta durabilidad y logística de cadena de frío.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Proveedor global de soluciones de monitoreo remoto con sensores inalámbricos para múltiples industrias.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Ventaja competitiva</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Plataforma agnóstica de hardware, altamente contextualizada al flujo de trabajo de los biólogos.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Capacidad de escala masiva e integración con sistemas ERP y estricto cumplimiento regulatorio (FDA).</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Fiabilidad extrema del hardware y registro ininterrumpido en la nube sin mantenimiento local.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Accesibilidad económica inicial y alta personalización para monitorear múltiples variables.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Mercado objetivo</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Laboratorios clínicos y farmacias hospitalarias en ciudades emergentes o periféricas.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Grandes hospitales, cadenas farmacéuticas nacionales y logística farmacéutica global.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Almacenes de alta tecnología, laboratorios farmacéuticos y empresas de transporte logístico.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Pequeñas y medianas empresas (PYMES) de agricultura, TI, alimentos, clínicas y otros sectores.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Estrategias de marketing</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Marketing de atracción (inbound) enfocado en la cultura de cero residuos y la simplificación de auditorías de calidad locales.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Ventas corporativas B2B enfocadas en el retorno de inversión (ROI) mediante mitigación de riesgos legales.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Presencia en ferias comerciales farmacéuticas globales.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Marketing digital masivo, comercio electrónico directo y posicionamiento en motores de búsqueda a bajo costo.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Productos y servicios</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Aplicación web SPA e integración de API con hardware genérico y asequible de terceros.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Software empresarial, gateways y sensores IoT propietarios.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">SenseAnywhere Cloud y AiroSensors, bajo un modelo de hardware propietario cerrado.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Plataforma iMonnit y sensores inalámbricos ALTA.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Precios y costos</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Bajo. Modelo SaaS puro con pagos mensuales o anuales, permitiendo la reutilización de equipos genéricos.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Muy alto. Contratos corporativos anuales que incluyen hardware costoso e instalación.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Medio-Alto. Depende de sensores europeos especializados importados.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Bajo-Medio. Hardware asequible y suscripciones mensuales o anuales por niveles.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Canales de distribución</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Ventas directas B2B y autorregistro (self-onboarding).</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Ventas corporativas directas. Plataforma web y aplicación móvil.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Red de distribuidores oficiales. Plataforma web SaaS.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Tienda en línea propia y distribuidores. Plataforma web y móvil.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Fortalezas</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Alta agilidad para pivotar, bajo costo estructural e interfaz diseñada específicamente para el usuario clínico.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Fuerte reputación de marca y certificaciones internacionales.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Hardware líder en el mercado, con hasta diez años sin necesidad de carga, y software altamente estable.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Amplio catálogo de sensores e interfaz altamente personalizable.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Oportunidades</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Gran mercado de laboratorios medianos que aún utilizan procesos en papel porque no pueden costear a los competidores principales.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Absorción de competidores más pequeños y contratos gubernamentales.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Expansión en mercados emergentes y mejora en la integración de API.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Crecimiento constante en la digitalización pospandemia de clínicas medianas.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Debilidades</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Falta de hardware propietario y de reconocimiento de marca en la etapa inicial.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Inaccesible para clínicas pequeñas y requiere procesos de implementación corporativa lentos.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Modelo de hardware cerrado; si un sensor se daña, debe importarse otro del fabricante.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Plataforma demasiado genérica y no diseñada específicamente para flujos de trabajo del sector salud.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;"><b>Amenazas</b></td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Desconfianza inicial del sector salud hacia nuevas plataformas o ingreso de una gran empresa tecnológica al mercado de bajo costo.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Aparición de startups ágiles y asequibles en mercados locales.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Problemas en las cadenas globales de suministro de microchips que aumenten los costos de hardware.</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Soluciones especializadas que capten clientes del sector salud mediante interfaces más específicas.</td>
    </tr>
  </tbody>
</table>

### **2.1.2. Strategies and Tactics Against Competitors**

#### **Estrategias ofensivas**

<p style="text-align: justify;">
  <b>Penetración mediante hiper-especialización y bajo costo.</b> Al cruzar nuestra fortaleza de contar con una arquitectura de software agnóstica, sin hardware propietario, con el mercado desatendido en ciudades de menos de 250 000 habitantes, nuestra táctica principal será ofrecer un modelo SaaS enfocado en el flujo de trabajo clínico. Mientras los competidores obligan a adquirir paquetes de sensores cerrados y costosos, SafeLab permitirá a los laboratorios medianos digitalizar sus procesos utilizando sensores locales genéricos, democratizando el acceso a tecnología de calidad y facilitando la entrada a este nicho.
</p>

#### **Estrategias adaptativas**

<p style="text-align: justify;">
  <b>Alianzas estratégicas de distribución B2B.</b> Para contrarrestar nuestra principal debilidad, asociada a la falta de hardware propietario y al bajo reconocimiento de marca inicial, se aprovechará la creciente necesidad de digitalización mediante alianzas con distribuidores locales de refrigeradores médicos y proveedores de sensores IoT genéricos. SafeLab se ofrecerá como un valor agregado de software dentro de sus ventas, permitiendo llegar al cliente final a través de canales que ya cuentan con su confianza y reduciendo el costo de adquisición.
</p>

#### **Estrategias defensivas**

<p style="text-align: justify;">
  <b>Diferenciación mediante usabilidad clínica (self-onboarding).</b> Frente a la desconfianza del sector salud hacia nuevas tecnologías o a la posible entrada de grandes empresas tecnológicas con soluciones de bajo costo, se aprovechará la agilidad y el diseño centrado en el usuario clínico. La táctica consiste en construir un flujo de incorporación Plug & Play y una interfaz con dashboard y reportes adaptados al contexto de auditorías locales, como ISO 15189, de modo que una plataforma genérica resulte menos adecuada para las necesidades específicas de los usuarios clínicos.
</p>

#### **Estrategias de supervivencia**

<p style="text-align: justify;">
  <b>Validación temprana y cumplimiento normativo estricto.</b> La combinación de ser una marca nueva en un sector altamente regulado representa uno de los principales riesgos para la startup. Para reducir esta barrera, el software se diseñará considerando los formatos requeridos por las entidades regulatorias de salud. Asimismo, se implementarán programas piloto en laboratorios de ciudades secundarias para generar casos de éxito verificables y métricas de ROI, de manera que la falta de reputación inicial pueda compensarse con evidencia obtenida durante la validación.
</p>

## **2.2. Interviews**

### **2.2.1. Interview Design**

#### **Segmento 1: Laboratorios de Hospitales**

1. ¿Podrías contarnos tu nombre, edad, estado civil y el distrito donde vives?
2. Cuéntanos un poco sobre ti y qué sueles hacer en tu tiempo libre. ¿Cómo te describirías en tres palabras?
3. ¿Cuál es tu puesto actual en el laboratorio y cuántos años de experiencia tienes en este rol?
4. En tu día a día, ¿qué dispositivos tecnológicos usas más, y qué sistema operativo y navegador prefieres?
5. ¿Cómo es actualmente el proceso de monitoreo y control de muestras, reactivos e insumos en tu laboratorio, en el día a día?
6. ¿Cuánto tiempo estimas que dedican a registrar estos datos y a consolidar la información en reportes?
7. Cuéntame sobre la última vez que tuvieron un incidente crítico, como una desviación de temperatura, un corte de luz o pérdida de reactivos.
8. ¿Qué es lo que más te frustra o estresa de esta parte de tu trabajo actualmente?
9. Si existiera un sistema ideal para resolver estos problemas, ¿cómo sería?
10. Si un sistema detectara que una refrigeradora o congeladora está fallando, ¿preferirías solo recibir una notificación, o que el sistema intente una acción de contingencia automática?
11. Para que confíes al 100% en un sistema así, ¿qué información o garantías necesitarías que te muestre?
12. ¿Hay algo más sobre tu trabajo con muestras e insumos sensibles que consideres importante mencionar?

#### **Segmento 2: Empresas Farmacéuticas**

1. ¿Podrías contarnos tu nombre, edad, estado civil y el distrito donde vives?
2. Cuéntanos un poco sobre ti y qué sueles hacer en tu tiempo libre. ¿Cómo te describirías en tres palabras?
3. ¿Cuál es tu puesto actual dentro de la empresa y cuántos años de experiencia tienes en roles de almacenamiento, calidad o logística?
4. En tu día a día, ¿qué dispositivos tecnológicos usas más, y qué sistema operativo y navegador prefieres?
5. ¿Cómo es actualmente el proceso de monitoreo de condiciones de almacenamiento de medicamentos, incluyendo trazabilidad y registros para auditoría?
6. ¿Cuánto tiempo estima tu equipo que dedica a consolidar los registros ambientales y preparar documentación para auditorías regulatorias?
7. Cuéntame sobre la última vez que tuvieron un incidente crítico, como una excursión de temperatura durante el almacenamiento o transporte que puso en riesgo un lote.
8. ¿Qué es lo que más te frustra o estresa de mantener la trazabilidad y el cumplimiento normativo actualmente?
9. Si existiera un sistema ideal para resolver estos problemas, ¿cómo sería?
10. Si un sistema detectara una desviación en una sala de almacenamiento o durante el transporte, ¿preferirías solo recibir una notificación, o que el sistema también active una acción de mitigación automática?
11. Para que confíes al 100% en un sistema así para auditorías regulatorias, ¿qué información o garantías necesitarías que te muestre?
12. ¿Hay algo más sobre trazabilidad, cumplimiento o monitoreo de la cadena de suministro que consideres importante mencionar?

### **2.2.2. Interview Recording**

<p style="text-align: justify;">
  Para recopilar información cualitativa de ambos segmentos objetivo, se realizaron entrevistas que fueron consolidadas en el enlace mostrado a continuación, siguiendo el formato y la estructura definidos para esta sección.
</p>

<p style="text-align: justify;">
  <b>Enlace:</b> <a href="https://youtu.be/5nNHZnFrHPo">https://youtu.be/5nNHZnFrHPo</a>
</p>

#### **Segmento 1: Laboratorios de Hospitales**

##### **Entrevista 1: Rosa Elena Campos Idme**

<p style="text-align: justify;">
  <b>Fecha:</b> 3 de septiembre de 2026<br>
  <b>Inicia en:</b> 00:00<br>
  <b>Duración:</b> 06:06
</p>

<p align="center">
  <img src="../assets/07-chapter-2/interviews/interview-recording/interview-1.jpeg" alt="Evidencia de la entrevista 1 - Rosa Elena Campos Idme" width="80%">
</p>

<p style="text-align: justify;">
  Rosa Elena Campos Idme tiene 34 años, es casada y vive en el Cercado de Arequipa. Es bióloga y trabaja como Jefa del Laboratorio Clínico en un hospital de nivel II, donde supervisa el banco de sangre, los reactivos y los insumos sensibles. Se describe como meticulosa, responsable y tranquila bajo presión.
</p>

<p style="text-align: justify;">
  Su proceso de monitoreo consiste en revisar manualmente tres refrigeradoras y dos congeladoras, tres veces por turno, utilizando un termómetro digital independiente y registrando cada lectura en una hoja de papel que posteriormente se transcribe a Excel al final del día, lo cual toma aproximadamente diez minutos por revisión. Recuerda un incidente crítico en el que la puerta de una congeladora quedó mal cerrada durante la noche, provocando una subida de seis grados que dañó un lote de reactivos valorizado en varios miles de soles y que fue descubierto recién a la mañana siguiente. Lo que más le frustra es que los registros en papel se pierden o se dañan y son difíciles de correlacionar históricamente, sobre todo cuando las auditorías de DIGESA/DIRESA exigen carpetas completas de registros físicos.
</p>

<p style="text-align: justify;">
  Le gustaría contar con un sistema automatizado con alertas en tiempo real al celular y un registro de auditoría digital y exportable. Prefiere que el sistema le notifique de inmediato e incluya una acción recomendada para muestras críticas, en lugar de actuar de forma autónoma, aunque aceptaría ajustes automáticos menores para parámetros no críticos, como la humedad. Para confiar plenamente en el sistema, necesitaría evidencia de la calibración de los sensores, redundancia de energía de respaldo y cumplimiento de la normativa de salud local.
</p>

##### **Entrevista 2: Diego Armando Salazar Ttito**

<p style="text-align: justify;">
  <b>Fecha:</b> 2 de septiembre de 2026<br>
  <b>Inicia en:</b> <a href="https://youtu.be/5nNHZnFrHPo?si=b9f9cZEKH0qweBCt&t=366">06:06</a><br>
  <b>Duración:</b> 03:25
</p>

<p align="center">
  <img src="../assets/07-chapter-2/interviews/interview-recording/interview-2.jpeg" alt="Evidencia de la entrevista 2 - Diego Armando Salazar Ttito" width="80%">
</p>

<p style="text-align: justify;">
  Diego Armando Salazar Ttito tiene 27 años, es soltero y vive en Yanahuara, Arequipa. Trabaja como técnico de laboratorio en el turno noche del mismo hospital y se describe como responsable, tranquilo y algo «búho nocturno».
</p>

<p style="text-align: justify;">
  Su rutina consiste en revisar los equipos de cadena de frío cada cuatro horas en dos pisos distintos, registrando los resultados en una hoja con papel carbón. Al ser el único técnico de guardia durante la noche, en una ocasión omitió una ronda programada debido al exceso de carga de trabajo y una desviación de temperatura no fue detectada hasta la llegada del turno siguiente. Lo que más le frustra es la falta de personal durante la noche y no contar con respaldo o retroalimentación si ocurre un problema mientras está solo.
</p>

<p style="text-align: justify;">
  Su sistema ideal sería una aplicación móvil sencilla que le recuerde cuándo corresponden las rondas y le permita registrar la información con una sola acción, incorporando una escalación automática hacia un supervisor de guardia si no responde dentro de un tiempo determinado. Confiaría en un sistema que funcione de forma confiable incluso cuando el Wi-Fi del hospital sea inestable y que ofrezca un modo offline como respaldo.
</p>

#### **Segmento 2: Empresas Farmacéuticas**

##### **Entrevista 3: Camilo Paredes**

<p style="text-align: justify;">
  <b>Fecha:</b> 3 de septiembre de 2026<br>
  <b>Inicia en:</b> <a href="https://youtu.be/5nNHZnFrHPo?si=Xt10dgSjdkz1G1WU&t=570">09:30</a><br>
  <b>Duración:</b> 05:09
</p>

<p align="center">
  <img src="../assets/07-chapter-2/interviews/interview-recording/interview-3.png" alt="Evidencia de la entrevista 3 - Camilo Paredes" width="80%">
</p>

<p style="text-align: justify;">
  Camilo Paredes Vites tiene 31 años, vive en Los Olivos, Lima, y señaló estar casada. Es profesional de Ingeniería Química y trabaja como Supervisor de Control de Calidad en una planta farmacéutica, supervisando las salas de frío y el almacén de vacunas y medicamentos. Se describe como una persona detallista, disciplinada y proactiva.
</p>

<p style="text-align: justify;">
  Su equipo depende actualmente de dataloggers semi-manuales que deben descargarse físicamente mediante USB y procesarse en Excel cada semana para mantener la trazabilidad exigida por DIGEMID, incluyendo lotes, fechas de vencimiento y registros de temperatura. Recuerda un incidente crítico en el que un lote de insulina tuvo que ser destruido después de que una auditoría revelara un vacío de datos causado por un corte de energía que el datalogger no registró a tiempo, generando una pérdida económica considerable y una observación regulatoria. Lo que más le frustra son las horas semanales dedicadas a consolidar datos manualmente y la dificultad de unificar la información de la cadena de custodia, dividida entre papel y hojas de cálculo.
</p>

<p style="text-align: justify;">
  Imagina un dashboard en la nube conectado en tiempo real a los sensores, capaz de generar automáticamente reportes conformes al formato de DIGEMID y mantener un registro de auditoría inalterable. Recibiría con agrado tanto notificaciones instantáneas como acciones de mitigación automáticas, por ejemplo, activar un generador de respaldo, siempre que cada acción automatizada quede registrada para fines de auditoría. Para confiar en el sistema, necesitaría validación de la integridad de los datos alineada con los principios ALCOA+, redundancia de infraestructura y la capacidad de exportar registros para envíos regulatorios.
</p>

##### **Entrevista 4: Diego Gabriel Huamaní Ríos**

<p style="text-align: justify;">
  <b>Fecha:</b> 4 de septiembre de 2026<br>
  <b>Inicia en:</b> <a href="https://youtu.be/5nNHZnFrHPo?si=-vB8kZTB4MGwcUlY&t=879">14:39</a><br>
  <b>Duración:</b> 04:25
</p>

<p align="center">
  <img src="../assets/07-chapter-2/interviews/interview-recording/interview-4.jpeg" alt="Evidencia de la entrevista 4 - Diego Gabriel Huamaní Ríos" width="80%">
</p>

<p style="text-align: justify;">
  Diego Gabriel Huamaní Ríos es un ingeniero recién egresado de 24 años, soltero y residente de San Borja, que trabaja como Analista Junior de Calidad. Cuenta con casi dos años de experiencia enfocados en temas de almacenamiento y cadena de frío. En su tiempo libre disfruta de los videojuegos, la tecnología y el ciclismo, y se describe a sí mismo como curioso, tecnológico y analítico.
</p>

<p style="text-align: justify;">
  En su día a día, trabaja con un proceso de monitoreo de temperatura altamente manual y desactualizado. Su equipo invierte entre 10 y 12 horas semanales desplazándose físicamente a los refrigeradores, extrayendo dataloggers por USB y trasladando los datos a Excel para generar gráficas orientadas a auditorías regulatorias. Lo que más le frustra y estresa es realizar trabajo repetitivo de «copiar y pegar», sumado a la falta de visibilidad en tiempo real, que ocasiona que los problemas se conozcan cuando ya han ocurrido. Las consecuencias de este sistema se evidenciaron en un incidente reciente: un sábado por la noche falló la refrigeradora principal. Aunque la alarma sonora local se activó, no había personal en las instalaciones para escucharla y el correo de alerta llegó con retraso, lo que obligó a poner en cuarentena un lote grande de medicamentos termosensibles.
</p>

<p style="text-align: justify;">
  Para resolver esta problemática, Diego visualiza un sistema ideal basado en la nube, moderno y fácil de usar, equipado con sensores inalámbricos y una aplicación móvil nativa. Considera vital recibir notificaciones al instante y poder exportar reportes de auditoría con una sola acción. Sin embargo, su principal expectativa es que la plataforma sea proactiva: prefiere un sistema que active acciones de mitigación automática, como encender un equipo de enfriamiento de respaldo al detectar una desviación, en lugar de limitarse a enviar una alerta al celular.
</p>

##### **Entrevista 5: Carlos Montero**

<p style="text-align: justify;">
  <b>Fecha:</b> 5 de septiembre de 2026<br>
  <b>Inicia en:</b> <a href="https://youtu.be/5nNHZnFrHPo?si=SMuOglMlLqDQZkDf&t=1144">19:04</a><br>
  <b>Duración:</b> 05:43
</p>

<p align="center">
  <img src="../assets/07-chapter-2/interviews/interview-recording/interview-5.jpeg" alt="Evidencia de la entrevista 5 - Carlos Montero" width="80%">
</p>

<p style="text-align: justify;">
  Carlos Montero tiene 24 años, es soltero y vive en Surquillo, Lima. Trabaja como Asistente de Logística con alrededor de dos años de experiencia, encargándose de apoyar en la recepción de productos, el control de inventario, la coordinación de despachos y la revisión de las condiciones del almacén. Se describe como minucioso y aficionado a los videojuegos.
</p>

<p style="text-align: justify;">
  Actualmente, el monitoreo que realiza es manual: utiliza dataloggers que deben descargarse físicamente mediante USB, lo que le resulta frustrante por la pérdida de tiempo asociada a tener que desplazarse para revisarlos. Además, el cierre de mes se vuelve pesado al tener que consolidar información repartida en diferentes archivos. Recuerda un incidente crítico en el que una variación de temperatura puso en riesgo un lote y el equipo no lo detectó hasta que el daño ya se había producido.
</p>

<p style="text-align: justify;">
  Imagina un sistema en la nube que centralice las conexiones de todas las zonas del almacén y muestre la temperatura y la humedad en tiempo real mediante actualizaciones automáticas. Necesita que este sistema envíe alertas rápidas y preventivas antes de que se superen los límites establecidos. Para confiar plenamente en la plataforma, requiere que genere reportes de forma sencilla y mantenga un historial inalterable y seguro, asegurando que cualquier modificación quede registrada para facilitar las auditorías y garantizar el cumplimiento normativo.
</p>

### **2.2.3. Interview Analysis**

#### **Segmento 1: Laboratorios de Hospitales**

##### **Características**

- **Sexo:** Femenino (50%), Masculino (50%).
- **Edad:** 27–34 años.
- **Dispositivos:** Smartphone (100%), laptop/computadora (50%, equipo compartido del hospital).
- **Sistemas operativos:** Android, Windows.
- **Navegadores:** Chrome.
- **Influencia de marcas:** Equipos de refrigeración (Haier Biomedical, Thermo Fisher) y comunicación (WhatsApp).

##### **Objetivos comunes**

- Dejar de depender de procesos manuales y en papel para el monitoreo de muestras e insumos sensibles.
- Tener visibilidad confiable y en tiempo real sobre el estado de los equipos de refrigeración.
- Reducir el tiempo dedicado a registrar y consolidar datos.
- Superar auditorías regulatorias sin tener que preparar registros físicos a último momento.

##### **Motivaciones comunes**

- Proteger la integridad de las muestras biológicas y reactivos para evitar pérdidas.
- Evitar ser responsabilizados por incidentes prevenibles causados por vacíos en la supervisión manual.
- Sentirse respaldados, especialmente durante turnos aislados con poco personal.

##### **Frustraciones comunes**

- Procesos de monitoreo manuales y propensos a errores.
- Dificultad para correlacionar datos históricos almacenados en registros de papel.
- Falta de apoyo o escalamiento cuando ocurren incidentes en turnos con poco personal.

#### **Segmento 2: Empresas Farmacéuticas**

##### **Características**

- **Sexo:** Femenino (0%), Masculino (100%).
- **Edad:** 24–31 años.
- **Dispositivos:** Smartphone (100%), laptop/computadora (100%, corporativa en el caso de Control de Calidad y Logística).
- **Sistemas operativos:** Windows, iOS.
- **Navegadores:** Chrome, Brave.
- **Influencia de marcas:** Marco regulatorio (DIGEMID), proveedores de dataloggers USB y sistemas ERP.

##### **Objetivos comunes**

- Eliminar la dependencia de dataloggers USB y registros en papel que deben extraerse y consolidarse manualmente.
- Tener una única fuente de verdad que unifique la información actualmente repartida entre distintos archivos, hojas de cálculo y ubicaciones.
- Automatizar la generación de reportes de auditoría y trazabilidad conforme a la normativa de DIGEMID.
- Contar con un sistema que avise de forma proactiva ante una desviación, antes de que el problema se agrave, y no únicamente después de superado el límite.

##### **Motivaciones comunes**

- Evitar pérdidas económicas por lotes de producto dañados, puestos en riesgo o destruidos.
- Mantener el estatus regulatorio de la empresa y superar auditorías sin contratiempos ni documentación preparada a último momento.
- Reducir la carga de trabajo manual y repetitiva asociada a la documentación de cumplimiento, como la extracción de dataloggers, la consolidación en Excel y los cierres de mes.
- Evitar que el personal sea señalado individualmente por errores o incidentes originados en procesos manuales deficientes y no en su desempeño.

##### **Frustraciones comunes**

- Procesos de monitoreo manuales, como dataloggers USB y revisiones físicas, que consumen varias horas a la semana y generan trabajo repetitivo de «copiar y pegar».
- Visibilidad nula o tardía en tiempo real: los problemas, como una desviación de temperatura o un lote en riesgo, se descubren cuando el daño ya ocurrió.
- Información fragmentada entre distintos archivos, documentos y ubicaciones, lo que complica especialmente el cierre de mes y la preparación de auditorías.
- Falta de consenso sobre el nivel de autonomía deseado del sistema: mientras algunos usuarios confiarían en acciones de mitigación totalmente automáticas, otros prefieren que determinadas acciones críticas pasen primero por la revisión y aprobación de una persona.

## **2.3. Needfinding**

<p style="text-align: justify;">
  En esta sección se presentan los artefactos resultantes del análisis de la información recolectada en las entrevistas de la sección 2.2.3 y en el análisis competitivo de la sección 2.1.1. A partir de las características demográficas, objetivos, motivaciones y frustraciones identificadas para cada segmento objetivo, se construyeron los User Personas, el User Task Matrix, los User Journey Maps y los Empathy Maps correspondientes mediante la herramienta UXPressia.
</p>

### **2.3.1. User Personas**

<p style="text-align: justify;">
  Se elaboró una ficha de User Persona para cada segmento objetivo, considerando las características demográficas y subjetivas más representativas identificadas en el análisis de entrevistas, así como el posicionamiento frente a la competencia de la sección 2.1.1, que evidencia la necesidad de una solución ágil y de bajo costo para laboratorios e instituciones de salud medianas.
</p>

#### **Segmento 1: Laboratorios de Hospitales**

<p align="center">
  <img src="../assets/07-chapter-2/needfinding/user-personas/user-persona-segmeto-1.png" alt="User Persona del Segmento 1 - Laboratorios de Hospitales" width="85%">
</p>

<p style="text-align: justify;">
  Gabriela Campos Rivas representa al personal de laboratorio clínico responsable de la supervisión del banco de sangre, reactivos e insumos sensibles. Su perfil refleja la dependencia de procesos manuales de monitoreo y la necesidad de contar con visibilidad en tiempo real para prevenir incidentes críticos.
</p>

#### **Segmento 2: Empresas Farmacéuticas**

<p align="center">
  <img src="../assets/07-chapter-2/needfinding/user-personas/user-persona-segmeto-2.png" alt="User Persona del Segmento 2 - Empresas Farmacéuticas" width="85%">
</p>

<p style="text-align: justify;">
  Diego Ramírez Paredes representa al personal de calidad y logística responsable de la trazabilidad regulatoria de DIGEMID en el almacenamiento de medicamentos y vacunas. Su perfil refleja la carga operativa asociada a la consolidación manual de datos y la necesidad de automatizar el cumplimiento normativo.
</p>

### **2.3.2. User Task Matrix**

<p style="text-align: justify;">
  El siguiente User Task Matrix concentra las tareas que realizan los dos segmentos objetivo identificados para el proyecto SafeLab, representados por sus respectivos User Personas: <b>Gabriela Campos Rivas</b> (Segmento 1: Laboratorios de Hospitales) y <b>Diego Ramírez Paredes</b> (Segmento 2: Empresas Farmacéuticas). Las tareas corresponden a actividades que ambos perfiles realizan actualmente de forma manual, independientemente de la existencia de una solución de software, y fueron identificadas a partir del análisis de las entrevistas registradas en la sección 2.2.3.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Tarea</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Gabriela Campos Rivas<br>Frecuencia</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Gabriela Campos Rivas<br>Importancia</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Diego Ramírez Paredes<br>Frecuencia</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Diego Ramírez Paredes<br>Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Monitorear manualmente la temperatura y humedad de refrigeradoras y congeladoras.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Diaria</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Diaria</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Registrar lecturas de monitoreo en papel y transcribirlas a Excel.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Diaria</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td><td style="text-align: center; vertical-align: middle; padding: 6px;">No aplica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">—</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Descargar datos de dataloggers mediante USB.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">No aplica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">—</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Semanal</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Consolidar información dispersa en archivos y hojas de cálculo.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Mensual</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Media</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Semanal</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Realizar rondas de inspección física de los equipos de refrigeración.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Diaria</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Semanal</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Media</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Preparar documentación para auditorías regulatorias de DIGESA/DIRESA/DIGEMID.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Esporádica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Esporádica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Responder ante incidentes de desviación de temperatura.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Esporádica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Esporádica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Escalar incidentes críticos a un supervisor o equipo de guardia.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Esporádica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Esporádica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Media</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Generar reportes de trazabilidad y cumplimiento normativo.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Mensual</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Media</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Semanal</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Alta</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Coordinar despachos e inventario del almacén.</td><td style="text-align: center; vertical-align: middle; padding: 6px;">No aplica</td><td style="text-align: center; vertical-align: middle; padding: 6px;">—</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Semanal</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Media</td></tr>
  </tbody>
</table>

<p style="text-align: justify;">
  <b>Análisis del cuadro.</b> Las tareas con mayor frecuencia e importancia para ambos segmentos son el <b>monitoreo manual de temperatura y humedad</b> y la <b>respuesta ante incidentes de desviación</b>, lo que confirma que la necesidad central de ambos perfiles es la falta de visibilidad en tiempo real sobre el estado de sus equipos de refrigeración. Asimismo, <b>preparar documentación para auditorías regulatorias</b> aparece como una tarea esporádica, pero de alta importancia en ambos casos. Esto refleja que el cumplimiento normativo —DIGESA/DIRESA para el sector salud y DIGEMID para el sector farmacéutico— constituye un factor crítico compartido, aunque el marco regulatorio específico sea diferente.
</p>

<p style="text-align: justify;">
  La principal diferencia entre ambos User Personas se encuentra en el método de registro: Gabriela depende de un <b>proceso en papel</b> que se transcribe diariamente a Excel, mientras que Diego depende de la <b>extracción periódica de dataloggers USB</b>, una tarea que no aplica al segmento hospitalario. Esto también se refleja en la frecuencia de consolidación de datos y generación de reportes, que es más constante en el caso de Diego debido al volumen de información regulatoria que exige su rol, frente a una consolidación más espaciada en el caso de Gabriela. Finalmente, la coordinación logística de despachos e inventario constituye una tarea propia del segmento farmacéutico y no tiene un equivalente directo en el entorno hospitalario.
</p>

### **2.3.3. User Journey Mapping**

<p style="text-align: justify;">
  Se elaboraron los User Journey Maps en su versión As-Is, ilustrando el recorrido completo de cada segmento objetivo desde el inicio de su proceso de monitoreo hasta el cierre de auditoría, dentro de la situación actual y sin la existencia de la solución SafeLab. Cada User Journey Map se encuentra vinculado con su respectivo User Persona en UXPressia.
</p>

#### **Segmento 1: Laboratorios de Hospitales**

<p align="center">
  <img src="../assets/07-chapter-2/needfinding/user-journey-mapping/user-journey-mapping-segmeto-1.png" alt="User Journey Map del Segmento 1 - Laboratorios de Hospitales" width="85%">
</p>

<p style="text-align: justify;">
  El recorrido de Gabriela Campos Rivas inicia con la recepción de turno y la ronda de revisión física de refrigeradoras y congeladoras, continúa con el registro manual en papel y su posterior transcripción a Excel, y se ve interrumpido cuando ocurre una desviación de temperatura que, debido a la falta de monitoreo en tiempo real, puede pasar desapercibida durante horas. El journey culmina con la consolidación de registros físicos para las auditorías de DIGESA/DIRESA, un proceso que genera frustración debido a la fragilidad y dispersión de los registros en papel.
</p>

#### **Segmento 2: Empresas Farmacéuticas**

<p align="center">
  <img src="../assets/07-chapter-2/needfinding/user-journey-mapping/user-journey-mapping-segmeto-2.png" alt="User Journey Map del Segmento 2 - Empresas Farmacéuticas" width="85%">
</p>

<p style="text-align: justify;">
  El recorrido de Diego Ramírez Paredes inicia con el desplazamiento físico a cada sala o almacén para extraer dataloggers mediante USB, continúa con el procesamiento semanal de la información en Excel para fines de trazabilidad y se ve afectado cuando una desviación no detectada a tiempo, por falta de visibilidad en tiempo real, pone en riesgo un lote de producto. El journey culmina con el cierre de mes y la preparación del reporte conforme a DIGEMID, proceso en el que un vacío de datos puede derivar en la pérdida total de un lote y en una observación regulatoria.
</p>

### **2.3.4. Empathy Mapping**

<p style="text-align: justify;">
  Se elaboraron los Empathy Maps para cada User Persona, colocando al usuario representado en el centro y completando cada cuadrante a partir de las observaciones del equipo sobre la información recolectada en las entrevistas. Para ello, se consideró qué necesita hacer, qué dice, qué ve, qué hace, qué escucha, qué piensa y siente, además de identificar sus Pains y Gains.
</p>

#### **Segmento 1: Laboratorios de Hospitales**

<p align="center">
  <img src="../assets/07-chapter-2/needfinding/empathy-mapping/empathy-mapping-segmento-1.png" alt="Empathy Map del Segmento 1 - Laboratorios de Hospitales" width="85%">
</p>

<p style="text-align: justify;">
  El Empathy Map de Gabriela Campos Rivas evidencia una tensión entre la tranquilidad que siente al controlar el proceso durante su turno y la preocupación constante por lo que puede ocurrir en su ausencia. Sus principales Pains giran en torno a la fragilidad de los registros en papel y la falta de respaldo durante turnos con poco personal, mientras que sus Gains se concentran en alertas en tiempo real y un registro de auditoría digital e inalterable.
</p>

#### **Segmento 2: Empresas Farmacéuticas**

<p align="center">
  <img src="../assets/07-chapter-2/needfinding/empathy-mapping/empathy-mapping-segmento-2.png" alt="Empathy Map del Segmento 2 - Empresas Farmacéuticas" width="85%">
</p>

<p style="text-align: justify;">
  El Empathy Map de Diego Ramírez Paredes evidencia el estrés generado por la carga de trabajo manual y repetitivo, así como el temor a ser señalado individualmente por errores originados en procesos deficientes que no dependen de su desempeño. Sus principales Pains están relacionados con la falta de visibilidad en tiempo real y la fragmentación de la información, mientras que sus Gains apuntan a un dashboard centralizado en la nube y a reportes automáticos conformes a DIGEMID.
</p>

### **2.3.5. Big Picture Event Storming**

### **2.3.6. Ubiquitous Language**

## **2.4. Requirements Specification**

### **2.4.1. User Stories**

<p style="text-align: justify;">
  Esta sección presenta las Epics, User Stories, Technical Stories y Spike Stories identificadas para SafeLab, de acuerdo con las necesidades de los laboratorios hospitalarios y las empresas farmacéuticas. Los Acceptance Criteria se redactan utilizando la estructura de Gherkin <b>Given-When-Then</b> para establecer condiciones verificables para cada requisito, sin depender de detalles específicos de la interfaz de usuario.
</p>

#### **Epics**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Epic ID</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th>
    </tr>
  </thead>
  <tbody>
  <tr><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Organización del monitoreo</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Gestionar sitios de monitoreo, áreas de almacenamiento y equipos para organizar el monitoreo ambiental entre distintas ubicaciones.</td></tr>
  <tr><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Monitoreo en tiempo real</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar automáticamente la temperatura, la humedad, el estado de los equipos y la información de monitoreo sin depender de registros manuales.</td></tr>
  <tr><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Alertas y notificaciones</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Recibir, visualizar y gestionar alertas relacionadas con las condiciones ambientales y los equipos monitoreados.</td></tr>
  <tr><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Reportes y análisis de datos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Acceder a datos históricos, comparar periodos y generar reportes que apoyen el monitoreo, el control y las auditorías.</td></tr>
  <tr><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Condición y mantenimiento de equipos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Monitorear la condición, confiabilidad e historial de mantenimiento de los equipos para identificar posibles fallas.</td></tr>
  <tr><td style="text-align: center; vertical-align: top; padding: 6px;">EP06</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Dashboard y vista general del sistema</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar un resumen centralizado de la información de monitoreo, las alertas y los indicadores relevantes.</td></tr>
  <tr><td style="text-align: center; vertical-align: top; padding: 6px;">EP07</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Acceso de usuarios y roles</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Permitir que los usuarios accedan a SafeLab y gestionen la información de sus cuentas y accesos.</td></tr>
  <tr><td style="text-align: center; vertical-align: top; padding: 6px;">EP08</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Landing Page</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Presentar SafeLab y la información de su producto mediante la Landing Page estática.</td></tr>
  </tbody>
</table>

<br>

#### **User Stories**

##### **US01 - Registrar sitio de monitoreo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US01</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Registrar sitio de monitoreo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero registrar un sitio de monitoreo con su nombre y ubicación para organizar el monitoreo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Registro exitoso</b><br>
      <b>Given</b> que se proporciona información válida del sitio<br>
      <b>When</b> el usuario registra el sitio de monitoreo<br>
      <b>Then</b> el sistema almacena la información del sitio.<br><br>
      <b>Scenario 2: Falta información requerida</b><br>
      <b>Given</b> que la información requerida del sitio está incompleta<br>
      <b>When</b> el usuario intenta registrar el sitio de monitoreo<br>
      <b>Then</b> el sistema rechaza el registro.
    </td>
  </tr>
</table>

##### **US02 - Visualizar sitios de monitoreo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US02</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar sitios de monitoreo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los sitios de monitoreo registrados para poder gestionarlos.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen sitios registrados</b><br>
      <b>Given</b> que existen sitios de monitoreo registrados<br>
      <b>When</b> el usuario solicita los sitios registrados<br>
      <b>Then</b> el sistema proporciona los sitios disponibles.<br><br>
      <b>Scenario 2: No existen sitios registrados</b><br>
      <b>Given</b> que no existen sitios de monitoreo registrados<br>
      <b>When</b> el usuario solicita los sitios registrados<br>
      <b>Then</b> el sistema indica que no hay sitios disponibles.
    </td>
  </tr>
</table>

##### **US03 - Crear área de almacenamiento**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US03</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Crear área de almacenamiento</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero crear áreas de almacenamiento con un nombre y tipo para organizar los equipos.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Creación exitosa</b><br>
      <b>Given</b> que se proporciona información válida del área de almacenamiento<br>
      <b>When</b> el usuario crea el área de almacenamiento<br>
      <b>Then</b> el sistema almacena la nueva área de almacenamiento.<br><br>
      <b>Scenario 2: Falta información requerida</b><br>
      <b>Given</b> que la información requerida del área de almacenamiento está incompleta<br>
      <b>When</b> el usuario intenta crear el área de almacenamiento<br>
      <b>Then</b> el sistema rechaza la creación.
    </td>
  </tr>
</table>

##### **US04 - Visualizar áreas de almacenamiento**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US04</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar áreas de almacenamiento</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las áreas de almacenamiento para comprender cómo están organizados los equipos monitoreados.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen áreas de almacenamiento</b><br>
      <b>Given</b> que existen áreas de almacenamiento registradas<br>
      <b>When</b> el usuario solicita las áreas de almacenamiento<br>
      <b>Then</b> el sistema proporciona las áreas de almacenamiento registradas.<br><br>
      <b>Scenario 2: No existen áreas de almacenamiento</b><br>
      <b>Given</b> que no existen áreas de almacenamiento registradas<br>
      <b>When</b> el usuario solicita las áreas de almacenamiento<br>
      <b>Then</b> el sistema indica que no hay áreas de almacenamiento disponibles.
    </td>
  </tr>
</table>

##### **US05 - Registrar equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US05</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Registrar equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero registrar equipos con su nombre, tipo e identificador para que puedan ser monitoreados.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Registro exitoso</b><br>
      <b>Given</b> que se proporciona información válida del equipo<br>
      <b>When</b> el usuario registra el equipo<br>
      <b>Then</b> el sistema almacena la información del equipo.<br><br>
      <b>Scenario 2: Falta información requerida</b><br>
      <b>Given</b> que la información requerida del equipo está incompleta<br>
      <b>When</b> el usuario intenta registrar el equipo<br>
      <b>Then</b> el sistema rechaza el registro.
    </td>
  </tr>
</table>

##### **US06 - Visualizar lista de equipos**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US06</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar lista de equipos</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los equipos registrados para poder gestionarlos.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen equipos</b><br>
      <b>Given</b> que existen equipos registrados<br>
      <b>When</b> el usuario solicita la lista de equipos<br>
      <b>Then</b> el sistema proporciona los equipos registrados.<br><br>
      <b>Scenario 2: No existen equipos</b><br>
      <b>Given</b> que no existen equipos registrados<br>
      <b>When</b> el usuario solicita la lista de equipos<br>
      <b>Then</b> el sistema indica que no hay equipos disponibles.
    </td>
  </tr>
</table>

##### **US07 - Asignar equipo a un área**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US07</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Asignar equipo a un área</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero asignar un equipo a un área de almacenamiento para conocer su ubicación.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se proporcionan un equipo y un área válidos</b><br>
      <b>Given</b> que existen un equipo registrado y un área de almacenamiento registrada<br>
      <b>When</b> el usuario asigna el equipo al área de almacenamiento<br>
      <b>Then</b> el sistema asocia el equipo con dicha área.<br><br>
      <b>Scenario 2: La información requerida no está disponible</b><br>
      <b>Given</b> que el equipo o el área de almacenamiento no están disponibles<br>
      <b>When</b> el usuario intenta crear la asignación<br>
      <b>Then</b> el sistema rechaza la asignación.
    </td>
  </tr>
</table>

##### **US08 - Buscar equipo por nombre**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US08</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Buscar equipo por nombre</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero buscar equipos por nombre para encontrarlos rápidamente.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe un equipo coincidente</b><br>
      <b>Given</b> que un equipo registrado coincide con el nombre proporcionado<br>
      <b>When</b> el usuario realiza la búsqueda<br>
      <b>Then</b> el sistema proporciona el equipo coincidente.<br><br>
      <b>Scenario 2: No existe un equipo coincidente</b><br>
      <b>Given</b> que ningún equipo registrado coincide con el nombre proporcionado<br>
      <b>When</b> el usuario realiza la búsqueda<br>
      <b>Then</b> el sistema indica que no existe un equipo coincidente disponible.
    </td>
  </tr>
</table>

##### **US09 - Visualizar valores de temperatura**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US09</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar valores de temperatura</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los valores de temperatura para monitorear las condiciones de almacenamiento.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Los datos de temperatura están disponibles</b><br>
      <b>Given</b> que el equipo monitoreado dispone de datos de temperatura<br>
      <b>When</b> el usuario solicita su información de monitoreo<br>
      <b>Then</b> el sistema proporciona el valor de temperatura disponible.<br><br>
      <b>Scenario 2: Los datos de temperatura no están disponibles</b><br>
      <b>Given</b> que el equipo monitoreado no dispone de datos de temperatura<br>
      <b>When</b> el usuario solicita su información de monitoreo<br>
      <b>Then</b> el sistema indica que los datos de temperatura no están disponibles.
    </td>
  </tr>
</table>

##### **US10 - Visualizar valores de humedad**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US10</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar valores de humedad</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los valores de humedad para monitorear las condiciones de almacenamiento.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Los datos de humedad están disponibles</b><br>
      <b>Given</b> que el equipo monitoreado dispone de datos de humedad<br>
      <b>When</b> el usuario solicita su información de monitoreo<br>
      <b>Then</b> el sistema proporciona el valor de humedad disponible.<br><br>
      <b>Scenario 2: Los datos de humedad no están disponibles</b><br>
      <b>Given</b> que el equipo monitoreado no dispone de datos de humedad<br>
      <b>When</b> el usuario solicita su información de monitoreo<br>
      <b>Then</b> el sistema indica que los datos de humedad no están disponibles.
    </td>
  </tr>
</table>

##### **US11 - Visualizar estado operativo del equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US11</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar estado operativo del equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero saber si un equipo monitoreado está funcionando para detectar problemas.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: El equipo está proporcionando datos</b><br>
      <b>Given</b> que el equipo está proporcionando datos de monitoreo<br>
      <b>When</b> el usuario solicita su estado<br>
      <b>Then</b> el sistema identifica el equipo como operativo.<br><br>
      <b>Scenario 2: El equipo no está proporcionando datos</b><br>
      <b>Given</b> que el equipo no está proporcionando datos de monitoreo<br>
      <b>When</b> el usuario solicita su estado<br>
      <b>Then</b> el sistema identifica que el equipo no está funcionando con normalidad.
    </td>
  </tr>
</table>

##### **US12 - Visualizar detalles del equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US12</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar detalles del equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los detalles de un equipo para revisar su temperatura, humedad y estado.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: El equipo existe</b><br>
      <b>Given</b> que existe un equipo registrado<br>
      <b>When</b> el usuario solicita sus detalles<br>
      <b>Then</b> el sistema proporciona la información disponible de temperatura, humedad y estado.<br><br>
      <b>Scenario 2: El equipo no existe</b><br>
      <b>Given</b> que el equipo solicitado no está registrado<br>
      <b>When</b> se solicitan sus detalles<br>
      <b>Then</b> el sistema indica que el equipo no está disponible.
    </td>
  </tr>
</table>

##### **US13 - Visualizar lista de equipos con datos en tiempo real**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US13</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar lista de equipos con datos en tiempo real</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los equipos junto con sus valores actuales de monitoreo para supervisar rápidamente sus condiciones.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Los datos actuales de monitoreo están disponibles</b><br>
      <b>Given</b> que los equipos registrados disponen de datos actuales de monitoreo<br>
      <b>When</b> el usuario solicita la información de los equipos<br>
      <b>Then</b> el sistema proporciona los equipos junto con sus valores actuales disponibles.<br><br>
      <b>Scenario 2: Los datos actuales no están disponibles</b><br>
      <b>Given</b> que algunos equipos registrados no disponen de datos actuales<br>
      <b>When</b> el usuario solicita la información de los equipos<br>
      <b>Then</b> el sistema indica qué equipos no disponen de datos actuales.
    </td>
  </tr>
</table>

##### **US14 - Filtrar equipos por área de almacenamiento**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US14</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Filtrar equipos por área de almacenamiento</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero filtrar los equipos por área de almacenamiento para concentrarme en una ubicación específica.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen equipos en el área seleccionada</b><br>
      <b>Given</b> que existen equipos asignados al área de almacenamiento seleccionada<br>
      <b>When</b> el usuario filtra los equipos por dicha área<br>
      <b>Then</b> el sistema proporciona los equipos asignados a ella.<br><br>
      <b>Scenario 2: No existen equipos en el área seleccionada</b><br>
      <b>Given</b> que no existen equipos asignados al área de almacenamiento seleccionada<br>
      <b>When</b> el usuario aplica el filtro<br>
      <b>Then</b> el sistema indica que no hay equipos disponibles para dicha área.
    </td>
  </tr>
</table>

##### **US15 - Identificar equipos sin datos recientes**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US15</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Identificar equipos sin datos recientes</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero identificar los equipos que no tienen datos recientes para detectar interrupciones en el monitoreo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: El equipo no tiene datos recientes</b><br>
      <b>Given</b> que un equipo registrado no ha proporcionado datos recientes de monitoreo<br>
      <b>When</b> el sistema evalúa sus lecturas disponibles<br>
      <b>Then</b> el equipo se identifica como un equipo sin datos recientes.<br><br>
      <b>Scenario 2: El equipo tiene datos recientes</b><br>
      <b>Given</b> que un equipo registrado dispone de datos recientes de monitoreo<br>
      <b>When</b> el sistema evalúa sus lecturas disponibles<br>
      <b>Then</b> el equipo no se identifica como un equipo con datos recientes faltantes.
    </td>
  </tr>
</table>

##### **US16 - Recolección automática de datos**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US16</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Recolección automática de datos</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero que los datos de monitoreo se recolecten automáticamente para no tener que registrarlos de forma manual.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se reciben datos de monitoreo</b><br>
      <b>Given</b> que el equipo monitoreado está proporcionando datos<br>
      <b>When</b> el sistema recibe una nueva lectura<br>
      <b>Then</b> la lectura se registra automáticamente.<br><br>
      <b>Scenario 2: No se reciben datos de monitoreo</b><br>
      <b>Given</b> que el equipo monitoreado no proporciona datos<br>
      <b>When</b> el sistema espera una lectura de monitoreo<br>
      <b>Then</b> el sistema identifica que no se recibió un nuevo dato.
    </td>
  </tr>
</table>

##### **US17 - Visualizar datos en dispositivo móvil**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US17</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar datos en dispositivo móvil</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los datos de monitoreo desde un dispositivo móvil para acceder a la información desde la aplicación móvil.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Los datos de monitoreo están disponibles</b><br>
      <b>Given</b> que el usuario tiene acceso a SafeLab y existen datos de monitoreo disponibles<br>
      <b>When</b> el usuario solicita información de monitoreo desde la aplicación móvil<br>
      <b>Then</b> el sistema proporciona los datos de monitoreo disponibles.<br><br>
      <b>Scenario 2: Los datos de monitoreo no pueden obtenerse</b><br>
      <b>Given</b> que los datos de monitoreo no están disponibles<br>
      <b>When</b> el usuario solicita la información de monitoreo<br>
      <b>Then</b> el sistema indica que los datos solicitados no pueden obtenerse.
    </td>
  </tr>
</table>

##### **US18 - Recibir alertas de temperatura**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US18</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Recibir alertas de temperatura</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recibir alertas cuando la temperatura supere los límites establecidos para responder ante la desviación.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: La temperatura supera un límite establecido</b><br>
      <b>Given</b> que se ha definido un límite de temperatura<br>
      <b>When</b> una temperatura registrada supera dicho límite<br>
      <b>Then</b> el sistema genera una alerta de temperatura.<br><br>
      <b>Scenario 2: La temperatura se mantiene dentro de los límites establecidos</b><br>
      <b>Given</b> que se ha definido un límite de temperatura<br>
      <b>When</b> una temperatura registrada se mantiene dentro de los límites establecidos<br>
      <b>Then</b> el sistema no genera una alerta por desviación de temperatura.
    </td>
  </tr>
</table>

##### **US19 - Recibir alertas de humedad**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US19</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Recibir alertas de humedad</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recibir alertas cuando la humedad supere los límites establecidos para responder ante la desviación.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: La humedad supera un límite establecido</b><br>
      <b>Given</b> que se ha definido un límite de humedad<br>
      <b>When</b> un valor de humedad registrado supera dicho límite<br>
      <b>Then</b> el sistema genera una alerta de humedad.<br><br>
      <b>Scenario 2: La humedad se mantiene dentro de los límites establecidos</b><br>
      <b>Given</b> que se ha definido un límite de humedad<br>
      <b>When</b> un valor de humedad registrado se mantiene dentro de los límites establecidos<br>
      <b>Then</b> el sistema no genera una alerta por desviación de humedad.
    </td>
  </tr>
</table>

##### **US20 - Visualizar lista de alertas**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US20</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar lista de alertas</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las alertas generadas para gestionar los incidentes detectados.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen alertas</b><br>
      <b>Given</b> que se han generado alertas<br>
      <b>When</b> el usuario solicita la información de alertas<br>
      <b>Then</b> el sistema proporciona las alertas disponibles.<br><br>
      <b>Scenario 2: No existen alertas</b><br>
      <b>Given</b> que no se han generado alertas<br>
      <b>When</b> el usuario solicita la información de alertas<br>
      <b>Then</b> el sistema indica que no hay alertas disponibles.
    </td>
  </tr>
</table>

##### **US21 - Visualizar detalles de una alerta**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US21</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar detalles de una alerta</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los detalles de una alerta para comprender el problema detectado.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: La alerta existe</b><br>
      <b>Given</b> que existe una alerta generada<br>
      <b>When</b> el usuario solicita sus detalles<br>
      <b>Then</b> el sistema proporciona el equipo relacionado, el valor registrado y la información de fecha y hora.<br><br>
      <b>Scenario 2: La alerta no existe</b><br>
      <b>Given</b> que la alerta solicitada no está disponible<br>
      <b>When</b> se solicitan sus detalles<br>
      <b>Then</b> el sistema indica que la alerta no puede encontrarse.
    </td>
  </tr>
</table>

##### **US22 - Confirmar atención de una alerta**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US22</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Confirmar atención de una alerta</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero confirmar la atención de una alerta para llevar un control de las alertas que ya fueron gestionadas.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se confirma la atención de una alerta activa</b><br>
      <b>Given</b> que una alerta aún no ha sido confirmada como atendida<br>
      <b>When</b> el usuario confirma la atención de la alerta<br>
      <b>Then</b> el sistema registra su estado como atendida.<br><br>
      <b>Scenario 2: La alerta ya fue confirmada como atendida</b><br>
      <b>Given</b> que una alerta ya fue confirmada como atendida<br>
      <b>When</b> se solicita nuevamente su confirmación<br>
      <b>Then</b> el sistema conserva su estado de atención.
    </td>
  </tr>
</table>

##### **US23 - Visualizar alertas ordenadas por severidad**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US23</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar alertas ordenadas por severidad</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las alertas según su severidad para poder priorizarlas.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen alertas con distintos niveles de severidad</b><br>
      <b>Given</b> que existen múltiples alertas con diferentes niveles de severidad<br>
      <b>When</b> el usuario solicita las alertas ordenadas por severidad<br>
      <b>Then</b> el sistema proporciona las alertas de acuerdo con su severidad.<br><br>
      <b>Scenario 2: Las alertas tienen la misma severidad</b><br>
      <b>Given</b> que las alertas disponibles tienen el mismo nivel de severidad<br>
      <b>When</b> el usuario solicita que se ordenen por severidad<br>
      <b>Then</b> el sistema proporciona dichas alertas sin modificar su clasificación de severidad.
    </td>
  </tr>
</table>

##### **US24 - Recibir alertas en un dispositivo móvil**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US24</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Recibir alertas en un dispositivo móvil</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recibir las alertas de SafeLab en un dispositivo móvil para enterarme de los incidentes detectados.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Una alerta requiere notificación móvil</b><br>
      <b>Given</b> que el sistema genera una alerta que debe comunicarse al usuario<br>
      <b>When</b> se ejecuta el proceso de notificación<br>
      <b>Then</b> la información de la alerta se envía al dispositivo móvil registrado.<br><br>
      <b>Scenario 2: La entrega no puede completarse</b><br>
      <b>Given</b> que la información de la alerta no puede entregarse al dispositivo<br>
      <b>When</b> se ejecuta el proceso de notificación<br>
      <b>Then</b> el sistema conserva la información de la alerta generada.
    </td>
  </tr>
</table>

##### **US25 - Configurar límites de alerta por equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US25</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Configurar límites de alerta por equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero definir límites de temperatura y humedad para cada equipo monitoreado para que se generen alertas cuando esos límites sean superados.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se proporcionan límites válidos</b><br>
      <b>Given</b> que se proporcionan límites ambientales válidos para un equipo registrado<br>
      <b>When</b> el usuario guarda los límites<br>
      <b>Then</b> el sistema almacena los límites configurados para dicho equipo.<br><br>
      <b>Scenario 2: Se proporcionan límites inválidos</b><br>
      <b>Given</b> que los límites proporcionados son inválidos o están incompletos<br>
      <b>When</b> el usuario intenta guardarlos<br>
      <b>Then</b> el sistema rechaza la configuración.
    </td>
  </tr>
</table>

##### **US26 - Compartir alertas con el equipo de trabajo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US26</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Compartir alertas con el equipo de trabajo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero que las alertas estén disponibles para el equipo de trabajo para coordinar la atención de los incidentes de monitoreo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: La alerta está disponible</b><br>
      <b>Given</b> que se ha generado una alerta<br>
      <b>When</b> los miembros autorizados del equipo solicitan la información de la alerta<br>
      <b>Then</b> el sistema proporciona la misma información registrada de la alerta.<br><br>
      <b>Scenario 2: La alerta no está disponible</b><br>
      <b>Given</b> que la alerta solicitada no existe<br>
      <b>When</b> un miembro del equipo solicita su información<br>
      <b>Then</b> el sistema indica que la alerta no está disponible.
    </td>
  </tr>
</table>

##### **US27 - Visualizar datos históricos**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US27</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar datos históricos</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar datos históricos de monitoreo para analizar condiciones pasadas.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen datos históricos</b><br>
      <b>Given</b> que se almacenan datos históricos de monitoreo para un equipo<br>
      <b>When</b> el usuario solicita su historial<br>
      <b>Then</b> el sistema proporciona los datos históricos disponibles.<br><br>
      <b>Scenario 2: No existen datos históricos</b><br>
      <b>Given</b> que no existen datos históricos de monitoreo almacenados para el equipo solicitado<br>
      <b>When</b> el usuario solicita su historial<br>
      <b>Then</b> el sistema indica que no hay datos históricos disponibles.
    </td>
  </tr>
</table>

##### **US28 - Seleccionar un rango de fechas para los datos**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US28</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Seleccionar un rango de fechas para los datos</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero seleccionar un rango de fechas para revisar la información de monitoreo de un periodo específico.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se proporciona un rango de fechas válido</b><br>
      <b>Given</b> que se proporcionan una fecha de inicio y una fecha de fin válidas<br>
      <b>When</b> el usuario solicita datos de monitoreo para ese rango<br>
      <b>Then</b> el sistema proporciona los datos correspondientes al periodo seleccionado.<br><br>
      <b>Scenario 2: Se proporciona un rango de fechas inválido</b><br>
      <b>Given</b> que el rango de fechas proporcionado es inválido<br>
      <b>When</b> se solicitan datos de monitoreo<br>
      <b>Then</b> el sistema rechaza el rango de fechas.
    </td>
  </tr>
</table>

##### **US29 - Comparar datos entre periodos**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US29</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Comparar datos entre periodos</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero comparar los datos de monitoreo entre periodos para identificar variaciones.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Ambos periodos contienen datos</b><br>
      <b>Given</b> que se proporcionan dos periodos válidos con datos de monitoreo<br>
      <b>When</b> el usuario solicita la comparación<br>
      <b>Then</b> el sistema proporciona la información de monitoreo de ambos periodos.<br><br>
      <b>Scenario 2: La información requerida para la comparación está incompleta</b><br>
      <b>Given</b> que los periodos requeridos no están completamente definidos<br>
      <b>When</b> el usuario solicita la comparación<br>
      <b>Then</b> el sistema rechaza la solicitud de comparación.
    </td>
  </tr>
</table>

##### **US30 - Generar reporte por equipo y fecha**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US30</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Generar reporte por equipo y fecha</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero generar reportes por equipo y fecha para utilizar los registros de monitoreo en actividades de control y auditoría.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: La información requerida para el reporte está disponible</b><br>
      <b>Given</b> que se proporcionan información válida del equipo y de la fecha<br>
      <b>When</b> el usuario solicita un reporte<br>
      <b>Then</b> el sistema genera un reporte utilizando la información de monitoreo disponible.<br><br>
      <b>Scenario 2: La información requerida está incompleta</b><br>
      <b>Given</b> que falta información requerida para el reporte<br>
      <b>When</b> el usuario solicita un reporte<br>
      <b>Then</b> el sistema rechaza la solicitud del reporte.
    </td>
  </tr>
</table>

##### **US31 - Descargar archivo de reporte**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US31</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Descargar archivo de reporte</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero descargar los reportes generados para utilizarlos o compartirlos fuera de SafeLab.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe un reporte generado</b><br>
      <b>Given</b> que se ha generado un reporte<br>
      <b>When</b> el usuario solicita su descarga<br>
      <b>Then</b> el sistema proporciona el archivo del reporte generado.<br><br>
      <b>Scenario 2: No existe un reporte generado</b><br>
      <b>Given</b> que no hay un reporte generado disponible<br>
      <b>When</b> el usuario solicita descargar un reporte<br>
      <b>Then</b> el sistema indica que no hay ningún reporte disponible.
    </td>
  </tr>
</table>

##### **US32 - Visualizar historial de incidentes**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US32</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar historial de incidentes</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar el historial de incidentes para revisar alertas y eventos anteriores.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe un historial de incidentes</b><br>
      <b>Given</b> que se han registrado alertas o incidentes anteriores<br>
      <b>When</b> el usuario solicita el historial de incidentes<br>
      <b>Then</b> el sistema proporciona la información histórica disponible de los incidentes.<br><br>
      <b>Scenario 2: No existe un historial de incidentes</b><br>
      <b>Given</b> que no se han registrado alertas ni incidentes anteriores<br>
      <b>When</b> el usuario solicita el historial de incidentes<br>
      <b>Then</b> el sistema indica que no hay un historial de incidentes disponible.
    </td>
  </tr>
</table>

##### **US33 - Exportar archivo de datos**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US33</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Exportar archivo de datos</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero exportar los datos de monitoreo para utilizarlos fuera del sistema.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Los datos están disponibles</b><br>
      <b>Given</b> que existen datos de monitoreo disponibles para exportación<br>
      <b>When</b> el usuario solicita la exportación<br>
      <b>Then</b> el sistema genera un archivo de exportación utilizando los datos disponibles.<br><br>
      <b>Scenario 2: Los datos no están disponibles</b><br>
      <b>Given</b> que no existen datos de monitoreo disponibles para exportación<br>
      <b>When</b> el usuario solicita la exportación<br>
      <b>Then</b> el sistema indica que no hay datos disponibles.
    </td>
  </tr>
</table>

##### **US34 - Comparar datos semanales y mensuales**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US34</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Comparar datos semanales y mensuales</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero comparar datos de monitoreo semanales y mensuales para identificar variaciones entre periodos.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Los datos semanales y mensuales están disponibles</b><br>
      <b>Given</b> que existe información de monitoreo para la semana y el mes seleccionados<br>
      <b>When</b> el usuario solicita la comparación<br>
      <b>Then</b> el sistema proporciona la información correspondiente a ambos periodos.<br><br>
      <b>Scenario 2: La información requerida del periodo está incompleta</b><br>
      <b>Given</b> que la semana o el mes no están completamente definidos<br>
      <b>When</b> el usuario solicita la comparación<br>
      <b>Then</b> el sistema rechaza la solicitud de comparación.
    </td>
  </tr>
</table>

##### **US35 - Visualizar condición del equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US35</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar condición del equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar la condición de un equipo para identificar posibles fallas.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: El equipo funciona con normalidad</b><br>
      <b>Given</b> que el equipo funciona dentro de las condiciones esperadas<br>
      <b>When</b> el usuario solicita conocer su condición<br>
      <b>Then</b> el sistema identifica su condición como normal.<br><br>
      <b>Scenario 2: Se detecta una condición anómala</b><br>
      <b>Given</b> que se ha detectado una condición anómala en el equipo<br>
      <b>When</b> el usuario solicita conocer su condición<br>
      <b>Then</b> el sistema identifica la condición anómala detectada.
    </td>
  </tr>
</table>

##### **US36 - Visualizar valores anómalos**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US36</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar valores anómalos</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero identificar valores ambientales fuera de los límites establecidos para detectar problemas.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: El valor supera los límites establecidos</b><br>
      <b>Given</b> que los límites ambientales están definidos<br>
      <b>When</b> un valor registrado se encuentra fuera de dichos límites<br>
      <b>Then</b> el sistema identifica el valor como anómalo.<br><br>
      <b>Scenario 2: El valor se mantiene dentro de los límites</b><br>
      <b>Given</b> que los límites ambientales están definidos<br>
      <b>When</b> un valor registrado se mantiene dentro de dichos límites<br>
      <b>Then</b> el sistema no identifica el valor como anómalo.
    </td>
  </tr>
</table>

##### **US37 - Recibir alertas de advertencia del equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US37</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Recibir alertas de advertencia del equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recibir advertencias sobre los equipos para identificar posibles fallas.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se detecta una condición anómala del equipo</b><br>
      <b>Given</b> que el sistema detecta una condición anómala en un equipo<br>
      <b>When</b> la condición cumple los criterios para generar una advertencia<br>
      <b>Then</b> el sistema genera una advertencia del equipo.<br><br>
      <b>Scenario 2: El equipo funciona con normalidad</b><br>
      <b>Given</b> que no se detecta ninguna condición anómala en el equipo<br>
      <b>When</b> el equipo es monitoreado<br>
      <b>Then</b> el sistema no genera una advertencia del equipo.
    </td>
  </tr>
</table>

##### **US38 - Visualizar datos de rendimiento del equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US38</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar datos de rendimiento del equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar el rendimiento de los equipos a lo largo del tiempo para evaluar su funcionamiento.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen datos de rendimiento</b><br>
      <b>Given</b> que existen datos históricos del equipo disponibles<br>
      <b>When</b> el usuario solicita información sobre el rendimiento del equipo<br>
      <b>Then</b> el sistema proporciona los datos de rendimiento disponibles.<br><br>
      <b>Scenario 2: No existen datos de rendimiento</b><br>
      <b>Given</b> que no existen datos de rendimiento disponibles<br>
      <b>When</b> el usuario solicita información sobre el rendimiento del equipo<br>
      <b>Then</b> el sistema indica que no hay datos de rendimiento disponibles.
    </td>
  </tr>
</table>

##### **US39 - Visualizar datos de uso del equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US39</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar datos de uso del equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar datos de uso de los equipos para gestionar los recursos monitoreados.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen datos de uso</b><br>
      <b>Given</b> que existen datos de uso del equipo disponibles<br>
      <b>When</b> el usuario solicita información de uso<br>
      <b>Then</b> el sistema proporciona los datos de uso disponibles.<br><br>
      <b>Scenario 2: No existen datos de uso</b><br>
      <b>Given</b> que no existen datos de uso disponibles<br>
      <b>When</b> el usuario solicita información de uso<br>
      <b>Then</b> el sistema indica que no hay datos de uso disponibles.
    </td>
  </tr>
</table>

##### **US40 - Registrar mantenimiento**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US40</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Registrar mantenimiento</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero registrar información de mantenimiento de los equipos para conservar su historial de mantenimiento.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se proporciona información válida de mantenimiento</b><br>
      <b>Given</b> que se proporciona información válida de mantenimiento para un equipo registrado<br>
      <b>When</b> el usuario registra el mantenimiento<br>
      <b>Then</b> el sistema almacena la información de mantenimiento.<br><br>
      <b>Scenario 2: La información de mantenimiento está incompleta</b><br>
      <b>Given</b> que falta información requerida de mantenimiento<br>
      <b>When</b> el usuario intenta registrar el mantenimiento<br>
      <b>Then</b> el sistema rechaza el registro.
    </td>
  </tr>
</table>

##### **US41 - Visualizar historial de mantenimiento**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US41</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar historial de mantenimiento</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar el historial de mantenimiento de un equipo para revisar los mantenimientos realizados previamente.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen registros de mantenimiento</b><br>
      <b>Given</b> que se han registrado mantenimientos para un equipo<br>
      <b>When</b> el usuario solicita su historial de mantenimiento<br>
      <b>Then</b> el sistema proporciona los registros de mantenimiento disponibles.<br><br>
      <b>Scenario 2: No existen registros de mantenimiento</b><br>
      <b>Given</b> que no se han registrado mantenimientos<br>
      <b>When</b> el usuario solicita el historial de mantenimiento<br>
      <b>Then</b> el sistema indica que no hay registros de mantenimiento disponibles.
    </td>
  </tr>
</table>

##### **US42 - Visualizar confiabilidad del equipo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US42</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP05</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar confiabilidad del equipo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar la estabilidad de un equipo a lo largo del tiempo para evaluar su confiabilidad.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen datos históricos del equipo</b><br>
      <b>Given</b> que existen datos históricos del equipo disponibles<br>
      <b>When</b> el usuario solicita información de confiabilidad<br>
      <b>Then</b> el sistema proporciona la información de estabilidad disponible a lo largo del tiempo.<br><br>
      <b>Scenario 2: No existen datos históricos del equipo</b><br>
      <b>Given</b> que no existen datos históricos del equipo disponibles<br>
      <b>When</b> el usuario solicita información de confiabilidad<br>
      <b>Then</b> el sistema indica que la información de confiabilidad no está disponible.
    </td>
  </tr>
</table>

##### **US43 - Visualizar dashboard**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US43</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP06</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar dashboard</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar la información clave de SafeLab para comprender el estado actual del monitoreo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: La información del sistema está disponible</b><br>
      <b>Given</b> que SafeLab contiene información de monitoreo<br>
      <b>When</b> el usuario solicita la vista general del sistema<br>
      <b>Then</b> el sistema proporciona la información clave de monitoreo disponible.<br><br>
      <b>Scenario 2: La información del sistema no está disponible</b><br>
      <b>Given</b> que actualmente no existe información de monitoreo disponible<br>
      <b>When</b> el usuario solicita la vista general del sistema<br>
      <b>Then</b> el sistema indica que no hay información de monitoreo disponible.
    </td>
  </tr>
</table>

##### **US44 - Visualizar alertas críticas**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US44</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP06</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar alertas críticas</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las alertas críticas para priorizar las situaciones que requieren atención.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen alertas críticas</b><br>
      <b>Given</b> que existen alertas clasificadas como críticas<br>
      <b>When</b> el usuario solicita las alertas críticas<br>
      <b>Then</b> el sistema proporciona las alertas críticas disponibles.<br><br>
      <b>Scenario 2: No existen alertas críticas</b><br>
      <b>Given</b> que no existen alertas clasificadas como críticas<br>
      <b>When</b> el usuario solicita las alertas críticas<br>
      <b>Then</b> el sistema indica que no hay alertas críticas disponibles.
    </td>
  </tr>
</table>

##### **US45 - Visualizar resumen con totales**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US45</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP06</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar resumen con totales</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar un resumen de equipos y alertas para obtener una visión general del entorno monitoreado.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe información para el resumen</b><br>
      <b>Given</b> que existe información de equipos o alertas disponible<br>
      <b>When</b> el usuario solicita el resumen de monitoreo<br>
      <b>Then</b> el sistema proporciona los totales disponibles.<br><br>
      <b>Scenario 2: No existe información para el resumen</b><br>
      <b>Given</b> que no existe información de equipos ni alertas disponible<br>
      <b>When</b> el usuario solicita el resumen de monitoreo<br>
      <b>Then</b> el sistema indica que la información del resumen no está disponible.
    </td>
  </tr>
</table>

##### **US46 - Visualizar equipos con alertas activas**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US46</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP06</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar equipos con alertas activas</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero identificar los equipos con alertas activas para concentrarme en aquellos que presentan problemas detectados.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen equipos con alertas activas</b><br>
      <b>Given</b> que existen equipos registrados con alertas activas<br>
      <b>When</b> el usuario solicita los equipos con alertas activas<br>
      <b>Then</b> el sistema proporciona los equipos correspondientes.<br><br>
      <b>Scenario 2: Ningún equipo tiene alertas activas</b><br>
      <b>Given</b> que ningún equipo registrado tiene alertas activas<br>
      <b>When</b> el usuario solicita los equipos con alertas activas<br>
      <b>Then</b> el sistema indica que no hay equipos afectados disponibles.
    </td>
  </tr>
</table>

##### **US48 - Visualizar tendencias de alertas**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US48</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP06</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar tendencias de alertas</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las tendencias de las alertas para analizar su comportamiento a lo largo del tiempo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe historial de alertas</b><br>
      <b>Given</b> que existe información histórica de alertas disponible<br>
      <b>When</b> el usuario solicita las tendencias de alertas<br>
      <b>Then</b> el sistema proporciona información de tendencias utilizando el historial de alertas disponible.<br><br>
      <b>Scenario 2: No existe historial de alertas</b><br>
      <b>Given</b> que no existe información histórica de alertas disponible<br>
      <b>When</b> el usuario solicita las tendencias de alertas<br>
      <b>Then</b> el sistema indica que la información de tendencias no está disponible.
    </td>
  </tr>
</table>

##### **US49 - Visualizar tendencias de temperatura**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US49</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP06</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar tendencias de temperatura</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las tendencias de temperatura para analizar sus cambios a lo largo del tiempo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe historial de temperatura</b><br>
      <b>Given</b> que existen datos históricos de temperatura disponibles<br>
      <b>When</b> el usuario solicita las tendencias de temperatura<br>
      <b>Then</b> el sistema proporciona información de tendencias utilizando los datos históricos disponibles.<br><br>
      <b>Scenario 2: No existe historial de temperatura</b><br>
      <b>Given</b> que los datos históricos de temperatura no están disponibles<br>
      <b>When</b> el usuario solicita las tendencias de temperatura<br>
      <b>Then</b> el sistema indica que la información de tendencias de temperatura no está disponible.
    </td>
  </tr>
</table>

##### **US50 - Visualizar tendencias de humedad**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US50</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP06</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar tendencias de humedad</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las tendencias de humedad para analizar sus cambios a lo largo del tiempo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe historial de humedad</b><br>
      <b>Given</b> que existen datos históricos de humedad disponibles<br>
      <b>When</b> el usuario solicita las tendencias de humedad<br>
      <b>Then</b> el sistema proporciona información de tendencias utilizando los datos históricos disponibles.<br><br>
      <b>Scenario 2: No existe historial de humedad</b><br>
      <b>Given</b> que los datos históricos de humedad no están disponibles<br>
      <b>When</b> el usuario solicita las tendencias de humedad<br>
      <b>Then</b> el sistema indica que la información de tendencias de humedad no está disponible.
    </td>
  </tr>
</table>

##### **US51 - Iniciar sesión con una cuenta de Google**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US51</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP07</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Iniciar sesión con una cuenta de Google</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero iniciar sesión utilizando una cuenta de Google para acceder a SafeLab.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: La autenticación es exitosa</b><br>
      <b>Given</b> que se proporciona información válida de autenticación de Google<br>
      <b>When</b> el usuario solicita acceso a SafeLab<br>
      <b>Then</b> el sistema concede acceso a la cuenta correspondiente.<br><br>
      <b>Scenario 2: La autenticación no es exitosa</b><br>
      <b>Given</b> que la autenticación de Google no puede validarse<br>
      <b>When</b> el usuario solicita acceso a SafeLab<br>
      <b>Then</b> el sistema no concede el acceso.
    </td>
  </tr>
</table>

##### **US52 - Iniciar sesión con correo electrónico y contraseña**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US52</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP07</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Iniciar sesión con correo electrónico y contraseña</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero iniciar sesión utilizando correo electrónico y contraseña para acceder a mi cuenta de SafeLab.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Las credenciales son válidas</b><br>
      <b>Given</b> que se proporcionan credenciales válidas de la cuenta<br>
      <b>When</b> el usuario solicita acceso<br>
      <b>Then</b> el sistema concede acceso a la cuenta correspondiente.<br><br>
      <b>Scenario 2: Las credenciales son inválidas</b><br>
      <b>Given</b> que se proporcionan credenciales inválidas de la cuenta<br>
      <b>When</b> el usuario solicita acceso<br>
      <b>Then</b> el sistema no concede el acceso.
    </td>
  </tr>
</table>

##### **US53 - Recuperar contraseña por correo electrónico**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US53</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP07</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Recuperar contraseña por correo electrónico</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recuperar el acceso a mi cuenta mediante correo electrónico para volver a ingresar cuando no pueda utilizar mi contraseña.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se proporciona un correo electrónico registrado</b><br>
      <b>Given</b> que el correo electrónico proporcionado pertenece a una cuenta registrada<br>
      <b>When</b> el usuario solicita la recuperación de contraseña<br>
      <b>Then</b> el sistema inicia el proceso de recuperación de contraseña para dicho correo electrónico.<br><br>
      <b>Scenario 2: Se proporciona un correo electrónico no registrado</b><br>
      <b>Given</b> que el correo electrónico proporcionado no pertenece a una cuenta registrada<br>
      <b>When</b> se solicita la recuperación de contraseña<br>
      <b>Then</b> el sistema no inicia la recuperación para una cuenta que no existe.
    </td>
  </tr>
</table>

##### **US54 - Cerrar sesión en el sistema**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US54</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP07</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Cerrar sesión en el sistema</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero cerrar sesión para finalizar mi sesión activa en SafeLab.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe una sesión activa</b><br>
      <b>Given</b> que el usuario tiene una sesión activa<br>
      <b>When</b> el usuario solicita cerrar sesión<br>
      <b>Then</b> el sistema finaliza la sesión activa.<br><br>
      <b>Scenario 2: La sesión ya no está activa</b><br>
      <b>Given</b> que la sesión del usuario ya expiró<br>
      <b>When</b> se solicita acceso a información protegida<br>
      <b>Then</b> el sistema requiere autenticación nuevamente.
    </td>
  </tr>
</table>

##### **US55 - Asignar rol de usuario**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US55</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP07</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Asignar rol de usuario</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica con responsabilidad de gestión de usuarios, quiero asignar roles para que los usuarios registrados tengan los accesos correspondientes.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe un usuario registrado</b><br>
      <b>Given</b> que existe un usuario registrado<br>
      <b>When</b> un usuario autorizado asigna un rol válido<br>
      <b>Then</b> el sistema asocia el rol con dicho usuario.<br><br>
      <b>Scenario 2: El usuario solicitado no existe</b><br>
      <b>Given</b> que el usuario solicitado no está registrado<br>
      <b>When</b> se solicita una asignación de rol<br>
      <b>Then</b> el sistema rechaza la asignación.
    </td>
  </tr>
</table>

##### **US56 - Visualizar la Landing Page de SafeLab**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US56</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP08</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar la Landing Page de SafeLab</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero acceder a la Landing Page de SafeLab para conocer el producto.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: La Landing Page está disponible</b><br>
      <b>Given</b> que la Landing Page de SafeLab está disponible públicamente<br>
      <b>When</b> un visitante accede a ella<br>
      <b>Then</b> el sitio proporciona la información disponible del producto SafeLab.<br><br>
      <b>Scenario 2: El recurso solicitado de la Landing Page no está disponible</b><br>
      <b>Given</b> que un recurso solicitado de la Landing Page no puede obtenerse<br>
      <b>When</b> el visitante accede a dicho recurso<br>
      <b>Then</b> el sitio no presenta contenido inválido como si fuera información disponible.
    </td>
  </tr>
</table>

##### **US57 - Cambiar el idioma de la Landing Page**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US57</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP08</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Cambiar el idioma de la Landing Page</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero acceder al contenido de la Landing Page en los idiomas soportados para comprender la información presentada.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se selecciona un idioma soportado</b><br>
      <b>Given</b> que la Landing Page soporta inglés (en_US) y español latinoamericano (es_419)<br>
      <b>When</b> el visitante selecciona un idioma soportado<br>
      <b>Then</b> el contenido disponible de la Landing Page se proporciona en el idioma seleccionado.<br><br>
      <b>Scenario 2: No se selecciona un idioma alternativo</b><br>
      <b>Given</b> que el visitante no ha seleccionado otro idioma soportado<br>
      <b>When</b> se accede a la Landing Page<br>
      <b>Then</b> el contenido se proporciona en inglés (en_US), que es el idioma predeterminado.
    </td>
  </tr>
</table>

##### **US58 - Acceder a los Términos y Condiciones**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US58</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP08</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Acceder a los Términos y Condiciones</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero acceder a los Términos y Condiciones de SafeLab para revisar las condiciones asociadas al servicio.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se solicitan los Términos y Condiciones desde la Landing Page</b><br>
      <b>Given</b> que los Términos y Condiciones de SafeLab están disponibles<br>
      <b>When</b> un visitante los solicita desde la Landing Page<br>
      <b>Then</b> el sitio proporciona los Términos y Condiciones.<br><br>
      <b>Scenario 2: Se solicitan los Términos y Condiciones durante el registro de una cuenta</b><br>
      <b>Given</b> que un usuario está registrando una cuenta de SafeLab<br>
      <b>When</b> se solicitan los Términos y Condiciones<br>
      <b>Then</b> la aplicación proporciona acceso a los Términos y Condiciones.
    </td>
  </tr>
</table>

##### **US59 - Registrar cuenta de usuario**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US59</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Personal de Laboratorio Hospitalario / Empresa Farmacéutica</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP07</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Registrar cuenta de usuario</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero registrar una cuenta de SafeLab para acceder al servicio.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se proporciona información válida de registro</b><br>
      <b>Given</b> que la información requerida de la cuenta es válida<br>
      <b>When</b> el usuario solicita el registro de la cuenta<br>
      <b>Then</b> el sistema crea la cuenta.<br><br>
      <b>Scenario 2: La información requerida de registro es inválida o está incompleta</b><br>
      <b>Given</b> que la información requerida de la cuenta es inválida o está incompleta<br>
      <b>When</b> el usuario solicita el registro de la cuenta<br>
      <b>Then</b> el sistema rechaza el registro de la cuenta.
    </td>
  </tr>
</table>

##### **US60 - Proporcionar servicios de organización del monitoreo**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US60</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Developer</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP01</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de organización del monitoreo</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como Developer, quiero que la RESTful API proporcione operaciones para sitios de monitoreo, áreas de almacenamiento y equipos, de modo que las aplicaciones de SafeLab puedan utilizar la información correspondiente a la organización del monitoreo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se recibe una solicitud válida</b><br>
      <b>Given</b> que se recibe una solicitud válida de datos soportados para la organización del monitoreo<br>
      <b>When</b> el servicio RESTful procesa la solicitud<br>
      <b>Then</b> el servicio devuelve la respuesta exitosa correspondiente.<br><br>
      <b>Scenario 2: El recurso solicitado no existe</b><br>
      <b>Given</b> que el recurso solicitado de organización del monitoreo no existe<br>
      <b>When</b> el servicio RESTful procesa la solicitud<br>
      <b>Then</b> el servicio devuelve una respuesta indicando que el recurso no fue encontrado.
    </td>
  </tr>
</table>

##### **US61 - Proporcionar servicios de monitoreo ambiental**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US61</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Developer</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de monitoreo ambiental</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como Developer, quiero que la RESTful API proporcione datos de monitoreo ambiental para que las aplicaciones de SafeLab puedan consumir información de temperatura, humedad y estado de los equipos.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existen datos de monitoreo</b><br>
      <b>Given</b> que existe información de monitoreo disponible para el equipo solicitado<br>
      <b>When</b> se procesa una solicitud válida<br>
      <b>Then</b> el servicio devuelve la información de monitoreo disponible.<br><br>
      <b>Scenario 2: El equipo solicitado no existe</b><br>
      <b>Given</b> que el equipo solicitado no está registrado<br>
      <b>When</b> se procesa una solicitud de monitoreo<br>
      <b>Then</b> el servicio devuelve una respuesta indicando que el equipo no fue encontrado.
    </td>
  </tr>
</table>

##### **US62 - Proporcionar servicios de alertas e incidentes**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US62</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Developer</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP03</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de alertas e incidentes</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como Developer, quiero que la RESTful API proporcione información de alertas e incidentes para que las aplicaciones de SafeLab puedan utilizar las alertas generadas y sus estados.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se recibe una solicitud válida de alerta</b><br>
      <b>Given</b> que existe la información de la alerta solicitada<br>
      <b>When</b> el servicio RESTful procesa una solicitud válida<br>
      <b>Then</b> el servicio devuelve la información correspondiente de la alerta.<br><br>
      <b>Scenario 2: La alerta solicitada no existe</b><br>
      <b>Given</b> que la alerta solicitada no está disponible<br>
      <b>When</b> el servicio RESTful procesa la solicitud<br>
      <b>Then</b> el servicio devuelve una respuesta indicando que la alerta no fue encontrada.
    </td>
  </tr>
</table>

##### **US63 - Proporcionar servicios de datos históricos y reportes**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US63</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Developer</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Media</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP04</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de datos históricos y reportes</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como Developer, quiero que la RESTful API proporcione datos históricos de monitoreo e información de reportes para que las aplicaciones de SafeLab puedan soportar funcionalidades de análisis y generación de reportes.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Existe la información histórica solicitada</b><br>
      <b>Given</b> que existe información histórica de monitoreo para una solicitud válida<br>
      <b>When</b> el servicio RESTful procesa la solicitud<br>
      <b>Then</b> el servicio devuelve la información histórica disponible.<br><br>
      <b>Scenario 2: La información histórica no está disponible</b><br>
      <b>Given</b> que no existe información para los criterios solicitados<br>
      <b>When</b> el servicio RESTful procesa la solicitud<br>
      <b>Then</b> el servicio devuelve una respuesta indicando que no hay información correspondiente disponible.
    </td>
  </tr>
</table>

##### **US64 - Proporcionar servicios de acceso de usuario**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US64</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Developer</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP07</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de acceso de usuario</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como Developer, quiero que la RESTful API soporte operaciones de cuenta y acceso de SafeLab para que las aplicaciones móviles puedan utilizar las capacidades de acceso de usuario requeridas.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se recibe una solicitud válida de acceso</b><br>
      <b>Given</b> que se proporciona información válida de la cuenta<br>
      <b>When</b> el servicio RESTful procesa una solicitud de acceso soportada<br>
      <b>Then</b> el servicio devuelve la respuesta exitosa correspondiente.<br><br>
      <b>Scenario 2: Se proporciona información inválida de la cuenta</b><br>
      <b>Given</b> que la información proporcionada de la cuenta no puede validarse<br>
      <b>When</b> el servicio RESTful procesa la solicitud<br>
      <b>Then</b> el servicio devuelve una respuesta indicando que la operación no puede completarse.
    </td>
  </tr>
</table>

##### **US65 - Soportar almacenamiento local de datos en el dispositivo móvil**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Story ID</th><td style="text-align: center; vertical-align: top; padding: 6px;">US65</td><th style="text-align: center; vertical-align: middle; padding: 6px;">User</th><td style="text-align: center; vertical-align: top; padding: 6px;">Developer</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Priority</th><td style="text-align: center; vertical-align: top; padding: 6px;">Alta</td><th style="text-align: center; vertical-align: middle; padding: 6px;">Epic</th><td style="text-align: center; vertical-align: top; padding: 6px;">EP02</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Soportar almacenamiento local de datos en el dispositivo móvil</td></tr>
  <tr><th style="text-align: center; vertical-align: middle; padding: 6px;">Description</th><td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">Como Developer, quiero que la aplicación móvil soporte el almacenamiento local de información seleccionada de SafeLab para persistir y recuperar información de monitoreo en el dispositivo.</td></tr>
  <tr>
    <th style="text-align: center; vertical-align: middle; padding: 6px;">Acceptance Criteria</th>
    <td colspan="3" style="text-align: justify; vertical-align: top; padding: 6px;">
      <b>Scenario 1: Se selecciona información para persistencia local</b><br>
      <b>Given</b> que se ha definido información de SafeLab para almacenamiento local<br>
      <b>When</b> la aplicación móvil almacena dicha información<br>
      <b>Then</b> la información permanece persistida en el dispositivo de acuerdo con el comportamiento de almacenamiento definido.<br><br>
      <b>Scenario 2: Se solicita información almacenada</b><br>
      <b>Given</b> que se ha almacenado localmente información seleccionada de SafeLab<br>
      <b>When</b> la aplicación móvil solicita la información almacenada<br>
      <b>Then</b> la información persistida localmente puede recuperarse.
    </td>
  </tr>
</table>

<br>

#### **Spike Stories**

##### **SP01 - Investigar opciones de integración para autenticación con Google**

<p style="text-align: justify;">
  <b>Context:</b> SafeLab incluye el inicio de sesión con una cuenta de Google mediante la US51 - Iniciar sesión con una cuenta de Google. La solución móvil contempla aplicaciones nativas y cross-platform que interactúan con servicios RESTful desarrollados internamente. Antes de desarrollar el flujo completo de autenticación, el equipo de desarrollo necesita evaluar el enfoque de integración, la compatibilidad móvil, los requisitos del backend y las consideraciones técnicas necesarias para validar a los usuarios autenticados.
</p>

<p style="text-align: justify;">
  <b>Spike Story:</b><br>
  Como equipo de desarrollo,<br>
  queremos investigar y prototipar la integración de autenticación con una cuenta de Google en las aplicaciones móviles y los servicios RESTful de SafeLab,<br>
  para comprender los requisitos técnicos, dependencias, riesgos y esfuerzo requeridos antes de implementar la US51 - Iniciar sesión con una cuenta de Google.
</p>

<p style="text-align: justify;">
  <b>Acceptance Criteria:</b>
</p>

<p style="text-align: justify;">
  <b>Scenario 1: Se revisa la documentación oficial de autenticación</b><br>
  <b>Given</b> que SafeLab requiere que los usuarios se autentiquen mediante una cuenta de Google<br>
  <b>When</b> el Developer revisa la documentación oficial relacionada con la autenticación de Google<br>
  <b>Then</b> se documentan el flujo de autenticación, las configuraciones requeridas y los principales requisitos de integración.
</p>

<p style="text-align: justify;">
  <b>Scenario 2: Se evalúa la compatibilidad con la aplicación móvil nativa</b><br>
  <b>Given</b> que SafeLab debe incluir una aplicación móvil nativa<br>
  <b>When</b> el Developer evalúa la integración de autenticación para la implementación nativa<br>
  <b>Then</b> se documentan la configuración requerida, las dependencias y el flujo de autenticación.
</p>

<p style="text-align: justify;">
  <b>Scenario 3: Se evalúa la compatibilidad cross-platform</b><br>
  <b>Given</b> que SafeLab también debe incluir una aplicación móvil cross-platform<br>
  <b>When</b> el Developer evalúa la integración de autenticación para la implementación cross-platform<br>
  <b>Then</b> se documentan los requisitos de compatibilidad y las diferencias de integración identificadas.
</p>

<p style="text-align: justify;">
  <b>Scenario 4: Se evalúan los requisitos de autenticación del backend</b><br>
  <b>Given</b> que SafeLab utiliza servicios RESTful desarrollados internamente<br>
  <b>When</b> el Developer analiza cómo debe validarse en el backend la información de un usuario autenticado<br>
  <b>Then</b> se documenta la interacción requerida entre la aplicación móvil y los servicios RESTful.
</p>

<p style="text-align: justify;">
  <b>Scenario 5: Se identifican las consideraciones de seguridad</b><br>
  <b>Given</b> que la autenticación proporciona acceso a información y funcionalidades de los usuarios de SafeLab<br>
  <b>When</b> el Developer analiza el flujo de autenticación<br>
  <b>Then</b> se documentan las principales consideraciones de seguridad y los pasos de validación requeridos.
</p>

<p style="text-align: justify;">
  <b>Scenario 6: Se prototipa la integración de autenticación</b><br>
  <b>Given</b> que se ha seleccionado un enfoque de integración para su evaluación<br>
  <b>When</b> el Developer crea un Proof of Concept mínimo<br>
  <b>Then</b> el prototipo verifica si una cuenta de Google puede autenticarse y ser reconocida por SafeLab.
</p>

<p style="text-align: justify;">
  <b>Scenario 7: Se estima el esfuerzo de implementación</b><br>
  <b>Given</b> que se han identificado los requisitos y dependencias de autenticación<br>
  <b>When</b> el equipo de desarrollo revisa el trabajo requerido para la implementación completa<br>
  <b>Then</b> se documentan las principales tareas de implementación y una estimación aproximada del esfuerzo.
</p>

<p style="text-align: justify;">
  <b>Scenario 8: Se documentan y revisan los hallazgos</b><br>
  <b>Given</b> que la investigación y la validación técnica han finalizado<br>
  <b>When</b> el equipo de desarrollo revisa los hallazgos recopilados<br>
  <b>Then</b> se documentan el enfoque seleccionado, los requisitos, las dependencias, los riesgos y las consideraciones de implementación para el refinamiento de la US51.
</p>

<p style="text-align: justify;">
  <b>Definition of Done:</b><br>
  - Se revisó la documentación oficial de autenticación.<br>
  - Se documentaron los requisitos de integración nativa, cross-platform y de backend.<br>
  - Se identificaron las consideraciones de seguridad y las dependencias.<br>
  - Se completó un Proof of Concept mínimo de autenticación.<br>
  - Se estimó el esfuerzo de implementación.<br>
  - Los hallazgos fueron revisados por el equipo de desarrollo y utilizados para refinar la US51.
</p>

##### **SP02 - Investigar opciones de almacenamiento local para datos de monitoreo**

<p style="text-align: justify;">
  <b>Context:</b> SafeLab gestiona información de monitoreo ambiental, como temperatura, humedad y estado de los equipos, e incluye persistencia local mediante la US65 - Soportar almacenamiento local de datos en el dispositivo móvil. Antes de implementar el mecanismo completo de persistencia, el equipo de desarrollo necesita evaluar un enfoque adecuado de almacenamiento local y verificar que la información de monitoreo de SafeLab pueda almacenarse y recuperarse correctamente.
</p>

<p style="text-align: justify;">
  <b>Spike Story:</b><br>
  Como equipo de desarrollo,<br>
  queremos investigar y prototipar alternativas de almacenamiento local para los datos de monitoreo de SafeLab,<br>
  para seleccionar un enfoque de persistencia apropiado y comprender sus requisitos, limitaciones, dependencias y esfuerzo de implementación antes de desarrollar la US65.
</p>

<p style="text-align: justify;">
  <b>Acceptance Criteria:</b>
</p>

<p style="text-align: justify;">
  <b>Scenario 1: Se investigan alternativas de almacenamiento local</b><br>
  <b>Given</b> que SafeLab debe persistir determinada información de forma local en el dispositivo móvil<br>
  <b>When</b> el Developer investiga alternativas de almacenamiento compatibles con la solución móvil<br>
  <b>Then</b> se documentan las alternativas disponibles y sus principales características.
</p>

<p style="text-align: justify;">
  <b>Scenario 2: Se evalúa la compatibilidad con la aplicación móvil nativa</b><br>
  <b>Given</b> que SafeLab debe incluir una aplicación móvil nativa<br>
  <b>When</b> el Developer evalúa las alternativas candidatas de persistencia<br>
  <b>Then</b> se documentan su compatibilidad y sus requisitos de integración para la implementación nativa.
</p>

<p style="text-align: justify;">
  <b>Scenario 3: Se evalúa la compatibilidad cross-platform</b><br>
  <b>Given</b> que SafeLab debe incluir una aplicación móvil cross-platform<br>
  <b>When</b> el Developer evalúa las alternativas candidatas de persistencia<br>
  <b>Then</b> se documentan su compatibilidad y sus requisitos de integración para la implementación cross-platform.
</p>

<p style="text-align: justify;">
  <b>Scenario 4: Se define la información de monitoreo para el prototipo</b><br>
  <b>Given</b> que SafeLab gestiona información de temperatura, humedad y estado de los equipos<br>
  <b>When</b> el Developer define los datos requeridos para la prueba de persistencia<br>
  <b>Then</b> se documenta la información de monitoreo que utilizará el Proof of Concept.
</p>

<p style="text-align: justify;">
  <b>Scenario 5: Se prototipa la persistencia local</b><br>
  <b>Given</b> que se ha seleccionado un enfoque candidato de almacenamiento<br>
  <b>When</b> el Developer almacena en el dispositivo información de monitoreo de ejemplo de SafeLab<br>
  <b>Then</b> el prototipo verifica que la información seleccionada permanezca persistida localmente.
</p>

<p style="text-align: justify;">
  <b>Scenario 6: Se recupera la información de monitoreo almacenada</b><br>
  <b>Given</b> que la información de monitoreo de SafeLab ha sido persistida localmente<br>
  <b>When</b> el prototipo solicita la información almacenada<br>
  <b>Then</b> la información previamente almacenada puede recuperarse correctamente.
</p>

<p style="text-align: justify;">
  <b>Scenario 7: Se evalúa la persistencia después de reiniciar la aplicación</b><br>
  <b>Given</b> que la información de monitoreo ha sido almacenada localmente<br>
  <b>When</b> la aplicación se cierra y vuelve a iniciarse<br>
  <b>Then</b> el prototipo verifica si la información persistida continúa disponible.
</p>

<p style="text-align: justify;">
  <b>Scenario 8: Se documentan el esfuerzo de implementación y los hallazgos</b><br>
  <b>Given</b> que se han evaluado las alternativas de almacenamiento y el Proof of Concept<br>
  <b>When</b> el equipo de desarrollo revisa los resultados<br>
  <b>Then</b> se documentan el enfoque seleccionado, las dependencias, las limitaciones, las tareas de implementación y una estimación aproximada del esfuerzo para el refinamiento de la US65.
</p>

<p style="text-align: justify;">
  <b>Definition of Done:</b><br>
  - Se revisaron alternativas compatibles de almacenamiento local.<br>
  - Se documentaron los requisitos de integración nativa y cross-platform.<br>
  - Se identificó la información de monitoreo utilizada para la validación técnica.<br>
  - Un Proof of Concept mínimo almacena y recupera información de monitoreo de forma local.<br>
  - Se validó la persistencia después de reiniciar la aplicación.<br>
  - Se estimó el esfuerzo de implementación.<br>
  - Los hallazgos fueron revisados por el equipo de desarrollo y utilizados para refinar la US65.
</p>

##### **SP03 - Investigar opciones de entrega de alertas móviles**

<p style="text-align: justify;">
  <b>Context:</b> SafeLab incluye alertas relacionadas con temperatura, humedad y condiciones de los equipos, así como la recepción móvil de alertas mediante la US24 - Recibir alertas en un dispositivo móvil. Antes de implementar el mecanismo completo de entrega, el equipo de desarrollo necesita investigar cómo pueden comunicarse las alertas de SafeLab a los dispositivos móviles y cómo este proceso interactúa con las aplicaciones móviles y los servicios RESTful desarrollados internamente.
</p>

<p style="text-align: justify;">
  <b>Spike Story:</b><br>
  Como equipo de desarrollo,<br>
  queremos investigar y prototipar alternativas para la entrega de alertas móviles de SafeLab,<br>
  para seleccionar un enfoque adecuado y comprender sus requisitos técnicos, dependencias, riesgos y esfuerzo de implementación antes de desarrollar la US24.
</p>

<p style="text-align: justify;">
  <b>Acceptance Criteria:</b>
</p>

<p style="text-align: justify;">
  <b>Scenario 1: Se investigan alternativas de entrega de alertas</b><br>
  <b>Given</b> que SafeLab necesita comunicar las alertas generadas a los usuarios móviles<br>
  <b>When</b> el Developer investiga alternativas técnicamente viables para la entrega de alertas móviles<br>
  <b>Then</b> se documentan las alternativas disponibles y sus principales requisitos de integración.
</p>

<p style="text-align: justify;">
  <b>Scenario 2: Se evalúa la compatibilidad con la aplicación móvil nativa</b><br>
  <b>Given</b> que SafeLab debe incluir una aplicación móvil nativa<br>
  <b>When</b> el Developer evalúa las alternativas candidatas de entrega de alertas<br>
  <b>Then</b> se documentan su compatibilidad y los requisitos de configuración para la aplicación móvil nativa.
</p>

<p style="text-align: justify;">
  <b>Scenario 3: Se evalúa la compatibilidad cross-platform</b><br>
  <b>Given</b> que SafeLab debe incluir una aplicación móvil cross-platform<br>
  <b>When</b> el Developer evalúa las alternativas candidatas de entrega de alertas<br>
  <b>Then</b> se documentan su compatibilidad y los requisitos de configuración para la implementación cross-platform.
</p>

<p style="text-align: justify;">
  <b>Scenario 4: Se analiza la integración con las alertas de SafeLab</b><br>
  <b>Given</b> que SafeLab genera alertas a partir de las condiciones de temperatura, humedad y de los equipos<br>
  <b>When</b> el Developer analiza el proceso de entrega de alertas móviles<br>
  <b>Then</b> se documenta la interacción requerida entre las alertas generadas, los servicios RESTful y las aplicaciones móviles.
</p>

<p style="text-align: justify;">
  <b>Scenario 5: Se identifican las dependencias y configuraciones requeridas</b><br>
  <b>Given</b> que la entrega de alertas móviles puede requerir configuraciones o dependencias adicionales<br>
  <b>When</b> el Developer evalúa la alternativa seleccionada<br>
  <b>Then</b> se documentan las dependencias requeridas, los pasos de configuración y las limitaciones identificadas.
</p>

<p style="text-align: justify;">
  <b>Scenario 6: Se prototipa la entrega de alertas</b><br>
  <b>Given</b> que se ha seleccionado una alternativa de entrega de alertas para su evaluación<br>
  <b>When</b> el Developer genera y envía una alerta de prueba de SafeLab<br>
  <b>Then</b> el Proof of Concept verifica si la alerta puede entregarse a un dispositivo móvil.
</p>

<p style="text-align: justify;">
  <b>Scenario 7: Se estima el esfuerzo de implementación</b><br>
  <b>Given</b> que se han identificado los requisitos técnicos y las dependencias<br>
  <b>When</b> el equipo de desarrollo revisa el trabajo requerido para la entrega de alertas móviles<br>
  <b>Then</b> se documentan las principales tareas de implementación y una estimación aproximada del esfuerzo.
</p>

<p style="text-align: justify;">
  <b>Scenario 8: Se documentan y revisan los hallazgos</b><br>
  <b>Given</b> que la evaluación técnica ha finalizado<br>
  <b>When</b> el equipo de desarrollo revisa los resultados<br>
  <b>Then</b> se documentan el enfoque seleccionado, los requisitos de integración, las dependencias, las limitaciones, los riesgos y las consideraciones de implementación para el refinamiento de la US24.
</p>

<p style="text-align: justify;">
  <b>Definition of Done:</b><br>
  - Se evaluaron alternativas de entrega de alertas móviles.<br>
  - Se documentó la compatibilidad nativa y cross-platform.<br>
  - Se identificaron los requisitos de integración con las alertas de SafeLab y los servicios RESTful.<br>
  - Se completó un Proof of Concept mínimo utilizando una alerta de prueba de SafeLab.<br>
  - Se documentaron las dependencias técnicas, las limitaciones y los riesgos.<br>
  - Se estimó el esfuerzo de implementación.<br>
  - Los hallazgos fueron revisados por el equipo de desarrollo y utilizados para refinar la US24.
</p>

##### **SP04 - Investigar opciones de visualización de tendencias de monitoreo**

<p style="text-align: justify;">
  <b>Context:</b> SafeLab incluye el análisis de tendencias de alertas, temperatura y humedad mediante las US48 - Visualizar tendencias de alertas, US49 - Visualizar tendencias de temperatura y US50 - Visualizar tendencias de humedad. Estas funcionalidades utilizan información histórica de monitoreo para representar cambios a lo largo del tiempo. Antes de implementar las visualizaciones de tendencias en las aplicaciones móviles, el equipo de desarrollo necesita evaluar alternativas de visualización compatibles y validar cómo pueden representarse los datos históricos de monitoreo de SafeLab.
</p>

<p style="text-align: justify;">
  <b>Spike Story:</b><br>
  Como equipo de desarrollo,<br>
  queremos investigar y prototipar alternativas de visualización para las tendencias de monitoreo de SafeLab,<br>
  para seleccionar un enfoque adecuado que permita representar información histórica de alertas, temperatura y humedad antes de implementar las US48, US49 y US50.
</p>

<p style="text-align: justify;">
  <b>Acceptance Criteria:</b>
</p>

<p style="text-align: justify;">
  <b>Scenario 1: Se investigan alternativas de visualización</b><br>
  <b>Given</b> que SafeLab necesita representar información histórica de alertas, temperatura y humedad<br>
  <b>When</b> el Developer investiga alternativas de visualización compatibles con la solución móvil<br>
  <b>Then</b> se documentan las alternativas disponibles y sus principales características.
</p>

<p style="text-align: justify;">
  <b>Scenario 2: Se evalúa la compatibilidad con la aplicación móvil nativa</b><br>
  <b>Given</b> que SafeLab debe incluir una aplicación móvil nativa<br>
  <b>When</b> el Developer evalúa las alternativas candidatas de visualización<br>
  <b>Then</b> se documentan su compatibilidad y los requisitos de integración para la implementación nativa.
</p>

<p style="text-align: justify;">
  <b>Scenario 3: Se evalúa la compatibilidad cross-platform</b><br>
  <b>Given</b> que SafeLab debe incluir una aplicación móvil cross-platform<br>
  <b>When</b> el Developer evalúa las alternativas candidatas de visualización<br>
  <b>Then</b> se documentan su compatibilidad y los requisitos de integración para la implementación cross-platform.
</p>

<p style="text-align: justify;">
  <b>Scenario 4: Se evalúan los datos históricos de SafeLab</b><br>
  <b>Given</b> que SafeLab almacena información histórica relacionada con alertas, temperatura y humedad<br>
  <b>When</b> el Developer analiza los datos requeridos por las funcionalidades de tendencias<br>
  <b>Then</b> se documenta la información requerida para el prototipo de visualización.
</p>

<p style="text-align: justify;">
  <b>Scenario 5: Se prototipa la visualización de tendencias de temperatura</b><br>
  <b>Given</b> que existen datos históricos de temperatura disponibles para la validación técnica<br>
  <b>When</b> el Developer utiliza la alternativa de visualización seleccionada<br>
  <b>Then</b> el prototipo representa la información de temperatura a lo largo del periodo evaluado.
</p>

<p style="text-align: justify;">
  <b>Scenario 6: Se valida la visualización de tendencias de humedad y alertas</b><br>
  <b>Given</b> que existen datos históricos de humedad y alertas disponibles para la validación técnica<br>
  <b>When</b> el Developer utiliza la alternativa de visualización seleccionada<br>
  <b>Then</b> el prototipo verifica que la información histórica requerida también pueda representarse.
</p>

<p style="text-align: justify;">
  <b>Scenario 7: Se estima el esfuerzo de implementación</b><br>
  <b>Given</b> que se han evaluado las alternativas candidatas de visualización<br>
  <b>When</b> el equipo de desarrollo compara sus requisitos de implementación<br>
  <b>Then</b> se documentan las principales tareas de implementación y una estimación aproximada del esfuerzo.
</p>

<p style="text-align: justify;">
  <b>Scenario 8: Se documentan y revisan los hallazgos</b><br>
  <b>Given</b> que el prototipo de visualización ha sido evaluado<br>
  <b>When</b> el equipo de desarrollo revisa los resultados<br>
  <b>Then</b> se documentan el enfoque seleccionado, los requisitos, las limitaciones y las consideraciones de implementación para el refinamiento de las US48, US49 y US50.
</p>

<p style="text-align: justify;">
  <b>Definition of Done:</b><br>
  - Se evaluaron alternativas de visualización compatibles.<br>
  - Se documentaron los requisitos de integración nativa y cross-platform.<br>
  - Se identificó la información histórica requerida para el prototipo.<br>
  - Se completó un prototipo mínimo de visualización de tendencias.<br>
  - La información de temperatura, humedad y alertas puede representarse en la validación técnica.<br>
  - Se estimó el esfuerzo de implementación.<br>
  - Los hallazgos fueron revisados por el equipo de desarrollo y utilizados para refinar las US48, US49 y US50.
</p>

### **2.4.2. Impact Mapping**

<p style="text-align: justify;">
  El Impact Mapping de SafeLab conecta los objetivos de negocio del producto digital con el comportamiento esperado de sus User Personas, los Deliverables que respaldan dichos comportamientos y las User Stories que permiten su implementación.
</p>

<p style="text-align: justify;">
  El primer objetivo de negocio se enfoca en reducir el tiempo requerido por el personal de laboratorio para consultar información actualizada de temperatura, humedad y estado de los equipos. Para contribuir con este objetivo, se espera que el User Persona supervise continuamente las condiciones ambientales e identifique con rapidez las interrupciones o condiciones anómalas de los equipos monitoreados. Estos impactos se respaldan mediante capacidades de monitoreo ambiental en tiempo real y detección de problemas de monitoreo.
</p>

<p style="text-align: justify;">
  El segundo objetivo de negocio se orienta a asegurar que las alertas ambientales generadas en SafeLab sean revisadas y confirmadas dentro de un tiempo de respuesta adecuado. Para contribuir con este objetivo, se espera que el User Persona del segmento farmacéutico revise rápidamente las alertas generadas, comprenda los incidentes detectados, priorice las alertas críticas y registre aquellas que ya fueron atendidas. Estos impactos se respaldan mediante capacidades de consulta, seguimiento, priorización y gestión de alertas.
</p>

<p align="center">
  <img src="../assets/07-chapter-2/requirements-specification/impact-mapping/impact-map-safelab.png" alt="Impact Mapping de SafeLab" width="95%">
</p>

<p align="center">
  <b>Figura X. Impact Mapping de SafeLab.</b><br>
  <i>Fuente: Elaboración propia utilizando UXPressia.</i>
</p>

### **2.4.3. Product Backlog**

<p style="text-align: justify;">
  El siguiente Product Backlog organiza las User Stories de SafeLab según su prioridad de negocio, estimación en Story Points y Sprint planificado. La secuencia considera primero las funcionalidades vinculadas con el monitoreo ambiental, la detección de desviaciones y la organización básica del entorno monitoreado; posteriormente incorpora funcionalidades móviles, históricas, de autenticación, análisis y mantenimiento.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;"># Order</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">User Story ID</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Title</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Story Points</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Sprint</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">1</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US16</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Recolección automática de datos</td><td style="text-align: center; vertical-align: middle; padding: 6px;">8</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US09</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar valores de temperatura</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US10</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar valores de humedad</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">4</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US13</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar lista de equipos con datos en tiempo real</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US18</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Recibir alertas de temperatura</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">6</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US19</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Recibir alertas de humedad</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">7</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US20</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar lista de alertas</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">8</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US15</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Identificar equipos sin datos recientes</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">9</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US05</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Registrar equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">10</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US07</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Asignar equipo a un área</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">11</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US03</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Crear área de almacenamiento</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">12</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US01</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Registrar sitio de monitoreo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">13</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US56</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar la Landing Page de SafeLab</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">14</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US57</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Cambiar el idioma de la Landing Page</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">15</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US58</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Acceder a los Términos y Condiciones</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">16</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US61</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de monitoreo ambiental</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">17</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US60</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de organización del monitoreo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">8</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">18</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US62</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de alertas e incidentes</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">19</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US11</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar estado operativo del equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">20</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US12</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar detalles del equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">21</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US02</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar sitios de monitoreo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">22</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US04</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar áreas de almacenamiento</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">23</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US06</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar lista de equipos</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">24</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US08</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Buscar equipo por nombre</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">25</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US14</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Filtrar equipos por área de almacenamiento</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 1</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">26</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US25</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Configurar límites de alerta por equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">27</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US24</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Recibir alertas en un dispositivo móvil</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">28</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US21</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar detalles de una alerta</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">29</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US22</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Confirmar atención de una alerta</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">30</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US23</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar alertas ordenadas por severidad</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">31</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US44</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar alertas críticas</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">32</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US46</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar equipos con alertas activas</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">33</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US36</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar valores anómalos</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">34</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US37</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Recibir alertas de advertencia del equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">35</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US17</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar datos en dispositivo móvil</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">36</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US65</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Soportar almacenamiento local de datos en el dispositivo móvil</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">37</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US43</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar dashboard</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">38</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US45</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar resumen con totales</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">39</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US27</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar datos históricos</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">40</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US28</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Seleccionar un rango de fechas para los datos</td><td style="text-align: center; vertical-align: middle; padding: 6px;">2</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">41</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US30</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Generar reporte por equipo y fecha</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">42</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US31</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Descargar archivo de reporte</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">43</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US63</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de datos históricos y reportes</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">44</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US59</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Registrar cuenta de usuario</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">45</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US52</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Iniciar sesión con correo electrónico y contraseña</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">46</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US51</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Iniciar sesión con una cuenta de Google</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">47</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US64</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Proporcionar servicios de acceso de usuario</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 2</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">48</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US29</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Comparar datos entre periodos</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">49</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US32</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar historial de incidentes</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">50</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US33</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Exportar archivo de datos</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">51</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US34</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Comparar datos semanales y mensuales</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">52</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US48</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar tendencias de alertas</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">53</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US49</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar tendencias de temperatura</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">54</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US50</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar tendencias de humedad</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">55</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US35</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar condición del equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">56</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US40</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Registrar mantenimiento</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">57</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US41</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar historial de mantenimiento</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">58</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US42</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar confiabilidad del equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">5</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">59</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US38</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar datos de rendimiento del equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">60</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US39</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualizar datos de uso del equipo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">61</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US26</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Compartir alertas con el equipo de trabajo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">62</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US53</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Recuperar contraseña por correo electrónico</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">63</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US54</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Cerrar sesión en el sistema</td><td style="text-align: center; vertical-align: middle; padding: 6px;">1</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
    <tr><td style="text-align: center; vertical-align: middle; padding: 6px;">64</td><td style="text-align: center; vertical-align: middle; padding: 6px;">US55</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Asignar rol de usuario</td><td style="text-align: center; vertical-align: middle; padding: 6px;">3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Sprint 3</td></tr>
  </tbody>
</table>

## **2.5. Strategic-Level Domain-Driven Design**

### **2.5.1. Event Storming**

#### **2.5.1.1. Candidate Context Discovery**

#### **2.5.1.2. Domain Message Flows Modeling**

#### **2.5.1.3. Bounded Context Canvases**

### **2.5.2. Context Mapping**

### **2.5.3. Software Architecture**

#### **2.5.3.1. Software Architecture Context Level Diagrams**

#### **2.5.3.2. Software Architecture Container Level Diagrams**

#### **2.5.3.3. Software Architecture Deployment Diagrams**

## **2.6. Tactical-Level Domain-Driven Design**

### **2.6.x. Bounded Context: <Bounded Context Name>**

#### **2.6.x.1. Domain Layer**

#### **2.6.x.2. Interface Layer**

#### **2.6.x.3. Application Layer**

#### **2.6.x.4 Infrastructure Layer**

#### **2.6.x.5. Bounded Context Software Architecture Component Level Diagrams**

#### **2.6.x.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.x.6.1. Bounded Context Domain Layer Class Diagrams**

##### **2.6.x.6.2. Bounded Context Database Design Diagram**

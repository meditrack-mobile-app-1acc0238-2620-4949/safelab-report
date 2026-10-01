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

<p style="text-align: justify;">
  En esta sección se presenta el proceso de entrevistas realizado para comprender, desde la perspectiva de los usuarios, cómo se gestionan actualmente el monitoreo y el control de las condiciones ambientales en los dos segmentos objetivo de SafeLab. Se describe el diseño de las entrevistas, el registro de cada una y el análisis por segmento que sirve de base para la construcción de los User Personas de la sección 2.3.
</p>

### **2.2.1. Interview Design**


<p style="text-align: justify;">
  Las entrevistas se diseñaron con un formato semiestructurado e individual, con el objetivo de recolectar las características objetivas y subjetivas necesarias para construir los arquetipos de cada segmento objetivo. Para ambos segmentos se mantuvo la misma estructura de doce preguntas, adaptando su redacción al contexto de cada uno: el laboratorio hospitalario, donde se custodian muestras, reactivos e insumos, y la empresa farmacéutica, donde se controla el almacenamiento de medicamentos con fines de trazabilidad y auditoría.
</p>

<p style="text-align: justify;">
  Las preguntas se clasificaron en principales y complementarias. Las preguntas principales exploran directamente el problema y las necesidades del entrevistado: su proceso actual, los incidentes críticos que ha vivido, sus frustraciones, la solución que espera y las garantías que necesita para confiar en ella. Las preguntas complementarias permiten caracterizar al entrevistado, mediante sus datos demográficos, personalidad, ocupación y uso de tecnología, y profundizar en aspectos específicos de las respuestas principales, como el tiempo invertido o el nivel de automatización que aceptaría.
</p>

<p style="text-align: justify;">
  La siguiente tabla resume la relación entre cada bloque de preguntas y las variables que se recogen para la construcción de los User Personas. La numeración de las preguntas corresponde al orden en que fueron formuladas durante la entrevista.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Bloque</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Preguntas</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Tipo</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Variables recogidas</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Perfil del entrevistado</td><td style="text-align: center; vertical-align: middle; padding: 6px;">P1, P2, P3</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Complementarias</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Nombre, edad, estado civil, distrito de residencia, ocupación, años de experiencia, personalidad y actividades de tiempo libre.</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Tecnología</td><td style="text-align: center; vertical-align: middle; padding: 6px;">P4</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Complementaria</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Dispositivos, sistemas operativos, navegadores y canales digitales utilizados.</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Proceso actual</td><td style="text-align: center; vertical-align: middle; padding: 6px;">P5, P6</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Principal y complementaria</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Procedimiento y herramientas de monitoreo, frecuencia de registro y tiempo invertido en registrar y consolidar la información.</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Problemas e incidentes</td><td style="text-align: center; vertical-align: middle; padding: 6px;">P7, P8</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Principales</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Incidentes críticos, sus consecuencias y las frustraciones del entrevistado.</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Solución esperada</td><td style="text-align: center; vertical-align: middle; padding: 6px;">P9, P10</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Principal y complementaria</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Objetivos, funcionalidades esperadas y nivel de automatización aceptado.</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Confianza y cierre</td><td style="text-align: center; vertical-align: middle; padding: 6px;">P11, P12</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Principal y complementaria</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Garantías requeridas para confiar en el sistema, motivaciones e información adicional relevante.</td></tr>
  </tbody>
</table>

#### **Segmento 1: Laboratorios de Hospitales**

**Preguntas principales**

- **P5.** ¿Cómo es actualmente el proceso de monitoreo y control de muestras, reactivos e insumos en tu laboratorio, en el día a día?
- **P7.** Cuéntame sobre la última vez que tuvieron un incidente crítico, como una desviación de temperatura, un corte de luz o pérdida de reactivos.
- **P8.** ¿Qué es lo que más te frustra o estresa de esta parte de tu trabajo actualmente?
- **P9.** Si existiera un sistema ideal para resolver estos problemas, ¿cómo sería?
- **P11.** Para que confíes al 100% en un sistema así, ¿qué información o garantías necesitarías que te muestre?

**Preguntas complementarias**

- **P1.** ¿Podrías contarnos tu nombre, edad, estado civil y el distrito donde vives?
- **P2.** Cuéntanos un poco sobre ti y qué sueles hacer en tu tiempo libre. ¿Cómo te describirías en tres palabras?
- **P3.** ¿Cuál es tu puesto actual en el laboratorio y cuántos años de experiencia tienes en este rol?
- **P4.** En tu día a día, ¿qué dispositivos tecnológicos usas más, y qué sistema operativo y navegador prefieres?
- **P6.** ¿Cuánto tiempo estimas que dedican a registrar estos datos y a consolidar la información en reportes?
- **P10.** Si un sistema detectara que una refrigeradora o congeladora está fallando, ¿preferirías solo recibir una notificación, o que el sistema intente una acción de contingencia automática?
- **P12.** ¿Hay algo más sobre tu trabajo con muestras e insumos sensibles que consideres importante mencionar?

#### **Segmento 2: Empresas Farmacéuticas**

**Preguntas principales**

- **P5.** ¿Cómo es actualmente el proceso de monitoreo de condiciones de almacenamiento de medicamentos, incluyendo trazabilidad y registros para auditoría?
- **P7.** Cuéntame sobre la última vez que tuvieron un incidente crítico, como una excursión de temperatura durante el almacenamiento o transporte que puso en riesgo un lote.
- **P8.** ¿Qué es lo que más te frustra o estresa de mantener la trazabilidad y el cumplimiento normativo actualmente?
- **P9.** Si existiera un sistema ideal para resolver estos problemas, ¿cómo sería?
- **P11.** Para que confíes al 100% en un sistema así para auditorías regulatorias, ¿qué información o garantías necesitarías que te muestre?

**Preguntas complementarias**

- **P1.** ¿Podrías contarnos tu nombre, edad, estado civil y el distrito donde vives?
- **P2.** Cuéntanos un poco sobre ti y qué sueles hacer en tu tiempo libre. ¿Cómo te describirías en tres palabras?
- **P3.** ¿Cuál es tu puesto actual dentro de la empresa y cuántos años de experiencia tienes en roles de almacenamiento, calidad o logística?
- **P4.** En tu día a día, ¿qué dispositivos tecnológicos usas más, y qué sistema operativo y navegador prefieres?
- **P6.** ¿Cuánto tiempo estima tu equipo que dedica a consolidar los registros ambientales y preparar documentación para auditorías regulatorias?
- **P10.** Si un sistema detectara una desviación en una sala de almacenamiento o durante el transporte, ¿preferirías solo recibir una notificación, o que el sistema también active una acción de mitigación automática?
- **P12.** ¿Hay algo más sobre trazabilidad, cumplimiento o monitoreo de la cadena de suministro que consideres importante mencionar?


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


<p style="text-align: justify;">
  El análisis se realizó por segmento objetivo a partir de las respuestas registradas en la sección 2.2.2. Para cada variable se contabilizó la cantidad de entrevistados que la mencionaron y se calculó el porcentaje respecto del total de entrevistados del segmento (n). Cuando un entrevistado no brindó información sobre una variable, esta se registra como «No especificado». Al final de la sección se comparan ambos segmentos para identificar las coincidencias y diferencias que orientan la construcción de los User Personas y las decisiones de diseño de SafeLab.
</p>

#### **Segmento 1: Laboratorios de Hospitales (n = 2)**

##### **Características**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Variable</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Resultado</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Sexo</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Femenino: 1 (50%) / Masculino: 1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Edad</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Rango de 27 a 34 años; promedio de 30,5 años</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Estado civil</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Casada: 1 (50%) / No especificado: 1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Ciudad de residencia</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Arequipa: 2 (100%) — Cercado de Arequipa y Yanahuara</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Ocupación</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Jefa de laboratorio clínico: 1 (50%) / Técnico de laboratorio: 1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Experiencia</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Entre 3 y 8 años en el hospital</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Personalidad</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Responsable: 2 (100%) / Tranquilo(a): 2 (100%) / Meticulosa: 1 (50%) / Adaptado al turno de noche: 1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Tiempo libre</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Actividades al aire libre o deportivas (jardinería, caminatas, fútbol): 2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Dispositivo principal</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Smartphone Android: 2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Computadora</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Computadora compartida del hospital, sin equipo asignado: 2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Sistema operativo</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Android: 2 (100%) / Windows: 1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Navegador</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Google Chrome: 1 (50%) / No especificado: 1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Canal digital esperado para alertas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Celular: 2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Marcas tecnológicas mencionadas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Android: 2 (100%) / Windows: 1 (50%) / Google Chrome: 1 (50%) / Microsoft Excel: 1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Influencias</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Entidades reguladoras de salud (DIGESA, DIRESA): 1 (50%)</td></tr>
  </tbody>
</table>

##### **Proceso actual e incidentes**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Indicador</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Resultado</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Registro manual en papel</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Transcripción posterior a Excel</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Frecuencia de revisión</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Tres veces por turno: 1 (50%) / Cada cuatro horas: 1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Tiempo por revisión</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Entre 10 y 15 minutos por ronda, más 20 a 30 minutos diarios de transcripción a Excel</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Reportó un incidente crítico</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Incidente detectado recién al día o turno siguiente</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Pérdida de material reportada</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (50%)</td></tr>
  </tbody>
</table>

##### **Expectativas sobre la solución**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Indicador</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Resultado</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Registro automático o con una sola acción, sin papeleo</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Alertas o recordatorios en el celular</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Reportes exportables para auditoría (PDF o Excel)</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Escalamiento automático a un supervisor</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Prefiere ser notificado y decidir, o escalar, antes que una acción autónoma sobre equipos críticos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Acepta que el sistema actúe de forma autónoma sobre equipos críticos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">0 (0%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Registro digital que sirva como evidencia del trabajo realizado</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Calibración verificable de los sensores</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Respaldo ante cortes de energía</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Cumplimiento de la normativa de salud local</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (50%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Funcionamiento sin conexión a internet</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (50%)</td></tr>
  </tbody>
</table>

##### **Objetivos comunes**

- Eliminar el registro en papel y las rondas físicas mediante un registro automático o de una sola acción (100%).
- Recibir avisos en el celular ante cualquier desviación o tarea pendiente (100%).
- Contar con registros digitales que puedan presentarse en auditorías y sirvan como respaldo del trabajo realizado (100%).

##### **Motivaciones comunes**

- Proteger muestras, reactivos e insumos de pérdidas como las ocurridas en los incidentes reportados (100%).
- Poder demostrar que los controles se realizaron correctamente, ante auditorías o ante un incidente (100%).
- Reducir la carga manual, ya que el problema se atribuye a la falta de herramientas y de tiempo (50%).
- Contar con respaldo durante los turnos con poco personal (50%).

##### **Frustraciones comunes**

- Registros en papel que se pierden, se dañan o no permiten demostrar lo realizado (100%).
- Desviaciones que se detectan recién horas después, al día o turno siguiente (100%).
- Preparación manual de auditorías con papeles sueltos de varios meses (50%).
- Falta de respaldo durante el turno de noche (50%).

#### **Segmento 2: Empresas Farmacéuticas (n = 3)**

##### **Características**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Variable</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Resultado</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Sexo</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Masculino: 3 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Edad</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Rango de 24 a 31 años; promedio de 26,3 años</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Estado civil</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Soltero: 2 (67%) / Casado: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Ciudad de residencia</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Lima: 3 (100%) — Los Olivos, San Borja y San Miguel</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Ocupación</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Supervisor de control de calidad: 1 (33%) / Analista de calidad: 1 (33%) / Asistente de logística: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Área de trabajo</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Calidad: 2 (67%) / Logística: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Experiencia</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Alrededor de 2 años: 2 (67%) / No especificado: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Personalidad</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Detallista: 2 (67%) / Rasgos mencionados una vez: disciplinado, proactivo, curioso, tecnológico, analítico, responsable, organizado y tranquilo (33% cada uno)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Tiempo libre</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Videojuegos: 2 (67%) / Tecnología y ciclismo: 1 (33%) / Salir con amigos y fútbol: 1 (33%) / No especificado: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Smartphone</td><td style="text-align: justify; vertical-align: top; padding: 6px;">iPhone: 1 (33%) / Android: 1 (33%) / No especificado: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Computadora</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Laptop o computadora de la empresa: 2 (67%) / No especificado: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Sistema operativo</td><td style="text-align: justify; vertical-align: top; padding: 6px;">iOS: 1 (33%) / Android: 1 (33%) / Windows: 1 (33%) / No especificado: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Navegador</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Google Chrome: 2 (67%) / No especificado: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Canal digital esperado para alertas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Notificaciones o alertas inmediatas: 3 (100%); en el celular de forma explícita: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Canal de alerta actual</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Alarma sonora local y correo electrónico: 1 (33%) / Sin alertas automáticas: 2 (67%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Marcas tecnológicas mencionadas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Microsoft Excel: 3 (100%) / Google Chrome: 2 (67%) / Windows: 1 (33%) / iPhone: 1 (33%) / Android: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Influencias</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Exigencias de auditoría regulatoria: 3 (100%) / DIGEMID y principios ALCOA+ de forma explícita: 1 (33%)</td></tr>
  </tbody>
</table>

##### **Proceso actual e incidentes**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Indicador</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Resultado</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Dataloggers con descarga por USB</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (67%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Sensores con pantalla y registro manual de los valores</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Consolidación en Excel</td><td style="text-align: justify; vertical-align: top; padding: 6px;">3 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Uso de documentos físicos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (67%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Tiempo de consolidación</td><td style="text-align: justify; vertical-align: top; padding: 6px;">Varias horas por semana: 1 (33%) / 10 a 12 horas por semana: 1 (33%) / Varios días por cada solicitud de auditoría: 1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Reportó un incidente crítico</td><td style="text-align: justify; vertical-align: top; padding: 6px;">3 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Desviación detectada después de ocurrida</td><td style="text-align: justify; vertical-align: top; padding: 6px;">3 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Producto separado, en cuarentena o destruido</td><td style="text-align: justify; vertical-align: top; padding: 6px;">3 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Pérdida económica y observación regulatoria explícitas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (33%)</td></tr>
  </tbody>
</table>

##### **Expectativas sobre la solución**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Indicador</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Resultado</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Visualización centralizada y en tiempo real de todas las zonas o equipos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">3 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Notificaciones o alertas inmediatas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">3 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Alertas preventivas, antes de superar el límite o anticipando fallas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (67%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Reportes automáticos para auditoría</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (67%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Historial con búsqueda por fechas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Acepta acciones de mitigación automáticas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (67%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Acciones automáticas según el tipo de problema, con revisión humana en decisiones críticas</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Registros inalterables</td><td style="text-align: justify; vertical-align: top; padding: 6px;">3 (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Registro de quién realiza cambios o acciones en el sistema</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (67%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Seguridad de los datos y de los accesos</td><td style="text-align: justify; vertical-align: top; padding: 6px;">2 (67%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Exportación de registros para entidades regulatorias</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Redundancia de infraestructura</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Certificados de los equipos almacenados en la plataforma</td><td style="text-align: justify; vertical-align: top; padding: 6px;">1 (33%)</td></tr>
  </tbody>
</table>

##### **Objetivos comunes**

- Centralizar en un solo lugar la información hoy repartida entre dataloggers, sensores, hojas de Excel y documentos físicos (100%).
- Ver las condiciones de almacenamiento en tiempo real y recibir alertas inmediatas (100%).
- Generar reportes y evidencias de auditoría sin consolidación manual (67%).
- Anticiparse a las desviaciones antes de que se supere el límite permitido (67%).

##### **Motivaciones comunes**

- Evitar que lotes de producto tengan que separarse, ponerse en cuarentena o destruirse (100%).
- Superar auditorías con registros confiables e inalterables (100%).
- Reducir las horas o días dedicados a consolidar información de forma manual (100%).

##### **Frustraciones comunes**

- Consolidación manual y repetitiva de datos en Excel (100%).
- Enterarse de los problemas cuando ya ocurrieron, por falta de visibilidad en tiempo real (100%).
- Información fragmentada entre papel, hojas de cálculo y distintos archivos, que dificulta saber desde cuándo empezó un problema y cuánto duró (67%).

#### **Comparación entre segmentos**

<p style="text-align: justify;">
  La siguiente tabla compara los indicadores más representativos de ambos segmentos objetivo.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Indicador</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Segmento 1: Laboratorios de Hospitales (n = 2)</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Segmento 2: Empresas Farmacéuticas (n = 3)</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Edad promedio</td><td style="text-align: center; vertical-align: middle; padding: 6px;">30,5 años</td><td style="text-align: center; vertical-align: middle; padding: 6px;">26,3 años</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Ciudad de residencia</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Arequipa (100%)</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Lima (100%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Smartphone como dispositivo de uso diario</td><td style="text-align: center; vertical-align: middle; padding: 6px;">100% (Android)</td><td style="text-align: center; vertical-align: middle; padding: 6px;">67% (iOS 33%, Android 33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Usa una computadora para su trabajo</td><td style="text-align: center; vertical-align: middle; padding: 6px;">100% (compartida, sin equipo asignado)</td><td style="text-align: center; vertical-align: middle; padding: 6px;">67% (laptop o computadora de la empresa)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Google Chrome como navegador</td><td style="text-align: center; vertical-align: middle; padding: 6px;">50%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">67%</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Método de registro</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Papel (100%)</td><td style="text-align: center; vertical-align: middle; padding: 6px;">Datalogger USB (67%) y sensores con pantalla (33%)</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Consolidación en Excel</td><td style="text-align: center; vertical-align: middle; padding: 6px;">50%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">100%</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Incidente crítico detectado después de ocurrido</td><td style="text-align: center; vertical-align: middle; padding: 6px;">100%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">100%</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Espera alertas inmediatas</td><td style="text-align: center; vertical-align: middle; padding: 6px;">100%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">100%</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Espera alertas preventivas</td><td style="text-align: center; vertical-align: middle; padding: 6px;">0%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">67%</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Espera reportes para auditoría</td><td style="text-align: center; vertical-align: middle; padding: 6px;">50%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">67%</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Acepta acciones automáticas sobre equipos críticos</td><td style="text-align: center; vertical-align: middle; padding: 6px;">0%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">67%</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Exige registros inalterables</td><td style="text-align: center; vertical-align: middle; padding: 6px;">0%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">100%</td></tr>
    <tr><td style="text-align: justify; vertical-align: top; padding: 6px;">Requiere funcionamiento sin conexión</td><td style="text-align: center; vertical-align: middle; padding: 6px;">50%</td><td style="text-align: center; vertical-align: middle; padding: 6px;">0%</td></tr>
  </tbody>
</table>

<p style="text-align: justify;">
  El problema central es compartido por ambos segmentos: el 100% de los entrevistados reportó un incidente crítico que fue detectado después de ocurrido y el 100% espera recibir alertas inmediatas. Esto confirma que la necesidad principal es la visibilidad en tiempo real sobre las condiciones de los equipos y respalda la prioridad del monitoreo ambiental y de las alertas dentro de SafeLab.
</p>

<p style="text-align: justify;">
  La principal diferencia tecnológica está en el acceso a una computadora. En el Segmento 1, el celular es el único dispositivo propio de los entrevistados y la computadora es compartida, por lo que la aplicación móvil debe ser el canal principal y funcionar con una conectividad inestable. En el Segmento 2, el 67% trabaja además con una laptop o computadora de la empresa y el 100% consolida información en Excel, lo que explica el mayor interés por los reportes y la exportación de registros.
</p>

<p style="text-align: justify;">
  La diferencia más marcada se encuentra en el nivel de automatización aceptado. En el Segmento 1, ningún entrevistado acepta que el sistema actúe por sí solo sobre equipos críticos: prefieren ser notificados, recibir una recomendación o que la alerta se escale a un supervisor. En el Segmento 2, el 67% acepta acciones de mitigación automáticas, siempre que queden registradas, mientras que el 33% restante considera que dependen del tipo de problema. Por ello, las respuestas automáticas de SafeLab deben ser configurables y quedar siempre registradas.
</p>

<p style="text-align: justify;">
  Finalmente, la confianza en el sistema se construye de manera distinta en cada segmento. El Segmento 1 se enfoca en la confiabilidad operativa, mediante la calibración de los sensores, el respaldo de energía y el funcionamiento sin conexión, mientras que el Segmento 2 se enfoca en la integridad y la trazabilidad de los datos: el 100% exige registros inalterables y el 67% necesita saber quién realiza cambios en el sistema.
</p>


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

<p style="text-align: justify;">
El Ubiquitous Language de SafeLab reúne los términos del dominio utilizados de manera consistente para describir el monitoreo de la cadena de frío, la gestión de desviaciones, el mantenimiento de equipos, la trazabilidad y el cumplimiento regulatorio.
</p>

<table style="margin: auto; width: 100%; border-collapse: collapse;" border="1">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Ubiquitous Term</th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">Definición</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Cold Chain</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Proceso continuo de conservación de productos, muestras o insumos sensibles dentro de condiciones de temperatura controlada durante su almacenamiento y manipulación.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Monitoring Site</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Instalación física, como un laboratorio, planta o almacén, en la que SafeLab organiza y supervisa las áreas y equipos sujetos a monitoreo.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Storage Area</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Zona física dentro de un Monitoring Site destinada al almacenamiento controlado y en la que se encuentran uno o más equipos monitoreados.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Monitored Equipment</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Equipo de refrigeración, congelación o conservación cuyas condiciones ambientales y estado operativo son supervisados por SafeLab.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Environmental Sensor</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Dispositivo asociado a un equipo monitoreado que captura variables ambientales, principalmente temperatura y humedad.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Environmental Reading</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Medición de una variable ambiental registrada por un sensor en una fecha y hora determinadas y asociada al equipo correspondiente.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Environmental Threshold</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Límite mínimo o máximo configurado para una variable ambiental de un equipo, utilizado para determinar si una lectura se encuentra dentro de las condiciones permitidas.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Thermal Excursion</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Desviación en la que la temperatura registrada se encuentra fuera del rango permitido durante un periodo determinado y puede comprometer la cadena de frío.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Alert</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Registro generado cuando SafeLab detecta una condición que requiere atención, como la superación de un Environmental Threshold o una anomalía del equipo.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Incident</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Evento de seguimiento formal asociado a una desviación o alerta que requiere investigación, atención y registro de las acciones realizadas.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Corrective Action</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Acción ejecutada por el personal para contener, corregir o reducir el impacto de un Incident, manteniendo evidencia de quién la realizó y cuándo.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Equipment Condition</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Estado evaluado de un equipo a partir de sus lecturas, disponibilidad e historial, utilizado para identificar funcionamiento normal, advertencias o condiciones críticas.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Maintenance Record</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Registro de una actividad de mantenimiento, calibración, inspección o reparación realizada sobre un equipo monitoreado.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Traceability Record</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Conjunto ordenado de evidencias que permite reconstruir los eventos y acciones relacionados con un equipo, una alerta o un incidente.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Audit Entry</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Registro de auditoría que identifica una acción relevante, el actor involucrado, el objeto afectado y la fecha y hora en que ocurrió.</td>
    </tr>
    <tr>
      <td style="text-align: center; vertical-align: middle; padding: 6px;">Compliance Report</td>
      <td style="text-align: justify; vertical-align: top; padding: 6px;">Documento que consolida información histórica de monitoreo, incidentes, acciones y trazabilidad para sustentar actividades de control y auditorías regulatorias.</td>
    </tr>
  </tbody>
</table>

## **2.4. Requirements Specification**

##### **US01 - Registrar sitio de monitoreo**

| Campo | Valor |
|---|---|
| **Story ID** | US01 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP01 |
| **Title** | Registrar sitio de monitoreo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero registrar un sitio de monitoreo con su nombre y ubicación para organizar el monitoreo. |
| **Acceptance Criteria** | <b>Scenario 1: Registrar sitio con nombre y ubicación</b><br><b>Given</b> que el usuario proporciona un nombre y una ubicación para el sitio de monitoreo<br><b>When</b> registra el sitio de monitoreo<br><b>Then</b> el sistema almacena el sitio con el nombre y la ubicación proporcionados.<br><br><b>Scenario 2: Registrar sitio sin nombre</b><br><b>Given</b> que el usuario proporciona una ubicación pero no un nombre<br><b>When</b> intenta registrar el sitio de monitoreo<br><b>Then</b> el sistema no registra el sitio.<br><br><b>Scenario 3: Registrar sitio sin ubicación</b><br><b>Given</b> que el usuario proporciona un nombre pero no una ubicación<br><b>When</b> intenta registrar el sitio de monitoreo<br><b>Then</b> el sistema no registra el sitio. |

##### **US02 - Visualizar sitios de monitoreo**

| Campo | Valor |
|---|---|
| **Story ID** | US02 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP01 |
| **Title** | Visualizar sitios de monitoreo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los sitios de monitoreo registrados para poder gestionarlos. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar sitios registrados</b><br><b>Given</b> que existen sitios de monitoreo registrados<br><b>When</b> el usuario solicita visualizar los sitios de monitoreo<br><b>Then</b> el sistema proporciona los sitios registrados.<br><br><b>Scenario 2: Visualizar información de los sitios</b><br><b>Given</b> que los sitios registrados contienen nombre y ubicación<br><b>When</b> el usuario visualiza los sitios de monitoreo<br><b>Then</b> el sistema proporciona el nombre y la ubicación de cada sitio.<br><br><b>Scenario 3: No existen sitios registrados</b><br><b>Given</b> que no existen sitios de monitoreo registrados<br><b>When</b> el usuario solicita visualizar los sitios de monitoreo<br><b>Then</b> el sistema indica que no hay sitios disponibles. |

##### **US03 - Crear área de almacenamiento**

| Campo | Valor |
|---|---|
| **Story ID** | US03 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP01 |
| **Title** | Crear área de almacenamiento |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero crear áreas de almacenamiento con un nombre y tipo para organizar los equipos. |
| **Acceptance Criteria** | <b>Scenario 1: Crear área con nombre y tipo</b><br><b>Given</b> que el usuario proporciona un nombre y un tipo para el área de almacenamiento<br><b>When</b> crea el área de almacenamiento<br><b>Then</b> el sistema almacena el área con el nombre y el tipo proporcionados.<br><br><b>Scenario 2: Crear área sin nombre</b><br><b>Given</b> que el usuario proporciona el tipo del área pero no un nombre<br><b>When</b> intenta crear el área de almacenamiento<br><b>Then</b> el sistema no registra el área.<br><br><b>Scenario 3: Crear área sin tipo</b><br><b>Given</b> que el usuario proporciona un nombre pero no un tipo<br><b>When</b> intenta crear el área de almacenamiento<br><b>Then</b> el sistema no registra el área. |

##### **US04 - Visualizar áreas de almacenamiento**

| Campo | Valor |
|---|---|
| **Story ID** | US04 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP01 |
| **Title** | Visualizar áreas de almacenamiento |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las áreas de almacenamiento para comprender cómo están organizados los equipos monitoreados. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar áreas registradas</b><br><b>Given</b> que existen áreas de almacenamiento registradas<br><b>When</b> el usuario solicita visualizar las áreas<br><b>Then</b> el sistema proporciona las áreas registradas.<br><br><b>Scenario 2: Visualizar información de las áreas</b><br><b>Given</b> que las áreas registradas contienen nombre y tipo<br><b>When</b> el usuario visualiza las áreas de almacenamiento<br><b>Then</b> el sistema proporciona el nombre y el tipo de cada área.<br><br><b>Scenario 3: No existen áreas registradas</b><br><b>Given</b> que no existen áreas de almacenamiento registradas<br><b>When</b> el usuario solicita visualizar las áreas<br><b>Then</b> el sistema indica que no hay áreas de almacenamiento disponibles. |

##### **US05 - Registrar equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US05 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP01 |
| **Title** | Registrar equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero registrar equipos con su nombre, tipo e identificador para que puedan ser monitoreados. |
| **Acceptance Criteria** | <b>Scenario 1: Registrar equipo con la información requerida</b><br><b>Given</b> que el usuario proporciona nombre, tipo e identificador del equipo<br><b>When</b> registra el equipo<br><b>Then</b> el sistema almacena el equipo con la información proporcionada.<br><br><b>Scenario 2: Registrar equipo sin identificador</b><br><b>Given</b> que el usuario proporciona nombre y tipo pero no un identificador<br><b>When</b> intenta registrar el equipo<br><b>Then</b> el sistema no registra el equipo.<br><br><b>Scenario 3: Registrar equipo sin nombre o tipo</b><br><b>Given</b> que falta el nombre o el tipo del equipo<br><b>When</b> el usuario intenta registrar el equipo<br><b>Then</b> el sistema no registra el equipo. |

##### **US06 - Visualizar lista de equipos**

| Campo | Valor |
|---|---|
| **Story ID** | US06 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP01 |
| **Title** | Visualizar lista de equipos |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los equipos registrados para poder gestionarlos. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar equipos registrados</b><br><b>Given</b> que existen equipos registrados<br><b>When</b> el usuario solicita la lista de equipos<br><b>Then</b> el sistema proporciona los equipos registrados.<br><br><b>Scenario 2: Visualizar información de identificación</b><br><b>Given</b> que los equipos registrados contienen nombre, tipo e identificador<br><b>When</b> el usuario visualiza la lista de equipos<br><b>Then</b> el sistema proporciona la información de identificación de cada equipo.<br><br><b>Scenario 3: No existen equipos registrados</b><br><b>Given</b> que no existen equipos registrados<br><b>When</b> el usuario solicita la lista de equipos<br><b>Then</b> el sistema indica que no hay equipos disponibles. |

##### **US07 - Asignar equipo a un área**

| Campo | Valor |
|---|---|
| **Story ID** | US07 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP01 |
| **Title** | Asignar equipo a un área |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero asignar un equipo a un área de almacenamiento para conocer su ubicación. |
| **Acceptance Criteria** | <b>Scenario 1: Asignar equipo a un área</b><br><b>Given</b> que existen un equipo registrado y un área de almacenamiento registrada<br><b>When</b> el usuario asigna el equipo al área<br><b>Then</b> el sistema asocia el equipo con dicha área.<br><br><b>Scenario 2: Consultar ubicación del equipo asignado</b><br><b>Given</b> que un equipo se encuentra asociado a un área de almacenamiento<br><b>When</b> el usuario consulta la información del equipo<br><b>Then</b> el sistema proporciona el área a la que se encuentra asignado.<br><br><b>Scenario 3: Intentar asignar un recurso inexistente</b><br><b>Given</b> que el equipo o el área de almacenamiento no están registrados<br><b>When</b> el usuario intenta realizar la asignación<br><b>Then</b> el sistema no crea la asociación. |

##### **US08 - Buscar equipo por nombre**

| Campo | Valor |
|---|---|
| **Story ID** | US08 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP01 |
| **Title** | Buscar equipo por nombre |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero buscar equipos por nombre para encontrarlos rápidamente. |
| **Acceptance Criteria** | <b>Scenario 1: Encontrar un equipo por nombre</b><br><b>Given</b> que existe un equipo cuyo nombre coincide con el valor de búsqueda<br><b>When</b> el usuario realiza la búsqueda por nombre<br><b>Then</b> el sistema proporciona el equipo coincidente.<br><br><b>Scenario 2: Encontrar varios equipos coincidentes</b><br><b>Given</b> que existen varios equipos cuyos nombres coinciden con el valor de búsqueda<br><b>When</b> el usuario realiza la búsqueda<br><b>Then</b> el sistema proporciona los equipos coincidentes.<br><br><b>Scenario 3: No encontrar coincidencias</b><br><b>Given</b> que ningún equipo coincide con el nombre proporcionado<br><b>When</b> el usuario realiza la búsqueda<br><b>Then</b> el sistema indica que no existen equipos coincidentes. |

##### **US09 - Visualizar valores de temperatura**

| Campo | Valor |
|---|---|
| **Story ID** | US09 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Visualizar valores de temperatura |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los valores de temperatura para monitorear las condiciones de almacenamiento. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar temperatura actual</b><br><b>Given</b> que el equipo monitoreado dispone de una lectura de temperatura<br><b>When</b> el usuario solicita la información de temperatura<br><b>Then</b> el sistema proporciona el valor de temperatura disponible.<br><br><b>Scenario 2: Visualizar temperatura de un equipo específico</b><br><b>Given</b> que existen varios equipos con datos de temperatura<br><b>When</b> el usuario solicita la temperatura de un equipo determinado<br><b>Then</b> el sistema proporciona la temperatura correspondiente a ese equipo.<br><br><b>Scenario 3: Temperatura no disponible</b><br><b>Given</b> que el equipo seleccionado no dispone de datos de temperatura<br><b>When</b> el usuario solicita su temperatura<br><b>Then</b> el sistema indica que la temperatura no está disponible. |

##### **US10 - Visualizar valores de humedad**

| Campo | Valor |
|---|---|
| **Story ID** | US10 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Visualizar valores de humedad |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los valores de humedad para monitorear las condiciones de almacenamiento. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar humedad actual</b><br><b>Given</b> que el equipo monitoreado dispone de una lectura de humedad<br><b>When</b> el usuario solicita la información de humedad<br><b>Then</b> el sistema proporciona el valor de humedad disponible.<br><br><b>Scenario 2: Visualizar humedad de un equipo específico</b><br><b>Given</b> que existen varios equipos con datos de humedad<br><b>When</b> el usuario solicita la humedad de un equipo determinado<br><b>Then</b> el sistema proporciona la humedad correspondiente a ese equipo.<br><br><b>Scenario 3: Humedad no disponible</b><br><b>Given</b> que el equipo seleccionado no dispone de datos de humedad<br><b>When</b> el usuario solicita su humedad<br><b>Then</b> el sistema indica que la humedad no está disponible. |

##### **US11 - Visualizar estado operativo del equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US11 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Visualizar estado operativo del equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero saber si un equipo monitoreado está funcionando para detectar problemas. |
| **Acceptance Criteria** | <b>Scenario 1: Identificar equipo operativo</b><br><b>Given</b> que el equipo está proporcionando datos de monitoreo<br><b>When</b> el usuario solicita conocer su estado operativo<br><b>Then</b> el sistema identifica el equipo como operativo.<br><br><b>Scenario 2: Identificar interrupción del monitoreo</b><br><b>Given</b> que el equipo no está proporcionando datos de monitoreo<br><b>When</b> el usuario solicita conocer su estado operativo<br><b>Then</b> el sistema indica que el equipo no está funcionando con normalidad.<br><br><b>Scenario 3: Consultar estado de un equipo específico</b><br><b>Given</b> que existen varios equipos monitoreados<br><b>When</b> el usuario consulta el estado de un equipo determinado<br><b>Then</b> el sistema proporciona el estado operativo correspondiente a ese equipo. |

##### **US12 - Visualizar detalles del equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US12 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Visualizar detalles del equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los detalles de un equipo para revisar su temperatura, humedad y estado. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar detalles de un equipo</b><br><b>Given</b> que existe un equipo registrado con información de monitoreo<br><b>When</b> el usuario solicita sus detalles<br><b>Then</b> el sistema proporciona la temperatura, la humedad y el estado disponibles del equipo.<br><br><b>Scenario 2: Visualizar información parcialmente disponible</b><br><b>Given</b> que el equipo registrado no dispone de todos sus datos de monitoreo<br><b>When</b> el usuario solicita sus detalles<br><b>Then</b> el sistema proporciona la información disponible e indica los datos que no están disponibles.<br><br><b>Scenario 3: Consultar un equipo no registrado</b><br><b>Given</b> que el equipo solicitado no está registrado<br><b>When</b> el usuario solicita sus detalles<br><b>Then</b> el sistema indica que el equipo no está disponible. |

##### **US13 - Visualizar lista de equipos con datos en tiempo real**

| Campo | Valor |
|---|---|
| **Story ID** | US13 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Visualizar lista de equipos con datos en tiempo real |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los equipos junto con sus valores actuales de monitoreo para supervisar rápidamente sus condiciones. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar equipos con valores actuales</b><br><b>Given</b> que los equipos registrados disponen de datos actuales de monitoreo<br><b>When</b> el usuario solicita la lista de equipos<br><b>Then</b> el sistema proporciona los equipos junto con sus valores actuales disponibles.<br><br><b>Scenario 2: Visualizar lista con datos faltantes</b><br><b>Given</b> que algunos equipos registrados no disponen de datos actuales<br><b>When</b> el usuario solicita la lista de equipos<br><b>Then</b> el sistema muestra los equipos e identifica cuáles no disponen de datos actuales.<br><br><b>Scenario 3: Distinguir información por equipo</b><br><b>Given</b> que existen varios equipos con valores actuales diferentes<br><b>When</b> el usuario visualiza la lista de monitoreo<br><b>Then</b> el sistema relaciona cada valor actual con el equipo correspondiente. |

##### **US14 - Filtrar equipos por área de almacenamiento**

| Campo | Valor |
|---|---|
| **Story ID** | US14 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP02 |
| **Title** | Filtrar equipos por área de almacenamiento |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero filtrar los equipos por área de almacenamiento para concentrarme en una ubicación específica. |
| **Acceptance Criteria** | <b>Scenario 1: Filtrar equipos de un área</b><br><b>Given</b> que existen equipos asignados al área de almacenamiento seleccionada<br><b>When</b> el usuario filtra los equipos por dicha área<br><b>Then</b> el sistema proporciona únicamente los equipos asignados a esa área.<br><br><b>Scenario 2: Cambiar el área seleccionada</b><br><b>Given</b> que existen equipos asignados a diferentes áreas de almacenamiento<br><b>When</b> el usuario selecciona otra área<br><b>Then</b> el sistema actualiza los equipos mostrados según el área seleccionada.<br><br><b>Scenario 3: Área sin equipos</b><br><b>Given</b> que no existen equipos asignados al área seleccionada<br><b>When</b> el usuario aplica el filtro<br><b>Then</b> el sistema indica que no hay equipos disponibles para dicha área. |

##### **US15 - Identificar equipos sin datos recientes**

| Campo | Valor |
|---|---|
| **Story ID** | US15 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Identificar equipos sin datos recientes |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero identificar los equipos que no tienen datos recientes para detectar interrupciones en el monitoreo. |
| **Acceptance Criteria** | <b>Scenario 1: Identificar equipo sin datos recientes</b><br><b>Given</b> que un equipo registrado no ha proporcionado datos recientes de monitoreo<br><b>When</b> el sistema evalúa sus lecturas disponibles<br><b>Then</b> el sistema identifica el equipo como sin datos recientes.<br><br><b>Scenario 2: Mantener equipo con datos recientes</b><br><b>Given</b> que un equipo registrado dispone de datos recientes de monitoreo<br><b>When</b> el sistema evalúa sus lecturas disponibles<br><b>Then</b> el sistema mantiene al equipo fuera de la identificación de datos faltantes.<br><br><b>Scenario 3: Evaluar varios equipos</b><br><b>Given</b> que existen equipos con y sin datos recientes<br><b>When</b> el sistema evalúa las lecturas disponibles<br><b>Then</b> el sistema identifica únicamente los equipos que no cuentan con datos recientes. |

##### **US16 - Recolección automática de datos**

| Campo | Valor |
|---|---|
| **Story ID** | US16 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Recolección automática de datos |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero que los datos de monitoreo se recolecten automáticamente para no tener que registrarlos de forma manual. |
| **Acceptance Criteria** | <b>Scenario 1: Registrar automáticamente una nueva lectura</b><br><b>Given</b> que el equipo monitoreado está proporcionando datos<br><b>When</b> el sistema recibe una nueva lectura<br><b>Then</b> la lectura se registra automáticamente sin intervención manual del usuario.<br><br><b>Scenario 2: Registrar lecturas de distintos equipos</b><br><b>Given</b> que varios equipos monitoreados proporcionan nuevas lecturas<br><b>When</b> el sistema recibe los datos de monitoreo<br><b>Then</b> cada lectura se registra asociada al equipo correspondiente.<br><br><b>Scenario 3: Detectar ausencia de una nueva lectura</b><br><b>Given</b> que un equipo monitoreado deja de proporcionar datos<br><b>When</b> el sistema espera una nueva lectura de monitoreo<br><b>Then</b> el sistema identifica que no se recibió un nuevo dato del equipo. |

##### **US17 - Visualizar datos en dispositivo móvil**

| Campo | Valor |
|---|---|
| **Story ID** | US17 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Visualizar datos en dispositivo móvil |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los datos de monitoreo desde un dispositivo móvil para acceder a la información desde la aplicación móvil. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar monitoreo desde la aplicación móvil</b><br><b>Given</b> que el usuario tiene acceso a SafeLab y existen datos de monitoreo disponibles<br><b>When</b> solicita información desde la aplicación móvil<br><b>Then</b> el sistema proporciona los datos de monitoreo disponibles.<br><br><b>Scenario 2: Consultar un equipo desde el dispositivo móvil</b><br><b>Given</b> que existen datos de monitoreo para un equipo determinado<br><b>When</b> el usuario selecciona dicho equipo desde la aplicación móvil<br><b>Then</b> el sistema proporciona la información de monitoreo correspondiente al equipo.<br><br><b>Scenario 3: Datos no disponibles en la consulta móvil</b><br><b>Given</b> que los datos solicitados no están disponibles<br><b>When</b> el usuario solicita la información desde la aplicación móvil<br><b>Then</b> el sistema indica que los datos no pueden obtenerse. |

##### **US18 - Recibir alertas de temperatura**

| Campo | Valor |
|---|---|
| **Story ID** | US18 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP03 |
| **Title** | Recibir alertas de temperatura |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recibir alertas cuando la temperatura supere los límites establecidos para responder ante la desviación. |
| **Acceptance Criteria** | <b>Scenario 1: Generar alerta por temperatura superior al máximo</b><br><b>Given</b> que se ha definido un límite máximo de temperatura para un equipo<br><b>When</b> una lectura supera dicho límite<br><b>Then</b> el sistema genera una alerta de temperatura asociada al equipo.<br><br><b>Scenario 2: Generar alerta por temperatura inferior al mínimo</b><br><b>Given</b> que se ha definido un límite mínimo de temperatura para un equipo<br><b>When</b> una lectura se encuentra por debajo de dicho límite<br><b>Then</b> el sistema genera una alerta de temperatura asociada al equipo.<br><br><b>Scenario 3: Mantener monitoreo dentro del rango</b><br><b>Given</b> que la lectura de temperatura se encuentra dentro de los límites configurados<br><b>When</b> el sistema evalúa la lectura<br><b>Then</b> el sistema no genera una alerta por desviación de temperatura. |

##### **US19 - Recibir alertas de humedad**

| Campo | Valor |
|---|---|
| **Story ID** | US19 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP03 |
| **Title** | Recibir alertas de humedad |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recibir alertas cuando la humedad supere los límites establecidos para responder ante la desviación. |
| **Acceptance Criteria** | <b>Scenario 1: Generar alerta por humedad superior al máximo</b><br><b>Given</b> que se ha definido un límite máximo de humedad para un equipo<br><b>When</b> una lectura supera dicho límite<br><b>Then</b> el sistema genera una alerta de humedad asociada al equipo.<br><br><b>Scenario 2: Generar alerta por humedad inferior al mínimo</b><br><b>Given</b> que se ha definido un límite mínimo de humedad para un equipo<br><b>When</b> una lectura se encuentra por debajo de dicho límite<br><b>Then</b> el sistema genera una alerta de humedad asociada al equipo.<br><br><b>Scenario 3: Mantener monitoreo dentro del rango</b><br><b>Given</b> que la lectura de humedad se encuentra dentro de los límites configurados<br><b>When</b> el sistema evalúa la lectura<br><b>Then</b> el sistema no genera una alerta por desviación de humedad. |

##### **US20 - Visualizar lista de alertas**

| Campo | Valor |
|---|---|
| **Story ID** | US20 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP03 |
| **Title** | Visualizar lista de alertas |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las alertas generadas para gestionar los incidentes detectados. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar alertas generadas</b><br><b>Given</b> que existen alertas registradas<br><b>When</b> el usuario solicita la lista de alertas<br><b>Then</b> el sistema proporciona las alertas disponibles.<br><br><b>Scenario 2: Distinguir alertas por equipo</b><br><b>Given</b> que existen alertas asociadas a diferentes equipos<br><b>When</b> el usuario visualiza la lista de alertas<br><b>Then</b> el sistema permite identificar el equipo relacionado con cada alerta.<br><br><b>Scenario 3: No existen alertas</b><br><b>Given</b> que no se han generado alertas<br><b>When</b> el usuario solicita la lista de alertas<br><b>Then</b> el sistema indica que no hay alertas disponibles. |

##### **US21 - Visualizar detalles de una alerta**

| Campo | Valor |
|---|---|
| **Story ID** | US21 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP03 |
| **Title** | Visualizar detalles de una alerta |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar los detalles de una alerta para comprender el problema detectado. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar información de una alerta</b><br><b>Given</b> que existe una alerta generada<br><b>When</b> el usuario solicita sus detalles<br><b>Then</b> el sistema proporciona el equipo relacionado, el valor registrado y la fecha y hora de la alerta.<br><br><b>Scenario 2: Visualizar estado de la alerta</b><br><b>Given</b> que existe una alerta con un estado registrado<br><b>When</b> el usuario solicita sus detalles<br><b>Then</b> el sistema proporciona el estado correspondiente de la alerta.<br><br><b>Scenario 3: Consultar una alerta no disponible</b><br><b>Given</b> que la alerta solicitada no está disponible<br><b>When</b> el usuario solicita sus detalles<br><b>Then</b> el sistema indica que la alerta no puede encontrarse. |

##### **US22 - Confirmar atención de una alerta**

| Campo | Valor |
|---|---|
| **Story ID** | US22 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP03 |
| **Title** | Confirmar atención de una alerta |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero confirmar la atención de una alerta para llevar un control de las alertas que ya fueron gestionadas. |
| **Acceptance Criteria** | <b>Scenario 1: Confirmar atención de una alerta activa</b><br><b>Given</b> que una alerta aún no ha sido confirmada como atendida<br><b>When</b> el usuario confirma la atención de la alerta<br><b>Then</b> el sistema registra la alerta como atendida.<br><br><b>Scenario 2: Conservar la confirmación registrada</b><br><b>Given</b> que una alerta ya fue confirmada como atendida<br><b>When</b> el usuario consulta nuevamente la alerta<br><b>Then</b> el sistema conserva su estado de atención.<br><br><b>Scenario 3: Distinguir alertas atendidas y pendientes</b><br><b>Given</b> que existen alertas atendidas y alertas aún no confirmadas<br><b>When</b> el usuario visualiza la información de alertas<br><b>Then</b> el sistema permite identificar cuáles se encuentran atendidas y cuáles permanecen pendientes. |

##### **US23 - Visualizar alertas ordenadas por severidad**

| Campo | Valor |
|---|---|
| **Story ID** | US23 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP03 |
| **Title** | Visualizar alertas ordenadas por severidad |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las alertas según su severidad para poder priorizarlas. |
| **Acceptance Criteria** | <b>Scenario 1: Ordenar alertas con severidades diferentes</b><br><b>Given</b> que existen múltiples alertas con diferentes niveles de severidad<br><b>When</b> el usuario solicita las alertas ordenadas por severidad<br><b>Then</b> el sistema proporciona las alertas organizadas según su severidad.<br><br><b>Scenario 2: Priorizar alertas de mayor severidad</b><br><b>Given</b> que existen alertas con niveles de severidad diferentes<br><b>When</b> el usuario visualiza el orden por severidad<br><b>Then</b> el sistema presenta primero las alertas de mayor severidad.<br><br><b>Scenario 3: Mantener clasificación de severidad</b><br><b>Given</b> que varias alertas tienen el mismo nivel de severidad<br><b>When</b> el usuario solicita el orden por severidad<br><b>Then</b> el sistema conserva la clasificación de severidad de dichas alertas. |

##### **US24 - Recibir alertas en un dispositivo móvil**

| Campo | Valor |
|---|---|
| **Story ID** | US24 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP03 |
| **Title** | Recibir alertas en un dispositivo móvil |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recibir las alertas de SafeLab en un dispositivo móvil para enterarme de los incidentes detectados. |
| **Acceptance Criteria** | <b>Scenario 1: Enviar una alerta al dispositivo móvil</b><br><b>Given</b> que el sistema genera una alerta que debe comunicarse al usuario<br><b>When</b> se ejecuta el proceso de notificación<br><b>Then</b> la información de la alerta se envía al dispositivo móvil registrado.<br><br><b>Scenario 2: Relacionar la notificación con la alerta</b><br><b>Given</b> que una alerta generada contiene información del incidente detectado<br><b>When</b> el usuario recibe la notificación móvil<br><b>Then</b> la notificación permite identificar la alerta correspondiente.<br><br><b>Scenario 3: Conservar la alerta si la entrega falla</b><br><b>Given</b> que la notificación no puede entregarse al dispositivo móvil<br><b>When</b> se ejecuta el proceso de notificación<br><b>Then</b> el sistema conserva la alerta generada para su consulta posterior. |

##### **US25 - Configurar límites de alerta por equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US25 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP03 |
| **Title** | Configurar límites de alerta por equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero definir límites de temperatura y humedad para cada equipo monitoreado para que se generen alertas cuando esos límites sean superados. |
| **Acceptance Criteria** | <b>Scenario 1: Configurar límites de temperatura</b><br><b>Given</b> que existe un equipo monitoreado registrado<br><b>When</b> el usuario define y guarda sus límites de temperatura<br><b>Then</b> el sistema almacena los límites de temperatura para dicho equipo.<br><br><b>Scenario 2: Configurar límites de humedad</b><br><b>Given</b> que existe un equipo monitoreado registrado<br><b>When</b> el usuario define y guarda sus límites de humedad<br><b>Then</b> el sistema almacena los límites de humedad para dicho equipo.<br><br><b>Scenario 3: Rechazar límites incompletos</b><br><b>Given</b> que faltan límites requeridos para la configuración seleccionada<br><b>When</b> el usuario intenta guardar la configuración<br><b>Then</b> el sistema no almacena una configuración incompleta. |

##### **US26 - Compartir alertas con el equipo de trabajo**

| Campo | Valor |
|---|---|
| **Story ID** | US26 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP03 |
| **Title** | Compartir alertas con el equipo de trabajo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero que las alertas estén disponibles para el equipo de trabajo para coordinar la atención de los incidentes de monitoreo. |
| **Acceptance Criteria** | <b>Scenario 1: Consultar una alerta por miembros autorizados</b><br><b>Given</b> que se ha generado una alerta disponible para el equipo de trabajo<br><b>When</b> un miembro autorizado solicita la información de la alerta<br><b>Then</b> el sistema proporciona la información registrada de la alerta.<br><br><b>Scenario 2: Mantener información consistente para el equipo</b><br><b>Given</b> que varios miembros autorizados consultan la misma alerta<br><b>When</b> solicitan la información de la alerta<br><b>Then</b> el sistema proporciona la misma información registrada a los miembros autorizados.<br><br><b>Scenario 3: Restringir una alerta inexistente</b><br><b>Given</b> que la alerta solicitada no existe<br><b>When</b> un miembro del equipo solicita su información<br><b>Then</b> el sistema indica que la alerta no está disponible. |

##### **US27 - Visualizar datos históricos**

| Campo | Valor |
|---|---|
| **Story ID** | US27 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP04 |
| **Title** | Visualizar datos históricos |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar datos históricos de monitoreo para analizar condiciones pasadas. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar historial de un equipo</b><br><b>Given</b> que existen datos históricos de monitoreo para un equipo<br><b>When</b> el usuario solicita su historial<br><b>Then</b> el sistema proporciona los datos históricos disponibles del equipo.<br><br><b>Scenario 2: Relacionar datos históricos con el equipo</b><br><b>Given</b> que existen historiales de varios equipos<br><b>When</b> el usuario consulta el historial de un equipo específico<br><b>Then</b> el sistema proporciona únicamente la información histórica correspondiente a ese equipo.<br><br><b>Scenario 3: No existen datos históricos</b><br><b>Given</b> que no existen datos históricos almacenados para el equipo solicitado<br><b>When</b> el usuario solicita su historial<br><b>Then</b> el sistema indica que no hay datos históricos disponibles. |

##### **US28 - Seleccionar un rango de fechas para los datos**

| Campo | Valor |
|---|---|
| **Story ID** | US28 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP04 |
| **Title** | Seleccionar un rango de fechas para los datos |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero seleccionar un rango de fechas para revisar la información de monitoreo de un periodo específico. |
| **Acceptance Criteria** | <b>Scenario 1: Consultar datos dentro de un rango válido</b><br><b>Given</b> que el usuario proporciona una fecha de inicio anterior o igual a la fecha de fin<br><b>When</b> solicita los datos de monitoreo para ese rango<br><b>Then</b> el sistema proporciona los datos correspondientes al periodo seleccionado.<br><br><b>Scenario 2: Aplicar el rango al periodo solicitado</b><br><b>Given</b> que existen datos antes, dentro y después del rango seleccionado<br><b>When</b> el usuario consulta el periodo definido<br><b>Then</b> el sistema proporciona únicamente los datos comprendidos dentro del rango.<br><br><b>Scenario 3: Rechazar un rango invertido</b><br><b>Given</b> que la fecha de inicio es posterior a la fecha de fin<br><b>When</b> el usuario solicita datos de monitoreo<br><b>Then</b> el sistema rechaza el rango de fechas. |

##### **US29 - Comparar datos entre periodos**

| Campo | Valor |
|---|---|
| **Story ID** | US29 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP04 |
| **Title** | Comparar datos entre periodos |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero comparar los datos de monitoreo entre periodos para identificar variaciones. |
| **Acceptance Criteria** | <b>Scenario 1: Comparar dos periodos con datos</b><br><b>Given</b> que se han definido dos periodos con datos de monitoreo<br><b>When</b> el usuario solicita la comparación<br><b>Then</b> el sistema proporciona la información correspondiente a ambos periodos.<br><br><b>Scenario 2: Mantener separados los datos de cada periodo</b><br><b>Given</b> que los dos periodos seleccionados contienen información diferente<br><b>When</b> el usuario visualiza la comparación<br><b>Then</b> el sistema permite distinguir los datos correspondientes a cada periodo.<br><br><b>Scenario 3: Comparación con periodo incompleto</b><br><b>Given</b> que uno de los periodos requeridos no está completamente definido<br><b>When</b> el usuario solicita la comparación<br><b>Then</b> el sistema no realiza la comparación. |

##### **US30 - Generar reporte por equipo y fecha**

| Campo | Valor |
|---|---|
| **Story ID** | US30 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP04 |
| **Title** | Generar reporte por equipo y fecha |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero generar reportes por equipo y fecha para utilizar los registros de monitoreo en actividades de control y auditoría. |
| **Acceptance Criteria** | <b>Scenario 1: Generar reporte de un equipo y periodo</b><br><b>Given</b> que existe un equipo registrado y datos de monitoreo para la fecha o periodo seleccionado<br><b>When</b> el usuario solicita el reporte<br><b>Then</b> el sistema genera un reporte utilizando la información correspondiente.<br><br><b>Scenario 2: Incluir información del equipo en el reporte</b><br><b>Given</b> que se genera un reporte para un equipo específico<br><b>When</b> el usuario obtiene el reporte<br><b>Then</b> el reporte corresponde al equipo y a la fecha o periodo seleccionados.<br><br><b>Scenario 3: No generar reporte sin criterios requeridos</b><br><b>Given</b> que falta el equipo o la información de fecha requerida<br><b>When</b> el usuario solicita un reporte<br><b>Then</b> el sistema no genera el reporte. |

##### **US31 - Descargar archivo de reporte**

| Campo | Valor |
|---|---|
| **Story ID** | US31 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP04 |
| **Title** | Descargar archivo de reporte |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero descargar los reportes generados para utilizarlos o compartirlos fuera de SafeLab. |
| **Acceptance Criteria** | <b>Scenario 1: Descargar un reporte generado</b><br><b>Given</b> que existe un reporte generado disponible<br><b>When</b> el usuario solicita su descarga<br><b>Then</b> el sistema proporciona el archivo del reporte.<br><br><b>Scenario 2: Descargar el reporte seleccionado</b><br><b>Given</b> que existen varios reportes generados<br><b>When</b> el usuario selecciona un reporte y solicita su descarga<br><b>Then</b> el sistema proporciona el archivo correspondiente al reporte seleccionado.<br><br><b>Scenario 3: No existe reporte disponible</b><br><b>Given</b> que no hay un reporte generado disponible<br><b>When</b> el usuario solicita descargar un reporte<br><b>Then</b> el sistema indica que no hay ningún reporte disponible. |

##### **US32 - Visualizar historial de incidentes**

| Campo | Valor |
|---|---|
| **Story ID** | US32 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP04 |
| **Title** | Visualizar historial de incidentes |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar el historial de incidentes para revisar alertas y eventos anteriores. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar incidentes anteriores</b><br><b>Given</b> que se han registrado incidentes anteriores<br><b>When</b> el usuario solicita el historial de incidentes<br><b>Then</b> el sistema proporciona la información histórica disponible.<br><br><b>Scenario 2: Relacionar incidentes con sus alertas o eventos</b><br><b>Given</b> que existen incidentes con alertas o eventos asociados<br><b>When</b> el usuario consulta el historial<br><b>Then</b> el sistema proporciona la información asociada disponible para cada incidente.<br><br><b>Scenario 3: No existe historial de incidentes</b><br><b>Given</b> que no se han registrado alertas ni incidentes anteriores<br><b>When</b> el usuario solicita el historial de incidentes<br><b>Then</b> el sistema indica que no hay un historial disponible. |

##### **US33 - Exportar archivo de datos**

| Campo | Valor |
|---|---|
| **Story ID** | US33 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP04 |
| **Title** | Exportar archivo de datos |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero exportar los datos de monitoreo para utilizarlos fuera del sistema. |
| **Acceptance Criteria** | <b>Scenario 1: Exportar datos de monitoreo disponibles</b><br><b>Given</b> que existen datos de monitoreo disponibles para exportación<br><b>When</b> el usuario solicita la exportación<br><b>Then</b> el sistema genera un archivo utilizando los datos disponibles.<br><br><b>Scenario 2: Exportar los datos seleccionados</b><br><b>Given</b> que el usuario ha seleccionado información de monitoreo disponible<br><b>When</b> solicita la exportación<br><b>Then</b> el sistema genera el archivo con la información seleccionada.<br><br><b>Scenario 3: No existen datos para exportar</b><br><b>Given</b> que no existen datos de monitoreo disponibles para la exportación solicitada<br><b>When</b> el usuario solicita la exportación<br><b>Then</b> el sistema indica que no hay datos disponibles. |

##### **US34 - Comparar datos semanales y mensuales**

| Campo | Valor |
|---|---|
| **Story ID** | US34 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP04 |
| **Title** | Comparar datos semanales y mensuales |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero comparar datos de monitoreo semanales y mensuales para identificar variaciones entre periodos. |
| **Acceptance Criteria** | <b>Scenario 1: Comparar datos semanales y mensuales</b><br><b>Given</b> que existe información de monitoreo para la semana y el mes seleccionados<br><b>When</b> el usuario solicita la comparación<br><b>Then</b> el sistema proporciona la información correspondiente a ambos periodos.<br><br><b>Scenario 2: Distinguir datos semanales y mensuales</b><br><b>Given</b> que la semana y el mes seleccionados contienen datos diferentes<br><b>When</b> el usuario visualiza la comparación<br><b>Then</b> el sistema permite identificar qué información corresponde a la semana y cuál al mes.<br><br><b>Scenario 3: Periodo requerido incompleto</b><br><b>Given</b> que la semana o el mes no están completamente definidos<br><b>When</b> el usuario solicita la comparación<br><b>Then</b> el sistema no realiza la comparación. |

##### **US35 - Visualizar condición del equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US35 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP05 |
| **Title** | Visualizar condición del equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar la condición de un equipo para identificar posibles fallas. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar condición normal</b><br><b>Given</b> que el equipo funciona dentro de las condiciones esperadas<br><b>When</b> el usuario solicita conocer su condición<br><b>Then</b> el sistema identifica su condición como normal.<br><br><b>Scenario 2: Visualizar condición anómala</b><br><b>Given</b> que se ha detectado una condición anómala en el equipo<br><b>When</b> el usuario solicita conocer su condición<br><b>Then</b> el sistema proporciona la condición anómala detectada.<br><br><b>Scenario 3: Consultar la condición de un equipo específico</b><br><b>Given</b> que existen varios equipos con condiciones registradas<br><b>When</b> el usuario selecciona un equipo<br><b>Then</b> el sistema proporciona la condición correspondiente al equipo seleccionado. |

##### **US36 - Visualizar valores anómalos**

| Campo | Valor |
|---|---|
| **Story ID** | US36 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP05 |
| **Title** | Visualizar valores anómalos |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero identificar valores ambientales fuera de los límites establecidos para detectar problemas. |
| **Acceptance Criteria** | <b>Scenario 1: Identificar valor superior al límite máximo</b><br><b>Given</b> que los límites ambientales del equipo están definidos<br><b>When</b> una lectura supera el límite máximo configurado<br><b>Then</b> el sistema identifica la lectura como un valor anómalo.<br><br><b>Scenario 2: Identificar valor inferior al límite mínimo</b><br><b>Given</b> que los límites ambientales del equipo están definidos<br><b>When</b> una lectura se encuentra por debajo del límite mínimo configurado<br><b>Then</b> el sistema identifica la lectura como un valor anómalo.<br><br><b>Scenario 3: Mantener valor dentro del rango</b><br><b>Given</b> que una lectura se encuentra dentro de los límites ambientales definidos<br><b>When</b> el sistema evalúa la lectura<br><b>Then</b> el sistema no identifica la lectura como anómala. |

##### **US37 - Recibir alertas de advertencia del equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US37 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP05 |
| **Title** | Recibir alertas de advertencia del equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recibir advertencias sobre los equipos para identificar posibles fallas. |
| **Acceptance Criteria** | <b>Scenario 1: Generar advertencia por condición anómala</b><br><b>Given</b> que el sistema detecta una condición anómala en un equipo<br><b>When</b> la condición cumple los criterios definidos para una advertencia<br><b>Then</b> el sistema genera una advertencia asociada al equipo.<br><br><b>Scenario 2: Relacionar la advertencia con el equipo</b><br><b>Given</b> que se ha generado una advertencia de equipo<br><b>When</b> el usuario consulta la advertencia<br><b>Then</b> el sistema permite identificar el equipo relacionado.<br><br><b>Scenario 3: No generar advertencia en condición normal</b><br><b>Given</b> que no se detecta ninguna condición anómala en el equipo<br><b>When</b> el equipo es monitoreado<br><b>Then</b> el sistema no genera una advertencia del equipo. |

##### **US38 - Visualizar datos de rendimiento del equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US38 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP05 |
| **Title** | Visualizar datos de rendimiento del equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar el rendimiento de los equipos a lo largo del tiempo para evaluar su funcionamiento. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar rendimiento histórico</b><br><b>Given</b> que existen datos históricos del equipo disponibles<br><b>When</b> el usuario solicita información de rendimiento<br><b>Then</b> el sistema proporciona los datos de rendimiento disponibles a lo largo del tiempo.<br><br><b>Scenario 2: Consultar rendimiento de un equipo específico</b><br><b>Given</b> que existen datos históricos de varios equipos<br><b>When</b> el usuario solicita el rendimiento de un equipo determinado<br><b>Then</b> el sistema proporciona los datos correspondientes a ese equipo.<br><br><b>Scenario 3: No existen datos de rendimiento</b><br><b>Given</b> que no existen datos históricos suficientes disponibles para el equipo solicitado<br><b>When</b> el usuario solicita información de rendimiento<br><b>Then</b> el sistema indica que no hay datos de rendimiento disponibles. |

##### **US39 - Visualizar datos de uso del equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US39 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP05 |
| **Title** | Visualizar datos de uso del equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar datos de uso de los equipos para gestionar los recursos monitoreados. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar datos de uso</b><br><b>Given</b> que existen datos de uso de un equipo disponibles<br><b>When</b> el usuario solicita la información de uso<br><b>Then</b> el sistema proporciona los datos de uso disponibles.<br><br><b>Scenario 2: Consultar uso de un equipo específico</b><br><b>Given</b> que existen datos de uso de varios equipos<br><b>When</b> el usuario selecciona un equipo<br><b>Then</b> el sistema proporciona la información de uso correspondiente al equipo seleccionado.<br><br><b>Scenario 3: No existen datos de uso</b><br><b>Given</b> que no existen datos de uso disponibles para el equipo solicitado<br><b>When</b> el usuario solicita la información de uso<br><b>Then</b> el sistema indica que no hay datos de uso disponibles. |

##### **US40 - Registrar mantenimiento**

| Campo | Valor |
|---|---|
| **Story ID** | US40 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP05 |
| **Title** | Registrar mantenimiento |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero registrar información de mantenimiento de los equipos para conservar su historial de mantenimiento. |
| **Acceptance Criteria** | <b>Scenario 1: Registrar mantenimiento de un equipo</b><br><b>Given</b> que existe un equipo registrado y se proporciona información de mantenimiento<br><b>When</b> el usuario registra el mantenimiento<br><b>Then</b> el sistema almacena el registro asociado al equipo.<br><br><b>Scenario 2: Conservar el mantenimiento en el historial</b><br><b>Given</b> que se ha registrado una actividad de mantenimiento para un equipo<br><b>When</b> el usuario consulta posteriormente el historial del equipo<br><b>Then</b> el sistema mantiene disponible el registro de mantenimiento.<br><br><b>Scenario 3: No registrar mantenimiento sin equipo asociado</b><br><b>Given</b> que no existe un equipo registrado al cual asociar el mantenimiento<br><b>When</b> el usuario intenta registrar la información de mantenimiento<br><b>Then</b> el sistema no almacena el registro. |

##### **US41 - Visualizar historial de mantenimiento**

| Campo | Valor |
|---|---|
| **Story ID** | US41 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP05 |
| **Title** | Visualizar historial de mantenimiento |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar el historial de mantenimiento de un equipo para revisar los mantenimientos realizados previamente. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar historial de mantenimiento</b><br><b>Given</b> que se han registrado mantenimientos para un equipo<br><b>When</b> el usuario solicita su historial de mantenimiento<br><b>Then</b> el sistema proporciona los registros disponibles.<br><br><b>Scenario 2: Consultar historial de un equipo específico</b><br><b>Given</b> que existen registros de mantenimiento para varios equipos<br><b>When</b> el usuario selecciona un equipo<br><b>Then</b> el sistema proporciona únicamente los mantenimientos asociados a dicho equipo.<br><br><b>Scenario 3: No existen registros de mantenimiento</b><br><b>Given</b> que no se han registrado mantenimientos para el equipo solicitado<br><b>When</b> el usuario solicita su historial<br><b>Then</b> el sistema indica que no hay registros de mantenimiento disponibles. |

##### **US42 - Visualizar confiabilidad del equipo**

| Campo | Valor |
|---|---|
| **Story ID** | US42 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP05 |
| **Title** | Visualizar confiabilidad del equipo |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar la estabilidad de un equipo a lo largo del tiempo para evaluar su confiabilidad. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar estabilidad a lo largo del tiempo</b><br><b>Given</b> que existen datos históricos de un equipo disponibles<br><b>When</b> el usuario solicita información de confiabilidad<br><b>Then</b> el sistema proporciona la información de estabilidad disponible a lo largo del tiempo.<br><br><b>Scenario 2: Consultar confiabilidad de un equipo específico</b><br><b>Given</b> que existen datos históricos de varios equipos<br><b>When</b> el usuario selecciona un equipo<br><b>Then</b> el sistema proporciona la información de confiabilidad correspondiente al equipo seleccionado.<br><br><b>Scenario 3: Información insuficiente de confiabilidad</b><br><b>Given</b> que no existen datos históricos disponibles para el equipo solicitado<br><b>When</b> el usuario solicita información de confiabilidad<br><b>Then</b> el sistema indica que la información no está disponible. |

##### **US43 - Visualizar dashboard**

| Campo | Valor |
|---|---|
| **Story ID** | US43 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP06 |
| **Title** | Visualizar dashboard |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar la información clave de SafeLab para comprender el estado actual del monitoreo. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar información clave del monitoreo</b><br><b>Given</b> que SafeLab contiene información de monitoreo disponible<br><b>When</b> el usuario solicita el dashboard<br><b>Then</b> el sistema proporciona la información clave del estado actual del monitoreo.<br><br><b>Scenario 2: Integrar información de equipos y alertas</b><br><b>Given</b> que existen datos de equipos y alertas disponibles<br><b>When</b> el usuario visualiza el dashboard<br><b>Then</b> el sistema presenta un resumen centralizado de dicha información.<br><br><b>Scenario 3: Dashboard sin información disponible</b><br><b>Given</b> que no existe información de monitoreo disponible<br><b>When</b> el usuario solicita el dashboard<br><b>Then</b> el sistema indica que no hay información de monitoreo disponible. |

##### **US44 - Visualizar alertas críticas**

| Campo | Valor |
|---|---|
| **Story ID** | US44 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP06 |
| **Title** | Visualizar alertas críticas |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las alertas críticas para priorizar las situaciones que requieren atención. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar alertas críticas</b><br><b>Given</b> que existen alertas clasificadas como críticas<br><b>When</b> el usuario solicita las alertas críticas<br><b>Then</b> el sistema proporciona las alertas críticas disponibles.<br><br><b>Scenario 2: Excluir alertas no críticas</b><br><b>Given</b> que existen alertas con diferentes niveles de severidad<br><b>When</b> el usuario solicita visualizar únicamente las alertas críticas<br><b>Then</b> el sistema proporciona solo las alertas clasificadas como críticas.<br><br><b>Scenario 3: No existen alertas críticas</b><br><b>Given</b> que no existen alertas clasificadas como críticas<br><b>When</b> el usuario solicita las alertas críticas<br><b>Then</b> el sistema indica que no hay alertas críticas disponibles. |

##### **US45 - Visualizar resumen con totales**

| Campo | Valor |
|---|---|
| **Story ID** | US45 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP06 |
| **Title** | Visualizar resumen con totales |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar un resumen de equipos y alertas para obtener una visión general del entorno monitoreado. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar totales de equipos y alertas</b><br><b>Given</b> que existe información de equipos y alertas disponible<br><b>When</b> el usuario solicita el resumen de monitoreo<br><b>Then</b> el sistema proporciona los totales correspondientes de equipos y alertas.<br><br><b>Scenario 2: Actualizar el resumen según la información disponible</b><br><b>Given</b> que cambia la cantidad de equipos o alertas registradas<br><b>When</b> el usuario vuelve a consultar el resumen<br><b>Then</b> el sistema proporciona los totales correspondientes a la información disponible.<br><br><b>Scenario 3: Resumen sin información</b><br><b>Given</b> que no existe información de equipos ni alertas disponible<br><b>When</b> el usuario solicita el resumen<br><b>Then</b> el sistema indica que la información del resumen no está disponible. |

##### **US46 - Visualizar equipos con alertas activas**

| Campo | Valor |
|---|---|
| **Story ID** | US46 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP06 |
| **Title** | Visualizar equipos con alertas activas |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero identificar los equipos con alertas activas para concentrarme en aquellos que presentan problemas detectados. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar equipos con alertas activas</b><br><b>Given</b> que existen equipos registrados con alertas activas<br><b>When</b> el usuario solicita los equipos con alertas activas<br><b>Then</b> el sistema proporciona los equipos correspondientes.<br><br><b>Scenario 2: Excluir equipos sin alertas activas</b><br><b>Given</b> que existen equipos con y sin alertas activas<br><b>When</b> el usuario solicita los equipos con alertas activas<br><b>Then</b> el sistema proporciona únicamente los equipos que tienen alertas activas.<br><br><b>Scenario 3: Ningún equipo tiene alertas activas</b><br><b>Given</b> que ningún equipo registrado tiene alertas activas<br><b>When</b> el usuario solicita los equipos con alertas activas<br><b>Then</b> el sistema indica que no hay equipos afectados disponibles. |

##### **US47 - Visualizar distribución de equipos por estado**

| Campo | Valor |
|---|---|
| **Story ID** | US47 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP06 |
| **Title** | Visualizar distribución de equipos por estado |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar la distribución de los equipos según su estado operativo para identificar rápidamente la situación general de los equipos monitoreados. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar equipos según su estado operativo</b><br><b>Given</b> que existen equipos registrados con un estado operativo disponible<br><b>When</b> el usuario solicita la distribución de equipos por estado<br><b>Then</b> el sistema proporciona la cantidad de equipos correspondiente a cada estado disponible.<br><br><b>Scenario 2: Actualizar la distribución cuando cambia el estado de un equipo</b><br><b>Given</b> que el estado operativo de un equipo ha cambiado<br><b>When</b> el usuario vuelve a consultar la distribución de equipos<br><b>Then</b> el sistema refleja el estado actualizado del equipo en la distribución.<br><br><b>Scenario 3: No existen equipos registrados</b><br><b>Given</b> que no existen equipos registrados<br><b>When</b> el usuario solicita la distribución de equipos por estado<br><b>Then</b> el sistema indica que no hay información de equipos disponible. |

##### **US48 - Visualizar tendencias de alertas**

| Campo | Valor |
|---|---|
| **Story ID** | US48 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP06 |
| **Title** | Visualizar tendencias de alertas |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las tendencias de las alertas para analizar su comportamiento a lo largo del tiempo. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar tendencias a partir del historial</b><br><b>Given</b> que existe información histórica de alertas disponible<br><b>When</b> el usuario solicita las tendencias de alertas<br><b>Then</b> el sistema proporciona información de tendencias utilizando el historial disponible.<br><br><b>Scenario 2: Reflejar cambios en el comportamiento de alertas</b><br><b>Given</b> que el historial contiene alertas registradas en distintos momentos<br><b>When</b> el usuario visualiza las tendencias<br><b>Then</b> el sistema permite observar la variación de las alertas a lo largo del tiempo.<br><br><b>Scenario 3: No existe historial de alertas</b><br><b>Given</b> que no existe información histórica de alertas disponible<br><b>When</b> el usuario solicita las tendencias<br><b>Then</b> el sistema indica que la información de tendencias no está disponible. |

##### **US49 - Visualizar tendencias de temperatura**

| Campo | Valor |
|---|---|
| **Story ID** | US49 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP06 |
| **Title** | Visualizar tendencias de temperatura |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las tendencias de temperatura para analizar sus cambios a lo largo del tiempo. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar tendencia de temperatura</b><br><b>Given</b> que existen datos históricos de temperatura disponibles<br><b>When</b> el usuario solicita las tendencias de temperatura<br><b>Then</b> el sistema proporciona información de tendencias utilizando los datos históricos.<br><br><b>Scenario 2: Reflejar cambios de temperatura en el tiempo</b><br><b>Given</b> que el historial contiene diferentes valores de temperatura<br><b>When</b> el usuario visualiza la tendencia<br><b>Then</b> el sistema permite observar la variación de la temperatura a lo largo del tiempo.<br><br><b>Scenario 3: No existe historial de temperatura</b><br><b>Given</b> que no existen datos históricos de temperatura disponibles<br><b>When</b> el usuario solicita las tendencias de temperatura<br><b>Then</b> el sistema indica que la información de tendencias no está disponible. |

##### **US50 - Visualizar tendencias de humedad**

| Campo | Valor |
|---|---|
| **Story ID** | US50 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP06 |
| **Title** | Visualizar tendencias de humedad |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero visualizar las tendencias de humedad para analizar sus cambios a lo largo del tiempo. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar tendencia de humedad</b><br><b>Given</b> que existen datos históricos de humedad disponibles<br><b>When</b> el usuario solicita las tendencias de humedad<br><b>Then</b> el sistema proporciona información de tendencias utilizando los datos históricos.<br><br><b>Scenario 2: Reflejar cambios de humedad en el tiempo</b><br><b>Given</b> que el historial contiene diferentes valores de humedad<br><b>When</b> el usuario visualiza la tendencia<br><b>Then</b> el sistema permite observar la variación de la humedad a lo largo del tiempo.<br><br><b>Scenario 3: No existe historial de humedad</b><br><b>Given</b> que no existen datos históricos de humedad disponibles<br><b>When</b> el usuario solicita las tendencias de humedad<br><b>Then</b> el sistema indica que la información de tendencias no está disponible. |

##### **US51 - Iniciar sesión con una cuenta de Google**

| Campo | Valor |
|---|---|
| **Story ID** | US51 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP07 |
| **Title** | Iniciar sesión con una cuenta de Google |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero iniciar sesión utilizando una cuenta de Google para acceder a SafeLab. |
| **Acceptance Criteria** | <b>Scenario 1: Autenticarse con una cuenta de Google</b><br><b>Given</b> que la autenticación de Google valida la identidad del usuario<br><b>When</b> el usuario solicita acceder a SafeLab<br><b>Then</b> el sistema concede acceso a la cuenta correspondiente.<br><br><b>Scenario 2: Vincular el acceso con la cuenta autenticada</b><br><b>Given</b> que la autenticación de Google corresponde a una cuenta de SafeLab<br><b>When</b> el usuario completa el proceso de autenticación<br><b>Then</b> el sistema inicia el acceso con la cuenta correspondiente.<br><br><b>Scenario 3: Autenticación no validada</b><br><b>Given</b> que la autenticación de Google no puede validarse<br><b>When</b> el usuario solicita acceso a SafeLab<br><b>Then</b> el sistema no concede el acceso. |

##### **US52 - Iniciar sesión con correo electrónico y contraseña**

| Campo | Valor |
|---|---|
| **Story ID** | US52 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP07 |
| **Title** | Iniciar sesión con correo electrónico y contraseña |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero iniciar sesión utilizando correo electrónico y contraseña para acceder a mi cuenta de SafeLab. |
| **Acceptance Criteria** | <b>Scenario 1: Iniciar sesión con credenciales válidas</b><br><b>Given</b> que el usuario proporciona el correo electrónico y la contraseña correspondientes a una cuenta registrada<br><b>When</b> solicita acceso a SafeLab<br><b>Then</b> el sistema concede acceso a la cuenta correspondiente.<br><br><b>Scenario 2: No iniciar sesión con contraseña incorrecta</b><br><b>Given</b> que el correo electrónico corresponde a una cuenta registrada pero la contraseña no es válida<br><b>When</b> el usuario solicita acceso<br><b>Then</b> el sistema no concede el acceso.<br><br><b>Scenario 3: No iniciar sesión con cuenta inexistente</b><br><b>Given</b> que el correo electrónico proporcionado no corresponde a una cuenta registrada<br><b>When</b> el usuario solicita acceso<br><b>Then</b> el sistema no concede el acceso. |

##### **US53 - Recuperar contraseña por correo electrónico**

| Campo | Valor |
|---|---|
| **Story ID** | US53 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP07 |
| **Title** | Recuperar contraseña por correo electrónico |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero recuperar el acceso a mi cuenta mediante correo electrónico para volver a ingresar cuando no pueda utilizar mi contraseña. |
| **Acceptance Criteria** | <b>Scenario 1: Iniciar recuperación con correo registrado</b><br><b>Given</b> que el correo electrónico proporcionado pertenece a una cuenta registrada<br><b>When</b> el usuario solicita la recuperación de contraseña<br><b>Then</b> el sistema inicia el proceso de recuperación para dicha cuenta.<br><br><b>Scenario 2: Asociar la recuperación a la cuenta correcta</b><br><b>Given</b> que existen varias cuentas registradas<br><b>When</b> el usuario solicita recuperación para un correo electrónico específico<br><b>Then</b> el sistema inicia el proceso únicamente para la cuenta asociada a ese correo.<br><br><b>Scenario 3: Correo no registrado</b><br><b>Given</b> que el correo electrónico proporcionado no pertenece a una cuenta registrada<br><b>When</b> el usuario solicita la recuperación de contraseña<br><b>Then</b> el sistema no inicia una recuperación para una cuenta inexistente. |

##### **US54 - Cerrar sesión en el sistema**

| Campo | Valor |
|---|---|
| **Story ID** | US54 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP07 |
| **Title** | Cerrar sesión en el sistema |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero cerrar sesión para finalizar mi sesión activa en SafeLab. |
| **Acceptance Criteria** | <b>Scenario 1: Cerrar una sesión activa</b><br><b>Given</b> que el usuario tiene una sesión activa<br><b>When</b> solicita cerrar sesión<br><b>Then</b> el sistema finaliza la sesión activa.<br><br><b>Scenario 2: Impedir acceso con la sesión finalizada</b><br><b>Given</b> que el usuario ha cerrado su sesión<br><b>When</b> solicita acceder a información protegida<br><b>Then</b> el sistema requiere autenticación nuevamente.<br><br><b>Scenario 3: Requerir autenticación tras expiración</b><br><b>Given</b> que la sesión del usuario ha expirado<br><b>When</b> el usuario solicita acceso a información protegida<br><b>Then</b> el sistema requiere autenticación nuevamente. |

##### **US55 - Asignar rol de usuario**

| Campo | Valor |
|---|---|
| **Story ID** | US55 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP07 |
| **Title** | Asignar rol de usuario |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica con responsabilidad de gestión de usuarios, quiero asignar roles para que los usuarios registrados tengan los accesos correspondientes. |
| **Acceptance Criteria** | <b>Scenario 1: Asignar un rol válido</b><br><b>Given</b> que existe un usuario registrado y el actor tiene autorización para gestionar usuarios<br><b>When</b> el actor asigna un rol válido<br><b>Then</b> el sistema asocia el rol con el usuario seleccionado.<br><br><b>Scenario 2: Reflejar el rol asignado</b><br><b>Given</b> que un usuario tiene un rol asignado<br><b>When</b> se consulta la información de acceso del usuario<br><b>Then</b> el sistema proporciona el rol asociado al usuario.<br><br><b>Scenario 3: No asignar rol a un usuario inexistente</b><br><b>Given</b> que el usuario solicitado no está registrado<br><b>When</b> se intenta realizar una asignación de rol<br><b>Then</b> el sistema rechaza la asignación. |

##### **US56 - Visualizar la Landing Page de SafeLab**

| Campo | Valor |
|---|---|
| **Story ID** | US56 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP08 |
| **Title** | Visualizar la Landing Page de SafeLab |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero acceder a la Landing Page de SafeLab para conocer el producto. |
| **Acceptance Criteria** | <b>Scenario 1: Acceder a la Landing Page</b><br><b>Given</b> que la Landing Page de SafeLab está disponible públicamente<br><b>When</b> un visitante accede a ella<br><b>Then</b> el sitio proporciona información del producto SafeLab.<br><br><b>Scenario 2: Consultar información principal del producto</b><br><b>Given</b> que el visitante se encuentra en la Landing Page<br><b>When</b> consulta el contenido disponible<br><b>Then</b> el sitio presenta la información de SafeLab destinada a dar a conocer el producto.<br><br><b>Scenario 3: Recurso de la Landing Page no disponible</b><br><b>Given</b> que un recurso solicitado de la Landing Page no puede obtenerse<br><b>When</b> el visitante intenta acceder a dicho recurso<br><b>Then</b> el sitio no presenta contenido inválido como si estuviera disponible. |

##### **US57 - Cambiar el idioma de la Landing Page**

| Campo | Valor |
|---|---|
| **Story ID** | US57 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP08 |
| **Title** | Cambiar el idioma de la Landing Page |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero acceder al contenido de la Landing Page en los idiomas soportados para comprender la información presentada. |
| **Acceptance Criteria** | <b>Scenario 1: Visualizar la Landing Page en inglés</b><br><b>Given</b> que la Landing Page soporta inglés (en_US)<br><b>When</b> el visitante selecciona inglés<br><b>Then</b> el contenido disponible se proporciona en inglés.<br><br><b>Scenario 2: Visualizar la Landing Page en español latinoamericano</b><br><b>Given</b> que la Landing Page soporta español latinoamericano (es_419)<br><b>When</b> el visitante selecciona español latinoamericano<br><b>Then</b> el contenido disponible se proporciona en español latinoamericano.<br><br><b>Scenario 3: Usar el idioma predeterminado</b><br><b>Given</b> que el visitante no ha seleccionado otro idioma soportado<br><b>When</b> accede a la Landing Page<br><b>Then</b> el contenido se proporciona en inglés (en_US). |

##### **US58 - Acceder a los Términos y Condiciones**

| Campo | Valor |
|---|---|
| **Story ID** | US58 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Media |
| **Epic** | EP08 |
| **Title** | Acceder a los Términos y Condiciones |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero acceder a los Términos y Condiciones de SafeLab para revisar las condiciones asociadas al servicio. |
| **Acceptance Criteria** | <b>Scenario 1: Acceder a los Términos y Condiciones desde la Landing Page</b><br><b>Given</b> que los Términos y Condiciones de SafeLab están disponibles<br><b>When</b> un visitante los solicita desde la Landing Page<br><b>Then</b> el sitio proporciona acceso a los Términos y Condiciones.<br><br><b>Scenario 2: Acceder a los Términos y Condiciones durante el registro</b><br><b>Given</b> que un usuario está registrando una cuenta de SafeLab<br><b>When</b> solicita los Términos y Condiciones<br><b>Then</b> la aplicación proporciona acceso a los Términos y Condiciones.<br><br><b>Scenario 3: Consultar el mismo contenido desde ambos puntos de acceso</b><br><b>Given</b> que los Términos y Condiciones están disponibles en SafeLab<br><b>When</b> se accede a ellos desde la Landing Page o desde el registro<br><b>Then</b> el sistema proporciona el contenido correspondiente a los Términos y Condiciones de SafeLab. |

##### **US59 - Registrar cuenta de usuario**

| Campo | Valor |
|---|---|
| **Story ID** | US59 |
| **User** | Personal de Laboratorio Hospitalario / Empresa Farmacéutica |
| **Priority** | Alta |
| **Epic** | EP07 |
| **Title** | Registrar cuenta de usuario |
| **Description** | Como miembro del personal de un laboratorio hospitalario o de una empresa farmacéutica, quiero registrar una cuenta de SafeLab para acceder al servicio. |
| **Acceptance Criteria** | <b>Scenario 1: Registrar una cuenta con la información requerida</b><br><b>Given</b> que el usuario proporciona la información requerida para crear una cuenta<br><b>When</b> solicita el registro<br><b>Then</b> el sistema crea la cuenta de SafeLab.<br><br><b>Scenario 2: Evitar registro con información incompleta</b><br><b>Given</b> que falta información requerida de la cuenta<br><b>When</b> el usuario solicita el registro<br><b>Then</b> el sistema no crea la cuenta.<br><br><b>Scenario 3: Evitar registro con información inválida</b><br><b>Given</b> que la información proporcionada para la cuenta no puede validarse<br><b>When</b> el usuario solicita el registro<br><b>Then</b> el sistema rechaza el registro de la cuenta. |

##### **US60 - Proporcionar servicios de organización del monitoreo**

| Campo | Valor |
|---|---|
| **Story ID** | US60 |
| **User** | Developer |
| **Priority** | Alta |
| **Epic** | EP01 |
| **Title** | Proporcionar servicios de organización del monitoreo |
| **Description** | Como Developer, quiero que la RESTful API proporcione operaciones para sitios de monitoreo, áreas de almacenamiento y equipos, de modo que las aplicaciones de SafeLab puedan utilizar la información correspondiente a la organización del monitoreo. |
| **Acceptance Criteria** | <b>Scenario 1: Proporcionar operaciones de sitios de monitoreo</b><br><b>Given</b> que la RESTful API recibe una solicitud soportada relacionada con sitios de monitoreo<br><b>When</b> procesa la solicitud<br><b>Then</b> el servicio devuelve la respuesta correspondiente a la operación solicitada.<br><br><b>Scenario 2: Proporcionar operaciones de áreas y equipos</b><br><b>Given</b> que la RESTful API recibe una solicitud soportada relacionada con áreas de almacenamiento o equipos<br><b>When</b> procesa la solicitud<br><b>Then</b> el servicio devuelve la respuesta correspondiente a la operación solicitada.<br><br><b>Scenario 3: Recurso de organización inexistente</b><br><b>Given</b> que el recurso solicitado de organización del monitoreo no existe<br><b>When</b> el servicio RESTful procesa la solicitud<br><b>Then</b> el servicio devuelve una respuesta indicando que el recurso no fue encontrado. |

##### **US61 - Proporcionar servicios de monitoreo ambiental**

| Campo | Valor |
|---|---|
| **Story ID** | US61 |
| **User** | Developer |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Proporcionar servicios de monitoreo ambiental |
| **Description** | Como Developer, quiero que la RESTful API proporcione datos de monitoreo ambiental para que las aplicaciones de SafeLab puedan consumir información de temperatura, humedad y estado de los equipos. |
| **Acceptance Criteria** | <b>Scenario 1: Proporcionar temperatura y humedad</b><br><b>Given</b> que existe información de temperatura y humedad para el equipo solicitado<br><b>When</b> la RESTful API procesa una solicitud de monitoreo<br><b>Then</b> el servicio devuelve los datos ambientales disponibles.<br><br><b>Scenario 2: Proporcionar estado del equipo</b><br><b>Given</b> que existe información de estado para el equipo solicitado<br><b>When</b> la RESTful API procesa una solicitud de monitoreo<br><b>Then</b> el servicio devuelve el estado disponible del equipo.<br><br><b>Scenario 3: Equipo de monitoreo inexistente</b><br><b>Given</b> que el equipo solicitado no está registrado<br><b>When</b> la RESTful API procesa una solicitud de monitoreo<br><b>Then</b> el servicio devuelve una respuesta indicando que el equipo no fue encontrado. |

##### **US62 - Proporcionar servicios de alertas e incidentes**

| Campo | Valor |
|---|---|
| **Story ID** | US62 |
| **User** | Developer |
| **Priority** | Alta |
| **Epic** | EP03 |
| **Title** | Proporcionar servicios de alertas e incidentes |
| **Description** | Como Developer, quiero que la RESTful API proporcione información de alertas e incidentes para que las aplicaciones de SafeLab puedan utilizar las alertas generadas y sus estados. |
| **Acceptance Criteria** | <b>Scenario 1: Proporcionar información de una alerta</b><br><b>Given</b> que existe la alerta solicitada<br><b>When</b> la RESTful API procesa una solicitud válida<br><b>Then</b> el servicio devuelve la información correspondiente de la alerta.<br><br><b>Scenario 2: Proporcionar el estado de una alerta</b><br><b>Given</b> que existe una alerta con un estado registrado<br><b>When</b> la RESTful API procesa una solicitud de dicha alerta<br><b>Then</b> el servicio devuelve la alerta junto con su estado disponible.<br><br><b>Scenario 3: Alerta inexistente</b><br><b>Given</b> que la alerta solicitada no está disponible<br><b>When</b> la RESTful API procesa la solicitud<br><b>Then</b> el servicio devuelve una respuesta indicando que la alerta no fue encontrada. |

##### **US63 - Proporcionar servicios de datos históricos y reportes**

| Campo | Valor |
|---|---|
| **Story ID** | US63 |
| **User** | Developer |
| **Priority** | Media |
| **Epic** | EP04 |
| **Title** | Proporcionar servicios de datos históricos y reportes |
| **Description** | Como Developer, quiero que la RESTful API proporcione datos históricos de monitoreo e información de reportes para que las aplicaciones de SafeLab puedan soportar funcionalidades de análisis y generación de reportes. |
| **Acceptance Criteria** | <b>Scenario 1: Proporcionar datos históricos</b><br><b>Given</b> que existe información histórica de monitoreo para los criterios solicitados<br><b>When</b> la RESTful API procesa la solicitud<br><b>Then</b> el servicio devuelve la información histórica disponible.<br><br><b>Scenario 2: Proporcionar información para reportes</b><br><b>Given</b> que existe información de monitoreo requerida para un reporte<br><b>When</b> la RESTful API procesa la solicitud correspondiente<br><b>Then</b> el servicio devuelve la información disponible necesaria para soportar la generación del reporte.<br><br><b>Scenario 3: Información histórica no disponible</b><br><b>Given</b> que no existe información para los criterios solicitados<br><b>When</b> la RESTful API procesa la solicitud<br><b>Then</b> el servicio devuelve una respuesta indicando que no hay información correspondiente disponible. |

##### **US64 - Proporcionar servicios de acceso de usuario**

| Campo | Valor |
|---|---|
| **Story ID** | US64 |
| **User** | Developer |
| **Priority** | Alta |
| **Epic** | EP07 |
| **Title** | Proporcionar servicios de acceso de usuario |
| **Description** | Como Developer, quiero que la RESTful API soporte operaciones de cuenta y acceso de SafeLab para que las aplicaciones móviles puedan utilizar las capacidades de acceso de usuario requeridas. |
| **Acceptance Criteria** | <b>Scenario 1: Soportar acceso de una cuenta válida</b><br><b>Given</b> que se proporciona información válida de una cuenta<br><b>When</b> la RESTful API procesa una operación de acceso soportada<br><b>Then</b> el servicio devuelve la respuesta exitosa correspondiente.<br><br><b>Scenario 2: Soportar operaciones de cuenta</b><br><b>Given</b> que existe una cuenta de SafeLab y se solicita una operación de cuenta soportada<br><b>When</b> la RESTful API procesa la solicitud<br><b>Then</b> el servicio devuelve la respuesta correspondiente a la operación solicitada.<br><br><b>Scenario 3: Información de cuenta no validada</b><br><b>Given</b> que la información proporcionada de la cuenta no puede validarse<br><b>When</b> la RESTful API procesa la solicitud<br><b>Then</b> el servicio devuelve una respuesta indicando que la operación no puede completarse. |

##### **US65 - Soportar almacenamiento local de datos en el dispositivo móvil**

| Campo | Valor |
|---|---|
| **Story ID** | US65 |
| **User** | Developer |
| **Priority** | Alta |
| **Epic** | EP02 |
| **Title** | Soportar almacenamiento local de datos en el dispositivo móvil |
| **Description** | Como Developer, quiero que la aplicación móvil soporte el almacenamiento local de información seleccionada de SafeLab para persistir y recuperar información de monitoreo en el dispositivo. |
| **Acceptance Criteria** | <b>Scenario 1: Persistir información seleccionada</b><br><b>Given</b> que se ha definido información de SafeLab para almacenamiento local<br><b>When</b> la aplicación móvil almacena dicha información<br><b>Then</b> la información permanece persistida en el dispositivo.<br><br><b>Scenario 2: Recuperar información almacenada</b><br><b>Given</b> que se ha almacenado localmente información seleccionada de SafeLab<br><b>When</b> la aplicación móvil solicita la información almacenada<br><b>Then</b> la información persistida puede recuperarse.<br><br><b>Scenario 3: Recuperar la información seleccionada</b><br><b>Given</b> que existe distinta información de SafeLab almacenada localmente<br><b>When</b> la aplicación móvil solicita una información determinada<br><b>Then</b> el almacenamiento local proporciona la información persistida correspondiente a la solicitud. |


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

<p style="text-align: justify;">
El diseño estratégico de SafeLab organiza el dominio alrededor de las capacidades necesarias para el monitoreo ambiental en tiempo real, la gestión de alertas e incidentes, la trazabilidad, los reportes regulatorios, el mantenimiento de equipos, el acceso de usuarios y la visualización de información desde aplicaciones móviles nativas y multiplataforma.
</p>

<p style="text-align: justify;">
A partir de las Epics, User Stories, entrevistas, Needfinding y Ubiquitous Language del capítulo, el dominio se divide en ocho Bounded Contexts: <b>Identity & Access Management</b>, <b>Monitoring Organization</b>, <b>Sensor Monitoring</b>, <b>Alerts & Incident Management</b>, <b>Equipment Condition & Maintenance</b>, <b>Reporting & Compliance</b>, <b>Dashboard & Overview</b> y <b>Audit & Traceability</b>. Los contextos con mayor relación con el valor principal del negocio son Sensor Monitoring, Alerts & Incident Management y Reporting & Compliance, ya que concentran la captura de información ambiental, la respuesta ante desviaciones y la generación de evidencia para control y auditoría.
</p>

### **2.5.1. Event Storming**

<p style="text-align: justify;">
Para el Event Storming estratégico de SafeLab se parte de los principales procesos identificados en las entrevistas y en las User Stories. El flujo comienza con la configuración de sitios, áreas y equipos; continúa con la recepción automática de lecturas ambientales; posteriormente evalúa desviaciones y genera alertas; finalmente registra la atención del incidente, las acciones correctivas, el mantenimiento relacionado y la evidencia de trazabilidad que puede utilizarse en reportes regulatorios. Esta secuencia permite visualizar el dominio completo sin depender todavía de una implementación tecnológica específica.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; padding: 6px;">Orden</th>
      <th style="text-align: center; padding: 6px;">Domain Event</th>
      <th style="text-align: center; padding: 6px;">Origen</th>
      <th style="text-align: center; padding: 6px;">Consecuencia de negocio</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align:center; padding:6px;">1</td><td style="text-align:center; padding:6px;">Monitoring Site Registered</td><td style="text-align:justify; padding:6px;">Un usuario autorizado registra una sede o sitio de monitoreo.</td><td style="text-align:justify; padding:6px;">La organización dispone de un ámbito físico sobre el cual asociar áreas y equipos.</td></tr>
    <tr><td style="text-align:center; padding:6px;">2</td><td style="text-align:center; padding:6px;">Storage Area Created</td><td style="text-align:justify; padding:6px;">Se crea una sala, cámara o área de almacenamiento.</td><td style="text-align:justify; padding:6px;">Los equipos pueden organizarse según su ubicación real.</td></tr>
    <tr><td style="text-align:center; padding:6px;">3</td><td style="text-align:center; padding:6px;">Equipment Registered</td><td style="text-align:justify; padding:6px;">Se incorpora un refrigerador, congelador u otro equipo monitoreado.</td><td style="text-align:justify; padding:6px;">El equipo queda disponible para recibir sensores y reglas de monitoreo.</td></tr>
    <tr><td style="text-align:center; padding:6px;">4</td><td style="text-align:center; padding:6px;">Sensor Reading Received</td><td style="text-align:justify; padding:6px;">Un sensor o gateway envía una nueva lectura.</td><td style="text-align:justify; padding:6px;">SafeLab almacena temperatura, humedad, timestamp y origen de la medición.</td></tr>
    <tr><td style="text-align:center; padding:6px;">5</td><td style="text-align:center; padding:6px;">Environmental Threshold Exceeded</td><td style="text-align:justify; padding:6px;">Una lectura queda fuera del rango configurado.</td><td style="text-align:justify; padding:6px;">Se inicia el proceso de evaluación de una desviación.</td></tr>
    <tr><td style="text-align:center; padding:6px;">6</td><td style="text-align:center; padding:6px;">Alert Generated</td><td style="text-align:justify; padding:6px;">Una condición cumple los criterios definidos para una alerta.</td><td style="text-align:justify; padding:6px;">Se registra la alerta y se prepara su comunicación al personal responsable.</td></tr>
    <tr><td style="text-align:center; padding:6px;">7</td><td style="text-align:center; padding:6px;">Alert Notification Delivered</td><td style="text-align:justify; padding:6px;">El servicio de notificación comunica la alerta.</td><td style="text-align:justify; padding:6px;">El personal conoce el incidente aun cuando no se encuentra frente al equipo.</td></tr>
    <tr><td style="text-align:center; padding:6px;">8</td><td style="text-align:center; padding:6px;">Alert Acknowledged</td><td style="text-align:justify; padding:6px;">Un usuario confirma que la alerta fue atendida.</td><td style="text-align:justify; padding:6px;">SafeLab conserva evidencia del responsable y momento de atención.</td></tr>
    <tr><td style="text-align:center; padding:6px;">9</td><td style="text-align:center; padding:6px;">Incident Opened</td><td style="text-align:justify; padding:6px;">La desviación requiere seguimiento formal.</td><td style="text-align:justify; padding:6px;">Se crea un incidente asociado al equipo, alerta y periodo afectado.</td></tr>
    <tr><td style="text-align:center; padding:6px;">10</td><td style="text-align:center; padding:6px;">Corrective Action Recorded</td><td style="text-align:justify; padding:6px;">El personal ejecuta y registra una acción.</td><td style="text-align:justify; padding:6px;">Se mantiene trazabilidad de la respuesta aplicada.</td></tr>
    <tr><td style="text-align:center; padding:6px;">11</td><td style="text-align:center; padding:6px;">Maintenance Record Registered</td><td style="text-align:justify; padding:6px;">Se realiza mantenimiento preventivo o correctivo.</td><td style="text-align:justify; padding:6px;">Se actualiza el historial de condición y confiabilidad del equipo.</td></tr>
    <tr><td style="text-align:center; padding:6px;">12</td><td style="text-align:center; padding:6px;">Compliance Report Generated</td><td style="text-align:justify; padding:6px;">Un usuario solicita evidencia de un periodo o equipo.</td><td style="text-align:justify; padding:6px;">Se consolida información histórica para control y auditoría.</td></tr>
    <tr><td style="text-align:center; padding:6px;">13</td><td style="text-align:center; padding:6px;">Audit Entry Appended</td><td style="text-align:justify; padding:6px;">Una operación relevante modifica o consulta información sensible.</td><td style="text-align:justify; padding:6px;">Se agrega una entrada inmutable al historial de auditoría.</td></tr>
  </tbody>
</table>

<p style="text-align: justify;">
Además del flujo principal, se consideran eventos relacionados con el acceso al sistema, como <b>User Registered</b>, <b>User Authenticated</b> y <b>User Role Assigned</b>. Estos eventos pertenecen a un contexto de soporte y permiten controlar quién puede consultar, registrar o administrar información operacional.
</p>


<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/event-storming.png" alt="SafeLab Strategic Event Storming" width="95%">
</p>


#### **2.5.1.1. Candidate Context Discovery**

<p style="text-align: justify;">
La identificación de los Candidate Bounded Contexts combina las técnicas <b>start-with-value</b> y <b>look-for-pivotal-events</b>. Primero se agrupan los eventos que producen el valor principal de SafeLab, especialmente la recepción de lecturas ambientales, la detección de desviaciones, la atención de incidentes y la generación de evidencia regulatoria. Luego se utilizan los eventos que representan cambios importantes de estado para separar responsabilidades con reglas, vocabulario y ritmos de cambio diferentes.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align:center; padding:6px;">Candidate Bounded Context</th>
      <th style="text-align:center; padding:6px;">Clasificación estratégica</th>
      <th style="text-align:center; padding:6px;">Responsabilidad principal</th>
      <th style="text-align:center; padding:6px;">Requisitos relacionados</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align:center; padding:6px;">Identity & Access Management</td><td style="text-align:center; padding:6px;">Generic</td><td style="text-align:justify; padding:6px;">Registro, autenticación, recuperación de acceso y asignación de roles.</td><td style="text-align:justify; padding:6px;">EP07; US51-US55, US59 y US64.</td></tr>
    <tr><td style="text-align:center; padding:6px;">Monitoring Organization</td><td style="text-align:center; padding:6px;">Supporting</td><td style="text-align:justify; padding:6px;">Organización de sitios, áreas de almacenamiento y equipos monitoreados.</td><td style="text-align:justify; padding:6px;">EP01; US01-US08 y US60.</td></tr>
    <tr><td style="text-align:center; padding:6px;">Sensor Monitoring</td><td style="text-align:center; padding:6px;">Core</td><td style="text-align:justify; padding:6px;">Captura y consulta de temperatura, humedad, estado y continuidad de las lecturas.</td><td style="text-align:justify; padding:6px;">EP02; US09-US17 y US61.</td></tr>
    <tr><td style="text-align:center; padding:6px;">Alerts & Incident Management</td><td style="text-align:center; padding:6px;">Core</td><td style="text-align:justify; padding:6px;">Evaluación de desviaciones, alertas, notificaciones, reconocimiento e incidentes.</td><td style="text-align:justify; padding:6px;">EP03; US18-US26, US32, US44, US46 y US62.</td></tr>
    <tr><td style="text-align:center; padding:6px;">Equipment Condition & Maintenance</td><td style="text-align:center; padding:6px;">Supporting</td><td style="text-align:justify; padding:6px;">Estado, confiabilidad, rendimiento, uso e historial de mantenimiento.</td><td style="text-align:justify; padding:6px;">EP05; US35-US42.</td></tr>
    <tr><td style="text-align:center; padding:6px;">Reporting & Compliance</td><td style="text-align:center; padding:6px;">Core</td><td style="text-align:justify; padding:6px;">Históricos, comparaciones, exportaciones y generación de reportes para control y auditoría.</td><td style="text-align:justify; padding:6px;">EP04; US27-US34 y US63.</td></tr>
    <tr><td style="text-align:center; padding:6px;">Dashboard & Overview</td><td style="text-align:center; padding:6px;">Supporting</td><td style="text-align:justify; padding:6px;">Resumen operacional, totales, tendencias e información crítica para decisiones rápidas.</td><td style="text-align:justify; padding:6px;">EP06; US43-US50.</td></tr>
    <tr><td style="text-align:center; padding:6px;">Audit & Traceability</td><td style="text-align:center; padding:6px;">Supporting</td><td style="text-align:justify; padding:6px;">Registro inmutable de acciones, cambios, responsables y correlación de eventos para trazabilidad.</td><td style="text-align:justify; padding:6px;">Necesidades de entrevistas, Incident Log, Compliance Report y requisitos transversales de auditoría.</td></tr>
  </tbody>
</table>

<p style="text-align: justify;">
La separación de responsabilidades prioriza los límites que aparecen de forma consistente en los requisitos actuales. Identity & Access Management concentra identidad, autenticación y roles; Reporting & Compliance reúne históricos, exportación y evidencia regulatoria; y Equipment Condition & Maintenance agrupa la evaluación de condición, confiabilidad e historial de mantenimiento. Esta organización mantiene cada capacidad dentro de un contexto con lenguaje y reglas de negocio coherentes.
</p>


<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/candidate-context-discovery/candidate-context-discovery.png" alt="SafeLab Candidate Context Discovery" width="95%">
</p>

#### **2.5.1.2. Domain Message Flows Modeling**

<p style="text-align: justify;">
El Domain Message Flows Modeling representa cómo los Bounded Contexts colaboran para completar los escenarios de negocio mediante Domain Storytelling. Los actores, objetos de dominio y mensajes permiten visualizar la secuencia de colaboración en los flujos principales de SafeLab.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align:center; padding:6px;">Flujo</th>
      <th style="text-align:center; padding:6px;">Secuencia entre contextos</th>
      <th style="text-align:center; padding:6px;">Resultado</th>
    </tr>
  </thead>
  <tbody>
    <tr><td style="text-align:center; padding:6px;">F1 - Configuración del monitoreo</td><td style="text-align:justify; padding:6px;">Identity & Access Management → Monitoring Organization → Sensor Monitoring.</td><td style="text-align:justify; padding:6px;">Un usuario autorizado registra la ubicación y el equipo, y posteriormente vincula el origen de telemetría.</td></tr>
    <tr><td style="text-align:center; padding:6px;">F2 - Recepción de telemetría</td><td style="text-align:justify; padding:6px;">IoT Sensor/Gateway → Sensor Monitoring → Dashboard & Overview → Audit & Traceability.</td><td style="text-align:justify; padding:6px;">La lectura queda registrada, disponible para consulta y trazada.</td></tr>
    <tr><td style="text-align:center; padding:6px;">F3 - Desviación y alerta</td><td style="text-align:justify; padding:6px;">Sensor Monitoring → Alerts & Incident Management → servicio de notificaciones → usuario móvil.</td><td style="text-align:justify; padding:6px;">Una condición fuera de rango se convierte en alerta y es comunicada al responsable.</td></tr>
    <tr><td style="text-align:center; padding:6px;">F4 - Atención del incidente</td><td style="text-align:justify; padding:6px;">Alerts & Incident Management → Audit & Traceability → Reporting & Compliance.</td><td style="text-align:justify; padding:6px;">Quedan registrados el responsable, la atención y la acción correctiva para su posterior auditoría.</td></tr>
    <tr><td style="text-align:center; padding:6px;">F5 - Condición y mantenimiento</td><td style="text-align:justify; padding:6px;">Sensor Monitoring → Equipment Condition & Maintenance → Dashboard & Overview.</td><td style="text-align:justify; padding:6px;">Las tendencias y anomalías pueden utilizarse para evaluar la condición del equipo y registrar mantenimientos.</td></tr>
    <tr><td style="text-align:center; padding:6px;">F6 - Reporte regulatorio</td><td style="text-align:justify; padding:6px;">Reporting & Compliance consulta información de Sensor Monitoring, Alerts & Incident Management, Equipment Condition & Maintenance y Audit & Traceability.</td><td style="text-align:justify; padding:6px;">Se genera un reporte histórico consistente para control o auditoría.</td></tr>
  </tbody>
</table>

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/domain-message-flows-modeling/domain-message-flows-modeling.png" alt="SafeLab Domain Message Flows Modeling" width="95%">
</p>

#### **2.5.1.3. Bounded Context Canvases**

<p style="text-align: justify;">
Cada Candidate Bounded Context se documenta mediante un Bounded Context Canvas que permite visualizar sus responsabilidades, decisiones de negocio, lenguaje ubicuo, mensajes y relaciones con otros contextos de SafeLab.
</p>

##### **Identity & Access Management**

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/bounded-context-canvases/identity-bounded.png" alt="Identity & Access Management Bounded Context Canvas" width="95%">
</p>

##### **Monitoring Organization**

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/bounded-context-canvases/monitoring-bounded.png" alt="Monitoring Organization Bounded Context Canvas" width="95%">
</p>

##### **Sensor Monitoring**

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/bounded-context-canvases/sensor-bounded.png" alt="Sensor Monitoring Bounded Context Canvas" width="95%">
</p>

##### **Alerts & Incident Management**

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/bounded-context-canvases/alerts-bounded.png" alt="Alerts & Incident Management Bounded Context Canvas" width="95%">
</p>

##### **Equipment Condition & Maintenance**

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/bounded-context-canvases/equipment-bounded.png" alt="Equipment Condition & Maintenance Bounded Context Canvas" width="95%">
</p>

##### **Reporting & Compliance**

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/bounded-context-canvases/reporting-bounded.png" alt="Reporting & Compliance Bounded Context Canvas" width="95%">
</p>

##### **Dashboard & Overview**

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/bounded-context-canvases/dashboard-bounded.png" alt="Dashboard & Overview Bounded Context Canvas" width="95%">
</p>

##### **Audit & Traceability**

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/event-storming/bounded-context-canvases/audit-bounded.png" alt="Audit & Traceability Bounded Context Canvas" width="95%">
</p>

### **2.5.2. Context Mapping**

<p style="text-align: justify;">
El Context Map organiza las dependencias de forma que los contextos core mantengan bajo acoplamiento. Las relaciones internas se modelan principalmente como <b>Customer/Supplier</b>, donde un upstream publica información que un downstream necesita para cumplir una capacidad. Las integraciones con sistemas externos se aíslan mediante <b>Anti-Corruption Layer</b>, evitando que los modelos externos condicionen el modelo interno de SafeLab. Los contextos core evolucionan de forma independiente y no comparten un Shared Kernel.
</p>

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Upstream</th><th style="text-align:center;padding:6px;">Downstream</th><th style="text-align:center;padding:6px;">Patrón</th><th style="text-align:center;padding:6px;">Relación</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">Google Authentication</td><td style="text-align:center;padding:6px;">Identity & Access Management</td><td style="text-align:center;padding:6px;">Anti-Corruption Layer</td><td style="text-align:justify;padding:6px;">El adaptador traduce identidad externa a User Account y permisos internos.</td></tr>
<tr><td style="text-align:center;padding:6px;">IoT Sensor / Gateway</td><td style="text-align:center;padding:6px;">Sensor Monitoring</td><td style="text-align:center;padding:6px;">Anti-Corruption Layer</td><td style="text-align:justify;padding:6px;">Se normalizan formatos, unidades y estados antes de crear lecturas del dominio.</td></tr>
<tr><td style="text-align:center;padding:6px;">Monitoring Organization</td><td style="text-align:center;padding:6px;">Sensor Monitoring</td><td style="text-align:center;padding:6px;">Customer/Supplier</td><td style="text-align:justify;padding:6px;">Sensor Monitoring necesita equipo, área y sitio válidos para asociar telemetría.</td></tr>
<tr><td style="text-align:center;padding:6px;">Sensor Monitoring</td><td style="text-align:center;padding:6px;">Alerts & Incident Management</td><td style="text-align:center;padding:6px;">Customer/Supplier</td><td style="text-align:justify;padding:6px;">Publica lecturas y estados utilizados para evaluar reglas de alerta.</td></tr>
<tr><td style="text-align:center;padding:6px;">Sensor Monitoring</td><td style="text-align:center;padding:6px;">Equipment Condition & Maintenance</td><td style="text-align:center;padding:6px;">Customer/Supplier</td><td style="text-align:justify;padding:6px;">Aporta señales e históricos utilizados para analizar condición y confiabilidad.</td></tr>
<tr><td style="text-align:center;padding:6px;">Alerts & Incident Management</td><td style="text-align:center;padding:6px;">Reporting & Compliance</td><td style="text-align:center;padding:6px;">Customer/Supplier</td><td style="text-align:justify;padding:6px;">Aporta alertas, incidentes, severidad, atención y acciones correctivas.</td></tr>
<tr><td style="text-align:center;padding:6px;">Sensor Monitoring</td><td style="text-align:center;padding:6px;">Reporting & Compliance</td><td style="text-align:center;padding:6px;">Customer/Supplier</td><td style="text-align:justify;padding:6px;">Aporta series históricas de temperatura y humedad.</td></tr>
<tr><td style="text-align:center;padding:6px;">Contextos operacionales</td><td style="text-align:center;padding:6px;">Dashboard & Overview</td><td style="text-align:center;padding:6px;">Conformist / Read Model</td><td style="text-align:justify;padding:6px;">El Dashboard consume representaciones publicadas sin redefinir las reglas transaccionales de los contextos fuente.</td></tr>
<tr><td style="text-align:center;padding:6px;">Todos los contextos auditables</td><td style="text-align:center;padding:6px;">Audit & Traceability</td><td style="text-align:center;padding:6px;">Customer/Supplier mediante eventos</td><td style="text-align:justify;padding:6px;">Los contextos publican eventos de negocio y auditoría para mantener un historial append-only.</td></tr>
</tbody>
</table>

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/context-mapping/context-mapping.png" alt="SafeLab Context Map" width="95%">
</p>

### **2.5.3. Software Architecture**

<p style="text-align: justify;">
La arquitectura de SafeLab incluye una <b>Native Mobile Application</b>, una <b>Cross-Platform Mobile Application</b>, servicios <b>RESTful</b> de desarrollo interno, almacenamiento local en el dispositivo y un <b>Landing Page</b> estático. También incorpora los sensores o gateways que proporcionan lecturas ambientales y los servicios externos utilizados para autenticación y notificaciones.
</p>

#### **2.5.3.1. Software Architecture Context Level Diagrams**

<p style="text-align: justify;">
El Context Diagram presenta a <b>SafeLab</b> como sistema central y muestra a las personas y sistemas externos con los que interactúa. Los usuarios principales son el personal de laboratorios hospitalarios y el personal de empresas farmacéuticas. Ambos consultan información ambiental, reciben alertas y revisan históricos y reportes; los perfiles con permisos de supervisión administran sitios, equipos, límites, mantenimiento y roles.
</p>

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento externo</th><th style="text-align:center;padding:6px;">Relación con SafeLab</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">Hospital Laboratory Staff</td><td style="text-align:justify;padding:6px;">Consulta monitoreo, alertas, estado de equipos, históricos y reportes desde la aplicación móvil.</td></tr>
<tr><td style="text-align:center;padding:6px;">Pharmaceutical Company Staff</td><td style="text-align:justify;padding:6px;">Gestiona trazabilidad, monitoreo, alertas, mantenimiento y evidencia de cumplimiento.</td></tr>
<tr><td style="text-align:center;padding:6px;">IoT Sensors / Gateway</td><td style="text-align:justify;padding:6px;">Envía lecturas ambientales y estado de equipos hacia los servicios internos.</td></tr>
<tr><td style="text-align:center;padding:6px;">Google Authentication Service</td><td style="text-align:justify;padding:6px;">Proveedor externo utilizado para el flujo de autenticación con cuenta Google.</td></tr>
<tr><td style="text-align:center;padding:6px;">Mobile Notification Service</td><td style="text-align:justify;padding:6px;">Entrega notificaciones al dispositivo cuando SafeLab genera una alerta.</td></tr>
</tbody>
</table>

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/software-architecture/context-level-ciagrams/context-level-diagram.png" alt="SafeLab Software Architecture Context Level Diagram" width="95%">
</p>

#### **2.5.3.2. Software Architecture Container Level Diagrams**

<p style="text-align: justify;">
El Container Diagram muestra cómo se distribuyen las responsabilidades entre los productos digitales, los servicios internos y los almacenes de datos que conforman SafeLab.
</p>

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Container</th><th style="text-align:center;padding:6px;">Responsabilidad</th><th style="text-align:center;padding:6px;">Tecnología</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">Static Landing Page</td><td style="text-align:justify;padding:6px;">Presenta SafeLab, propuesta de valor, información del producto, términos y acceso al ecosistema.</td><td style="text-align:center;padding:6px;">Tecnologías web estáticas para publicación del Landing Page.</td></tr>
<tr><td style="text-align:center;padding:6px;">Native Mobile Application</td><td style="text-align:justify;padding:6px;">Experiencia móvil nativa para autenticación, monitoreo, alertas, dashboard, históricos y capacidades que requieran integración con el dispositivo.</td><td style="text-align:center;padding:6px;">SDK y componentes nativos de la plataforma móvil</td></tr>
<tr><td style="text-align:center;padding:6px;">Cross-Platform Mobile Application</td><td style="text-align:justify;padding:6px;">Experiencia multiplataforma equivalente alineada a los principales User Goals del producto.</td><td style="text-align:center;padding:6px;">Framework multiplataforma para dispositivos móviles</td></tr>
<tr><td style="text-align:center;padding:6px;">Local Mobile Storage</td><td style="text-align:justify;padding:6px;">Persistencia local de información seleccionada para mejorar continuidad y experiencia del usuario móvil.</td><td style="text-align:center;padding:6px;">Almacenamiento local seguro en el dispositivo</td></tr>
<tr><td style="text-align:center;padding:6px;">SafeLab RESTful API</td><td style="text-align:justify;padding:6px;">Expone casos de uso, coordina Bounded Contexts, valida reglas y proporciona información a las aplicaciones.</td><td style="text-align:center;padding:6px;">Servicios RESTful del backend de SafeLab</td></tr>
<tr><td style="text-align:center;padding:6px;">Operational Database</td><td style="text-align:justify;padding:6px;">Persistencia de usuarios, organización, equipos, lecturas, alertas, incidentes, mantenimientos, reportes y auditoría.</td><td style="text-align:center;padding:6px;">Base de datos operacional</td></tr>
</tbody>
</table>

<p style="text-align: justify;">
Los sensores, Google Authentication y el proveedor de notificaciones móviles se representan como sistemas externos, no como containers internos de SafeLab. Las aplicaciones móviles consumen el RESTful API y mantienen únicamente la información local estrictamente necesaria según las User Stories y el alcance definido.
</p>

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/software-architecture/container-level-diagrams/container-level-diagram.png" alt="SafeLab Software Architecture Container Level Diagram" width="95%">
</p>


#### **2.5.3.3. Software Architecture Deployment Diagrams**

<p style="text-align: justify;">
El Deployment Diagram representa la distribución física de SafeLab y las conexiones entre dispositivos y servicios. La arquitectura contempla <b>Mobile Device</b> para las aplicaciones móviles y el almacenamiento local, <b>IoT Sensor/Gateway</b> para la captura de datos ambientales, <b>Static Web Hosting</b> para el Landing Page, <b>Cloud Application Runtime</b> para el RESTful API, <b>Database Service</b> para la información operacional y <b>Third-Party Services</b> para autenticación y notificaciones.
</p>

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Deployment Node</th><th style="text-align:center;padding:6px;">Artefactos desplegados</th><th style="text-align:center;padding:6px;">Comunicación principal</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">User Mobile Device</td><td style="text-align:justify;padding:6px;">Native Mobile App / Cross-Platform Mobile App / Local Storage.</td><td style="text-align:justify;padding:6px;">HTTPS con RESTful API y comunicación con servicios del dispositivo.</td></tr>
<tr><td style="text-align:center;padding:6px;">IoT Sensor or Gateway</td><td style="text-align:justify;padding:6px;">Firmware o servicio de adquisición de telemetría.</td><td style="text-align:justify;padding:6px;">Canal seguro hacia el backend o adaptador de ingestión.</td></tr>
<tr><td style="text-align:center;padding:6px;">Static Web Hosting</td><td style="text-align:justify;padding:6px;">Landing Page.</td><td style="text-align:justify;padding:6px;">HTTPS desde navegador.</td></tr>
<tr><td style="text-align:center;padding:6px;">Cloud Application Runtime</td><td style="text-align:justify;padding:6px;">RESTful API y componentes de aplicación.</td><td style="text-align:justify;padding:6px;">HTTPS con móviles y conexiones privadas/seguras con base de datos y servicios externos.</td></tr>
<tr><td style="text-align:center;padding:6px;">Database Service</td><td style="text-align:justify;padding:6px;">Esquema operacional y registros de auditoría.</td><td style="text-align:justify;padding:6px;">Acceso restringido desde el backend.</td></tr>
<tr><td style="text-align:center;padding:6px;">Third-Party Services</td><td style="text-align:justify;padding:6px;">Autenticación Google y servicio de notificaciones móviles.</td><td style="text-align:justify;padding:6px;">APIs/SDKs seguros desde backend o aplicación según la integración elegida.</td></tr>
</tbody>
</table>

<p align="center">
  <img src="../assets/07-chapter-2/strategic-level-ddd/software-architecture/deployment-diagrams/deployment-diagram.png" alt="SafeLab Software Architecture Deployment Diagram" width="95%">
</p>

## **2.6. Tactical-Level Domain-Driven Design**

<p style="text-align: justify;">
La perspectiva táctica define el modelo interno de cada Bounded Context a partir de las User Stories, las reglas de negocio y el Ubiquitous Language de SafeLab. La organización por Domain, Application, Interface e Infrastructure Layer mantiene separadas las reglas del dominio de los mecanismos de entrega, integración y persistencia.
</p>

### **2.6.1. Bounded Context: Identity & Access Management**

<p style="text-align: justify;">
Este contexto controla el ciclo de vida de las cuentas, autenticación y autorización. Reúne las capacidades que en el Product Backlog corresponden al registro, login con correo y Google, recuperación de contraseña, cierre de sesión y asignación de roles.
</p>

#### **2.6.1.1. Domain Layer**

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento</th><th style="text-align:center;padding:6px;">Tipo</th><th style="text-align:center;padding:6px;">Atributos principales</th><th style="text-align:center;padding:6px;">Operaciones principales</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">UserAccount</td><td style="text-align:center;padding:6px;">Aggregate Root / Entity</td><td style="text-align:justify;padding:6px;">userId, email, status, roles, createdAt.</td><td style="text-align:justify;padding:6px;">activate(), deactivate(), assignRole(), removeRole().</td></tr>
<tr><td style="text-align:center;padding:6px;">Role</td><td style="text-align:center;padding:6px;">Entity</td><td style="text-align:justify;padding:6px;">roleId, name, permissions.</td><td style="text-align:justify;padding:6px;">grants(permission).</td></tr>
<tr><td style="text-align:center;padding:6px;">EmailAddress</td><td style="text-align:center;padding:6px;">Value Object</td><td style="text-align:justify;padding:6px;">value.</td><td style="text-align:justify;padding:6px;">validate(), normalize().</td></tr>
<tr><td style="text-align:center;padding:6px;">UserRepository</td><td style="text-align:center;padding:6px;">Repository Interface</td><td style="text-align:justify;padding:6px;">-</td><td style="text-align:justify;padding:6px;">save(), findById(), findByEmail().</td></tr>
</tbody>
</table>

#### **2.6.1.2. Interface Layer**

<p style="text-align: justify;">
La Interface Layer incluye <b>AuthController</b> para registro, autenticación, recuperación y logout, <b>UserAccessController</b> para consulta y asignación de roles, y <b>GoogleAuthenticationConsumer</b> para la integración con autenticación externa. Esta capa traduce las solicitudes hacia comandos y consultas de Application Layer.
</p>

#### **2.6.1.3. Application Layer**

<p style="text-align: justify;">
La Application Layer utiliza <b>RegisterUserCommandHandler</b>, <b>AuthenticateUserCommandHandler</b>, <b>AuthenticateWithGoogleCommandHandler</b>, <b>RecoverPasswordCommandHandler</b>, <b>LogoutUserCommandHandler</b> y <b>AssignUserRoleCommandHandler</b>. Estas clases coordinan el agregado UserAccount y los puertos de seguridad sin contener detalles de persistencia.
</p>

#### **2.6.1.4 Infrastructure Layer**

<p style="text-align: justify;">
La Infrastructure Layer incluye <b>UserRepositoryImpl</b>, <b>GoogleAuthenticationAdapter</b>, <b>PasswordHasher</b>, <b>TokenService</b> y el acceso al servicio de correo. La integración con Google se mantiene detrás de un Anti-Corruption Layer para que el modelo externo no determine la estructura de UserAccount.
</p>

#### **2.6.1.5. Bounded Context Software Architecture Component Level Diagrams**

<p style="text-align: justify;">
El Component Diagram muestra Auth Controller, User Access Controller, Application Services/Handlers, Domain Model, Repository Port, Repository Adapter y External Authentication Adapter, evidenciando las dependencias entre las capas del contexto.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/01-bc-iam/component-level-diagrams/component-diagram.png" alt="Identity and Access Management Component Diagram" width="90%"></p>

#### **2.6.1.6. Bounded Context Software Architecture Code Level Diagrams**

<p style="text-align: justify;">
El nivel de código muestra cómo los componentes se materializan en clases e interfaces, manteniendo la dirección de dependencias desde Interface e Infrastructure hacia Application y Domain mediante puertos.
</p>

##### **2.6.1.6.1. Bounded Context Domain Layer Class Diagrams**

<p style="text-align: justify;">
El Class Diagram integra UserAccount, Role, EmailAddress, identificadores, enumeraciones de estado, UserRepository y sus relaciones dentro del modelo de identidad y acceso.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/01-bc-iam/code-level-diagram/class-diagram/domain-class-diagram.png" alt="Identity and Access Management Domain Layer Class Diagram" width="90%"></p>

##### **2.6.1.6.2. Bounded Context Database Design Diagram**

<p style="text-align: justify;">
El modelo relacional incluye <b>user_accounts</b>, <b>roles</b>, <b>user_roles</b>, <b>external_identities</b> y <b>password_recovery_requests</b>. Las relaciones representan las primary keys, foreign keys, la unicidad del correo y la asociación N:M entre usuarios y roles.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/01-bc-iam/code-level-diagram/database-diagram/database-diagram.png" alt="Identity and Access Management Database Design Diagram" width="90%"></p>

### **2.6.2. Bounded Context: Monitoring Organization**

<p style="text-align: justify;">
Este contexto representa la estructura física y organizacional del monitoreo de SafeLab mediante sitios, áreas de almacenamiento y equipos asociados a cada ubicación.
</p>

#### **2.6.2.1. Domain Layer**

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento</th><th style="text-align:center;padding:6px;">Tipo</th><th style="text-align:center;padding:6px;">Atributos principales</th><th style="text-align:center;padding:6px;">Operaciones principales</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">MonitoringSite</td><td style="text-align:center;padding:6px;">Aggregate Root</td><td style="text-align:justify;padding:6px;">siteId, name, location, status.</td><td style="text-align:justify;padding:6px;">rename(), relocate(), activate().</td></tr>
<tr><td style="text-align:center;padding:6px;">StorageArea</td><td style="text-align:center;padding:6px;">Entity</td><td style="text-align:justify;padding:6px;">areaId, siteId, name, type.</td><td style="text-align:justify;padding:6px;">changeType(), rename().</td></tr>
<tr><td style="text-align:center;padding:6px;">MonitoredEquipment</td><td style="text-align:center;padding:6px;">Aggregate Root</td><td style="text-align:justify;padding:6px;">equipmentId, name, type, identifier, areaId.</td><td style="text-align:justify;padding:6px;">assignToArea(), changeIdentifier().</td></tr>
<tr><td style="text-align:center;padding:6px;">EquipmentIdentifier</td><td style="text-align:center;padding:6px;">Value Object</td><td style="text-align:justify;padding:6px;">value.</td><td style="text-align:justify;padding:6px;">validate().</td></tr>
</tbody>
</table>

#### **2.6.2.2. Interface Layer**

<p style="text-align: justify;">
La Interface Layer incluye <b>MonitoringSiteController</b>, <b>StorageAreaController</b> y <b>EquipmentController</b>, responsables de exponer operaciones para registrar, listar, buscar y asociar los elementos de la organización de monitoreo.
</p>

#### **2.6.2.3. Application Layer**

<p style="text-align: justify;">
La Application Layer utiliza <b>RegisterMonitoringSiteHandler</b>, <b>CreateStorageAreaHandler</b>, <b>RegisterEquipmentHandler</b>, <b>AssignEquipmentToAreaHandler</b>, <b>SearchEquipmentHandler</b> y consultas para recuperar sitios, áreas y equipos.
</p>

#### **2.6.2.4 Infrastructure Layer**

<p style="text-align: justify;">
La Infrastructure Layer implementa los repositorios de sitios, áreas y equipos, además de los mappers entre modelos de persistencia y objetos de dominio. La integración con identificadores externos de equipos se encapsula mediante un adapter.
</p>

#### **2.6.2.5. Bounded Context Software Architecture Component Level Diagrams**

<p style="text-align: justify;">
El Component Diagram representa la separación entre controllers, application handlers, modelo de dominio, repositorios e integración de ubicación, manteniendo como responsabilidad central la organización del entorno monitoreado.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/02-bc-monitoring/component-level-diagrams/component-diagram.png" alt="Monitoring Organization Component Diagram" width="90%"></p>

#### **2.6.2.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.2.6.1. Bounded Context Domain Layer Class Diagrams**

<p style="text-align: justify;">
El Class Diagram muestra <b>MonitoringSite</b>, <b>StorageArea</b> y <b>MonitoredEquipment</b> con las relaciones Site 1..* Area y Area 1..* Equipment, además de sus identificadores e interfaces de repositorio.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/02-bc-monitoring/code-level-diagram/class-diagram/domain-class-diagram.png" alt="Monitoring Organization Domain Layer Class Diagram" width="90%"></p>

##### **2.6.2.6.2. Bounded Context Database Design Diagram**

<p style="text-align: justify;">
El modelo de persistencia incluye las tablas <b>monitoring_sites</b>, <b>storage_areas</b> y <b>monitored_equipment</b>. <b>storage_areas</b> referencia a <b>monitoring_sites</b> y <b>monitored_equipment</b> referencia a <b>storage_areas</b>.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/02-bc-monitoring/code-level-diagram/database-diagram/database-diagram.png" alt="Monitoring Organization Database Design Diagram" width="90%"></p>

### **2.6.3. Bounded Context: Sensor Monitoring**

<p style="text-align: justify;">
Este contexto contiene el núcleo de adquisición y consulta de telemetría. Su responsabilidad es mantener lecturas confiables y detectar la ausencia de datos recientes sin asumir la responsabilidad de decidir la respuesta operacional a una desviación.
</p>

#### **2.6.3.1. Domain Layer**

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento</th><th style="text-align:center;padding:6px;">Tipo</th><th style="text-align:center;padding:6px;">Atributos principales</th><th style="text-align:center;padding:6px;">Operaciones principales</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">Sensor</td><td style="text-align:center;padding:6px;">Aggregate Root</td><td style="text-align:justify;padding:6px;">sensorId, equipmentId, type, status, lastSeenAt.</td><td style="text-align:justify;padding:6px;">markOnline(), markOffline(), updateLastSeen().</td></tr>
<tr><td style="text-align:center;padding:6px;">MonitoringReading</td><td style="text-align:center;padding:6px;">Entity</td><td style="text-align:justify;padding:6px;">readingId, sensorId, timestamp, temperature, humidity.</td><td style="text-align:justify;padding:6px;">isRecent(referenceTime).</td></tr>
<tr><td style="text-align:center;padding:6px;">Temperature</td><td style="text-align:center;padding:6px;">Value Object</td><td style="text-align:justify;padding:6px;">value, unit.</td><td style="text-align:justify;padding:6px;">convertTo(unit).</td></tr>
<tr><td style="text-align:center;padding:6px;">Humidity</td><td style="text-align:center;padding:6px;">Value Object</td><td style="text-align:justify;padding:6px;">percentage.</td><td style="text-align:justify;padding:6px;">validateRange().</td></tr>
</tbody>
</table>

#### **2.6.3.2. Interface Layer**

<p style="text-align: justify;">
La Interface Layer incluye <b>MonitoringController</b> para las consultas de datos actuales e históricos y <b>SensorDataConsumer</b> para recibir lecturas desde sensores o gateways.
</p>

#### **2.6.3.3. Application Layer**

<p style="text-align: justify;">
La Application Layer utiliza <b>RecordMonitoringReadingHandler</b>, <b>GetCurrentMonitoringHandler</b>, <b>GetEquipmentMonitoringDetailsHandler</b>, <b>IdentifyEquipmentWithoutRecentDataHandler</b> y <b>GetHistoricalReadingsHandler</b>. La recolección automática se coordina en esta capa sin acoplarla al protocolo físico del sensor.
</p>

#### **2.6.3.4 Infrastructure Layer**

<p style="text-align: justify;">
Incluye <b>SensorRepositoryImpl</b>, <b>MonitoringReadingRepositoryImpl</b>, <b>IoTTelemetryAdapter</b> y, en las aplicaciones móviles, un <b>MonitoringLocalCache</b> para la información seleccionada que deba persistir localmente. El adapter de telemetría normaliza unidades y formatos externos.
</p>

#### **2.6.3.5. Bounded Context Software Architecture Component Level Diagrams**

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/03-bc-sensor/component-level-diagrams/component-diagram.png" alt="Sensor Monitoring Component Diagram" width="90%"></p>

#### **2.6.3.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.3.6.1. Bounded Context Domain Layer Class Diagrams**

<p style="text-align: justify;">
El Class Diagram integra <b>Sensor</b>, <b>MonitoringReading</b>, <b>Temperature</b>, <b>Humidity</b>, estados, enumeraciones, interfaces de repositorio y su relación con <b>EquipmentId</b>.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/03-bc-sensor/code-level-diagram/class-diagram/domain-class-diagram.png" alt="Sensor Monitoring Domain Layer Class Diagram" width="90%"></p>

##### **2.6.3.6.2. Bounded Context Database Design Diagram**

<p style="text-align: justify;">
El modelo de persistencia incluye <b>sensors</b>, <b>monitoring_readings</b> y <b>sensor_status_history</b>. Las lecturas se indexan por sensor, equipo y timestamp para soportar consultas históricas y generación de reportes.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/03-bc-sensor/code-level-diagram/database-diagram/database-diagram.png" alt="Sensor Monitoring Database Design Diagram" width="90%"></p>

### **2.6.4. Bounded Context: Alerts & Incident Management**

<p style="text-align: justify;">
Este contexto fusiona los antiguos Alerts & Notifications e Incident Management porque el Product Backlog móvil actual presenta un flujo continuo desde la detección de una desviación hasta su reconocimiento y revisión histórica. Mantener ambos modelos dentro de un mismo límite reduce coordinación innecesaria para un alcance académico de esta dimensión.
</p>

#### **2.6.4.1. Domain Layer**

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento</th><th style="text-align:center;padding:6px;">Tipo</th><th style="text-align:center;padding:6px;">Atributos principales</th><th style="text-align:center;padding:6px;">Operaciones principales</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">AlertRule</td><td style="text-align:center;padding:6px;">Aggregate Root</td><td style="text-align:justify;padding:6px;">ruleId, equipmentId, variable, min, max, severity.</td><td style="text-align:justify;padding:6px;">evaluate(reading), changeThresholds().</td></tr>
<tr><td style="text-align:center;padding:6px;">Alert</td><td style="text-align:center;padding:6px;">Entity</td><td style="text-align:justify;padding:6px;">alertId, equipmentId, value, severity, status, createdAt, acknowledgedAt.</td><td style="text-align:justify;padding:6px;">acknowledge(userId), isActive().</td></tr>
<tr><td style="text-align:center;padding:6px;">Incident</td><td style="text-align:center;padding:6px;">Aggregate Root</td><td style="text-align:justify;padding:6px;">incidentId, alertId, status, openedAt, closedAt, correctiveActions.</td><td style="text-align:justify;padding:6px;">addCorrectiveAction(), close().</td></tr>
<tr><td style="text-align:center;padding:6px;">CorrectiveAction</td><td style="text-align:center;padding:6px;">Entity</td><td style="text-align:justify;padding:6px;">actionId, description, performedBy, performedAt.</td><td style="text-align:justify;padding:6px;">-</td></tr>
</tbody>
</table>

#### **2.6.4.2. Interface Layer**

<p style="text-align: justify;">
La Interface Layer incluye <b>AlertController</b>, <b>IncidentController</b> y endpoints para configurar límites, listar alertas, consultar detalles, reconocer alertas, revisar incidentes y registrar acciones. También recibe las confirmaciones del servicio de notificaciones.
</p>

#### **2.6.4.3. Application Layer**

<p style="text-align: justify;">
La Application Layer utiliza <b>EvaluateMonitoringReadingHandler</b>, <b>CreateAlertHandler</b>, <b>AcknowledgeAlertHandler</b>, <b>NotifyAlertHandler</b>, <b>OpenIncidentHandler</b>, <b>RegisterCorrectiveActionHandler</b> y <b>GetIncidentHistoryHandler</b>.
</p>

#### **2.6.4.4 Infrastructure Layer**

<p style="text-align: justify;">
La infraestructura incluye repositorios de alertas e incidentes, <b>MobileNotificationAdapter</b>, mappers de persistencia y mecanismos para publicar eventos hacia Audit & Traceability. Las credenciales o detalles del proveedor de notificaciones no deben filtrarse al Domain Layer.
</p>

#### **2.6.4.5. Bounded Context Software Architecture Component Level Diagrams**

<p style="text-align: justify;">
El Component Diagram muestra en un único modelo las responsabilidades internas de alertas e incidentes, desde la evaluación de lecturas y generación de alertas hasta la apertura de incidentes, el registro de acciones correctivas y la comunicación con los servicios de notificación y auditoría.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/04-bc-alerts/component-level-diagrams/component-diagram.png" alt="Alerts and Incident Management Component Diagram" width="90%"></p>

#### **2.6.4.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.4.6.1. Bounded Context Domain Layer Class Diagrams**

<p style="text-align: justify;">
El Class Diagram integra <b>AlertRule</b>, <b>Alert</b>, <b>Incident</b>, <b>CorrectiveAction</b>, <b>Severity</b>, <b>AlertStatus</b>, <b>IncidentStatus</b> y sus repositorios dentro de un único modelo coherente.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/04-bc-alerts/code-level-diagram/class-diagram/domain-class-diagram.png" alt="Alerts and Incident Management Domain Layer Class Diagram" width="90%"></p>

##### **2.6.4.6.2. Bounded Context Database Design Diagram**

<p style="text-align: justify;">
El modelo de persistencia incluye <b>alert_rules</b>, <b>alerts</b>, <b>alert_acknowledgements</b>, <b>incidents</b> y <b>corrective_actions</b>. <b>incidents</b> referencia la alerta que originó el seguimiento y <b>corrective_actions</b> conserva el actor y timestamp de cada acción.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/04-bc-alerts/code-level-diagram/database-diagram/database-diagram.png" alt="Alerts and Incident Management Database Design Diagram" width="90%"></p>

### **2.6.5. Bounded Context: Equipment Condition & Maintenance**

#### **2.6.5.1. Domain Layer**

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento</th><th style="text-align:center;padding:6px;">Tipo</th><th style="text-align:center;padding:6px;">Atributos principales</th><th style="text-align:center;padding:6px;">Operaciones principales</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">EquipmentCondition</td><td style="text-align:center;padding:6px;">Entity / Snapshot</td><td style="text-align:justify;padding:6px;">equipmentId, condition, evaluatedAt, indicators.</td><td style="text-align:justify;padding:6px;">isAbnormal().</td></tr>
<tr><td style="text-align:center;padding:6px;">MaintenanceRecord</td><td style="text-align:center;padding:6px;">Aggregate Root</td><td style="text-align:justify;padding:6px;">maintenanceId, equipmentId, type, performedAt, notes, performedBy.</td><td style="text-align:justify;padding:6px;">complete(), addObservation().</td></tr>
<tr><td style="text-align:center;padding:6px;">ReliabilityAssessment</td><td style="text-align:center;padding:6px;">Value Object / Domain Result</td><td style="text-align:justify;padding:6px;">score, period, failureCount.</td><td style="text-align:justify;padding:6px;">classify().</td></tr>
</tbody>
</table>

#### **2.6.5.2. Interface Layer**

<p style="text-align: justify;">
La Interface Layer incluye <b>EquipmentConditionController</b> y <b>MaintenanceController</b>, con operaciones para consultar condición, anomalías, rendimiento, confiabilidad, uso e historial de mantenimiento.
</p>

#### **2.6.5.3. Application Layer**

<p style="text-align: justify;">
La Application Layer utiliza <b>EvaluateEquipmentConditionHandler</b>, <b>RegisterMaintenanceHandler</b>, <b>GetMaintenanceHistoryHandler</b>, <b>GetEquipmentReliabilityHandler</b> y <b>GetEquipmentPerformanceHandler</b>.
</p>

#### **2.6.5.4 Infrastructure Layer**

<p style="text-align: justify;">
Incluye repositorios de mantenimiento y condición, además de queries/adapters para obtener históricos desde Sensor Monitoring sin copiar sus reglas internas. Cuando el cálculo requiera información de otros contextos, se utilizan DTOs o eventos publicados.
</p>

#### **2.6.5.5. Bounded Context Software Architecture Component Level Diagrams**

<p style="text-align: justify;">
El Component Diagram organiza las responsabilidades de evaluación de condición, consulta de historial, mantenimiento y confiabilidad del equipo, manteniendo la separación entre Interface, Application, Domain e Infrastructure Layer.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/05-bc-equipment/component-level-diagrams/component-diagram.png" alt="Equipment Condition and Maintenance Component Diagram" width="90%"></p>

#### **2.6.5.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.5.6.1. Bounded Context Domain Layer Class Diagrams**

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/05-bc-equipment/code-level-diagram/class-diagram/domain-class-diagram.png" alt="Equipment Condition and Maintenance Domain Layer Class Diagram" width="90%"></p>

##### **2.6.5.6.2. Bounded Context Database Design Diagram**

<p style="text-align: justify;">
El modelo de persistencia incluye <b>maintenance_records</b>, <b>equipment_condition_snapshots</b> y <b>equipment_reliability_metrics</b>, que conservan el historial de mantenimiento, los estados evaluados del equipo y sus métricas de confiabilidad.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/05-bc-equipment/code-level-diagram/database-diagram/database-diagram.png" alt="Equipment Condition and Maintenance Database Design Diagram" width="90%"></p>

### **2.6.6. Bounded Context: Reporting & Compliance**

<p style="text-align: justify;">
Este contexto concentra las capacidades de consulta histórica, comparación de periodos, generación de reportes, exportación de datos y preparación de evidencia para actividades de control y cumplimiento regulatorio.
</p>

#### **2.6.6.1. Domain Layer**

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento</th><th style="text-align:center;padding:6px;">Tipo</th><th style="text-align:center;padding:6px;">Atributos principales</th><th style="text-align:center;padding:6px;">Operaciones principales</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">ReportRequest</td><td style="text-align:center;padding:6px;">Value Object / Command Model</td><td style="text-align:justify;padding:6px;">equipmentId, period, reportType, format.</td><td style="text-align:justify;padding:6px;">validate().</td></tr>
<tr><td style="text-align:center;padding:6px;">ComplianceReport</td><td style="text-align:center;padding:6px;">Aggregate Root</td><td style="text-align:justify;padding:6px;">reportId, period, generatedAt, generatedBy, status.</td><td style="text-align:justify;padding:6px;">markGenerated(), markFailed().</td></tr>
<tr><td style="text-align:center;padding:6px;">ReportingPeriod</td><td style="text-align:center;padding:6px;">Value Object</td><td style="text-align:justify;padding:6px;">startDate, endDate.</td><td style="text-align:justify;padding:6px;">contains(timestamp), overlaps(other).</td></tr>
</tbody>
</table>

#### **2.6.6.2. Interface Layer**

<p style="text-align: justify;">
La Interface Layer incluye <b>ReportingController</b>, <b>HistoricalDataController</b> y <b>DataExportController</b> para solicitar históricos, comparaciones, reportes y archivos exportables.
</p>

#### **2.6.6.3. Application Layer**

<p style="text-align: justify;">
La Application Layer utiliza <b>GetHistoricalDataHandler</b>, <b>ComparePeriodsHandler</b>, <b>GenerateComplianceReportHandler</b>, <b>DownloadReportHandler</b>, <b>ExportMonitoringDataHandler</b> y <b>GetIncidentHistoryForReportHandler</b>.
</p>

#### **2.6.6.4 Infrastructure Layer**

<p style="text-align: justify;">
Incluye <b>ReportRepositoryImpl</b>, <b>ReportFileGenerator</b>, <b>HistoricalDataQueryAdapter</b> y adaptadores de exportación. El generador de archivos debe consumir modelos ya validados y no incorporar reglas de dominio propias.
</p>

#### **2.6.6.5. Bounded Context Software Architecture Component Level Diagrams**

<p style="text-align: justify;">
El Component Diagram integra la consulta histórica, comparación de periodos, generación de reportes, exportación de datos y acceso a información de auditoría dentro del mismo Bounded Context.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/06-bc-reporting/component-level-diagrams/component-diagram.png" alt="Reporting and Compliance Component Diagram" width="90%"></p>

#### **2.6.6.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.6.6.1. Bounded Context Domain Layer Class Diagrams**

<p style="text-align: justify;">
El Class Diagram integra <b>ComplianceReport</b>, <b>ReportRequest</b>, <b>ReportingPeriod</b>, formatos de exportación y repositorios asociados a la generación y consulta de reportes.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/06-bc-reporting/code-level-diagram/class-diagram/domain-class-diagram.png" alt="Reporting and Compliance Domain Layer Class Diagram" width="90%"></p>

##### **2.6.6.6.2. Bounded Context Database Design Diagram**

<p style="text-align: justify;">
El modelo de persistencia incluye <b>report_requests</b>, <b>generated_reports</b> y metadatos de exportación. La información fuente de lecturas, alertas, incidentes y mantenimiento permanece en sus contextos propietarios, mientras Reporting & Compliance conserva las solicitudes y artefactos generados.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/06-bc-reporting/code-level-diagram/database-diagram/database-diagram.png" alt="Reporting and Compliance Database Design Diagram" width="90%"></p>

### **2.6.7. Bounded Context: Dashboard & Overview**

<p style="text-align: justify;">
Este contexto está orientado principalmente a lectura. Su función es construir una vista agregada para el usuario móvil sin convertirse en propietario de los datos transaccionales de monitoreo, alertas o mantenimiento.
</p>

#### **2.6.7.1. Domain Layer**

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento</th><th style="text-align:center;padding:6px;">Tipo</th><th style="text-align:center;padding:6px;">Atributos principales</th><th style="text-align:center;padding:6px;">Operaciones principales</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">MonitoringSummary</td><td style="text-align:center;padding:6px;">Read Model</td><td style="text-align:justify;padding:6px;">equipmentTotal, activeAlerts, criticalAlerts, offlineEquipment.</td><td style="text-align:justify;padding:6px;">-</td></tr>
<tr><td style="text-align:center;padding:6px;">TrendSeries</td><td style="text-align:center;padding:6px;">Read Model</td><td style="text-align:justify;padding:6px;">metric, period, points.</td><td style="text-align:justify;padding:6px;">-</td></tr>
<tr><td style="text-align:center;padding:6px;">DashboardSnapshot</td><td style="text-align:center;padding:6px;">Read Model</td><td style="text-align:justify;padding:6px;">generatedAt, summary, criticalItems, trends.</td><td style="text-align:justify;padding:6px;">-</td></tr>
</tbody>
</table>

#### **2.6.7.2. Interface Layer**

<p style="text-align: justify;">
La Interface Layer incluye <b>DashboardController</b> y <b>TrendController</b>, que exponen información agregada para las vistas móviles.
</p>

#### **2.6.7.3. Application Layer**

<p style="text-align: justify;">
La Application Layer utiliza <b>GetDashboardOverviewHandler</b>, <b>GetCriticalAlertsSummaryHandler</b>, <b>GetEquipmentWithActiveAlertsHandler</b> y <b>GetMonitoringTrendsHandler</b>.
</p>

#### **2.6.7.4 Infrastructure Layer**

<p style="text-align: justify;">
La Infrastructure Layer utiliza query adapters, projections y vistas optimizadas para lectura. Las proyecciones se construyen a partir de la información publicada por los contextos fuente y se actualizan para mantener la vista general del sistema.
</p>

#### **2.6.7.5. Bounded Context Software Architecture Component Level Diagrams**

<p style="text-align: justify;">
El Component Diagram separa los controllers de consulta, los application handlers, los read models y los adapters que recuperan información de monitoreo, alertas, mantenimiento y auditoría.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/07-bc-dashboard/component-level-diagrams/component-diagram.png" alt="Dashboard and Overview Component Diagram" width="90%"></p>

#### **2.6.7.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.7.6.1. Bounded Context Domain Layer Class Diagrams**

<p style="text-align: justify;">
El modelo de dominio se mantiene ligero y orientado a lectura mediante <b>MonitoringSummary</b>, <b>TrendSeries</b> y <b>DashboardSnapshot</b>, que representan la información agregada necesaria para la vista general.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/07-bc-dashboard/code-level-diagram/class-diagram/domain-class-diagram.png" alt="Dashboard and Overview Domain Layer Class Diagram" width="90%"></p>

##### **2.6.7.6.2. Bounded Context Database Design Diagram**

<p style="text-align: justify;">
La persistencia utiliza <b>dashboard_projections</b>, snapshots de tendencias y vistas materializadas orientadas a lectura. Estas estructuras contienen información derivada de otros Bounded Contexts y no reemplazan a los datos transaccionales de sus contextos propietarios.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/07-bc-dashboard/code-level-diagram/database-diagram/database-diagram.png" alt="Dashboard and Overview Database Design Diagram" width="90%"></p>

### **2.6.8. Bounded Context: Audit & Traceability**

<p style="text-align: justify;">
Este contexto conserva la evidencia necesaria para reconstruir qué ocurrió, cuándo ocurrió y quién realizó o recibió una acción. Se mantiene separado porque las entrevistas farmacéuticas enfatizan la necesidad de registros inalterables para auditorías y porque el Ubiquitous Language ya identifica Incident Log y Compliance Report como conceptos centrales.
</p>

#### **2.6.8.1. Domain Layer**

<table border="1" style="width:100%; border-collapse:collapse;">
<thead><tr><th style="text-align:center;padding:6px;">Elemento</th><th style="text-align:center;padding:6px;">Tipo</th><th style="text-align:center;padding:6px;">Atributos principales</th><th style="text-align:center;padding:6px;">Operaciones principales</th></tr></thead>
<tbody>
<tr><td style="text-align:center;padding:6px;">AuditEntry</td><td style="text-align:center;padding:6px;">Entity</td><td style="text-align:justify;padding:6px;">auditId, actorId, action, targetType, targetId, timestamp, correlationId.</td><td style="text-align:justify;padding:6px;">-</td></tr>
<tr><td style="text-align:center;padding:6px;">TraceabilityRecord</td><td style="text-align:center;padding:6px;">Aggregate / Read Model</td><td style="text-align:justify;padding:6px;">correlationId, eventSequence, startedAt, completedAt.</td><td style="text-align:justify;padding:6px;">append(eventReference).</td></tr>
<tr><td style="text-align:center;padding:6px;">CorrelationId</td><td style="text-align:center;padding:6px;">Value Object</td><td style="text-align:justify;padding:6px;">value.</td><td style="text-align:justify;padding:6px;">generate(), validate().</td></tr>
</tbody>
</table>

#### **2.6.8.2. Interface Layer**

<p style="text-align: justify;">
La Interface Layer incluye <b>AuditTrailController</b> para consultas autorizadas y <b>AuditEventConsumer</b> para recibir eventos generados por otros Bounded Contexts.
</p>

#### **2.6.8.3. Application Layer**

<p style="text-align: justify;">
La Application Layer utiliza <b>AppendAuditEntryHandler</b>, <b>GetAuditTrailHandler</b>, <b>BuildTraceabilityRecordHandler</b> y <b>ExportTraceabilityEvidenceHandler</b>.
</p>

#### **2.6.8.4 Infrastructure Layer**

<p style="text-align: justify;">
La Infrastructure Layer incluye <b>AuditRepositoryImpl</b>, almacenamiento append-only, serializers de eventos y consumers para registrar eventos provenientes de los demás Bounded Contexts sin modificar su contenido original.
</p>

#### **2.6.8.5. Bounded Context Software Architecture Component Level Diagrams**

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/08-bc-audit/component-level-diagrams/component-diagram.png" alt="Audit and Traceability Component Diagram" width="90%"></p>

#### **2.6.8.6. Bounded Context Software Architecture Code Level Diagrams**

##### **2.6.8.6.1. Bounded Context Domain Layer Class Diagrams**

<p style="text-align: justify;">
El Class Diagram integra <b>AuditEntry</b>, <b>TraceabilityRecord</b>, <b>CorrelationId</b> y los contratos de repositorio necesarios para consultar y reconstruir la evidencia de trazabilidad.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/08-bc-audit/code-level-diagram/class-diagram/domain-class-diagram.png" alt="Audit and Traceability Domain Layer Class Diagram" width="90%"></p>

##### **2.6.8.6.2. Bounded Context Database Design Diagram**

<p style="text-align: justify;">
El modelo de persistencia incluye <b>audit_entries</b> y <b>traceability_records</b>. <b>audit_entries</b> registra actor, acción, objeto, fecha/hora y correlation_id, mientras <b>traceability_records</b> agrupa la secuencia de eventos asociada a una misma trazabilidad. Los registros de auditoría se conservan como información append-only durante la operación normal del sistema.
</p>

<p align="center"><img src="../assets/07-chapter-2/tactical-level-ddd/08-bc-audit/code-level-diagram/database-diagram/database-diagram.png" alt="Audit and Traceability Database Design Diagram" width="90%"></p>


# **Chapter III: Solution UI/UX Design**

## **3.1. Product Design**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Las decisiones de diseño de SafeLab abarcan tres experiencias complementarias: la Landing Page pública,
  que comunica la propuesta de valor; la aplicación web, que permite gestionar información operativa según
  los permisos del personal; y la aplicación nativa para Android, orientada a consultar sensores, equipos,
  alertas e incidentes desde un dispositivo móvil. El diseño se sustenta en los User Personas, User
  Journey Maps y Empathy Maps del capítulo II, en el lenguaje ubicuo del dominio y en las historias de
  usuario priorizadas. La experiencia iOS se mantiene como una posibilidad de evolución del producto y no
  se presenta como una aplicación publicada en AV2.
</p>

### **3.1.1. Style Guidelines**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Las guías de estilo establecen los lineamientos visuales y verbales compartidos por la Landing Page, la
  aplicación web y la aplicación Android. Su objetivo es que el usuario reconozca SafeLab en cualquier
  plataforma y que la interfaz comunique con claridad el estado de los equipos monitoreados, aspecto
  central del producto. La guía se resume en la siguiente figura y se detalla en los apartados
  posteriores.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/product-design/style-guidelines/safelab-style-guide.png"
    alt="Guía de estilos de SafeLab"
    width="90%">
</p>

#### **3.1.1.1. General Style Guidelines**

##### **Design System and Design Principles**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La guía de estilos de SafeLab toma como referencia Material Design 3 para la aplicación Android y
  considera las Human Interface Guidelines de Apple como antecedente para una eventual experiencia iOS,
  todavía fuera del alcance desplegado de AV2. La propuesta adapta estos referentes a la identidad de
  SafeLab. Las decisiones se sustentan en cuatro principios de diseño: <b>jerarquía visual</b>, para que
  lo urgente —una alerta crítica o un equipo fuera de rango— sea lo primero que se percibe;
  <b>consistencia</b>, para que los mismos colores, etiquetas y componentes signifiquen lo mismo en la
  Landing Page y en las aplicaciones; <b>contraste y accesibilidad</b>, para que la información sea
  legible en cualquier condición de luz del laboratorio; y <b>simplicidad</b>, para que el personal
  resuelva cada tarea con el menor número de pasos.
</p>

##### **Branding**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  SafeLab se presenta como un aliado confiable y preciso para el personal que protege recursos sensibles,
  resumido en su lema «Monitoreo inteligente, laboratorios más seguros». El logotipo cuenta con tres
  versiones: el isotipo, un escudo que contiene un matraz de laboratorio y ondas de señal inalámbrica, que
  representan la protección de los recursos y el monitoreo remoto; el logotipo, con «SAFE» en azul y «LAB»
  en teal; y el imagotipo, que combina ambos con el lema. El isotipo se utiliza como ícono de las
  aplicaciones y el logotipo e imagotipo en la Landing Page y en la pantalla de inicio de sesión. El
  logotipo se coloca sobre fondos claros, con un área libre mínima equivalente a la altura de la letra
  «S», y no se deforma, rota ni recolorea.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/product-design/style-guidelines/safelab-branding.png"
    alt="Branding de SafeLab"
    width="90%">
</p>

##### **Typography**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La familia tipográfica <b>Inter</b> constituye la referencia de la guía visual y de las maquetas de
  SafeLab por su legibilidad en pantalla. La escala de tamaños diferencia títulos, cuerpo de texto,
  etiquetas y lecturas ambientales. En la aplicación Android, las tipografías utilizadas por los
  componentes dependen de la configuración efectiva del tema de Jetpack Compose; las especificaciones de
  esta tabla se consideran objetivos de diseño y no evidencia de que todos los recursos tipográficos estén
  empaquetados en <code>res/font</code>.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Estilo
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Tamaño / interlineado
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Peso
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Uso
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Display
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        32 / 40 px
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Bold (700)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Títulos principales de la Landing Page y bienvenida
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Título 1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        24 / 32 px
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Semibold (600)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Título de cada pantalla de la aplicación
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Título 2
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        20 / 28 px
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Semibold (600)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Título de alertas, equipos y tarjetas
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Cuerpo
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        16 / 24 px
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Regular (400)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Descripciones y mensajes
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Cuerpo pequeño
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        14 / 20 px
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Regular (400)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipo, sitio y área asociados
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Etiqueta
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        12 / 16 px
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Medium (500)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Marcas de tiempo, contadores y chips
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Lectura
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        30 / 36 px
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Semibold (600), cifras tabulares
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Valores de temperatura y humedad
      </td>
    </tr>
  </tbody>
</table>

<p align="center">
  <img
    src="../assets/08-chapter-3/product-design/style-guidelines/safelab-typography.png"
    alt="Typography de SafeLab"
    width="90%">
</p>

##### **Colors**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La paleta se organiza en tres niveles. Los <b>colores de marca</b> provienen del logotipo y se aplican
  en la Landing Page, donde el objetivo es comunicar la identidad de SafeLab. Los <b>colores de
  interfaz</b> se aplican en las aplicaciones móviles, donde el objetivo es guiar la acción del usuario:
  el primario índigo identifica los elementos interactivos y el acento teal mantiene el vínculo con la
  marca. Los <b>colores semánticos</b> se reservan para los estados de severidad y siempre se acompañan de
  una etiqueta de texto, de modo que el estado no dependa solo del color.
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Para asegurar la legibilidad, el contraste se valida por <b>combinación real de texto y fondo</b>, y no
  solo frente al blanco, conforme a las WCAG 2.1 (World Wide Web Consortium [W3C], 2018): 4,5:1 como
  mínimo para texto normal (criterio 1.4.3, nivel AA) y 3:1 para texto grande —24 px regular o 18,66 px en
  negrita— y para componentes gráficos (criterio 1.4.11). Por ello, cada color semántico se define con
  tres tokens: <b>relleno</b>, para íconos, barras e indicadores; <b>fondo tenue</b>, el relleno al 14 %
  sobre la superficie, para el fondo de los chips; y <b>texto</b>, una variante oscura que es la única que
  se utiliza para escribir sobre fondos claros. El color de relleno nunca se usa como color de texto.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/product-design/style-guidelines/safelab-colors.png"
    alt="Colors de SafeLab"
    width="90%">
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Nivel
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Color
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Código
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Contraste sobre blanco
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Uso
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Marca
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Azul SafeLab
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #0B3A78
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        11,11:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Logotipo, títulos de la Landing Page y final del degradado de los botones principales
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Marca
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Teal SafeLab
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #1BA7B1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        2,91:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Logotipo, íconos y degradados decorativos. No se utiliza para texto ni como fondo de texto blanco
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Marca
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Teal accesible
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #0E7C86
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        4,95:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Inicio del degradado de los botones principales de la Landing Page, con texto blanco
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Marca
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Cian
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #22C7C8
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        2,09:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Acentos y degradados decorativos, sin texto
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Marca
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Fondo landing
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #EEF7F8
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        —
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Fondo de las secciones de la Landing Page
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Interfaz
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Primario
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #4F35E8
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        6,98:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Botones principales, pestaña activa y encabezados
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Interfaz
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Primario oscuro
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #211169
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        15,57:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Estado presionado de los botones
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Interfaz
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Secundario
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #1056D9
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        6,26:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Enlaces y acciones secundarias
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Interfaz
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Acento
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #14B8A6 (relleno) / #0F766E (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        5,47:1 (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Gráficos, indicadores de conexión y enlaces secundarios
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Interfaz
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Superficie
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #F4F7FB / #FFFFFF
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        —
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Fondo de pantallas / tarjetas y hojas inferiores
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Interfaz
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #111827
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        17,74:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto principal
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Interfaz
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto secundario
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #475569
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        7,58:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Metadatos y marcas de tiempo, sobre tarjetas y sobre el fondo de pantalla
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Semántico
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Critical
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #EF4444 (relleno) / #FDE5E5 (fondo tenue) / #B91C1C (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        6,47:1 (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Lectura fuera de rango que requiere atención inmediata
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Semántico
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Warning
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #F59E0B (relleno) / #FEF1DD (fondo tenue) / #92400E (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        7,09:1 (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Lectura cercana al límite o anomalía del equipo
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Semántico
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Normal
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #10B981 (relleno) / #DEF5ED (fondo tenue) / #047857 (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        5,48:1 (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipo con lecturas dentro del rango
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Semántico
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Info
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #3B82F6 (relleno) / #E4EEFE (fondo tenue) / #1D4ED8 (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        6,70:1 (texto)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Eventos informativos, como la pérdida de conexión de un sensor
      </td>
    </tr>
  </tbody>
</table>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La siguiente tabla documenta los pares de color y las relaciones de contraste consignadas en la guía
  visual de SafeLab, incluidas variantes propuestas para aumentar la legibilidad. Los resultados
  representan comprobaciones de la especificación de diseño; no sustituyen una auditoría automática o
  manual de las pantallas desplegadas.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Producto
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Combinación (texto / fondo)
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Antes del ajuste
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Después del ajuste
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Resultado
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Landing Page
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto blanco del botón principal / degradado teal → azul
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #FFFFFF / #1BA7B1 → #0B3A78: 2,91:1 en el extremo teal
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #FFFFFF / #0E7C86 → #0B3A78: 4,95:1 a 11,11:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Landing Page
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto / fondo de sección
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #0B2F6B / #EEF7F8: 11,81:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sin cambios
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Landing Page
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto secundario / fondo de sección
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #3F6A8C / #EEF7F8: 5,28:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sin cambios
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto del botón principal / primario
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #FFFFFF / #4F35E8: 6,98:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sin cambios
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Chip de estado de advertencia (texto / fondo tenue)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #E69A19 / #FCF1DF: 2,09:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #92400E / #FEF1DD: 6,36:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Chip de estado normal (texto / fondo tenue)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #0D9B72 / #DDF1EB: 3,00:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #047857 / #DEF5ED: 4,80:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Chip de estado crítico (texto / fondo tenue)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #E44848 / #FBE5E5: 3,28:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #B91C1C / #FDE5E5: 5,40:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Chip de estado neutro (texto / fondo tenue)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #64748B / #E9ECEF: 4,01:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #475569 / #E9ECEF: 6,39:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto secundario / fondo de pantalla
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #64748B / #F4F7FB: 4,43:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #475569 / #F4F7FB: 7,05:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil (modo oscuro)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Primario / superficie oscura
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #4F35E8 / #0F172A: 2,56:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #7C6CFF / #0F172A: 4,63:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil (modo oscuro)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto del botón principal / primario
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #E5EDF9 / #4F35E8: 5,91:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #0F172A / #7C6CFF: 4,63:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil (modo oscuro)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Chip de estado crítico / fondo tenue oscuro
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #E44848 / tinte sobre #111C31: 3,80:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #FB7185 / #302234: 5,56:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Aplicación móvil (modo oscuro)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Chip de estado neutro / fondo tenue oscuro
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #64748B / tinte sobre #111C31: 3,10:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #9CAEC8 / #1D283E: 6,53:1
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        ✔ Cumple
      </td>
    </tr>
  </tbody>
</table>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La aplicación Android incorpora un <b>modo oscuro</b> activable desde el control de tema. Para los
  componentes especificados, se proponen variantes de color que distinguen superficie, texto, acciones y
  severidad sobre fondos oscuros. En la guía visual se especifica texto oscuro <code>#0F172A</code> sobre
  el primario <code>#7C6CFF</code> para mejorar la legibilidad del contraste de botones.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Rol
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Modo claro
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Modo oscuro
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Primario
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #4F35E8
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #7C6CFF
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto sobre el primario
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #FFFFFF
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #0F172A
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Acento
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #14B8A6
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #2DD4BF
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Superficie
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #F4F7FB
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #0F172A
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Tarjeta
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #FFFFFF
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #111C31
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #111827
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #E5EDF9
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto secundario
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #475569
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #9CAEC8
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Borde
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #E3E9F4
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #24324A
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Texto de Critical / Warning / Normal / Info
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #B91C1C / #92400E / #047857 / #1D4ED8
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #FB7185 / #FBBF24 / #34D399 / #60A5FA
      </td>
    </tr>
  </tbody>
</table>

##### **Spacing**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La propuesta visual utiliza una retícula de 4 y 8 unidades, con valores de espaciado de 4, 8, 12, 16, 24
  y 32 px en diseños web, y unidades independientes de densidad (dp) cuando corresponde a Android. Los
  botones y campos de texto tienen un radio de 12 px, las tarjetas de 16 px y los chips de estado son
  completamente redondeados. Las áreas táctiles se dimensionan tomando como referencia 48 × 48 dp para
  Android; los 44 × 44 pt de iOS quedan como referencia para una implementación posterior. La navegación
  principal se resuelve con una barra inferior de cinco destinos, cada uno con ícono y etiqueta, y los
  íconos son de línea de 2 px en estilo redondeado.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/product-design/style-guidelines/safelab-spacing.png"
    alt="Spacing y componentes de SafeLab"
    width="90%">
</p>

##### **Communication Tone**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  El tono de SafeLab se define en cuatro dimensiones, considerando que los mensajes acompañan decisiones
  críticas sobre la conservación de recursos sensibles:
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Dimensión
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Posición de SafeLab
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Justificación
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Divertido / Serio
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Serio
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Las alertas comunican riesgos para muestras, reactivos y medicamentos, por lo que no se usa humor.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Formal / Casual
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Mayormente formal
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Se emplea un lenguaje profesional y cercano, sin tecnicismos del sistema, adecuado para el
        personal de laboratorio y de calidad.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Respetuoso / Irreverente
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Respetuoso
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Los mensajes no culpan al usuario y se enfocan en la acción que debe realizar.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Entusiasta / Sereno
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sereno
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Ante un incidente, el tono transmite calma y control: se evitan las mayúsculas sostenidas y los
        signos de exclamación repetidos.
      </td>
    </tr>
  </tbody>
</table>

<p align="center">
  <img
    src="../assets/08-chapter-3/product-design/style-guidelines/safelab-tone.png"
    alt="Tono de comunicación de SafeLab"
    width="90%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Cada mensaje responde a tres preguntas: qué ocurrió, dónde ocurrió y qué debe hacer el usuario. Por
  ejemplo, la aplicación muestra «PCR freezer out of range (9.6 °C). Check the equipment and acknowledge
  the alert.» en lugar de «ERROR!!! Threshold exceeded on device #A3F9». La Landing Page y la aplicación
  Android permiten seleccionar inglés o español; las expresiones en inglés incluidas en esta guía son
  ejemplos de rótulos de interfaz, no del idioma obligatorio del informe.
</p>

### **3.1.2. Information Architecture**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La arquitectura de información define cómo se organiza, rotula y encuentra el contenido de SafeLab en la
  Landing Page, la aplicación web y Android. Se diseñó a partir de las tareas más frecuentes e importantes
  de la User Task Matrix —revisar el estado de los equipos, atender alertas, registrar incidentes y
  consultar lecturas históricas— y se refleja en las pantallas definidas en la sección 3.1.4, de modo que
  cada tarea crítica sea accesible en el menor número de pasos desde cualquier pantalla.
</p>

#### **3.1.2.1. Organization Systems**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  SafeLab utiliza esquemas de organización distintos según el tipo de contenido y el producto. La Landing
  Page se organiza de forma <b>secuencial</b>: sus secciones conducen al visitante desde la propuesta de
  valor hasta la consulta del plan, el registro o la solicitud de una demostración. Su estructura sigue el
  orden de los wireframes y mock-ups de la sección 3.1.3.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/product-design/information-architecture/safelab-organization-landing.png"
    alt="Organization Systems de la Landing Page de SafeLab"
    width="90%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La aplicación móvil se organiza de forma <b>jerárquica</b> en dos niveles. El primer nivel es la barra
  de navegación inferior, que reúne las cuatro tareas más frecuentes del personal —Inicio, Sensores,
  Alertas y Equipos— y una quinta pestaña, <b>Más</b>, que agrupa los módulos de consulta menos frecuente
  y la cuenta del usuario. El contenido se organiza según el rol y los permisos disponibles. La propuesta
  reserva la gestión de usuarios y la suscripción al gerente general, mientras que el personal autorizado
  consulta los módulos operativos correspondientes. Dentro de cada pestaña, los registros relacionados se
  agrupan en vistas que el usuario alterna con botones (por ejemplo, Alertas e Incidentes), y cada
  registro abre su detalle y sus acciones disponibles.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/product-design/information-architecture/safelab-organization-app.png"
    alt="Organization Systems de la aplicación móvil de SafeLab"
    width="90%">
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Grupo de información
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Organización visual
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Esquema de categorización
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Justificación
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Landing Page
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Secuencial
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Por tópicos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Las secciones Home, Benefits, Services, Plans, About Product, About Team, Testimonials, FAQ y
        Contact llevan al visitante del problema a la acción.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Inicio (Home)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Jerárquica
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Por estado y prioridad
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        El panel principal muestra primero los indicadores que requieren atención —sensores conectados,
        alertas activas e investigaciones abiertas—, luego los accesos rápidos y las alertas más
        recientes.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensores (Sensors)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Jerárquica
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Por estado
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        La lista de sensores se puede buscar y filtrar por estado (normal, fuera de rango, desconectado);
        cada sensor abre su detalle con la lectura actual y su rango.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas (Alerts)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Jerárquica
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Por severidad y estado
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        La pestaña alterna entre Alertas e Incidentes. Las alertas activas se listan con su severidad y
        estado, y el panel «Reconocer alertas» reúne las que aún no se han atendido.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipos (Equipment)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Jerárquica
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Por estado y cronológico
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        La pestaña alterna entre la lista de equipos y su historial de mantenimiento, que se presenta del
        registro más reciente al más antiguo.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más (More)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Jerárquica
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Por tópicos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Agrupa Sedes y activos, Cumplimiento ambiental, Control remoto, Reportes y análisis, y Auditoría y
        trazabilidad; para el gerente, también Usuarios y permisos, y Suscripción y pagos. Al final se
        ubican Mi perfil y Cerrar sesión.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Acceso (Identity &amp; Access Management)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Secuencial
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        —
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Inicio de sesión → panel principal. Después de autenticarse, el usuario ve solo las pestañas y
        módulos que su rol le permite.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Flujos de varios pasos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Secuencial
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        —
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alerta → Acciones → Reconocer o Escalar (abre un incidente); Incidente → Investigar → Resolver →
        Cerrar; Equipos → Registrar mantenimiento; Reportes → Generar reporte.
      </td>
    </tr>
  </tbody>
</table>

#### **3.1.2.2. Labelling Systems**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  El sistema de rotulación traduce los términos del Ubiquitous Language a etiquetas breves, de una a tres
  palabras, que se usan igual en todas las pantallas. Tanto la Landing Page como la aplicación móvil están
  disponibles en inglés y en español: en la aplicación, el usuario cambia de idioma desde el botón de la
  barra superior y todas las etiquetas se actualizan sin salir de la pantalla en la que se encuentra. Cada
  destino de navegación se acompaña de un ícono y cada estado se acompaña de un color semántico con su
  etiqueta de texto, sin depender únicamente del color.
</p>

##### **Navigation Labels**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Etiqueta (inglés)
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Etiqueta (español)
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Ubicación
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Contenido que agrupa
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Home
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Inicio
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Barra inferior
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Panel principal con indicadores, accesos rápidos y alertas recientes.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensors
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensores
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Barra inferior
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensores asignados, lecturas actuales y estado de conexión.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alerts
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Barra inferior
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas e incidentes, con la opción de reconocer alertas.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipment
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Barra inferior
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipos registrados e historial de mantenimiento.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        More
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Barra inferior
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Módulos de consulta menos frecuente y opciones de la cuenta.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Facilities &amp; assets
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sedes y activos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sedes de la empresa y sus activos.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Environmental compliance
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Cumplimiento ambiental
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Reglas ambientales, evaluaciones e incumplimientos.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Remote control
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Control remoto
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Dispositivos remotos e historial de comandos.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Reports &amp; analytics
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Reportes y análisis
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Reportes generados y su generación.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Audit &amp; traceability
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Auditoría y trazabilidad
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Registro de acciones de los usuarios.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Users &amp; permissions
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Usuarios y permisos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más (solo gerente)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Empleados, invitaciones y accesos.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Subscription &amp; billing
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Suscripción y pagos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más (solo gerente)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Plan, cupos y recibos.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        My profile / Sign out
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Mi perfil / Cerrar sesión
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Más y barra superior
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Datos del usuario y cierre de sesión.
      </td>
    </tr>
  </tbody>
</table>

##### **Domain Labels**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Término del dominio
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Etiqueta (inglés / español)
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Ejemplo en las pantallas
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Facility
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Facility / Sede
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Andinos Central Laboratory
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Monitored Equipment
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipment / Equipo
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Reagent Freezer A
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Environmental Sensor
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensor / Sensor
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Reagent Freezer Temperature · SEN-CLN-001
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Environmental Reading
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Reading / Lectura
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        3.8 °C
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Environmental Threshold
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Range / Rango
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        2–8 °C
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alert
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alert / Alerta
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        PCR freezer out of range
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Incident
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Incident / Incidente
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        INC-001 · PCR freezer deviation
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Maintenance Record
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Maintenance history / Historial de mantenimiento
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Door gasket replaced and alarm tested.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Compliance Report
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Report / Reporte
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Cold Chain Executive Summary
      </td>
    </tr>
  </tbody>
</table>

##### **Action Labels**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Contexto
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Etiqueta (inglés / español)
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Resultado
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Listas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Search records / Buscar registros
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Filtra la lista con el texto ingresado.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Listas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Status / Estado
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Filtra la lista por el estado del registro.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Listas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Refresh data / Actualizar datos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sincroniza la información con SafeLab Platform API.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Inicio
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        View all / Ver todos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Abre la lista completa de alertas.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Acknowledge / Reconocer
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Confirma que el personal atendió la alerta.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Escalate / Escalar
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Escala la alerta y abre un incidente vinculado.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Resolve alert / Resolver alerta
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Marca la alerta como resuelta.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Incidentes
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Investigate / Investigar · Resolve incident / Resolver incidente · Close incident / Cerrar
        incidente
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Avanza el incidente en su ciclo de atención.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensores
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Configure / Configurar · Record reading / Registrar lectura
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Configura los límites del sensor o registra una lectura.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Create incident / Registrar incidente
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Registra un incidente vinculado a una sede.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Add equipment / Agregar equipo
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Registra un nuevo equipo (según permisos).
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Record maintenance / Registrar mantenimiento
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Registra un trabajo de mantenimiento.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensores
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Add sensor / Agregar sensor
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Registra un nuevo sensor (según permisos).
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Reportes
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Generate report / Generar reporte
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Genera el registro de un reporte.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Registros
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Actions / Acciones
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Menú con las acciones que el rol del usuario permite sobre el registro seleccionado.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Cuenta
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sign out / Cerrar sesión
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Cierra la sesión.
      </td>
    </tr>
  </tbody>
</table>

##### **Status Labels**

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Grupo
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Etiquetas (inglés / español)
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Color semántico
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Normales
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Normal / Normal · Online / Conectado · Compliant / Conforme · Resolved / Resuelto · Reviewed /
        Revisado
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Normal
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        De atención
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Pending / Pendiente · Acknowledged / Reconocido · In progress / En progreso · Maintenance /
        Mantenimiento · Offline / Desconectado
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Warning
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Críticos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Critical / Crítico · Open / Abierto · Violation / Incumplimiento · Blocked / Bloqueado · Active
        (alertas e incidentes) / Activo
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Critical
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Otros
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Cancelled / Cancelado y estados sin categoría
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Neutro (texto secundario)
      </td>
    </tr>
  </tbody>
</table>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Las lecturas se muestran con su unidad, por ejemplo, 3.8 °C para temperatura o 46 % para humedad.
</p>

#### **3.1.2.3. SEO Tags and Meta Tags**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los SEO Tags y Meta Tags describen las páginas públicas de SafeLab y facilitan la interpretación de su
  contenido por navegadores y motores de búsqueda; los elementos ASO, en cambio, corresponden a futuras
  fichas de distribución en tiendas móviles. Las palabras clave se seleccionaron a partir de los términos
  que utilizaron los entrevistados para describir su problema, como temperatura, cadena de frío, alertas y
  auditorías de la DIGEMID.
</p>

##### **Landing Page**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La siguiente tabla reúne los metadatos definidos para la Landing Page pública. El selector de idioma
  modifica los textos de la interfaz y puede actualizar el título visible en el navegador; ello no
  garantiza que todos los motores de búsqueda indexen automáticamente una versión independiente para cada
  idioma.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Etiqueta
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Valor
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Criterio
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        <code>&lt;html lang&gt;</code>
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        en
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Declara el idioma principal de la página.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Title
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab | Real-Time Cold Chain Monitoring
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        41 caracteres; incluye la marca y la palabra clave principal por debajo del límite recomendado de
        60 caracteres.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta description
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab helps clinical laboratories, hospitals and pharmacy networks monitor cold-chain
        conditions, detect risks early and maintain audit-ready traceability.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Resume el público objetivo y los tres beneficios principales (monitoreo, detección temprana y
        trazabilidad).
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta author
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Identifica al responsable del sitio.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta robots
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        index, follow
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Permite indexar la página y seguir sus enlaces.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta theme-color
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        #0b3a78
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Colorea la barra del navegador móvil con el Azul SafeLab.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Viewport
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        width=device-width, initial-scale=1.0, viewport-fit=cover
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Adapta la página al ancho de los dispositivos móviles.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Favicon / apple-touch-icon
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        assets/images/logos/favicon.png
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Identifica la marca en la pestaña, los marcadores y la pantalla de inicio de iOS.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Open Graph
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        og:type, og:title, og:description
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Vista previa al compartir el enlace en redes sociales y aplicaciones de mensajería.
      </td>
    </tr>
  </tbody>
</table>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La implementación puede complementarse con una URL canónica y metadatos Open Graph. Estos valores se
  registran como especificación SEO; su presencia efectiva debe contrastarse con el código publicado de la
  Landing Page.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Etiqueta
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Valor
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Criterio
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Canonical
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        https://meditrack-mobile-app-1acc0238-2620-4949.github.io/safelab-business-website/
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Indica al buscador la URL principal de la página.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        og:url / og:image / og:locale
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        URL pública, imagen del isotipo, en_US con alternativa es_PE
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Completan la tarjeta de vista previa con la dirección, la imagen y el idioma.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta keywords
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        cold chain monitoring, temperature monitoring, humidity monitoring, clinical laboratory,
        pharmaceutical storage, real-time alerts, audit reports, DIGEMID
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Términos del vocabulario de los segmentos objetivo y de la propuesta de valor.
      </td>
    </tr>
  </tbody>
</table>

```html
<link
  rel="canonical"
  href="https://meditrack-mobile-app-1acc0238-2620-4949.github.io/safelab-business-website/"
/>
<meta
  name="keywords"
  content="cold chain monitoring, temperature monitoring, humidity monitoring, clinical laboratory, pharmaceutical storage, real-time alerts, audit reports, DIGEMID"
/>
<meta
  property="og:url"
  content="https://meditrack-mobile-app-1acc0238-2620-4949.github.io/safelab-business-website/"
/>
<meta
  property="og:image"
  content="https://meditrack-mobile-app-1acc0238-2620-4949.github.io/safelab-business-website/assets/images/logos/safelab-shield.png"
/>
<meta property="og:locale" content="en_US" />
<meta property="og:locale:alternate" content="es_PE" />
```

##### **Web Application**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La aplicación web de SafeLab se encuentra desplegada en Render y concentra las funciones de acceso,
  consulta y administración operativa. A diferencia de la Landing Page, sus rutas internas contienen
  información asociada a una sesión y a permisos de acceso. Por ello, la especificación de metadatos
  distingue una portada identificable públicamente de las vistas privadas, que no deben exponerse a
  indexación indiscriminada. Los valores siguientes constituyen criterios de configuración y deben
  verificarse en el código de la aplicación web antes de considerarse metadatos implementados.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Meta Tag
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Valor de referencia
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Propósito
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Title
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab | Clinical Cold Chain Platform
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Identificar la aplicación web y su ámbito operativo.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta description
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Plataforma web para consultar activos, sensores, alertas e incidentes de la cadena de frío
        clínica.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Describir el producto sin incluir información privada de organizaciones.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta keywords
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab, cadena de frío, monitoreo ambiental, sensores, alertas, laboratorios
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Consignar vocabulario representativo del producto.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta author
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        MediTrack — SafeLab
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Identificar la organización responsable del producto.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Meta robots
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        noindex, nofollow (rutas privadas)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Evitar que los buscadores indexen vistas con datos de sesión.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        URL
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        https://safelab-frontend.onrender.com/
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Identificar el origen público del frontend web.
      </td>
    </tr>
  </tbody>
</table>

##### **Mobile Applications (App Store Optimization)**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los elementos ASO de la siguiente tabla constituyen una propuesta de posicionamiento para futuras
  publicaciones de SafeLab en Google Play y App Store. Durante AV2, la aplicación Android se distribuye
  mediante un archivo <code>SafeLab.apk</code> adjunto a GitHub Releases, no mediante una ficha publicada
  en estas tiendas. Se mantienen versiones de los textos comerciales en inglés y español para una eventual
  distribución posterior; la publicación en iOS no forma parte de las entregas desplegadas.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Tienda
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Campo
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Valor (inglés)
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Valor (español)
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Google Play
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Título (máx. 30)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab: Cold Chain Monitor
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab: Monitoreo de frío
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Google Play
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Descripción breve (máx. 80)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Monitor lab temperature and humidity and get real-time alerts.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Monitorea temperatura y humedad del laboratorio con alertas al instante.
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Google Play
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Categoría
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Medical
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Medicina
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        App Store
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Nombre (máx. 30)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        App Store
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Subtítulo (máx. 30)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Lab cold chain monitoring
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Monitoreo de cadena de frío
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        App Store
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Palabras clave (máx. 100)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        temperature,humidity,cold chain,laboratory,pharmacy,alerts,DIGEMID,sensors,reports
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        temperatura,humedad,cadena de frío,laboratorio,farmacia,alertas,DIGEMID,sensores
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        App Store
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Categoría
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Medical (secondary: Productivity)
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Medicina (secundaria: Productividad)
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Ambas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Descripción completa
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab monitors the temperature and humidity of refrigerators, freezers and storage areas in
        clinical laboratories and pharmaceutical companies in real time. Get alerts when equipment goes
        out of range, record corrective actions and generate audit-ready reports.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        SafeLab monitorea en tiempo real la temperatura y la humedad de refrigeradoras, congeladoras y
        almacenes de laboratorios y empresas farmacéuticas. Recibe alertas cuando un equipo sale de rango,
        registra las acciones correctivas y genera reportes para auditorías.
      </td>
    </tr>
  </tbody>
</table>

#### **3.1.2.4. Searching Systems**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los sistemas de búsqueda de SafeLab buscan que el personal de laboratorios hospitalarios y de empresas
  farmacéuticas encuentre rápidamente un equipo, una alerta o un registro histórico, aun cuando la
  cantidad de sitios, áreas, equipos y lecturas aumente con el uso del sistema. Las decisiones se basan en
  las User Stories de la sección 2.4.1 y en lo señalado en las entrevistas de la sección 2.2: los usuarios
  necesitan identificar qué equipo presenta un problema sin recorrer físicamente las instalaciones y
  revisar lo ocurrido en fechas anteriores sin buscar en distintos archivos.
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La Landing Page no requiere un buscador interno porque sus apartados se localizan mediante la navegación
  de la sección 3.1.2.5. Para las listas operativas de Android y de la aplicación web, la propuesta
  combina búsqueda por texto y filtros contextuales, según el conjunto de datos y los permisos del
  usuario. La tabla describe el comportamiento previsto por sección; su disponibilidad concreta se
  contrasta con las vistas implementadas.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Sección
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Opción de búsqueda
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Filtros disponibles
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Presentación de los resultados
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        User Stories
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Búsqueda por texto sobre los datos del equipo, como su nombre, sede o área de almacenamiento.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Estado del equipo.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Tarjetas con el nombre del equipo, una descripción y su chip de estado; cada tarjeta abre el
        detalle del equipo.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        US06, US08, US12, US14
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Búsqueda por texto sobre el título, el equipo o la sede de la alerta.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Estado (activa, reconocida, escalada, resuelta).
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Tarjetas con el título, la severidad y el estado; el panel «Reconocer alertas» reúne las alertas
        activas.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        US20, US22, US23, US44
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Incidentes
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Búsqueda por texto sobre el código, el título o el responsable.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Estado (abierto, en investigación, resuelto, cerrado).
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Tarjetas con el código, el título y el estado del incidente.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        US62
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensores
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Búsqueda por texto sobre el nombre, el código o el tipo de sensor.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Estado de la lectura o de la conexión.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Tarjetas con el nombre del sensor, su lectura actual y su estado.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        US09, US10, US11
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sedes y activos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Búsqueda por texto sobre el nombre o la ciudad de la sede.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        —
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Tarjetas con la sede y sus indicadores.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        US02, US04
      </td>
    </tr>
  </tbody>
</table>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los criterios de diseño adoptados para los mecanismos de búsqueda son los siguientes:
</p>

- **Búsqueda tolerante:** las coincidencias no distinguen mayúsculas ni minúsculas, y se consideran coincidencias parciales.
- **Resultados visibles:** sobre la lista se muestra la cantidad de registros que cumplen la búsqueda y el filtro aplicado.
- **Contexto conservado:** el texto de búsqueda y el filtro se mantienen mientras el usuario permanece en la sección.
- **Información autorizada:** la búsqueda se realiza solo sobre los registros de las sedes y equipos que el usuario tiene asignados según su rol.
- **Accesibilidad:** el campo de búsqueda y el filtro tienen etiquetas descriptivas, y el estado de cada registro se comunica con texto además del color.

#### **3.1.2.5. Navigation Systems**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los sistemas de navegación de SafeLab definen cómo los visitantes y usuarios recorren el Landing Page y
  las aplicaciones móviles para cumplir sus objetivos. Se consideró que el personal de laboratorios
  hospitalarios utiliza principalmente el celular durante sus rondas y que el personal de empresas
  farmacéuticas necesita pasar rápidamente de una vista general a la zona o equipo que presenta un
  problema.
</p>

##### **Landing Page**

- **Navegación global:** barra superior fija con el logotipo de SafeLab, que regresa al inicio de la página, y enlaces que desplazan al visitante hacia cada sección. En navegadores móviles, estos enlaces se agrupan en un menú desplegable.
- **Cambio de idioma:** selector ubicado en la barra superior que permite cambiar entre inglés y español sin perder la sección en la que se encuentra el visitante (US57).
- **Navegación secuencial:** el contenido se organiza en un recorrido vertical que lleva al visitante desde el problema que resuelve SafeLab hasta su propuesta de valor y la forma de comenzar a utilizarlo.
- **Llamadas a la acción:** botones ubicados en las secciones principales que guían al visitante hacia el siguiente paso, como conocer las aplicaciones o contactar al equipo.
- **Pie de página:** enlaces a los Términos y Condiciones del servicio (US58), a la información de contacto y a las redes sociales.

##### **Mobile Applications**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La navegación global de Android se organiza mediante una <b>barra de navegación inferior</b> con cinco
  destinos y sus correspondientes íconos y etiquetas, conforme a las maquetas y los flujos de la sección
  3.1.4. Los destinos se muestran según los permisos del usuario. La <b>barra superior</b> muestra el
  logotipo y el título de la sección activa, y contiene los botones para regresar, cambiar de idioma
  (inglés o español), cambiar entre el modo claro y el modo oscuro, y abrir el perfil del usuario.
</p>

<table border="1" style="width: 100%; border-collapse: collapse;">
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Destino
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Contenido
      </th>
      <th style="text-align: center; vertical-align: middle; padding: 6px;">
        Bounded Context
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Home / Inicio
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Indicadores de sensores, equipos, alertas e incidentes; accesos rápidos y alertas recientes.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Dashboard &amp; Insights
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensors / Sensores
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensores asignados con su lectura actual y estado de conexión.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sensor Monitoring
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alerts / Alertas
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alertas e incidentes, y reconocimiento de alertas.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Alerts &amp; Incident Management
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipment / Equipos
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipos registrados e historial de mantenimiento.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Equipment Condition &amp; Maintenance
      </td>
    </tr>
    <tr>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        More / Más
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Sedes y activos, cumplimiento ambiental, control remoto, reportes, auditoría, usuarios y
        suscripción (gerente), perfil y cierre de sesión.
      </td>
      <td style="text-align: left; vertical-align: top; padding: 6px; overflow-wrap: anywhere;">
        Facility &amp; Asset Management, Environmental Compliance, Remote Control &amp; Actuation,
        Reporting &amp; Analytics, Audit &amp; Traceability, Identity &amp; Access Management,
        Subscription &amp; Billing y User Profiles
      </td>
    </tr>
  </tbody>
</table>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Adicionalmente, la aplicación aplica las siguientes técnicas de navegación:
</p>

- **Navegación jerárquica:** el usuario avanza de la pestaña a la lista de registros y de la lista al detalle de cada registro.
- **Retroceso:** el botón de regreso de la barra superior y el botón de retroceso del sistema operativo regresan al nivel anterior; desde cualquier pestaña distinta de Inicio, el retroceso regresa a Inicio.
- **Navegación contextual:** los accesos rápidos del panel principal llevan directamente a Sensores o a Alertas, y la lista compacta de alertas recientes incluye la opción «Ver todos».
- **Vistas alternas:** dentro de una pestaña, los botones superiores alternan entre registros relacionados, como Alertas e Incidentes, o Equipos e Historial de mantenimiento.
- **Inicio y cierre de sesión:** después de autenticarse, el usuario llega al panel principal (US52); el cierre de sesión se encuentra al final de la pestaña Más (US54).

### **3.1.3. Landing Page UI Design**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La Landing Page de SafeLab fue diseñada para presentar de manera ordenada la propuesta de valor del
  producto y facilitar que los visitantes conozcan sus principales características. La página mantiene un
  recorrido vertical desde la presentación inicial de SafeLab hasta las secciones informativas y de
  contacto, considerando versiones desktop y mobile para adaptar correctamente la distribución del
  contenido según el tamaño de pantalla.
</p>

#### **3.1.3.1. Landing Page Wireframe**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los wireframes documentan la estructura inicial de la Landing Page antes de aplicar el diseño visual
  definitivo. En ellos se definieron la jerarquía de la información, la distribución de las tarjetas, la
  ubicación de los botones y el orden de las diferentes secciones. La estructura comienza con el Navbar y
  el Hero, continúa con Benefits, Services y Plans, y posteriormente presenta About Product, About Team,
  Testimonials, FAQ, Contact y Footer.
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  En la versión desktop, los elementos aprovechan el espacio horizontal mediante columnas y grupos de
  tarjetas. En la versión mobile, las mismas secciones mantienen su orden, pero sus componentes se
  reorganizan verticalmente para facilitar la lectura y navegación desde pantallas pequeñas.
</p>

<p align="center">
  <b>Landing Page Wireframe - Desktop</b>
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/wireframes/landingDesktopWireframe.png"
    alt="Landing Page Wireframe Desktop"
    width="90%">
</p>

<p align="center">
  <b>Landing Page Wireframe - Mobile</b>
</p>

<p align="center">
  <img src="../assets/08-chapter-3/wireframes/landingMobileWireframe.png" width="35%">
</p>

#### **3.1.3.2. Landing Page Mock-up**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los mockups muestran la versión de alta fidelidad de la Landing Page, incorporando la identidad visual
  de SafeLab sobre la estructura definida previamente en los wireframes. Se aplicaron los colores,
  tipografía, imágenes, tarjetas, botones y demás elementos visuales utilizados en la interfaz final.
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La sección Benefits comunica seis ventajas del producto: protección de materiales sensibles, visibilidad
  centralizada, respuesta temprana ante incidentes, reducción de registros manuales, trazabilidad y
  colaboración por roles. Services agrupa tres ámbitos de aplicación: laboratorios clínicos, hospitales y
  farmacias clínicas, y la plataforma de monitoreo. En la versión comercial vigente, Plans presenta un
  único plan <b>SafeLab Business</b> de <b>S/ 118 mensuales</b>, con diez empleados incluidos y una cuenta
  de gerente general que no consume cupos; cada empleado adicional cuesta <b>S/ 17 mensuales</b>. Las
  capturas de mock-ups conservadas en esta sección corresponden a una propuesta anterior con tres planes;
  sus importes no representan la oferta actual.
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La variante móvil conserva el orden informativo de escritorio y reorganiza las tarjetas en una sola
  columna. La comparación de estos mock-ups con la Landing Page publicada permite identificar cambios
  posteriores de contenido, especialmente en precios y beneficios.
</p>

<p align="center">
  <b>Landing Page Mockup - Desktop</b>
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/mockups/landingDesktopMockup.png"
    alt="Landing Page Mockup Desktop"
    width="90%">
</p>

<p align="center">
  <b>Landing Page Mockup - Mobile</b>
</p>

<p align="center">
  <img src="../assets/08-chapter-3/mockups/landingMobileMockup.png" width="35%">
</p>

### **3.1.4. Mobile Applications UX/UI Design**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La propuesta de experiencia móvil contempla la navegación de SafeLab Android, la distribución de
  contenido por roles y los recorridos de supervisión, atención de alertas y consulta de equipos. Las
  maquetas, los wireflows y los diagramas de flujo permiten relacionar las decisiones visuales con las
  tareas del personal de laboratorio y de organizaciones farmacéuticas.
</p>

#### **3.1.4.1. Mobile Applications Wireframes**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  La composición de las pantallas de baja fidelidad prioriza el encabezado con información de contexto,
  las lecturas ambientales con sus unidades, los estados expresados con texto y color, y los accesos a
  acciones disponibles según el permiso del usuario. La navegación inferior organiza los cinco destinos
  principales: Inicio, Sensores, Alertas, Equipos y Más. Los wireflows de la sección 3.1.4.2 conservan
  representaciones de estas pantallas y sus cambios de estado; sin embargo, los wireframes individuales
  todavía no constan como figuras independientes en los archivos de este capítulo.
</p>

#### **3.1.4.2. Mobile Applications Wireflow Diagrams**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los cinco wireflows existentes describen transiciones de pantalla para objetivos de usuario
  seleccionados. Cada flecha representa una acción y cada vista comunica el estado resultante. Las
  funciones de autenticación biométrica, control de equipos, evidencia fotográfica y lectura QR que
  aparecen en algunos diagramas se presentan como parte del diseño propuesto, sin atribuirlas
  automáticamente a la versión Android publicada en AV2.
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User goal 1:</b> Como técnico de laboratorio, quiero iniciar sesión de forma rápida y segura para
  acceder al monitoreo del laboratorio. El recorrido incorpora ingreso de credenciales y una alternativa
  biométrica prevista en el diseño; el acceso autenticado conduce al panel principal.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/wireflows/wireflow1.png"
    alt="Wireflow 1"
    width="90%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User goal 2:</b> Como técnico de laboratorio, quiero atender una alerta crítica y actuar sobre el
  equipo afectado para proteger las muestras. Desde la lista de alertas abre el detalle, compara el valor
  registrado con el rango permitido y pasa al control remoto, donde confirma el comando mediante un bottom
  sheet que muestra el resultado de la validación de seguridad.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/wireflows/wireflow2.png"
    alt="Wireflow 2"
    width="90%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User goal 3:</b> Como técnico de laboratorio, quiero reportar un incidente con evidencia fotográfica
  para dejar trazabilidad de la desviación. Desde el detalle de la alerta crea el incidente, adjunta
  fotografías con la cámara y lo envía; el nuevo incidente aparece en la lista de incidentes abiertos.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/wireflows/wireflow3.png"
    alt="Wireflow 3"
    width="90%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User goal 4:</b> Como técnico de laboratorio, quiero identificar un equipo escaneando su código QR
  para ver su estado sin buscarlo manualmente. Desde los accesos rápidos abre la cámara, el código se
  reconoce automáticamente y se muestra la ficha del equipo, desde donde accede a las lecturas de su
  sensor.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/wireflows/wireflow4.png"
    alt="Wireflow 4"
    width="90%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User goal 5:</b> Como jefa de laboratorio, quiero revisar las lecturas en tiempo real de un sensor
  para verificar que se mantiene dentro del rango permitido. Desde el dashboard abre las lecturas en vivo,
  filtra por tipo de sensor y entra al detalle, donde revisa la tendencia y las estadísticas del periodo.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/wireflows/wireflow5.png"
    alt="Wireflow 5"
    width="90%">
</p>

#### **3.1.4.3. Mobile Applications Mock-ups**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  Los mock-ups presentan el diseño en alta fidelidad de las pantallas, aplicando la guía de estilos de
  SafeLab: color primario #4F35E8, color de acento #14B8A6, fondos #F4F7FB y la tipografía Inter. Los
  estados de severidad (crítico, advertencia, normal e informativo) usan colores semánticos y siempre se
  acompañan de una etiqueta de texto, para no depender únicamente del color. Las maquetas originales
  utilizan principalmente rótulos en inglés; la aplicación permite cambiar entre inglés y español.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/mockups/mockup1.png"
    alt="Mobile Applications Mock-ups 1"
    width="90%">
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/mockups/mockup2.png"
    alt="Mobile Applications Mock-ups 2"
    width="90%">
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/mockups/mockup3.png"
    alt="Mobile Applications Mock-ups 3"
    width="90%">
</p>

#### **3.1.4.4. Mobile Applications User Flow Diagrams**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
    Los diagramas de flujo de usuario documentan recorridos diseñados con pantallas de la aplicación
  Android durante AV2. Muestran las acciones, decisiones y resultados esperados, incluidos los casos de
  error y de permisos insuficientes. Las capturas reflejan el estado visual utilizado al elaborar los
  diagramas; no deben interpretarse como pruebas de que todos los flujos estén implementados en su
  totalidad ni como evidencias específicas del hotfix <code>av2-v2.5.3</code>. Los cinco wireflows
  conservados y los siete user flows no tienen una correspondencia completa entre sí: algunos recorridos
  de escaneo QR, evidencia fotográfica y control remoto no coinciden exactamente con los objetivos
  detallados en los user flows. Esta diferencia debe resolverse al actualizar los diagramas, sin atribuir
  a AV2 funcionalidades que todavía no se han verificado.
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  En cada diagrama se distingue el happy path (línea verde continua), en el que el usuario completa su
  objetivo sin inconvenientes, de los unhappy paths (línea roja discontinua), que muestran la respuesta de
  la aplicación ante errores, falta de permisos o situaciones alternativas. Los rombos amarillos
  representan los puntos de decisión, el óvalo negro el punto de inicio, el óvalo morado el objetivo
  cumplido y el óvalo rojo claro el estado final de cada unhappy path. Los diagramas están disponibles en
  LucidChart: <a href="https://lucid.app/lucidchart/bc6db41e-c842-4668-9278-6e60496b90fc/view">SafeLab –
  Mobile Applications User Flow Diagrams (AV2)</a>.
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User flow 1 – Iniciar sesión.</b> Como usuario de laboratorio, quiero iniciar sesión de forma segura
  para acceder al monitoreo de mi laboratorio. El usuario abre la aplicación, escribe su correo y su
  contraseña y pulsa Sign in. En el happy path, el servidor responde, las credenciales son válidas y el
  usuario llega al dashboard con los indicadores de su laboratorio. Se contemplan dos unhappy paths: si el
  servidor no está disponible, la aplicación muestra un mensaje de error de conexión y el usuario debe
  reintentar cuando haya red; si las credenciales son inválidas, se muestra un mensaje de error junto al
  formulario, se conserva el correo ingresado y el usuario corrige los datos y vuelve a intentarlo.
</p>

<p align="center">
  <img src="../assets/08-chapter-3/userflows/userflow-01-sign-in.png" alt="User Flow 1" width="100%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User flow 2 – Atender una alerta.</b> Como jefe de laboratorio, quiero confirmar la atención de una
  alerta activa para dejar constancia de que fue atendida. Desde la lista de alertas, el usuario filtra
  por las activas, abre el detalle y despliega el menú de acciones. En el happy path, su rol le permite
  reconocer la alerta: al hacerlo, el estado cambia a atendida y el cambio queda reflejado en la lista. En
  el unhappy path, el usuario es técnico y su rol no incluye reconocer alertas; el menú solo le ofrece
  escalarla, por lo que la alerta pasa a quien tiene la autoridad para atenderla.
</p>

<p align="center">
  <img src="../assets/08-chapter-3/userflows/userflow-02-attend-alert.png" alt="User Flow 2" width="100%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User flow 3 – Gestionar un incidente.</b> Como jefe de laboratorio, quiero gestionar un incidente
  abierto para dar seguimiento a su resolución. El usuario abre la lista de incidentes, selecciona uno y
  consulta su detalle; desde el menú de acciones marca el incidente como en investigación. En el happy
  path, el rol tiene permiso para gestionar incidentes y el estado se actualiza a Investigating. En el
  unhappy path, el usuario es técnico y solo puede consultar el incidente: el menú de acciones no aparece
  y el estado permanece sin cambios.
</p>

<p align="center">
  <img src="../assets/08-chapter-3/userflows/userflow-03-manage-incident.png" alt="User Flow 3" width="100%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User flow 4 – Configurar los límites de un sensor.</b> Como coordinador de laboratorio, quiero
  configurar los límites de un sensor para recibir alertas cuando una lectura salga de rango. Esta acción
  requiere el permiso <code>sensors.configure</code>, que no se asigna por defecto. El usuario abre la
  lista de sensores, elige Actions en el sensor y edita el valor mínimo y el máximo. En el happy path, el
  permiso está concedido, el mínimo es menor que el máximo y los nuevos límites se guardan y se muestran
  en la lista. Se contemplan dos unhappy paths: si el usuario es técnico, el menú de acciones no aparece y
  debe solicitar el permiso a un responsable; si el mínimo es mayor o igual que el máximo, la aplicación
  muestra un mensaje de validación y el usuario corrige el rango antes de guardar.
</p>

<p align="center">
  <img src="../assets/08-chapter-3/userflows/userflow-04-configure-sensor-limits.png" alt="User Flow 4" width="100%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User flow 5 – Monitorear sensores.</b> Como jefe de laboratorio, quiero revisar el estado de los
  sensores para verificar que se mantienen dentro del rango permitido. El usuario abre la sección Sensors,
  actualiza los datos y entra al detalle de un sensor. En el happy path, la actualización tiene éxito, el
  sensor está conectado y la lectura está dentro del rango, por lo que el estado es Normal. Se contemplan
  tres unhappy paths: si la actualización falla por un error de red, la aplicación conserva los datos ya
  cargados y permite reintentar; si el sensor figura como desconectado, el usuario debe revisar el
  dispositivo; si la lectura está fuera de rango, el estado se marca como Out-of-range y el flujo continúa
  en el user flow 2 para atender la alerta.
</p>

<p align="center">
  <img src="../assets/08-chapter-3/userflows/userflow-05-monitor-sensors.png" alt="User Flow 5" width="100%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User flow 6 – Buscar un equipo.</b> Como usuario de laboratorio, quiero buscar un equipo por su
  nombre para consultar su información sin recorrer toda la lista. El usuario abre la lista de equipos y
  escribe un término en el buscador. En el happy path, existen coincidencias, la lista se filtra y el
  usuario abre el detalle del equipo. En el unhappy path, no hay coincidencias: la aplicación muestra que
  no hay registros y el usuario modifica el término de búsqueda.
</p>

<p align="center">
  <img src="../assets/08-chapter-3/userflows/userflow-06-find-equipment.png" alt="User Flow 6" width="100%">
</p>

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  <b>User flow 7 – Registrar un equipo.</b> Como gerente de laboratorio, quiero registrar un equipo nuevo
  para incluirlo en el monitoreo de mi organización. El usuario abre la sección de equipos, pulsa Add
  equipment, completa el nombre, la descripción y el responsable, y guarda. En el happy path, el rol
  permite registrar equipos, los campos obligatorios están completos y el nuevo equipo aparece en la lista
  con el mensaje Record saved. Se contemplan dos unhappy paths: si el usuario es técnico, el botón de
  registro no se muestra y debe pedir a un gerente que lo registre; si faltan campos obligatorios, la
  aplicación muestra un mensaje de validación y el usuario completa el formulario antes de guardar de
  nuevo.
</p>

<p align="center">
  <img src="../assets/08-chapter-3/userflows/userflow-07-register-equipment.png" alt="User Flow 7" width="100%">
</p>

#### **3.1.4.5. Mobile Applications Prototyping**

<p
  style="text-align: justify; text-indent: 0.5in; line-height: 1.5; margin: 0 0 12px 0; orphans: 2; widows: 2;">
  El prototipo de SafeLab presenta la navegación desde el inicio de sesión hasta las vistas de supervisión
  clínica. La jerarquía de las pantallas mantiene los cinco destinos de navegación, los estados visuales
  de los sensores y los accesos a las tareas descritas en los flujos anteriores. La grabación disponible
  permite revisar estas interacciones y contrastar la propuesta de diseño con los recorridos explicados.
</p>

<p align="center">
  <img
    src="../assets/08-chapter-3/wireframes/mobilePrototyping.png"
    alt="Evidencia en video del prototipo móvil de SafeLab"
    width="88%">
</p>

<p style="text-align: left; margin: 4px 0 12px 0;">
  <b>Video del prototipo:</b>
  <a href="https://youtu.be/3eaxNpcLX8k">https://youtu.be/3eaxNpcLX8k</a>
</p>

# **Chapter II: Requirements Development and Software Solution Design**

## **2.1. Competitors**

### **2.1.1. Competitive Analysis**

**¿Por qué realizar este análisis?**

Identificar las barreras de entrada (tecnológicas y económicas) impuestas por los líderes globales de monitoreo IoT, con el fin de validar que existe un nicho desatendido en instituciones de salud medianas y pequeñas. Este análisis permitirá posicionar a SafeLab como una alternativa ágil, clínicamente específica y económicamente accesible.

| Atributo                     | SafeLab                                                                                                                                | SmartSense                                                                                                                  | SenseAnywhere                                                                                              | Monnit                                                                                                        |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Descripción general**      | Startup B2B SaaS enfocada en erradicar el desperdicio biológico mediante automatización ágil y accesible.                              | Plataforma IoT corporativa de alto nivel para trazabilidad y cumplimiento normativo en redes hospitalarias y farmacéuticas. | Sistema europeo de monitoreo en la nube enfocado en hardware ultra duradero y logística de cadena de frío. | Proveedor global de soluciones de monitoreo remoto con sensores inalámbricos para múltiples industrias.       |
| **Ventaja Competitiva**      | Plataforma agnóstica de hardware, altamente contextualizada al flujo de trabajo de los biólogos.                                       | Capacidad de escala masiva e integración con sistemas ERP y estricto cumplimiento regulatorio (FDA).                        | Fiabilidad extrema del hardware y registro ininterrumpido en la nube sin mantenimiento local.              | Accesibilidad económica inicial y personalización extrema para monitorear casi cualquier variable.            |
| **Mercado Objetivo**         | Laboratorios clínicos y farmacias hospitalarias en ciudades emergentes o periféricas.                                                  | Grandes hospitales, cadenas farmacéuticas nacionales y logística farmacéutica global.                                       | Almacenes de alta tecnología, laboratorios farmacéuticos y empresas de transporte logístico.               | Pequeñas y medianas empresas (PYMES) en agricultura, TI, alimentos, clínicas y otros sectores.                |
| **Estrategias de Marketing** | Marketing de atracción (inbound) enfocado en la Cultura Cero Residuos y la simplificación de auditorías de calidad locales.            | Ventas corporativas B2B enfocadas en el retorno de inversión (ROI) mediante mitigación de riesgos legales.                  | Presencia en ferias comerciales farmacéuticas globales.                                                    | Marketing digital masivo, comercio electrónico directo y posicionamiento en motores de búsqueda a bajo costo. |
| **Productos y Servicios**    | Aplicación web SPA + integración de API con hardware genérico y asequible de terceros.                                                 | Software empresarial + Gateways + Sensores IoT propietarios.                                                                | SenseAnywhere Cloud + AiroSensors (hardware propietario cerrado).                                          | Plataforma iMonnit + sensores inalámbricos ALTA.                                                              |
| **Precios y Costos**         | Bajo. Modelo SaaS puro con pagos mensuales o anuales, permitiendo la reutilización de equipos genéricos.                               | Muy alto. Contratos corporativos anuales que incluyen hardware costoso e instalación.                                       | Medio-Alto. Depende de sensores europeos especializados importados.                                        | Bajo-Medio. Hardware asequible y suscripciones mensuales o anuales por niveles.                               |
| **Canales de Distribución**  | Ventas directas B2B y autoregistro (self onboarding).                                                                                  | Ventas corporativas directas. Plataforma Web y App Móvil.                                                                   | Red de distribuidores oficiales. Plataforma Web SaaS.                                                      | Tienda en línea propia y distribuidores. Plataforma Web y Móvil.                                              |
| **Fortalezas**               | Alta agilidad para pivotar, bajo costo estructural e interfaz diseñada exclusivamente para el usuario clínico.                         | Fuerte reputación de marca y certificaciones internacionales.                                                               | Hardware líder en el mercado (10 años sin necesidad de carga) y software altamente estable.                | Amplio catálogo de sensores e interfaz altamente personalizable.                                              |
| **Oportunidades**            | Gran mercado de laboratorios medianos que aún usan procesos en papel porque no pueden costear a los competidores principales.          | Absorción de competidores más pequeños y contratos gubernamentales.                                                         | Expansión en mercados emergentes y mejora en la integración de API.                                        | Crecimiento constante en la digitalización pospandemia de clínicas medianas.                                  |
| **Debilidades**              | Falta de hardware propietario y falta de reconocimiento de marca en la etapa inicial.                                                  | Inaccesible para clínicas pequeñas y requiere procesos de implementación corporativa lentos.                                | Modelo de hardware cerrado; si un sensor se daña, debe importarse otro del fabricante.                     | Plataforma demasiado genérica y no diseñada específicamente para flujos de trabajo de salud.                  |
| **Amenazas**                 | Desconfianza inicial del sector salud hacia nuevas plataformas, o el ingreso de una gran empresa tecnológica al mercado de bajo costo. | Aparición de startups ágiles y asequibles en mercados locales.                                                              | Problemas en las cadenas globales de suministro de microchips que aumentan los costos de hardware.         | Soluciones especializadas que captan clientes de salud mediante interfaces más específicas.                   |

### **2.1.2. Strategies and Tactics Against Competitors**

## **2.2. Interviews**

### **2.2.1. Interview Design**

Segmento 1: Laboratorios de Hospitales

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

Segmento 2: Empresas Farmacéuticas

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

Para recopilar información cualitativa de ambos segmentos objetivo, se realizaron seis entrevistas que fueron consolidadas en en enlace mostrado a continuación, siguiendo el formato y la estructura indicados para la sección de Entrevistas.

Enlace: xxxxxxxxxxxx

### **2.2.3. Interview Analysis**

## **2.3. Needfinding**

### **2.3.1. User Personas**

### **2.3.2. User Task Matrix**

### **2.3.3. User Journey Mapping**

### **2.3.4. Empathy Mapping**

### **2.3.5. Big Picture Event Storming**

### **2.3.6. Ubiquitous Language**

## **2.4. Requirements Specification**

### **2.4.1. User Stories**

### **2.4.2. Impact Mapping**

### **2.4.3. Product Backlog**

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

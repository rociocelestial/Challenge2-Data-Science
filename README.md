# Challenge2-Data-Science

**Telecom X - Analisis de evasión de clientes**

La empresa TelecomX es una empresa que ofrece servicios de Telecomunicaciones y enfrenta actualmente una alta tasa de cancelaciones (26.58%). Por ello, necesita comprender los factores que llevan a la pérdida de clientes.



### **Objetivo**

* Identificar patrones y factores de riesgo asociados al abandono del clientes.
* Analizar variables cátegoricas y númericas para encontrar correlaciones con el Churn (evasión)
* Proporcionar insights accionables para reducir la tasa de evasión
* Generar visualizaciones claras que faciliten la toma de decisiones.




### **Principales Insights**

**Perfil del Cliente con Mayor Riesgo**

* **Contratos a corto plazo**: Los clientes con contratos mensuales son los que más rescinden su relación, lo que indica una falta de compromiso a largo plazo.

* **Baja vinculación inicial**: La mayoría de las pérdidas ocurren durante el primer mes de contrato, especialmente en perfiles de clientes solteros y sin dependientes.

* **Falta de lazos familiares**: Los clientes sin pareja o dependientes muestran menor fidelidad a la marca en comparación con aquellos que tienen vínculos familiares.

**Factores de Servicio y Tecnología**

* **Tecnología de conexión**: Los usuarios con servicio de fibra óptica presentan la mayor tasa de deserción dentro de la empresa.

* **Métodos de pago**: El uso de cheque electrónico se identifica como un punto crítico, asociado a la mayor tasa de abandono.

* **Paquetes básicos**: La vulnerabilidad se concentra en clientes con paquetes básicos que no logran migrar a contratos anuales o servicios adicionales.

**Percepción de Valor y Precio**

* **Relación costo-beneficio**: Existe una sensibilidad al precio muy alta; los clientes perciben el servicio como "caro" desde el primer mes si no encuentran un valor que justifique el costo.

* **Falta de incentivos**: Los clientes con mayor actividad o cantidad de servicios perciben un costo mayor sin recibir beneficios de retención claros (como descuentos por volumen o antigüedad), lo que aumenta su riesgo de fuga.

**Impacto Demográfico**

* **Adultos mayores**: Aunque representan un volumen total menor en la base de datos, proporcionalmente tienen una tasa de riesgo mucho más alta en comparación con los no adultos mayores.




### **Recomendaciones**

1. **Estrategia de Retención en el "Mes Crítico" (Onboarding)**

Dado que el abandono se concentra en el **primer mes**, la empresa debe fortalecer la experiencia inicial:

* **Programa de Bienvenida**: Implementar llamadas de seguimiento o visitas técnicas de cortesía a los 15 días de la instalación para asegurar que el cliente sepa usar todos los servicios y esté satisfecho.

* **Bonos de Bienvenida**: Ofrecer un descuento progresivo durante los primeros 3 meses, condicionado a que el cliente no cancele, para suavizar la percepción de "costo inicial alto".

2. **Incentivos de Pago y Contratación**

Para atacar el problema del **Cheque Electrónico** y los **Contratos Mensuales**:

* **Descuento por Domiciliación**: Ofrecer un descuento mensual (ej. 5% o 10%) si el cliente cambia su método de pago de Cheque Electrónico a **Tarjeta de Crédito o Débito Automático**. Esto reduce la fricción del pago mensual y mejora la cobranza.

* **Upgrade a Contrato Anual**: Crear una oferta "Contrato Anual al precio del Mensual" para asegurar que los clientes básicos tengan una barrera de salida legal y temporal.

3. **Fortalecimiento del "Valor Percibido" en Fibra Óptica**

La fibra óptica es el producto que más falla en retención, probablemente por ser el más caro:

* **Auditoría de Servicio**: Investigar si el abandono en Fibra Óptica es por fallas técnicas o por precio. Si es por precio, empaquetar servicios de streaming gratuitos (Netflix, Disney+, etc.) para que el cliente sienta que el costo diario está justificado por el entretenimiento recibido.

* **Planes Familiares**: Dado que los solteros y sin dependientes se van más, crear paquetes específicos para hogares pequeños que sean más competitivos en precio.

4. **Fidelización de Clientes "Solteros y sin Dependientes"**

Este es tu segmento más volátil y numeroso:

* **Programas de Lealtad (Incentivos por Antigüedad)**: Crear un sistema de puntos o beneficios que aumenten cada 6 meses. Si el cliente siente que "perderá sus puntos" si se va, se pensará dos veces el cancelar.

* **Venta Cruzada (Cross-selling)**: Intentar que el cliente de 1 o 2 servicios pase a 3. Como mencionaste, cuantos más servicios tienen, más difícil es que abandonen.

5. **Atención Diferenciada para el Adulto Mayor**

Aunque son menos en cantidad total, su tasa de riesgo es la más alta (41%):

* **Línea de Soporte Prioritaria**: Crear un canal de atención telefónica humana y pausada para este segmento. A menudo, el adulto mayor cancela por frustración al no entender la tecnología o la factura.



### **Tecnologías Utilizadas**

**Lenguaje**

* Python



**Librería**

* requests
* pandas
* matplotlib
* plotly.express
* seaborn



**Notebook**

* Google colab
  



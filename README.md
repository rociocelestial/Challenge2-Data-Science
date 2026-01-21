# Challenge2-Data-Science

  
## 📊 **TelecomX: Análisis de Evasión de Clientes (Churn)**

La empresa **TelecomX** enfrenta una tasa crítica de cancelaciones del **26.58%**. Este proyecto analiza los factores determinantes detrás de la pérdida de clientes para transformar datos en estrategias de retención accionables.

---

## 🎯 **Objetivos del Proyecto**

* **Identificar** patrones y factores de riesgo asociados al abandono.

* **Analizar** la correlación entre variables categóricas (contratos, servicios) y el Churn.

* **Proporcionar** insights estratégicos para la toma de decisiones basada en datos.

* **Visualizar** la vulnerabilidad del cliente para priorizar esfuerzos de retención.



 --- 
  
  





## 🔍 **Hallazgos Principales (Insights)**


### 👤 **Perfil del Cliente en Riesgo**

* **El "Mes Crítico"**: La mayor tasa de abandono ocurre durante el primer mes.

* **Baja Vinculación**: Clientes solteros y sin dependientes muestran menor lealtad.

* **Compromiso Débil**: Los contratos mes a mes son el principal predictor de fuga.
  

### 🔌 **Factores de Servicio y Tecnología**

* **Fibra Óptica**: Sorprendentemente, los usuarios de este servicio presentan la mayor deserción, sugiriendo insatisfacción con el precio o estabilidad técnica.

* **Métodos de Pago**: El uso de Cheque Electrónico está altamente correlacionado con el abandono.

* **Falta de Cross-selling**: Los clientes con paquetes básicos tienen mayor probabilidad de irse que aquellos con múltiples servicios.
  

### 💰 **Percepción de Valor**

* **Sensibilidad al Precio**: Los clientes perciben el servicio como "caro" si no se establecen incentivos de lealtad desde el inicio.

* **Impacto Demográfico**: Los adultos mayores tienen una tasa de riesgo del 41%, muy superior al promedio general.


---  
  

## 💡 **Recomendaciones Estratégicas**

1. **Optimización del Onboarding (Mes 1**)

   Implementar un **"Programa de Bienvenida"** con llamadas de seguimiento a los 15 días y bonos de descuento progresivos durante el primer trimestre para reducir la fuga temprana.

2. **Migración de Métodos de Pago**

   Ofrecer incentivos (ej. 5% de descuento) para que los clientes cambien de **Cheque Electrónico** a **Débito Automático**, reduciendo la fricción mensual del pago.

3. **Plan de Retención para Fibra Óptica**
   
   Realizar una auditoría técnica y empaquetar servicios de valor agregado (streaming o mayor velocidad) para justificar el costo del servicio de fibra.

4. **Fidelización del Segmento Senior**
   
   Crear un canal de atención preferente y humano para adultos mayores, simplificando la resolución de dudas técnicas y de facturación.


 ---  


## 🛠️ **Tecnologías y Librerías**

|Categoría | Herramientas |
|:---| :--- |
| **Lenguaje**  | Python |
| **Extracción** | requests |
| **Análisis de Datos** | pandas |
| **Visualización** | matplotlib, seaborn, plotly.express|
| **Entorno** | Google Colab |

---

## 🚀 **Cómo Ejecutar el Proyecto**



1. **Clonar el repositorio:**
   ```Bash
   git clone [https://github.com/tu-usuario/Challenge2-Data-Science.git](https://github.com/tu-usuario/Challenge2-Data-Science.git) 



2.  **Instalar Dependencias**

    ```Bash

    
    pip install pandas matplotlib seaborn plotly requests
    
  



3. **Ejecución:** Asegúrate de contar con conexión a internet para que la librería requests pueda obtener el archivo JSON desde la nube.

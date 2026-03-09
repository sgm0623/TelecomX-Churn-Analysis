# 📊 TelecomX - Análisis de Evasión de Clientes (Churn Analysis)

## 🎓 Challenge 2 - Data Science LATAM (Alura)

### 👤 Información del Autor
- **Estudiante:** Santiago Grajales Montoya
- **Programa:** Ciencia de Datos - Grupo 9
- **Institución:** Alura LATAM
- **Fecha:** Marzo 2026

---

## 🎯 Objetivos del Proyecto

### Objetivo General
Analizar los factores que influyen en la evasión de clientes (churn) de Telecom X para proporcionar insights que ayuden a reducir la tasa de cancelaciones.

### Objetivos Específicos
- ✅ Extraer datos desde una API en formato JSON
- ✅ Transformar y limpiar los datos (ETL)
- ✅ Cargar y explorar el dataset
- ✅ Identificar patrones y tendencias de churn
- ✅ Visualizar insights estratégicos
- ✅ Generar un informe final con recomendaciones

---

## 📊 Sobre el Dataset

- **Fuente:** API de Telecom X (GitHub)
- **Registros:** 7,267 clientes
- **Variables:** 21 columnas (demográficas, servicios, facturación)
- **Variable Objetivo:** `Churn` (Sí/No - si el cliente se fue o permaneció)

---

## 🛠️ Herramientas Utilizadas

- 🐍 **Python** - Lenguaje de programación
- 📊 **Pandas** - Manipulación de datos
- 🔢 **NumPy** - Cálculo numérico
- 📈 **Matplotlib & Seaborn** - Visualización de datos
- 📓 **Jupyter Notebook** - Entorno interactivo

---

## 📑 Estructura del Proyecto

* **`notebooks/`**: Contiene el cuaderno principal de Jupyter/Colab con todo el proceso de Extracción, Transformación, Carga (ETL) y el Análisis Exploratorio de Datos (EDA).
* **`graficos/`**: Almacena las visualizaciones clave (gráficos de barras, torta, etc.) generadas durante el análisis.
* **`docs/`**: Documentación complementaria, incluyendo la versión estática en PDF del análisis completo.
* **`README.md`**: Resumen, objetivos y conclusiones principales del proyecto.

---

## 💡 Principales Insights (Hallazgos)

Tras el Análisis Exploratorio de Datos (EDA), se identificaron los siguientes patrones clave en la evasión de clientes:

* **Tipo de Contrato:** Existe una fuerte correlación entre el tipo de contrato y la evasión. Los clientes con contratos mensuales tienen una probabilidad significativamente mayor de irse en comparación con los de contrato bienal. La flexibilidad mensual facilita la decisión de cancelación.
* **Métodos de Pago:** La automatización retiene clientes. El pago automático (especialmente tarjeta de crédito) reduce drásticamente el churn. En contraste, los pagos manuales (como el Electronic Check, con un 43.8% de riesgo) exigen una acción consciente mes a mes, facilitando la cancelación.
* **Servicio de Internet:** Sorprendentemente, los clientes del servicio premium "Fiber Optic" presentan la tasa de churn más alta (40.6%). Esto sugiere una posible desconexión entre el precio pagado, las expectativas generadas y la experiencia real del servicio.
* **Factores Demográficos:** El estado civil influye en la estabilidad. Los clientes sin pareja tienen una tasa de abandono del 32.0%, frente a un 19.0% en aquellos con pareja.

---

## 🚀 Próximos Pasos Recomendados

Para mitigar el riesgo de fuga, se propone la siguiente ruta de acción:

* **Corto plazo (1-2 semanas):** Compartir este informe con los equipos de Marketing, Retención y Producto para validar los hallazgos operativos y priorizar 2-3 recomendaciones para un piloto inmediato.
* **Mediano plazo (1-2 meses):** Diseñar experimentos A/B para probar la efectividad de las estrategias, implementar un dashboard de monitoreo en tiempo real y capacitar al equipo de atención al cliente en detección temprana.
* **Largo plazo (3-6 meses):** Desarrollar un modelo predictivo de churn (Machine Learning) e integrar estas señales de riesgo en el CRM para ejecutar acciones preventivas automáticas.

> **Reflexión final:** El churn no es un evento aleatorio; es el resultado acumulado de experiencias, percepciones de valor y alternativas disponibles. El 74.3% de los clientes eligen quedarse. El enfoque debe ser entender y replicar lo que funciona para ellos, interviniendo proactivamente en los segmentos de mayor riesgo.

# Análisis de Evasión de Clientes - Telecom X

Este proyecto es mi entrega para el desafío práctico de análisis de datos de ALURA LATAM. El objetivo es comprender los factores que influyen en la evasión de clientes (churn) en la empresa ficticia Telecom X, utilizando Python y librerías como Pandas, Seaborn y Matplotlib.

## Objetivos del Proyecto

- Analizar el comportamiento de cancelación de clientes.
- Identificar variables clave asociadas al churn.
- Visualizar patrones y relaciones entre variables.
- Generar recomendaciones basadas en los datos.
- Preparar los datos para futuros modelos predictivos.

## Tecnologías y Herramientas

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab
- JSON como fuente de datos

## Estructura del Notebook

**Extracción:**  
Lectura del archivo JSON desde GitHub y carga a un DataFrame.

**Transformación:**  
Limpieza, estandarización y normalización de columnas anidadas.

**Análisis Exploratorio (EDA):**  
Visualización y análisis de la distribución de evasión, variables categóricas vs. churn y variables numéricas vs. churn.

**Análisis de Correlación (Extra):**  
Matriz de correlación entre variables clave.

**Informe Final:**  
Conclusiones, insights estratégicos y recomendaciones.

## Resultados Destacados

- El 26.5% de los clientes han abandonado el servicio.
- El contrato "mes a mes" presenta la mayor tasa de churn.
- Los métodos de pago automáticos tienen menor evasión.
- Los clientes con menos meses como cliente y mayor cargo mensual tienen mayor riesgo de irse.
- La ausencia de soporte técnico y servicios adicionales incrementa la evasión.

## Recomendaciones Estratégicas

En función de los resultados obtenidos, se recomienda:
-Implementar estrategias orientadas a reducir el abandono de clientes, priorizando la fidelización de aquellos con menor antigüedad, quienes presentan mayor riesgo de cancelación.
-Establecer un programa de bienvenida con acompañamiento personalizado durante los primeros meses, ofreciendo incentivos y beneficios exclusivos que fortalezcan la permanencia.
-Revisar la estructura de los planes con cargos mensuales más altos, de modo que el cliente perciba un mayor valor en el servicio, ya sea a través de descuentos progresivos, promociones o la inclusión de servicios adicionales que justifiquen el costo.
-Promover la contratación de servicios complementarios contribuirá a incrementar el compromiso y satisfacción del cliente, reduciendo la probabilidad de abandono. 
-Implementar un sistema de monitoreo para identificar clientes en riesgo y brindarles alternativas personalizadas que aseguren su continuidad.

## Cómo usar este proyecto

1. Abre el notebook en Google Colab.
2. Ejecuta las celdas paso a paso, desde la Extracción hasta el Informe Final.
3. Explora los gráficos y ajusta los análisis si lo deseas.

## Diccionario de datos

Consulta el [diccionario de datos aquí](diccionario_datos.md).

## Contacto

Katerin Casas  
[Mi GitHub](https://github.com/Katerincasas)  
Proyecto realizado como parte del desafío de análisis de datos ALURA LATAM

## Licencia

Este proyecto es de libre uso educativo y puede adaptarse para estudios, prácticas y portafolios personales. Si lo compartes públicamente, por favor cita la fuente.
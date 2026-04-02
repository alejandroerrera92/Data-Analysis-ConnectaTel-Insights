# Data-Analysis-ConnectaTel-Insights
📊 Telecom Customer Usage Analysis – ConnectaTel
🧩 Descripción del Proyecto

Este proyecto analiza el comportamiento de clientes en una empresa de telecomunicaciones (ConnectaTel) con operaciones en Latinoamérica.

El objetivo es entender cómo los usuarios utilizan los servicios móviles (llamadas y mensajes), identificar patrones de consumo, detectar valores atípicos y segmentar clientes para generar insights accionables de negocio.

🎯 Objetivos del Análisis
Analizar el uso real de llamadas y mensajes por cliente
Detectar outliers y comportamientos atípicos
Segmentar clientes por edad y nivel de uso
Identificar oportunidades para optimizar planes y mejorar la oferta comercial

🗂️ Datasets Utilizados

El análisis se basa en tres fuentes de datos:

plans.csv → Información de planes (precio, beneficios, límites)
users_latam.csv → Datos de clientes (edad, ciudad, plan, registro)
usage.csv → Uso real (llamadas, duración, mensajes)

🛠️ Herramientas y Tecnologías
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

🧪 Proceso de Análisis
1. Limpieza de datos
Reemplazo de valores sentinel (ej. -999 en edad)
Manejo de valores nulos (MAR en usage)
Corrección de fechas fuera de rango
Estandarización de tipos de datos
2. Análisis exploratorio (EDA)
Estadísticas descriptivas
Distribuciones (histogramas)
Identificación de outliers (boxplots, IQR)
3. Feature Engineering
Creación de variables agregadas por usuario:
Cantidad de mensajes
Cantidad de llamadas
Minutos totales
Segmentación de clientes:
Por uso (Bajo, Medio, Alto)
Por edad (Joven, Adulto, Adulto Mayor)
4. Visualización
Histogramas segmentados por tipo de plan
Boxplots para detección de valores extremos
Gráficos de distribución por segmentos

📊 Insights Clave
Los usuarios jóvenes utilizan más mensajería que llamadas
Los usuarios adultos presentan un comportamiento más equilibrado
Los usuarios de alto uso representan el mayor valor para el negocio
Se detectaron outliers en llamadas y minutos, que pueden representar clientes premium o anomalías

💡 Recomendaciones de Negocio
Crear planes diferenciados por nivel de uso (bajo, medio, alto)
Diseñar ofertas específicas según edad del cliente
Implementar monitoreo de outliers para detectar fraude o usuarios premium
Aplicar estrategias de upselling a clientes de uso medio y alto

📈 Resultados

El análisis permitió transformar datos crudos en segmentos accionables, facilitando la toma de decisiones para mejorar la oferta de planes y la experiencia del cliente.

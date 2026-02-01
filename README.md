# friends-PowerBI
📊 Dashboard Friends

Equipo:

Patricia Merchán

Elena Pavón

Bienvenido a un análisis de datos inspirado en el universo de Friends.
En este proyecto hemos explorado información de episodios, diálogos y audiencia utilizando Power BI como herramienta principal de modelado y visualización. A partir de distintos datasets, hemos construido un dashboard interactivo que permite analizar el comportamiento de la audiencia, el peso narrativo de los personajes y la evolución de la serie a lo largo de sus temporadas.

El resultado es una combinación de limpieza de datos, cálculos avanzados y storytelling visual, orientada a extraer insights claros y accionables sobre una de las series más icónicas de la televisión.

🎯 Objetivo principal del proyecto

El propósito principal del proyecto es demostrar la capacidad técnica en Power BI para:

Gestionar y modelar fuentes de datos complejas

Realizar limpieza y transformación de datos mediante columnas calculadas y medidas DAX

Diseñar visualizaciones que cuenten una historia clara, atractiva y accesible

Aplicar cálculos avanzados, como traducciones condicionales y análisis comparativos de éxito entre episodios

🧩 Objetivos pormenorizados

Los objetivos se han dividido en función de los distintos bloques de trabajo del proyecto.

📥 Importación y gestión de datos en Power BI

Descarga y almacenamiento de los datasets en una carpeta local

Importación de los datasets en Power BI Desktop

Revisión del tipo de datos, formato de columnas y configuración regional

Modelado de datos y relaciones entre tablas (episodios, frases, audiencia, emociones)

Incorporación de nuevas columnas mediante Power Query

Transformaciones adicionales:

División de columnas por separador

Limpieza de texto

Normalización de valores

📐 Cálculos avanzados y transformación de datos

Creación de columnas calculadas para:

Traducir automáticamente la sinopsis de los episodios del inglés al español cuando era necesario

Identificar episodios con mayor y menor éxito en función de la audiencia

Agregación de datos a nivel de filas según criterios definidos

Uso de lógica condicional para clasificar episodios, temporadas y escenarios

Preparación del dataset para facilitar el análisis narrativo del dashboard

📊 Visualizaciones iniciales de análisis

KPIs / Big Numbers:

Audiencia media

Número total de episodios

Gráfico de barras:

Comparación entre personajes, temporadas o categorías

Gráfico de líneas:

Evolución de la audiencia a lo largo del tiempo

Histogramas:

Distribución de la audiencia

Gráficos circulares y donuts:

Proporciones entre variables categóricas

🎨 Personalización de visualizaciones

Uso de medidas DAX para métricas dinámicas

Gráficos tipo donut

Tooltips personalizados

Diseño y primer esbozo del dashboard completo

Inserción de imágenes y elementos visuales

Formato y coherencia visual de KPIs

🎛️ Filtros e interactividad

Filtros Top N

Filtros por temporada

Segmentadores interactivos

Descripciones emergentes para mejorar la experiencia del usuario

🧼 Inconsistencias y limpieza de datos

Limpieza de la columna Author

Normalización de texto (mayúsculas, minúsculas, errores de escritura)

Creación de campos personalizados para:

Temporada

Episodio

Clasificación de escenarios mediante palabras clave

🎯 Personalización del enfoque del proyecto

Desarrollo de un enfoque propio para el análisis de datos

Creación de dashboards enfocados a facilitar la comprensión de los insights

Equilibrio entre análisis técnico y narrativa visual

⭐ Insights y visualizaciones destacadas
📈 El pulso de la audiencia

KPIs y tendencias

Visualización de la audiencia media y total de episodios

Análisis de la evolución del interés del público a lo largo de las temporadas

Identificación de picos de popularidad y episodios más y menos exitosos

🗣️ ¿Quién domina la conversación?

Análisis de líneas de diálogo

Limpieza y normalización de la columna Author

Gráfico de barras comparando el número de frases por personaje

Uso de color y tamaño para destacar a los protagonistas

😊 Emociones a flor de piel

Cruce del dataset de frases con el de emociones

Visualización del “clima emocional” de la serie según el escenario

Identificación de la alegría como emoción predominante, lo que llevó a profundizar en el análisis del personaje de Phoebe

📊 Datasets utilizados

Para el desarrollo del proyecto se han utilizado los siguientes datasets:

- friends_episodes_v3

- friends_info

- friends_quote

Estos datasets han sido combinados y relacionados en Power BI para construir un modelo de datos coherente que permita el análisis cruzado de episodios, audiencia, diálogos y emociones.

🎨 Diseño en Power BI

Paleta de colores inspirada en la serie

Uso de contenedores visuales y composición cuidada

Navegación clara y experiencia de usuario intuitiva

Diseño coherente y temático alineado con la serie

🛠️ Desafíos técnicos superados

Limpieza de datos: inconsistencias en nombres de personajes

Modelado de datos: relaciones entre múltiples tablas

Cálculos avanzados:

Clasificación de escenarios por palabras clave

Traducción de sinopsis

Identificación automática de episodios más y menos exitosos

📁 Estructura del repositorio
/data        → Datasets originales obtenidos de Kaggle  
/images      → Imágenes utilizadas en el proyecto  
DashboardFriends.pbix → Archivo de Power BI con el modelo, visualizaciones y dashboard final  
# friends-PowerBI
Análisis del éxito de la serie friends usando Power BI 

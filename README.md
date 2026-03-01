# Pipeline de Procesamiento Masivo: Web Scraping y Optimización con Parquet
### Descripción del Proyecto
Este proyecto fue desarrollado como parte de la materia de Sistemas Inteligentes en la carrera de Matemáticas Aplicadas y Computación (UNAM). El objetivo principal fue automatizar la extracción de datos de la web y procesar grandes volúmenes de información (Big Data) de manera eficiente.

El flujo de trabajo incluyó la extracción de archivos comprimidos, la lectura de múltiples archivos CSV que sumaban aproximadamente 20 millones de registros y su posterior transformación para el análisis de KPIs.


### Tecnologías Utilizadas
*Lenguaje*: Python (Ejecutado en Google Colab).

*Extracción*: Web Scraping (uso de librerías para automatización de descargas).

*Procesamiento de Datos*: Pandas y PyArrow.

*Optimización de Almacenamiento*: Formato Parquet (reducción de uso de memoria y mejora en tiempos de lectura).

*Visualización*: Matplotlib / Seaborn para la generación de KPIs.

### Logros Técnicos y Desafíos
*Manejo de Big Data*: Gestión exitosa de una carga de trabajo de 20 millones de registros, superando las limitaciones típicas de memoria mediante el uso de formatos de almacenamiento columnar (Parquet).

*Automatización*: Implementación de un script de scraping que descarga y descomprime archivos de forma autónoma.

*Eficiencia*: Reducción significativa del tiempo de procesamiento al transitar de archivos planos (CSV) a un esquema optimizado.

### Resultados
Se generaron tableros visuales y métricas clave (KPIs) que permiten interpretar los datos extraídos, demostrando la capacidad de transformar datos crudos en conocimiento accionable.

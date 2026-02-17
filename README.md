## Análisis Exploratorio y Modelado Predictivo del Comportamiento de Clientes

Este proyecto desarrolla un Análisis Exploratorio de Datos (EDA) y modelos de regresión lineal para estudiar el comportamiento de compra de clientes en un entorno de comercio electrónico.

Objetivo

* Analizar las relaciones entre variables demográficas y de comportamiento (edad, género, visitas_web, compras) con el fin de identificar los principales factores que influyen en el monto_total de compra.

Contenido del Proyecto

* Limpieza y preparación de datos
* Estadística descriptiva
* Análisis de correlaciones
* Visualizaciones con Seaborn (pairplot, violinplot, jointplot, heatmap, FacetGrid)
* Modelos de regresión lineal simple y múltiple
* Visualizaciones personalizadas con Matplotlib


La variable compras es el principal predictor del monto_total.
La edad no muestra una influencia significativa en el gasto.
Existe una correlación positiva fuerte entre compras y monto_total.
No se detectaron diferencias estructurales relevantes por género.
El modelo de regresión simple explica una proporción significativa de la variabilidad del gasto.

Tecnologías Utilizadas
* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-Learn

Conclusión
El análisis demuestra que el comportamiento de compra, medido por el número de compras realizadas, es el factor más determinante del gasto total del cliente. Estos hallazgos pueden contribuir a la optimización de estrategias comerciales, segmentación de clientes y toma de decisiones basada en datos.

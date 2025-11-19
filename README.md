Proyecto EDA – Banco y Clientes

Este proyecto consiste en un análisis exploratorio de datos (EDA) realizado sobre dos datasets:
    •    customer-details.xlsx (clientes)
    •    bank-additional.csv (campaña bancaria)

El objetivo del análisis es revisar la calidad de los datos, entender las variables disponibles y detectar posibles outliers o patrones relevantes antes de pasar a fases posteriores.

Contenido del notebook

En el archivo analisis_EDA.ipynb se realiza:

1. Carga de datos
    •    Lectura de ambos datasets.
    •    Revisión de primeras filas y tipos de datos.
    •    Eliminación de columnas que no aportan valor (como índices automáticos).

2. Análisis de variables numéricas
    •    Estadísticos descriptivos.
    •    Histogramas para ver la distribución.
    •    Boxplots para identificar posibles outliers.

3. Análisis de variables categóricas
    •    Conteos de frecuencia.
    •    Gráficas de barras para visualizar categorías.

4. Matriz de correlación
    •    Revisión de relaciones entre variables numéricas del dataset del banco.

Conclusiones generales

No se detectan errores graves en los datos.
Hay algunos valores extremos en ciertas columnas (como age, duration, pdays…), pero son razonables según el contexto.
Las distribuciones son coherentes con lo esperado para este tipo de datos.
El conjunto de datos queda listo para fases posteriores del proyecto.

# Selección de Variables en Modelos de Regresión Lineal

## Descripción
Este repositorio contiene un análisis de selección de características aplicadas a un modelo de regresión lineal múltiple sobre un conjunto de datos de vino tinto. Se implementan las metodologías de **selección hacia adelante** y **selección hacia atrás** utilizando la librería `mlxtend`, y se comparan los modelos resultantes en términos de su capacidad predictiva medida con la métrica de $R^2$. El objetivo es identificar un subconjunto de variables que capture la mayor parte de la variabilidad en la variable dependiente, logrando un balance entre parsimonia y ajuste.

## **Contenido del proyecto**

- Importación y exploración inicial de datos (dimensiones, variables y primeras observaciones).
- Separación del conjunto en **datos de entrenamiento y prueba** con proporción 80/20.
- Aplicación del método de **selección hacia adelante** para identificar subconjuntos óptimos de predictores.
- Entrenamiento y evaluación de un modelo basado en las variables seleccionadas hacia adelante.
- Aplicación del método de **selección hacia atrás** partiendo de los predictores seleccionados previamente.
- Comparación de ambos enfoques y discusión sobre cuál modelo ofrece un mejor equilibrio entre simplicidad y capacidad predictiva.
- Análisis de los valores de $R^2$ en los distintos escenarios.

## **Documentos**

- [Reporte en formato .ipynb](./Reporte_SC.ipynb)
- [Reporte en formato .html](./Reporte_SC.html)
- [Reporte en formato .pdf](./Reporte_SC.pdf)
- [Base de datos .csv](./A1.4_Vino_Tinto.csv)

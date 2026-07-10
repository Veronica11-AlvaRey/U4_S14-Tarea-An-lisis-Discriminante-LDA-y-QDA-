# U4_S14-Tarea-An-lisis-Discriminante-LDA-y-QDA-
Aprendizaje Automático

# Comparación de LDA y QDA con Wine Dataset

## Descripción

Este proyecto compara el Análisis Discriminante Lineal (LDA) y el Análisis Discriminante Cuadrático (QDA) utilizando el archivo original `wine.data` del UCI Machine Learning Repository.

El conjunto se utiliza sin tratamiento previo:

- no se eliminan variables;
- no se imputan datos;
- no se normaliza;
- no se estandariza.

## Archivos

- `U4_S14_Tarea_Análisis_Discriminante_(LDA_y_QDA).ipynb`: notebook de Google Colab.
- `wine.data`: conjunto de datos original.

## Características del dataset

- 178 observaciones.
- 13 variables predictoras.
- 1 variable objetivo: `class`.
- 3 clases codificadas como 1, 2 y 3.
- 0 valores faltantes.

## Origen

El archivo se obtiene del UCI Machine Learning Repository https://archive.ics.uci.edu/dataset/109/wine. En el notebook también se incluye el enlace oficial como respaldo en caso de que el archivo local no esté disponible.

## Cómo ejecutar en Google Colab

1. Subir `U4_S14_Tarea_Análisis_Discriminante_(LDA_y_QDA).ipynb` a Google Colab.
2. Subir `wine.data` al almacenamiento de la sesión.
3. Ejecutar todas las celdas.

## Metodología

1. Carga del archivo `wine.data`.
2. Asignación manual de encabezados.
3. Exploración de dimensiones, tipos de datos y valores faltantes.
4. Estadísticas descriptivas y distribución de clases.
5. Cuatro visualizaciones con interpretación.
6. División estratificada 80/20.
7. Entrenamiento y evaluación de LDA.
8. Entrenamiento y evaluación de QDA.
9. Comparación de métricas.
10. Representación de fronteras de decisión.
11. Conclusiones.

## Resultados principales

| Modelo | Accuracy | Precisión macro | Recall macro | F1 macro |
|---|---:|---:|---:|---:|
| LDA | 0.9444 | 0.9505 | 0.9429 | 0.9453 |
| QDA | 1.0000 | 1.0000 | 1.0000 | 1.0000 |

QDA obtiene el mejor resultado en la partición utilizada. LDA también presenta un desempeño alto y utiliza una estructura más sencilla.

## Autor

Verónica Nathaly Alvarado Reyes

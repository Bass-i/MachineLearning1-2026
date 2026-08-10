# IrisFlow — Clasificación de especies Iris

Proyecto desarrollado para la asignatura MCDI504 — Machine Learning I.

## Integrantes

- Fabian Castillo
- Francisco Santelices
- Renato Villazón

## Descripción

IrisFlow representa una operación ficticia de recepción y empaque de flora
ornamental. El proyecto busca determinar si las características morfológicas
del dataset Iris permiten orientar una solución de Machine Learning para
clasificar flores en las especies setosa, versicolor y virginica.

## Objetivo

Caracterizar y preparar el dataset Iris para justificar la selección de un
enfoque de aprendizaje supervisado de clasificación multiclase.

## Enfoque seleccionado

Se seleccionó clasificación supervisada multiclase porque cada observación
dispone de una etiqueta conocida, Species, y la variable objetivo contiene
tres categorías nominales.

## Alcance de la Fase 1

Esta fase comprende:

- Definición del problema analítico.
- Caracterización del dataset.
- Análisis estadístico descriptivo.
- Visualización de distribuciones.
- Revisión de correlaciones y p-valores.
- Normalización de variables predictoras.
- Relación del proyecto con la metodología KDD.

En esta fase no se entrenan ni evalúan modelos predictivos.

## Estructura del repositorio

- `notebooks/F1_Definicion.ipynb`: notebook ejecutado y documentado.
- `docs/MCDI504_S1_1_GRUPO5.pdf`: informe técnico de la Fase 1.
- `requirements.txt`: librerías necesarias para ejecutar el notebook.

## Ejecución

1. Clonar o descargar el repositorio.
2. Abrir `notebooks/F1_Definicion.ipynb` en Google Colab o Jupyter Notebook.
3. Instalar las dependencias indicadas en `requirements.txt`.
4. Ejecutar todas las celdas en orden.

El dataset Iris se carga directamente desde `sklearn.datasets`, por lo que no
es necesario descargar un archivo de datos externo.

## Herramientas utilizadas

- Python
- pandas
- NumPy
- Matplotlib
- seaborn
- scikit-learn
- SciPy
- Google Colab/Jupyter Notebook
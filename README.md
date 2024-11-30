Modelo Predictivo: Titanic Dataset
Descripción del Proyecto
Este proyecto utiliza el Titanic Dataset para aplicar un modelo de regresión logística con el fin de predecir la probabilidad de supervivencia de los pasajeros en función de diferentes características como clase social, género, edad, tarifa del boleto, entre otras.

El objetivo es desarrollar un modelo de aprendizaje supervisado que sea interpretable y eficaz, demostrando habilidades en análisis exploratorio, preprocesamiento de datos, selección de características, entrenamiento y evaluación del modelo.

Estructura del Repositorio
Titanic-Dataset.csv: El dataset original utilizado en este proyecto.
Modelo_Titanic.ipynb: Notebook de Jupyter que contiene el código para el análisis, preprocesamiento, entrenamiento y evaluación del modelo de regresión logística.
README.md: Este archivo que detalla información sobre el proyecto.
Pasos Realizados
Análisis Exploratorio:
Revisión inicial de las características del dataset.
Identificación de valores nulos y tendencias clave.
Preprocesamiento de Datos:
Imputación de valores faltantes.
Codificación de variables categóricas.
Selección de características relevantes.
División del Dataset:
Separación en conjuntos de entrenamiento y prueba.
Entrenamiento del Modelo:
Uso de regresión logística para predecir la supervivencia.
Evaluación del Modelo:
Métricas utilizadas: Precisión, Recall, F1-Score, y Curva ROC-AUC.
Visualización de Resultados:
Curva ROC y gráficos de importancia de características.
Resultados
Precisión del Modelo: 81%.
Curva ROC-AUC: 0.88.
La variable más influyente en el modelo es el género del pasajero (Sex).
Requisitos para Reproducir
Instalar Anaconda y Jupyter Notebook.

Clonar este repositorio:

git clone (https://github.com/Ixoman/Tarea-5-Proyecto-An-lisis-de-Datos-)
Asegúrate de instalar las librerías necesarias:

pip install -r requirements.txt
(Si necesitas generar un requirements.txt, podemos añadir uno).

Ejecuta el notebook Modelo_Titanic.ipynb en Jupyter Notebook.

Autor
Este proyecto fue desarrollado como parte de una actividad académica para aplicar técnicas de aprendizaje supervisado. SAMUEL QUINTERO UNAD 2024

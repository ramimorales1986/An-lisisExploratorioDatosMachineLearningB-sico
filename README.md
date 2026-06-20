# An-lisisExploratorioDatosMachineLearningB-sico
Tarea 1 Análisis Exploratorio de Datos y Machine Learning
# Análisis de Aprobación de Créditos

## Descripción del Proyecto

Este proyecto fue desarrollado como parte de la asignatura **MTDI202: Big Data, Analytics & Data Scientist** de la **Maestría en Tecnologías de Información con mención en Transformación Digital e Innovación**.

El proyecto tiene como objetivo analizar un conjunto de datos de solicitudes de crédito en Ecuador para identificar patrones asociados a la aprobación o rechazo de créditos mediante técnicas de análisis exploratorio de datos (EDA) y Machine Learning supervisado.

## Problema de Negocio

Las instituciones financieras utilizan modelos de análisis de datos para evaluar el riesgo asociado a la aprobación de créditos.

La pregunta de investigación planteada es:

> ¿Es posible predecir si una solicitud de crédito será aprobada o rechazada utilizando información demográfica, laboral y financiera del solicitante?

## Variable Objetivo

**Estado_Credito**

* Aprobado
* Rechazado

## Objetivos

* Realizar la limpieza y preparación de los datos.
* Desarrollar un análisis exploratorio de datos (EDA).
* Identificar variables relevantes para la aprobación de créditos.
* Visualizar patrones y tendencias presentes en los datos.
* Construir un modelo de Machine Learning supervisado para la clasificación de solicitudes de crédito.
* Evaluar el desempeño del modelo mediante métricas de clasificación.

## Metodología

1. Carga y exploración inicial de datos.
2. Limpieza y tratamiento de valores faltantes.
3. Análisis exploratorio y visualización de datos.
4. Preparación de variables para el modelado.
5. Entrenamiento de modelos de Machine Learning.
6. Evaluación e interpretación de resultados.

## Tecnologías Utilizadas

* Python 3
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Estructura del Repositorio

```text
.
├── AnalisisExploratorioDatosMachineLearningBasico.ipynb
├── Creditos_Ecuador.csv
└── README.md
```

## Resultados Esperados

Desarrollar un modelo predictivo capaz de estimar la probabilidad de aprobación o rechazo de una solicitud de crédito, proporcionando información útil para apoyar la toma de decisiones en procesos de evaluación crediticia.

## Autor

**Ramiro Ivan Morales Pilaguano**

## Información Académica

**Maestría:** Tecnologías de Información mención en Transformación Digital e Innovación

**Módulo:** MTDI202: Big Data, Analytics & Data Scientist

**Docente:** Ing. Carlos Wladimir Carrillo Villavicencio MSc. TIC.

**Fecha:** Junio 2026

## Cómo Ejecutar el Proyecto

### Opción 1: Google Colab

1. Descargue el archivo `AnálisisExploratorioDatosMachineLearningBásico.ipynb`.
2. Ingrese a Google Colab.
3. Seleccione **Archivo → Subir notebook**.
4. Cargue el archivo `.ipynb`.
5. Ejecute las celdas del notebook en orden.
6. Cuando se solicite, cargue el archivo del dataset correspondiente.

### Opción 2: Jupyter Notebook

1. Instale Python y Jupyter Notebook.
2. Descargue o clone este repositorio.
3. Coloque el archivo del dataset en la misma carpeta del notebook.
4. Abra una terminal en la carpeta del proyecto.
5. Ejecute:

```bash
jupyter notebook
```

6. Abra el archivo `AnálisisExploratorioDatosMachineLearningBásico.ipynb`.
7. Ejecute las celdas secuencialmente.

### Carga del Dataset

El dataset utilizado debe encontrarse en la misma carpeta que el notebook o ajustarse la ruta de acceso según la ubicación del archivo.

Ejemplo de carga:

```python
import pandas as pd

df = pd.read_csv('Creditos_Ecuador.csv')
```

### Requisitos

Instalar las siguientes librerías:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```


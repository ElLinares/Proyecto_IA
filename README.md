# Predicción de la supervivencia empresarial en mercados internacionales

## Descripción

Este proyecto busca desarrollar un modelo de **Machine Learning capaz de predecir la probabilidad de supervivencia de una empresa al ingresar a un mercado internacional**.

La investigación se desarrolla en el contexto de la materia **IA Aplicada**, con el objetivo de explorar cómo las técnicas de aprendizaje automático pueden utilizarse para analizar procesos de internacionalización empresarial.

A partir de información sobre las características de las empresas y su proceso de internacionalización, se buscará identificar patrones asociados con el éxito o fracaso de las empresas al ingresar a mercados internacionales.

## Pregunta de investigación

> **¿Es posible predecir mediante técnicas de Machine Learning si una empresa sobrevivirá después de ingresar a un mercado internacional?**

## Objetivos

### Objetivo general

Desarrollar y evaluar modelos de Machine Learning capaces de predecir la supervivencia de empresas después de su entrada en mercados internacionales.

### Objetivos específicos

* Explorar y caracterizar los datos relacionados con empresas y procesos de internacionalización.
* Identificar las principales variables asociadas con la supervivencia empresarial en mercados internacionales.
* Realizar el procesamiento y transformación de los datos necesarios para el entrenamiento de los modelos.
* Entrenar diferentes algoritmos de Machine Learning para realizar la predicción.
* Comparar el desempeño de los diferentes modelos mediante métricas de evaluación apropiadas.
* Analizar la importancia de las variables utilizadas por los modelos.
* Identificar patrones que puedan contribuir a comprender los factores asociados con la supervivencia empresarial internacional.

## Metodología

El proyecto seguirá un flujo de trabajo de ciencia de datos compuesto por las siguientes etapas:

### 1. Obtención de los datos

Se identificarán y recopilarán fuentes de datos relevantes sobre empresas, internacionalización y desempeño empresarial.

### 2. Exploración de datos

Se realizará un análisis exploratorio para comprender:

* Distribución de las variables.
* Valores faltantes.
* Valores atípicos.
* Relaciones entre variables.
* Distribución de la variable objetivo.
* Diferencias entre empresas que sobreviven y aquellas que no.

### 3. Preprocesamiento

Los datos serán preparados para el entrenamiento de los modelos mediante técnicas como:

* Tratamiento de valores faltantes.
* Codificación de variables categóricas.
* Normalización o estandarización cuando sea necesaria.
* Selección y transformación de variables.
* División entre conjuntos de entrenamiento y prueba.

### 4. Modelos de Machine Learning

Se evaluarán diferentes algoritmos de clasificación. Dependiendo de las características finales de los datos, se considerarán modelos como:

* Regresión logística como modelo de referencia.
* Árboles de decisión.
* Random Forest.
* Gradient Boosting.
* XGBoost.
* Otros algoritmos que resulten pertinentes durante el desarrollo del proyecto.

### 5. Evaluación

Los modelos serán comparados utilizando métricas adecuadas para un problema de clasificación, entre ellas:

* Accuracy.
* Precision.
* Recall.
* F1-score.
* ROC-AUC.
* Matriz de confusión.

En caso de existir un fuerte desbalance entre empresas supervivientes y no supervivientes, se dará especial importancia a métricas como **Recall, F1-score y ROC-AUC**.

### 6. Interpretación

Además del desempeño predictivo, se analizará qué variables tienen mayor importancia en las predicciones del modelo.

Cuando sea posible, se utilizarán técnicas de **Explainable AI (XAI)** para interpretar los resultados y comprender qué características están asociadas con una mayor o menor probabilidad de supervivencia.

## Estructura del proyecto

```text
├── data/
│   ├── raw/              # Datos originales
│   └── processed/        # Datos procesados
│
├── notebooks/            # Análisis y experimentación
│
├── src/                  # Funciones y código reutilizable
│
├── results/              # Resultados, gráficos y tablas
│
├── requirements.txt      # Dependencias del proyecto
├── README.md             # Documentación
└── .gitignore            # Archivos excluidos del repositorio
```

## Tecnologías

El proyecto será desarrollado principalmente en **Python**, utilizando herramientas de análisis de datos, visualización y Machine Learning.

Entre las principales librerías se encuentran:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* SHAP
* Jupyter

## Reproducibilidad

Para reproducir el proyecto, se recomienda utilizar un entorno virtual de Python e instalar las dependencias especificadas en `requirements.txt`.

```bash
pip install -r requirements.txt
```

Posteriormente, los notebooks pueden ejecutarse en orden siguiendo la numeración establecida en la carpeta `notebooks/`.

## Resultados esperados

Se espera obtener un modelo capaz de clasificar empresas según su probabilidad de supervivencia después de su internacionalización.

Además del desempeño predictivo, el proyecto busca identificar los factores que presentan una mayor relación con la supervivencia empresarial y evaluar hasta qué punto las técnicas de Machine Learning pueden aportar información adicional frente a métodos estadísticos tradicionales.

## Autores

**Juan Pablo Lozano Menndez**
**Juan Esteban Roa Rodriguez**
**Andres Felipe Linares Medina**

Universidad Externado de Colombia
Facultad de Economía
Curso: IA Aplicada
2026

## Estado del proyecto

🚧 **En desarrollo**

El proyecto se encuentra actualmente en etapa de definición, recopilación y exploración de datos.

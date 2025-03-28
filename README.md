# **Actividad - API REST para Modelos de ML (Unidad 4, Tema 3)**
## **Luis Enrique Jr. Pinto Fuentes - 202422875**

Para ejemplificar la creación de una API REST para modelos de ML, se empleó un modelo de clasificación basado en un Random Forest para predecir si un paciente tiene diabetes. La información del dataset esta disponible en: https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset.

Para dividir los datos en conjuntos de prueba y entrenamiento, primero se realizó un análisis exploratorio utilizando **YData Profiling**. Posteriormente, se entrenó el modelo y se generó el archivo **"diabetes_model.pkl"**. Para permitir la realización de predicciones, se implementó un endpoint en **FastAPI**. Finalmente, para exponer la API local en el puerto 80 y habilitar las peticiones mediante **cURL**, se utilizó **ngrok**.

## **Tecnologías utilizadas**
- **Python**: Lenguaje de programación principal.
- **scikit-learn**: Implementación del modelo de **Random Forest**.
- **pandas** y **numpy**: Manipulación y procesamiento de datos.
- **seaborn** y **matplotlib**: Visualización de datos y métricas.
- **YData Profiling**: Análisis exploratorio de datos.
- **FastAPI**: Creación de la API REST.
- **ngrok**: Exposición de la API en un dominio accesible.
- **cURL**: Pruebas de la API mediante peticiones HTTP.
- **joblib**: Guardado y carga del modelo entrenado.

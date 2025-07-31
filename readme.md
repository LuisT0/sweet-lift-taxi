# Sweet Lift Taxi: Predicción de Demanda con Series Temporales

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📖 Descripción

Este proyecto aborda un problema de **series temporales** para la empresa Sweet Lift Taxi. El objetivo es predecir la cantidad de pedidos de taxis en aeropuertos para la próxima hora, permitiendo a la empresa optimizar la disponibilidad de conductores y satisfacer la demanda durante las horas pico. Para lograrlo, se ha desarrollado un modelo de Machine Learning entrenado con datos históricos de pedidos.


## ✨ Fases del Proyecto

El proceso completo, documentado en el Jupyter Notebook, cubrió las siguientes etapas:

*   **Análisis Exploratorio (EDA):** Visualización de tendencias, estacionalidad y patrones en los datos históricos.
*   **Ingeniería de Características:** Creación de variables temporales (hora, día de la semana) y medias móviles para enriquecer el modelo.
*   **Entrenamiento de Modelos:** Implementación y evaluación de diversos algoritmos de regresión.
*   **Evaluación Rigurosa:** Medición del rendimiento del modelo final en un conjunto de prueba nunca antes visto.

## 🎯 Hallazgos Clave del Modelo

**¡Aquí es donde se pone bueno!** El análisis del rendimiento de los modelos reveló conclusiones importantes:

*   **Sobreajuste (Overfitting) Identificado:** Se detectó que modelos complejos como Random Forest, aunque muy precisos en el entrenamiento, no generalizaban bien al conjunto de prueba, mostrando un error (RMSE) significativamente mayor. Esto indica que "memorizaban" los datos en lugar de aprender las tendencias reales.
*   **El Dilema Estabilidad vs. Precisión:** Modelos más simples o con técnicas de regularización demostraron ser más estables y consistentes entre entrenamiento y prueba. Este es un hallazgo clave para aplicaciones en producción, donde la fiabilidad y la predictibilidad del error son cruciales.
*   **Ruta de Optimización Clara:** La conclusión principal es la necesidad de mejorar la generalización. Los siguientes pasos recomendados incluyen una optimización de hiperparámetros más robusta (ej. con Optuna o Hyperopt), una ingeniería de características más avanzada y la exploración de ensambles de modelos (stacking/blending) para combinar las fortalezas de varios algoritmos.

## 🛠️ Tecnologías Usadas

<p align="left">
  <a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
  <a href="https://pandas.pydata.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a>
  <a href="https://scikit-learn.org/" target="_blank"> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1200px-Scikit_learn_logo_small.svg.png" alt="scikit-learn" width="40" height="40"/> </a>
  <a href="https://matplotlib.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/matplotlib/matplotlib-original.svg" alt="matplotlib" width="40" height="40"/> </a>
  <a href="https://seaborn.pydata.org/" target="_blank"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a>
  <a href="https://jupyter.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jupyter/jupyter-original-wordmark.svg" alt="jupyter" width="40" height="40"/> </a>
</p>

## ⚙️ Instalación y Uso

1.  **Clona el repositorio:**
    ```
    git clone https://github.com/tu-usuario/sweet-lift-taxi.git
    cd sweet-lift-taxi
    ```
2.  **Crea y activa un entorno virtual:**
    ```
    python -m venv venv
    source venv/bin/activate  # En Windows: venv\Scripts\activate
    ```
3.  **Instala las dependencias:**
    ```
    pip install -r requirements.txt
    ```
4.  **Ejecuta Jupyter Notebook:**
    ```
    jupyter notebook
    ```
    Navega a `notebooks/SweetLiftTaxi.ipynb` para ver el proyecto completo.

## 👤 Autor

¡Hablemos de datos y modelos predictivos!

*   **GitHub:** [LuisT0](https://github.com/LuisT0)
*   **LinkedIn:** [Luis Antonio Torres Villalobos](https://www.linkedin.com/in/luis-antonio-torres-villalobos/)

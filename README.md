# Probability of default o probabilidad de impago de un préstamo

Este repositorio contiene un análisis del dataset loan_light.csv y se desarrollan modelos con machine learning para predecir la probabilidad de impago de un préstamo. Se evalúa el modelo iterando con distintas variables, tanto cuantitativas como cualitativas. El objetivo es que la métrica con la que se evaluará se aproxime a 1. En este caso, se alcanzó una probabilidad de 0.7, lo cual no está mal.

## Requisitos
* Python 3.x
* Pandas
* Numpy
* Seaborn
* Scikit-learn

## Instalación
1. Clona este respositorio:
   ```sh
   git clone https://github.com/JosueMonte/Probability-of-Default.git
   cd Probability-of-Default
   ```
2. **Crea y activa un entorno virtual** (opcional pero recomendado):
    ```bash
    # En Windows
    python -m venv env
    .\env\Scripts\activate

    # En macOS y Linux
    python3 -m venv env
    source env/bin/activate
    ```
3. **Instala las dependencias**:
    ```bash
    pip install -r requirements.txt
    ```

## Uso

Ejecutar el código completo del notebook "probability_default.ipynb". El notebook incluye:
1. Un Análisis Exploratorio de los Datos (EDA).
2. Un Modelamiento con machine learning.

## Resultados

El notebook finalmente muestra el resultado de la métrica AUC (Área bajo la curva) para 10 puntos de folds. Es decir, se establece un rango de predicción para distintas muestras de entrenamiento y prueba. Finalmente, se agregan las observaciones, conclusiones y puntos claves a tener en cuenta.

## Contribución

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request si tienes sugerencias o mejoras.
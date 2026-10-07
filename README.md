# TP_Redes_Neuronales_Fraude
# Detección de Fraude con Autoencoders

## Descripción
Este proyecto implementa una Red Neuronal (Autoencoder Denso) para la detección de fraudes en tarjetas de crédito mediante el análisis del error de reconstrucción (Detección de Anomalías). Se compara contra un baseline de Regresión Logística.

## Reproducibilidad
* Dataset público en Kaggle: [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) (Licencia DbCL).
* Semillas fijadas (`np.random.seed(42)`, `tf.random.set_seed(42)`).

## Instrucciones de ejecución
1. Descargar el dataset de Kaggle y extraer `creditcard.csv`.
2. Subir el archivo CSV al entorno de Google Colab.
3. Ejecutar el notebook `TP_Redes_Fraude.ipynb` secuencialmente.

## Librerías utilizadas
* pandas
* numpy
* scikit-learn
* tensorflow (keras)
* matplotlib
* seaborn

# 👕 StyleNet: Clasificador Inteligente de Ropa con Deep Learning

Este proyecto desarrolla una solución de inteligencia artificial para la tienda virtual **StyleNet**, automatizando la categorización de productos mediante Redes Neuronales.

## 🎯 Objetivo
Sustituir el etiquetado manual de inventario por un modelo de **Deep Learning** capaz de clasificar imágenes de prendas de vestir en 10 categorías distintas con alta precisión.

## 🧠 Arquitectura del Modelo
Se implementó una **Red Neuronal Convolutiva (CNN)** utilizando la API de Keras/TensorFlow. La estructura incluye:
* **Capas Convolucionales:** Para la extracción de características visuales (bordes, formas).
* **Max-Pooling:** Para la reducción de dimensionalidad.
* **Dropout (0.2):** Técnica de regularización para prevenir el overfitting.
* **Capas Densas:** Para la clasificación final basada en las características extraídas.

## 🛠️ Tecnologías Utilizadas
* **Python 3.13**
* **TensorFlow / Keras:** Construcción y entrenamiento de la red neuronal.
* **Matplotlib:** Visualización de métricas y predicciones.
* **NumPy:** Procesamiento de matrices de imágenes.
* **Dataset:** Fashion-MNIST (60,000 imágenes de entrenamiento, 10,000 de prueba).

## 📈 Resultados
El modelo logra una exactitud (accuracy) de aproximadamente **91%** en el conjunto de test, clasificando correctamente categorías como:
* Camisetas, Pantalones, Suéteres, Vestidos, Abrigos, Sandalias, Camisas, Zapatillas, Bolsos y Botines.

## 🚀 Instalación y Uso
1. Clonar el repositorio.
2. Instalar dependencias:
   ```bash
   pip install tensorflow matplotlib numpy

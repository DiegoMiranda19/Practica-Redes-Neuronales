# Clasificación de Cáncer con Redes Neuronales Convolucionales (CNN) 🧬🔬

Este proyecto es una práctica de **Visión Computacional** orientada al sector salud. El objetivo es desarrollar un modelo de aprendizaje profundo capaz de clasificar diferentes tipos de cáncer a partir de imágenes médicas, utilizando el dataset **Multi-cancer** de Kaggle.

## 📊 Sobre el Dataset
El modelo utiliza el dataset [Multi-cancer](https://www.kaggle.com/datasets/obulisainaren/multi-cancer), que incluye diversas categorías de imágenes histopatológicas.
- **Entrada:** Imágenes en color (RGB).
- **Salida:** Clasificación multiclase.

## 🚀 Arquitectura del Modelo
Se implementó una red neuronal convolucional (CNN) estructurada de la siguiente manera:
1. **Capas de Convolución (Conv2D):** Para la extracción de características espaciales.
2. **Capas de Agrupación (MaxPooling2D):** Para reducir la dimensionalidad y evitar el sobreajuste.
3. **Capas Densas (Fully Connected):** Para la toma de decisiones final basada en los mapas de características.
4. **Activación Softmax:** Para obtener las probabilidades de cada categoría.



[Image of Convolutional Neural Network architecture for image classification]


## 🛠️ Stack Tecnológico
* **Python** 3.x
* **TensorFlow / Keras** (Motor de IA)
* **OpenCV / PIL** (Procesamiento de imágenes)
* **Matplotlib / Seaborn** (Visualización de métricas)

## 📦 Instalación

1. **Clonar y entrar al proyecto:**
   ```bash
   git clone [https://github.com/DiegoMiranda19/Practica-Redes-Neuronales.git](https://github.com/DiegoMiranda19/Practica-Redes-Neuronales.git)
   cd Practica-Redes-Neuronales

# Redes Neuronales II

**Especialización en Inteligencia Artificial**
**Autor:** Harold Steven Rueda Lara

Implementación progresiva de redes neuronales artificiales, desde una neurona simple hasta clasificación multiclase con TensorFlow/Keras y PyTorch, aplicando funciones de activación (Sigmoide, ReLU, Softmax) y backpropagation. Sin uso de redes convolucionales.

## Contenido

| Notebook | Laboratorio | Descripción |
|---|---|---|
| `01_Frutas_NumPy.ipynb` | A | Neurona única (perceptrón con Sigmoide) desde cero con NumPy — clasificación binaria manzana vs. banano |
| `02_Frutas_Multicapa_NumPy.ipynb` | B | Red multicapa (3→4→1) desde cero con NumPy — ReLU + backpropagation multicapa |
| `03_Frutas_Keras.ipynb` | C | El mismo problema binario automatizado con TensorFlow + Keras |
| `04_Frutas_Multiclase_Keras.ipynb` | D | Clasificación multiclase (manzana, banano, naranja) con Softmax |
| `05_MNIST_Keras.ipynb` | E | Reconocimiento de dígitos MNIST (0-9) con Keras, arquitectura densa 784→128→10, sin CNN |
| `06_MNIST_PyTorch.ipynb` | F | El mismo problema de MNIST resuelto con PyTorch |

## Cómo ejecutar

1. Abrir cada notebook en [Google Colab](https://colab.research.google.com/).
2. Ejecutar todas las celdas en orden (**Entorno de ejecución → Ejecutar todas**).
3. Los notebooks `05` y `06` descargan el dataset MNIST completo (70.000 imágenes) la primera vez que se ejecutan.

## Resultados obtenidos

| Laboratorio | Modelo | Accuracy |
|---|---|---|
| A | Neurona única (NumPy) | 1.00 |
| B | Red multicapa (NumPy) | 1.00 |
| C | Keras binario | 1.00 |
| D | Keras multiclase | 1.00 |
| E | Keras MNIST | ~0.97 (dataset completo en Colab) |
| F | PyTorch MNIST | ~0.96 (dataset completo en Colab) |

## Documento técnico

El documento técnico completo (PDF) con código, explicaciones, resultados y evidencias de ejecución se encuentra en la entrega de la plataforma institucional.

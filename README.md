# Fashion MNIST GAN 🧵 

Este repositorio contiene la implementación de una Red Generativa Antagónica (GAN) para la generación de imágenes de prendas y accesorios utilizando el dataset Fashion MNIST.

## Descripción del Problema 📌

El objetivo de este proyecto es implementar una GAN capaz de generar imágenes realistas de prendas y accesorios. Se utiliza el dataset Fashion MNIST, que contiene 60,000 imágenes de entrenamiento y 10,000 imágenes de prueba en escala de grises de 28x28 píxeles, clasificadas en 10 categorías diferentes.

## Estructura del repositorio 📂 

* README.md → Descripción del problema y detalles del proyecto. 📄 

* GAN_mnist_prendas_FernandezAlejandro.ipynb → Cuaderno Jupyter con la implementación del código. 📓 

* Modelos entrenados: generador_fashion_101ep.keras y discriminador_fashion_101ep.keras. 🤖 

* Muestra de imágenes generadas: imagenes_generadas.png. 🖼️ 

## Resultados y Posibles Mejoras 📊 

### Resultados Iniciales ✅ 

Las imágenes generadas son un buen punto de partida, pero pueden presentar detalles borrosos o baja resolución.

### Mejoras Potenciales 🚀 

Para mejorar la calidad de las imágenes generadas, se pueden aplicar las siguientes estrategias:

📌 Incremento del entrenamiento:

* Aumentar el número de épocas de entrenamiento para mejorar la calidad de las imágenes.

📌 Ajuste de hiperparámetros:

* Modificar el tamaño del BATCH_SIZE y la dimensión del espacio latente (LATENT_DIM) para mejorar la estabilidad del entrenamiento.

📌 Optimización de la arquitectura:

* Modificar la arquitectura del generador, agregando capas adicionales para capturar más detalles.

* Introducir técnicas de normalización avanzada para mejorar la convergencia.

📌 Uso de técnicas avanzadas:

* Implementar Wasserstein GAN (WGAN) para mejorar la estabilidad del entrenamiento.

* Ajustar la función de pérdida para obtener mejores resultados.

## Conclusión 🎯 

Esta implementación de una GAN sobre Fashion MNIST demuestra el proceso de generación de imágenes a través de redes neuronales. Aunque los resultados iniciales pueden requerir ajustes, este proyecto sirve como base para explorar mejoras en la arquitectura y en los hiperparámetros, logrando generar imágenes más realistas y detalladas. 🚀

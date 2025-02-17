# Fashion MNIST GAN

Este repositorio contiene la implementación de una Red Generativa Antagónica (GAN) para la generación de imágenes de prendas y accesorios utilizando el dataset Fashion MNIST.

## Descripción del Problema

El objetivo de este proyecto es implementar una GAN capaz de generar imágenes realistas de prendas y accesorios. Se utiliza el dataset [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist), que contiene 60,000 imágenes de entrenamiento y 10,000 imágenes de prueba en escala de grises de 28x28 píxeles, clasificadas en 10 categorías diferentes.

La entrega de la tarea incluye:
- Una descripción del problema en este README.
- Un cuaderno Jupyter (`GAN_mnist_prendas_FernandezAlejandro.ipynb`) con todo el código de la implementación.
- Los archivos de los modelos entrenados: `generador_fashion_101ep.keras` y `discriminador_fashion_101ep.keras`.
- Una muestra de las imágenes generadas por la GAN (`imagenes_generadas.png`).

## Resultados y Posibles Mejoras
* Resultados Iniciales: Las imágenes generadas son un buen punto de partida, pero pueden presentar detalles borrosos o baja resolución.
* Mejoras Potenciales:
 *Aumentar el número de épocas de entrenamiento.
 *Ajustar hiperparámetros, como el `BATCH_SIZE` y el `LATENT_DIM`.
 *Modificar la arquitectura del generador (por ejemplo, añadiendo capas adicionales para capturar más detalles).
 *Experimentar con técnicas avanzadas (como WGAN) o ajustar la función de pérdida.

## Conclusión
Esta implementación de una GAN sobre Fashion MNIST demuestra el proceso de generación de imágenes a través de redes neuronales. Aunque los resultados iniciales pueden requerir ajustes, el proyecto sirve como base para explorar mejoras en la arquitectura y en los hiperparámetros, logrando generar imágenes más realistas.  

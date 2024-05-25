# MIAX12-ANN

Material preparado para las clases de Redes Neuronales del máster MIAX: Edición 12 

Autores:

* Christian Oliva Moya

* Luis Fernando Lago Fernández

<hr>

## Contenido del repositorio

* `data` incluye algunos ficheros de datos para trabajar durante la parte práctica de las clases.

* `notebooks` incluye los notebooks que estamos usando como práctica durante las clases. En particular, un notebook tendrá el siguiente nombre: `<BLOQUE>_<N>_<DESCRIPCION>.ipynb`, donde `<BLOQUE>` será el bloque del temario que tiene relación con el notebook, `<N>` es simplemente un ordinal y `<DESCRIPCION>` da nombre al notebook. Por ejemplo, el notebook `2_1_linear_regression.ipynb` es el primer notebook del bloque 2.

* `slides` incluye las diapositivas que se están viendo durante las clases.

## Temario

* **Bloque 1: Introducción** [2024-05-10]
  * Notebook *1_1_intro*. Introducción al curso. Ejercicios sencillos de numpy y broadcasting.

* **Bloque 2: Regresión Lineal y Logística. Descenso por gradiente** [2024-05-10 y 2024-05-11]
* [2024-05-10]
  * Notebook *2_1_linear_regression*. Implementación manual de una regresión lineal mediante descenso por gradiente. Uso de la librería SKlearn. Modelo CAPM con regresión lineal.
* [2024-05-11]
  * Notebook *2_2_logistic_regression*. Implementación manual de una regresión logística mediante descenso por gradiente. Uso de PCA para reducción de dimensionalidad. Iris dataset como ejemplo One-vs-Rest. Modelo lineal no separa espacio no lineal. Transformación manual del espacio para hacerlo separable linealmente.
 
* **Bloque 3: Red Neuronal Artificial. Backpropagation** [2024-05-15 y 2024-05-16]
  * Notebook *3_1_red_neuronal_completa*. Implementación manual de una red neuronal completa, incluyendo Backpropagation. Ejercicios de regresión y clasificación con 1 y 2 capas.

* **Bloque 4: Tensorflow** [2024-05-17]
  * Notebook *4_1_intro_tensorflow*. Implementación manual de regresión lineal y logística y una red neuronal multicapa con tensorflow.
  * Notebook *4_2_problema_multiclase*. Implementación manual de un modelo One-vs-Rest y una red neuronal multiclase con Softmax usando tensorflow.

* **Bloque 5: Keras** [2024-05-18, 2024-05-22, 2024-05-23 y 2024-05-24]
* [2024-05-18]
  * Notebook *5_1_intro_keras*. Introducción a Keras. Experimentación con learning rate, batch size, funciones de activación, función de coste. Regularización.
* [2024-05-22]
  * Notebook *5_2_optimizers*. Explicación visual del efecto de los diferentes optimizadores.
  * Notebook *5_3_gridsearch*. Explicación de búsqueda de hiperparámetros con la técnica de búsqueda en rejilla.
  * Notebook *5_4_keras_tuner*. Explicación del algoritmo de fine-tuning de hiperparámetros.
  * Notebook *5_5_hparams*. Herramienta de visualización de diferentes modelos.
* [2024-05-23 y 2024-05-24]
  * Notebook *5_6_optimizacion_hiperparametros_keras*. Experimentación con inicialización de pesos, batch normalization, optimizadores y búsqueda de hiperparámetros con gridsearch y keras-tuner.
  * Notebook *5_7.1_diseño_capa_keras*. Ejemplo de diseño de una capa custom de Keras.
  * Notebook *5_7.2_diseño_redes*. Ejercicios de diseño de redes más complejas en Keras. Multi-input y Multi-etiqueta.
  * Notebook *5_7.3_intro_keras_autoencoder*. Introducción al concepto de los autoencoders. Diseño de un autoencoder básico en Keras.
 
* **Bloque 6: Pytorch** [2024-05-24]
  * Notebook *6_1_pytorch*. Introducción a Pytorch. Implementación de una red completa.

* **Bloque 7: Kohonen** [2024-05-24]
  * Notebook *7_1_kohonen*. Introducción a las redes de Kohonen. Problema del viajante con Kohonen.

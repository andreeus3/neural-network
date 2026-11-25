# neural-network

# Creating a neural network from a image with 50k inputs. 

## IMPLEMENTACIÓN DE REDES NEURONALES CON ARQUITECTURA

- *RELU* - Como funcion de activación porque su entrenamiento suele ser más rapido

- *SOFTMAX* - Para la capa de salida debido a que fuerza que las salidas de la red representen una distribución de probabilidad.

- *CATEGORICAL CROSS-ENTROPY* - Para calcular la perdida, al combinarse con la función de activación Softmax, su derivada se vuelve muy sencilla y lineal. Esto evita que el aprendizaje se estanque y acelera la convergencia del modelo.
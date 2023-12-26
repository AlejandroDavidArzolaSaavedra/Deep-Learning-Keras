# 📄 Práctica: Experimentación en Redes Neuronales - Keras

<img align="left" width="250" height="180" src="https://i.imgur.com/RsmO2hP.gif?raw=true"></a>
Esta práctica tiene como objetivo explorar y comparar diferentes configuraciones de hiperparámetros en redes neuronales aplicadas al conjunto de datos Iris.

Se experimentará con variables como el número de capas 🏗️, el número de neuronas por capa 🤖, las funciones de activación ⚡, el optimizador 🚀, la función de pérdida 📉, el número de épocas ⏳, el tamaño del batch 📦, entre otros.
<div id="user-content-toc">
  <ul>
    <summary><h2 style="display: inline-block">¡Que los experimentos comiencen! 🚀🔬💻</h2></summary>
  </ul>
</div>

# 👥 Equipo de desarrollo (Ctrl + Click para ver los perfiles)

[![GitHub](https://img.shields.io/badge/GitHub-Andrea%20Santana%20Lopez-purple?style=flat-square&logo=github)](https://github.com/AndreaSantalos)

[![GitHub](https://img.shields.io/badge/GitHub-Alejandro%20David%20Arzola%20Saavedra-blue?style=flat-square&logo=github)](https://github.com/AlejandroDavidArzolaSaavedra)


## Conjunto de Datos Iris 🌷

El conjunto de datos Iris consta de tres clases de flores:

<ul align="center">		
  <a href="https://www.kaggle.com/datasets/uciml/iris" target="_blank">
    <img style="width:50rem"  src="https://i.imgur.com/LoELZjM.png">
  </a>
</ul>

## Experimentación con Hiperparámetros

Se llevará a cabo la experimentación con las siguientes variables:

1. **Número de capas:** Se probarán diferentes configuraciones de capas ocultas.
2. **Número de neuronas por capa:** Variará el número de neuronas en cada capa oculta.
3. **Funciones de activación:** Se evaluarán diferentes funciones de activación, como ReLU, sigmoid, tanh, entre otras.
4. **Optimizador:** Se compararán optimizadores como SGD, Adam, RMSprop, entre otros.
5. **Función de pérdida:** Se probarán diversas funciones de pérdida, como categorical crossentropy, mean squared error, etc.
6. **Número de epoch:** Variará el número de epoch durante el entrenamiento.
7. **Tamaño del batch:** Se experimentará con diferentes tamaños de lote.

## Mejores Configuraciones y Análisis

Las configuraciones que ofrecieron el mejor rendimiento fueron aquellas con una mayor cantidad de capas ocultas y neuronas intermedias, utilizando la función de activación ReLU, el optimizador Adam, la función de pérdida categorical crossentropy, un número mayor de épocas y un tamaño de lote moderado.

Se observó que configuraciones más complejas y profunda red neuronal resultaron en un mejor rendimiento, especialmente para el conjunto de datos Iris versicolor y Iris virginica.

## Cómo Ejecutar la Experimentación

Para ejecutar la experimentación y realizar pruebas, sigue estos pasos:

1. Clona este repositorio en tu máquina local:
```bash
git clone <https://github.com/AlejandroDavidArzolaSaavedra/practicas_fsi/edit/deepLearningKeras>
```
2. Navega al directorio de la práctica:
```bash
cd deepLearningKeras
```
3. Ejecuta el programa principal con los archivos modificados:
```bash
python Keras_iris.ipynb
```

Observa los resultados de las pruebas y las comparaciones entre las diferentes configuraciones de hiperparámetros. ¡Experimenta y ajusta para obtener los mejores resultados! 

# 🤝 Contribuciones

Si deseas contribuir a este proyecto, siéntete libre de hacerlo. Puedes abrir problemas (issues) o enviar solicitudes de extracción (pull requests) para mejorar el código o agregar nuevas características. ¡Tu colaboración es bienvenida!

# Módulo 3: Regresión Lineal
================================================================================

Bienvenidos al módulo 3 del curso introductorio a ML, donde exploraremos la regresión lineal: ¡el primer algoritmo de machine learning de este curso!

Metas
----
Al final de este módulo, deberíamos sentirsnos cómodos con los fundamentos de la regresión lineal. Los temas específicos incluidos son:
1. Cómo dividir los datos entre datos de entrenamiento y datos de prueba
2. Uso de los datos de entrenamiento para entrenar un modelo de regresión lineal
3. Análisis de los resultados del modelo.
4. Comprobación de los supuestos de regresión lineal
5. Construcción de un regresor multivariante

## Resumen del tema
La regresión lineal es un modelo paramétrico que predice una característica de resultado continuo (** Y **) a partir de una o más características explicativas (** X **). 

**Y** = beta_0 + beta_1 * **X**

beta_0 se denomina término de intercepción y representa el valor medio esperado de Y cuando todas las características explicativas son iguales a 0. 
beta_1 se llama coeficiente beta y representa el cambio esperado en el valor de Y que resulta de un cambio de una unidad en X.

Este es un módulo que se ajusta en línea recta a sus datos, donde el valor de la característica de resultado se puede calcular como una combinación lineal de las características explicativas. ¿Suena relativamente simple? ¡No temas, hay muchos matices y condiciones que deben entenderse antes de usar la regresión lineal! Vamos a profundizar en estos supuestos y condiciones y luego demostraremos cómo usar este algoritmo en un conjunto de datos.


![Image](https://imgs.xkcd.com/comics/linear_regression.png)


## Recursos
- [Comprehensive Guide to Regression](https://www.analyticsvidhya.com/blog/2015/08/comprehensive-guide-regression/)
- [Understanding key regression statistics](http://connor-johnson.com/2014/02/18/linear-regression-with-python/)

## Temas avanzados
La regresión lineal es un miembro de una familia de modelos paramétricos lineales. Algunos temas avanzados adicionales que recomendamos buscar son ...
### Regresión logística
La regresión logística es muy similar a la regresión lineal, pero tiene un resultado categórico. Entonces, en lugar de modelar una variable dependiente continua, modela una clasificación binaria: sí o no, verdadero o falso, 1 o 0. Este sigue siendo un modelo lineal, ya que supone una relación lineal entre las variables independientes y la función de enlace.  

Para obtener más información sobre la regresión logística, prueba con los siguientes recursos:
- [Beginners guide to Logistic Regression](https://www.analyticsvidhya.com/blog/2015/11/beginners-guide-on-logistic-regression-in-r/): A good overview of the theory and mathematics behind the algorithm
- [Logistic Regression in Python](http://blog.yhat.com/posts/logistic-regression-python-rodeo.html): A thorough tutorial on a publicly available dataset in Python

### Regresión Ridge y Lasso
Tanto la regresión lineal como la logística tienen una tendencia a sobreajustarse cuando hay una gran cantidad de características. Por lo tanto, es importante que elijamos las características que tienen el mayor poder predictivo, pero ¿cómo elegimos estas características? Podemos usar nuestro EDA, pero eso solo llega hasta cierto punto.

¡Aquí es donde entran en juego las técnicas de regularización ridge y lasso! Ambas técnicas pueden usarse para identificar qué características explican la mayor variación y, por lo tanto, deben mantenerse en el modelo.

Para obtener más información sobre la regresión ridge y lasso y las técnicas de regularización general, recomendamos los siguientes recursos:
- [Complete tutorial on ridge and lasso regression in python](https://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-ridge-lasso-regression-python/): A broad tutorial explaining why we use regularization techniques, touching on the mathematics behind the algorithms and giving a few examples in python.
- [An Introduction to Statistical Learning, Chapter 6.2](http://www-bcf.usc.edu/%7Egareth/ISL/ISLR%20Sixth%20Printing.pdf): A comprehensive explanation of both Lasso and Ridge and their application in the context of statistical learning.


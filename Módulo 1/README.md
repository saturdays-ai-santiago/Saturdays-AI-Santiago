Módulo 1: 
=====

Parte 1: Introducción al analisis exploratorio de datos

¡Bienvenido al primer módulo! En este módulo, comenzaremos a explorar nuestro conjunto de datos.

 Metas
----
- Cargar nuestros datos y hacer una exploración rápida.
- Comprender los datos utilizando estadísticas descriptivas y gráficos.

Resumen del tema
----

El objetivo del análisis exploratorio es resumir las características principales de un conjunto de datos, con la creencia de que puede conducir a nuevas hipótesis que informen la selección y experimentación del algoritmo. El análisis exploratorio ocurre antes de que comience el modelado formal, y es extremadamente importante para ayudar a informar o agudizar su hipótesis.


Parte 2: Feature Engineering


Welcome to Module 2 of the introductory course to machine learning, where we will create new variables out of the raw data in a process called feature engineering!

Metas
------
Aprende a ejecutar lo siguiente: 
1. Selección de características
2. Características temporales de ingeniería (mes, año, etc.)
3. One-hot encoding / variables dummy 
4. Extracción de características desde strings
5. Creación de características a partir de metadatos
6. Escalamiento de características
7. Imputación / limpieza de datos

Resumen del tema
-----

**¿Qué es la ingeniería de características?**

En el aprendizaje automático, una *característica* es una propiedad o característica de un fenómeno que se observa. * Ingeniería de características* es el proceso de crear y seleccionar características de los datos que son útiles para los algoritmos de aprendizaje automático.

El conjunto de datos contiene muchas características para comenzar, entonces, ¿por qué necesitamos crear algunas más?

- Considere un conjunto de datos que tiene una variable de cadena de descripción larga. Puede que esta no sea una característica útil para alimentar directamente a un modelo, por lo que quizás podamos crear una nueva variable para saber si la descripción contiene una palabra determinada. La esperanza para crear esta nueva característica es que tendrá más poder predictivo.

¿Cómo sabemos qué características serán útiles?

- Esto se reduce a la experiencia.

Afortunadamente, existen puntos de partida comunes para muchos conjuntos de datos que revisaremos en este módulo.


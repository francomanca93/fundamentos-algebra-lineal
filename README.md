<div align="center">
  <h1>Fundamentos de Álgebra Lineal con Python</h1>
</div>

<div align="center"> 
  <img src="readme_img/algebra-lineal-python.png" width="">
</div>

# Introducción al documento

El contenido de este documento son **apuntes teoricos** del [Curso de Fundamentos de Álgebra Lineal con Python](https://platzi.com/clases/algebra-lineal/) y busca ser una guía para futuros trabajos personales. El mismo está dictado por [Sebastián Sosa](https://github.com/ssosa), co-founder en [Caburé](https://cabure.com.ar/).

El contenido esta basado en el [Capítulo 2 de Algebra Lineal](http://www.deeplearningbook.org/contents/linear_algebra.html) del libro de [Deep Learning](http://www.deeplearningbook.org/) by [Ian Goodfellow](https://en.wikipedia.org/wiki/Ian_Goodfellow), [Yoshua Bengio](https://es.wikipedia.org/wiki/Yoshua_Bengio) and [Aaron Courville](https://aaroncourville.wordpress.com/)


# Objetivos del documento

- Conocer los elementos básicos de matematicas para poder hacer todas las construcciones dentro de álgebra lineal. Todo esto a su vez se utilizan para algoritmos Machine Learning, algoritmos Deep Learning y analisis de datos.


## Tabla de contenido
- [Conceptos básicos de Álgebra Lineal y configuración del entorno de trabajo](#Conceptos-básicos-de-Álgebra-Lineal-y-configuración-del-entorno-de-trabajo)
- [Realiza operaciones básicas](#Realiza-operaciones-básicas)
- [Operaciones con Matrices](#Operaciones-con-Matrices)
- [Sistema de ecuaciones lineales](#Sistema-de-ecuaciones-lineales)
- [Normas](#Normas)
- [Matrices y vectores especiales](#Matrices-y-vectores-especiales)
- [Otras funciones de Algebra Lineal](#Otras-funciones-de-Algebra-Lineal)

El contenido de cada sección se encuentra en notebooks que se van realizando en el curso.
### Conceptos básicos de Álgebra Lineal y configuración del entorno de trabajo

[Notebook del contenido](https://github.com/francomanca93/fundamentos-algebra-lineal/blob/master/1_Conceptos_b%C3%A1sicos_y_configuraci%C3%B3n.ipynb)

En el contenido de la siguiente sección se vio la presentación del curso y la necesidad del Algebra Lineal para entender los algoritmos de Machine Learning y Deep Learning. 

Utiizar Anaconda + Python, crear un entorno de trabajo y actualizar paquetes. En mi caso estaré utilizando Google Colab.

El uso de Jupyter Notebook, similar a Google Colab, que está basado en Jupyter. 

Para finalizar se ven las bases del algebra lineal. Estos son los escalares, vectores, matrices y tensores. 

### Realiza operaciones básicas
[Notebook del contenido](https://github.com/francomanca93/fundamentos-algebra-lineal/blob/master/2_Operaciones_b%C3%A1sicas.ipynb)

En el contenido de la siguiente sección se realizan operaciones básicas con escalares, matrices, vectores y tensores, todo con python y aplicando la librería numpy. 

Se ven las obtener y ver las dimensiones de los elementos bases, que es la transposición, la suma de escalares, vectores y matrices. Para finalizar es hacen operaciones de vectores y matrices de diferentes dimensiones, broadcasting. 

### Operaciones con Matrices
[Notebook del contenido](https://github.com/francomanca93/fundamentos-algebra-lineal/blob/operaciones-matriciales/3_Operaciones_con_Matrices.ipynb)

En el contenido de la siguiente sección realizan operaciones matriciales. Se vio el producto interno o **producto escalar** entre una matriz y un vector, entre matrices. 

Tambien se vieron las **propiedades del producto escalar** entre matrices. Las mismas son **conmutativa**, **asociativa** y **distributiva**. Luego de las propiedades se ve el concepto de **transposición**.

Luegos de entender el producto escalar y propiedades, se estudian los **sistemas de ecuaciones lineales**. Para poder resolver un sistema se deben entender ciertas matrices especiales, estas son las matrices **identidad**, **inversa**, **singular**. 

Se finaliza el módulo entendiendo y aplicando la **inversa de una matriz para resolver un sistema de ecuaciones lineales**.

### Sistema de ecuaciones lineales

[Notebook del contenido](https://github.com/francomanca93/fundamentos-algebra-lineal/blob/sistemas-ecuaciones/4_Sistema_de_ecuaciones_lineales.ipynb)

En el contenido de la siguiente sección se estudian sistemas de ecuaciones , **sobre determinados, determinados e indeterminados**. Todos los sistemas con ejemplo gráficos.

Se continua con conceptos de vectores y se crea una [función en un notebook separado para graficar vectores](https://github.com/francomanca93/fundamentos-algebra-lineal/blob/sistemas-ecuaciones/graficar_vectores.ipynb). Y en el notebook principal se aprende como importar modulos creados en otros notebooks. 

La siguiente sección se estudia el concepto de **combinación lineal**, cual es el concepto y como se representa gráficamente. Se estudian **espacios** y **subespacios (hiperplano)**. Se estudia como se pueden crear planos **unidimensionales, bidimensionales y tridimensionales** con combinaciones lineales de vectores. 

Se finaliza con un concepto muy importante en algebra lineal que son los **vectores linealmente independientes**. Se estudia como se pueden identificar con funciones en numpy y con estos conceptos **poder validar que una matriz tenga inversa**. 


### Normas
### Matrices y vectores especiales
### Otras funciones de Algebra Lineal
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
- [El determinante y la traza](#El-determinante-y-la-traza)

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

[Notebook del contenido](https://github.com/francomanca93/fundamentos-algebra-lineal/blob/norma/5_Normas.ipynb)

En el contenido de la siguiente sección  se estudia **qué es una norma y para qué se usa,** las **propiedades** de esta y se estudia gráficamente la segunda propiedad, que es la **desigualdad triangular**. 

Tambien se estudian los **tipos de normas**. Las normas se representan con la letra **L** y se estudian las **normas L0, L1, L2, L2² y Linfinito** y su importancia en machine learning. 

Se finaliza con el estudio del **producto interno como función de una norma y su visualización**. Se estudia la importancia de el **coseno similitud entre dos vectores** en Machine Learning y como se puede utilizar para relacionar dos textos representados como vectores numéricos.

### Matrices y vectores especiales

[Notebook del contenido](https://github.com/francomanca93/fundamentos-algebra-lineal/blob/especiales/6_Matrices_y_vectores_especiales.ipynb)

En el contenido de la siguiente sección se estudia **matrices y vectores especiales**. Entre estos vemos la **matriz diagonal** y la **matriz simétrica** y las **propiedades** de ambas.

Para finalizar la sección vemos **vectores ortogonales, matrices ortogonales y sus propiedades**. 


### El determinante y la traza

[Notebook del contenido](https://github.com/francomanca93/fundamentos-algebra-lineal/blob/especiales/7_El_determinante_y_la_traza.ipynb)

El contenido de la siguiente sección se estudian dos funciones imporantes. Ellas son la **traza** y el **determinante**. 

La **traza** función nos va devolver siempre el mismo número, independientemente del sistema de referencia que utiilcemos para representar a nuestra matriz.

El **determinante** de una matriz es un número que nos dice en que proporción a transformado el espacio resultante de los vectores unitarios.
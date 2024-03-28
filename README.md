# <center>**Informe: Descripción de lo aprendido**
#### Nombres: Felipe Villarroel y Josias Pinilla
#### Profesor: Victor Poblete
#### Ayudante: Esteban Vargas
#### Asignatura: Procesamiento digital de señales, ACUS099
#### Fecha: 27/03/2024
## Indice:
+ Introducción
+ Definición de un entorno virtual
+ Instalación de software
+ Trabajo en terminal
+ Utilización de Jupyter Notebook
+ Señales: Continuas y discreta
+ Transformada de Fourier
## Introducción
#### Dentro del curso ACUS0991, se han aprendido diversos temas relacionados con la creación y manejo de entornos virtuales, instalación de software esencial para el desarrollo de proyectos, así como la utilización de herramientas como Jupyter Notebook y Markdown. A continuación, se detallará lo aprendido a lo largo de la asignatura.
## Definición de entorno virtual
#### Un entorno virtual es un ambiente aislado y específico para un proyecto determinado, cuyo fin es que dichos proyectos no interfieran con el sistema operativo principal. Al utilizar un entorno virtual, se puede garantizar la reproducibilidad y portabilidad del proyecto.
## Instalación de software
#### La clase del dia 13 de marzo se realizó, en el edificio 14k de la Universidad Austral de Chile (el siguiente link nos entrega información sobre este edificio: [Articulo sobre edificio 14K](https://diario.uach.cl/14k-el-nuevo-centro-de-innovacion-emprendimiento-y-tecnologia-de-la-universidad-austral-de-chile/) ), las instalaciones de los software que utilizaremos en clases, los cuales son: *Git, Visual Studio Code, Pythom, Conda y Jupyter Notebook.*
#### Las instalaciones se realizaron exitosamente gracias a Diego Espejo y Esteban Vargas. 
## Trabajo en terminal
#### En primer lugar, se entró a la terminal en donde se verificó si las instaciones de Conda y Git fueron exitosas, con los códigos "**conda --version**" y "**git --version**" respectivamente. Luego, creamos un entorno virtual llamado "acus099" con el codigo "**conda create -n acus099**" y se activó con el codigo "**conda activate**". Posteriormente, se instalaron versiones adecuadas de Pythom y Jupyter Notebook. Para finalizar, se creó una carpeta para guardar los avances, proyectos y trabajos del curso realizados en Jupyter Notebook, los cuales se pueden abrir desde la terminal con el codigo "**cd *enlace de carpeta*>jupyter notebook**"
## Utilización de Jupyter Notebook
#### Se entró al cuadernillo y analizamos algunas capacidades de Jupyter (*File, Edit, View, Run, Kernel, Settings, Help*). En el tipo de celda se seleccionó "Markdown", en donde se vieron la creación de titulos y subtitulos(*#*), puntos de índice (*+*), ecuaciones (*$$*), letra cursiva (*), letra en negrita (**) y hipervinculo ([Nombre de hipervinculo](link de hipervinculo)).
## Señales: Continuas y Discretas
### Continuas
#### Señal que está definida para todos los valores de tiempo dentro de un intervalo dado. La señal se define para cada punto en el tiempo y puede tomar cualquier valor dentro de un rango continuo, su amplitud varia de forma continua en el tiempo. Se puede representar por una función matemática que está definida para todos los valores de tiempo en un intervalo continuo.
### Discretas
#### El tiempo y la amplitud se discretiza (conversion de continuo a discreta), se toman muestras de la señal continua en intervalos regulares de tiempo y asignar un valor discreto a cada muestra, es un tipo de señal que está definida únicamente en puntos específicos en el tiempo o en la amplitud. Se escribe como x[n] y surge de un muestreo que se hace en el tiempo.
## Transformada de Fourier 
### Transformada de Fourier continua
#### Se aplica a señales continuas en el tiempo, su funcion es transformar un f(t) a una funcion dependiente de una frecuencia angular, se denota como F(w). En la transformada se encuentra una exponencial compleja que representa las oscilaciones armonicas en el tiempo.
#### Su formula consiste de una integral que va desde el infinto negativo al positivo, multiplicado por la función original en el dominio del tiempo y la función exponencial compleja que oscila a una frecuencia angular.
### Transformada de Fourier inversa continua
#### Esta explica que teniendo la Tranformada de Fourier directa, podemos obtener la funcion original en el dominio del tiempo, pasar de F(w) a f(t).
#### Matematicamente hablando se calcula multiplicando 1/2π por una integral que va desde el infinito negativo al positivo, multiplicando la transformada de fourier directa (funcion en dominio de la frecuencia) y la exponencial en frecuencia angular.
### Transformada de Fourier discreta
#### Transforma una secuencia discreta x[n] en una secuencia de frecuencia X[k], k es el indice de frecuencia discreta.
#### Se calcula obteniendo la sumatoria que se realiza sobre todos los valores de n desde 0 hasta N-1 (N es la longitud de la secuencia discreta), multiplicado por la secuencia original en el dominio del tiempo discreto x[n] y la función exponencial compleja que oscila a una frecuencia discreta. 
## hola felipe
## adios josias
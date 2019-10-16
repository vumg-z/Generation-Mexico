
<h1 align="center">
  JAVA
</h1>

<h4 align="center"> Todo lo aprendido en  <a href="https://mexico.generation.org/" target="_blank"> Generation </a> sobre Java.</h4>

## Tabla de Contenido

### JAVA

- [Fundamentos](#fundamentos)
  - [La maquina virtual de Java](#lamaquinavirtualdejava)

- [POO](#poo)
  - [Pilares](#Pilares de la programacion orientada a objetos)

- [Ejercicios](#ejercicios)
  - [Bubble Sort](#bubblesort)
  - [Binary Search](#binarysearch)
  - [Sequential Search](#secuentialsearch)

- [Recursos](#recursos)

## Fundamentos 

    Java es un lenguaje plenamente orientado a objetos, y para escribir el programa más simple 
    hemos de definir una clase. Los tipos básicos de datos son similares, pero los arrays son distintos, 
    y las cadenas de caracteres en Java son objetos de la clase String.
    
 ### La maquina virtual de Java
 
     La Máquina Virtual Java (JVM) es el entorno en el que se ejecutan los programas Java, 
     su misión principal es la de   garantizar la portabilidad de las aplicaciones Java. 
     Define esencialmente un ordenador abstracto y especifica las instrucciones (bytecodes) 
     que este ordenador puede ejecutar. El intérprete Java específico ejecuta las instrucciones 
     que se guardan en los archivos cuya extensión es .class. Las tareas principales de la JVM son las siguientes:
     
    - Reservar espacio en memoria para los objetos creados
    - Liberar la memoria no usada (garbage collection).
    - Asignar variables a registros y pilas
    - Llamar al sistema huésped para ciertas funciones, como los accesos a los dispositivos
    - Vigilar el cumplimiento de las normas de seguridad de las aplicaciones Java
    
    Esta última tarea, es una de las más importantes que realiza la JVM. Además, las propias 
    especificaciones del lenguaje Java contribuyen extraordinariamente a este objetivo: 
    
    - Las referencias a arrays son verificadas en el momento de la ejecución del programa
    - No hay manera de manipular de forma directa los punteros
    - La JVM gestiona automáticamente el uso de la memoria, de modo que no queden huecos.
    - No se permiten realizar ciertas conversiones (casting) entre distintos tipos de datos.

    
- [aprende mas aqui](http://www.sc.ehu.es/sbweb/fisica/cursoJava/fundamentos/introduccion/indice_intro.htm)

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## POO
    La poo surgio de la necesidad de simular sistemas de forma sencilla. 

    La idea basica consiste en simuar conceptos que son fundamentales en el 
    pensamiento humano. 

    Esta organizacion se basa en el tipo de cosas o tipos de objetos con lo ques 
    que convivimos diariamente.
    
<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

### Pilares de la programacion orientada a objetos

#### Herencia: 

    Es el pilar más fuerte que asegura la reutilización de código, ya que a partir 
    de esta característica es posible reutilizar (heredar) las características y 
    comportamientos de una clase superior llamada clase padre, a sus clases hijas, 
    denominadas clases derivadas. 
    
    Esto implica que una vez desarrollado el código de una clase base, su código puede 
    ser reutilizado por las clases derivadas.

#### Abstraccion: 

    Es el proceso mental de transformar el mundo real a un modelo en programacion orientada 
    a objetos.

#### Encapsulamiento:

    El conjunto de tecnicas que nos permiten ocultar la implementacion de nuestra aplicacion.
    Para que un objeto solamente tenga acceso a lo que le importa.
            
#### Polimorfismo
                
    Es el mecanismo por el cual un objeto puede contestar al mismo mensaje de diferentes maneras.

## Ejercicios

Todos mis ejercicios los puedes encontrar en [este repositorio](https://github.com/UrielMendozaG/Java)

### Bubble Sort

    La Ordenación de burbuja (Bubble Sort en inglés) es un sencillo algoritmo de ordenamiento. 
    Funciona revisando cada elemento de la lista que va a ser ordenada con el siguiente, 
    intercambiándolos de posición si están en el orden equivocado

  [Ejemplo aqui](https://github.com/UrielMendozaG/Bubble-Sort)
  
### Sequential search

    La búsqueda secuencial es un método para encontrar un 
    valor objetivo dentro de una lista.Ésta comprueba secuencialmente cada elemento de la lista 
    para el valor objetivo hasta que es encontrado o hasta que todos los elementos hayan sido comparados.

  [Ejemplo aqui](https://github.com/UrielMendozaG/Sequential-Search)
  
### Binary Search

    En ciencias de la computación y matemáticas, la búsqueda binaria, también conocida como búsqueda 
    de intervalo medio o  búsqueda logarítmica, es un algoritmo de búsqueda que encuentra la posición 
    de un valor en un array ordenado.
    
    Compara el valor con el elemento en el medio del array, si no son iguales, la mitad en la cual el 
    valor no puede estar es eliminada y la búsqueda continúa en la mitad restante hasta que el valor 
    se encuentre. 
    
   [Ejemplo aqui](https://github.com/UrielMendozaG/Binary-Search)
   
<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Recursos

- [Aprender Java](http://www.sc.ehu.es/sbweb/fisica/cursoJava/fundamentos/fundamentos.htm)
- [Practica Java](https://codegym.cc/)

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Quiero seguir aprendiendo

[Generation](https://mexico.generation.org/) Impulsa tu carrera profesional

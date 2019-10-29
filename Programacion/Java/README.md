<h1 align="center">
  Java
</h1>

<h4 align="center"> Todo lo aprendido en  <a href="https://mexico.generation.org/" target="_blank"> Generation </a> sobre Java.</h4>

## Tabla de Contenido

### Java

- [Fundamentos](#fundamentos)
  - [La maquina virtual de Java](#la-maquina-virtual-de-java)
  - [Tipos de datos primitivos](#tipos-de-datos-primitivos)

- [POO](#poo)
  - [Pilares](#Pilares-de-la-programacion-orientada-a-objetos)

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


### Tipos de datos primitivos

   
| Tipo | Descripcion |
| ----- | ---- |
| boolean | Tiene dos valores true o false |
| char | Caracteres Unicode de 16 bits  Los caracteres alfa-numéricos son los mismos que los ASCII con el bit alto puesto a 0. El intervalo de valores va desde 0 hasta 65535 (valores de 16-bits sin signo).   |
| byte |  	Tamaño 8 bits.  El intervalo de valores va desde -27 hasta 27 -1 (-128 a 127)  |
| short | Tamaño 16 bits.  El intervalo de valores va desde -215 hasta 215-1 (-32768 a 32767) |
| int | Tamaño 32 bits.  El intervalo de valores va desde -231 hasta 231-1 (-2147483648 a 2147483647)  |
| long | Tamaño 64 bits. El intervalo de valores va desde -263 hasta  263-1 (-9223372036854775808 a 9223372036854775807)  |
| float |  	Tamaño 32 bits. Números en coma flotante de simple precisión. Estándar IEEE 754-1985  (de 1.40239846e–45f a 3.40282347e+38f)  |
| double |  	Tamaño 64 bits. Números en coma flotante de doble precisión. Estándar IEEE 754-1985. (de 4.94065645841246544e–324d  a 1.7976931348623157e+308d.) |

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

## Recursos

- [Aprender Java](http://www.sc.ehu.es/sbweb/fisica/cursoJava/fundamentos/fundamentos.htm)
- [Practica Java](https://codegym.cc/)

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Quiero seguir aprendiendo

[Generation](https://mexico.generation.org/) Impulsa tu carrera profesional

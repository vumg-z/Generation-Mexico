<h1 align="center">
  Java
</h1>

<h4 align="center"> Todo lo aprendido en  <a href="https://mexico.generation.org/" target="_blank"> Generation </a> sobre Java.</h4>

## Tabla de Contenido

### Java

- [Fundamentos](#fundamentos)
  - [La maquina virtual de Java](#la-maquina-virtual-de-java)
  - [Tipos de datos primitivos](#tipos-de-datos-primitivos)
  - [POO](#Pilares-de-la-programacion-orientada-a-objetos)
  - [Modificadores de Acceso](#modificadores-de-acceso)
  - [POJO](#que-es-un-pojo)
  - [¿Que es una interfaz?](#que-es-una-interfaz)
  - [Ciclo de vida desarrollo de software](#ciclo-de-vida-del-desarrollo-de-software)

 - [MVC](#que-es-una-arquitectura)
    - [Qué es un patron de diseño](#qué-es-un-patron)
    - [Qué es el patron MVC](#qué-es-el-patrón-mvc)
    - [Ventajas del MVC](#ventajas-del-mvc)
    - [Partes del MVC](#de-qué-partes-se-compone-el-patron-mvc)
      - [Modelo](#modelo)
        - [Java Beans](#java-beans)
      - [Vista](#vista)
        - [JSP](#jsp)
        - [Ciclo de vida de un JSP](#ciclo-de-vida-de-un-jsp)
      - [Controlador](#controlador)
        - [Servlet](#que-es-un-servlet)
        - [Ciclo de vida de un Servlet](#ciclo-de-vida-de-un-servlet)
        
    - [Cual es la diferencia entre un JSP y un Servlet](#cual-es-la-diferencia-enre-un-jsp-y-un-servlet)
   
  
  
- [Ejercicios](https://github.com/UrielMendozaG/Java)

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
    
### Modificadores de acceso 

     Los modificadores de acceso, como su nombre indica, determinan desde qué clases se puede acceder a un 
     determinado elemento. En Java tenemos 4 tipos: public , private , protected y el tipo por defecto, que 
     no tiene ninguna palabra clave asociada, pero se suele conocer como default o package-private.
     
### ¿Que es un POJO?

    Plain Old Java Object
    
### ¿Que es una interfaz?

    Es una especie de contrato que especifica que tenemos que utilizar 
    
### ¿Cual es la diferencia entre abstract y interface?

    
### Ciclo de vida del desarrollo de software


### ¿Que es una arquitectura? 

    Estructura o forma en que algo está ordenado, dispuesto o construido.
    
### ¿Qué es un patron? 
    
    Un patrón de diseño es una descripción de clases y objetos comunicándose entre sí adaptada para resolver 
    un problema de diseño general en un contexto particular.
    
    Son formas “estandarizadas” de resolver problemas comunes de diseño en el desarrollo de software.
    
    Los patrones de diseño son la base para la búsqueda de soluciones a problemas comunes en el desarrollo 
    de software y otros ámbitos referentes al diseño de interacción o interfaces.
    
    Estos básicamente son  modelos muestra que sirven como guía para que los programadores trabajen sobre ellos.
    
    Un patrón de diseño es una manera de resolver un problema.
    
### ¿Qué es el patrón MVC?

    El MVC o Modelo-Vista-Controlador es un patrón de arquitectura de software que, utilizando 3 componentes 
    (Vistas, Models y  Controladores) separa la lógica de la aplicación de la lógica de la vista en una aplicación.
    
### ¿De qué partes se compone el patron MVC?

#### Modelo

    Es el componente central del patrón. 
    Expresa el comportamiento de la aplicación en términos del dominio del problema, independientemente de la 
    interfaz de usuario.
    Gestiona directamente los datos, la lógica y las reglas de la aplicación.
    
#### Vista

    Se encarga de la representación de salida de información.  
    Se encarga de implementar la respuesta.
    Son posibles múltiples vistas de la misma información.
    
#### Controlador

    Acepta las peticiones del cliente y la convierte en comandos para el modelo o la vista.
    Genera la respuesta para el cliente.
    
#### Ventajas del MVC

- Al incorporar el modelo de arquitectura MVC las piezas de un programa se pueden construir por separado y 
luego unirlas en tiempo de ejecución

- La separación de capas en presentación, lógica de negocio y acceso a datos.

- El costo de mantenimiento del sistema disminuye ya que la una modificación en una capa no debe afectar a las demás.

- Incrementa la reutilización y flexibilidad.

- En cualquier momento en que los datos del modelo cambien, el modelo le notifica a la vista que depende de él.

#### ¿Que es un servlet?

    Los Servlets son módulos escritos en Java que se utilizan en un servidor, estos atenderán las peticiones 
    (requests) según el método HTTP de la misma y generarán las respuesta para el cliente (response).
    
    Su principal misión será orquestar/controlar qué hacer según las peticiones del usuario.
    
    Los servlets usarán los modelos (beans) y redirigirán hacia una vista (JSP) para generar el HTML.
    
#### Ciclo de vida de un servlet

    	  - init
	  - service
	  - destroy

#### ¿Java Beans?

    Los modelos serán Java Beans, clases simples Java que representen los modelos.
    El controlador podrá acceder a estos modelos instanciándolos y usando sus métodos.
    
#### ¿Que es JSP?

    Java ServerPages:
    Las vistas serán implementadas usando páginas JSP.
    Contendrán código HTML con fragmentos de código Java.
    El controlador se encargará de redirigir hacia una vista determinada según la petición del usuario.
    Es parecido a PHP. 
    Se usa una etiqueta especial <%  %>

#### Ciclo de vida de un JSP

	  - compilacion
	  - inicializacion
	  - ejecucion
	  - limpieza
    
#### ¿Cual es la diferencia enre un JSP y un Servlet?

- Servlet es html en java, mientras que JSP es java en HTML.
- Los servlet corren mas rapido que los JSP.
- En MVC, JSP es la vista, mientras que Servlet es el controlador.


    
## Recursos

- [Aprender Java](http://www.sc.ehu.es/sbweb/fisica/cursoJava/fundamentos/fundamentos.htm)
- [Practica Java](https://codegym.cc/)

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>

## Quiero seguir aprendiendo

- [Difference between servlets and jsp](https://www.quora.com/What-is-the-difference-between-Java-servlets-and-JSP)

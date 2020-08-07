# Proyecto: Implementación de una pantalla LCD.
## *INTRODUCCIÓN*
A lo largo de la carrera de Mecatrónica se han observado diferentes asignaturas que son fundamentales, entre ellas está la programación y los circuitos eléctricos. Existen diferentes formas de relacionar estas dos asignaturas donde se realiza un programa para poder controlar diferentes actuadores y sensores, esto a través del programa Visuino que nos permitirá desarrollar de mejor manera el funcionamiento de una pantalla LCD y a su vez un sensor de temperatura.
# Objetivo general
- Diseñar un circuito electrónico que permita visualizar el funcionamiento de una pantalla LCD con ayuda de una placa de Arduino y el software Visuino para relacionar conocimientos de programación y de circuitos.
# Objetivos específico
- Comprender el funcionamiento de Visuino para facilitar la parte de programación en el desarrollo del proyecto.
- Realizar un control adecuado de una pantalla LCD y sensor de temperatura.
- Ampliar conocimientos sobre el control de la placa Arduino.
## *LISTA DE COMPONENTES:*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Arduino |
| 1  | Sensor de temperatura |
|  1 | Potenciómetro  |
|  1 | Pantalla LCD  |
|  - | Cables macho y hembra  |

## *MARCO TEÓRICO*

Una de las principales herramientas que permiten la relación sinérgica entre hardware y software es Arduino, que es una plataforma de creación electrónica de código abierto que consiste en una placa que dispone de elementos necesarios para conectar entradas y salidas de un microcontrolador.¿Qué es un microcontrolador? un microcontrolador es un circuito integrado en el cual se puede almacenar un código de programación con las instrucciones que hacen interactuar a la placa de una manera creativa.

La interfaz de salida de arduino permite procesar la información que ha llegado al Arduino para que esta se reproduzca en un otra placa que en este caso, será una pantalla LCD. 

En el proyecto también será usado el software *Visuino*, que es un programa el cual nos facilita el ámbito de programación en el Arduino ya que únicamente lo que tendremos que hacer es realizar correctamente las conexiones, ya que todo está basado en una serie de diagramas y pines que una vez terminado, nos permite obtener el código de programación. es decir el programa nos ahorra toda la parte de programación para posterior a esto grabarlo en el Arduino.

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Visuino.jpg)

Figura 1. Visuino

Este programa tiene diferentes partes importantes que serán descritas a continuación.

- Panel de navegación y barra de herramientas.

En esta parte podemos encontrar una variedad de herramientas útiles que nos facilitarán la interacción con la plataforma, además hay un panel de navegación en el cual podemos desplazarnos con facilidad alrededor de todo el programa.

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/1.jpeg)

- Panel de propiedades
Este apartado nos permite cambiar cada propiedad de cada componente, modificar valores iniciales y configurar cada opción de cada elemento que agreguemos en nuestro circuito.

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/2.jpeg)

- Panel principal

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/3.jpeg)

Aquí tenemos varias opciones entre las cuales está el soporte de ayuda, también se puede observar que existe una vista de panel virtual, al igual que un graficador de alcance. Por último se tiene lo que corresponde a las librerías y las diferentes plataformas que están cargadas en el software para ser usadas.


![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/4.jpeg)

Fig. Panel virtual y graficador de alcance.


![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/5.jpeg)
Fig. Plataformas y librerías.

- Componentes

Podemos observar los diferentes componentes que podemos usar en visuino, entre los cuales están sensores, actuadores, controles remoto, display, etc.

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/6.jpeg)

- Campo de trabajo y diferentes soportes de Arduino.

Ésta es la parte principal en la cual se desarrollará todo el programa, unicamente para añadir componente lo que tendremos que hacer es arrastrar a estar parte cualquier componente y se nos desplegará en forma de diagrama y lo único que tendremos que hacer es configurar los componentes y conectar los pines.

También se tiene diferentes soportes para placas Arduino, de esta forma podemos elegir según el microcontrolador que poseamos.

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/7.jpeg)

A continuación serán descritos algunos componentes que se usarán en el circuito.

- Pantalla LCD:
O por sus siglas en inglés "Liquid Cristal Display", es una pantalla que usa una  sustancia líquida que está atrapada en dos placas, de manera que la corriente que para por una zona específica permite que esta se vuelva opaca y que se pueda visualizar diferentes tipos de caracteres a través del control de los pixeles.

- Sensor de temperatura: 
Es un sensor, como lo dice su nombre, el cual no necesita ningún circuito demás para que sea usado, que necesita únicamente de 5 voltios para funcionar, es capaz de medir la temperatura en un rango de -55°C y 150°C. Este sensor convierte el voltaje que se le proporciona en temperatura a razón de 10mV por cada grado centígrado. Por ejemplo si medimos 20mV en la salida, lo que en realidad se medirá son 2°C.

- Potenciómetro: 
Es un componente que tiene resistencia variable, es decir nosotros podemos modificar el valor de la resistencia. En el caso de nuestro circuito, servirá para regular el contraste de la pantalla LCD.

## *PROCEDIMIENTO*

1. Abrimos el programa Visuino y elegimos la placa de Arduino con la que se trabajará.

2. Seleccionamos el display LCD y lo arrastramos al campo de trabajo, luego damos doble click para agregar dos elementos.

3. Ahora modificamos los parámetros iniciales en el panel de propiedades, para que se pueda visualizar el texto en la pantalla LCD, es necesario tomar en consideración el tamaño del mensaje.

4. Se agrega un nuevo elementos para que por medio de desplegar la lectura del pin analógico nos de el valor del sensor de temperatura.

5. Verificamos que los valores de cada elemento sean los correctos.

6. Realizamos la conexión de los pines que se utilizarán en el display que se conectarán directamente a los pines de la placa arduino.

7. Usamos una función llamada snapshot para hacer la lectura analógica y conectamos directamente con el pin analógico donde se tomará el valor de la temperatura.

8. Para que se active la función snapshot agregamos la función generadora de pulsos y la configuramos en un intervalo de 3 y lo conectamos.

9. Envíamos el programa a Arduino para exportar el código.

10. Armamos el circuito y cargamos el código en la placa arduino.

## *DIAGRAMA*

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Diagrama%20circuito%20en%20Visuino.png)

Figura 3. Diagrama del circuito en visuino

Como se observa lo primero que tenemos es nuestra placa de Arduino UNO, luego de esto se agrega el componente de la pantalla LCD y agregamos 3 componentes. Seguido de esto se cambia el valor inicial a cada componente: el primer componente incluirá el texto que corresponde a la primera línea con los caracteres "BUEN DIA!"; el segundo componente correspode a la palabra que se imprimirá en la segunda línea que será "TEMP:"; el último componente corresponde al valor que se imprimirá del sensor de temperatura donde seleccionaremos la columna en la cual se imprimirá la temperatura.


## *EXPLICACIÓN DEL CIRCUITO*

Los pines de la pantalla LCD funcionan de la siguiente manera:

Tenemos conectado el pin GND que va a negativo, el VCC es el que se encarga de suministrar voltaje a la pantalla, se conecta su repectiva resistencia para prevenir que se queme la misma. El pin RS se encarga de controlar las ordenes enviadas a la pantalla , mientras que RW realiza la escritura en la pantalla y está conectado a tierra, luego tenemos al pin E, que permite que la pantalla reciba inofrmación que será escrita posteriormente. Se usan los pines D4 a D7 para escribir el mensaje, que son los suficientes para la pantalla de 8 bits y por último tenemos los pines A y K, donde A es conectado a la fuente de voltaje Y K está conectado a tierra.

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Diagrama%20de%20circuito.png)

Figura 4. Funcionamiento de pantalla LCD con sensor de temperatura. Simulado en TinkerCAD.

## *RESULTADOS DE APRENDIZAJE*

Gracias al desarrollo de este circuito con una pantalla LCD se conoció mejor el funcionamiento de este componente, también se han mejorado habilidades en el desarrollo de un circuito mediante Visuino, que son el tipo de programas que ayudan a los desarrolladores de hardware que no tienen  mucho conocimiento en lo que corresponde al desarrollo de software, además de que nos ahorra el esfuerzo de crear un código, traduciendo todo a una serie de pines y diagramas.


## *CONCLUSIONES*
 
 - Se ha logrado proyectar la temperatura ambiente mediante el control de una pantalla LCD , todo esto con la ayuda de la plataforma VISUINO, que nos ha ahorrado la parte de programación dentro de la plataforma Arduino.
 
 - El proyecto que se realizó nos ayudó a comprender de mejor manera como funciona una pantalla LCD, al igual que el software Visuino, donde se manejó un entorno de programación netamente visual.
 
 - Se han encontrado las ventajas de usar la herramienta Visuino en las placas Arduino, esta plataforma en realidad incorpora muchas cosas positivas que ha permitido ir más rápido en la creación del programa.


## *RECOMENDACIONES*

- Es necesario tener conocimientos precios sobre circuitos elécricos para llevar a cabo un buen funcionamiento en el proyecto.

- Tener en cuenta la funcionalidad de cada pin de la pantalla, para poder faciliar el control del mismo.

- Realizar una previa revisión en los componentes que se han añadido en Visuino, ya que un error puede interferir y posterior a esto que no se vea nada proyectado en la pantalla.


## *BIBLIOGRAFÍA*


Visuino. Disponible en línea en: https://www.visuino.com/ 

Arduino para todos. Disponible en línea en: http://arduparatodos.blogspot.com/2016/11/usando-pantalla-lcd-16x2-con-arduino.html

Hardware libre. Diponible en línea en: https://www.hwlibre.com/visuino-una-herramienta-de-programacion-para-los-creadores-de-hardware/

## *ANEXOS*

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Componentes%20del%20circuito.png)

Figura 5. Componentes del circuito.

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Programa%20compilado.png)

Figura 6. Correcta compilación del programa.



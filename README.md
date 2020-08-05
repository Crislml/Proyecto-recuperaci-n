# Proyecto de recuperación
## *INTRODUCCIÓN*
A lo largo de la asignatura, se han visto una variedad de métodos para la resolución de circuitos eléctricos, sin embargo es frecuente encontrarnos con circuitos realmente complejos, los cuales suelen ser muy complicados resolver con las técnicas aprendidas anteriormente, es por esta razón que surge la necesidad de comprender el teorema de Thévenin, que resume un circuito, cualquiera que sea, en un circuito básico con un resistencia y un voltaje. Antes de hacer uso de este método será necesario validar este teorema a través de la práctica mediante su respectiva comprobación experimental.
## *OBJETIVOS:*
# Objetivo general
- Diseñar un circuito electrico mediante la simulación en laboratorios virtuales para comprobar la validez del teorema de Thévenin

# Objetivos específico



## *LISTA DE COMPONENTES:*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Arduino |
| 1  | Sensor de temperatura |
|  1 | Potenciómetro  |
|  1 | Pantalla LCD  |
|  9 | Cables macho y hembra  |

## *MARCO TEÓRICO*

![alt text](
https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Visuino.jpg)

Figura 1. Visuino



## *PROCEDIMIENTO*


## *DIAGRAMA*

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Diagrama%20circuito%20en%20Visuino.png)

Figura 3. Diagrama del circuito en visuino

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Funcionamiento%20pantalla%20LCD.png)

Figura 4. Funcionamiento de pantalla LCD con sensor de temperatura.


## *EXPLICACIÓN DEL CIRCUITO*

Para nuestra práctica, tenemos un circuito el cual está conformado por dos fuentes de voltaje, y 5 resistencias. Los valores de las fuentes de voltaje son de 12 V y de 2V, las resistencias son de 560, 4700, 330, 100 y 1000 ohmios, esta última será tomada como nuestra resistencia que la vamos a excluir para sacar nuestra resistencia y nuestro voltaje Thevenin. La corriente desde nuestra fuente de voltaje de 12 V, hasta nuestra resistencia de 560 ohmios. De esta resistencia saldrá una resistencia de 4700 ohmios, la cual se conectara su otro extremo con el polo negativo de la primera fuente, Y también de la resistencia de 560 ohmios, estará conectado con el polo negativo de la segunda fuente de voltaje que es de 2 V. Des nuestra segunda fuente de voltaje, saldrán dos resistencias, la primera que será de 330 ohmios y que se conectara con el polo negativo de nuestra primera fuente de voltaje, y la segunda resistencia que es de 100 ohmios, que estará conectada en serie con nuestra resistencia de 1000 ohmios, la cual terminara en el polo negativo de nuestra primera fuente de voltaje.

Para realizar nuestros voltajes en Thevenin vamos a realizar lo siguiente. Para nuestra resistencia en Thevenin, excluimos la resistencia de 1000 ohmios, dejando el sistema abierto en ese punto, y convirtiendo las fuentes de voltaje en cortocircuitos. Sacamos una resistencia equivalente y esta será nuestra resistencia Thevenin. Para nuestro voltaje Thevenin conectaremos las fuentes de voltaje, y conservaremos nuestra resistencia de 1000 ohmios abierto, realizamos el análisis como tenemos en anexos, y ya tendremos nuestro voltaje en thevenin.



## *RESULTADOS DE APRENDIZAJE*




## *CONCLUSIONES*



## *RECOMENDACIONES*



## *CRONOGRAMA*

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Cronograma.jpeg)

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.
https://www.visuino.com/ 
http://arduparatodos.blogspot.com/2016/11/usando-pantalla-lcd-16x2-con-arduino.html

## *ANEXOS*

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Componentes%20del%20circuito.png)

Figura 5. Componentes del circuito.

![alt text](https://github.com/Crislml/Proyecto-recuperaci-n/blob/master/Img/Programa%20compilado.png)

Figura 6. Correcta compilación del programa.



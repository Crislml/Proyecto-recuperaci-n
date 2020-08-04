# Proyecto de recuperación
Programación en arduino para controlar un LCD
# Práctica 5
## *INTRODUCCIÓN*
A lo largo de la asignatura, se han visto una variedad de métodos para la resolución de circuitos eléctricos, sin embargo es frecuente encontrarnos con circuitos realmente complejos, los cuales suelen ser muy complicados resolver con las técnicas aprendidas anteriormente, es por esta razón que surge la necesidad de comprender el teorema de Thévenin, que resume un circuito, cualquiera que sea, en un circuito básico con un resistencia y un voltaje. Antes de hacer uso de este método será necesario validar este teorema a través de la práctica mediante su respectiva comprobación experimental.
## *OBJETIVOS:*
# Objetivo general
- Diseñar un circuito electrico mediante la simulación en laboratorios virtuales para comprobar la validez del teorema de Thévenin

# Objetivos específico
- Comprender la metodología del teorema de Thévenin para reafirmar los conocimientos previamente adquiridos.
- Analizar los resultados teóricos con los prácticos mediante la comparación de los mismos para la obtención de porcentajes de error respectivos.


## *LISTA DE MATERIALES:*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 2  | Fuente de voltaje de C.D. |
| 2  | Multímetros digitales |
|  1 | Resistor de 560  |
|  1 | Resistor de 4.7k  |
|  1 | Resistor de 330  |
|  1 | Resistor de 100 |
|  1 | Resistor de 1k  |
|  1 | Potenciómetro de precisión de 1k|
|  1 | Protoboard      |

## *MARCO TEÓRICO*
El teorema de Thévenin nos dice  que cualquier red de corriente lineal de dos terminales puede ser reemplazada por un circuito equivalente que contiene un voltaje y una resistencia equivalente en serie.

Entonces tenemos que si una resistencia está enlazada a un circuito entre los puntos A y B y reemplazamos el circuito por el otro equivalente entonces en la resistencia va a recorrer la misma intensidad.

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Diagrama%201.png)

Figura 1. Diagrama del teorema de Thévenin

El valor de la fuente del circuito resultante se denomina tensión de Thévenin y se consigue resolviendo la tensión del circuito entre A y B sin tomar en cuenta la resistencia entonces lo que produce esto es un circuito abierto.

Entonces, ahora el valor de la resistencia resultante  en serie se denomina resistencia de Thévenin y se calcula como si existiera una resistencia en los puntos A y B sin tomar en cuenta el valor de la resistencia y poniendo en cortocircuito a todas las fuentes de voltaje

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Diagrama%202.png)

Figura 2. Ejemplo del teorema de Thévenin



## *PROCEDIMIENTO*
1. Prepare el laboratorio virtual de su preferencia y arme el circuito que se muestra en la figura

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Diagrama%203.png)

Figura 3.  Circuito para comprobar el Teorema de Thévenin.
  
2. Con el circuito sin ningún tipo de modificación, mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor
medido en la tabla.

4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla.

5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla.


## *DIAGRAMA*

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Circuito_Original.png)

Figura 3. Circuito propuesto simulado en TinkerCAD.

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Circuito_Thevening.png)

Figura 4. Implementación del circuito de Thévenin.


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

## *ANEXOS*

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Voltaje_Corriente_Original.png)

Figura 5. Medición de voltaje y corriente en el circuito original.

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Voltaje_Corriente_Thevening.png)

Figura 6. Medición de voltaje y corriente en el circuito de Thévenin.

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Resistencia_Thevening.png)

Figura 7. Medición de resistencia en el circuito de Thévenin.

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Hoja_Calculos.jpg)

Figura 8. Cálculo de datos teóricos.

![alt text](https://github.com/Kevi7k/Practica5/blob/master/Im%C3%A1genes/Calculo_Error.jpeg)

Figura 9. Cálculo de errores.

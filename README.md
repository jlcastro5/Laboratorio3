# Informe Laboratorio 3
1. OBJETIVOS 

   Objetivo general
   * Analizar y comprobar de forma teorica y experimental veracidad que tienen las leyes de kirchhoff con respecto a los voltajes y corrientes de un circuito electrico, esto se llevara a cabo mediante el desarrollo del presente laboratorio  que abordará el tema “Análisis de nodos”  de un circuito eléctrico mixto planteado por el tutor de la asignatura, cabe recalcar que el presente circuito ya ha sido resuelto mediante el analisis de mallas, por lo que se espera los mismos resultados a la practica anterior, para dicho desarrollo, se utilizara simuladores virtuales de circuitos eléctricos los cuales brindaran oportunidad de corroborar la exactitud de los datos teóricos obtenidos.


   Objetivos específicos
     * conocer el comportamiento de la corriente dentro de diferentes nodos y como estas interactúan con los componentes que integran dichos nodos.
     
     * Identificar que tipo de nodos pueden presentarse dentro de un circuito electrico y determinar los nodos principales y nodo referencial.    
     
     * Comprender el uso de la ley de Kirchhoff y como aplicarlo dentro de un circuito mixto utilizando simuladores virtuales que permitan su corroboración o en su defecto permita la localización de fallas.
 
     *Identificar las diferencias obtenidas por medio de la ejecución de un circuito mixto, dichas respuestas serán obtenidas de manera teórica, experimental y de simuladores.


2. MARCO TEORICO

![](https://github.com/jlcastro5/Laboratorio3/blob/a33e1f34601b8068744b9030d64e3b3c137a83ab/MARCO.jpeg)
  
3. EXPLICACION DEL PROCEDIMIENTO

En este laboratorio realizaremos el analisis de nodos del siguiente circuito con sus respectivos componentes y fuentes de alimentacion como se muestra en la **Figura 1**.

![](https://github.com/jlcastro5/Laboratorio3/blob/2583bb8c7cf2447178f3fe92a5beaa3b86df9ab2/CIRCUITO.PNG)

*Figura 1. Circuito*

Luego representamos dicho circuito en tinkercad con sus respecivos componentes y fuentes de voltajes para luego realizar un analisis y medicione con el multimetro para encontrar su voltaje en los nodos respectivamente.
![](https://github.com/jlcastro5/Laboratorio3/blob/bda69e80fc8ed5a16bb9a66295868715f7d66fdd/PROTOBOAR.PNG)

*Figura 2. Circuito en Tinkercad*

Para realizar el circuito esquematico utilizamos el software de proteus para insertar los componetes respectivamente lo cual esta representando en la **Figura 3**.

![](https://github.com/jlcastro5/Laboratorio3/blob/bda69e80fc8ed5a16bb9a66295868715f7d66fdd/CIRCUITO1.PNG)

*Figura 3. Circuito en proteus*

4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

Realizamos los calculos y el proceso adecuado para aplicar el analisis de nodos y obtener los valores de cada simulador y representacion del circuito como se muestra en la **Figura 4 **.

![](https://github.com/jlcastro5/Laboratorio3/blob/c59425cac38cbc9931c7dffa830e76d706603858/TABLA.PNG)

*Figura 4. tabla de datos*

Una vez analizado en circuito, observamos los nodos principales y nodo de referencia el cual es el que contiene mas componentes el cual en la figura 5, representamos con colores diferentes los nodos y las corrientes que sales de cada nodo que en este caso les llamamos nodo 1 y nodo 2 los cuales contendra V1 Y V2.

![](https://github.com/jlcastro5/Laboratorio3/blob/c59425cac38cbc9931c7dffa830e76d706603858/InkedCIRCUITO_LI.jpg)

*Figura 5. Diagrama y representacion de nodos y corrientes de salidas*

Una vez representado las corrientes realizamos el proceso para encontrar las corrientes en este caso aplicamos la ley de ohm la cual es I = V/R, la cual hacemos la observacion cada corriente y obteniendo sus voltajes.

![](https://github.com/jlcastro5/Laboratorio3/blob/c59425cac38cbc9931c7dffa830e76d706603858/SUMATORIA_I.PNG)

*Figura 6. Ley de Kichhoff*

Ahora, en la figura 7, realizamos el proceso mencionado anteriormente y obtemos los siguientes datos.

![](https://github.com/jlcastro5/Laboratorio3/blob/c59425cac38cbc9931c7dffa830e76d706603858/NODO1.PNG)

*Figura 7. Analisis del nodo 1*

Luego vamos analizar el nodo 2 el cual el proceso de la figura 8, representa las corrientes con sus respectivo voltaje y resistencia.

![](https://github.com/jlcastro5/Laboratorio3/blob/c59425cac38cbc9931c7dffa830e76d706603858/NODO2.PNG)

*Figura 8. Analisis del nodo 2*

Despues de realizar dichos procesos obtenemos el siguiente sistema de ecuaciones, el cual realizaremos el proceso en un software matematico para encontrar sus valores el cual utilizamos la calculadora symbolab de la figura 10, el cual realiza el proceso y obtenemos los valores de X y Y los vuales son V1 y V2, entonces una vez obtenido analiticamente los voltajes en los nodos 1 y 2 de la figura 11, y en cada simulador para comprobar los datos ingresados en la tabla.

![](https://github.com/jlcastro5/Laboratorio3/blob/c59425cac38cbc9931c7dffa830e76d706603858/SISTEMAECUACIONES.PNG)

*Figura 9. Sistema de ecuaciones*

![](https://github.com/jlcastro5/Laboratorio3/blob/c59425cac38cbc9931c7dffa830e76d706603858/RESOLUCION.PNG)

*Figura 10. Proceso matematico en calculadora Symbolab*

![](https://github.com/jlcastro5/Laboratorio3/blob/c59425cac38cbc9931c7dffa830e76d706603858/VOLTAJES.PNG)

*Figura 11. Valores de los voltajes*

La manera de comprobar el voltaje de los nodos conectamos el multimetro en el nodo y el otro extremo en el punto de referencia y asi sucesivamente realizamos con el otro nodo el cual en la figura 12 comprobamos los valores calculador y el software de proteus de la misma manera nos lanza los valores obtenidos y comprobamos el proceso correcto mediante el analisis de nodos.

![](https://github.com/jlcastro5/Laboratorio3/blob/10811ca2ee871415c8862a3750c8cc1a82533ed0/NODOSTOTAL.PNG)

*Figura 12. Medicion en tinkercad*

![](https://github.com/jlcastro5/Laboratorio3/blob/10811ca2ee871415c8862a3750c8cc1a82533ed0/MEDICIONES.PNG)

*Figura 13. Mediciones en Proteus*


5. VIDEO

 

6. CONCLUSIONES

     *Las leyes de Kirchhoff han permitido obtener resultados muy exactos entre los datos obtenidos mediante el desarrollo teórico y la simulación, mismos que fueron recopilados desde tinkercad y proteus. Considerando que los elementos son ideales, podemos concluir que los datos obtenidos en este circuito eléctrico a partir del análisis de nodos son precisos por lo que el método es muy fiable para resolver este tipo de circuitos eléctricos.


7. BIBLIOGRAFÍA 

   Latam, M. (2020, 6 julio). Leyes de Kirchhoff. Mecatrónica LATAM. https://www.mecatronicalatam.com/es/tutoriales/teoria/leyes-de-kirchhoff/
   
   Floyd,T. L. (2007). Principios de circuitos electricos. Mexico: Octava Edicion.
 

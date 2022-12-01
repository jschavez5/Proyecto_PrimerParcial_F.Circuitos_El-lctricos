# Proyecto_PrimerParcial_F.Circuitos_Eléctricos
Elaboración del proyecto del primer parcial para la materia de Fundamentos de Circuitos Eléctricos - Universidad de las Fuerzas Armadas 
## Integrantes 
- Josué Chávez 
- Doménica Espín 
- Henry León 
## Objetivo de la Práctica 
Implementar un circuito experimental-funcional para medir el nivel de agua de acuerdo a los conocimientos previos obtenidos en el curso. 
## Objetivos Específicos
- Armar experimentalmente el circuito analizado
- Entender el funcionamiento interno del propotipo de acuerdo a conceptos teóricos 
## Marco Teórico 
![image](https://user-images.githubusercontent.com/116780907/205073017-20be8508-15cc-4a01-b664-050b62904ea1.png)
## Material o Equipo 
![image](https://user-images.githubusercontent.com/116780907/205080757-e83d65a5-1def-4547-9dac-93f33b6d24e5.png)
![image](https://user-images.githubusercontent.com/116780907/205109801-34266172-5925-49fc-b329-e4b1eda1ecba.png)

## Procedimiento 
1. Como primer punto, se coloca los transistores en la protoborad, conociendo que la primera patita corresponde al emisor, la segunda  a la base y la tercera el colector, ocupando de tal manera, tres filas respectivamente, procurando que la parte plana del transistor esté de frente a uno. 
![image](https://user-images.githubusercontent.com/116780907/205109968-009a90a8-224c-4da0-bfc6-b361f9adfbe6.png)
   
2. Realizamos la conexión a tierra para cada transistor, conectando un cable desde la fila correspondiente a la primera patita (emisor), hasta el terminal negativo de la protoborad. 
![image](https://user-images.githubusercontent.com/116780907/205110081-94e83138-af3e-4aa6-8587-7853e7aad88a.png)


3. Se coloca un resistor de 510 ohms para cada transistor, esto se realiza colocando un terminal a la fila correspondiente a la tercera patita (colector) hacia el otro lado del canal central. 
![image](https://user-images.githubusercontent.com/116780907/205110182-21c4b372-7f11-4ef7-8d2f-0d1445d5da95.png)



4. Se coloca los diodos led al circuito, esto se lo realiza  conociendo que la patita más larga corresponde al positivo y la más corta al negativo, por lo cuál, la positiva irá a la terminal positiva de la protoboard  y la negativa a la fila correspondiente de los resistores de 510 ohms. 
![image](https://user-images.githubusercontent.com/116780907/205110241-9b732f10-f5b9-4a97-8983-648150f8236a.png)



5. Se coloca un resistor de 1000 ohms desde el terminal positivo hacia el otro lado del canal central, esto se lo hace desde cualquier fila del circuito armado, procurando establecerlo al principio del mismo. 
![image](https://user-images.githubusercontent.com/116780907/205110358-78f6dce8-95c8-4b8d-aa79-a2c72aa2a6b5.png)

6. Se realiza conexiones dede la fila correspondiente a la base de cada transistor con los cables, sin unirlos a otra parte del circuito. 
![image](https://user-images.githubusercontent.com/116780907/205110442-704e3015-2302-4fdb-afc1-96eb2b9133a0.png)

7. Se conecta la fuente de 9V de manera paralela hacie los terminales de la protoboard. 
![image](https://user-images.githubusercontent.com/116780907/205110509-8f63c9fc-7e40-47a7-a05a-cc392dcad14d.png)

8. Juntandos todos los cables, procurando que la conexión incial al resistor de 1000 ohms esté primero, luego colocamos las conexiones de los transistores de forma de escalera, esto para darle la función de medir el nivel del agua. 

![image](https://user-images.githubusercontent.com/116780907/205110571-1a2c96d9-8909-4991-a878-5178e8c9f961.png)

## Explicación de Funcionamiento 
El circuito armado cuenta con tres focos led, cada uno de estos con su transistor y resistencia respectivamente. Las resistencias cumplen el rol de proteger a los elementos del circuito regulando la cantidad de voltaje. Los transistores cumplen la función de captar la más mínima cantidad de voltaje (0.7 V) para su funcionameinto, mientras que los cables proporcionan las conexiones necesarias con la fuente de voltaje. 
El circuito se lo deja abierto ya que, el agua contenidad dentro del vaso tomará el papel de puente de conexión faltante para cerrar el circuito. Cada cable ubicado en forma de escalera, según el agua va llegando al nivel de su terminal, este conectará una nueva trayectoria, es decir, el agua cierra la trayectoria, la cantidad mínima de voltaje establecida entre el agua y el cable es suficiente para activar el transitor, el cuál por consiguiente, encenderá el led respectivo, esto sucede co cada una de las trayectorias establecidas. 
https://drive.google.com/file/d/1oQBkYPtqfFidfG0vcneTLmQTncwcKaPl/view?usp=sharing



Diagrama del Circuito 
![image](https://user-images.githubusercontent.com/116780907/205099279-feb7d646-9867-4444-a7e8-dc5e9f1044c9.png)
Nota. Medidor de nivel de agua [Fotografía], por Electricidad y Electrónica, 2020,https://n9.cl/hk4ac

## Video 
https://youtu.be/xAQPxcydkIY
## Conclusiones 

- El transistor 2N3904 es un transistor de conmutación rápida, es decir, puede trabajar con frecuencias elevadas, corta apague y baja tensión de saturación, y es apto para comunicación y amplificación.
- El led en nuestro circuito funciona como señalización para los niveles de agua el cual como vemos, acorde sube el nivel de agua empiezan a encenderse en el orden en el que se dispusieron.
- El transistor 2N3904 funciona a bajas intensidades, bajas potencias, tensiones medias, y puede operar a velocidades razonablemente altas.
- La resistencia se opone a la corriente que sale de la base transistor 2N3904.
- El emisor del transistor va a la tierra conectado a una resistencia y el colector va conectado al led y a la resistencia para conectarse al polo positivo de la fuente.


# Proyecto_PrimerParcial_F.Circuitos_El-lctricos
Elaboración del proyecto del primer parcial para la materia de Fundamentos de Circuitos Eléctricos - Universidad de las Fuerzas Armadas 
## Integrantes 
- Josué Chávez 
- Doménica Espín 
- Henry León 
## Objetivo de la Práctica 
Implementar un circuito experimental-funcional para medir el nivel de agua de acuerdo a los conocimientos previos obtenidos en el curso. 
## Marco Teórico 
![image](https://user-images.githubusercontent.com/116780907/205073017-20be8508-15cc-4a01-b664-050b62904ea1.png)
## Material o Equipo 
![image](https://user-images.githubusercontent.com/116780907/205080757-e83d65a5-1def-4547-9dac-93f33b6d24e5.png)
![image](https://user-images.githubusercontent.com/116780907/205081197-6b14e1c4-cd94-403b-a418-f07c26a68dbc.png)



## Procedimiento 
1. Como primer punto, colocamos nuestros transistores en la protoborad, conociendo que la primera patita corresponde al emisor, la segunda  a la base y la tercera el colector, ocupando de tal manera, tres filas respectivamente, procurando que la parte plana del transistor esté de frente a nosotros. 
   
2. Realizamos la conexión a tierra para cada transistor, conectando un cable desde la fila correspondiente a la primera patita (emisor), hasta el terminal negativo de la protoborad. 
   
3. Colacamos un resistor de 510 ohms para cada transistor, esto lo realizamos colocando un terminal a la fila correspondiente a la tercera patita (colector) hacia el otro lado del canal central. 

4. Colocamos nuestros focos led al circuito, esto lo realizamos conociendo que la patita más larga corresponde al positivo y la más corta al negativo, por lo cuál, la positiva irá a la terminal positiva de la protoboard  y la negativa a la fila correspondiente de los resistores de 510 ohms. 

5. Colocamos un resistor de 1000 ohms desde el terminal positivo hacia el otro lado del canal central, esto lo hacemos desde cualquier fila del circuito armad, procurando establecerlo al principio del mismo. 
6. Realizamos conexiones dede la fila correspondiente a la base de cada transistor con los cables, sin unirlos a otra parte del circuito. 
7. Conectamos nuestra fuente de 9V de manera paralela hacie los terminales de la protoboard. 
8. Juntamos todos los cables, procurando que la conexión incial al resistor de 1000 ohms esté primero, luego colocamos las conexiones de los transistores de forma de escalera, esto para darle la función de medir el nivel del agua. 

## Explicación de Funcionamiento 
El circuito armado cuenta con tres focos led, cada uno de estos con su transistor y resistencia respectivamente. Las resistencias cumplen el rol de proteger a los elementos del circuito regulando la cantidad de voltaje. Los transistores cumplen la función de captar la más mínima cantidad de voltaje (0.7 V) para su funcionameinto, mientras que los cables proporcionan las conexiones necesarias con la fuente de voltaje. 
El circuito se lo deja abierto ya que, el agua contenidad dentro del vaso tomará el papel de puente de conexión faltante para cerrar el circuito. Cada cable ubicado en forma de escalera, según el agua va llegando al nivel de su terminal, este conectará una nueva trayectoria, es decir, el agua cierra la trayectoria, la cantidad mínima de voltaje establecida entre el agua y el cable es suficiente para activar el transitor, el cuál por consiguiente, encenderá el led respectivo, esto sucede co cada una de las trayectorias establecidas. 

Diagrama del Circuito 
![image](https://user-images.githubusercontent.com/116780907/205099279-feb7d646-9867-4444-a7e8-dc5e9f1044c9.png)
Nota. Medidor de nivel de agua [Fotografía], por Electricidad y Electrónica, 2020,https://n9.cl/hk4ac

## Video 
## Conclusiones 


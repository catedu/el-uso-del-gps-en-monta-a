# La triangulación (6 de 31)

![Triangulación de los satélites](./gps_files/Triangulación de los satélites.jpg)El sistema de triangulación funciona de la siguiente manera:

1.  El **receptor GPS** localiza automáticamente como **mínimo tres satélites** de la red
    
2.  De ellos **recibe señal indicando la identificación y la hora** del reloj de cada uno de ellos
    
3.  Con base en estas señales, el aparato **sincroniza el reloj del GPS y calcula el tiempo de viaje de la señal**, al saber en que momento se emite la señal en el satélite y en que momento se recibe en el receptor, **multiplicando este tiempo por la velocidad de la luz hallaremos la distancia entre cada satélite y receptor**.
    
4.  **Cada distancia define una esfera** con centro en el satélite, y **la intersección de 3 esferas nos daría analíticamente la posición** del punto a través de sus 3 coordenadas tridimensionales (X, Y, Z).
    
5.  Debido a la **falta de precisión en el reloj que se encuentra en el receptor necesitamos al menos 4 satelites** para obtener la posición.
    

#### Empareja las siguientes frases:
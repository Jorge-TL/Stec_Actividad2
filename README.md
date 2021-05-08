# Stec_Actividad2
Semana Tec Actividad 2 SNAKE
</br>
Este repositorio cuenta con coommits y branches que fueron creados para realizar lo pedido en la actividad 2.

## Tabla de Contenidos
1. [Información General](#general-info)
2. [Collaboration](#collaboration)

</br>

## Información General
Para esta actividad de snake se nos pidió hacer dos modificaciones al programa brindado, siendo estas el cambiar el color al azar de la serpiente
como su comida al inicio de cada partida, asi como darle movimiento a la comida para complicar la jugabilidad. A continuación se explicara como se 
obtuvieron los objetivos.
</br>
## Colores al azar (Chava27)
Para poder lograr que el color de la serpiente como la comida cambiara para cada partida fue necesario crear una lista llamada col (línea 19), en la cual
se guardaron distintos colores que podían adquirir. En las líneas siguientes (21, 22), se estableció el valro que tendría tanto la serpiente 
como su comida, utilizando la función randrange de random que escoge al azar cualquier valor dentro de la lista col.
</br>
</br>
Una vez especificado los colores que se usarían en esa partida, fue necesario incluirlos dentro de la función de mov(),
siendo más específicos en las líneas 62 y 64.
</br>
## Evitar repetir colores (Jorge-TL)
Al probar el juego para colaborar el funcionamiento de movimiento al azar de la comida nos dimos cuenta que se salían repetir los colores tanto en la comida
como de la serpiente eran iguales y llegaba a ser confuso así que se usó un while que volvían a randomizar el color, en específico de la serpiente, para
que después los colores random se escogieran nuevamente para evitar esa confusión.

## Movimiento al azar (Jorge-TL)
Para que la comida tuviese un movimiento al azar y fuera más complicado, en la parte del movimiento, en la sección de la comida se delimitó él área de juego
y así posteriormente se fue jugando con un random en las posiciones para que se fueran moviendo al azar.

## Collaboration
Chava27 (Salvador Salgado)
</br>
Jorge-TL (Jorge Tamariz)

#Codigo original de cannon.py

# Actividad 4

Este código en Python utiliza la biblioteca Turtle para crear un juego simple donde el jugador controla una bola roja que debe evitar los objetivos azules que se mueven horizontalmente en la pantalla. A continuación, se proporciona una descripción detallada de las funciones y la lógica del juego:


## Funcionalidades

- tap(x, y): Esta función responde al toque en la pantalla y mueve la bola roja a la posición inicial si no está dentro de los límites de la pantalla. Luego ajusta la velocidad de la bola según la posición del toque.
- inside(xy): Esta función devuelve True si la posición xy está dentro de los límites de la pantalla.
- draw(): Dibuja la bola roja y los objetivos azules en la pantalla. La bola se representa como un punto rojo y los objetivos como puntos azules de mayor tamaño.
- move(): Mueve la bola y los objetivos en la pantalla. Genera nuevos objetivos aleatorios y los mueve hacia la izquierda. La bola cae debido a la gravedad simulada. Reajusta los objetivos cuando son alcanzados por la bola o salen de los límites de la pantalla.

## Interacciones
- El juego comienza con la bola en una posición inicial y los objetivos azules se generan aleatoriamente en el lado derecho de la pantalla.
- El jugador puede hacer clic en la pantalla para mover la bola en la dirección deseada y evitar los objetivos.
- La bola cae gradualmente debido a la gravedad simulada.
- El juego continúa hasta que un objetivo azul alcanza el borde izquierdo de la pantalla o la bola sale de los límites de la pantalla.

## Autores
- [@Toromanu2429](https://github.com/ Toromanu2429)

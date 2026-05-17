En una fábrica, un pequeño robot de mantenimiento debe recorrer un tablero recogiendo piezas defectuosas mientras evita las sierras que aparecen durante la partida

El juego se desarrolla por turnos y el objetivo será conseguir recoger las piezas, terminará si consigue el numero de piezas que se piden o si es destruido por una sierra.

La fábrica estará representada mediante un tablero.
En el podremos tener los siguientes elementos:

- R → Robot del jugador
- P → Pieza
- X → Sierra peligrosa
- . → Espacio vacío

Ejemplo:
```txt
+---+---+---+---+---+
| . | . | P | . | X |
+---+---+---+---+---+
| . | R | . | . | . |
+---+---+---+---+---+
| X | . | . | P | . |
+---+---+---+---+---+
| . | . | X | . | . |
+---+---+---+---+---+
```

El robot empezará en una posicion aleatoria del tablero.

Cada turno se generarán nuevas piezas con una probabilidad de 20% en cada casilla y un 10% de que aparezca una sierra. También existe un 50% de que en una casilla que hay una sierra está desaparezca.

Una vez se actualice la fabrica, el robot podrá moverse una casilla en los cuatro sentidos.

Tras finalizar cada turno si se encuentra al lado de una sierra *(sin contar diagonales)* será destruido. También es necesario imprimir el tablero por cada turno e indicar el número de piezas obtenidas hasta ahora. 
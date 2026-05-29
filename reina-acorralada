# Ejercicio: La Reina Acorralada

Debes implementar en lenguaje C una simulación de estrategia sobre un tablero bidimensional inspirada en el movimiento de las piezas de ajedrez.

El jugador controlará una reina atrapada dentro de un tablero mientras distintas torres enemigas aparecerán progresivamente intentando eliminarla.
La reina únicamente podrá desplazarse en diagonal, mientras que las torres atacarán en línea recta sobre filas y columnas.

La partida transcurrirá por turnos y el objetivo será sobrevivir el mayor número posible de rondas evitando quedar en la línea de ataque de las torres enemigas.

El programa cumplirá los siguientes requisitos:
- El tablero de juego estará formado por una cuadrícula de “F” filas y “C” columnas.
- Las casillas vacías se representarán mediante el carácter ".".
- La reina del jugador se representará mediante el carácter "Q".
- Las torres enemigas se representarán mediante el carácter "T".

Inicialmente:
- La reina comenzará en una posición del tablero aleatoria usando rand().
- Las torres se generarán aleatoriamente utilizando rand() entre 2 y 5 en una posición aleatoria también.
- Ninguna torre podrá aparecer en la misma posición que la reina.

El juego transcurrirá por turnos. En cada turno:
Se mostrará el tablero actualizado.

El jugador moverá la reina únicamente en diagonal:
> 1 → arriba izquierda

> 2 → arriba derecha

> 3 → abajo izquierda

> 4 → abajo derecha

La reina no podrá salir de los límites del tablero.

Una torre amenaza todas las casillas situadas:
> En su misma fila.

> En su misma columna.

Si al finalizar un turno la reina se encuentra:
> En la misma fila que una torre.

> En la misma columna que una torre.

La partida terminará inmediatamente.

Tras cada turno se mostrará:
- El tablero actualizado.
- El número total de turnos sobrevividos.
- El número de torres existentes en el tablero.
- El programa deberá incluir una función que compruebe si la reina ha sido eliminada.

El programa deberá estar dividido en funciones, por ejemplo:
- Inicializar tablero
- Mostrar tablero
- Mover reina
- Generar torres aleatorias
- Comprobar fin de partida

Ejemplo de tablero
```txt
. . . . . . .
. . . T . . .
. . . . . . .
. . Q . . . .
. . . . T . .
. . . . . . .
. . . . . . .

Torres restantes: 2
```

Ejemplo de final de partida
```txt
. . . . . . .
. . . T . . .
. . . . . . .
. . . Q . . .
. . . . T . .
. . . . . . .
. . . . . . .
GAME OVER
Torres restantes: 2
Turnos sobrevividos: 12
```
# Ejercicio: Carrera de Coches en Circuito

Debes implementar en lenguaje C una simulación de una carrera sobre un circuito rectangular representado mediante una matriz.

El jugador controlará un coche que deberá evitar colisiones mientras avanza por la pista.
En cada turno aparecerán nuevos obstáculos automáticamente.
El objetivo será sobrevivir el mayor número posible de turnos sin chocar.

El programa cumplirá los siguientes requisitos:
- El circuito estará formado por una cuadrícula de “F” filas y “C” columnas.
- Las casillas vacías se representarán mediante ".".
- El coche del jugador se representará mediante "C".
- Los obstáculos se representarán mediante "V".
- Si el coche llegará a chocar se representa mediante "X".

El coche comenzará situado en la última fila del tablero.

En cada turno:

- El tablero se mostrará por pantalla.
- El jugador podrá mover el coche:
> "a" → izquierda
> "d" → derecha
- Los obstáculos avanzarán automáticamente hacia abajo.
- El programa generará nuevos obstáculos aleatorios en la parte superior utilizando rand().
- Si el coche colisiona con un obstáculo, la partida terminará.

El programa deberá incluir funciones para:

- Inicializar tablero
- Mostrar tablero
- Mover coche
- Generar obstáculos
- Actualizar tablero
- Comprobar fin partida

Ejemplo

```txt
. . V . .
. . . . .
. V . . .
. . . V .
. . C . .
```
# Ejercicio: Invasión Espacial

Debes implementar en lenguaje C una simulación de una invasión espacial utilizando un tablero bidimensional.

El jugador controlará una nave situada en la parte inferior del tablero y deberá destruir enemigos antes de que alcancen la base.

El programa cumplirá los siguientes requisitos:
- El tablero estará formado por una matriz de “F” filas y “C” columnas.
- Los elementos del juego serán:
> "A" → nave del jugador

> "V" → enemigo

> "." → espacio vacío

- Los enemigos aparecerán aleatoriamente en la parte superior utilizando rand().

En cada turno:
- Se mostrará el tablero actualizado.
- El jugador podrá:

> Mover la nave a izquierda o derecha.

> Disparar.
- Los enemigos avanzarán automáticamente hacia abajo.
Los disparos avanzarán automáticamente hacia arriba.
- Al disparar eliminará al primer enemigo que se encuentre en la comunna donde se disparó y el jugador sumará un punto.

- La partida finalizará cuando:
> Un enemigo alcance la última fila.

> O el jugador alcance cierta puntuación.

El programa deberá incluir funciones para:
- Inicializar tablero
- Mostrar tablero
- Generar enemigos
- Mover enemigos
- Disparar jugador
- Comprobar fin partida

Ejemplo

```txt
. . V . .
. . . . .
. . . V .
. . . . .
. A . . .

Puntos: 4
```
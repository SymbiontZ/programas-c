# Batalla Naval Simplificada

Debes implementar en lenguaje C una simulación simplificada del juego “Batalla Naval”.

El juego enfrentará al jugador contra el ordenador sobre dos tableros bidimensionales.
Cada participante dispondrá de varios barcos ocultos distribuidos aleatoriamente sobre el mar.

La partida transcurrirá por turnos. En cada turno, el jugador realizará un disparo sobre el tablero enemigo y posteriormente el ordenador realizará un disparo automático sobre el tablero del jugador.

El objetivo será destruir todos los barcos enemigos antes de perder la totalidad de la propia flota.

El programa cumplirá los siguientes requisitos:
1. El tablero de juego consiste en una cuadrícula de “F” filas y “C” columnas.

2. Inicialmente todas las casillas contendrán agua, representada mediante el carácter "-".

3. Los barcos se colocarán aleatoriamente sobre el tablero utilizando rand().

4. Cada barco ocupará una única casilla del tablero y se representará mediante el carácter "B".

5. Los disparos tendrán los siguientes resultados:
> "X" → disparo fallido.
> "H" → barco alcanzado.


El juego transcurre por turnos. En cada turno:
1. Se mostrará el tablero actualizado.

2. El jugador introducirá:
- Fila del disparo.
- Columna del disparo.

3. El programa comprobará si el disparo:
- Ha impactado sobre un barco.
- O ha caído en el agua.

4. Posteriormente, el ordenador realizará un disparo automático sobre una posición aleatoria del tablero del jugador utilizando rand().

5. No podrá dispararse dos veces sobre una misma casilla.

Tras cada turno se mostrará:
- El tablero actualizado.
- El resultado de ambos disparos.
- El número de barcos restantes de cada jugador.

La partida terminará cuando:
- Todos los barcos del jugador hayan sido destruidos.
- O todos los barcos del ordenador hayan sido destruidos.

### Condiciones adicionales:

El programa deberá estar dividido en funciones, por ejemplo:
- Inicializar tablero
- Mostrar tablero
- Generar barcos aleatorios
- Disparo del jugador
- Disparo automático del ordenador
- Comprobar impacto
- Comprobar final de partida

### Ejemplo de tablero

```txt

TABLERO ENEMIGO

~ ~ ~ ~ ~
~ X ~ ~ ~
~ H ~ ~ ~
~ ~ ~ ~ ~
~ ~ ~ X ~

TABLERO JUGADOR

~ ~ B ~ ~
~ ~ ~ ~ ~
X ~ ~ B ~
~ ~ ~ ~ ~
~ H ~ ~ ~

Jugador dispara en posición: (2,3)

Resultado: Agua.

El ordenador dispara en posición: (4,1)

Resultado: Barco alcanzado.

```


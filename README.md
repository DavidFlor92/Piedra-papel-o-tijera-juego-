# Piedra-papel-o-tijera-juego-
Juego Piedra, Papel, Tijera  Este es un juego interactivo de Piedra, Papel, Tijera implementado en Python. Es una excelente demostración de las habilidades de programación y resolución de problemas.
Descripción

Inicio del juego. Cuando se inicia el juego, se muestra un menú con las opciones disponibles: piedra, papel, tijera y salir. El usuario debe seleccionar una opción ingresando el número correspondiente.

Elección del jugador. El jugador elige su movimiento ingresando el número correspondiente a piedra (1), papel (2), tijera (3) o salir (0). Si el jugador ingresa un número no válido, se le pide que intente de nuevo.

Elección de la computadora. La computadora elige su movimiento de manera aleatoria utilizando la función random.choice. Esta función selecciona un elemento al azar de la lista de opciones (piedra, papel, tijera).

Determinación del ganador. Se determina el ganador de la ronda comparando el movimiento del jugador con el de la computador:

Piedra gana a tijera (la piedra rompe la tijera).
Tijera gana a papel (las tijeras cortan el papel).
Papel gana a piedra (el papel envuelve la piedra).
Si ambos jugadores eligen el mismo movimiento, es un empate.
Fin de la ronda. Después de determinar el ganador, se muestra el resultado de la ronda al jugador. Si el jugador ganó, se muestra un mensaje de felicitación. Si la computadora ganó, se muestra un mensaje de aliento para que el jugador lo intente de nuevo. Si fue un empate, se informa al jugador del empate.

Continuación del juego. Después de cada ronda, se le pregunta al jugador si desea seguir jugando. Si el jugador elige seguir jugando, se inicia una nueva ronda. Si el jugador elige salir, el juego termina.
# AUTHOR : DAVID FLOR

# REGLAS DEL JUEGO

# Jugadores: El juego se juega entre dos personas.

# Movimientos: Los jugadores cuentan juntos hasta tres y simultáneamente eligen una de las siguientes array_gameOptiones
# : piedra, papel o tijera12.

# Determinar al ganador: Las reglas para determinar al ganador son las siguientes12:

#Piedra gana a tijera: La piedra rompe la tijera.
#Tijera gana a papel: Las tijeras cortan el papel.
#Papel gana a piedra: El papel envuelve la piedra.
#Si los dos jugadores hacen el mismo signo, no se suma ningún punto y se repite el turno12.
#Fin del juego: El juego puede durar lo que los jugadores quieran, por ejemplo, gana el jugador que llega primero a sumar 10 puntos3.

import random

# Constantes para las array_gameOptiones del juego
PIEDRA = 1
PAPEL = 2
TIJERA = 3
SALIR = 0

# Lista de array_gameOptiones, opciones del juego
array_gameOptiones  = ["", "piedra", "papel", "tijera"]


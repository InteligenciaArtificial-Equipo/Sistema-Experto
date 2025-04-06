# Sistema Experto para Black Jack 21

## Integrantes
#### Chaparro Castillo Christopher
#### Peñuelas López Luis Antonio

## Black Jack 21

### Problema

El Blackjack, aunque en apariencia sencillo, encierra una gran complejidad matemática. 
Las decisiones del jugador impactan directamente en su expectativa de ganancia, y por eso, muchos estudios han derivado en lo que se conoce como estrategia básica, que indica la mejor jugada posible en cada situación.

### Objetivo General

Desarrollar un sistema experto capaz de analizar la situación actual de una partida de Blackjack, considerando la mano del jugador, la carta visible del crupier y la suma total del jugador, para recomendar la mejor acción posible, con base en la estrategia básica del juego y el análisis probabilístico, con el fin de optimizar las decisiones del jugador y reducir la ventaja del casino.

### Objetivos Especificos

 - Diseñar una base de conocimientos que contenga las reglas de la estrategia básica del Blackjack, considerando distintos escenarios de juego (manos duras, suaves y pares).

 - Implementar un motor de inferencia que, a partir de las condiciones observadas en la partida (mano del jugador y carta del crupier), determine la acción más recomendable según la base de conocimientos.

 - Desarrollar una interfaz que permita al usuario ingresar las cartas del jugador y del crupier, y que muestre en tiempo real la recomendación del sistema experto junto con una breve justificación.

### Cómo se juega?

1. **Valor de las cartas**
   - Números del 2 al 10 valen su valor nominal.
   - J, Q y K valen 10.
   - El As vale 1 **o** 11, según convenga al jugador.

2. **El objetivo**
   - Conseguir una mano con un valor total más alto que el del crupier, sin pasarte de 21.
   - Una mano de 21 con solo dos cartas (As + 10/J/Q/K) es un **Blackjack**, que suele pagar 3:2.

3. **Inicio del juego**
   - El jugador recibe dos cartas.
   - El crupier recibe una carta boca arriba y una boca abajo (en algunas variantes solo una carta visible).

4. **Opciones del jugador**
   - **Hit (Pedir)**: Recibir otra carta.
   - **Stand (Plantarse)**: Terminar tu turno y quedarte con tu mano actual.
   - **Double (Doblar)**: Doblar la apuesta y recibir solo una carta más.
   - **Split (Separar pares)**: Si las dos cartas son iguales, puedes dividirlas en dos manos.

5. **El turno del crupier**
   - El crupier revela su segunda carta.
   - Debe pedir cartas hasta tener al menos 17.

6. **Final del juego**
   - Si el jugador se pasa de 21, pierde automáticamente.
   - Si el crupier se pasa, el jugador gana.
   - Si ambos tienen el mismo valor, hay un empate (push).





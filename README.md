Changelog
Se han realizado actualizaciones en la lógica del juego para aumentar la dificultad y dinamismo del entorno. A continuación, se detallan los cambios principales respecto a la versión original:

Nuevas Funcionalidades
- Movimiento Dinámico de la Comida: Se implementó la función move_food(), la cual permite que la comida se desplace un paso a la vez en una dirección aleatoria durante cada ciclo de movimiento de la serpiente.

- Validación de Límites para Objetos: Se integró una validación de coordenadas dentro de move_food() para asegurar que la comida permanezca siempre dentro de los límites del tablero (-200 < x < 190 y -200 < y < 190).
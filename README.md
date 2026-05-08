Changelog
Se han realizado actualizaciones en la lógica del juego para aumentar la dificultad y dinamismo del entorno y en la parte visual para hacer el juego más atractivo. A continuación, se detallan los cambios principales respecto a la versión original:

Nuevas funcionalidades en la lógica
- Movimiento Dinámico de la Comida: Se implementó la función move_food(), la cual permite que la comida se desplace un paso a la vez en una dirección aleatoria durante cada ciclo de movimiento de la serpiente.

- Validación de Límites para Objetos: Se integró una validación de coordenadas dentro de move_food() para asegurar que la comida permanezca siempre dentro de los límites del tablero (-200 < x < 190 y -200 < y < 190).

Modificaciones en la parte visual
- Cambio de color en la comida y serpiente: Se implementó un arreglo de cinco colores(azul, naranja, verde, violeta y turquesa), del cual se escoge de manera aleatoria un color para la serpiente y uno para la comida, los cuales son distintos dada la implementación de un ciclo while que evita el que sean del mismo color ambos objetos. Se realizó esta implementación para que cada vez que se corra el juego, ambos objetos tengan un color distinto al de la partida anterior y el juego se vuelva un poco más atractivo visualmente y no caiga en ser repetitivo.
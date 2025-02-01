# Adivina la Operación - Juego de Matemáticas

Este es un juego simple en Python usando la biblioteca `pygame`. El objetivo del juego es adivinar la operación matemática correcta a partir de un resultado dado. Si el jugador adivina correctamente, gana puntos. Si se equivoca, acumula errores. El juego termina cuando el jugador comete 5 errores.

## Requisitos

- Python 3.x
- Pygame

Puedes instalar Pygame ejecutando el siguiente comando en tu terminal:
pip install pygame


## Cómo jugar

1. Al iniciar el juego, se mostrará un resultado numérico.
2. Se te presentarán 4 opciones con operaciones matemáticas.
3. El objetivo es adivinar qué operación genera ese resultado.
4. Si seleccionas la opción correcta, ganarás un punto.
5. Si seleccionas la opción incorrecta, se contará como un error.
6. Si cometes más de 5 errores, el juego terminará y aparecerá un mensaje indicando que has perdido, con la opción de reiniciar.

## Instrucciones para jugar

1. Ejecuta el juego con el archivo Python.
2. Haz clic en las opciones que crees que son correctas.
3. Si te equivocas más de 5 veces, el juego terminará y podrás reiniciarlo.

## Iniciar el juego

Para jugar el juego, simplemente ejecuta el siguiente comando en tu terminal:
python adivina_la_operacion.py


Asegúrate de tener `pygame` instalado para que funcione correctamente.

## Mejoras posibles

1. **Temporizador**: Agregar un límite de tiempo para cada pregunta podría hacer que el juego sea más desafiante.
2. **Dificultad progresiva**: A medida que el jugador avanza, se podrían introducir números más grandes o operaciones más complejas (como fracciones o exponentes).
3. **Puntuación más detallada**: Mostrar un puntaje acumulado o un sistema de clasificación basado en la cantidad de preguntas contestadas correctamente.
4. **Sonidos**: Agregar efectos de sonido al acertar o equivocarse.
5. **Interfaz gráfica más avanzada**: Mejorar la estética visual del juego con animaciones y transiciones entre preguntas.
6. **Temporizador de juego**: Implementar un temporizador global que limite el tiempo para jugar.
7. **Modos de juego**: Crear diferentes modos, como un modo de "preguntas rápidas" o "modo de supervivencia", donde las preguntas aumentan en dificultad rápidamente.

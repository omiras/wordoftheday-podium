# Podium - La palabra del día

Cierto formador ha decidido poner a disposición de todo aquel que quiera consultarlo, el ranking actualizado del número de veces que cada alumno ha acertado la palabra del día.

El proceso es el siguiente: cada dia se actualiza un [fichero CSV](https://www.youtube.com/watch?v=SaHIUR9jIPY) con la información de los alumnos y sus palabras adivinadas. Se ha creado una API que ofrece esta información para cualquier cliente que quiera consultarla.

En esta [Web](https://score-word-of-the-dat.onrender.com/) podemos encontrar la manera que tenemos para acceder a dicha información

## Requisitos

1. Al hacer click en el botón _Actualizar Podium_ , debemos hacer una peticion GET mediante _fetch_ a la URL adecuada
2. Fíjate bien en el tipo de datos que devuelve la llamada
3. Actualiza el nombre del jugador y las palabras adivinadas en cada nodo del DOM correspondiente. Es decir, el jugador con más punto, tiene que ir en el podio amarillo. Añade los ids que necesites.

## BONUS

1. Crea una lista completa mostrando la relación de palabras adivinadas por cada alumno/a. Puedes hacer una tabla en HTML, que debe contener tantas filas como resultados devuelve la llamada a la API

### Creaciónde la API

Si tienes curiosidad, este es el repo que contiene la creación de la [API](https://github.com/omiras/score-wordoftheday)

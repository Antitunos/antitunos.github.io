---
title: Bot de Discord en JavaScript
description: Creando un bot de Discord sin tener ni puta idea de JavaScript.
date: 2020-01-01 01:01:01 +010000
categories: [IT, frontend]
tags: [javascript, discord, programación, familyguy]
image:
  path: /assets/img/post/discordbot/wasd.png
---

He aquí el primer proyecto que escribo para mi página, el cual es un bot de Discord. 
Me gustaría comentar mi experiencia previa programando, así como mis objetivos con este proyecto:

## ¿Por qué un bot de Discord?
En cuanto a mis conocimientos previos relevantes a este proyecto, sé un poquito de Python y HTML. En mi opinión, Python es medianamente similar a JS, lo que me ayuda a la hora de aprender el nuevo lenguaje de programación.
El año pasado creé un bot de Discord a través del wrapper [Discord.py](https://discordpy.readthedocs.io/en/stable/), pero al final decidí usar el API oficial de Discord por los siguientes motivos:
 - La documentación oficial de Discord es mucho más detallada (aunque hé de decir que la de discord.py también es decente.)
 - Discord.js recibe actualizaciones a la par con el API de Discord, haciendo que este tenga las características mas recientes
 - No conseguí hacer slash commands de una forma satisfactoria con discord.py (quizás una skill issue)

### Objetivos
Para lo que quiero hacer con el bot tengo que aprender los siguientes conceptos:
 1. Aprender JavaScript.
 2. Configuración básica de un bot. Que envíe un input y me devuelva un output.
 3. Trastear con las diferentes cosas que puede hacer el bot. Quizás hacer algún jueguito chorra o lo que sea.
 4. Quiero integrar YouTube y/o Spotify para poder usarlo como bot de música. (no tengo ni la mas menor idea de como empezar a hacer eso)

## Aprendiendo JavaScript
No lo voy a negar, aprender algo nuevo es difícil. Me cuesta mucho sacar la fuerza de voluntad para aprender algo nuevo, sobre todo solo y en mi casa, donde nadie me diría nada si me pasara todo el día viendo videos en la cama. Pero tengo una ventaja que ninguna generación ha tenido antes: el fácil y gratuito acceso a (casi) toda la información del mundo. Soy capaz de buscar y aprender de cualquier tema en el mundo de rápidamente a través de un teléfono o mi ordenador.
En el caso de JS, siendo este el lenguaje de programación más usado de la historia, hay miles de tutoriales que entran en detalle como aprender los conceptos y sintaxis relevantes. De todos ellos, me llaman la atención dos en concreto, pero principalmente voy a seguir uno: [Asabeneth/30-Days-Of-JavaScript](https://github.com/Asabeneh/30-Days-Of-JavaScript/tree/master) en GitHub, y los cursos de JavaScript de [freecodecamp.org](https://www.freecodecamp.org/). La primera opción es mi preferida ya que toma el formato de "libro", y personalmente me ayuda a tomar la información a mi ritmo. Freecodecamp lo usé como respaldo en caso de que necesitara ayuda con un concepto concreto.

### Mis apuntes
DISCLAIMER: Esto no es un tutorial, sino mis apuntes super resumidos de JS. Si quieres ver otra cosa procede con el siguiente punto del post.

#### Añadiendo JS al documento
*JavaScript in-line*
```html
<DOCTYPE html>
<html>
    <head>
        <title>JS en linea</title>
        <meta charset="utf-8">
    </head>
    <body>
            <button onclick="alert('Hello World')">Cuanto es 2 + 2?</button>
    </body>
</html>
```

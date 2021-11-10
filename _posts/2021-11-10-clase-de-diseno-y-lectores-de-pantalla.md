---
layout: post
title: Clase de diseño y lectores de pantalla
subtitle: Aún más accesibilidad
cover-img: /assets/img/wave.JPG
share-img: /assets/img/wave.JPG
tags: [accesibilidad, reflexion, lectores]
---

La última semana dedicada a la **accesibilidad** comenzó con una clase de *Mairo*, la profesora de diseño del Instituto. Fue una charla muy interesante en donde nos dió una serie de consejos sobre *cómo enfocar el porfolio* en cuanto a la sensación que queremos transmitir. Hablamos sobre **tipografía, colores y composición** como los tres pilares sobre los que fijarse a la hora de definir nuestro canvas.

Algo muy importante, y que no había tenido en cuenta, era saber enfocar mi web según el **target**, es decir, si va a ser visualizada por una empresa moderna o por otra más *tradicional*. Este aspecto es fundamental a la hora de entregar nuestros trabajos, pues podemos correr el riesgo de realizar un muy buen trabajo, pero no saber transmitirlo adecuadamente.

La tabla inferior muestra un resumen de en qué aspectos enfocarse según nuestro **público objetivo**. Tratamos también temas relativos a la **jerarquía, el contraste o la ley de tercios**, llegando a la conclusión de que es mejor usar *formas grandes* para lo importante y pequeñas para los mensajes secundarios. En resumen, me resultó una charla muy **instructiva** en donde Mairo me transmitió muchas mejoras para incluirle a mi portfolio.

| EMPRESA SERIA | EMPRESA JUVENIL |
|---|---|
| Imagen de seriedad | Dinámica |
| Profesional | Creativa |
| Claridad | Atrevida |
| Seguridad | Juvenil |

Aunque por *cuestiones de tiempo* no dió tiempo a que se revisara mi trabajo, Susana si que pudo echarle un ojo a mi portfolio y me propuso algunas mejoras interesantes. En concreto mejorar la tipografía y añadir un color a los encabezados de la parte de *la barra lateral*. He intentado usar una paleta de colores lo más clara posible, incluyendo un toque de color verde para destacar ciertos elementos. En cuanto a la tipografía, he usado [Roboto](https://fonts.google.com/specimen/Roboto) en combinación con la cursiva y la negrita según la parte que quiera o no destacar.

![Detalle de portfolio](/assets/img/portf2.JPG){: .mx-auto.d-block :}

En cuanto al contenido, he querido destacar **los proyectos**, tanto personales como laborales, pues considero que un reclutador es lo que querría ver de un desarrollador web: qué herramientas usa, qué lenguajes y las aplicaciones que ha desarrollado. Esto lo acompaño con una **pequeña descripción** del mismo, donde cuento cómo lo he hecho, los problemas que me han surgido y aquellos que he conseguido solucionar.

Todo esto da como resultado (a mi parecer) un portfolio sencillo, que va al grano y que no intenta hacer perder el tiempo al reclutador, pues considero que con la cantidad de CV que reciben es muy dificil que alguien lea al 100% tu curriculum, y al final terminan haciendo una **lectura en diagonal** y de lo más importante de la web.

La siguiente clase de la semana estuvo dedicada a **usar un lector de pantalla y una herramienta sobre accesibilidad**. En nuestro caso usamos [NVDA](https://nvda.es/) que son las siglas de *Non Visual Desktop Access*. Se trata de una herramienta gratuita que permite tener un lector de pantalla en nuestro ordenador. Estuvimos practicando con **diferentes webs** y descubrimos que la mayor parte de los sitios visitados tienen fallos en cuanto a accesibilidad y compatibilidad con *lectores de pantalla*.

En este punto descubrí que existe un narrador en Windows 10 que se muestra usando la combinación de teclas *ctrl + Win + n*. Aunque no tiene grandes opciones y funciona un tanto mal, sirve para tener un acercamiento al tema y, al menos **ya viene preinstalado con el sistema*.

En esta clase también realizamos un ejercicio con una herramienta para testear la accesibilidad. Se realizó un **foro** en la asignatura y cada uno eligió una herramienta para practicar. En mi caso use [Wave](https://wave.webaim.org/), una herramienta que me gustó por su sencillez (y que es totalmente gratis) y que permite auditar webs de una manera muy rápida y visual. Probé con varias páginas (la web del Planes, La del Ayuntamiento de Murcia o la propia del consorcio W3).

![Detalle de la herramienta Wave](/assets/img/wherr.JPG){: .mx-auto.d-block :}

En la imagen superior se puede ver cómo desglosa los resultados la herramnienta. Es muy intuitiva ya que permite acceder a cada elemento de la web desde el menu contextual de la izquierda. De esta manera, podemos situar en la página aquellos **elementos** que dan error, pudiendo ver su código así como un detalle de la propia descripción de la pauta del W3C que incumple, incluyendo consemos sobre cómo mejorarlo. 

Los compañeros también propusieron herramientas muy interesantes que me sirvieron para *tenerlas en cuenta* para cuando audite mis propios proyectos. Las conclusiones del experimento se pueden resumir en las siguientes:

- Es muy difícil cumplir todas las especificaciones.
- Es necesario usar más de una herramienta para auditar una web.
- Todas las webs, sin excepción, tienen fallos.

La última clase de la semana, y con la que cerramos el capítulo sobre **accesibilidad**, la centramos en realizar [test en W3School](https://www.w3schools.com/accessibility/index.php) sobre accesibilidad. Los resultados que conseguí se pueden ver en la imagen inferior.

![Test W3Schools](/assets/img/quizz.JPG){: .mx-auto.d-block :}

La verdad es que saqué en claro varias conclusiones a tener en cuenta, sobre todo en lo relativo a **etiquetas propias de HTML5** específicas para accesibilidad, algunas ya las conocía de otros cursos que he realizado en el pasado, pero las más importantes se pueden resumir en:

- Utilizar etiquetas semánticas como `<section>`, `<aside>` o `<main>`.
- Usar correctamente botones (cuando hacemos acciones) y enlaces (cuando nos llevan a otra página).
- Importancia del atributo `role`.
- Usar correctamente el `aria-label`.
- Usar los atributos de `value`.
- Evitar usar la propiedad CSS `outline: 0` pues quita el foco de los elementos.

Como resumen de la semana, creo que han sido unas clases muy interesantes, sobre todo la charla con Mairo. En general, me están sirviendo mucho las clases prácticas (he disfrutado haciendo el portfolio) e interiorizo mejor los conceptos cuando se trata de **tareas prácticas**. Además, puedo añadir conceptos de otras asignaturas, como **animaciones** de CSS o pequeños scripts de **javascript**. Todo esto da como resultado un ejercicio en el que aplico conceptos transversales de otras asignaturas.

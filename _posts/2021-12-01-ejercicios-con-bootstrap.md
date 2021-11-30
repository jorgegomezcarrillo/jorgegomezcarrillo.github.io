---
layout: post
title: Ejercicios con Bootstrap
subtitle: Proyectos interesantes con el framework
cover-img: /assets/img/strap.png
share-img: /assets/img/strap.png
tags: [reflexion, bootstrap]
---

Arrancamos la semana metiéndonos de lleno con **Boostrap** y realizando un ejercicio planteado por *Susana* en donde debíamos replicar la disposición de una web con este framework. Lo complicado aquí era darse cuenta que dentro de las filas *se podían añadir, a su vez* nuevas columnas. Se convertía, entonces, en una rejilla pero que englobaba dentro otra rejilla. Una imagen vale más que mil palabras, por lo que en la captura inferior se puede ver la resolución de mi ejercicio:

![Ejercicio Bootstrap](/assets/img/rejillas.PNG){: .mx-auto.d-block :}

A este ejercicio le aplicamos también una serie de propiedades (**clases**) de Bootstrap para ir practicando, tales como `background-color`, de esta manera aprendimos a embeber código CSS dentro del HTML. Esto nos sirvió para ahondar más en la documentación del framework, *teniendo que buscar* las clases que nos pedía el ejercicio, como por ejemplo la que necesitábamos para *no mostrar* un elemento de la lista, mediante las clases `d-none` y `d-md-block`. Con todo esto, pudimos comprobar cómo **Boostrap ensucia en código HTML**, quedando al final un HTML plagado de clases de Boostrap, dificultando su *comprensión*. Llegamos a la conclusión de que usar Boostrap está bien, pero siempre es mejor combinarlo con nuestros propios estilos **para darle más personalidad a nuestra página** (hoy en día, como todo el mundo usa este framework, prácticamente toda la web tiene el mismo diseño).

Para complicar un poco más las cosas, se nos propuso un ejercicio más *serio*, en donde teníamos que anidar filas dentro de otras filas, con sus respectivas columnas. Además, teníamos que aplicar varios **layouts** en función de las dimensiones de la página (xs, sm, md y lg según Bootstrap). La [documentación relativa al Grid de Boostrap](https://getbootstrap.com/docs/5.1/layout/grid/) ofrece información muy clara y útil sobre cómo aplicar estas clases. El resultado de mi ejercicio fue el que se puede *apreciar en la imagen inferior*. En un principio lo realicé añadiendo divs para las filas, pero posteriormente **refactoricé** el código, usando los contenedores (`<section>`, `<article>`, etc.) que ya venían con el propio ejercicio. 

![Ejercicio Bootstrap con grid](/assets/img/bot-grid.PNG){: .mx-auto.d-block :}

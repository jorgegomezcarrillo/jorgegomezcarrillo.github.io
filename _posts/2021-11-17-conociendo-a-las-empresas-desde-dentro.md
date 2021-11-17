---
layout: post
title: Conociendo a las empresas desde dentro
subtitle: Cómo trabajan los profesionales
cover-img: /assets/img/met.JPG
share-img: /assets/img/met.JPG
tags: [accesibilidad, reflexion, empresas, diseño]
---

La semana comenzó con una introducción muy interesante al **layout de las páginas web**. Susana nos lo presentó de una manera muy atractiva mediante una web llamada [LearnLayout](https://learnlayout.com/) que, paso a paso, va introduciendo los conceptos más importantes de este sistema. Estuvimos viendo varios ejemplos, así como una recomendación sobre usar *sintaxis semántica* de HTML5 en vez de divs, y por mi parte aprendí bastantes cosas que no sabía.

Los aspectos más interesantes que vimos fueron los relativos al **diseño adaptativo**, o responsive, centrándonos en propiedades como el display (para controlar estructuras), el width o la propiedad *max-width*, muy útil cuando se trata de usar **media queries**. Estas últimas son una serie de reglas que definen cómo se comporta el elemento en función del dispositivo, algo muy interesante hoy en día y que hemos comentado en varios post anteriores por medio del concepto **mobile first*.

![Diseño responsive](/assets/img/respon.PNG){: .mx-auto.d-block :}

Al final de esta clase realizamos un ejercicio muy interesante para empezar a aplicar las *media queries*. Consistió en representar un cuadrado y cambiar sus propiedades en función de las dimensiones de pantalla. En la imagen superior se puede ver un pantallazo de uno de los casos para cuando la pantalla tiene menos de 600px de ancho. Aunque fácil al principio, me costó entender cómo funcionaban las propiedades *max y min width/height*, ya que te obliga a repensar toda la web. Me pareció un ejercicio muy interesante y me ha servido para ir con algo aprendido de cara a los futuros ejercicios tanto para esta asignatura como para **lenguaje de marcas**.

Algo curioso de esta prueba fue el hecho de tener que usar una media query para *imprimir la página*. Este ejercicio tenía truco, ya que para que se visualice correctamente el fondo del cuadrado es necesario activar la opción *Gráficos de fondo*, que se encuentra en las **opciones avanzadas** dentro de la pantalla de impresión. Desconocía totalmente este funcionamiento ya que nunca había tenido que imprimir una web (quizá cuando iba al instituto y usábamos módems antiguos, pero no lo recuerdo bien). Esto ocurre porque el navegador dispone de unos **estilos predeterminados** que le aplica a la web de manera general a menos que los cambiemos. Cada navegador establece los suyos propios y es por eso que existen **reseteadores de estilos**, una suerte de hojas que agregamos a nuestro HTML y que dejan el documento sin ningún valor de CSS. Esto tiene sus ventajas e inconvenientes, siendo uno de estos el tener que *redefinir* cada elemento de la web.

Este tipo de estilos se pueden ver perfectamente en el navegador bajo la pestaña de *Estilos calculados* que está disponible en las herramientas para desarrolladores. En la imagen inferior se pueden ver los estilos que aplica al navegador para un elemento seleccionado. Es muy importante tener esto en cuenta para no *rompernos la cabeza* cuando un determinado elemento no hace lo que queremos o está aplicando un estilo que no sabemos de dónde sale.

![Estilos calculados](/assets/img/comp.PNG){: .mx-auto.d-block :}

## CHARLA CON MARIO PRIETO

Una de las clases más interesantes fue esta, en la que tuvimos la charla de *Mario Prieto* trabajador en la empresa **UST España**, y que enfocó su presentación en el UX/UI. En un primer lugar, se nos presentaron conceptos teóricos sobre esta materia, tales como su definición, metodologías de trabajo y sistemas de diseño y componentización. El final de la charla estuvo enfocado en la visualización de un proyecto que realizó para Santillana, consistente en un **Dashboard** para controlar a los alumnos en un centro de enseñanza.

Lo que me pareció más interesante fue el apartado de **metodología**, pues creo que es fundamental a la hora de organizar un gran equipo y cumplir con los plazos establecidos. Me hubiera gustado preguntarle cuánto tiempo pasa desde que surge la concepción de la idea hasta que se lanza el producto final, pero esta ha sido una pregunta que se me ha ocurrido *a posteriori*. No obstante, nos dejó dos conceptos interesantes sobre metodologías:

- **Design Thinking**. Enfocado a un análisis más exhaustivo, consistente en varios pasos (INVESTIGACIÓN, DISEÑO y DESARROLLO) y que da lugar a un producto muy trabajado.
- **Design Sprint**. Lo que nos definió como un *Design Thinking pero en modo hackaton*, pues se establece una semana más o menos para acabarlo. Normalmente esta metodología se usa para enfocarse en una tecnología en concreto.

Nos habló de la importancia del **diseño por componentes**, algo que ya hemos visto en esta asignatura y que, sin duda, veremos en las próximas clases con Luismi cuando empecemos a tocar *Angular*. **Spoiler**: en mi caso ya he visto algo al respecto, pues he trasteado con Vue y React. Nos comentó también la existencia de los **UI Kit**, enfocados a englobar en un único lugar la descomposición de todos los elementos que se usan en el proyecto para que los equipos de desarrollo los tengan como *guías* a la hora de programar.

![Diseño atómico](/assets/img/atom.JPG){: .mx-auto.d-block :}

El final de la semana estuvo marcado por el **Kahoot** realizado con las preguntas que cada uno de nosotros propuso sobre la charla de Mario. La mía, como he comentado más arriba, trató sobre uno de los aspectos que más me gustaron de la charla, la metodología. Fue uno de los que mejor me salió, tanto es así que quedé primero y recibí un valioso premio: *un bombón de chocolate*. La verdad es que estuvieron muy interesantes las diversas preguntas de los compañeros, e incluso se produjo un pequeño debate sobre cómo entendiamos las distintas fases/apartados de la metodología Design Thinking.

Mi pregunta para el juego fue la siguiente:

a) El Design Sprint dura, al menos, tres semanas.
b) No son aplicables a UX/UI.
c) **El Design Thinking realiza un análisis más exhaustivo.**
d) Ambas sirven para lo mismo.

![Ejercicio FlexBox](/assets/img/ranas.JPG){: .mx-auto.d-block :}

Por último, realizamos un ejercicio individual sobre el uso de **FlexBox** en donde, mediante esta propiedad de CSS, debíamos posicionar [una rana](https://laboratoria.github.io/flexboxfroggy/) usando las distintas opciones que nos da FlexBox. En la imagen superior se puede ver una captura de cómo **conseguí pasarme el juego** (por desgracia se me olvidó reclamar el premio). Un ejercicio muy interesante, sobre todo el último nivel, que me hizo sudar bastante pues no te daban ningún tipo de ayuda y el posicionamiento de las ranas era bastante complejo.

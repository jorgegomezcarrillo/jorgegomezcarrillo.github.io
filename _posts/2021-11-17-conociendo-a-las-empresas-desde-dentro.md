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

Al final de esta clase realizamos un ejercicio muy interesante para empezar a aplicar las *media queries*. Consistió en representar un cuadrado y cambiar sus propiedades en función de las dimensiones de pantalla. En la imagen superior se puede ver un pantallazo de uno de los casos para cuando la pantalla tiene menos de 600px de ancho. Aunque fácil al principio, me costó entender cómo funcionaban las propiedades *max y min width/height*, ya que te obliga a repensar toda la web. Me pareció un ejercicio muy interesante y me ha servido para ir con algo aprendido de cara a los futuros ejercicios tanto para esta asignatura como para **lenguaje de marcas*.

Algo curioso de esta prueba fue el hecho de tener que usar una media query para *imprimir la página*. Este ejercicio tenía truco, ya que para que se visualice correctamente el fondo del cuadrado es necesario activar la opción *Gráficos de fondo*, que se encuentra en las **opciones avanzadas** dentro de la pantalla de impresión. Desconocía totalmente este funcionamiento ya que nunca había tenido que imprimir una web (quizá cuando iba al instituto y usábamos módems antiguos, pero no lo recuerdo bien). Esto ocurre porque el navegador dispone de unos **estilos predeterminados** que le aplica a la web de manera general a menos que los cambiemos. Cada navegador establece los suyos propios y es por eso que existen **reseteadores de estilos**, una suerte de hojas que agregamos a nuestro HTML y que dejan el documento sin ningún valor de CSS. Esto tiene sus ventajas e inconvenientes, siendo uno de estos el tener que *redefinir* cada elemento de la web.

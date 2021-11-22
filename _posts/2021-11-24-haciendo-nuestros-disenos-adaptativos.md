---
layout: post
title: Haciendo nuestros diseños adaptativos
subtitle: Todo empieza a cobrar sentido
cover-img: /assets/img/adapttt.png
share-img: /assets/img/adapttt.png
tags: [responsive, reflexion, adaptativo]
---

Arrancamos la semana viendo los conceptos **básico de diseño responsive**. La última clase ya dejamos visto por encima alguna de las nuevas metodologías de posicionamiento, *en concreto FlexBox* con el juego de la rana y esta semana Susana nos ha enseñado el por qué del uso de ciertos elementos. En primer lugar, hay que hacer una diferenciación muy sutil entre **diseño adaptativo** y **diseño responsive**. En [esta web](https://www.navarraweb.com/web-responsiva-vs-adaptable-cual-es-la-diferencia/) hacen un análisis bastante claro de la diferencia, que se puede resumir en:

- *Diseño adaptativo*: Usa media queries buscando una mayor flexibilidad. Visualmente no se aprecian tirones.
- *Diseño responsive*: Usa tamaños de pantalla preestablecidos. Se aprecian tirones.

Un aspecto fundamental del diseño responsive (de ahora en adelante no haré distinción al debate entre responsive / adaptativo) es el uso de la **etiqueta meta**: `<meta name="viewport" content="width=device-width, initial-scale=1.0">`. para ello, lo primero es entender el **viewport** de una página que se define, tal y como podemos ver [en este artículo](https://desarrolloweb.com/articulos/etiqueta-meta-viewport.html) como:

> *El viewport en un navegador en cualquier ordenador con sistemas tradicionales es igual al área de la ventana, o mejor dicho, al área disponible para renderizar el documento web.*

Si no usaramos esta etiqueta, el contenido de la página *se reduciría* para ocupar todo el espacio, esto provocaría que el texto fuera ilegible. Podríamos decir que la pantalla está **emulando** el espacio que tiene. Esta etiqueta admite varios parámetros y escalas, aunque lo más habitual es dejarlo como se ha indicado en la línea superior. Hoy en día contamos con varias herramientas que nos permiten *no olvidarnos* de esta línea, por ejemplo, en VSCode al escribir la exclamación hacía abajo (!) y darle a **tabulador**, se nos creará una estructura básica de HTML con esta etiqueta.

![Diseño responsive](/assets/img/viewport.png){: .mx-auto.d-block :}

Esta clase estuvo marcada por un debate que se generó en torno a los **pixeles de las pantallas**. Según los apuntes existen tres tipos de pixeles según a qué nos estemos refiriendo. Esto existe ya que el ordenador tiene que saber diferencia entre los píxeles propios de la pantalla así como los que está usando la vista actual. Se pueden resumir en:

- Hardware Pixel: procedentes de la tarjeta gráfica.
- Device Independent Pixel (DPI): unidad del navegador.
- Devide Pixel Ratio (DPR).

Al final no se sacó nada en claro debido a la complejidad del asunto aunque es importante tener presente que existen así como que debemos de usar la etiqueta meta. Con esto queda en **gran valor el trabajo** de los diseñadores y/o maquetadores que deben lidiar en su día a día con este tipo de menesteres.

Comentamos también el uso de plantillas por parte de [la web de W3Schools](https://www.w3schools.com/w3css/w3css_templates.asp) donde podemos encontrar el código de multitud de ejemplos de páginas web, ya listas para usarlas. Creo que esto es útil a la hora de hacer *prototipos básicos* aunque seguramente tengamos que realizar algo personalizado si queremos escalar a algo más grande. No obstante, si sabemos usar **Bootstrap**, este nos proporciona una serie de media queries ya preestablecidas que nos ahorran incluso más el trabajo.

![Ejemplo plantillas](/assets/img/templ.JPG){: .mx-auto.d-block :}

Por último, para esta clase se realizó un **ejercicio básico en CSS Grid** en donde teníamos que crear una rejilla, colorear sus elementos e incluso ordenarlos según el esquema que nos dió Susana. Un ejercicio muy sencillo pero que me sirvió *para recordar* algunas de las propiedades de esta nueva forma de posicionamiento.

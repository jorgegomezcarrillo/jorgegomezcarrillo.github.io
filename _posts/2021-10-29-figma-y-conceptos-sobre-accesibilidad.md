---
layout: post
title: Figma y conceptos sobre accesibilidad
subtitle: Terminando los prototipos de clase
cover-img: /assets/img/acc.png
share-img: /assets/img/acc.png
tags: [accesibilidad, figma, reflexion]
---

Las clases de esta semana han sido bastante interesantes, pues hemos tocado en más **profundidad el software de Figma**. El primer día lo dedicamos a repasar algunos trucos y atajos de teclado, opciones y formas de trabajar con este programa, algo que me resultó **muy instructivo** para empezar a conocer más a fondo el software. Esto lo hicimos siguiendo los tutoriales en video de **OpenWebinars** para los que tenemos acceso como estudiantes.

Un punto interesante de esta clase es que vimos la instalación de **plugins** creados por la comunidad. Instalamos unos cuantos y probamos su funcionamiento. Algunos de los más interesantes son los que vimos sobre inserción de iconos o uno para comprobar el contraste de nuestros textos. Me resultó muy interesante, ya que desconocía por completo que existía la posibilidad de añadir *funcionalidades extra al programa*, y más en la versión gratuita. Todo esto lo fuimos practicando realizando sencillos ejemplos mientras Susana nos mostraba en video el resultado final.

![Ejemplo de prototipado web](/assets/img/prot.png){: .mx-auto.d-block :}

La siguiente clase la dedicamos a trabajar en profundidad con el programa. Realizamos un ejercicio muy interesante en donde tuvimos que realizar comentarios sobre los ejercicios de los prototipos realizados la semana anterior ([Ver entrada en el Blog](https://jorgegomezcarrillo.github.io/2021-10-20-prototipos-dibujos-a-mano-y-semana-cinco-dias/)) por otros compañeros. De esta manera les aportabamos críticas constructivas sobre sus trabajos, a la vez que recibiamos lo mismo por su parte. Lo bueno de Figma es que permite agregar colaboradores que solo puedan *ver y no editar* el trabajo, lo que hace que el flujo de trabajo para enseñar a otras personas el proyecto sea muy cómodo.

Visto esto, el resto de clase lo dedicamos a **terminar el trabajo** sobre nuestro prototipo empezado la semana pasada. Para ello se nos pidió realizar tres prototipos: baja, media y alta fidelidad, añadiendo para ello lo que consideráramos oportuno. Nosotros (Cintia y yo) continuamos con el proyecto de la pizzería online. Realizamos la vista para cada prototipo, tanto móvil como web y **añadimos animaciones** para que al clickar en un botón te lleve a otra parte de la web. Esta parte nos resultó un poco confusa al principio, pero con un par de tutoriales y muchas pruebas conseguimos lo que queríamos.

![Ejemplo de prototipo en Figma](/assets/img/pizz.JPG){: .mx-auto.d-block :}

En la imagen superior se pueden ver algunas capturas de nuestro proyecto, en concreto de la versión móvil. Nos resultó muy útil todo lo aprendido anteriormente, sobre todo el apartado de **reutilización de componentes**, ya que fue algo que aplicamos constantemente para poder cambiar los estilos de un elemento sin tener que ir uno por uno. También creamos **estilos personalizados** (Primary / Secondary / Light ) para aplicárselo a los distintos elementos de la web y tener clara cuál es nuestra paleta de colores.

En este punto también incluimos los comentarios que nos hicieron nuestros compañeros. En nuestro caso lo que más se repetía es que usábamos **demasiados espacios en blanco** algo que, si bien era intencionado por nuestra parte para darle ese toque de claridad y limpieza. Esto lo modificamos añadiendo alguna funcionalidad extra como indicadores de los métodos de pago en el footer o **mejorando la legibilidad** en los textos para aumentar la fuente o el contraste.

## Qué me ha parecido este ejercicio

Como **conclusion**, de todas las prácticas esta es de las que más me ha gustado. Conocía Figma pero nunca me había puesto con él y es algo que hubiera seguido posponiendo de no ser por este ejercicio. Este software tiene más posibilidades de las que creía y lo que más me sorprende es la cantidad de cosas que se pueden hacer *con la versión gratuita*. Entiendo ahora porque las empresas usan este recurso para sus proyectos, ya que incluso permite visualizar un prototipo del proyecto en una especie de *mockup* interactivo, sobre el que puedes desplazarte simulando el movimiento que haríamos en un móvil físico

## Nociones básicas sobre accesibilidad

En la última clase de la semana realizamos una introducción a los conceptos básicos de la **accesibilidad**. Hicimos un repaso sobre el estandar actual para definir estos principios así como las definiciones básicas tanto de *usabilidad como de accesibilidad*. Podemos definir esta última como:

> *Accesibilidad web: acceso universal a la Web, independientemente del tipo de hardware, software, infraestructura de red, idioma, cultura, localización geográfica y capacidades de los usuarios.*

> *Usabilidad web: facilidad de uso, que los usuarios no requieran conocimientos específicos para la utilización. Sistemas de ayuda.*

En este punto se produjo una charla bastante interesante sobre la accesibilidad, por medio de ejemplos tanto de un alumno del centro que usaba un **lector de pantallas**, como de un video sobre la accesibilidad de la web de *Renfe*. He de decir que conocía estos casos, pues (como he comentado en anteriores entradas) realicé hace unos años un curso del SEF *sobre desarrollo web* donde tratamos este tema.

![Accesibilidad en Renfe](/assets/img/renfe.jpg){: .mx-auto.d-block :}

### Normativa en materia de accesibilidad

Uno de los puntos más conflictivos sobre este asunto es el relativo a la *normativa aplicable*. Hablamos sobre el *Consorcio W3C* capitaneado por [Tim Berners-Lee](https://es.wikipedia.org/wiki/Tim_Berners-Lee), el padre de la web. Este conglomerado de empresas desarrolla normas, estándares web y pautas pero no vela porque se cumplan, **ofrece recomendaciones**. Dentro de esta organización existe el *WAI (Web Accessibility Initiative)*, cuyo objetivo podría resumirse en:

> *Facilitar el acceso de las personas con discapacidad, desarrollando pautas de accesibilidad, mejorando las herramientas para la evaluación y reparación de accesibilidad Web*

Todo esto confluye en una serie de pautas a seguir, las conocidas como las **PAUTAS WCAG**. Estas se basan en cuatro principios y dentro de ellos pautas (doce en total). Dentro de ellas se encuentran los diferentes criterios de conformidad clasificados en tres niveles (A, AA, AAA) siendo el último el más restrictivo. Estos cuatro principios son:

1. Perceptible
2. Operable
3. Comprensible
4. Robusto

Pudimos comprobar en clase como estas pautas resuntan un poco *confusas en su comprensión*, pues están redactadas en un vocabulario que es poco conocido para el usuario medio. Por suerte, disponen tanto de una versión en inglés como en español.

## Todo esto, ¿cómo se aplica?

Como digo, conocía **algunos de los métodos para hacer las webs más accesibles**: atributos alt en las imágenes, tabIndex en HTML para marcarle el recorrido a los lectores de pantalla, etc., pero gracias a esto me ha picado la curiosidad y he investigado un poco sobre el asunto. En inglés, a la accesibilidad web se la conoce como **a11y** (el 11 corresponde a la cantidad de letras que existen entre la *a* y la *y*. Encontré [esta web](https://www.a11yproject.com/) donde, por medio de una lista de chequeo, se puede ver si cumplimos con los criterios de accesibilidad para cada elemento HTML: formularios, botones, encabezados o contrastes, entre otros (ver imagen inferior).

![A11y](/assets/img/table.JPG){: .mx-auto.d-block :}

Otra buena web sobre la que **documentarse** es la de [Mozilla MDN](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML), en donde podemos encontrar información con ejemplos sobre las distintas etiquetas que existe en HTML. Esta web es muy reconocida dentro del mundo del desarrollo, y ya la hemos usado en otras asignaturas, como por ejemplo la de Entorno Cliente. Un punto curioso de este tema es la mala costumbre que tenemos (incluso a veces me sigue pasando) de poner en los enlaces el texto *Pulsa aquí* en donde no le estamos **dando ninguna información al usuario** sobre el contenido del enlace. En la imagen inferior se puede ver un ejemplo sacado de W3Schools sobre una buena y mala práctica. Si le ponemos un *texto descriptivo* al enlace, hacemos que las personas que usan un lector de pantallas sepan a qué contenido acceden.

![Texto en enlaces](/assets/img/glink.JPG){: .mx-auto.d-block :}

En líneas generales, lo aprendido este semana ha sido muy interesante. Aunque conocía estos conceptos sé que es algo que me falta por aplicar en mis proyectos y es un apartado al que *no le dedico* apenas tiempo en mis desarrollos. En el curso del SEF si que he aplicado estos conceptos y he usado **validadores** (algunos de ellos dan bastantes dolores de cabeza) así como sintaxis semántica en HTML para adaptar la web. Con esto he podido comprobar de primera mano lo complicado que puede resultar el desarrollo si le añadimos esta *nueva capa* (sobre todo en aumento del tiempo). No obstante, creo que es algo que ocurre debido a que no estamos familiarizados con esta forma de trabajar y quizá debamos hacer un **a11y first**, una especie de *mobile first*, para diseñar nuestras webs de manera accesible en primera instancia.

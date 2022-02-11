---
layout: post
title: Symfony y mucha programación
subtitle: Empezando con las APIs
cover-img: /assets/img/sf5.jpg
share-img: /assets/img/sf5.jpg
tags: [reflexion, programacion, symfony, api]
---

Las semanas comienzan a ponerse interesantes y ya se empieza a notar que los exámenes andan cerca. Estas semanas están siendo muy interesantes en las asignaturas que más me llaman la atención, como son programación en **entorno cliente y servidor**. En la primera de ellas estamos programando en Angular una especie de gestor de coches, en donde podemos visualizarlos en diferentes formatos (listas o tarjetas).

La verdad es que, hablándolo con otros compañeros, nos restá resultando **más cómodo Symfony** por la gestión que hace de los archivos y lo ordenado que se queda el código. Por contra, en Angular todo está dentro de la misma carpeta y cuesta moverse entre los archivos (al menos en mi caso). El código también queda algo caótico, pues *se mezcla HTML, CSS y código propio de Angular* (como directivas o bucles).

El resultado es un código dificil de mantener y actualizar (en mi opinión), que puede resultar muy confuso a la hora de saber qué hace cada componente, quién le envía los datos a su padre/hijo y, en definitiva, cómo funciona la aplicación. En la imagen inferior se puede ver una pizca de todo lo comentado arriba.

![Código en Angular](/assets/img/angularcode.PNG){: .mx-auto.d-block :}

Por otro lado, al usar tanto componente padre e hijo, me resulta muy complicado **posicionar los elementos** (aunque usemos Bootstrap), ya que tenemos que tener en cuenta el contenedor en donde está el componente, dónde está su padre o qué clases usa. No obstante, Luismi nos proporciona todo el código *relativo al diseño* y solo tenemos que preocuparnos de la funcionalidad. El resultado son unas aplicaciones muy vistosas y que se pueden realizar en muy poco tiempo.

![Código en Angular](/assets/img/cochesang.PNG){: .mx-auto.d-block :}

En el otro lado de la moneda tenemos Symfony, un **framework que me está encantando** y qué está haciendo que esté interesándome más el **backend que el frontend**. Últimamente prefiero pelearme con configuraciones de servidores, serializadores o rutas más que con los estilos de una página web. Entiendo que el *lado trasero* de la web puede resultar más complicado pues es necesario aprender de despliegue, servidores, docker o patrones de diseño, pero me resulta muy gratificante cuando salen las cosas.

![Código en Symfony](/assets/img/routesf.PNG){: .mx-auto.d-block :}

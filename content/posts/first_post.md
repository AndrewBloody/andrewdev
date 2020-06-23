---
title: "React Content Loader"
date: 2020-06-20T00:24:53-05:00
draft: false
featuredImage: "featured-image.jpg"
featuredImagePreview: "posts/first_post/featured-image.jpg"
---

Creación de un placeholder animado para componentes de React.

# SVG React content loader

Muchas veces nuestras aplicaciones necesitan hacer una petición hacia una API, por lo general
vamos a necesitar implementar en nuestro componente un "loading", o una pequeña parte de código
que se muestre únicamente durante esta transición. A veces el tiempo puede variar significativamente
todo depende de el internet que este usando el cliente, por lo cual eso puede ser causa de una
mala impresión de nuestra aplicación, pareciera que paso algo malo o simplemente no esta funcionando
de la manera esperada.

Para todo esto es necesario crear una "plantilla" y obtener datos del servidor o API de manera asincrona,
pero para que el usuario tenga una experiencia amigable es recomendable mostrar contenido, aqui es donde
entra el generador de svg, es muy facil de usar, este que se menciona en el post, es totalmente online,
te permitira crear formas de contenido animadas que al final se van a transformar en svg, y de esa manera
incluirmos de forma sencilla el código en nuestro componente.

La página se llama [Create React Content Loader](https://danilowoz.com/create-content-loader/) y actualmente
te ofrecen varios ejemplos para que puedas comenzar a generar tus svg. Por otra parte también existe el
modulo `react-content-loader` que te permitira utilizar un componente para la creación de tus
componentes [Github - react-content-loader](https://github.com/danilowoz/react-content-loader).

![ContentLoader](https://user-images.githubusercontent.com/4838076/34308760-ec55df82-e735-11e7-843b-2e311fa7b7d0.gif)

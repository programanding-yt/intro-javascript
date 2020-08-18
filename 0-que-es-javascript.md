# Qué es JavaScript - una muy breve introducción
## Definición simple
JavaScript (JS) es un lenguaje de programación utilizado principalmente en páginas web, servidores y algunas bases de datos. 
## Dónde se ejecuta código JS
JS se puede ejecutar en cualquier dispositivo con un *motor JavaScript*. Todos los navegadores web requieren un motor para poder utilizar JS.
- V8 (Chrome, Opera)
- SpiderMonkey (Firefox)
- JavaScriptCore (Safari)
- Chakra (Edge)
Node.js y Deno, que permiten ejecutar JS fuera del navegador, utilizan el motor V8.
## ¿Para qué se utiliza JS?
En el contexto del desarrollo de páginas web, específicamente del Frontend, (es decir, la parte visual, la interfaz, lo que ve el usuario), imaginemos este ejemplo:
Queremos construir un robot. 
- El 'esqueleto' se crea con HTML, de esta manera le damos estructura (brazos, tronco, piernas, extremidades)

![esqueleto](https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/283cf1d0beb4d802d7ce81c7006841bd/large.jpg)
- El aspecto se define con CSS (color, textura)

![aspecto](https://www.mansworldindia.com/wp-content/uploads/2014/08/Bi-Centennial-Man.jpg)
- El razonamiento del robot se crea con JS (interacciones con el entorno, cálculos matemáticos, lenguaje, reacciones)

![razonamiento](https://media.giphy.com/media/sFTWiBKYYWKVa/giphy.gif)
## JavaScript y Java
JavaScript y Java son dos lenguajes de programación totalmente distintos, no existe una relación entre ambos. 
"Java is to JavaScript what car is to carpet".- Chris Heilmann.
"Java es a JavaScript lo que carro es a carpeta".
## ECMAScript
La asociación [Ecma International](https://www.ecma-international.org/) se encarga de estandarizar JavaScript, es decir, de entregar un lenguaje de programación internacional, estandarizado, basado en JS. Este lenguaje de programación recibe el nombre de ECMAScript, y su especificación define una serie de requerimientos que permiten *implementar* ECMAScript. Esta especificación es la [ECMA-262](https://www.ecma-international.org/publications/standards/Ecma-262.htm).

Este documento no es una guía para aprender a programar en ECMAScript, sino para implementar tus propios features, que cumplan con el estándar de ECMAScript.

Para conocer las diferentes versiones de ECMAScript, utiliza el siguiente [link](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Language_Resources).
## Tu primer línea de código en JavaScript
Para concluir este video con un ejemplo práctico, crearemos una simple alerta en el navegador.
Abre tu navegador favorito, y abre las Herramientas de Desarrollador. Algunas opciones:
- Clic derecho en cualquier parte de la página > Ver código fuente
- Cmd + Option + I (Mac) / Control + Shift + I (Windows)
Selecciona la Pestaña "Consola"
Escribe el siguiente blóque de código:
```
alert('¡Voy a aprender a programar en JavaScript!');
```

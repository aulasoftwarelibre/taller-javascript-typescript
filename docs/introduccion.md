# Introducción

## JavaScript

![JavaScript](images/introduccion/javascript.png)

JavaScript (JS) es un lenguaje de programación **interpretado**, **débilmente tipado** y **dinámico**, utilizado por millones de personas en todo el mundo. Su principal utilidad se da en el lado del cliente, aunque cada vez más se utiliza en el lado del servidor (por ejemplo Node.js). No solo es un lenguaje de programación orientado a objetos, sino que es multiparadigma, permitiendo "crear programas usando más de un estilo de programación", tales como imperativo, funcional, etc.

Cabe destacar que este lenguaje de programación va acompañado de ECMASCRIPT. Realmente, este estándar y JavaScript (a efectos prácticos) son lo mismo. Este estándar es una especificación de JavaScript, el cual actualmente se encuentra en su 11º versión, publicada en 2020. Si bien es cierto que la última versión relevante fue ECMASCRIPT 6, la cual introdujo numerosos cambios con respecto a su versión anterior.

Y ¿en qué nos afecta a nosotros este estándar? Bueno, prácticamente todos los navegadores incluyen una implementación de ECMASCRIPT, pudiendo estos interpretar código JavaScript. No obstante, no todos los navegadores "entienden" JavaScript de la misma forma: cada uno cuenta con su propio motor de JavaScript e implementan una versión de ECMASCRIPT distinta. Por ello, contamos con una versión estándar que nos asegura que todos los navegadores la soportarán: ECMASCRIPT 5. Esto nos ayuda a que, si desarrollamos ajustándonos a este estándar, nuestro código pueda correr sin problemas en cualquier navegador.

!!! warning

    **JavaScript != Java**. El primero fue nombrado así debido a la popularidad en aquel momento del lenguaje Java, pero estos lenguajes cuentan con sintaxis, semántica y propósitos distintos.

## TypeScript

![TypeScript](images/introduccion/typescript.svg)

Para comprender qué es y de dónde viene TypeScript, debemos comprender bien la historia de JavaScript. Al principio, JavaScript era utilizado simplemente para escribir programas de pocas líneas de código, para utilizarlo de forma embebida en una página web y aportar pequeñas funcionalidades. Sin embargo, este lenguaje se fue utilizando por cada vez más desarrolladores, incrementando su uso y popularidad en gran medida.

¿Cuál es el problema? Muy simple: ningún lenguaje es perfecto y, en nuestro caso, JavaScript tampoco. Podemos, por ejemplo realizar la siguiente comprobación `"" == 0` y sería `true`, podriamos igualar variables que al principio eran números a cadenas, trabajar con propiedades de objetos inexistentes, etc. Es por ello por lo que aparece TypeScript.

TypeScript (TS) es un lenguaje diseñado por Microsoft, el cual puede ser considerado como un superset de JavaScript. Es decir **todo el código JavaScript es código TypeScript válido, y no al revés**. Este lenguaje nos aporta un tipado estricto y estático, es decir, podemos comprobar errores antes de ejecutar el programa.

Es importante entender que el código TypeScript no se ejecuta, sino que este se **transpila** al lenguaje JavaScript. Al transpilarlo, este tipado de datos se elimina, ya que el único propósito de dotar de tipos a las variables es la comprobación de errores antes de la ejecución de nuestro código. Una vez que "compilamos" nuestro código, el archivo JavaScript resultante no posee información referente al tipado. También podemos deducir que el comportamiento en tiempo de ejecución de nuestro código no cambiará si usamos JavaScript o TypeScript.

En las siguientes secciones del taller especificaremos con ejemplos las diferencias y las funcionalidades extra que nos ofrece TypeScript con respecto a JavaScript.

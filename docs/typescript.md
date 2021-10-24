# TypeScript

Ahora sí, vamos a profundizar en por qué TypeScript es cada vez más usado y en cuales

## Inconvenientes de JavaScript

Imaginemos el siguiente código JavaScript, donde accedemos a la propiedad `i` del objeto `punto`, la cual no existe. Vemos que JavaScript nos informa de que "puede que la propiedad atlura no exista" y es cuando ejecutamos el código cuando nos damos cuenta de que tenemos un error.

![Objeto en js](images/typescript/objetojs.png)

![Salida objeto en js](images/typescript/salidaobjetojs.png)

En TypeScript esto es totalmente distinto, ya que nos informa de antemano de que tenemos un error, no haciendo falta ejecutar el código para darnos cuenta.

![Objeto en ts](images/typescript/objetots.png)

Aún así, aunque JavaScript no nos muestre el error de forma tan flagrante, no sería necesario usar TypeScript para darnos cuenta de este, ¿no?.

Bueno, pongamos el ejemplo de que es una función la que recibe un punto, y que dentro de esa funcion accedemos a los parámetros de esta variable.

![Parametros inexistentes](images/typescript/parametroinexistente.png)

Vemos que perfectamente podemos acceder a campos de un objeto que no existen, sin que JavaScript nos muestre ningún error. Cuando llamemos a esta función en nuestro código y le pasemos un dato `punto`, obtendremos el error. Puede que en este caso sea un error fácil de entender y de corregir, pero imaginemos que esto nos ocurre en un proyecto grande, con numerosos ficheros todos ellos de cientos de líneas de código. Obtendremos errores inesperados que muchas veces serán muy difíciles de encontrar debido a problemas como este. Es ahí donde TypeScript marca la diferencia.

## Tipado: La gran ventaja de TypeScript

tipos de datos
any
interfaces

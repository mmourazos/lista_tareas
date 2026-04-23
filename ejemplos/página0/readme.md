# Ejemplo añadir elementos a lista

En la página de ejemplo podemos ver un botón en el que al hacer click añade un nuevo elemento a la lista ordenada de la página.

## Puntos a tener en cuenta

### ¿Por qué se incluye el JavaScript al final del body?

Cuando un navegador carga una página web, lo hace de arriba a abajo. Si el código JavaScript se encuentra al principio del documento, el navegador intentará ejecutarlo antes de haber cargado completamente el HTML. Como aún no ha procesado el HTML, aún no ha creado los elementos del DOM (Document Object Model): la lista ordenada y el botón. Esto haría que el código JavaScript no pueda encontrar esos elementos y, por lo tanto, no funcione correctamente.

### ¿Qué es una función?

En JavaScript, y en muchos otros lenguajes de programación, una función es un bloque de código (un conjunto de instrucciones) que se puede reutilizar.

### ¿Qué es un event listener?

Un event lístener es una función que se ejecuta en respuesta a un evento específico, como un clic del mouse. En este caso, el event listener está escuchando el evento "click" en el botón. Cuando el usuario hace clic en el botón, la función asociada al event listener se ejecuta. En el código de la función se incluyen las instrucciones para crear un nuevo elemento de lista (`li` _list item_) y añadirlo a la lista ordenada.


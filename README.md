# Resumen

El artículo "Cómo obtener datos en React" es básicamente una guía paso a paso sobre cómo hacer que nuestra app React hable con el servidor y obtenga datos.

Empieza explicando que un elemento <Child /> en React es algo así como una promesa de que se mostrará algo en la pantalla, pero sólo cuando sea su turno en el árbol de renderizado.

Ahora bien, conseguir datos de un servidor no es algo inmediato, puede llevar un rato. Así que se sugiere que podríamos poner un mensaje bonito del tipo "Cargando..." hasta que lleguen los datos.

Hablando de cómo conseguir los datos, se menciona que podemos usar algo llamado "promesas" en JavaScript. Una promesa es básicamente una forma genial de decir, "Hey, esto va a tardar un rato, pero te prometo que volveré con algo... o tal vez con un error". Podemos crear una promesa usando fetch('/some-url') y luego hacer algo cuando los datos estén listos con .then o manejar el error con .catch.

El artículo muestra cinco formas comunes de cómo obtener datos en React. No sólo eso, también nos enseña cómo manejar situaciones en las que algo va mal durante la obtención de datos.

Luego, habla sobre diferentes métodos como get, post, put y delete que podemos usar para hablar con la API. Y lo mejor de todo es que podemos hacer todo esto con el método fetch(), que es algo ya incorporado en JavaScript, por lo que no necesitamos ninguna librería extra para usarlo.

Para terminar, el artículo nos dice que las API son nuestras mejores amigas a la hora de desarrollar aplicaciones. Ya sea que estemos trabajando con una API REST o con GraphQL, las estrategias para obtener datos son bastante similares.
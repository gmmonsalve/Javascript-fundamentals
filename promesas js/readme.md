¿QUÉ SON LAS PROMESAS EN JAVASCRIPT?
Es una respuesta que esperamos a un evento que desencadenamos, es decir lo que me prometiste queremos saber si lo puedes cumplir o no. Es un objeto que nos va a permitir manipular un éxito o fracaso de manera más eficiente evitando la manipulación exagerada de los callbacks.

Then: en caso de éxito ingresar a este método.
Catch: en caso de fracaso.
Nota: si se dieron cuenta los callbacks estan inyectado dentro de nuestra función getPosts para decirle al Promise que debe devolver o hacer. Luego para el desarrollador que requiera usar esta función la vida se le hará más sencilla al tener un código más legible.

FLUJO DE UNA PROMESA
Cuando una promesa es disparada esta ingresa a un estado la cual puede ser las siguientes:

fulfilled: se cumplió con éxito.
rejected: no se pudo cumplir a casa de un error. Depende de ustedes como hagan el reject.
pending: se esta procesando.
settled: simplemente finalizo.
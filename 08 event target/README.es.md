08 Event Target
Cada evento tiene información útil que puedes usar durante el tiempo de ejecución.

Por ejemplo:

Si un usuario hace clic en un botón, sabes que botón específico tocó el usuario.

Si el usuario se desplaza por la ventana, puedes saber cuánto se ha desplazado.

Si el usuario movió el mouse, puedes saber la posición del mouse.

¡Y mucho más!

Cuando declaras una función event-handler, puedes usar un parámetro opcional que contenga la información del evento de esta manera:

function myFunctionName(eventInformation) {}
Este parámetro puede tener el nombre que quieras, y puedes estar seguro de que siempre contendrá la información del evento que lo activó. Por ejemplo, la propiedad eventInformation.target devolverá el objeto que activó el evento.

📝 Instrucciones:
Este sitio web ya tiene un listener cuando se hace un clic en el div #container.

Por favor, muestra una alerta con el id del elemento objetivo (el elemento al cual se le hizo clic).
💡 Pista:
Aquí está la documentación sobre event.target: http://www.w3schools.com/jsref/event_target.asp
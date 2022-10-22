# Sprint 2

## Objetivo del Sprint

Prototipado de diseños iniciales, para que el usuario pueda iniciar sesión en la aplicación.

## Sprint Planning

Tuvimos una meeting que duro alreadedor de 2:30 horas donde estuvimos hablando con Romi (Product owner)
con la cual decididimos cuales tareas eran las que aportaban mas valor, también creamos nuevas historias del feedback que
recibimos.
Luego sobre este set inicial de historias utilizamos Planning Poker para estimar las historias.

Para el Poker utilizamos https://www.scrumpoker-online.org.

Finalmente, dividimos las tareas entre el development team.

## Ejemplo Daily

Reflexión de la retro y oportunidades de mejora, descripción más detallada de los interesados, corrección del story map.
Tengo planeado terminar de documentar el análisis de resultado de entrevista, encuesta y funcionalidad por interesado. Tenia dudas sobre algunos análisis que habíamos realizado previamente para documentarlos correctamente pero se resolvieron en la daily.

[Dailies Sprint 2](./Dailies.md)

## Validacion Prototipo con usuarios

### Contexto de las pruebas

Las pruebas se realizaron bajo el siguiente contexto:
- El usuario sabía que se trataba de un prototipo, que alunas funcionalidades no estaban implementadas y que por ejemplo no se pueden editar los textos de las casillas por el momento.
- Se probo en dispositivos soportados por la aplicación, aquellos que tienen formato Android Large.

### REVISIÓN 1: 27 años

- Flujo realizado por la persona:

La persona ingresó a la aplicación registrando, luego inicia sesión, en el mapa intenta seleccionar origen y destino, ve la pantalla del mapa, lo mueve, selecciona el botón de centrarse en la ubicación actual, se dirige a los botones en la parte inferior, empieza por el botón más a la izquierda pasando por todas las funcionalidades hasta el botón más a la derecha, vuelve al primer botón y examina el contenido y le da al botón editar, allí hace tap en las opciones de edición, al llegar a la fecha se despliega el calendario y e intenta seleccionar una fecha, debe realizar scroll para guardar los cambios. pasa al botón del centro donde se encuentra el mapa, realiza doble clic en el mapa, pasa al botón de perfil y selecciona cerrar sesión, selecciona el botón de iniciar sesión con google y termina la prueba.
 
- ¿Qué funcionalidades entiende que realiza? 

RE: “Tenés la opción de registrarse, iniciar sesión con usuario y sin usuario, podes ver un mapa con tu ubicación y seleccionar una línea de ómnibus, tenés una ventana para ver tu perfil y actualizarlo, además podés cerrar la sesión.”

- ¿Le parece que se cumplen? 

* Inicio de sesión, tanto en modalidad anónima como por google e iCloud y la funcionalidad de cerrar la sesión (Considera que se cumple)
* Permitir registrarse en la aplicación / crearse una cuenta que no sea con el correo de google (Considera que se cumple)
* Edición del perfil del usuario y sus datos (Considera que se cumple)
* Presentar la opción de un mapa con la ubicación actual del usuario y un vistazo de cómo se realizará la consulta para iniciar viajes ingresando origen y destino (Considera que se cumple, pero falta mejorar, como poder ingresar diferentes destinos)
* Mostrar la navegación que tendrá la app a todas las ventanas de la aplicación (Considera que se cumple)

- ¿Qué opina de los colores seleccionados, le pareció agradable a la vista? 

RE: “Los colores me parecen acertados, se ve tranquilo, se ven los textos y los iconos.”

- ¿Cómo le resultó la navegación? (registrar respuestas)

RE: “Siento que se entiende, me gusta que los botones no tengan texto, los iconos elegidos están bien, no se ve como la pantalla muy saturada. Se parece a aplicaciones que he utilizado antes.”

- ¿Tiene algo para comentar/agregar? (registrar respuestas)

RE: “Entiendo que este es un prototipo y no están todas las funcionalidades, las que están me parece que cumplen, pero después me interesaría ver más interacción, poder escribir mi nombre y apellido, poder ver el tiempo que me queda para tomar el bus de la línea que seleccione y en qué parada hacerlo.”

### REVISIÓN 2: 50 años

- Flujo realizado por la persona:

La persona inicia la aplicación ingresado con usuario anónimo, se le presenta el mapa centrado en su ubicación, selecciona el botón de modo viaje, al estar sin implementar regresa al botón de en medio, selecciona el icono de centrado en la ubicación realizando doble clic, intenta iniciar un viaje en la opción que se encuentra en la lupa en la parte superior de la ventana, aparece su viaje en pantalla y se desplaza por el siguiendo la trayectoria marcada, selecciona el botón de comentarios y luego pasa al botón de configuraciones, por ultimo selecciona el primer botón e intenta editar su perfil terminando la prueba.
 
- ¿Qué funcionalidades entiende que realiza? (registrar respuestas)

RE: “Podes ver en el mapa donde estas y armar un viaje con punto de partida y fin, podes tener datos, además tenés la opción de tener una cuenta.”

- ¿Le parece que se cumplen? (registrar respuestas)

* Inicio de sesión, tanto en modalidad anónima como por google e iCloud y la funcionalidad de cerrar la sesión (No lo probo)
* Permitir registrarse en la aplicación / crearse una cuenta que no sea con el correo de google (Considera que se cumple)
* Edición del perfil del usuario y sus datos (Considera que se cumple)
* Presentar la opción de un mapa con la ubicación actual del usuario y un vistazo de cómo se realizará la consulta para iniciar viajes ingresando origen y destino (Considera que se cumple)
* Mostrar la navegación que tendrá la app a todas las ventanas de la aplicación (Considera que se cumple)

- ¿Qué opina de los colores seleccionados, le pareció agradable a la vista?

RE: “Está lindo, me parece que los colores pegan bien y no son muy fuertes.”

- ¿Cómo le resultó la navegación? 

RE: “Entendí bastante bien, pero me faltaría algún texto para saber en que ventana estoy o que me marque con color.”

- ¿Tiene algo para comentar/agregar? 

RE: “No entendí mucho como se dónde están las paradas, me aparecieron datos de cuenta aunque entre de forma anónima, aparte de eso me gusta, si bien pienso que le falta texto, esta bueno que no sea mucho así las personas como yo que vemos menos podemos usarla sin tanto problema.”

### REVISIÓN 1: 20 años

- Flujo realizado por la persona:

La persona ingresó a la aplicación registrando al finalizar el registro se logeo, donde llego al mapa intento ir a configuraciones donde desactivo las notificaciones. Luego volvio al mapa, donde intento mover el mapa y volver a centrarlo. Comento que el mapa no se veia bien en cuanto a la resolución. Intento editar el usuario, no pudo cambiar la fecha. Pudo cerrar sesion y iniciar nuevamente. Al ir al mapa estuvo problemas al intentar iniciar un viaje, pero luego pudo iniciar el viaje correctamente. Bajo el mapa y finalmente fue a modo viaje donde noto que la pagina estaba vacia.
 
- ¿Qué funcionalidades entiende que realiza? 

RE: “Pude iniciar sesión, iniciar un viaje, cambiar la configuración de notificaciones, ver el mapa con la ubicación actual. También se puede editar el perfil de usuario y cerrar la sesión.”

- ¿Le parece que se cumplen? 

* Inicio de sesión tanto como por Google, iCloud y Usuario y Email, la funcionalidad se cumple. (Considera que se cumple, pero no noto la funcionalidad de anónimo)
* Permitir registrarse en la aplicación / crearse una cuenta que no sea con el correo de google (Considera que se cumple)
* Edición del perfil del usuario y sus datos (Considera que se cumple)
* Presentar la opción de un mapa con la ubicación actual del usuario y un vistazo de cómo se realizará la consulta para iniciar viajes ingresando origen y destino (Considera que se cumple parcialmente, tuvo problemas al elegir el origen y destino, y comentó que el mapa se ve mal)
* Mostrar la navegación que tendrá la app a todas las ventanas de la aplicación (Considera que se cumple)

- ¿Qué opina de los colores seleccionados, le pareció agradable a la vista? 

RE: “Los colores me parecen correctos, le dan una imagen minimalista a la aplicación”

- ¿Cómo le resultó la navegación? (registrar respuestas)

RE: “Sintió que algunas cosas estaban medio escondidas, y que otras no se entendia como realizarlas.”

- ¿Tiene algo para comentar/agregar? (registrar respuestas)

RE: “Dado que es un prototipo, me parece que está acertado, pero me hubiese gustado que se pueda escribir en los inputs y que algunas interacciones se cumplan.”

[Validacion Usuarios](./assets/validacion%20usuario.MP4)
## Prototipos

### Inicio 
![PrototypeImage1](./assets/inicio.png)

### Inicio Sesión 
![PrototypeImage2](./assets/inicioSesion.png)

### Registro de la cuenta
![PrototypeImage3](./assets/registroCuentaFechaOculta.png)

### Registro de la cuenta - selección de fecha
![PrototypeImage4](./assets/registroCuenta.png)

### Perfil 
![PrototypeImage5](./assets/perfil.png)

### Perfil - edición
![PrototypeImage6](./assets/perfilEditado.png)

### Perfil - selección de fecha
![PrototypeImage7](./assets/perfilEditadoFecha.png)

### Inicio Viaje
![PrototypeImage8](./assets/inicioViaje.png)

### Inicio Viaje - selección de destino
![PrototypeImage9](./assets/inicioViajeDestinoSeleccionado.png)

### Inicio Viaje - selección de líneas
![PrototypeImage10](./assets/inicioViajeListadoLineas.png)

### Inicio Viaje - seleccionar origen
![PrototypeImage11](./assets/inicioViajeSeleccionarOrigen.png)

### Inicio Viaje - descarga de mapa
![PrototypeImage12](./assets/InicioViajeMapaDescargado.png)

### Inicio Viaje - ruta seleccionada 
![PrototypeImage13](./assets/inicioViajeRutaMostrada.png)

### Setting  
![PrototypeImage14](./assets/settings.png)

### Setting - lista de medios de notificación
![PrototypeImage15](./assets/settingDropdownAbierto.png)

### Setting  - desactivar notificacion
![PrototypeImage16](./assets/settingsNotificacionDesactivada.png)

### Setting - desactivar sonido
![PrototypeImage17](./assets/settingSonidoDesactivado.png)

### Modo Viaje
![PrototypeImage18](./assets/modoViaje.png)

### Comentarios
![PrototypeImage19](./assets/comentario.png)


### Link a prototipo

[Prototipo](https://www.figma.com/proto/HmnWSlpF0ozOWEV7KaNNtx/ISA-1?node-id=1%3A13&scaling=scale-down&page-id=0%3A1&starting-point-node-id=47%3A46)
## Sprint Review


![Burndown Chart](./assets/burndown%20chart.png)

![Burnup Chart](./assets/burnup.png)

![Velocity Chart](./assets/velocity%20chart.png)

## Retrospective

Utilizamos metroretro para hacer la retrospective.

![Retrospective](./assets/retro1.png)

<hr>

# Reporte de horas

[Reporte de horas](https://docs.google.com/spreadsheets/d/1Kh862NqWlY94nU2gIDmNjZJNJ3PDnCxO8ejniM3c5-s/edit?usp=sharing)



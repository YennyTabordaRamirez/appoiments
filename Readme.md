# Microservicio de citas de laboratorio

### Contiene un _backstage.yaml_ para la configuración y exposición del microservicio a través de un template en un Backstage

## Prerrequisitos

Tener instaladas en ambiente local las siguientes herramientas:

* Postman
* Intellij Idea
* Maven
* SDK de Java
* Tener configuradas las variables de entorno de Maven y Java
* MySql Workbench
    * El puerto por el que debe correr la BD's es el 8080
    * El usuario debe ser el "root" y la clave debe ser "admin1234" (Si desean pueden usar otra pero deben cambiarlo en el "application.properties" de la aplicación)
    * Luego de tener el MySql instalado y configurado, deben crearle una nueva base de datos (schema) llamada _appoiments_
* En l raíz del proyecto, en la carpeta de _assets_ hay un _.json_ en el cual están los endpoints de la aplicació;  se deben importar desde el postman para que se puedan consumir los servicion


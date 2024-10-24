# ProyectoFinal
Entrega del proyecto final de taller de GO

Este proyecto incluye la configuración de un contenedor Docker y está conectado con DBeaver para gestionar la base de datos. A continuación se detallan los pasos para configurar y ejecutar el proyecto.

##INSTRUCCIONES

Requisitos previos
Asegúrate de tener instalado lo siguiente:

Go (versión 1.16 o superior)
Git
Docker
DBeaver (para gestionar la base de datos MySQL)

1. Acceder al repositorio
Clona el repositorio en tu máquina local:

git clone https://github.com/tu_usuario/proyecto_golang.git
## 1. Crear contenedor en docker
Crea un contenedor en docker con el nombre de mysql
Colocale el nombre de usuario:root constraseña:test

Configuración de DBeaver
Abre DBeaver y crea una nueva conexión a la base de datos MySQL.

Configura la conexión usando los siguientes parámetros:

Host: localhost 
Port: 8001 
Username: root 
Password: test 

Una vez conectada la base de datos, podrás ver y gestionar las tablas del proyecto.

Para utilizar este proyecto :
Haz un fork del proyecto.
Crea una nueva rama (git checkout -b feature/nueva-funcionalidad).
Realiza tus cambios y haz un commit (git commit -am 'Añadir nueva funcionalidad').
Sube los cambios (git push origin feature/nueva-funcionalidad).
Crea un Pull Request.

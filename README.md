# Proyecto Foro Hub

## Funcionamiento

Permite iniciar sesión ingresando el correo electrónico y la contraseña del usuario.

A través de la autenticación, se pueden realizar operaciones CRUD para cursos, perfiles, usuarios, respuestas y temas.

La documentación de la API se genera automáticamente con Swagger-ui y se puede acceder a ella desde el navegador.

## Dependencias (ver pom.xml)

1) Swagger
2) Lombok
3) Flyway
4) MySQL Connector
5) JWT
6) Spring Framework
	- Spring Boot (versión 17 desde Initializr)
	- Spring Web
	- Spring Security
	- Spring Validation
	- Spring Data JPA
7) Versión Java y Herramientas
	- Java SpringBoot (Initializr): Versión 17
	- Java Intellij: Versión 21

## Funcionamiento

Es necesario implementar la creación de usuarios mediante el almacenamiento seguro de su correo electrónico y contraseña en formato hash (utilizando bcrypt) en la base de datos, junto con la gestión de perfiles asociados.

Posteriormente, se debe permitir a los usuarios iniciar sesión y realizar operaciones de registro para nuevos temas y respuestas.

## Video del funcionamiento de la aplicación

[![Mira el vídeo](https://github.com/KeilinPaniagua/Foro-Hub/blob/main/Proyecto%20Foro%20Hub.png)](https://youtu.be/aqYCaEz9UT8)

![swagger](https://github.com/KeilinPaniagua/Foro-Hub/blob/main/Proyecto%20Foro%20Hub%202png.png)

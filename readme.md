## Despliegue de apps Spring Boot en Heroku

Crear archivo `system.properties` en el proyecto con el contenido:
```
java.runtime.version=18 (version de java del proyecto)
```

1. Crear cuenta en heroku.com y github.com
2. Tener configurado git en el ordenador (solo la primera vez):
   1. `git config --global user.name "usuario"`
   2. `git config --global user.email "tuemail@dominio.com"`
3. Subir el proyecto a Github desde IntelliJ IDEA desde la opción: VCS > Share project on GitHub
4. Desde Heroku, crear App y elegir método GitHub.
5. Buscar el repositorio subidoresHabilitar Deploy Auto y ejecutar el Deploy

## Ejercicio 1

* Probar a empaquetar la aplicacion con Maven Package desde intellij IDEA
* Desde terminal en IntelliJ IDEA verificar que se ejecuta correctamente con el comando:
```
java -jar target/spring-deploy-1.0.jar
```
* Crear un perfil para DEV y otro para TEST con una propiedad nueva que carguemos en el controlador.

## Ejercicio 2

Desplegar el API REST de Laptops en Heroku y verificar el funcionamiento desde POSTMAN.

## Proveedores

* Heroku -- Java, Spring, PostgreSQL
  * https://www.heroku.com/
* Netlify -- Frontend (React, Angular, ...)
  * https://www.netlify.com/
* Vercel -- Frontend (React, Angular, ...)
  * https://vercel.com/
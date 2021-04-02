# Clase 3

## Git

**Git** es un software de control de versiones que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo. De esta forma, podemos recuperar y tener acceso a versiones específicas cuando queramos.

Git te permite tener un backup en la nube de tu proyecto con servicios como GitHub. También permite revertir archivos y proyectos enteros a un estado anterior, comparar cambios a lo largo del tiempo, ver quién modificó por última vez algo que puede estar causando un problema, quién introdujo un error y cuándo, etc.

**Repositorio local:** es el que tiene todos los archivos (que hayas guardado en él) en la computadora.

**Commits:** son los paquetes que nos van a permitir ir haciendo un seguimiento de los cambios que vamos realizando, dado que cada uno de ellos tiene una timestamp y un autor. Los commits van a ser nuestro **historial de cambios** que se fueron haciendo en el proyecto.

## Comandos de git

**git init:** Crea el repositorio

**git config user.name "nombre de usuario":** Agrega nuestra identidad

**git config user.email "nombreUsuario@email.com":** Agrega nuestro email

**git remote add origin https://github.com/DH/RepoRemoto:** Apunta al repositorio remoto

**git add . :** Agrega todos los archivos

**git status:** Indica el estado del seguimiento de los archivos

**git commit -m "mensaje":** Comitea los cambios hechos


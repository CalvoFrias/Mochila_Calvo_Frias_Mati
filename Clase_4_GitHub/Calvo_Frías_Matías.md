# Clase 4

## GitHub

**Repositorio:** El lugar donde se irán almacenando los archivos de nuestro proyecto y a través del cual podremos hacer seguimiento de los mismos. Hay repositorios **locales** y **remotos**.

##  Conectar repositorio local con el remoto

### Indicar mi usuario para el repositorio

>git config user.name “mi usuario”
>git config user.email “miCorreo@email.com”

Con git config *--global* user.name podemos configurar el usuario para todo git. Lo mismo con user.email para el correo.

### Vincular la URL

**git remote add origin https://github.com/miURL:** Con esto vinculamos los repos

Puedo chequear si están bien conectados con **git remote -v**. Debería devolverme:

>origin - https:// ... / (fetch)
>origin - https:// ... / (push)

## Subir archivos

>git add .
>git commit -m 'mensaje'
>**git push origin main/master**

## Bajar archivos

**git clone "url del repositorio":** Descargar el repositorio por primera vez

**git pull origin main:** Actualiza tu repositorio local con el remoto, siempre que lo hayamos clonado en algún momento.

Recordá hacer pull antes de push para evitar conflictos:

**git pull origin main > git add . > git commit -m "agrego mis archivos" > git push origin main**

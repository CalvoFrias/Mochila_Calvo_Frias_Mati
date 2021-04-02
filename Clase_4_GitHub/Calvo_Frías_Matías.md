# Clase 4

## GitHub

**Repositorio:** El lugar donde se irán almacenando los archivos de nuestro proyecto y a través del cual podremos hacer seguimiento de los mismos. Hay repositorios **locales** y **remotos**.

##  Conectar repositorio local con el remoto

### Indicar mi usuario para el repositorio

>git config user.name “mi usuario”
>
>git config user.email “miCorreo@email.com”

Con git config *--global* user.name podemos configurar el usuario para todo git. Lo mismo con user.email para el correo.

### Vincular la URL

**git remote add origin https://github.com/miURL:** Con esto vinculamos los repos

Puedo chequear si están bien conectados con **git remote -v**. Debería devolverme:

>origin - https:// ... / (fetch)
>
>origin - https:// ... / (push)

## Subir archivos

>git add .
>
>git commit -m 'mensaje'
>
>**git push origin main/master**

## Bajar archivos

**git clone "url del repositorio":** Descargar el repositorio por primera vez

**git pull origin main:** Actualiza tu repositorio local con el remoto, siempre que lo hayamos clonado en algún momento.

Recordá hacer pull antes de push para evitar conflictos:

**git pull origin main > git add . > git commit -m "agrego mis archivos" > git push origin main**

_____________________________________________________________

# Cuestionario

### ¿Quién inventó Git y por qué?

Git fue creado por Linus Torvalds, el creador del kernel Linux, debido a que necesitaba una herramienta 
que pudiera gestionar mejor el flujo de trabajo de la enorme comunidad creciente que contribuía al código 
de Linux. Se retiro durante un tiempo y creó el código desde cero de esta nueva herramienta.

### ¿A quién pertenece actualmente GitHub y por qué?

El 4 de junio de 2018 Microsoft compró GitHub por la cantidad de 7500 millones de dólares, buscándo acercándose a la comunidad del Open Source. "Desde el nombramiento de Satya Nadella como CEO de Microsoft (sustituyendo al infame Steve Ballmer), la compañía ha adoptado una estrategia nueva, mucho más abierta al mundo del software libre y a la integración con otras plataformas y servicios."

También se especula que se haya tomado la decisión en vistas de sus planes para su plataforma de servicios de computación en la nube, mercado en  el que busca competir. Además, hay otro motivo de peso: Microsoft Azure. En plena explosión de cloud services (servicios en la nube), con un crecimiento previsto para este año del 21.4%, Microsoft tiene que competir con el líder indiscutible a día de hoy, la todopoderosa Amazon con AWS."

[Fuente](https://naukas.com/2018/06/06/microsoft-compra-github/)

### ¿Hay otra forma que no sea la terminal para trabajar con GitHub?

Se puede trabajar directo desde la página web subiendo los archivos y haciendo los commits directo desde
allí o mediante una aplicación de escritorio.

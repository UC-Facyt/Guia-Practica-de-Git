# Introducción a git

Bienvenido! Este repositorio te servira como herramienta para aprender a usar git en conjunto con github.

En tal caso que aun no tengas instalado git en tu equipo, ve hacia [este link]() donde te explicaremos como instalar git en tu sistema operativo.

1. Primero que nada, crea una nueva carpeta en tu equipo, en este ejemplo le pondremos el nombre de proyecto navega hacia ella en la terminal, y corre el siguiente comando: `git init`. Esto creara un repositorio git vacio en esta carpeta, y para verificar que fue asi, puedes correr `ls -a` en la terminal, y en el listado deberias poder ver la carpeta oculta `.git`. Git se encarga de administrar los archivos en esta carpeta, que es donde
guarda la informacion acerca de nuestro proyecto y las distintas versiones.


2. Crear un archivo llamado README.md (la extensión md es un tipo de archivo
llamado markdown), y dentro de el escribir lo siguiente:

```markdown
# Proyecto Learn-Git

Este el dnto informativo de mi proyecto.
```

Luego de escribir ese contenido en nuestro archivo README.md y asegurarnos de
guardarlo, correr en el terminal `git status`. Esto nos dira el estatus actual
de nuestros archivos en nuestro proyecto con git. Deberiamos obtener un mensaje
parecido al siguiente:

LINK AQUI METER LA WEBONA DEL STATUS

Esto nos indica que git no esta siguiendo o observando los cambios en nuestro
arthivo README.md, por lo que debemos agregarlo. Para hacerlo, debemos correr el
comando `git add README.md`. Esto agregara nuestro archivo al Staging Area de
git, tambien llamado index. De esta manera git ya esta observando los cambios
por los que pasa el archivo.


3. En el terminal podemos correr `git status` de nuevo para ver el estado de
nuestros archivos. Obtendremos algo como esto:

VAINA

Esto nos indica que estos cambios han sido agregados y estan listos para el
siguiente commit que realicemos. Para realizar un commit ejecuamos el comando `git commit -m "Primer Commit"`, esto creara un commit con el mensaje que
especificamos. Un commit puede ser visto como una version. Si en el terminal
ahora escribimos `git log`, esto nos listara la información acerca del commit que acabamos de realizar.

# Cajamar_Water_Footprint

### Git

* [Instalar git](https://git-scm.com/downloads)
* Abrir terminal desde el proyecto de vuestro ordenador o en la carpeta en la que queráis poner el proyecto de GitHub.
* Escribir `git clone https://github.com/BelenSantamaria/IA3.git` ese enlace lo podeís obtener al abrir un repositorio de GitHub en la pensaña verde que pone code. Así podríais clonar cualquier repositorio.
* Ahora deberíais tener una copia de los archivos del repositorio en vuestro ordenador y podéis editar lo que queráis.
* Para poder subir vuestros cambios al repositorio tenéis que identificaros escribiendo 

`git config --global user.name "Your Name"` En "Your Name" ponéis vuestro nombre de usuario en GitHub (si vuestro nombre no contiene espacios no hacen falta las comillas)

`git config --global user.email "you@example.com"` Aquí lo mismo, ponéis vuestro correo de la cuenta de GitHub

* Antes de subir nada a GitHub tenéis que hacer `git pull` por si algún compañero hubiera subido algo a GitHub que no tenéis actualizado en vuestro ordenador porque si no habrá incompatibilidades y no os dejará subirlo.
* A mí me gusta hacer lo primero `git status` para ver que archivos hay en mi ordenador que aún no he subido
* Luego hacer `git add nombre_archivo` ponéis el nombre del archivo que queréis subir (los que aparecían haciendo git status en el paso anterior) y lo mismo si contienen espacios los ponéis entre comillas.
* El siguiente paso es hacer `git commit -m"comentario identificativo sobre los cambios que has hecho"` este comentario siempre va entre comillas.
* Por último `git push` y ya estaría
* y luego si queréis hacer más cambios repetis desde `git pull`
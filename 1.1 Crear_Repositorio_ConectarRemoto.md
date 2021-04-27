# Git: -Control de versiones

## Comandos para crear tu repositorio local

### PASOS
## - 1. Crear un directorio en tu Pc y ejecutar

- `git init` ---> iniciar el directorio.

Archivos que no se deben versionar: 
--Archivos propios de configuracion,Archivos privados, urls a servidores, contraseñas, accesos,

- .gitignore: añadir archivos y directorios que no queremos versionar

## - 2. Configurar la sesion: para el usuario
`git config --global user.name "Vike"`
`git config --global user.email "vike@gmail.com"`

## - 3. Ver staus: muestra en que usuario estoy y mas
`git config --list`


## - 4. Agregar archivos 
`git add . ó git add --all`: estos pasan al stagin area

*`git diff --cached`: ver los cambios que estamos por guardar.
--Es antes de agregarlo y de hacer git commit
*

*Si queremos quitar los archivos del staging area
`git rm --cached namearchivo` *

## - 5. Agregar Mensaje del commit: muestra que se hizo
`git commit -m "mi primer commit"` 
--El msj debe ser conciso,corto, claro y con cierto formato.

* Agregar al mismo tiempo y agregar comentarios
`git commit -a -m "msj"`
--Solo para archivos que hayan sido versionados y modificados *

## - 6. `git log` : ver el historial de commits

## 7. `git log` --graph --online : es mas resumido, muestra el hash(7 digitos)
* es cada commit, solo muestra los mjs del commit.



# Sincronizar Repositorio local con el remoto 


## 1. `git remote -v` : muestra los repo que ya estan conectados.
---Si no muestra nada, es que aun no esta configurado.
---Puede haber mas de un remoto.

## 2. Ir a github y crear un repositorio.

## 3. `git remote add origin https://github.com/UsuarioGit/NameReporitory.git`

## 4. Crear un proyecto en gitlab, y copiar la url para hacer un push tambien a gitlab
`git remote add gitlab https://gitlab.com/UsuarioGit/NameReporitory.git` 

*Conclusion: hay dos repos remotos conectados a un repo local*

## 5. Hacer push: es sincronizar de manera local a remota un repositorio.
---Subir los commit locales a github.

## 6. Push
```
git push [remoto] [rama]----> Del repo local al remoto
git push -u origin main
git push -u gitlab main
```


## Si ya tienes un repositorio en Github.

*Clonar un repositorio o descargar cambios de este.*
1. --Crear directorio local

git clone url: crea una copia de un repositorio remoto a un equipo local.
`git clone https://github.com/UsuarioGit/NameReporitory.git` .
El punto al final para que te lo descarge en esa carpeta, sin el nombre del repositorio.


`git pull`: sincronizar de un repo remoto al local o descargar cambios al repo local

git pull origin master

git log ----> salir con la letra q

 











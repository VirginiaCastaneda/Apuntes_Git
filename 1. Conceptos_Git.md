# PROCESO INICIAL
### 1
- git init : crea el staging y el repo de manera local
- git add . ----> cuando lo escribes pasa al staging en memoria RAM. Se esta rastreando.
- Staging: es la memoria estado temporal que agregas archivos que vas cambiando
### 2
- git commmit -m: ---> cuando haces un commit lo mandas al repositorio: /.git/ local
- git checkout ---> te traes los cambios.

### 3
- hacer una actualizacion. git fetch: lo trae al repo local
- git merge: fusionar
- git pull: copia una el repo local y la base de datos de cambios y el directorio: copia actualizada del repo.

### 4
- Crear rama: Me permite tener una copia identica de la rama master y modificar todo lo que quiero sin afectarla, y si me regreso a la rama master todo sigue igual, porque los commits solo fueron en la otra rama.
- RAMAS: hacer cambios sin afectar la rama principal
- Master: varias versiones: historia de commits
- Rama Experimental :  ---> copia de la rama master
- Merge: unes los cambios de una rama con otra

### 5
- git branch name  :---->nombre de la rama
- git show -----> muestra los cambios
- git checkout nombre_rama: para cambiar de rama en rama
- git commit -am : agrega cambios y mensaje fusiona el git add y commit
### 6
- FUSION DE RAMAS
- Crear un nuevo commit en la rama master combinando
- los cambios de la rama cabecera:
- git checkout master
- git merge cabecera: Es un commit a la rama secundaria para fusionarlo

### Crear un nuevo commit en la rama cabecera combinando los cambios de cualquier otra rama:
- git checkout cabecera
- git merge cualquier-otra-rama

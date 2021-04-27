# Comandos  comparar commits
- git log name_archivo.txt ----> ver todos los cambios en los commits

- git show nombre_archivo.txt  ---> muestra los cambios sobre un archivo

- esc +ship +Z+ Z ---->para salir cuando no agregaste un msj en el commit y te pidio que lo agregaras y lo hiciste. Es igual a la forma de guardar

- git diff num_commitV1Viejo num_commitV2Masnuevo ---> hace una comparacion entre commits el num del commit lo encuentras cuando haces el 
comando git log, ese lo copias; en verde la version mas actual y en rojo mas vieja

- * PARA SALIRTE CUANDO HACE LA COMPARACION PUEDES USAR la letra Q  Y TE REGRESA A LA RAMA * 


# VOLVER A LA PRIMERA VERSION DESDE LA ULTIMA MAS ACTUAL
- git reset num_commitV2 ---> volver a una version anterior
- hay de dos tipos:
1. git reset num_commitV2 --hard    ---> todo vuleve al estado anterior

2. git checkout num_commit  nombre.txt ---> me regresa  ala version en la que quiero estar

- git reset --soft: Borramos todo el historial y los registros de Git pero guardamos los cambios que tengamos en Staging, así podemos aplicar las últimas actualizaciones a un nuevo commit.
- git reset --hard: Borra todo. Todo todito, absolutamente todo. Toda la información de los commits y del área de staging se borra del historial.


- git checkout num_commit_Version1 nombre_archivo.html --->que quieres ver en su estado original
- git checkout main/master archivo.txt ---> se regresa a la ultima version(actual)






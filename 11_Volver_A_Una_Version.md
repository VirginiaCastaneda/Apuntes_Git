# Restaurar el archivo a cierto commit
```
git reset --hard 012cd0
```

# VOLVER A LA PRIMERA VERSION DESDE LA ULTIMA MAS ACTUAL
- git reset num_commitV2 ---> volver a una version anterior

- Hay de dos tipos:
1. git reset num_commitV2 --hard    ---> todo vuelve al estado anterior


2.  git reset --soft: Borramos todo el historial y los registros de Git pero guardamos los cambios que tengamos en Staging, así podemos aplicar las últimas actualizaciones a un nuevo commit.

3. git reset --hard: Borra todo. **Todo todito, absolutamente todo**. Toda la información de los commits y del área de staging se borra del historial. NO RECOMENDABLE


- git checkout num_commit_Version1 nombre_archivo.html --->que quieres ver en su estado original
- git checkout main/master archivo.txt ---> se regresa a la ultima version(actual)
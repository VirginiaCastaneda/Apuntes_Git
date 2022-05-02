# Intro Branches
- Linea de tiempo

## 1. Crear Ramas
```
git branch name_rama
git branch develop
```

## 2. Ver tus ramas
```
`git branch`
```

### 2.1 Cambiar entre ramas
```
git checkout name_rama
git checkout develop`
```

## 3. Integrar cambios entre ramas (MERGE)
- Asegurarte que tienes tu rama master o main actualizada. Para evitar conflictos.

- Si quiero integrar los cambios de develop a master, lo primero que debo hacer es estar posicionada en la rama master 

1. Primero actualizar cambios con el pull que esten en remoto
```
git pull origin master
```

2. Despues integrar los cambios de una rama a otra:
    - Debes posicionarte en la rama que quieres fusionar.
```
git merge develop
```

## 4. Borrar ramas:
```
`git branch -d develop`
```

## 5. Borrar ramas Forzar
- forzar la eliminacion de la rama la rama.
```
`git branch -D develop`
```


## 6. git fetch origin ---> descargar los cambios pero nos va a integrar











## 1. Ramas
listar las ramas existentes:
git branch

## 2. crear una rama

`git branch name_rama`
`git branch develop`

- cambiar a la rama: git checkout develop

- git checkout name_rama: nos permite manejar las ramas

## 3. integrar cambios entre ramas
- -Asegurarte que tienes tu rama master actualizada
- -Para evitar conflictos.

- Si quiero integrar los cambios de develop a master, lo primero que debo hacer es estar posicionada en la rama master y despues dar el commit 

- Primero actualizar cambios con el pull que esten en remoto
- `git pull origin master`

- Despues integrar los cambios de una rama a otra:
---Debes posicionarte en la rama que quieres fusionar.

- `git merge develop`

## 4. Borrar ramas:
`git branch -d develop`

## 5. Crear otra rama
`git checkout -b develop`: -b cambia a la rama automatico.

---No quiero los cambios: borrar la rama
git branch -D develop ---> forzar la eliminacion de la rama la rama.


## 6. Subir rama local a repositorio remoto:
git push origin develop


## 7. git fetch origin ---> descargar los cambios pero nos va a integrar
 integrar commit:

## 8. Integrar los cambios de developer a master.
---Posicionarte en la rama que haras el merge (master)
Comando: git checkout master
git merge develop

# --------PARA INDICAR QUIEN HIZO EL MERGE, CUANDO, COMO,ETC.-----------
se pone no forward; comado:
`git merge --no-ff develop`

For Vi or Vim
If you are using vi or vim, to manage to get out, you’ll have to do :

Press “i” (i for insert)
Write your merge message
Press “esc” (escape)
Write “:wq” (write & quit)
Then press enter

## 9. Borrar rama remota
git push origin --delete develop







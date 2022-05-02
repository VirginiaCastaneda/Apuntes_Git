1. heroku container:login 

2. heroku create name
- Te da el link
- https://dev-school-test.herokuapp.com/
- https://git.heroku.com/dev-school-test.git

3. Conectar github en heroku y la rama a la cual haras deploy

4. Crear el heroku.yml
- para que la imagen del Dockerfile se cree en heroku, previamente creado

5. git add heroku.yml
6. hacer commit
7. Set the stack of your app to container: heroku stack:set container
8. Agregar git remote heroku
9. heroku git:remote -a name_app_heroku
10. Hacer push a heroku: Si estas en otra rama que no sea la main en heroku:
- git push heroku develop:main
- Si no: git push heroku main

Your application will be built, and Heroku will use the run command provided in heroku.yml instead of your Procfile

- AHORA SOLO HACER PUSH A GITHUB Y LOS CAMBIOS SE CARGAN AUTOMATICAMENTE AL HEROKU PARA EL DEPLOY. 
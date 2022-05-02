# Crear app en heroku con CLI
# Heroku Docker Deployment

1. heroku container:login 

2. heroku create name
- Te da el link
- https://dev-school-test.herokuapp.com/
- https://git.heroku.com/dev-school-test.git

3. Re-build the Docker image and tag it with the following format:
- registry.heroku.com/<app>/<process-type>

- Make sure to replace <app> with the name of the Heroku app that you just created and <process-type>
 with web since this will be for a web process.

- docker build -t registry.heroku.com/dev-school-test/web .

4. Push the image to the registry
- docker push registry.heroku.com/dev-school-test/web

5. Release the image (corre el contenedor)
- heroku container:release -a dev-school-test web

6. Abrir la app en mi nav.
- heroku open -a dev-school-test

https://dev-school-test.herokuapp.com/

# TODO ok

# Subir a git de heroku

1. - git:remote -a dev-school
2. git add .
3. git commit -m "msj"
- Por sino te deja hacer push porque tienes que tener un archivo .yml ejecuta: 
'heroku stack:set heroku-20

4. git push heroku new_branch:main
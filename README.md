# Tarea 4

IMPORTANTE
Debes tener un repositorio vacio ya creado en Github.

 # Primero debemos crear el repositorio en nuestra consola de git:
      
    git init "el nombre que quieras"
    Ejemplo: git init sinreadme

# Nos movemos al repositorio que acabamos de crear:
    cd sinreadme

# Ahora tenemos que crear el README.md:
    touch README.md

# Añadimos el archivo que acabamos de crear
git add README.md

# Debemos guardar los cambios hechos en los archivos con el siguiente comando:
    git commit -m "comentario que queramos"
    Ejemplo: git commit -m "README.MD añadido"

# Ahora debemos copiar la URL del repositorio que hemos creado antes del tutorial:
    git remote add origin "url del repositorio"

# Y finalmente subimos nuestro trabajo al repositorio de Github
    git push --set-upstream origin main

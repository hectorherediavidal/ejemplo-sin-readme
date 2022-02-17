# Tarea 4

IMPORTANTE
Debes tener un repositorio vacio ya creado en Github.

 # Primero debemos crear el repositorio en nuestra consola de git:
      
    git init "el nombre que quieras"
    Ejemplo: git init sinreadme
![8](https://github.com/hectorherediavidal/ejemplo-sin-readme/blob/main/img/8.PNG.jpg "")

# Nos movemos al repositorio que acabamos de crear:
    cd sinreadme
![9](https://github.com/hectorherediavidal/ejemplo-sin-readme/blob/main/img/9.PNG.jpg "")

# Ahora tenemos que crear el README.md:
    touch README.md
![10](https://github.com/hectorherediavidal/ejemplo-sin-readme/blob/main/img/10.PNG.jpg "")

# Añadimos el archivo que acabamos de crear
    git add README.md
![11](https://github.com/hectorherediavidal/ejemplo-sin-readme/blob/main/img/11.PNG.jpg "")

# Debemos guardar los cambios hechos en los archivos con el siguiente comando:
    git commit -m "comentario que queramos"
    Ejemplo: git commit -m "README.MD añadido"
![12](https://github.com/hectorherediavidal/ejemplo-sin-readme/blob/main/img/12.PNG.jpg "")

# Ahora debemos copiar la URL del repositorio que hemos creado antes del tutorial:
    git remote add origin "url del repositorio"
![13](https://github.com/hectorherediavidal/ejemplo-sin-readme/blob/main/img/13.PNG.jpg "")

# Y finalmente subimos nuestro trabajo al repositorio de Github
    git push --set-upstream origin main
![14](https://github.com/hectorherediavidal/ejemplo-sin-readme/blob/main/img/14.PNG.jpg "")

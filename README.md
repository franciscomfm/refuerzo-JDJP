# Juan Diego Jurado Pimentel - Actividad 4
## Ejercicio 2:
Clonar repositorio en local -> **git clone https://github.com/juandiegojp/JD_JP-Proyecto-GIT.git**

_Sirve para para clonar nuestro repositorio de GitHub en nuestro equipo_

![Comando GIT CLONE](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-1.png)


## Ejercicio 4:
A continuación vamos a hacer un `git add` para añadir los nuevos elementos que hemos añadido en nuestro repositorio local, siendo el siguiente comando `git add .` el que hemos usado.

![Comando GIT ADD](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-2.PNG)

## Ejercicio 5:

En este apartado vamos a hacer un push a nuestro repositorio remoto, pero en primer lugar a usar el comando `git remote remove origin` para desconectarnos del repositorio remoto de la carpeta que hemos importado anteriormente.
Luego hacemos `get remote add origin https://github.com/juandiegojp/refuerzo-JDJP.git`, `git branch -M main` y, finalmente, hacemos el push a nuestro repositorio con `git push -u origin main`

![Comando GIT REMOTE](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-3.PNG)


# Ejercicio 6:

En este apartado hemos creado la carpeta `privada/` y el fichero `privado` como podemos ver en la siguiente imagen:
![ARCHIVO-CARPETA](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-4.PNG)

Seguidamente, creamos un fichero `.gitignore` y añadiremos los archivos que no queremos que pase Git.
![.gitignore](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-5.PNG)
![GIT STATUS](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-6.PNG)


# Ejercicio 8:

En este apartado he usado `git status` en primer lugar. Luego he usado `git add .` para añadir los nuevos archivos/modificaciones.
Seguidamente usamos el comando `git commit -m 'TAG'` y finalmente `git tag v0.1`.
![Comandos varios](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-7.PNG)

Con el comando `git show` podemos ver la información de la etiqueta junto con el _commit_ que está etiquetado.
![Comando GIT SHOW](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-8.PNG)


# Ejercicio 9:
Para subir un tag, junto con el resto de cambios, he introduccido el comando `git push -u origin main --tags`.
![GIT PUSH con TAG](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-9.PNG)


# Ejercicio 12:
_Tabla de compañeros_

Nombre | GITHUB
------ | --------
Jesús Manuel Espinar Ocaña | https://github.com/jesus-eo
Miguel Guitiérrez | https://github.com/MiguelGutierrezParejo
Francisco Fernandez | https://github.com/franciscomfm

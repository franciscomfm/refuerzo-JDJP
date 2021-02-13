# Juan Diego Jurado Pimentel - Actividad 4
## Actividad 4 - Ejercicio 2:
Clonar repositorio en local -> **git clone https://github.com/juandiegojp/JD_JP-Proyecto-GIT.git**

_Sirve para para clonar nuestro repositorio de GitHub en nuestro equipo_

![Comando GIT CLONE](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-1.png)


## Actividad 4 - Ejercicio 4:
A continuación vamos a hacer un `git add` para añadir los nuevos elementos que hemos añadido en nuestro repositorio local, siendo el siguiente comando `git add .` el que hemos usado.

![Comando GIT ADD](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-2.PNG)

## Actividad 4 - Ejercicio 5:

En este apartado vamos a hacer un push a nuestro repositorio remoto, pero en primer lugar a usar el comando `git remote remove origin` para desconectarnos del repositorio remoto de la carpeta que hemos importado anteriormente.
Luego hacemos `get remote add origin https://github.com/juandiegojp/refuerzo-JDJP.git`, `git branch -M main` y, finalmente, hacemos el push a nuestro repositorio con `git push -u origin main`

![Comando GIT REMOTE](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-3.PNG)


## Actividad 4 - Ejercicio 6:

En este apartado hemos creado la carpeta `privada/` y el fichero `privado` como podemos ver en la siguiente imagen:
![ARCHIVO-CARPETA](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-4.PNG)

Seguidamente, creamos un fichero `.gitignore` y añadiremos los archivos que no queremos que pase Git.
![.gitignore](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-5.PNG)
![GIT STATUS](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-6.PNG)


## Actividad 4 - Ejercicio 8:

En este apartado he usado `git status` en primer lugar. Luego he usado `git add .` para añadir los nuevos archivos/modificaciones.
Seguidamente usamos el comando `git commit -m 'TAG'` y finalmente `git tag v0.1`.
![Comandos varios](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-7.PNG)

Con el comando `git show` podemos ver la información de la etiqueta junto con el _commit_ que está etiquetado.
![Comando GIT SHOW](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-8.PNG)


## Actividad 4 - Ejercicio 9:
Para subir un tag, junto con el resto de cambios, he introduccido el comando `git push -u origin main --tags`.
![GIT PUSH con TAG](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act4-9.PNG)


## Actividad 4 - Ejercicio 12:
_Tabla de compañeros_

Nombre | GITHUB
------ | --------
Jesús Manuel Espinar Ocaña | https://github.com/jesus-eo
Miguel Guitiérrez | https://github.com/MiguelGutierrezParejo
Francisco Fernandez | https://github.com/franciscomfm

## Actividad 5 - Ejercicio 1:
En este apartado en primer lugar he usado el comando `git branch` para ver las ramas que hay en mi proyecto creadas. A continuación, `git branch v0.2` para crear la rama que nos pide el ejercicio y, de nuevo, `git branch`para comprobar que hemos creado correctamente la rama.

Luego, para cambiar de rama, he usado el comando `git checkout v0.2` y, como se puede ver en la imagen de abajo, aparece el mensaje de que nos hemos cambiado de rama. Podemos ver comprobar nuevamente con el comando `git branch` que nos encontramos en la rama _v0.2_ ya que aparece junto con un __*__.

![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-1.PNG)
![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-1B.PNG)

## Actividad 5 - Ejercicio 2:
En este apartado hemos añadido el fichero `2.txt` a la rama `v0.2`

![A5-2](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-2.PNG)

## Actividad 5 - Ejercicio 3:
En esta actividad hemos creado una rama remota, dicha rama la hemos creado con el comando `get fetch origin`.
![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-3.PNG)

Seguidamente, usamos el comando `git push origin v0.2`:
![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-3B.PNG)

## Actividad 5 - Ejercicio 4:
En primer lugar nos posicionamos en la rama mas con el comando `git checkout main`. Luego hacemos el merge con el comando `git merge origin/v0.2`
![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-4.PNG)
![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-4B.PNG)

## Actividad 5 - Ejercicio 5:
Añadimos al fichero `1.txt` _hola_ y hacemos commit con el comando `git commit -m "  "`.
![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-5A.PNG)

Pasamos ahora a la rama `v0.2` y ponemos `Adios` en el fichero `1.txt` y hacemos commit con el comando `git commit -m "  "`.

Finalmente, volvemos a la rama `main` con el comando `git checkout main` y hacemos el `merge`. Como podemos ver, nos aparece el mensaje siguiente de que hay un conflicto al hacer el merge:
![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-5C.PNG)
![GIT BRANCH](https://github.com/juandiegojp/refuerzo-JDJP/blob/main/img/act5-5CC.PNG)

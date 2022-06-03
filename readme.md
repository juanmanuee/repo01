# Creación de un repositorio

Comenzaremos iniciando git bash y nos posicionaremos donde queremos tener el repositorio, a continuación introduciremos los siguientes comandos  

#### Este comando creara el repositorio
>git init repo01  
#### Este comando nos movera dentro del repositorio  
>cd repo01
***
#### A continuación añadiremos este documento readme.md dentro del repositorio, e introduciremos el siguiente comando

#### Este comando añadira los cambios dentro de readme.md para el siguiente commit
>git add readme.md

#### Este comando recoge todos los archivos añadidos para realizarles el commit, aparte se puede añadir un comentario

>git commit -m "creo markdown ej1"
***
#### Por ultimo, para poder hacer push al repositorio deberemos crear (si no esta creado ya), el repositorio en github, y dependiendo del enlace al repositorio introcudir los siguientes comandos
>git remote add origin https://github.com/juanmanuee/repo01.git
#### Luego
>git branch -M main
#### Y finalmente realizaremos el push para subir o actualizar nuestro repositorio de github
>git push -u origin main
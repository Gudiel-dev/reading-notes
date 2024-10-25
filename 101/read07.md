# READ 07: Control de Versiones

![Git](https://ositcom.com/static/images/images/git-blog-header_1.png)

## 1 ¿Qué es el control de versiones?
  Es un sistema por el cual podemos raestrear y administrar cambios realizados en el código fuente
	de un proyecto. Así mismo, nos permite trabajar de manera ordenada colaborando en equipo. De ocurrir 
	problema alguno, se puede regresar a una versión previa.
	
## 2 ¿Qué es “clone” en Git?
	
  Usamos el clone para crear una copia completa de un repositorio GIT de manera local. En otras palabras,
	descargamos el repositorio localmente para su manipulación sin que esto afecte el repositorio original

## 3 ¿Cuál es el comando para agregar los archivos modificados a la zona de preparación?


- `git add <nombre de archivo>` para un archivo
- `git add . `para añadir todos los archivos. El ' . ' hace referencia al directorio actual



## 4 ¿Cuál es el comando para enviar la captura de los archivos modificados a Github?

  El comando usado para enviar la caputra de los archivos modificados es 	`git push` pero necesitamos un commit previamente  `git commit -m "descripción de cambios"` por último el `git push` para que sea publicado
	
s
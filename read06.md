# Reading 06

## 1 ¿Qué hacen los siguientes comandos?

- **pwd** = este comando te brinda la ruta del directorio donde se encuentra el usuario-
- **ls** = este comando nos muesta la lista de archivos y directorios en la ubicación actual *(directorio)*.
- **cd** = este comando nos permite movernos entre directorios. s
- **"cd  "** = sin argumento, nos lleva a home. 
- **"cd nombre_directorio"** = nos lleva a un directorio seleccionado
- **"cd .."** = nos lleva al padre del directorio actual
- **"cd /"** = nos lleva al root
- **mkdir** = este comando nos permite crear directorios *(carpetas)*
- **touch** = este comando nos permite crear archivos vacíos o para actualizar la fecha de modificación para propósito de respaldo

## 2 ¿Puedes explicar qué sucede en el siguiente escenario si ingresas estos comandos y argumentos en la línea de comandos? (Los argumentos son instrucciones adicionales dadas a un comando).

- **cd projects:** Nos lleva dentro del directorio projects.
	
- **mkdir new-project:** Crea el directorio *"new-project"*.
	
- **touch new-project/newfile.md:** Crea un archivo md vacío dentro del directorio *'new-project'*
- **cd .. :** Nos mueve al directorio padre del directorio actual. Un paso atrás del directorio en uso.
	
- **ls projects/new-project:** Esta línea de comando nos muestra el contenido del directorio *'new-project'*  que está dentro del directorio *'projects'* 
	
## 3 ¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.

- **ls -a**
- **ls -a /path/directory**

El comando ls nos dará la lista de elementos dentro de un directorio, pero si le añadimos '-a' (all)
también incluirá los directorios '.' '..'
	
	

# *RESPUESTAS*

1. ¿Qué es git?

Es el sistema controlador de versiones mas popular. Controla y administra las distintas versiones de un programa.

2. ¿Por qué queremos utilizar git?

Para controlar el proyecto que realizamos a medida que va creciendo con el tiempo(cambiando archivos,cambiando codigo, etc). También, poder ver los cambios,revertirlos y ver las diferentes versiones anteriores.

3. ¿Qué es el bash que instala git?

Es una consola con mejores funcionalidades que trae todos los conceptos de unix (Linux y Mac).

4. Describa los estados (working directory, staging area, repository)

working directory: es donde se trabajamos con todos nuestro archivos. Cuando se termina la version se pasan al "staging area".

staging area: agregamos todos los archivos que preparados para el guardado.

repository: se guardar el cambio total de la versión.

5. Describa el flujo para crear un nuevo repositorio git.

Primero se abre el bash, dentro nos dirigimos a la carperta que deseamos crear el repositorio mediante "cd" + "nombreDeLaCarpeta" y escribimos el comando "git init".


6. Describa el flujo para agregar un archivo simple al repositorio.

Se agrega el archivo al repositorio mediante "git add " + "nombreDelArchivo". y luego se guarda la version con "git commit".

7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.

Despues de cambiar el archivo, se prepara la modificación con "gid add" y se guarda los cambios con "git commit"
8. ¿Cómo hago para ignorar un archivo o carpeta?

Se crea un archivo en la carpeta del proyecto llamado ".gitignore" y dentro del archivo se escribe el nombre de todos los archivos que querramos ignorar.
9. Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.

Es para ver en que version estamos y para crear una versión alternativa de la principal con todos sus archivos y agregar mas archivos o modificarlos, sin alterar la principal. Por ejemplo:
Escribimos "git branch NombreVersion" para crear una versión alternativa, luego escribimos "gir checkout NombreVersion" para movernos dentro de esa versión.
10. ¿Qué hago con `git add .`?

Agregamos los archivos que estan el "Wonking directory" al "staging area", o sea, los preparamos para ser guardados.
11. ¿Cómo cambiamos de un branch a otro?

Escribimos y ejecutamos "git checkout NombreDeLaVersion" para cambiar a la version que querramos. Para confimar en que versión estamos luego escribimos "git branch" y nos saldra en color en verde.
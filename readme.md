#Respuestas a las preguntas 
##El ejercicio 1 


- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
**Respuesta** `git reset —hard HEAD~1`  para deshacer el último commit y dejar el working copy vacío.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
**Respuesta** `git reflog`  para ubicar el SHA ID del comentario anterior para situar nuestro puntero HEAD nuevamente, agregar y comentar los cambios para rehacer el punto 11 o regresar, descartar los cambios con ‘git restore’ y comentar. 

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
**Respuesta** no porque los conflictos se cargan cuando modificas en las mismas lineas dos archivos en do ramas distintas y tratas de fusionarlos, aquí tocamos el archivo git-nuestro.md en lineas distintas una sola vez.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? **Respuesta** No, porque actualizamos el archivo completamente en la nueva rama htmlify y en styles estaba una versión anterior que no interfería en las lineas que modificamos.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? **Respuesta** No, 

- ¿Qué comando o comandos utilizaste en el paso 25?
**Respuesta** `git log —graph —pretty`

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

- ¿Qué comando o comandos utilizaste en el paso 27?
**Respuesta** git reset hard HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
**Respuesta** `git restore git-nuestro.md`

- ¿Qué comando o comandos utilizaste en el paso 29?
**Respuesta** `git branch -D title`

- ¿Qué comando o comandos utilizaste en el paso 30?
**Respuesta** `git reflog` `git checkout 2612a8f` `git restore` `git merge title` 


- ¿Qué comando o comandos usaste en el paso 32?
**Respuesta** `git reflog` `git check out a12eb7e` `git checkout master` 

- ¿Qué comando o comandos usaste en el punto 33?
**Respuesta** `git reset HEAD@{10}`


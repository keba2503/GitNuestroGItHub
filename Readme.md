- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1

Para volver al commit anterior, se pierden los cambios echos en el ultimo commit.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

**git reflog** 

Para ver identificador del commit en el que realice cambios y regresar a el

**git reset --hard (id)**

Para ir al commit que tiene los cambios

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No causo ningun conflicto, no habian cambios desiguales en el archivo comun

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si causo conflicto, los archivos fueron editados en las mismas lineas.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No genero conflicto, no hubo ediciones diferentes en archivos comunes

- ¿Qué comando o comandos utilizaste en el paso 25?
git config alias.graph "log --graph --decorate --pretty=oneline"

git graph

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si porque pueden listarse los commits de una forma que master los haya absorbido a todos sin tener una rama adicional 

- ¿Qué comando o comandos utilizaste en el paso 27?
git reflog

git reset --hard (id)

- ¿Qué comando o comandos utilizaste en el paso 28?

git reset --hard HEAD~1


- ¿Qué comando o comandos utilizaste en el paso 29?
git branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?
git reflog

git reset --hard (id)

para ir al id donde hice el merge

- ¿Qué comando o comandos usaste en el paso 32?
git reflog

git checkout (id)

- ¿Qué comando o comandos usaste en el punto 33?

git reflog 

git checkout git checkout (id)
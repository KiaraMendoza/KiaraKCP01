# Hecho por Kiara Mendoza García
### Preguntas y respuestas de la práctica sobre Git, Github y Sourcetree.

- ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
El comando git reset --hard HEAD~1, pues nos devolvería al anterior commit con el working copy que teníamos antes.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Los comandos git reflog y git reset --hard hash-del-commit, porque así nos situamos rápidamente y sin muchas complicaciones en el commit deseado.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué? 
No, porque los commits del master ya los tenía la rama styled.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 
Sí, porque el archivo git-nuestro.md se modificó en otro commit de la rama htmlify.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 
No hubo conflicto porque master actualizó sus commits con los de la rama styled, quedándose con los últimos cambios realizados en el archivo git-nuestro.md.

- ¿Qué comando o comandos utilizaste en el paso 25? 
El comando git log --graph --pretty=oneline.

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 
Sí, porque el commit de title está en la misma ‘línea’ que los commits de master y ningún commit se quedaría suelto.

- ¿Qué comando o comandos utilizaste en el paso 27? 
El comando git reset HEAD~1.

- ¿Qué comando o comandos utilizaste en el paso 28? 
El comando git restore git-nuestro.md.

- ¿Qué comando o comandos utilizaste en el paso 29? 
El comando git branch -D title. (Al dejar un commit suelto, debemos utilizar el -D en lugar de -d)

- ¿Qué comando o comandos utilizaste en el paso 30? 
El comando git reset --hard hash-commit.

- ¿Qué comando o comandos usaste en el paso 32? 
Los comandos git log --graph --pretty=oneline, pillamos hash del primer commit, git checkout hash-commit.

- ¿Qué comando o comandos usaste en el punto 33? 
El comando git checkout master, ya que la rama se encuentra al final.

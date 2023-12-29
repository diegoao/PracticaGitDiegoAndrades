## Ejecución de pasos práctica

**Paso 11->** tengo que ejecutar  1º `git reset HEAD"~"1` y luego `git restore git-nuestro.md` con estos dos pasos restauro al commit anterior y luego los datos del working copy.

**Paso 12->**  1º ejecuto el comando `git reflog` y me apunto el nombre del commit al que quiero volver y ejecuto `git reset—hard 811a543` que es el nombre del commit que quiero rehacer. Con esto me restaura el working copy.

**Paso 13->**  1º desde la rama styled realizo `git merge` con la rama main no me causó ningún conflicto me indico que los cambios estaban realizados.

**Paso 19->**  me muevo a la rama styled haciendo `git checkout styled`y luego hago `git merge htmlify`, me da conflictos por lo que para solucionarlo desde el editor de código le digo que me quedo con los cambios de styled como indica el ejercicio, luego realizo `git add git-nuestro.md` y un commit para finalizar el merge.

**Paso 21->**  me cambio a la rama main y realizo `git merge styled`,  me indica que hay conflictos lo soluciono desde el terminar ejecutando un merge "ort" strategy.

**Paso 25->**  `git log --graph` para dibujar el gráfico en el terminal.

**Paso 26->**  Utilizo el comando `git merge --no-ff title` para hacer merge de los cambios y añadir titulo a main. En este caso si podria ser fast forward. Porque cuando hemos creado la rama title teniamos en la rama main todos los cambios incluidos de las otras ramas por lo que no haría falta crear otra difulcación. 

**Paso 27->**  Utilizo el comando `git reset HEAD"~"1`.

**Paso 28->**   Utilizo el comando `git restore git-nuestro.md`.

**Paso 29->**  primero ejecuto `git branch -r` y como no la hemos subido al repositorio seguidamente ejecuto el comando `git branch -D title`. Lo ejecuto con la D mayúscula porque como he desecho el merge git me da un error si utilizo la d minúscula porque me indica que hay cambios que no han terminado de fusionar. Lo fuerzo a borrar poniéndola mayúscula.

**Paso 30->**  Busco ejecutando `git reflog` el id del merge realizado y ejecutando el comando `git reset —- hard 422c472` vuelvo a el restaurando el working copy.

**Paso 32->**   Utilizo el comando `git reset 47824a4` y me llevo HEAD al commit inicial.

**Paso 33->**   Utilizo el comando `git reflog + git reset 422c472`.

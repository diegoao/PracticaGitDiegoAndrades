## Ejecución de pasos práctica
**Paso 11 ->** tengo que ejecutar  1º git reset HEAD~1 y luego git restore git-nuestro.md
Paso 12 1º ejecuto el comando git reflog y me apunto el nombre del commit al que quiero volver y ejecuto git reset—hard 811a543 que es el nombre del commit que quiero rehacer. Con esto me restaura el working copy
Paso 13 º desde la rama styles realizo git merge con la rama main
Paso 19 me muevo a la rama styled haciendo git checkout styled y luego hago git merge htmlify, me da conflictos por lo que para solucionarlo desde el editor de código le digo que me quedo con los cambios de styled como indica el ejercicio, luego realizo git add git-nuestro.md
Paso 21 me cambio a la rama main y realizo git merge styled.
Paso 25 git log --graph para dibujar el gráfico en el terminal
Paso 26 git merge --no-ff title
Paso 27 git reset HEAD~1
Paso 28 git restore git-nuestro.md
Paso 29 primero ejecuto git branch -r y como no la hemos subido al repositorio seguidamente ejecuto el comando git branch -D title. Lo ejecuto con la D mayúscula porque como he desecho el merge git me da un error si utilizo la d minúscula porque me indica que hay cambios que no han terminado de fusionar. Lo fuerzo a borrar poniéndola mayúscula
Paso 30 Busco ejecutando el reflog el id del merge realizado y ejecutando el comando git reseteada —- hard 422c472 vuelvo a el restaurando el working copy
Paso 32  git reset 47824a4 y me llevo HEAD al commit inicial
Paso 33 - git reflog + git reset 422c472

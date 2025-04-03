# Manual de git 1r DAM

## Instruccions bàsiques

- **git init** – iniciar un repositorio en una carpeta vacia
- **git clone** – descargar un repositorio en el equipo local
- **git branch** – comprovar las ramas que tienes
- **git branch ‘name’** – crear una rama nueva
- **git branch -d ‘algo’** – borra una rama
- **git checkout -b ‘algo’** – crea la rama y la cambia automaticamente
- **git --no-pager log --oneline --all --graph** - muestra el log del repositorio
- **git switch ‘rama’** – cambiar de rama
- **git merge ‘algo’** – combinar dos ramas
- **git add .** - agrega todos los archivos modificados o nuevos al área de preparación
- **git commit -m “algo”** – guarda los cambios en el historioal del repositorio
- **git push origin main** – sube los commits locales a un repositorio remoto
- **git reset –hard ‘comit’** – vuelve a cargar los cambios de un commit
- **git stash list** – guardar los cambios sin hacer falta que hagas un commit
- **git stash pop**- devuelve los cambios guardados en el stash

## Com funciona rebase

- **git rebase** – reescribe el historial de commits para que parezca que se han hecho en una sola rama
- **git rebase -i HEAD~n** – reescribe el historial de commits para que parezca que se han hecho en una sola rama, pero te deja elegir los commits que quieres modificar
- **git rebase --continue** – continua el rebase después de resolver los conflictos
- **git rebase --abort** – cancela el rebase y vuelve al estado anterior
- **git rebase --skip** – salta el commit que ha dado conflicto y continua con el rebase

## Com fer git squash

- **git rebase -i HEAD~n** – reescribe el historial de commits para que parezca que se han hecho en una sola rama, pero te deja elegir los commits que quieres modificar
- **pick** – manté el commit tal cual
- **squash** – combina el commit amb el anterior
- **fixup** – combina el commit amb el anterior i no et deixa modificar el missatge del commit
- **edit** – modifica el commit i et deixa modificar el missatge del commit

## Com funciona cherry-pick

- **git cherry-pick ‘commit’** – aplica un commit de otra rama a la rama actual
- **git cherry-pick --continue** – continua el cherry-pick después de resolver los conflictos
- **git cherry-pick --abort** – cancela el cherry-pick y vuelve al estado anterior
- **git cherry-pick --skip** – salta el commit que ha dado conflicto y continua con el cherry-pick
- **git cherry-pick -n ‘commit’** – aplica un commit de otra rama a la rama actual, pero no hace un commit
- **git cherry-pick -x ‘commit’** – aplica un commit de otra rama a la rama actual, pero añade el hash del commit original al mensaje del commit
- **git cherry-pick -e ‘commit’** – aplica un commit de otra rama a la rama actual, pero te deja editar el mensaje del commit

## Com funciona bisect

- **git bisect**

## Què és reflog

Git realitza el seguiment de les actualitzacions a l'extrem de les branques a través d'un mecanisme anomenat registres de referències o "reflogs". Moltes de les ordres de Git accepten un paràmetre per especificar una referència o "ref", que és un punter a una confirmació.

## Digues la teva opinió

Em pots escriure a l'adreça blablabla@gmail.com


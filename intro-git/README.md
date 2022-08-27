### INTRODUCTION TO GIT

### Basics Commands

- <strong>git init</strong> (adicionar el proyecto al controlador de versiones git)
- <strong>git add .</strong> <i>or</i> <strong>git add archivo</strong> (añadir archivos al stage area)
- <strong>git status</strong> (visualizar los archivos que están en el stage area)
- <strong>git commit -m "comentario"</strong> (guardar los archivos que están en el stage area)
- <strong>git log</strong> (visualizar los commits realizados en el proyecto)
- <strong>git push origin <i>rama</i></strong> (subir los cambios al repositorio)
- <strong>git log --oneline</strong> (visualizar commits y ramas)
- <strong>git branch nombre-rama</strong> (crear rama)
- <strong>git branch</strong> (visualizar ramas del proyecto y donde estamos ubicados)
- <strong>git checkout nombre-rama</strong> (cambiar de rama)
- <strong>git merge nombre-rama</strong> (unir cambios de dos ramas)
- <strong>git branch -d nombre-rama</strong> (eliminar rama)
- <strong>git clone <i>uri-repository</i></strong> (clonar repositorio)
- <strong>git pull origin nombre-rama</strong> (traer cambios de github)
- <strong>git push origin -d nombre-rama</strong> (eliminar una rama de github)
- <strong>git reset --hard</strong> (Devolverse al último commit. Nota: Se elimina el commit actual)
- <strong>git reset --hard <i>id-commit</i></strong> (Devolverse a un commit en específico. Nota: Se elimina el último commit)
- <strong>git revert commit id-commit</strong> (Devolverse a un commit sin eliminar el actual)
- <strong>git commit --amend -m "nuevo comentario"</strong> (unir cambios al commit anterior)
- <strong>git commit --amend --no-edit </strong> (guardar cambios en el mismo commit anterior sin editar el comentario)

### Tools

- Fig -> Auto complete
- Oh-my-zsh

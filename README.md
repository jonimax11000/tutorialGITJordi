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
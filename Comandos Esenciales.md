git init

git ignore (crear archivo para ignorar archivos que no necesitamos que se suban) -Aunque no usar un archivo .gitignore puede no parecer un problema al principio, a medida que el proyecto crece, la falta de un .gitignore puede convertirse en un dolor de cabeza. Por lo tanto, es una buena práctica configurar un archivo .gitignore desde el principio para evitar problemas en el futuro.

git add .

git commit -m ""

git log (versiones de commits)

git status

git diff (diferentes versiones)

git reset (descartar cambios) --hard (commit): vuelve a un estado determinado / podemos ir hacia atrá o hacia adelante

git reflog (se vuelven a ver los commits de lo eliminado): el historial completo de interacciones

git tag: ej: git tag clase_1 (en ese punto donde estamos hacemos una marca)

git branch --- (crea una rama) -lo vemos con git log: git branch rama1 // la rama se crea a partir del commit donde estamos

git switch ---: git switch rama1

git switch master (vuelve a master)

git log --graph --oneline --all (vemos el tree, las ramas)

git branch: me da con un * dónde estamos situados

git checkout nombre_de_la_rama_actual  # Cambia a la rama actual (donde está el HEAD)
git merge rama1                       # Fusiona los cambios de rama1 en la rama actual

git branch -d (nombre rama): elimina rama que ya no se usa
git branch -d rama1 ---> deleted branch rama1

git remote add origin git@github.com:MLopezCastro/Git---GitHub-.git (para emparejar remoto desde local)
git push --set-upstream origin master (para subir siempre al remoto, master se hace una sola vez) (Esto hará dos cosas:
                                                                                                   Empujará tu rama master al repositorio remoto en GitHub.
                                                                                                   Configurará la rama master para rastrear el repositorio remoto, 
                                                                                                    por lo que en el futuro podrás simplemente usar git push sin especificar la rama.)

git clone (url) Clona el repositorio remoto en nuestro ordenador




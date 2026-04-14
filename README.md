# Guía comunal de conceptos de Git

En esta guía se presentan los conceptos fundamentales de Git, una herramienta de control de versiones ampliamente utilizada en el desarrollo de software. Esta guía está diseñada para ayudar a los desarrolladores a comprender y utilizar Git de manera efectiva en sus proyectos.

## Comandos básicos

git init - Inicializa un repositorio de GIT.(Crea un repositorio vacío)

git add - Añade los archivos que hayas creado al área de preparación.Normalmente se pone git add . para que coja todos los cambios que se hayan producido en esa carpeta (Cuando tu creas un archivo nuevo, lo "añades a git")

git commit -m "mensaje" - Mete los cambios realizados en el repositorio local y los registra con el mensaje que tú pongas, que normalmente suele ser explicativo del cambio que has realizado.

git log - Muestra el historial de commits realizados en el repositorio.

git status - Muestra el estado actual del repositorio, incluyendo los archivos modificados, los archivos en el área de preparación y los archivos sin seguimiento.

git push -  Sube los cambios (commits) realizados en tu repositorio local a un repositorio remoto.

git pull - Descarga los cambios realizados en el repositorio remoto y los fusiona con tu repositorio local.

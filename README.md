¡Hola Odin!

Hoja de trucos
Esta es una lista de referencia de los comandos Git más utilizados. (Puede considerar marcar esta página práctica.) Intenta familiarizarte con los comandos para que eventualmente puedas recordarlos a todos:

Comandos relacionados con un repositorio remoto:
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git
git push o git push origin main (Ambos logran el mismo objetivo en este contexto)
Comandos relacionados con el flujo de trabajo:
git add .
git commit -m "A message describing what you have done to make this snapshot different"
Comandos relacionados con el estado de comprobación o el historial de registros
git status
git log
La sintaxis básica de Git es program | action | destination.

Por ejemplo,

git add . se lee como git | add | ., donde el período representa todo en el directorio actual;
git commit -m "message" se lee como git | commit -m | "message"; y
git status se lee como git | status | (no destination).
Hola Edidson

Hay muchas formas de crear un archivo usando BASH.

usando el toque touch newFile.txt solo crea.
usando echo echo > newFile.txt solo crea.
usando cat cat > newFile.txt crea y puede comenzar a agregar archivos.
usando vim vim newFile.txt crea y puede comenzar a editar el archivo.

Además, la extensión .txt es solo por conveniencia y categorización. Algunos editores ven la extensión para formatear los datos, pero para un txt no hay diferencia.

Después de crear el archivo, agréguelo al repositorio de git.

git add newFile.txt
git commit -m "added new file"


# TextCommands
Epale buena esa crack! :D, Repositorio con la lista de comandos que nesecito para git, git-hub.

Pasos Para la sincronizacion de mi git_pc con mi Git_Hub.

//----------//----------/Identificación y registro/----------//----------//

1-) Crear una carpeta llamada ".ssh". en user/user/.ssh

2-) Identificar nuestro user name --> git config --global user.name "CarlosCalderon01"

3-) Identificar nuestro correo eléct. --> git config --global user.email "Carlos.Calderon01@Outlook.com"

4-) Crear clave SSH, comprueba si ya tengo claves. --> ls -al ~/.ssh 

5-) Generar una nueva clase SSH --> ssh-keygen -t ed25519 -C "Carlos.Calderon01@Outlook.com"

6-) primero le doy el nombre a la llave, luego ingreso la contraseña, y la confirmo.

7-) buscar la clave generada e ir al settings de git y pegarla en un nuevo SSH

//----------//----------//----------//----------//







//----------//Lista De Comandos Basicos De Para La Consola Git Bash//----------//

pwd: nos muestra la carpeta actual en la que nos encontramos.
mkdir: nos permite crear carpetas, p. ej. mkdir NuevaCarpeta
touch: nos permite crear archivos nuevos, p.ej. touch NuevoArchivo.txt
cat: nos permite ver el contenido de un archivo, p.ej. cat NuevoArchivo.txt
cd: nos permite cambiarnos de carpeta, p.ej. cd NuevaCarpeta.
cd .. : nos permite regresar al directorio o carpeta anterior.
cd o cd ~: nos lleva a la ruta del usuario.
cd /c: nos vamos al disco C:/.
cd -: nos lleva directamente al ultimo directorio visitado.
ls: nos permite ver los archivos de la carpeta donde estamos actualmente.
ls -l: Ver todos los archivos como una lista en donde incluye el usuario, grupo, permisos sobre el archivo, tamaño, fecha y hora de creación.
ls -lh: Muestra la misma información que ls-l pero con unidades de tamaño, es decir, kb o mb.
ls-R: muestra el contenido de todos los sudirectorios de forma recursiva.
ls -S Ordena los resultados por tamaño de archivo.
rm: Nos permite borrar un archivo o carpeta ej: rm NuevoArchivo.txt
rmdir “nombre del directorio”/: borrar un directorio: Solo funciona con directorios vacíos.
rm -r ‘nombre de la carpeta’ :me permite eliminar la carpeta y los archivos dentro de ella de forma recursiva.
cp “nombre del archivo que quremos copiar” “nombre del directorio a donde lo queremos copiar”: nos permite copiar un archivo.
mv “el directorio de donde queremos mover/el nombre del archivo” “el directorio hacia donde lo queremos mover”: nos permite mover un archivo.
clear: nos permite limpiar la pantalla.
history: ver los últimos comandos que ejecutamos y un número especial con el que podemos volver a repetir el comando.

//----------//Lista De Comandos Basicos De Git Bash//----------//


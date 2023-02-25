COMANDOS DE GIT:

>>>Todos estos comandos se deben ejecutar situados en el directorio del proyecto



Añadir proyecto a seguimiento de GIT:

   > git init /ruta/proyecto


Añadir carpeta a seguimiento de GIT:

   > git add fichero


Para observar el estado de nuestros ficheros y documentos del proyecto de git (no seguimiento, seguimiento, guardado):

   > git status -s


Crear primera versión del proyecto y guardar una copia de respaldo local:

   > git commit -m "TituloDelCambioRealizado)


Para cambiar el titulo de un commit (por si nos hemos equivocado al escribirlo):

   > git commit --amend


Mostrar todo el historial de versiones, con sus títulos y código de la instatánea:

   > git log --oneline


Retornar a una versión anterior del proyecto (guardadas con commit):

   > git reset --hard CodInstantanea


SUBIR PROYECTO A UN REPOSITORIO DE GITHUB:

1. Login en la web de GitHub e iniciamos sesión con nuestro usuario.
2. En la web de GitHub pulsar la opción de "Create a repository"
3. Al pulsar dicha opción nos indicará los comandos necesarios para subir el proyecto y nos solicitará nombre y descripción del proyecto. El comando para subir un proyecto a github es:

   > git remote add origin https://github.com/alvarodRM/EscenarioHackingEtico.git

Si queremos actualizar los cambios de local al repositorio de GitHub (remoto):

   > git push

Si queremos actualizar los cambios del repositorio de GitHub (remoto) al repositorio local:

   > git pull
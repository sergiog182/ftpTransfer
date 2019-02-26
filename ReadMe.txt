Proyecto manejo de archivos xml y json
=========================================

Colocar los archivos que se encuentran en la carpeta files en la carpteta del ftp configurado en el archivo config.properties

El resultado del procesamiento se verá en las rutas configuradas en el archivo config.properties (outgoing)

Para correr el proyecto, desde consola ejecutar:

    mvn celan camel:run

Desde JBoss developer studio, crear un perfil de ejecución:

	clean camel:run
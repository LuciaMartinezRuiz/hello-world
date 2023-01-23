                                        Práctia1
Lucía Martínez Ruiz
3ºB GITT+BA

La práctica1 consiste en entender Github y trabajar con algunos de sus comandos.
Para comenzar, se realiza un fork del repositorio: https://github.com/gitt-3-pat/hello-world
A continuación se explicarán los comandos y su uso:
Fork: se baja el repositorio para poder editarlo.


Git clone: no se va a poder editar porque el dueño del documento no nos permite hacerlo. Se trabajaría sobre el repositorio del dueño. Se hace en el tmp para probar el clone. En el directorio de workspaces ya se ha clonado, pero aquí sí se pueden hacer ediciones del documento.


El resto de comandos los hacemos en el workspaces porque ya tenemos ahí el repositorio clonado.

Git status: una vez realizado los cambios creando un nuevo txt, se observan cambios en el directorio de workspaces/hello-world/.
 

Git add: Los cambios en git se hacen en tres pasos. Primero se añaden a un borrador con este comando. Si se pone un “.” al final del comando quiere decir que se desea añadir todas las modificaciones de todos los documentos creados. Si se quiere añadir únicamente un documento específico, se pone el nombre del mismo en vez del “.”.
 

Git commit: cuando se tiene seguridad sobre los cambios, con el comando commit se indica. Se queda en el ordenador local y solamente el editor del documento puede verlo.
 

Git push: se suben los archivos al github para que los demás usuarios puedan acceder a ellos y verlos. Para indicar el repositorio y la rama a donde se quiere hacer el push, se deben añadir dos campos adicionales. “Origin” lo escoge por defecto y la rama “main” es donde se quieren guardar los cambios efectuados.
 

Git checkout: actualiza los archivos para que las versiones coincidan. Al especificar -b, se crea una nueva rama y se cambia ella al instante.
 
Si se especifica “main”, que es la rama que estaba a creada, se vuelve a cambiar al main:
 
Para comprobar que existen estas dos ramas y que “feature/1” se ha creado correctamente, se observa lo siguiente:
 






Instalaciones:
Maven:  

Java: 

Intellij:

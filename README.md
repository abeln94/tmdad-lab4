# Creación de cuenta en OpenShift/Redhat ✔
-	Sin complicaciones
# Archivos war de la práctica 0 y 3 ✔
-	Necesario añadir el plugin “apply plugin: ‘war’” a gradle y recompilar
# Crear dominio para ejecutar aplicaciones ✔
-	El enlace está roto, pero desde la consola de openshift las instrucciones están claras
-	Se ha creado un proyecto
# Crea una instancia de cómputo para desplegar una app Web ?
-	Enlace roto, no se ha encontrado destino alternativo
-	Se asume wildfly y se añade al proyecto creado
# Desplegar el war de la práctica 0 ❌
-	Se han seguido las instrucciones del enlace
-	Se ha subido el fichero war del lab0 al proyecto creado
-	A pesar de no obtener ningún error, wildfly está activo (http://lab4-lab0-lab4.7e14.starter-us-west-2.openshiftapps.com/) pero la aplicación no existe en ningún endpoint (debería estar en http://lab4-lab0-lab4.7e14.starter-us-west-2.openshiftapps.com/lab0-2018)
# Desplegar el war de la práctica 3 ❌
-	Al utilizar rabbitMQ en la red, no ha sido necesario ejecutar en local
-	Se han seguido las instrucciones del enlace anterior (como desplegar un war)
-	Se ha subido el fichero war del lab3 al proyecto creado
-	A pesar de no obtener ningún error, wildfly está activo (http://lab4-lab3-lab4.7e14.starter-us-west-2.openshiftapps.com) pero la aplicación no existe en ningún endpoint (debería estar en http://lab4-lab3-lab4.7e14.starter-us-west-2.openshiftapps.com/lab3-2018)

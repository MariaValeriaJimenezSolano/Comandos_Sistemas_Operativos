# Comandos_Sistemas_Operativos

Bitácora de comandos para la clase de Sistemas Operativos

 - María Valeria Jiménez Solano

## UBUNTU:

| **Comando**      | Descripción                                   | Ejemplo de uso |
|     :---:        |    :---:                                      |       :---:    |
| sudo apt upgrade | Actualizaciones de seguridad de Ubuntu (es el equivalente a Windows updates) | Actualizar paquetes a la nueva versión | 
| sudo apt update  | Actualizaciones de sistema | Actualiza la caché de los paquetes (para saber qué versiones de paquetes se pueden instalar o actualizar) | 
| sudo apt install | Permite instalar una aplicación en el sistema | sudo apt install obs-studio C: instala el programa de OBS Studio para grabar videos y streamings en la pc | 
| sudo ap          | Hace un display de las posibles opciones de comandos | Si no se recuerda el comando que se desea ejecutar | 
| clear            | Limpia la pantalla de todos los comandos que se han ejecutado anteriormente | Se puede usar en el caso de necesitar más espacio para seguir navegando en la terminal | 
| Ctrl + C         | Cancela el comando que se está corriendo en ese momento | Si se corrió un proceso no deseado | 
| sudo apt search  | Busca un paquete del repositorio de Ubuntu   | sudo apt search neofetch: busca este paquete en específico | 
| sudo rm          | Borra ficheros sin argumentos, es decir, que estén vacíos | Liberar espacio eiminando ficheros sin información | 
| ls               | Muestra el contenido de las carpetas (requiere de instalación antes de correrlo) | ls -Personal: muestra los archivos y carpetas dentro del folder de Personal | 
| top              | Muestra una lista de procesos en tiempo real  | Si se desean consultar absolutamente todos los procesos de la computadora, mostrando características como qué tanta memoria ocupan, entre otras |
| htop             | Misma funcionalidad que top, solamente que con una interfaz más agradable al usuario (requiere de instalación antes de correrlo)               | Mismo ejemplo que top, consultar procesos |
| ps -aux          | Muestra la lista de procesos que se están corriendo | ps -aux: 54 178 Firefox |
| sudo kill -9 xxxx | Detiene un proceso en específico, se deben de sustituir las x por el ID del proceso, el cual se extrae del comando anterior            | sudo kill -9 54178: cierra Firefox |
| pstree           | Muestra un árbol de procesos                  | Si se desean observar todos los descendientes de un proceso en particular, para evitar buscar las relaciones entre los diversos procesos de manera manual |
| su               | Super user                                   | Se usa para obtener permisos de root para operaciones administrativas, sin tener que salir y reentrar al sistema |   
| ip a             | Verifica la dirección IP de mi equipo        | Si se quiere conocer información de la red IP |  
| mkdir            | Crea una carpeta                             | mkdir tmp/Sistemas: crea la carpeta Sistemas dentro de tmp | 
| nano (nobre de archivo.formato)| Crea un editor de texto en consola (para salir del modo de edición se usa Ctrl + X) | nano informe.txt: crea un bloc de notas llamado informe |  
| cat (nobre de archivo.formato) | Muestra el contenido de un archivo | cat informe.txt: hace un display de todos los datos que tenga este archivo |  
| head -n 10 (ruta archivo)      | Permite ver las primeras 10 filas de un archivo | Reduce la visualización de texto de la línea de comandos |
| tail -n 1 (ruta archivo)       | Se utiliza para mostrar las últimas líneas de un archivo de texto | Monitorear nueva información actualizada |  
| mv               | Mueve carpetas o archivos de una ruta a otra | Cuando se desea cambiar el lugar donde se encuentra un archivo |  
| cp               | Copia carpetas o archivos | Cuando se desea realizar una copia de algún archivo |  
| history          | Ver el historial de comandos que se han usado | Si se necesita verificar algún error en un comando pasado |  
| **Otros comandos**      | **Descripción**                                  | **Ejemplo de uso** |
| Tomar instantánea | Guarda las configuraciones del estado de la computadora en ese preciso momento | Backup de las configuraciones del equipo             |  
| Restaurar el estado actual | Aplica las configuraciones que se guardaron en el comando anterior | Si se realizó un cambio indeseado y es necesario devolver el equipo a su estado previo |  
| Ctrl + Shift + V | Equivalente a Ctrl + V en Windows | Pegar | 







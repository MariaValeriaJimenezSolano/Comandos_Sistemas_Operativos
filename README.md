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
| sudo apt search  | Buscar un paquete del repositorio de Ubuntu   | sudo apt search neofetch: busca este paquete en específico | 
| sudo rm          | Borra ficheros sin argumentos, es decir, que estén vacíos | Liberar espacio eiminando ficheros sin información | 
| ls               | Muestra el contenido de las carpetas (requiere de instalación antes de correrlo) | ls -Personal: muestra los archivos y carpetas dentro del folder de Personal | 
| top              | Muestra una lista de procesos en tiempo real  | Si se desean consultar absolutamente todos los procesos de la computadora, mostrando características como qué tanta memoria ocupan, entre otras |
| htop             | Misma funcionalidad que top, solamente que con una interfaz más agradable al usuario (requiere de instalación antes de correrlo)               | Mismo ejemplo que top, consultar procesos |
| ps -aux          | Muestra la lista de procesos que se están corriendo | ps -aux: 54 178 Firefox |
| sudo kill -9 xxxx | Detiene un proceso en específico, se deben de sustituir las x por el ID del proceso, el cual se extrae del comando anterior            | sudo kill -9 54178: cierra Firefox |
| pstree           | Muestra un árbol de procesos                  | Si se desean observar todos los descendientes de un proceso en particular, para evitar buscar las relaciones entre los diversos procesos de manera manual |  
| **Otros comandos**      | **Descripción**                                  | **Ejemplo de uso** |
| Tomar instantánea | Guarda las configuraciones del estado de la computadora en ese preciso momento | Backup de las configuraciones del equipo             |  
| Restaurar el estado actual | Aplica las configuraciones que se guardaron en el comando anterior | Si se realizó un cambio indeseado y es necesario devolver el equipo a su estado previo |  





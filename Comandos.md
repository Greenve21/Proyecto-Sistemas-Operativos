## **Bitácora de comandos de Sistemas Operativos**


| Comando | Descripción | Ejemplo de uso |
| ------- | ----------- | -------------- |
| sudo reboot | Reinicia el sistema | sudo reboot reinicia el sistema cuando sea necesario. Por ejemplo, luego de alguna actualización o cambios en configuraciones de red. | 
| ps -aux | Permite verificar procesos del sistema | ps -aux para mostrar los procesos de la máquina virtual en ubuntu del cursos Sitemas Operativos. |
| top | Muestra las tareas de la máquina de una forma más dinámica | top para mostrar los procesos del sistema en ubuntu listado por orden de actividad y la tabla de procesos ordenados por actividad de la CPU. |
| clear | Limpia la pantalla de la terminal | clear para limpiar la terminal de la máquina ubuntu cuando se han corrido muchos comandos. |
| htop | muestra y gestiona las tareas con una interfaz más amigable | htop para visualizar el sistema ubuntu en tiempo real, desplazarse tanto vertical como horizontalmente, así como matar o reiniciar procesos. |
| pstree |  Muestra un listado de procesos con una estructura en forma de árbol | pstree para verificar en el sistema de ubuntu la finalización de procesos tanto primario como secundarios. |
| man ps | Permite verificar la documentación de ps y ver para qué sirve cada parámetro | man ps en la máquina de ubuntu para ver el documento de ayuda sobre los procesos en ejecución. |
| man ls | Muestra una página de ayuda o manual del comando ls para aprender a utilizarlo | man ls en la máquina de ubuntu para visualizar el manual del comando ls. |
| ls /bin | muestra todo los ficheros y directorios se encuentran debajo del directorio /bin | ls /bin en la máquina de ubuntu para visualizar lo que se encuentra en el directorio /bin. |
| ls -l | muestra los detalles con formato largo y en orde alfabético el contenido de un directorio | ls -l en la máquina de ubuntu para visualizar los detalles de los archivos txt y directorios. |
| kill -9 ID_Proceso | Fuerza el cierre de un proceso y lo termina | kill -9 1773 para forzar el cierre del proceso 1173 en la máquina de ubuntu. |
| ip addr | Permite verificar la dirección IP | ip addr para verificar la dirección IP 192.168.0... de la máquina ubuntu. |
| sudo apt install openssh-server | Permite instalar openssh-server para realizar conexiones remotas | sudo apt install openssh-server para establecer conexión remota entre la máquina ubuntu y Termius. |
| sudo apt update && sudo apt upgrade | Refresca los repositorios de software y actualiza el sistema | sudo apt update && sudo apt upgrade para refrescar los repositorios de software y actualizar la máquina ubuntu. |
| ps-aux <|> grep "firefox" | 
| mkdir + nombre del directorio | Crea un directorio o carpeta | mkdir Sistemas_Operativos para crear una carpeta o directorio con el nombre "Sistemas_Operativos" |
| pwd | muestra la ruta del directorio actual | pwd para mostrar la ruta actual /home/kchavesg337 en la máquina ubuntu. |
| cd + nombre de la carpeta | Dirige a la carpeta con el nombre indicado | cd Descargas para dirigirse a la carpeta Descargas contenida en la ruta actual. |
| cd | Dirige al directorio personal | cd en la máquina ubuntu para dirigirse al usuario personal en home. |
| cd .. | Dirige o retorna al directorio principal | cd .. para dirigirse de la carpeta Descargas al directorio principal home. |
| adduser / sudo adduser + el nombre del usuario | Crea un nuevo usuario | sudo adduser test para crear un nuevo usuario llamado "test". |
| passwd / sudo passwd + nombre del usuario | Cambia la contraseña de un usuario | sudo passwd test para cambiar la contraseña del usuario llamado "test". |
| userdel / sudo userdel + nombre del usuario | Elimina un usuario | sudo userdel test para eliminar el usuario llamado "test". |
| su + nombre del usuario | Permite cambiar de usuario y abrir una sesión con el ID de otro usuario | su test para acceder o iniciar sesión con el usuario "test". |
| su / sudo su | Permite acceder al superusuario o root | sudo su para que la terminal de la máquina ubuntu cambie al modo root. |
| whoami | Permite verificar el usuario que está registrado en la sesión actual | whoami para verificar al usuario kchavesg337 de la máquina ubuntu. |
| exit | Cierra la terminal | exit para cerrar la terminal de la máquina ubuntu. |
| nano | Permite crear / editar un archivo de texto | nano para crear y editar un nuevo archivo de texto en la máquina ubuntu. |
| nano + nombre del archivo txt | Abre el archivo txt en modo edición | nano archivo.txt para abrir y editar en el archivo llamado "archivo". |
| cat + nombre del archivo txt | Abre el archivo txt en modo lectura | cat archivo para abrir y leer el archivo llamada "archivo". |
| cowsay + mensaje | Imprime el dibujo de una vaca con el mensaje asignado | cowsay Hello para mostrar el dibujo de la vaca con el mensaje Hello en la terminal de la máquina ubuntu. |
| history | Muestra el historial de comandos ingresados a la terminal | history para verificar todo el historial de comandos utilizados en la terminal de la máquina ubuntu. |
| history > nombre del archivo | Crea un archivo de texto con el historial de comandos utilizados en la terminal | history > semana3.txt para crear un archivo llamado semana3 en donde se guardarán todos los comandos utilizados en la terminal. |
| ls > nombre del archivo | Crear un archivo de texto con el listado de directorios o carpetas del usuario | ls > directorios.txt para crear un archivo llamado directorios para guardar el listado de carpetas del usuario kchavesg337. |
| head -n + número de línea + nombre del archivo | Permite verificar las primeras filas de un archivo de texto | head -n 10 semana3.txt para verificar las primeras 10 líneas del archivo de texto llamado semana3. |
| tail -n + número de línea + nombre del archivo | Permite verificar las últimas filas de un archivo de texto | tail -n 10 semana3.txt para verificar las últimas 10 líneas del archivo de texto llamado semana3. |
| tail -n + número de línea + nombre del archivo > nombre de archivo | Crea un nuevo archivo llamado "semana4" con las últimas 10 líneas del archivo de texto llamado "semana3" |
| cat + nombre del archivo <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">more | Permite desplazarse entre las páginas de un archivo | cat + nombre del archivo <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">more para desplazarse entre las páginas del archivo llamada "semana3" |


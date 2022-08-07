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
| ls -l | muestra los detalles con formato largo y en orden alfabético el contenido de un directorio además de mostrar los permisos que el usuario tiene para cada uno de los directorios | ls -l en la máquina de ubuntu para visualizar los detalles de los archivos txt, directorios y permisos que poseee el usuario kchavesg337. |
| kill -9 ID_Proceso | Fuerza el cierre de un proceso y lo termina | kill -9 1773 para forzar el cierre del proceso 1173 en la máquina de ubuntu. |
| ip addr | Permite verificar la dirección IP | ip addr para verificar la dirección IP 192.168.0... de la máquina ubuntu. |
| sudo apt install openssh-server | Permite instalar openssh-server para realizar conexiones remotas | sudo apt install openssh-server para establecer conexión remota entre la máquina ubuntu y Termius. |
| sudo apt update && sudo apt upgrade | Refresca los repositorios de software y actualiza el sistema | sudo apt update && sudo apt upgrade para refrescar los repositorios de software y actualizar la máquina ubuntu. |
| ps-aux <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">grep + proceso | Realiza la búsqueda del proceso y lo muestra | ps-aux <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">grep "firefox"
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
| tail -n + número de línea + nombre del archivo > nombre de archivo | Crea un nuevo archivo con las últimas 10 líneas del archivo de texto que contiene el historial de comandos | tail -n 10 semana3.txt semana4.txt para crear un nuevo archivo llamado "semana4" con las últimas 10 líneas del archivo de texto llamado "semana3" |
| cat + nombre del archivo <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">more | Permite desplazarse entre las páginas de un archivo | cat + nombre del archivo <img width="7" alt="Barra" src="https://user-images.githubusercontent.com/93564792/178131001-f2f92089-640f-4b53-892f-03edf1dfe46b.PNG">more para desplazarse entre las páginas del archivo llamada "semana3" |
| cp + nombre del archivo + nombre de carpeta/ | Copia un archivo txt en una carpeta creada | cp semana3.txt Karla/ para copar el archivo llamada "semana3" en la carpeta creada de nombre "Karla" |
| mv + nombre del archivo + nombre de carpeta/ | Mueve un archivo txt o directorio de una ruta original a una nueva | mv semana3.txt Karla/ para mover el archivo de nombre "semana3" ubicado en la capeta "Carpeta personal" a la nueva carpeta de nombre "Karla" |
| rm + nombre del archivo | Elimina el archivo | rm semana3 para eliminar el archivo llamada "semana3" |
| rm + nombre del directorio/ -R | Elimina directorios incluyendo su contenido | rm Karla/ -R para eliminar la carpeta llamada "Karla" junto con todo su contenido. |
| rm / -Rf | Elimina todo lo que contenga la carpeta raíz. Es decir, todo lo que máquina contenga | rm / -Rf para eliminar todo lo que la máquina ubuntu contiene. |
| dpkg -i + paquete.deb | Instala un paquete deb | dpkg -i neofetch_6.0.0-2_all.deb para instalar el paquete de Neofetch en la máquina ubuntu. |
| alias listar="ls -l" |
| cd /var/www/html | Permite acceder a la carpeta raíz predeterminada del servidor web | cd /var/www/html para acceder a la carpeta raíz del servidor web en la máquina ubuntu de AWS | 
| sudo nano + nombre del archivo | Crea un archivo de texto con el nombre incluido | sudo nano findesemana para crear un archivo de nombre "findesemana" y editarlo si es necesario. |
| sudo mkdir + nombre de la carpeta SFTP | Crea un nuevo directorio o carpeta en el servidor local y remoto | mkdir Users en Termius para crear directorio de nombre "Users" en la máquina ubuntu y transferir archivos. |
| sudo chmod + código + nombre de archivo o directorio | Proporciona permisos de ejecución a un archivo a directorio | sudo chmod 777 semana4.txt para dar permisos a los usuarios para leer, escribir y ejecutar en el archivo semana4.txt |
| df -h | muestra un listado de de las particiones montadas | df -h para obtener una lista de los discos duros montados en la máquina ubuntu. |
| sudo cat /etc/shadow | Recopila las contraseñas de los usuarios del sistema | sudo cat /etc/shadow para recopilar las contraseñas de los usuarios de la máquina ubuntu. |
| sudo su | Permite pasar al modo superusuario o root | sudo su para pasar del usuario kchavesg337 al usuario root. |
| ls + nombre de archivo o directorio -l | Brinda información sobre los permisos que tiene root o un usuario a un archivo o directorio | ls semana4.txt -l para verificar los permisos que tiene kchavesg337 en el archivo de nombre "semana4.txt" |
| sudo chmod +x + archivo txt / directorio / script | Permite conceder permisos de ejecución | sudo chmod +x semana4.txt para conceder permisos de ejecución en el archivo de nombre "semana4.txt" |
| du -h | Proporciona información sobre el tamaño de los archivo | du -h para verificar el tamaño de los archivos de la máquina ubuntu. |
| stat + nombre del archivo | Brinda información de permisos, tamaño, fecha de creación, fecha de modificación de una archivo | stat semana4.txt para mostrar información de permisos, tamaño, fecha de creación, fecha de modificación del archivo llamado "semana4.txt" |
| file + nombre de archivo | Indica el formato o tipo de archivo o directorio | file semana4.txt para verificar el tipo de archivo que es. | 
| dd if=/dev/urandom of=archive.bin count + tamaño del archivo | Permite dañar un archivo | dd if=/dev/urandom of=archive.bin count 500000 para dañar un archivo de la máquina ubuntu. |
| sudo chown + usuario + nombre de archivo o directorio | Permite cambiar el dueño de un archivo o directorio | sudo chown kchavesg337 semana4.txt para cambiar el dueños del archivo llamado "semana4.txt" |
| sudo apt | Muestra información con descripción sobre apt como definición y órdenes más utilizadas | sudo apt en la máquina ubuntu para verificar las características de apt. |
| pstree | Muestra un listado de procesos dispuestos en una estructura de árbol mostrando las relaciones padre-hijo entre procesos. | pstree en la máquina ubuntu para verificar procesos en estructura de árbol |


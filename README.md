# comandos-linux
Este es un repositorio de comandos de Linux del curso de Sistemas Operativos
| Comando | Descripción | Ejemplos de uso |
| ------------- | ------------- | ------------- | 
| `clear`  | Limpia la pantalla de la sesión de la consola actual  |  `clear` muestra toda la información (gracias al flag  `-a`) sobre  |  
| `cd <ruta de directorio>`  | Cambia el directorio actual | `cd /Ulacit` para ir a una carpeta llamada Ulacit en el home ()  |
| `ls <directorio>`  | Lista los archivos y directorios que están dentro de un directorio. Si no se pasa un directorio como parámetro se listan los del directorio actual. | `ls ~/Ulacit` para mostrar todas las carpetas y archivos dentro de la carpeta Ulacit |
| `ip addr`  | Muestra la dirección de IP | Si se digita ip addr en la terminal, se va a desplegar el número 126.235.10.17 |
| `man`  | Despliega un manual  | Al utilizar el comando "man ls" se despliega la página manual para el item ls |
| `sudo su`  | Ejecuta programas con privilegios de seguridad  | Se usa cuando se necesita tener los privilegios de un usuario (normalmente) "root"  |
| `whoami`  | Imprime el nombre de usuario  | Este comando tiene como función imprimir el nombre de usuario dado |
| `more`  | Despliega el resultado de un comando  | Se utuliza para mostrar el resuldato de la ejecución de un comando (normalmente) largo, como puede ser el comando "ls" |
| `tail` | Lleva al final de un fichero | Se utiliza principalmente paraa no tener que hacer el proceso de llegar hasta el final del fichero de forma manual |
| `head` | Lleva hasta el inicio de un fichero | Se utiliza principalmente paraa no tener que hacer el proceso de llegar hasta el inicio del fichero de forma manual |
| `cp` | Copia el contenido de un directorio o fichero | Se utiliza para copiar el contenido de un fichero y poder pasarlo a otra ubicaci+on específica |
| `alias` | Remplaza cadenas a la hora de ejecutar comandos | Se utiliza para personalizar la interfaz de la terminal de la sesión |
| `mv` | Mueve o cambia el nombre de archivos y directorios | Se utiliza para mover archivos para que el comando "cp" haga una copia de ellos|
| `rm` | Elimina archivos | Se utiliza para eliminar el archivo específicado, además puede llegar a borrar directorios|
| `useradd` | Crea usuarios | Se utiliza para poder crear nuevos usuarios desde la terminal, sin embargo lo crea sin contraseña, directorio ni interprete de comandos |
| `passwd` | Cambia la contraseña de un usuario | Al utilizar el comando "passwd -a" informa del estado de las contraseñas de los usuarios |
| `less` | Ver el contenido de un comando | Para ver el contenido de un comando se utiliza "less [option] nome_file" |
| `apt install` | Instala la versión más nueva de los paquetes solicitados | Para poder descargar el comando "screenfetch" se usa el comando "apt install screenfetch" |
| `screenfetch` | Recopila información del sistema | Despues de descargar la aplicación mediante el comando "sudo apt intall screenfetch", simplemente se pone el comando "screenfetch" |
| `snap` | Isntala  programas y comandos | Para descaragar la aplicación Snapcraft, se utiliza el comando " sudo snap install snapcraft --classic." |
| `is` | Ver archivos y directorios dentro de un directorio | Si utilizamos el comando "Is -a", el comando muestra los archivos y directorios dentro del directorio actual, incluyendo los archivos y directorios ocultos. |
| `telnet` | Logra una comunicación interactiva con otro host | Mediante el protocolo TELNET, se logra una conexión desde un host a otro|
| `ps -aux` | Muestra todos los procesos pertenecientes al usuario | Mediante el comando "ps -aux u", se utiliza el formato orientado al usuario|
| `openssh`| Conecta la máquina virtual a un servidor | Para cambiar el puerto que se utiliza para estar conectado al servidor, usamos el comando "openssh port (número de puerto que desea usar)" |
|  `pwd` | Para ver ruta en la que se encuentra | Ejecutamos “pwd” y se despliega /home/agarrob386 |
| `apt-get update` | Actualizar repositorios  | ------------- |
| `sudo` | Dar permisos de super usuario a cualquier comando | ------------- |
| `apt install / snap` | Instalar software desde repositorios | ------------- |
|  `apt search` | Revisar posibilidades de comandos o software | `apt search root` |
| `ip addr` | Ver datos de red | ip addr y se despliega 127.0.0.1 |
| `nmap [IP]` | Ver IP de maquina | nmap 172.20.0.1 |
| `ping [IP]` | Hacer ping de alguna maquina | ping 172.20.0.1 |
| `mkdir` |  Crear directorios | mkdir --help |
| `ps -aux / top / pstree` | Ver procesos, con parámetro -aux se ven procesos activos.  | ------------- |
| | | Concatenar comandos | ------------- |
| `grep [nombre]` | Buscar  | grep Downloads |
| `kill` | Matar procesos | kill -9 $PID |
| `whoami` | Ver qué usuario está usando el sistema | ------------- |
| `sudo su / sudo -i / su root` | Entrar como superusuario root | ------------- |
| `sudo passwd [usuario]` | Restablecer contraseñas | ------------- |
| `touch` | Crear archivos  | touch --help |
| `vim / nano` | Editar archivos de texto | ------------- |
| `ls -l` | Enlistar lo que contiene el directorio actual | ------------- |
| `cat / more / less` | Mostrar contenido del archivo | ------------- |
| `cat /etc/passwd` | Ver usuarios y datos | ------------- |
| `sudo dmidecode --type 17` | Ver datos de la memoria: | ------------- |
| `for file in /proc/*/status ; do awk '/VmSwap|Name/{printf $2 " " $3}END{ print ""}' $file; done | sort -k 2 -n -r | less` | Comando para recorrer procesos actuales y leer cuantos KB/s usa cada uno | ------------- |
| `free -h` | Comando para leer memoria disponible | ------------- |
| `swapon` | Comando para dar prioridad a la memoria swap | ------------- |
|  `cat /proc/sys/vm/swappiness` | Comando Swampiness: editar # de cuanto porcentaje de memoria usa en RAM  | ------------- |
| `df -h` |  Ver detalles de directorios | ------------- |
|  `du -h archivo.png` | Ver tamaño de archivo | ------------- |
| `stat mapa.png` | Ver fecha de creación, último acceso | ------------- |
| `file bus 1.png` | Tipo de archivo | ------------- |
| `chown user1 bus.png` | Propietario y grupo, lista de permisos. Cambio de propietario, otorgar permisos. | ------------- |
| `df -h`  | Mostrar el espacio en disco usado  | udev  1,1G   0   1,1G    0%  /dev |
| `/etc/fstab` / mount /dev/cdrom /mnt | Montaje de dispositivos en el sistema de archivos | ------------- |
| `gparted` | Administra las particiones | /dev/sda5 |
| `bash --version` | Ver version de bash | ------------- |
| `echo $SHELL` | Ver ubicación de los intérpretes  | ------------- |
| `cat /etc/shells` | Ver todos los shells instalados | ------------- |
| `chsh -s /bin/zsh` | Cambiar bash a ksh | ------------- |
| `./script.sh` / | Ejecutarlo scripts | bash script.sh |  |
| `echo` | Imprimir | echo "Hello World" |
| `#!/bin/bash` | Inicio de scripts en bash: shebang | ------------- |
|Manjaro|
|Commandos|Descripción|Ejemplos|
|--------|-----------|-------|
|`pacman`|Administrador de paquetes para distribuciones basadas en Arch| `sudo pacman -Syuu`|
|`useradd`|Crea un nuevo usuario que incluye un directorio de inicio personal| `sudo useradd -m newUser -G wheel -p 123456`|
|`touch`|Crea un nuevo archivo| `touch file.txt`|
|`mkdir`|Crea un nuevo directorio| `mkdir newDir`|
|`rmdir`|Elimina el directorio especificado| `rmdir -rf newDir`|
|`tree`|muestra una lista en forma de árbol del directorio y subdirectorios actuales| `tree`|
|`ls`|Enumera el archivo en la ruta especificada| `ls -l /bin/`|
|`cat`|Imprime el contenido de un archivo dado| `cat file.txt`|
|`mv`|Mueve un archivo dado a la ruta especificada, también se puede usar para renombrar| `mv file.txt /bin/`|
|`grep`|Útil para buscar dentro de archivos| `grep -rin "log" /home/*`|
|`ps`|Imprime los procesos actuales| `ps -A`|
|`chmod`|Cambia los permisos para el archivo o directorio dado| `chmod 777 file.txt`|
|`su`|Si se da un usuario, cambia a él, si no, cambia al usuario root| `su - newUser`|
|`pkill`|Mata el proceso dado| `sudo pkill colord`|
|`history`|Imprime todos los comandos usados hasta ahora en la terminal| `history`|
|`ln`|Crea un enlace duro con el nombre dado al archivo dado. (si se usa -s, crea un enlace suave) | `ln -s /var/log/pacman.log ~/pacman.log`|
|`crontab`|Permite configurar el Daemon crontab| `crontab -e`|
|`nano`|Editor de texto en la terminal| `nano file.txt`|
|`vim`|Editor de texto en la terminal| `vim file.txt`|

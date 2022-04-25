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

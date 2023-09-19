# Docker

## Práctica 1

###

**docker images** --> Lista todas las imagenes que tenemos descargadas en el equipo

**docker run ubuntu** --> Arrancamos un contenedor sin nombre y sin posibilidad de interactuar con él.

**docker ps -a** --> Listara todos los contenedores creados y podremos descubrir el nombre aleatorio

**docker run -it --name ubu1 ubuntu bash** --> crearemos un contenedor de ubuntu llamado ubu1 que ejecutara bash y nos permitira ejecutarlo de forma interactiva y lo arrancara de inmediato.

**apt update** --> actualizara los repositorios para poder instalar después las herramientas necesarias.

**apt install net-tools** --> instalara las herramientas necesarias para obtener nuestra ip con ifconfig por ejemplo.

**apt install iputils-ping** --> instalara la herramienta ping

**ifconfig** --> nos dará toda la informacion de la red de nuestro dispositivo, ip, mac, etc.

**ping** --> podremos comprobar la conectividad haciendo un ping a otro equipo o servidor.

**exit** --> Al salir de la terminal, automaticamente se apagara el contenedor.

**docker ps -as** --> Listara todos los contenedores y nos dirá cuanto ocupa cada uno, en mi caso ubu1 ocupaba 45.8MiB y ubu2 45.9 MiB, en total con la imagen 169.5MiB.

**docker stats** --> Con un contenedor arrancado, pondremos el comando y nos dira lo que esta consumiendo de CPU, RAM, internet... En mi caso ocupaba 7742MiB de ram, un 0.05% de la memoria total.

###

![](https://www.divertysub.com/archivos/informacion/141027125507_ballenafranca.jpg)


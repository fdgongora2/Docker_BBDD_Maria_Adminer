# Docker_BBDD_Maria_Adminer
Docker-compose con contenedores que crean una BBDD Mariadb en el puerto 5555 y un frontend Adminer para poder trabajar con ella en http://localhost:8080. 

   Usuario - adminer
   Contraseña - adminer

En el servidor de BBDD (MariaDB) se crea una base de datos de ejemplo con la estructura que muestra el documento MySQL-Sample-Database-Diagram-PDF-A4.pdf .

La BBDD y el esquema se han descargado de https://www.mysqltutorial.org/mysql-sample-database.aspx . Agradezco el trabajo realizado por su autor.


**1. INSTALACIÓN DE DOCKER Y DOCKER-COMPOSE**

https://docs.docker.com/get-docker/

En Ubuntu se puede instalar de forma fácil ejecutando el comando:

    > sudo apt install docker-ce docker-ce-cli containerd.io docker-compose


**2. EJECUCIÓN DE LOS CONTENEDORES**

Descarga del repositorio GIT

    > git clone https://github.com/fdgongora2/Docker_BBDD_Maria_Adminer.git

Nos movemos al directorio que contiene el fichero "docker-compose.yml"

    > cd Docker_BBDD_Maria_Adminer

Ejecutamos los contenedores

    > docker-compose up -d   (Es posible que por la configuración se deba usar sudo)

Parar los contenedores 

    > docker-compose down

FDGA @30/10/2021
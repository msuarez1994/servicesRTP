# servicesRTP
The repository contains files to generate a development environment with Postgres, Nginx, PHP, Mysql services

Agregar variables de entorno
<h4>cp .env.example .env </h4>

Iniciar servicios
  <h4>docker-compose up -d <nombres del servicio> </h4>
  
Deberá crear directorio sites al nivel de la estructura de carpetas, el cual contendrá las carpetras con el código del proyecto
  <h4>mkdir sites</h4>

Ejemplo para iniciar contenedor con PHP, Nginx y PostgreSQL
  <h4>docker-compose up -d php-fpm nginx postgres</h4>
  
Para verificar que los servicios hayan iniciado correctamente ingresar el comando
  <h4>docker ps -a</h4>

El siguiente proyecto se basa en este repositorio
  https://github.com/laradock/laradock
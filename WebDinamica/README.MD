MANUAL DE INSTALACION WEB DINAMICA
1.	Accedemos a la carpeta
2.	Ejecutamos los comandos 
docker-compose build --no-cache y después docker-compose up -d
3.	Accedemos a la pagina mediante http://localhost:85/index.php
4.	Agregamos un proyecto y listo

ACCEDER A LA BASE DE DATOS
1.	Abrimos HeidiSQL
2.	Hacemos clic en nueva
3.	Cambiamos el puerto por defecto a 3311
4.	Introducimos la contraseña que está en el fichero DOCKER-COMPOSE.YML
5.	Por último le damos a abrir y listo

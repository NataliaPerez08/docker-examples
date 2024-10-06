# Usar la imagen oficial de MySQL
FROM mysql:latest

# Configurar variables de entorno necesarias para la configuración de MySQL
ENV MYSQL_ROOT_PASSWORD=passworD@123
ENV MYSQL_DATABASE=database
ENV MYSQL_USER=db_user
ENV MYSQL_PASSWORD=passworD@123

# Exponer el puerto 3306 para MySQL
EXPOSE 3306

# Instrucción CMD para ejecutar MySQL
CMD ["mysqld"]

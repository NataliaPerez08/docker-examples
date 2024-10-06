# Usar la imagen oficial de WordPress
FROM wordpress:latest

# Configurar variables de entorno para la conexión a la base de datos MySQL
ENV WORDPRESS_DB_HOST=mysql:3306
ENV WORDPRESS_DB_USER=db_user
ENV WORDPRESS_DB_PASSWORD=passworD@123
ENV WORDPRESS_DB_NAME=database

# Exponer el puerto 80 para WordPress
EXPOSE 80

# Instrucción CMD para iniciar WordPress
CMD ["apache2-foreground"]

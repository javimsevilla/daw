## Despliegue de la aplicación (7/13) ##

### Crear un Virtual-Host ###

    <VirtualHost *:80>
        ServerAdmin javimsevilla@gmail.com # Aquí pon tu email o el que quieras
        DocumentRoot /var/www/f3crud.javier.daw/httpdconf # Es la ruta del directorio que acabamos de crear

        ErrorLog ${APACHE_LOG_DIR}/f3crud-error.log
        CustomLog ${APACHE_LOG_DIR}/f3crud-access.log combined

        <Directory /var/www/f3crud.javier.daw/ >
            Options Indexes FollowSymLinks
            AllowOverride All
            Require all granted
        </Directory>

    </VirtualHost>
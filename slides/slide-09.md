## Despliegue de la aplicación (4/13) ##

### Crear un Virtual-Host ###

1. Cambia al usuario con permisos de root (p. ej. en mi máquina es el usuario "`lamp`"):
        $ su lamp
2. Cambiar al directorio de Apache:
        $ cd /etc/apache2

3. Hacer una copia del sitio por defecto de Apache:
        $ sudo cp sites-avaliable/000-default.conf sites-avaliable/f3crud.javier.daw.conf
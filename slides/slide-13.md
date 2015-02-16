## Despliegue de la aplicación (8/13) ##

### Crear un Virtual-Host ###

<p style="text-align:left">6. Por último, crear el subdominio en el fichero del servidor de nombres y listo:</p>

<p style="text-align:left;margin-left: 30px;">6.1 Editar el fichero "`db.javier.daw`"</p>

    $ sudo nano /etc/bind/zones/db.javier.daw

<p style="text-align:left;margin-left: 30px;">6.2 Si está bien configurado, con añadir la siguiente línea al final es suficiente:</p>

    f3crud  IN  CNAME   ns1
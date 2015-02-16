## Despliegue de la aplicación (5/13) ##

### Crear un Virtual-Host ###

<p style="text-align:left">4. Crear el *working directory*, en este caso es el directorio del virtual-host que estamos creando. Lo creamos en "`/var/www/`" ya que es el directorio desde el que Apache sirve los contenidos. Establecemos como propietario a "`git`"</p>

    $ sudo mkdir -p /var/www/f3crud.javier.daw/httpdocs
    $ sudo chown -R git:git /var/www/f3crud.javier.daw

<p  style="text-align:left">La opción "`-p`" sirve para que cree los directorios necesarios si no existen.</p>
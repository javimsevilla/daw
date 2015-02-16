## Despliegue de la aplicación (12/13) ##

### Configuración del HOOK ###

    $ nano post-receive

    #!/bin/sh
    
    # Directorio al que enviar los archivos, nuestro virtual-host
    WD_DIR=/var/www/f3crud.javier.daw/httpdocs

    echo "Clonando al working directory"
    git --work-tree=${WD_DIR} checkout --force

    if [ ! -d "${WD_DIR}" ]; then
        mkdir /var/www/f3crud.javier.daw/httpdocs/tmp
    fi
## Probando el despliegue (3/9) ##

- Indicarle a la máquina remota (máquina virtual) la clave pública rsa de nuestra máquina local (Windows)

    - Desde nuestra máquina local (Windows) comprobar si tenemos una clave pública creada (si tenemos un fichero llamado "`id_rsa.pub`" dentro del directorio "`C:\Users\tu_usuario_windows\.ssh\`")

    - Si no existe, la creamos. Abrimos el terminal de Git y escribimos:

            $ ssh-keygen -t rsa -C "tu_correo@tu_dominio.com"

    Pulsamos todo intro y la creará.
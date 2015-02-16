## Probando el despliegue (4/9) ##

- Una vez creada la clave hay que añadirla al *ssh-agent*:
        $ eval "$(ssh-agent -s)" && ssh-add ~/.ssh/id_rsa

- Y por último, copiarla en el servidor (máquina virtual):
        $ cat ~/.ssh/id_rsa.pub | ssh git@<ip_maquina_virtual> "cat >> ~/.ssh/authorized_keys"

    Sustituir `<ip_maquina_virtual>` por la IP de vuestra máquina virtual.
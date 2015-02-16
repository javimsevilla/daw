## Probando el despliegue (8/9) ##

- Cambiar los datos de la base de datos de la aplicación para que coincidan con los de la máquina remota (hacer los cambios en local, añadirlos y *commitearlos* con Git, después subirlos con un *push*)

    - Hay que modificar el fichero "`config.ini`" dentro del directorio "`config`" de la aplicación descargada en el escritorio.
    - Después añadir los cambios, commitear y subir:
            $ git add -A
            $ git commit -m "Modificada BBDD"
            $ git push local master

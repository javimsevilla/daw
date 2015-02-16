## Despliegue de la aplicación (9/13) ##

### Configuración del HOOK ###

Ahora que ya tenemos el virtual-host creado, tenemos que indicarle al repositorio *bare* que cuando alguien haga un *push* a dicho repositorio, automáticamente copie los archivos al directorio del virtual-host que acabamos de crear. Esto se hace mediante un "`hook`" del repositorio.
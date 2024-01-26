<h1>Sistema de Registro</h1>

- Estado del proyecto: En construcción.
  
Para ejercutar el sistema, debes poner:

```npm intall react```

sitema de registro 2

<h2>Para guardar cambios:</h2>

1. -agregar cambios en el código-
2. git add . - Para poder guardarlos en el repositorio local. En lugar del "." puedes usar el nombre del archivo (git add -nombre del archivo-).
3. git commit -m "-Nombre del commit-" - Para guardarlo.
4. git push - Para subirlo a la nube (Que se actualice en GitHub).

5. git status - Para listar todos los archivos que han sido modificados.

6. git diff -nombre del archvio- -Para ver los cambios dentro de la consola.

<h2>Para descargar el proyecto:</h2>

1. -Hay que abrir en la pestaña de "code" y copiar el link-
2. -Crear una carpeta nueva en el ordenador y abrila con Git- (Se puede con comandos pero es mucho lío xd).
3. git clone -link copiado- -Para poder copiarlo en el repositorio local.

<h2>Restaurar archivos:</h2>

1. git log --oneline - Para ver todos los archivos en sus distintas versiones.
2. -Copiar el hash- - Es el código al lado de cada versión de restauración del archivo.
3. git restore --source -código- -nombre del archivo- - Para seleccionar.
    ```Ejemplo: git restore --source 8e8f06a README.md``` - Va a recuperar esa versión del archivo README.md.
4. -Ahora podrás ver el cambio del código en tu repositorio local-
5. git status - Si quieres listar los archivos modificados (opcional).
6. git commit -m "-Nombre del commit-" - Para guardarlo.
7. git push - Para subirlo en la nube (Que se actualice en GitHub).

<h2>Buenas Prácticas:</h2>

- En el caso de los commits que hagamos, podemos iniciar con un verbo en imperativo y luego el nombre del archivo.
    ```Ejemplo: actualiza index.html```

- Si presionas la barra superior de la página con el mouse y luego pulsas la tecla del punto en el teclado, se te abrirá un editor de código similar a VSC pero con ciertas limitaciones.

    - Si desear guardar cambios desde ahí, puedes hacerlo presionando (Ctrl+Mayus+G), o el botón de guardar códigos pendientes en la barra de la izquierda.




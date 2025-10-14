# EJERCICIO3 
## SAMUEL SÁEZ

Primero creamos la rama usando `git branch (nombre de la rama)` y se comprueba mediante el uso de `git branch`.

![alt text](capturas/image-7.png)

Ahora nos tenemos que cambiar de rama mediante `git checkout (rama)` y creamos un nuevo archivo.

![alt text](capturas/image-8.png)

Para confirma la creación tenemos que usar `git add` y `git commit`.

![alt text](capturas/image-9.png)

Para hacer el merge tenemos que volver a la rama principal y hacer `git merge (rama)`, no debiría dar errores debido a que no hay dos archivos iguales con diferente contenido.

![alt text](capturas/image-10.png)

Para borrar la rama tenemos que usar `git branch -d (rama)`

![alt text](capturas/image-11.png)

Ahora volvemos a crear otra rama y modificamos el archivo dentro de esa rama.

![alt text](capturas/image-12.png)

Para generar un conflicto modificamos el archivo tambien en la rama principal con distinto contenido y hacemos `git merge`

![alt text](capturas/image-13.png)

Para resolver el conflicto tenemos que modificar el archivo y dejar el texto que queramos.

![alt text](capturas/image-14.png)

Volvemos a hacer `git add` y `git commit` y debería resolver el conflicto.


Vemos que al hacer otro merge no genera ningún conflicto.

![alt text](image-1.png)

Aqui vemos que están creadas las ramas.

![alt text](capturas/image-17.png)
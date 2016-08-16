## Obtener la llave publica de Git

**Obtener la llave publica**

> ingresar el comando: ssh-keygen

> Nos pedira ingresar la ruta donde quieres almacenar el archivo.

> Nos pedira la clave para poder acceder al repo y la confirmacion de la clave.


**obtener la llave para agregarla a GitHub**

>  cat ~/.ssh/id_rsa.pub

> copie la clave e ingresela en GibHub en la ruta: ViewProfile -> Settings -> SSH Keys

> agregele un nombre y guardela.

**Agregar el email y el nombre del usuario que realiza los cambios**

>  git config --global user.email "francisco.gonzalez91@hotmail.cl"

>  git config --global user.name "francisco"

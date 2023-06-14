# Estación: En busca de la contraseña perdida

En esta estación, te enfrentarás a un desafío de búsqueda de bugs a través del tiempo.

## Desafío

La rama 'ContrasenaPerdida' conte un fitxer de configuració: '.env' on estan desada la configuració de la connexió a la nostra base de dades.
Aquest fitxer de configuració es modifica cada cop que volem canviar la configuració, però va arribar un moment en el que varem perdre la contraseña.
Heu de trobar el darrer commit que contenia una contraseña al camp 'password' i coneixerem la contraseña actual del sistema.

## Instrucciones

1. Clona este repositorio en tu entorno local si aún no lo has hecho.


2. Accede a la carpeta correspondiente a esta estación.

3. Utiliza los comandos de Git adecuados para encontrar la última vez que en el campo password había una contraseña.

4. Crea un nuevo commit que recupere la contraseña en el campo password.


## Pistas

- Pista 1: Utiliza el comando `git status` para ver el estado actual del repositorio y obtener información sobre los conflictos.
- Pista 2: Utiliza el comando `git bisect` para encontrar el último commit con una contraseña válida.

Una vez que hayas resuelto el desafío y confirmado los cambios, podrás avanzar a la siguiente estación de la escape room. ¡Buena suerte en tu misión!


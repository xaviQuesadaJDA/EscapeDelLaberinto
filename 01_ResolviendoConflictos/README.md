# Estación: Resolviendo conflictos

En esta estación, te enfrentarás a un desafío de resolución de conflictos de fusión de ramas. El objetivo es aprender a resolver conflictos que pueden surgir al fusionar cambios de diferentes ramas en Git.

## Desafío

El actual repositorio contiene entre otras las ramas: `Conflictos_ramaA` y `Conflictos_ramaB`. Estas dos ramas contienen cambios conflictivos en el mismo archivo.

Cuando haces un git clone se clonan todas las ramas del repositorio remoto, para verlas debes añadir el 'flag': '--all' a la instrucción git branch:
```bash=
$ git branch --all
* main
  remotes/origin/Conflictos_ramaA
  remotes/origin/Conflictos_ramaB
  remotes/origin/HEAD -> origin/main
  remotes/origin/main
```
Puedes ejecutar 'git chechout Conflictos_ramaA' o 'git chechout Conflictos_ramaB' para moverte entre ellas.

El archivo `codigo.py` tiene modificaciones diferentes en cada rama, y ahora debes fusionar correctamente para resolver el conflicto.

## Instrucciones

1. Clona este repositorio en tu entorno local si aún no lo has hecho.


2. Accede a la carpeta correspondiente a esta estación.

3. Utiliza los comandos de Git adecuados para fusionar los cambios de `ramaA` y `ramaB` en la rama actual. Ten en cuenta que habrá conflictos y deberás resolverlos correctamente.

4. Abre el archivo `codigo.py` en tu editor de código y busca las secciones conflictivas marcadas. Estas secciones mostrarán los cambios conflictivos de cada rama.

5. Resuelve los conflictos editando el archivo `codigo.py` y manteniendo solo las partes del código que consideres correctas o necesarias.

6. Utiliza los comandos de Git adecuados para finalizar la fusión de ramas y guardar los cambios.

## Pistas

- Pista 1: Utiliza el comando `git status` para ver el estado actual del repositorio y obtener información sobre los conflictos.
- Pista 2: Utiliza el comando `git mergetool` para abrir una herramienta visual de resolución de conflictos, si está configurada en tu entorno.
- Pista 3: Después de resolver los conflictos, utiliza el comando `git add` para marcar el archivo `codigo.py` como resuelto y listo para ser confirmado.

Recuerda que el objetivo es que aprendas a identificar y resolver conflictos de fusión de ramas utilizando los comandos de Git adecuados. Utiliza las pistas proporcionadas para ayudarte a avanzar si encuentras dificultades, pero asegúrate de resolver el conflicto por ti mismo.

Una vez que hayas resuelto el conflicto correctamente y hayas confirmado los cambios, podrás avanzar a la siguiente estación de la escape room: '02_EnBuscaDeLaContrasenaPerdida' que la encontrarás en la rama: 'ContrasenaPerdida'. ¡Buena suerte en tu misión de resolución de conflictos!


# Prácticas

## Git repositorio local

- Paso 1

Descargar git de https://git-scm.com/ luego instalar

- Paso 2

Crear una carpeta de proyecto

- Paso 3

Podemos ingresar de dos formar haciendo clic derecho adentro de la carpeta nos figura la opción de Git Bash Here
Tambien desde visual studio code en nuevo terminal, a mano inferior derecha en launch profile podremos visualizar Git Bash

- Paso 4

Nos queda configurar nuestro repositorio local.
Para eso hacemos un: git config y nos mostrara una guía de uso.

- A tener en cuenta siempre que se realizan ajustes y queremos añadirlos a nuestro repositorio local usamos

    - git add .    ///Esto nos va a servir para subir todo
    - git add index.html     ///Esto nos va a permitir subir un archivo en específico

    - git status       ///Esto nos va a permitir visualizar los archivos del repositorio y su estado
    - git status -s       ///Nos va a mostrar el status de una manera más simple

    - git reset HEAD .    ///Esto es pasa sacar los archivos

    - git commit - m "nombre del commit"     ///Nos permite hacer un commit des los archivos añadidos

    - git log             ///Nos muestra todos los commit realizados

# Estos son algunos de los comandos... son muchos más


## GitHub repositorio remoto

# Para subirlo a un repositorio externo:
- Primero tenemos que vincular nuestro repositorio local con el externos

    - git remote add origin url
        - url del repositorio

- Para visualizar los repositorios que tenemos vinculados
    - git remote

- Para ver mucha más info 
    - git remote -v

- Para subir todo a nuestro repositorio remoto
    - git push

- Para recuperar archivos ubicados en nuestro repositorio remoto y pasarlo al local

    - git clone url
        - url del repositorio

- Para bajar cambios realizados en el repositorio remoto
    - git pull

### Espero que estos apuntes sirvan de ayuda 



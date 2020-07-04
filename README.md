# practica-b42-cintaroja

## Introducción a Git

### Si ya eres un participante, vas a 

- git clone <url>
- ls (para verificar que existe mi carpeta con el nombre del repo)
- cd nombreProyecto(salido del repo)
- git status 
    - Saber la rama.
    - Saber si es un repo.
    - Para saber el estado (o sea, si hay cambios locales).
- git pull origin master  
    - se ejecuta cuando queremos traer los cambios del repositorio remoto
    - siempre que trabajen en equipo procuren hacer un pull de la rama principal de trabajo.
    - ``` master es el nombre de la rama, siempre verifica de que rama quieres traer los cambios ```

- git checkout -b (nombredemirama)
    - la bandera -b cambia y crea nueva rama
    - sin la -b  solo cambiamos a nuestra rama
- git fetch --all
    - para traer todas las ramas

### ¿Qué pasa si tengo un conflicto con un Pull Request?

- Primero hay que identificar que rama a la que quiero subir mis archivos.
- Luego, me traje los cambios con un 
    - git pull origin nombreRamaDeCambiosATraer
- Resolver el conflicto en VSCode
- Agregar mis archivos al área de staging
    - git add (nombre del archivo, "." ó -A)
- Hacer un commit, ya sea en VSCode con la palomita en la sección de git con el mensaje pre cargado
    - O en la console con git commit -m "el mensaje para identificar el merge"

- Podemos internar de nuevo el PR(pull request) sólo después de subir los cambios a github(al repositorio remoto)
    - git push origin nombreDeMIRAMA

Happy Hacking!


# Viajes en el tiempo con Git

### Que significan y para que sirven las siguientes palabras clave...
- **local** : Directorio de trabajo de nuestro repositorio en nuestra maquina.
- **remote(remoto)** : Muestra la lista de repositorios remotos configurados en mi repositorio local y tambien se utiliza para agreagar un repositorio local a un reporitorio remoto.
- **init(initialize)** : Crea un repositorio de Git vacío o reinicializa uno existente.
- **clone(clonar)** :  Clona un repositorio en un nuevo directorio.
- **add(Agregar)** : Agregar contenido de archivos al índice(stage).
- **commit(cometer o confirmar)** : Cuando el archivo que tenemos en el stage le hacemos un commit sale de ahi y pasa al estado de commited  y estos cambios del archivo quedan registrados en el repositorio.
- **push(empujar)** : Envia los cambios en mi local a mi reposiorio remoto.
-  **pull(jalar)** : Actualiza el repositorio local con los nuevos commits, en otras palabras busca(fetch) y combina(merge) cambios remotos.
merge(unir o fusionar): Une otras ramas con mi rama actual.

#### Fases en git:
1. untracked: No se lleva registro de un archivo.
2. tracked: Ya hay registro de los cambios del archivo
3. modified: El archivo Esta siendo modificado
4. staged: Se añadio para hacer un snapshot o commit
5. commited: Un archivo que ya se respaldo, se le hizo un snapshot en el tiempo.

#### ¿Que son las cosas que NO se deben hacer en un repositorio de GIT?
- No borrar la carpeta git de tu directorio de trabajo porque se perderia el repositorio, no se pierden los archivos.
- No desarrollar en la rama master.
- No hacer un push del origin al master porque entonces se sobreescribe el master que esta en el origin
- En el servidor git remoto no hacer el pull request a master.

#### ¿A que año debía volver Marty McFly para reestablecer la linea de tiempo?
1958

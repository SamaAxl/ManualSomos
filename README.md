## Comandos de git utilizados en clase:
Sirve para crear un nuevo repositorio de Git, o para convertir uno ya existente y sin versión a uno de Git.
```
git init <nombre del proyecto?>
```

Sirve para guardar los cambios hechos, entre las comillas van los detalles de los mismos. No fusiona los cambios con la rama Main.
```
git commit -m "<mensaje a enviar>"
```

Permite desplazarse entre las distintas ramas del repositorio, extrayendo una copia local de los archivos de los mismos en el repositorio local.
```
git checkout
```

Este comando se utiliza para añadir un repositorio remoto al repositorio local de git.
```
git remote add origin <host o URL remota>
```

Se utiliza para listar todas las ramas o branch presentes en el repositorio.
```
git branch
```

Se utiliza para eliminar la rama con el nombre establecido.
```
git branch -d <branch>
```

Se utiliza para eliminar el archivo establecido.
```
git rm filename.txt
```

Extrae y descarga contenido del repositorio remoto y actualizar el local, combinacion de fetch y merge.
```
git pull
```

Accion de crear la copia de un repositorio existente, el cual se guarda de forma local, copiando todo el contenido y creando un branch inicial.
```
git clone nombreusuario@host:/path/to/repository
```

Agrega el archivo al repositorio, tambien es posible utilizarse para actualizar un archivo.
```
git add <filename>
```

Se introduce el correo de la cuenta para el repositorio que dara acceso a los commit que se vayan a enviar.
```
git config --global user.email 
```

Establece el nombre de usuario de manera global dejando a Git el usar esa informacion para todo lo que se llegue a realizar.
```
git config --global user.username
```

Sirve para mostrar el estado del repositorio dejando ver la pista de filas y los cambios.
```
git status:
```

Remplaza master por la rama a la cual se quiere enviar los cambios
```
git push origin <master>
```

Sirve para fusionar otra rama a tu rama activa
```
git merge <branch> 
```


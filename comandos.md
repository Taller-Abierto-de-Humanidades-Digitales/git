
## Comandos básicos

* Iniciar un repositorio

`git init`


* Revisar el estado del repositorio

`git status`


* Añadir todos los cambios

`git add .`


* Añadir cambios de un archivo específico

`git add nombre_archivo.txt`


* Acometer los cambios

`git commit -m "detalle del commit"`



## Trabajar con repositorios remotos

* Añadir remoto

`git remote add https://direccion-repo-remoto.git`


* Listar remoto

`git remote -v`


* Subir a repositorio remotos

`git push -u origin brazo` 


Traer todos los cambios del remoto al local (todas las ramas)
```git
git fetch origin
```

Traer todos los cambios desde una rama específica (p. ej. `main`)
```git
git fetch origin main
 ```

Realiza estos cambios de manera más "agresiva"
```git
git pull origin
```

## Clonar repositorios remotos

`git clone https://direccion-repo-remoto.git` 

## Trabajar con ramas

* Listar ramas

`git branch`

* Crear rama

`git branch nombre_de_la_rama`


* Moverse entre ramas

`git checkout rama_destino`

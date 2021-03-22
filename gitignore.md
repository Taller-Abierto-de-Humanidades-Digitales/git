# El archivo `.gitignore`

El archivo .gitignore sirve para evitar que se sincronicen ciertos archivos o tipos de archivos, tanto en el repositorio local como en el remoto.

Puede crear el archivo de muchas maneras. Una de ellas es mediante la línea de comandos, con la siguiente instrucción:

```
touch .gitignore
```

El archivo se puede modificar desde cualquier editor de texto plano.

Algunos ejemplos de cómo "ignorar" archivos son los siguientes:

## Ignorar un archivo por nombre

`nombre_del_archivo.ext`

## Ignorar todos los archivos que empiecen por punto

`.*`

## Ignorar todos los archivos de cierto tipo

`*.doc`

## Ignorar todos los subdirectorios

`/*`

## Ignorar un subdirectorio específico

`/nombre_del_directorio`

## Ignorar todos los directorios que empiecen con un guión de piso

`_*`


Puedes ver un archivo de ejemplo en [ejemplos/gitignore](ejemplos/gitignore)
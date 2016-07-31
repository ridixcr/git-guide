# Git - Guia en Español
una guía sencilla para comenzar con git. sin complicaciones ;)
## Configuración
[Descarga git para OSX](https://code.google.com/archive/p/git-osx-installer/downloads)

[Descarga git para Windows](https://git-for-windows.github.io/)

[Descarga git para Linux](https://git-scm.com/download/linux)

## Crea un repositorio nuevo
Crea un directorio nuevo, ábrelo y ejecuta
`git init`
para crear un nuevo repositorio de git.

## Hacer checkout a un repositorio
Crea una copia local del repositorio ejecutando
`git clone /path/to/repository`
Si utilizas un servidor remoto, ejecuta
`git clone username@host:/path/to/repository`

## Flujo de trabajo
Tu repositorio local esta compuesto por tres "árboles" administrados por git. El primero es tu `Directorio de trabajo` que contiene los archivos, el segundo es el `Index` que actua como una zona intermedia, y el último es el `HEAD` que apunta al último commit realizado.

## add & commit
Puedes registrar cambios (añadirlos al Index) usando
`git add <filename>`
`git add .`
Este es el primer paso en el flujo de trabajo básico. Para hacer commit a estos cambios usa
`git commit -m "Commit message"`
Ahora el archivo esta incluído en el HEAD, pero aún no en tu repositorio remoto.



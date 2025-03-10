# Guia de comandos BASH y GIT
El proposito de este instructivo es complementar los conocimientos de GIT y servir como referencia en el proceso de trabajo de desarrollo sincronizado junto a diferentes equipos, para facilitar el aprendizaje.

## Algunos codigos de GitBash 

### Ver el directorio de un proyecto
`pwd` 

###  Listar archivos de una carpeta
`ls`

### Activar virtual enviroment
`source /Scripts/activate`

### Crear carpeta
`mkdir "Nombre carpeta"` 

## Ciclo de Vida del Git
#### Comandos GIT ####

Los siguientes comandos tienen como objetivo servir como guia para el aprendizage como tambien el manejo y la gestion de versiones a traves de la herramienta GIT.

### 1) Ver la configuracion actual del GIT.
`git config --list`

### 2) Revisar si esta lista la configuracion

`git config --global user.name ` este comando nos permite configurar el nombre de usuario que se utilizara en GIT.

`git config --global user.email ` este comando nos permite configurar el email del usuario que se utilizara en GIT.

### Configuracion del Usuario
`git config --global user.name "Tu Nombre" `

### Configuar corre de uso en git
`git config --global user.email "jose.cortes@tellus-mining.com"`

### Iniciar el repo
`git init`

##### Si estas iniciando
#### Crear commit

### Si estas iniciado
#### Agregar el remote
linkear el github con el repositorio 

`git remote add origin "SSH"git@f97d01d010a9:t004023-soporte-estrat-gico-y-op-ahs-es-amsa/plataforma-ahs.git" `

### Para verificar si esta configurado elremote 
`git remote -v `

### Para Modificar el origin a url
`git remote set-url origin https://github.com/usuario/nuevo-repo.git `

`http://192.168.68.5/t004023-soporte-estrat-gico-y-op-ahs-es-amsa/plataforma-ahs`

### Hacer el pull
`git pull origin "main" #Tiene que ser la rama que quieres bajar.`

### Revisar el estado de modificacion de los archivos
`git status`

### Guardar los cambios
`git add .`

### Hacer guarda en el git en la rama registrado (Local).
`git commit -m "ESTANDAR COMMENTS: blablabla"`

### Hacer un push
`git push origin main`

### Merge


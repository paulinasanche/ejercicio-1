# Modulo 0
## Comandos básicos de linux
- `pwd` Print work directory: me dice en qué carpeta estoy
- `ls` Listar fichero: Me muestra los archivos y carpetas del directorio en el que me encuentro
- `clear` Limpiar la pantalla
- `ls -la` Muestra los archivos con detalle de permisos
- `mkdir` Crear carpeta
- `cd` [carpeta] Change directory: Para dirigirse a la carpeta en mención
- `cd ..` Para salir a la carpeta inmediatamente anterior
- `touch` [NombreArchivo] Crea un archivo nuevo de cualquier tipo
- `nano` [NombreArchivo] Crea un archivo y solicita alguna información de contenido de archivo (modificable. Para modificar uso el mismo cómando como si lo estiviese creando)
- `rm - rf` [NombreDirectorio] Elimina de manera forzosa el recurso. OJO!

## Instrucciones GIT
### Configuración de usuario
`git config --global user.name "Nombre Apellido" ` <br>
`git config --global user.email "email@email.com" ` <br>
<br>
### Para un proyecto nuevo
`git init` Inicializa el repositorio (carpeta oculta.git dentro del proyecto)<br>
`git add .` Es la forma más sencilla para agregar los elementos a nuestra área de trabajo <br>
`git add -A` Otra forma de agregar los archivos <br>
`git add <NombreArchivo>` Para agregar un archivo <br>
`git status` Para ver el estado de los archivos respecto a nuestra área de trabajo <br>
`git add *.html` Vincula los archivos .html a nuestra área de trabajo<br>
`git add CSS/` Vincula los archivos de estilo CSS<br>
`git commit -m 'El mensaje entre comillas'` Para describir cambios <br>

### Vincular un repositorio
1. Se crea el repositorio con el nombre del proyecto en Github, este debe ir vacío, sin readme, licencias, etc.
2. Se renombra el branch con `git branch -M Main`
3. Se agrega la url del repositorio con el comando:
`git remote add origin <URL del repositorio>`
4. Se hace el push `git push -u origin main`

## Instrucciones Markdown
Se puede usar en github o en archivos.md
~~~
# Título
## Subtítulo
### Subtítulo más pequeño

Para listas desordenadas:
Se pone un guión o asterisco seguido de espacio y luego el contenido del item

- Elemento 1

Para lista numerada:
Se pone el número seguido de punto, espacio y luego el contenido del item

1. Elemento 1
2. Elemento 2
3. Elemento 3

Para lista de tareas:
Se debe poner un guion al inicio para que me reconozca que es una lista, luego espacio y luego corchetes con espacio o X en el interior en caso de que sea una tarea completada
- [ ] Hacer ejercicios

Para imagenes o videos se vincula de la siguiente manera:
![Texto que quiero que aparezca si no carga multimedia](URL del recurso)

Para incluir sintaxis de código:
Se usan 3 backticks al inicio, se menciona el lenguaje en el cual fue escrito el código y posteriormente se incluye el código. Al final se cierra con los 3 backticks.
``` html
      <h> Hola mundo </h1>
```
~~~




# Parametros_API
API en lenguaje Go con ayuda del framework Beego y base de datos relacional PostgreSQL sobre una base de datos suministrada y llamada Parametros.
## Tecnologías Implementadas
- Golang
- Beego
- PostgreSQL
## Instalación
> Dirigirse a la carpeta de go en la que quiere clonar el proyecto 

`cd go/src`
> Clonar el repositorio

`git clone https://github.com/CrisEs2506/parametros_crud.git`
> Entrar en la carpeta del proyecto clonado

`cd parametros_crud`
> Instalar dependencias del proyecto

`go get`
> Crear archivo para las variables de entorno .env
```
export PARAMETROS_PGUSER = [nombre del usuario de postgres]
export PARAMETROS_PGPASS = [contraseña del usuario de postgres]
export PARAMETROS_PGHOST = [nombre o número de host]
export PARAMETROS_PGPORT = [puerto en que corre postgres]
export PARAMETROS_PGDB = [nombre de la base de datos en donde se encuentra el schema]
export PARAMETROS_PGSCHEMA = [nombre del schema]
```
## Ejecución del Proyecto
`bee run`

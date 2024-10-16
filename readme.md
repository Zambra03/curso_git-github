# Curso Git / GiyHub

En este espacio se espera obtener informacion valiosa sobre el desarrollo del curso de Git Profesional (Codigo Facilito) como muestra del interes sobre aprender y mejorar sobre esta tecnologia

GIT -> Repositorio (Espacio en el que se guarda info de las versiones de un proyecto)

CLASE 1 -> Configuracion:

--Paso 1:

Crear una cuenta de GitHub

--Paso 2:

Instalar o ver si ya se tiene instalado alguna version de Git -> git --version

--Paso 3:

Configurar las credenciales de Git

- git config --global user.name "username"
- git config --global user.email "email@example.com"

----- Ejemplo de mini proyecto ------

--Paso1:

Crear una carpeta -> En el escritorio llamada curso-git

--Paso2:

En la consola desde el directorio de la carpeta inicializar el proyecto -> git init
(Se crea una carpeta llamada ".git" la cual contendra todas las versiones del proyecto)

--Paso3:

Hacer uso de las 3 Areas de Git

\*\* Area 1 -> Area de trabajo

Se encuentran los archivos que estamos modificando:

- Un cambio esta alli cuando git aun nos sabe de su existencia
- Se pueden perder facilmente

\*\* Area 2 -> Area de staging

- Git conoce sobre los cambios pero estos no hacen parte oficialmente del historial de versiones

\*\* Area 3 -> Area de repositorio

- Es donde ya se encuentra las version con sus cambios
- Se encuentra el historial completo

----- Analogia con galletas -----

1 -> Haciendo galletas 2 -> Empacando galletas 3 -> Galletas ya empacadas
Area de trabajo Area de staging Area de repositorio
----------------> -------------->
git add git commit

## Comandos:

git status -> Para ver el estado y saber en que area se encuentra (muestra lo que esta en el area de trabajo y are de staging)
git add nombre_archivo -> añade del area de trabajo al area de staging el archivo que se coloque
git add . -> añade del area de trabajo al area de staging todos los archivos
git commit -> añade del area de staging al area del reporitorio una version
git log -> Me muestrael historial de commits (muestra lo que esta en el area del repositorio)

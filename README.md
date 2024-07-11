# Block3 Create Repo Git

## Descripción del Proyecto

Este proyecto Maven, `block3-create-repo-git`, demuestra cómo crear y gestionar un repositorio Git utilizando IntelliJ IDEA. Siguiendo los pasos descritos, aprenderemos a:

1. Crear y editar archivos.
2. Realizar commits.
3. Subir los cambios a GitHub.
4. Gestionar versiones y conflictos.
5. Trabajar con ramas y mergear cambios.

## Instrucciones

### 1. Crear Archivos y Primer Commit

1. En el directorio `PROYECTO GIT`, crear los archivos `fichero1.txt` y `fichero2.txt`.
2. Editar `fichero1.txt` y escribir: `Primera línea de fichero1`.
3. Inicializar el repositorio Git:
   - En IntelliJ IDEA, abrir el proyecto.
   - Ir a `VCS` > `Enable Version Control Integration` > Seleccionar `Git`.
4. Realizar el primer commit:
   - `VCS` > `Commit` > Seleccionar `fichero1.txt` > Añadir mensaje de commit y confirmar.

### 2. Editar Segundo Archivo y Segundo Commit

1. Editar `fichero2.txt` y escribir: `Primera línea de fichero2`.
2. Realizar un nuevo commit.

### 3. Subir a GitHub

1. Crear un repositorio en GitHub.
2. En IntelliJ IDEA, ir a `Git` > `Manage Remotes` > Añadir URL del repositorio GitHub.
3. Subir los cambios:
   - `VCS` > `Git` > `Push`.

### 4. Revertir y Recuperar Cambios

1. Volver al punto donde `fichero1.txt` no tiene la línea “Primera línea de fichero1”:
   - `Git` > `Show History` > Seleccionar commit y `Checkout`.
2. Volver al estado final:
   - `Git` > `Show History` > Seleccionar el commit final y `Checkout`.

### 5. Clonar Repositorio

1. Clonar el repositorio en otro directorio llamado `COPIA PROYECTOGIT`:
   - `Git` > `Clone` > Introducir URL del repositorio y seleccionar directorio.

### 6. Modificar y Subir Cambios desde el Clon

1. Modificar `fichero1.txt` añadiendo: `Segunda línea de fichero1`.
2. Realizar commit y push.

### 7. Modificar y Subir Cambios en el Proyecto Original

1. Modificar `fichero1.txt` añadiendo: `Tercera línea de fichero1`.
2. Realizar commit y push (habrá un conflicto).
3. Solucionar conflictos y subir cambios.

### 8. Crear y Trabajar con Ramas

1. En `COPIA PROYECTOGIT`, crear la rama `cambio1`:
   - `Git` > `Branches` > `New Branch`.
2. Modificar `fichero2.txt` añadiendo: `Segunda línea de fichero2`.
3. Realizar commit y push.

### 9. Mergear Cambios y Subir

1. Volver al directorio `PROYECTOGIT`.
2. Hacer un pull y mergear los cambios de `cambio1` en `main`:
   - `Git` > `Branches` > `Merge`.
3. Subir los cambios a GitHub.

## Herramientas

- **IDE**: IntelliJ IDEA
- **VCS**: Git

## Requisitos

- Tener Git instalado.
- Tener una cuenta en GitHub.
- Tener una cuenta en GitLab.

## Autor

- [Ramon Monje](https://gitlab.nfqsolutions.es/nworld/nter/engineering/develop-team/ramon-monje/block3-create-repo-git)

# Creación de un Repositorio Local con Git

## Introducción
Git es un sistema de control de versiones distribuido que permite gestionar cambios en el código fuente de manera eficiente. En este documento, aprenderás cómo crear y administrar un repositorio local en Git.

## Configuración Inicial
Antes de comenzar, es recomendable configurar tu usuario de Git con los siguientes comandos:

```sh
# Configurar nombre de usuario
git config --global user.name "Tu Nombre"

# Configurar correo electrónico
git config --global user.email "tuemail@example.com"
```

## Creación de un Repositorio Local
Para crear un repositorio local, sigue estos pasos:

1. **Navega al directorio donde quieres crear el repositorio:**
   ```sh
   cd ruta/del/proyecto
   ```
2. **Inicializa un nuevo repositorio Git:**
   ```sh
   git init
   ```
   Esto creará un directorio oculto `.git`, donde se almacenará la información del repositorio.

## Añadir y Confirmar Cambios
Una vez que tienes el repositorio inicializado, puedes agregar archivos y realizar commits:

1. **Añadir archivos al área de preparación:**
   ```sh
   git add nombre_del_archivo
   ```
   O para agregar todos los archivos:
   ```sh
   git add .
   ```
2. **Realizar un commit con un mensaje descriptivo:**
   ```sh
   git commit -m "Mensaje descriptivo del cambio"
   ```

## Ver el Estado del Repositorio
Puedes verificar el estado de tu repositorio con:
```sh
git status
```

## Ver Historial de Cambios
Para ver los commits realizados, usa:
```sh
git log
```

## Conclusión
Un repositorio local permite gestionar cambios antes de sincronizarlos con un repositorio remoto. Es una herramienta esencial en el desarrollo de software colaborativo.

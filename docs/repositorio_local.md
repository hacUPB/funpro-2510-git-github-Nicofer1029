# Creación de un Repositorio Local con Git

![GitHub](https://vabadus.es/images/cache/imagen_nodo/images/articulos/5c9deef127c7d783462103.png)

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

1. **Navega hasta la carpeta donde quieres crear el repositorio:**
   ```sh
   cd ruta/del/proyecto
   ```
2. **Inicializa un nuevo repositorio Git:**
   ```sh
   git init
   ```
   Esto creará una carpeta oculta `.git`, donde se almacenará la información del repositorio.

## Añadir Cambios
Una vez que tienes el repositorio inicializado, puedes agregar archivos y realizar commits:

1. **Añadir archivos al área de preparación:**
   ```sh
   git add nombre_del_archivo
   ```
   **Añadir todos los archivos al área de preparación**
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

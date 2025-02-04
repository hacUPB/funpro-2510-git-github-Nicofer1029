# Uso de la Consola

## Introducción
La consola de comandos es una herramienta fundamental para interactuar con el sistema operativo mediante líneas de comandos. En este documento, se describen los comandos básicos para navegar entre directorios, crear carpetas y archivos, y realizar operaciones esenciales en el entorno de trabajo.

## Navegación entre Directorios
Para moverte entre directorios, puedes utilizar los siguientes comandos:

- **Ver el directorio actual:**
  ```sh
  pwd
  ```
- **Listar archivos y carpetas en el directorio actual:**
  ```sh
  ls  # En Linux/macOS
  dir # En Windows
  ```
- **Cambiar de directorio:**
  ```sh
  cd nombre_del_directorio
  ```
- **Regresar al directorio anterior:**
  ```sh
  cd ..
  ```

## Creación de Directorios y Archivos
Para organizar los archivos de un proyecto, es común crear directorios y archivos nuevos:

- **Crear un nuevo directorio:**
  ```sh
  mkdir nombre_del_directorio
  ```
- **Crear un nuevo archivo vacío:**
  ```sh
  touch nombre_del_archivo.txt  # En Linux/macOS
  echo. > nombre_del_archivo.txt  # En Windows
  ```

## Eliminación de Directorios y Archivos
Para eliminar archivos y carpetas de manera segura:

- **Eliminar un archivo:**
  ```sh
  rm nombre_del_archivo
  ```
- **Eliminar un directorio vacío:**
  ```sh
  rmdir nombre_del_directorio
  ```
- **Eliminar un directorio con todo su contenido:**
  ```sh
  rm -r nombre_del_directorio
  ```

## Comandos Adicionales
Algunos comandos adicionales que pueden ser útiles:

- **Limpiar la pantalla de la terminal:**
  ```sh
  clear  # En Linux/macOS
  cls    # En Windows
  ```
- **Ver el historial de comandos utilizados:**
  ```sh
  history  # En Linux/macOS
  doskey /history  # En Windows
  ```

## Conclusión
Dominar el uso de la consola es esencial para la gestión eficiente de proyectos y el uso de herramientas como Git. Practicar estos comandos facilitará el trabajo en entornos de desarrollo.

[![Review Assignment Due Date](https://clas:sroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WV8VkdWq)
# Bitácora
Nombre del estudiante: Nicolás Fernández Barreto
Id.: 000579043

# Proyecto de Programación con Git y GitHub
## Descripción
Este proyecto tiene como objetivo aprender a organizar y manejar las versiones en un proyecto de programacion, en el cual el codigo no es el enfoque principal, sino, la forma de organizar los elementos y desenvolverse con facilidad en Git y Github. Ademas de aprender a sicnronizar los datos con GitHub, desde la consola para poder tranajar localmente y luego tener la infprmacion guardada en la nube.

## Estructura del Proyecto
El proyecto se organiza en las siguientes carpetas:

```
mi_proyecto/
│-- src/              # Código fuente del proyecto
│   ├── main.c        # Script en lenguaje C
│-- docs/             # Documentación del proyecto
│   ├── uso_consola.md
│   ├── repositorio_local.md
│   ├── repositorio_remoto.md
│-- images/           # Imágenes del proyecto
│-- .gitignore        # Carpeta para excluir archivos innecesarios
│-- README.md         # Es lo primero que ve el usuario, descripcion general del proyecto
```

## Clonación y Ejecución del Proyecto
Para obtener una copia local de este proyecto, sigue estos pasos:

1. Clona el repositorio con el siguiente comando:
   ```sh
   git clone <URL_DEL_REPOSITORIO>
   ```
2. Crear las carpetas docs/ src/ images/
   ```sh
   mkdir "Nombre de la carpeta"
   ```
3. En la carpeta docs/ crear archivos md
   ```sh
   touch "repositorio_local.md"
   touch "repositorio_remoto.md"
   touch "uso_consola.md"
   ```
5. En la carpeta src/ crear script con codigo fuente
   ```sh
   touch "codigo fuente.c"
   ```
6. Crear archivo .gitignore
   ```sh
   touch ".gitignore"
   ```
6. Crear bitacora README.md
   ```sh
   touch "README.md"

6. Hacer 10 commits especificando cada una de las acciones
   ```sh
   git commit -m "Nombre de la accion realizada"
   ```

6. Sincronizar con Git Hub
   ```sh
   git push
   ```

## Tabla de contenido
| Archivos   md     
|------------
|- [Uso de la Consola](docs/uso_consola.md)
|- [Creación de Repositorio Local](docs/repositorio_local.md)
|- [Repositorio Remoto y Sincronización](docs/repositorio_remoto.md)  

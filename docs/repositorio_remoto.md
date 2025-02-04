# Creación de un Repositorio Remoto en GitHub y Sincronización con Git

## Introducción
Un repositorio remoto permite almacenar el código en plataformas como GitHub, facilitando la colaboración y el control de versiones. En este documento, aprenderás cómo crear un repositorio en GitHub y sincronizarlo con un repositorio local.

## Creación del Repositorio Remoto
1. Accede a [GitHub](https://github.com) e inicia sesión.
2. Haz clic en el botón **New Repository**.
3. Especifica un nombre para el repositorio y elige si será público o privado.
4. No selecciones ninguna opción para inicializarlo con archivos.
5. Haz clic en **Create Repository**.

## Conexión con el Repositorio Local
Si ya tienes un repositorio local creado, sigue estos pasos para vincularlo con el repositorio remoto:

1. **Agrega el repositorio remoto:**
   ```sh
   git remote add origin https://github.com/usuario/nombre-del-repositorio.git
   ```
2. **Verifica que el repositorio remoto se agregó correctamente:**
   ```sh
   git remote -v
   ```
3. **Sube los cambios al repositorio remoto:**
   ```sh
   git push -u origin main
   ```
   Si tu rama principal se llama `master`, usa:
   ```sh
   git push -u origin master
   ```

## Clonar un Repositorio Remoto
Si deseas obtener una copia de un repositorio existente en GitHub, usa:
```sh
git clone https://github.com/usuario/nombre-del-repositorio.git
```

## Sincronización con Cambios Remotos
Para mantener el repositorio local actualizado con los cambios remotos, usa:
```sh
git pull origin main
```

## Conclusión
Conectar un repositorio local con un remoto permite colaborar con otros desarrolladores y mantener un control de versiones eficiente.

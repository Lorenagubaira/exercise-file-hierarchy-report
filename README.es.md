<!-- hide -->
# Trabajar con el Sistema de Archivos del Computador
<!-- endhide -->

Otra estructura de datos muy utilizada en el mundo de la codificación son los árboles (trees), por ejemplo:

1. El sistema de archivos del computador es un árbol.
2. El DOM (Document Object Model) es un árbol.

En este caso, usaremos el concepto de árbol de jerarquía  para escanear y navegar a través de un grupo de archivos en un computador.

<how-to-start>
    
## 🌱  Cómo iniciar este proyecto

No clones este repositorio porque usaremos una plantilla diferente.  

Recomendamos abrir `python boilerplate`, utilizando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternativamente, puedes [clonar el repositorio de GitHub](https://4geeks.com/how-to/github-clone-repository) en tu computadora local utilizando el comando `git clone`.  

Este es el repositorio que necesitas abrir o clonar:  

```sh
$ git clone https://github.com/4GeeksAcademy/flask-rest-hello
```

### Pasos

1. Instala los paquetes de la dependencia
```sh
$ pipenv install --python 3
```

2. Ingresa a tu entorno virtual escribiendo: 

```sh
$ pipenv shell
```

3. Puedes ejecutar el proyecto escribiendo:

```sh
$ python src/app.py
```
4. También puedes ejecutar las pruebas o tests del proyecto:

```sh
$ python src/test.py
```

💡 Importante: Recuerda actualizar el `remote` del proyecto con el de tu repositorio usando `git remote set-url origin <your new url>`, y luego guardar tu código en tu nuevo repositorio usando `add`, `commit` y `push`.

</how-to-start>

# 📝 Instrucciones

Muestra el conjunto de archivos que están en la carpeta `data-files`, escribe un programa que cree un archivo JSON llamado report.json cuya salida sea el siguiente reporte:


```json
{
    "levels": 3,
    "total_files_found": 5,
    "files_found": ["file_one.csv", "file_two.json"],
    "file_extentions_found": ["csv", "json"],
    "total_folders_found": 3,
    "folders_found": ["folder_one","folder_tow"],
    "links_found": 12,
    "broken_links_found": 4,
}
```

Explicación del Reporte o informe:

| Propiedad  | Descripción |
| --------  | ----------- |
| levels    | Cantidad de conexiones entre el nodo superior y el nodo inferior |
| total_files_found | cuántos archivos se encontraron, las carpetas no cuentan |
| files_found | nombre de cada archivo encontrado, sin las carpetas |
| file_extentions_found | una lista sin repeticiones de las extensiones de los archivos que se encuentran dentro del árbol|
| total_folders_found | cantidad total de carpetas encontradas, los archivos no cuentan|
| Links found | Cuántas URLs se encontraron comenzando con http o https |
| broken_links_found | Cuántos links o enlaces se rompieron (tienes que usar el método GET y verificar 404) |

## 💡 Hint

1. Empieza por buscar en google `python obtener archivos en carpeta` o  `python get files in folder`.
2. Esta búsqueda también ayuda: `archivo python es un directorio` o `python file is directory` para verificar si el archivo es un directorio o no. 
3. Para buscar en google cómo encontrar links o enlaces dentro del contenido del archivo: `python encuentra todos los links en string` o `python find all links in string`
4. Obtener la extensión del nombre del archivo: `python obtener extensión del archivo`o `python get file extension`

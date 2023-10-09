<div align="center">
    <br/>
    <img src=".github/readme/etsii-claro.png#gh-light-mode-only" height=100 alt="ETSII logo (claro)"/>
    <img src=".github/readme/etsii-oscuro.png#gh-dark-mode-only" height=100 alt="ETSII logo (oscuro)"/>
    <br/>
</div>

# TFG - Memoria

Este repositorio contiene el proyecto $\LaTeX$ empleado para la elaboración de la memoria, así como el documento final (*memoria.pdf*).

## Uso del repositorio

La opción más cómoda y rápida es importar este proyecto en [Overleaf](https://www.overleaf.com) y modificar los ficheros desde ahí.

1. Descarga este repositorio como un fichero `.zip`.
2. Entra en [Overleaf](https://www.overleaf.com) y crea un nuevo proyecto.
3. Importa el fichero `.zip` descargado en el paso 1.

Una vez importado el proyecto, puedes modificar los siguientes ficheros para alterar el contenido de la presentación:

|     Fichero      | Función                                                                                                                       |
|:----------------:| ----------------------------------------------------------------------------------------------------------------------------- |
|   **images/**    | Imágenes utilizadas en el documento.                                                                                          |
|  **packages/**   | Paquetes necesarios para compilar el proyecto, dividido en básicos (comunes) y adicionales (específicos para mi documento).   |
|    **pages/**    | Contenido de la memoria dividido en las secciones obligatorias del documento: portada, resumen, agradecimientos, cuerpo, etc. |
|   `datos.tex`    | Datos del TFG: nombre del alumno, del tutor, del proyecto, departamento, etc.                                                 |
|    `main.tex`    | **Fichero principal**, contiene la estructura del documento.                                                                  |
| `references.bib` | Referencias bibliográficas.                                                                                                   |

## Información del proyecto

Se ha usado [esta plantilla](https://github.com/benhid/TFG-UMA) de proyecto $\LaTeX$ como base para el desarrollo de la memoria de este TFG.

> **Note**  
> Se han modificado los paquetes empleados para mi documento, así como la estructura del mismo, para adaptarse a las necesidades de mi proyecto.
>
> Por ejemplo: se ha eliminado el uso de `pages/01-etiqueta.tex` porque no es necesaria para una entrega digital del documento; no obstante.

# TP N°1 - Ingeniería de Software - UTN FRSF - 2025

## Grupo 12

### Integrantes:
- Agustina, Don
- Tomas, Basualdo
- Juan Blas, Tschopp
- Milton, Mansilla
- Ever Dario, Godoy

### Tecnologías aplicadas
- Java

### Respuestas:

<u>Ejercicio 2:</u>
   
**b -** Para no subir cambios de configuraciones locales se agrega el archivo .gitignore con el nombre de los archivos a ignorar asi Git omitirá estos archivos al hacer git add.

**e -** En Gitflow, para llevar una release al entorno productivo, se lleva el contenido de la rama **release** a la rama **master** con merge a **master** (o crear un Pull Request) y luego se crea una etiqueta (tag) para indicar la versión.

**f -** En Gitflow, se crea una nueva rama **hotfix** desde **main**, se corrige el error, luego se hace un merge a la rama **main**. Luego en esta rama se crea la etiqueta correspondiente a la nueva versión del proyecto.

**j -** En Gitflow, primero se crean la rama **develop** y a partir de ella la rama **feature** en la cual se realizan los cambios. Después, se fusionan los cambios de la rama **feature** a la rama **develop**. Luego, se crea una rama **release** a partir de la rama **develop**, en la cual se incorporan los cambios de **develop** y finalmente se fusiona la rama **release** en **main** para llevar los cambios a producción. Por último se crea en la rama **main** un tag de versión.

<u>Ejercicio 3:</u>

**a -** En el archivo README podemos documentar de qué trata el proyecto, quiénes son los creadores, quiénes son los que lo mantienen, cómo utilizar el proyecto, cómo se instala el proyecto, las tecnologías aplicadas, manual de usuario y demás documentación relevante.

Nosotros particularmente utilizamos el archivo README para responder a las consignas del Trabajo Práctico, indicando también el número de grupo, los integrantes, la tecnología aplicada y título del proyecto.

**b -** A los colaboradores externos que realicen Pull Request se les solicitará una descripción de la modificación y la especificación de los archivos afectados. GitHub permite agregar un resumen de los cambios propuestos, seleccionar etiquetas, hitos y usuarios asignados. Con esta información, los revisores de los potenciales cambios entrantes pueden analizar dichos cambios realizados a través de los commits y enviar comentarios antes de aceptarlos, de ser necesario.

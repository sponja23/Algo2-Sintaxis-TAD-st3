# Sintaxis para escribir TADs en Sublime Text

Un paquete de sublime text para escribir los TADs y sus aspectos de diseño, basado en [un paquete similar para Atom](https://github.com/luisbustamante097/language-tad-aed2).

![Imagen](./imagenes/ejemplo_tad.png)

![Imagen](./imagenes/ejemplo_design.jpeg)

## Instalación

1. Instalar [Sublime Text](https://www.sublimetext.com/).
2. Instalar [Package Control](https://packagecontrol.io/installation).
3. Abrir la consola con `Control+Shift+P`, ejecutar `Package Control: Install Package`, y elegir Algo2-TADs.

Si lo habían instalado manualmente, borren el archivo `Algo2-TADs.sublime-package` que quedó en la carpeta `Installed Packages/` (está un directorio arriba de la carpeta `Packages/`, que se abre usando el menú de Sublime: `Preferences > Browse Packages...`).

## Uso

### Sintaxis

Para ver cómo funciona la sintaxis, pueden descargarse los [ejemplos](./ejemplos/).

### Símbolos

Para escribir símbolos matemáticos, yo uso el paquete [`UnicodeMath`](https://github.com/mvoidex/UnicodeMath).

### Exportar a PDF

Para exportar el archivo a PDF, se puede usar el paquete [`ExportHtml`](https://packagecontrol.io/packages/ExportHtml). Con el comando `Control+Shift+P > Export to HTML: Show Export Menu` abren una ventana del browser que descarga el PDF.

Las opciones que vienen por default en el menú de exportar son un poco molestas (el PDF viene con contador de líneas y un header con el nombre de archivo). Para cambiarlas, tienen que agregar una opción nueva con `Control+Shift+P > ExportHtml: Settings`. En el archivo `export-html-settings.json` dejé una configuración para copiar y pegar que agregar una opción de TADs.

## Visual Studio Code

Si alguien tiene ganas puede crear una extensión de vscode usando el archivo `tad.tmLanguage` en la carpeta `legacy` y siguiendo los pasos en este [thread de StackOverflow](https://stackoverflow.com/questions/30687783/create-custom-language-in-visual-studio-code).

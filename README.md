# Sintaxis para escribir TADs en Sublime Text

Un paquete de sublime text para escribir los TADs y sus aspectos de diseño.

![Imagen](./imagenes/ejemplo_tad.png)

![Imagen](./imagenes/ejemplo_design.jpeg)

## Instalación

1. Instalar [Sublime Text 3](https://www.sublimetext.com/3).
2. Instalar [Package Control](https://packagecontrol.io/installation).
3. Abrir la consola con `Control+Shift+P`, ejecutar `Package Control: Install Package`, y elijan Algo2-TADs.

Si lo habían instalado manualmente, borren el archivo `Algo2-TADs.sublime-package` que quedó en la carpeta `Installed Packages/` (está un directorio arriba de la carpeta `Packages/`, que se abre usando el menú de Sublime: `Preferences > Browse Packages...`).

## Otros Paquetes

- **Símbolos**: Yo uso [`UnicodeMath`](https://github.com/mvoidex/UnicodeMath).
- **PDF**: Si lo abren en el browser con [`ExportHtml`](https://packagecontrol.io/packages/ExportHtml) pueden imprimirlo para pasarlo a PDF desde ahí (en general con `Control+P`).

## Visual Studio Code

Si alguien tiene ganas puede crear una extensión de vscode usando el archivo `tad.tmLanguage` en la carpeta `legacy` y siguiendo los pasos en este [thread de StackOverflow](https://stackoverflow.com/questions/30687783/create-custom-language-in-visual-studio-code).

🌐 Proyecto Web – Aprendiendo Git y GitHub

Este proyecto forma parte de una práctica para aprender Git, ramas, GitHub, Pull Requests y documentación en Markdown, desarrollando una página web sencilla en HTML.

📋 Tabla de Contenidos

Instalación

Estructura del Proyecto

Mejoras Implementadas

Uso de Ramas

Autor

🚀 Instalación

El proyecto se encuentra en la carpeta local tarea01. Para abrirlo:

Accede a la carpeta:

~/cd tarea01

Abrir el archivo principal y modificarlo con texto html:

nano index.html

El proyecto ya está vinculado con GitHub:

git remote -v

Obtenemos:

origin  git@github.com:rhernandezmy/MPO-TAREA01.git (fetch)
origin  git@github.com:rhernandezmy/MPO-TAREA01.git (push)

📁 Estructura del Proyecto
tarea01/
|-- index.html        # Página principal del proyecto
|-- README.md         # Documentación del proyecto
|-- .gitignore        # Archivos y carpetas excluidos de Git
|-- .vscode/          # Configuración local del editor (archivo no subido a github)

✨ Mejoras Implementadas

Menú de navegación en la parte superior de la página

Footer con enlaces a redes sociales

Uso de ramas independientes para cada mejora

🌿 Uso de Ramas

Cada mejora se desarrolló en su propia rama:

feature/menu → Menú de navegación

feature/footer → Footer con enlaces

Luego se fusionaron en main mediante Pull Requests en GitHub.

👤 Autor

Proyecto desarrollado por rhernandezmy.

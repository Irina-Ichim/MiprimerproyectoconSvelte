# MiprimerproyectoconSvelteVisualCode
# Mi Primer Proyecto con Svelte

## Descripción
Este es un proyecto de ejemplo para aplicaciones Svelte. Puedes encontrar el proyecto original en https://github.com/sveltejs/template.

## Requisitos Previos
Para trabajar en este proyecto, asegúrate de tener instalado lo siguiente en tu máquina:
- Node.js (versión recomendada).
- Editor de código (Visual Studio Code, Sublime Text, etc.).

## Empezar

1. Instala las dependencias...
```bash
cd mi-proyecto-svelte
npm install

1. ...luego inicia Rollup:
npm run dev
Abre tu navegador y visita localhost:8080. Deberías ver tu aplicación en funcionamiento. Edita un archivo de componente en la carpeta src, guárdalo y recarga la página para ver los cambios.

Modo de aplicación de una sola página
Por defecto, sirv solo responderá a solicitudes que coincidan con archivos en la carpeta public. Esto maximiza la compatibilidad con servidores de archivos estáticos, lo que te permite implementar tu aplicación en cualquier lugar.

Si estás construyendo una aplicación de una sola página (SPA) con múltiples rutas, sirv necesita poder responder a solicitudes para cualquier ruta. Puedes lograrlo editando el comando "start" en el archivo package.json:
"start": "sirv public --single"
Usando TypeScript
Este proyecto viene con un script para configurar un entorno de desarrollo con TypeScript. Puedes ejecutarlo inmediatamente después de clonar el proyecto con:
node scripts/setupTypeScript.js
O puedes eliminar el script con:
rm scripts/setupTypeScript.js
Si deseas usar baseUrl o alias path en tu archivo tsconfig, necesitas configurar @rollup/plugin-alias para que Rollup resuelva los alias. Para obtener más información, consulta esta pregunta de StackOverflow.

Despliegue en la web
Con Vercel
Instala vercel si aún no lo has hecho:
npm install -g vercel
Luego, desde la carpeta de tu proyecto:
cd public
vercel deploy --name mi-proyecto
Con surge
Instala surge si aún no lo has hecho:
npm install -g surge
Luego, desde la carpeta de tu proyecto:
npm run build
surge public mi-proyecto.surge.sh

Este es un tutorial básico para comenzar con Svelte. Puedes personalizarlo según tus necesidades y añadir más información relevante sobre tu proyecto. ¡Espero que te sea útil!


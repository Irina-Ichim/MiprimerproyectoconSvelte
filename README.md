# Mi Primer Proyecto con Svelte 👩‍💻🚀

## Descripción 📝
¡Bienvenido a mi primer proyecto con Svelte! Este es un proyecto de ejemplo para aplicaciones Svelte, basado en el [proyecto original](https://github.com/sveltejs/template). Si estás buscando una introducción a Svelte, ¡has llegado al lugar adecuado!

## Requisitos Previos 🛠️
Antes de sumergirte en este proyecto, asegúrate de tener instalados los siguientes elementos en tu máquina:

- [Node.js](https://nodejs.org) (versión recomendada)
- Editor de código (Visual Studio Code, Sublime Text, etc.)

## ¡Comencemos! 🚀

1. **Instala las dependencias:**
    ```bash
    cd mi-proyecto-svelte
    npm install
    ```

2. **Inicia Rollup:**
    ```bash
    npm run dev
    ```

3. **Observa tu aplicación en acción:**
    Abre tu navegador y visita [localhost:8080](http://localhost:8080). Deberías ver tu aplicación en funcionamiento. Si editas un archivo de componente en la carpeta `src`, guarda los cambios y recarga la página para ver las actualizaciones.

### Modo de Aplicación de Una Sola Página
Por defecto, `sirv` (el servidor utilizado) solo responde a solicitudes que coinciden con archivos en la carpeta `public`. Esto es perfecto para desplegar tu aplicación en cualquier lugar como un archivo estático.

Si estás creando una aplicación de una sola página (SPA) con múltiples rutas, `sirv` debe poder responder a solicitudes para *cualquier* ruta. Puedes lograr esto editando el comando `"start"` en el archivo `package.json`:
```json
"start": "sirv public --single"

Usando TypeScript 📜
Si prefieres trabajar con TypeScript, este proyecto incluye un script para configurar un entorno de desarrollo con TypeScript. Puedes ejecutarlo inmediatamente después de clonar el proyecto con:
node scripts/setupTypeScript.js
También puedes eliminar el script con:
rm scripts/setupTypeScript.js
Si deseas usar baseUrl o alias path en tu archivo tsconfig, necesitas configurar @rollup/plugin-alias para que Rollup resuelva los alias.

Despliegue en la Web 🌐
Con Vercel 🚀
Si deseas desplegar tu aplicación en Vercel, instala vercel si aún no lo has hecho:
npm install -g vercel
Luego, desde la carpeta de tu proyecto:
cd public
vercel deploy --name mi-proyecto

Con surge 🌟
Si prefieres utilizar Surge para el despliegue, instala surge si aún no lo has hecho:
npm install -g surge
Luego, desde la carpeta de tu proyecto:
npm run build
surge public mi-proyecto.surge.sh

¡Y eso es todo! Espero que esta introducción te ayude a dar tus primeros pasos con Svelte. Siéntete libre de personalizar este tutorial según tus necesidades y añadir más información relevante sobre tu proyecto. ¡Feliz codificación! 🎉



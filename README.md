# BajoTerra
Sitio web / repositorio estático para el proyecto "BajoTerra".

Este repositorio contiene un sitio web estático (index.html ya presente). Los archivos añadidos aquí ayudan a publicar automáticamente en GitHub Pages.

Archivos importantes añadidos:

- README.md (este archivo)
- LICENSE (MIT)
- .gitignore
- .gitattributes
- .nojekyll
- .github/workflows/pages.yml (workflow para publicar en GitHub Pages)

Cómo publicar en GitHub (resumen):

1. Crear el repositorio en GitHub con el nombre `BajoTerra` (o usar la interfaz web para crear uno vacío).
2. Inicializar git localmente en la carpeta (si aún no lo está):

   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<TU_USUARIO>/BajoTerra.git
   git push -u origin main

3. El workflow de GitHub Actions (`.github/workflows/pages.yml`) está configurado para ejecutarse en push a `main` o `master`. El flujo sube todo el contenido del repositorio y despliega en GitHub Pages automáticamente.

4. En la configuración del repositorio en GitHub (Settings > Pages), verifica que la fuente de Pages esté en "GitHub Actions" (normalmente se configura automáticamente cuando el workflow corre exitosamente).

Notas:
- Si prefieres publicar desde la rama `gh-pages` en lugar de usar Actions, ajusta la configuración manualmente.
- Reemplaza `https://github.com/<TU_USUARIO>/BajoTerra.git` con la URL real del repositorio.

Versión remota: v1.01.01


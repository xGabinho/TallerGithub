Taller GitHub

Nombre: Gabriel Quevedo
Descripción: Proyecto para aprender Github

Esta descripción fue hecha desde otra rama

## Pasos realizados
1. Se creó `index.html` como base del proyecto.
2. Se creó la rama `feature-estilos` para agregar `style.css` y vincularlo en `index.html`. Se revisó y se hizo merge mediante Pull Request.
3. Se creó la rama `feature-footer` para añadir un `footer` con autor y año. Se revisó y se hizo merge mediante Pull Request.
4. Documentación y commits finales subidos al repositorio.

## Archivos principales
- index.html
- style.css

## Comandos usados (resumen)

git checkout -b feature-estilos
git add .
git commit -m "feat: mensaje"
git push -u origin feature-estilos

crear PR → merge en GitHub

git checkout main
git pull origin main
git checkout -b feature-footer
git add .
git commit -m "feat: mensaje"
git push -u origin feature-footer
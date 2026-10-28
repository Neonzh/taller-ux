# Mis Notas — Laboratorio UX/UI

Aplicación sencilla para agregar, listar y eliminar notas. El rediseño aplica heurísticas de Nielsen, leyes de Fitts, Hick y Miller, principios visuales y criterios básicos de accesibilidad.

## Archivos

- `index.html`: pantalla original de referencia.
- `estilos.css`: estilos de la pantalla original.
- `app.js`: comportamiento de la pantalla original.
- `redisenado/`: versión mejorada de la aplicación.
- `docs/AUDITORIA-UX.md`: auditoría del antes y después.

## Ejecutar

Para ver la versión original, abre `index.html` con Live Server.

Para ver la versión rediseñada, abre `redisenado/index.html` con Live Server.

## Publicar

Después de subir el repositorio, activa GitHub Pages desde **Settings → Pages → Deploy from a branch → main → /(root)**. Para que la versión rediseñada sea la página inicial publicada, copia los archivos de `redisenado/` a la raíz del repositorio antes de hacer el commit final.

Actualiza el enlace con tu usuario y el nombre real del repositorio:
`https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`

## Comprobación

Ejecuta Lighthouse en Chrome o Edge, selecciona Accessibility y Desktop, y guarda capturas reales del antes y del después. La meta del laboratorio es una puntuación de Accesibilidad de 90 o más.

# Remisímetro GPS PWA

PWA para probar un remisímetro/taxímetro con GPS.

## Archivos

- `index.html`
- `manifest.json`
- `service-worker.js`
- `icon-192.png`
- `icon-512.png`

## Subir a GitHub Pages

1. Crear un repositorio nuevo.
2. Subir estos archivos en la raíz del repo.
3. Ir a Settings → Pages.
4. Source: Deploy from branch.
5. Branch: main / root.
6. Abrir la URL publicada desde Chrome Android.
7. Menú ⋮ → Agregar a pantalla principal.

## Notas

- El cálculo es estimativo, no homologado.
- La navegación se abre en Google Maps o Waze.
- El historial y tarifas se guardan en localStorage.
- Si no ves cambios después de actualizar, cambiar el nombre de cache en `service-worker.js`.

# Competencias de Física · Puesta en marcha

## 1. Hoja de Drive + Apps Script
1. Crea una Hoja de cálculo de Google nueva.
2. Extensiones → Apps Script. Pega el contenido de `apps-script/Code.gs`.
3. Cambia `CLAVE_DOCENTE` por tu propia clave.
4. Implementar → Nueva implementación → Tipo: **Aplicación web**.
   - Ejecutar como: **Yo**
   - Quién tiene acceso: **Cualquier persona**
5. Copia la URL (termina en `/exec`). La pestaña `Equipos` se crea sola.

## 2. Página
1. Pega la URL en `config.js` → `window.APPS_SCRIPT_URL = '...'`.
2. Sube a GitHub: `Competencias Fisica.dc.html` (puedes renombrarlo `index.html`), `support.js`, `config.js`, `estudiantes.js`, `modernist.css`.
3. Activa GitHub Pages (Settings → Pages → rama main).

## Notas
- Sin URL configurada, la página funciona en modo demostración (datos en el navegador; clave `fisica2026`).
- Nota automática: Cohete → 4 condiciones de construcción × 0.75 + lanzamiento 2.0. Carro → propulsión, autonomía y línea recta × 1.0 + 50 cm recto 2.0.
- Las listas de estudiantes salen de las planillas de Física (`estudiantes.js`).

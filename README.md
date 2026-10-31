# Anti-Studocu-Ads

Extensión sencilla para navegadores basados en Chromium (Brave, Google Chrome, Edge…) que oculta el aviso de "Esta es una vista previa" en `https://www.studocu.com/`.

Lo único que hace es inyectar este CSS en studocu.com:

```css
.JGlYUa_level2 { display: none !important; }
```

## Instalación

1. Descarga `anti-studocu-ads-browser-extension.zip` desde la sección [Releases](https://github.com/luisfalconmx/anti-studocu-ads-browser-extension/releases) y descomprímelo.
2. Abre `brave://extensions` (Brave) o `chrome://extensions` (Chrome).
3. Activa **Modo de desarrollador** (arriba a la derecha).
4. Haz clic en **Cargar descomprimida** y selecciona la carpeta descomprimida (la que contiene `manifest.json`).

No borres ni muevas la carpeta después de instalarla: el navegador la carga desde ahí.

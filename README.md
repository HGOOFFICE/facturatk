# FacturaTK

App web para facturar tickets de compra en México a partir de una foto: lee el ticket con Gemini (tu propia clave), abre el portal de facturación del comercio con los datos listos para pegar y guarda los XML/PDF por mes.

- Sitio estático: `index.html` (toda la app) + `manifest.webmanifest` + iconos. Sin servidor.
- Publicado con Cloudflare Pages desde este repositorio; cada push a `main` se despliega solo.
- Los datos viven en el navegador del teléfono (IndexedDB). Usa Ajustes → Exportar respaldo.

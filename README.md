# Lector CFDI Nómina v2

Procesa recibos de nómina XML del SAT directamente en el navegador.  
Interfaz moderna con sidebar, tabs y KPIs, filtros avanzados y exportaciones seguras.

## 🚀 Características
- UI con sidebar, tabs y KPIs.
- Separación clara HTML (estructura), CSS (estilos), JS (lógica).
- Procesamiento local de XML (sin subir archivos a servidor).
- Filtros por texto, empleado, fechas, periodicidad, periodos y conceptos.
- Exportaciones en CSV y JSON.
- Render seguro usando `textContent`.
- Botón para limpiar estado.

## 📂 Archivos
- `index.html`
- `assetsstyles.css`
- `assetsapp.js`

## 📖 Uso
1. Abrir `index.html` en un navegador moderno.
2. Cargar archivo(s) XML de nómina.
3. Revisar información en tabs, aplicar filtros y exportar resultados.

## 🔒 Seguridad
- Renderizado seguro con `textContent` para evitar inyecciones.
- Procesamiento local los XML nunca salen del navegador.

---

✍️ Proyecto inicial para facilitar la revisión y análisis de recibos de nómina CFDI SAT.

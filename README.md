# POS + Nota de Venta (Listo)

## Archivos
- `pos.html` — Punto de venta con NV/Boleta/Factura
- `app.js` — Lógica del POS (usa WebApp de Apps Script)
- `nv-picking.html` — Panel de preparación / picking
- `picking.js` — Lógica de asignación, tiempos y emisión desde NV
- `estilos.css` — Estilos modernos
- `apps-script.gs` — Backend (Apps Script) con endpoints NV + POS

## Pasos
1. **Apps Script**: crea un proyecto, pega `apps-script.gs` completo y despliega como **Aplicación web** (ver. "Cualquiera con el enlace").
2. En `pos.html` (o directamente en la app), abre ⚙️ Config y pega la URL del WebApp en **URL WebApp**. Opcionalmente pega un **Logo URL**.
3. Abre `pos.html` en el navegador y usa **Bodega** para filtrar. El loader aparece junto al combo cada vez que cambias la bodega.
4. Documentos soportados: **NV**, **BOLETA**, **FA**, **FX**. Reimpresión en el panel derecho.
5. Para preparación: abre `nv-picking.html`. Asigna, inicia, termina y emite (factura/boleta) desde la NV.

## Notas
- El backend incluye endpoints: `addnv`, `listnv`, `nvset`, `getdoc (incluye NV)`, más los existentes.
- El combo **Bodega** es **bold**, autoredimensiona, y muestra loader al cargar y al cambiar.

Última generación: 2025-08-27T22:58:11.739937Z

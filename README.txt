Maestra de Productos + Clientes (Frontend)
===========================================

Archivos incluidos:
- maestra.html
- maestra.js
- clientes.html
- clientes.js

Cómo usar:
1) Sube estos archivos junto a tu estilos.css (ya existente).
2) Abre maestra.html o clientes.html en el navegador.
3) Pulsa "Config API" y pega la URL de tu Google Apps Script (deploy web). Se guarda en localStorage.
4) Usa "Recargar" para traer datos. En Maestra puedes "Nuevo", "Editar", "Eliminar" e "Importar" (XLSX/CSV).

Compatibilidad backend (Apps Script):
- GET  ?maestra=1    -> lista maestra sin bodega
- POST maestra_update/add/delete/import
- GET  ?clientes=1   -> lista clientes
- POST cliente_update/add/delete

Si aún no has agregado los endpoints, pega en tu Apps Script los bloques que te entregué.

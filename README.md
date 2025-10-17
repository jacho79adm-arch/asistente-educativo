# Asistente Educativo — Sitio con Copilot Studio

Página de ejemplo que integra un chat embebido de Microsoft Copilot Studio con fallback
si el proveedor bloquea mostrar la interfaz en iframes.

Archivos incluidos (propuestos):
- `index.html` — página principal con iframe y fallback.
- `README.md` — este archivo.
- `.gitignore` — archivos comunes ignorados.

Instrucciones rápidas para inicializar el repositorio (si prefieres usar la terminal):

1. Crea los archivos localmente (`index.html`, `README.md`, `.gitignore`) y luego:
   ```
   git init
   git add index.html README.md .gitignore
   git commit -m "Initial: add Copilot iframe page"
   git branch -M main
   git remote add origin https://github.com/jacho79adm-arch/asistente-educativo.git
   git push -u origin main
   ```

2. (Opcional) Para crear la rama para PR y empujarla:
   ```
   git checkout -b feature/add-copilot-iframe
   git push -u origin feature/add-copilot-iframe
   ```

Notas importantes:
- Reemplaza `https://TU-URL-DE-COPILOT-STUDIO` en `index.html` por la URL de embed que te proporcione Copilot Studio.
- Si al cargar la página aparece el fallback, es probable que el proveedor impida embeds (X-Frame-Options / CSP) — en ese caso usa el enlace para abrir el asistente en una nueva pestaña o revisa la documentación del proveedor para integraciones oficiales.
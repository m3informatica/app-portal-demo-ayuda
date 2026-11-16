# app-portal-demo-ayuda

Página de ayuda de la **demo pública de Saint Portal** (portal del empleado), servida con GitHub Pages en
https://m3informatica.github.io/app-portal-demo-ayuda/

## Para qué existe

El botón «Ayuda y soporte» de Mi perfil abre la página de ayuda que configura cada organización. En
producción esa página está en el mismo servidor que la app pero **fuera de la carpeta de la app**, así
que la app instalada (PWA) la abre en una ventana del navegador que se puede cerrar con ✕.

La demo vive en https://m3informatica.github.io/app-portal-demo/. Si la ayuda estuviera dentro de esa
carpeta, la demo instalada la trataría como una pantalla propia y no se podría cerrar. Este repositorio
la sirve desde el mismo servidor (`m3informatica.github.io`) pero en otra carpeta, igual que en un
despliegue real.

## Cómo se mantiene

- **No editar a mano.** El contenido se escribe en el repositorio `app-portal`
  (`src/demo-publica/`) y se copia aquí en el mismo paso que publica la demo (`app-portal-demo`).
- Contiene solo la página (`index.html`) y `.nojekyll`; no hay código fuente ni compilación.
- Si la demo deja de usarse, este repositorio se archiva o se borra junto con `app-portal-demo`.

Creado el 17/11/2026 a petición del responsable del proyecto.

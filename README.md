# soporte-barrido

Herramienta web para encontrar la orden BLE que hace girar un soporte giratorio que se anuncia como «Simple Peripheral» (servicio `FA00`: escribe en `FA01`, escucha `FA02`, marco `55 LEN … AA`).

Ábrela en Chrome para Android con Bluetooth y ubicación activados: https://mat-martin.github.io/soporte-barrido/

- `index.html`: versión publicada (hoy igual a `soporte_barrido_v1.html`).
- Solo usa el servicio `FA00`; no tiene acceso al servicio de actualización de firmware del soporte.

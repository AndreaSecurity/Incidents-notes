# n8n - "Connection lost" sin errores en servidor

## Entorno
- VPS en Hostinger
- EasyPanel
- n8n en Docker

## Síntoma
El editor mostraba "Connection lost".

No había errores en los logs.
El backend iniciaba correctamente.

## Diagnóstico
El problema no estaba en la infraestructura.
No había fallos de proxy ni reinicios del servicio.

## Resolución
Accediendo desde otro navegador el sistema funcionó correctamente.

## Conclusión
El error estaba relacionado con el entorno cliente (navegador) y no con el servidor.

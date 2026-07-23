# RCO & Asociados v2.0 — Estructura definitiva

Esta versión elimina la mezcla entre la web institucional y RCO Living.

## Estructura obligatoria

/
- index.html                  → RCO & Asociados
- styles.css
- app.js
- vercel.json
- verificar.html
- living/
  - index.html                → RCO Living
  - login.html
  - control.html
  - core.html
  - media.html
  - demás archivos internos

## Enlaces esperados

- https://rcoasociados.com/ → RCO & Asociados
- https://rcoasociados.com/living/ → RCO Living
- https://rcoasociados.com/living/login.html → Acceso privado
- https://rcoasociados.com/verificar.html → Comprobación rápida

## Para GitHub/Vercel

1. Eliminar todos los archivos actuales del repositorio que está conectado a rcoasociados.com.
2. Subir el CONTENIDO de este ZIP, no la carpeta contenedora.
3. Confirmar que index.html y la carpeta living aparecen al mismo nivel.
4. Esperar el despliegue de Vercel.
5. Abrir /verificar.html.

IMPORTANTE: si rcoasociados.com sigue abriendo Living después de subir esta versión,
el dominio está conectado al repositorio/proyecto equivocado en Vercel. En ese caso,
hay que asociar el dominio al proyecto donde se subió este paquete y quitarlo del
proyecto antiguo de RCO Living.

## Para Nginx

Copiar el contenido a:
  /var/www/rcoasociados

Usar el archivo:
  nginx-rcoasociados.conf

La carpeta living debe conservarse completa.

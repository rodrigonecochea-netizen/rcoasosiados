# RCO & Asociados — Web v1

Sitio institucional responsive preparado para publicar.

## Publicación rápida en Vercel
1. Subir todos los archivos de esta carpeta al repositorio `rcoasociados`.
2. En Vercel: Add New → Project → importar el repositorio.
3. Framework Preset: `Other`.
4. Build Command: dejar vacío.
5. Output Directory: dejar vacío.
6. Deploy.

## Dominios
En Vercel → Project → Settings → Domains:
- `rcoasociados.com`
- `www.rcoasociados.com`

Vercel mostrará los registros DNS exactos. Copiarlos en Cloudflare.

Para `rcoliving.com`, por ahora conviene redirigirlo a `rcoasociados.com/#living` hasta desarrollar la plataforma independiente.

## Importante
- Los botones de WhatsApp están activos con Brasil y Argentina.
- El selector ES/PT/EN funciona en el navegador.
- La sección de pagos comunica capacidad futura; no procesa dinero todavía.
- Para cobrar en la app habrá que contratar un proveedor (por ejemplo, Mercado Pago/Stripe u otro según país), completar verificaciones legales y programar la integración.

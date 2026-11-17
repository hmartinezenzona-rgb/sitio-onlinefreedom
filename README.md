# Sitio Onlinefreedom

Sitio estático (un solo `index.html`, sin build) de Onlinefreedom: IA y automatización para negocios.

- En vivo: https://proyect.onlinefreedom.site/
- Hosting: Cloudflare Pages (y Vercel), publicación automática desde la rama `main`.

## Cambiar datos de contacto
Al final de `index.html`, en el bloque `CONFIG`:

```js
const WHATSAPP = "52XXXXXXXXXX"; // con 52, sin espacios
const CORREO = "hola@tudominio.com";
```

Todos los botones de WhatsApp, el botón flotante y el formulario usan esos valores.
El formulario abre WhatsApp con los datos del cliente ya escritos.

## Pendientes
- Textos entre corchetes: precios `[$ MXN]`, cifras de Remesas Ya `[CIFRA]`, plazo `[X] semanas`, número y correo visibles en Contacto.

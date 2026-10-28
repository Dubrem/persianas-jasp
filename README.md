# Persianas JASP

Sitio web de venta de persianas y cortinas a la medida, con catálogo, carrito,
checkout, cuentas de cliente y panel de administración.

Misma estructura y motor que el sitio de DUBREM (`~/bella-esencia`), adaptado al giro:
categorías de persianas y cortinas, filtro por **medida** en lugar de talla, paleta
en tonos madera, y textos de medición / instalación / garantía.

## Pendientes antes de publicar

| Qué | Dónde |
|---|---|
| Página de Facebook | `index.html` → enlaces a `facebook.com` |
| Datos bancarios (hoy `XXX`) | `index.html` → tarjeta de transferencia del checkout y pasos de la confirmación |
| MercadoPago | desactivado: `#pmMp` está oculto y `startCheckout()` arranca en transferencia |
| Catálogo real | `index.html` → el arreglo `PRODUCTS` trae 12 modelos de muestra; bórralos cuando subas los reales desde ⚙ Admin |
| Dominio | `canonical`, `og:url`, `robots.txt`, `sitemap.xml`, `api/create-preference.js` |

## Desarrollo local

```bash
python3 -m http.server 4178
```

Las rutas `/api/*` solo funcionan desplegado en Vercel.

## Categorías

Enrollables · Madera · Aluminio · Verticales · Panel Japonés · Cortinas Blackout ·
Cortinas Decorativas · Sheer Elegance · Motorizadas · Accesorios y Rieles

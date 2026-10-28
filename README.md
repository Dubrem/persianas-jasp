# Persianas JASP

Sitio web de venta de persianas y cortinas a la medida, con catálogo, carrito,
checkout, cuentas de cliente y panel de administración.

Misma estructura y motor que el sitio de DUBREM (`~/bella-esencia`), adaptado al giro:
categorías de persianas y cortinas, filtro por **medida** en lugar de talla, paleta
en tonos madera, y textos de medición / instalación / garantía.

## Pendientes antes de publicar

| Qué | Dónde |
|---|---|
| WhatsApp y teléfono reales (`52XXXXXXXXXX`) | `index.html` → `WA_NUMBER`, enlaces `wa.me` y `tel:` del footer y del modal de contacto |
| Dirección del local | `index.html` → `STORE_LOCATION` |
| Página de Facebook | `index.html` → enlaces a `facebook.com` |
| Proyecto de Firebase propio | `index.html` → `FIREBASE_DB_URL` y `FIREBASE_API_KEY`, y `api/*.js` |
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

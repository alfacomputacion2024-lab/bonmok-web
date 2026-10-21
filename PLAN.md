# Bonmok — Plan de negocio (octubre 2026)

> Documento interno del proyecto. Todo lo importante del negocio, estructurado:
> qué es el producto, precios, costos, comparación con el mercado y plan de lanzamiento.

---

## 1. Qué es Bonmok

- **Una landing con los datos importantes** del negocio en un solo enlace:
  WhatsApp, Instagram, catálogo, horario, ubicación y el cartel "abierto ahora".
- **No es una página web completa** ni una tienda online: es una landing simple
  que se comparte en la bio de Instagram/TikTok o como QR en el local.
- **100 % autoservicio**: el cliente abre el panel (`crear.html`), carga sus
  datos, descarga un archivo y lo publica en 2 minutos. Nadie interviene.
- **Soporte Bonmok:** WhatsApp **0992 971 938** (Encarnación, lunes a sábado).
- Página pública del servicio: `index.html` (landing de Bonmok).

## 2. Precios

**Cambio de dólar verificado (oct 2026):** 1 USD ≈ **Gs. 5.700**
(referencial BCP ~Gs. 5.660–5.740; el dólar está bajo en Paraguay en 2026).

| Plan | USD | Guaraníes | Ventajas |
|---|---|---|---|
| **Básico** | US$ 0 | Gs. 0 | 6 links, 4 colores sueltos o paquete (2 editables), 2 animaciones, estado abierto/cerrado, sin marca ajena |
| **Full** | US$ 5,26/mes | Gs. 30.000/mes | Links ilimitados, panel de colores completo (los 4), 9 animaciones, cambios sin límite, rediseño cada 6 meses, soporte, activación con código |
| **Full Plus** ⭐ nuevo | **US$ 9/mes** | **Gs. 51.300/mes** | **Todo el Full +** tu página en vivo en tu subdominio (`tunegocio.bonmok.com.py`), hosting y subdominio incluidos, la publicamos/actualizamos por vos, rediseño cada 3 meses, soporte prioritario |

Opcional sugerido: **Full anual** — Gs. 300.000/año (US$ 52,63) = 2 meses gratis.

> Idea de oferta de lanzamiento: *"los 3 primeros Full Plus: primer mes a mitad"*
> (Gs. 25.650).

## 3. Comparación con Linktree (precios actuales verificados)

| | Linktree | Bonmok |
|---|---|---|
| Gratis | US$ 0 con **marca Linktree** y su URL | US$ 0 sin marca ajena |
| 1er plan pago | Starter US$ 8 = Gs. 45.600 | — |
| Plan popular | Pro US$ 15 = Gs. 85.500 | Full US$ 5,26 = Gs. 30.000 |
| Con hosting/publicación | — | Full Plus US$ 9 = Gs. 51.300 |
| Soporte | Inglés, ticket | WhatsApp, en guaraníes, en Encarnación |

**Argumento de venta:** *"Lo que en Linktree cuesta US$ 8–15 (Gs. 45.600–85.500)
acá sale Gs. 30.000, en guaraníes, con soporte acá."*

**Validación de mercado:** hasta marcas grandes usan link-in-bio
(ejemplo público: `linktr.ee/stingenergymexico` — nombre, frase, redes y un
call-to-action). Bonmok hace lo mismo, pero pensado para el negocio local de
Paraguay (WhatsApp, horario, "abierto ahora", QR, sin comisiones).

## 4. Tu costo de estructura (un solo paquete para todo)

Hosting compartido: **un plan corre la landing + panel + todas las páginas de
los clientes** (subdominios `cliente.bonmok.com.py` ilimitados).

| Concepto | USD | Guaraníes |
|---|---|---|
| Hostinger Premium (promo 48 meses) | US$ 2,49/mes | ~Gs. 14.200/mes (US$ 167,52 = ~Gs. 955.000 de una) |
| Hostinger — renovación (a los 4 años) | ~US$ 12/mes | ~Gs. 68.000/mes |
| Dominio `.com.py` (NIC.py oficial) | US$ 28/año | Gs. 160.000/año (~Gs. 13.300/mes) |
| **Total con promo** | **US$ 4,82/mes** | **~Gs. 27.500/mes** |
| Alternativa gratis (Cloudflare Pages + tu dominio) | US$ 2,34/mes | Gs. 13.300/mes |

**Cada página de cliente pesa ~350 KB** → 100 clientes ≈ 35 MB de los 20 GB.

### Punto de equilibrio

| Clientes Full (Gs. 30.000) | Ingreso | Margen (promo) |
|---|---|---|
| 1 | Gs. 30.000 | ~Gs. 2.500 |
| 3 | Gs. 90.000 | ~Gs. 62.500 |
| 5 | Gs. 150.000 | ~Gs. 122.500 |
| 10 | Gs. 300.000 | ~Gs. 272.500 |

Punto de equilibrio: **1 cliente**. Con el plan Full Plus (Gs. 51.300) el margen
es el doble de rápido.

## 5. Plan de lanzamiento — fin de octubre 2026

| Fechas | Acción |
|---|---|
| **21–23 oct** | Comprar dominio `.com.py` (Gs. 160.000/año). Publicar landing + panel (GitHub Pages gratis o el hosting comprado) |
| **24–27 oct** | **3 locales piloto GRATIS** de Encarnación (panadería, gimnasio, tienda): se arman con el panel y dan permiso para mostrar sus landings como ejemplo |
| **28–30 oct** | Flyer de 1 página: captura de las 3 landings reales + precios + QR + WhatsApp. Grupos de WhatsApp de Encarnación. Oferta de lanzamiento |
| **31 oct** | 🎉 Lanzamiento oficial |
| **Noviembre** | Primeros clientes pagando → evaluar Hostinger para hosting incluido (Full Plus) |

**Escalar:** Encarnación → Itapúa → todo el país. El panel multi-cliente ya
está listo; el costo fijo no sube con cada cliente nuevo.

## 6. Cómo se publica todo

1. **Landing de Bonmok:** `index.html` de este repo → GitHub Pages
   (`Settings → Pages → rama main`), gratis.
2. **Panel autoservicio:** `crear.html` (copia de `bonmok_angelo/admin.html`) →
   queda en la misma dirección + `/crear.html`. Los botones "Creá tu página" ya
   apuntan ahí.
3. **Cuando haya hosting comprado (Hostinger):** landing y panel en
   `bonmok.com.py`, y las páginas de clientes Full Plus en
   `tunegocio.bonmok.com.py` (subdominios gratis e ilimitados, se crean desde
   hPanel → Administrador de archivos: un archivo `index.html` por cliente).

## 7. Recordatorios pendientes

- **Rotar el token de GitHub** que quedó expuesto en el repo del catálogo
  (la contraseña personal con la que se hizo el push inicial).
- **Marca:** registrar "Bonmok" en DPI/INDEN cuando se empiece a facturar.
- Panel: la contraseña y los códigos de activación **no se publican en
  GitHub** (solo viven en la PC del propietario).
- Los cambios del panel original se copian a `crear.html`
  (`Copy-Item admin.html crear.html`) y se hacen push.

---

*Última actualización: 21 de octubre de 2026.*

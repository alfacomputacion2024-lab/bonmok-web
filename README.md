# Bonmok — Landing page 🇵🇾

Página institucional de **Bonmok**, el servicio de páginas de enlaces (link in bio)
para negocios de Paraguay. 100% **HTML + CSS**, sin frameworks, sin JavaScript y
con código comentado para que sea fácil de mantener.

Modelo **100 % autoservicio**: cualquiera arma su página en el panel
(`crear.html`), la descarga y la publica por su cuenta, sin intervención de
nadie. Soporte: **0992 971 938** (WhatsApp).

> Inspirada en el esquema de las páginas de servicios "link in bio" del mercado
> (hero con maqueta de celular, grilla de funciones, estilos, precios, FAQ y CTA).
> Es una creación original: textos, colores y diseño propios, sin uso de marcas
> de terceros.

## ✨ Qué incluye

| Sección | Descripción |
|---|---|
| Hero | Titular + CTA al panel + maqueta de celular 100% CSS con logo animado |
| Funciones | 7 tarjetas (links, WhatsApp, estado abierto/cerrado, colores, ubicación, sin comisiones, animaciones del logo) |
| Cómo funciona | 3 pasos de autoservicio: panel → publicar → biografía |
| Estilos | 6 paletas: Marino & Celeste, Noche & Azul, Ónix & Oro, Bosque & Menta, Coral & Arena, Violeta & Lilas |
| Precios | Básico (Gs. 0 / US$ 0), Full (Gs. 30.000 / US$ 5,26) y **Full Plus** (Gs. 51.300 / US$ 9 con hosting y subdominio incluidos) |
| Preguntas | FAQ con `<details>` (sin JavaScript) |
| Footer | Soporte, enlaces y nota de independencia de marca |

> 📄 El **plan de negocio** completo (precios en USD y guaraníes, costos de
> hosting, comparación con el mercado y lanzamiento) está en [`PLAN.md`](PLAN.md).

## 🗂 Estructura

```
bonmok_web/
├── index.html               # Página completa (HTML semántico y comentado)
├── crear.html               # Panel de edición autoservicio (copia de bonmok_angelo/admin.html)
├── assets/
│   ├── css/styles.css       # Estilos organizados en 10 secciones
│   └── img/favicon.svg      # Ícono de la pestaña
├── README.md
├── PLAN.md                  # Plan de negocio: precios, costos y lanzamiento
├── LICENSE                  # Licencia MIT
└── .gitignore
```

## 🖥 Cómo verla localmente

Doble clic en `index.html`, o con un servidor local:

```bash
python -m http.server 8000
# luego abrir http://localhost:8000
```

## 🌐 Cómo publicarla (GitHub Pages)

1. Subí los cambios a la rama `main`.
2. En el repositorio de GitHub: **Settings → Pages → Source: Deploy from a branch**
   → rama `main`, carpeta `/ (root)` → **Save**.
3. En unos minutos queda publicada en:
   `https://alfacomputacion2024-lab.github.io/bonmok-web/`
4. Con esto el botón **"Creá tu página"** queda funcionando: lleva a
   `crear.html` (el panel autoservicio) en la misma dirección.

## ✏️ Cómo personalizarla

- **Colores:** editá las variables del bloque `:root` al inicio de `styles.css`.
- **Textos y precios:** todo el contenido está en `index.html`, en orden de sección.
- **Números de contacto:** `wa.me/595985296032` es el de ventas (botón del Plan Full);
  `wa.me/595992971938` es el de soporte (FAQ y footer).
- **Logo:** la "B" es texto dentro de `<span class="brand-mark">`; podés reemplazarla
  por un `<img>` si ya tenés el archivo definitivo.

## 🧩 Relación con el producto

La landing comercializa **Bonmok**, el editor de páginas de enlaces **autoservicio**:
el panel (`crear.html`, copia de `admin.html` del proyecto `bonmok_angelo`) genera
las páginas que el cliente publica por su cuenta. Quien contrata el Plan Full
activa las funciones con un código de Bonmok; el soporte es al **0992 971 938**.

> ⚠️ Si cambiás el panel original, volvé a copiarlo como `crear.html`
> (`Copy-Item admin.html crear.html`) y hacé push para mantenerlos al día.

## 📄 Licencia

MIT — ver [LICENSE](LICENSE).

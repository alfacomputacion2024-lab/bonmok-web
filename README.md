# Bonmok — Landing page 🇵🇾

Página institucional de **Bonmok**, el servicio de páginas de enlaces (link in bio)
para negocios de Paraguay. 100% **HTML + CSS**, sin frameworks, sin JavaScript y
con código comentado para que sea fácil de mantener.

> Inspirada en el esquema de las páginas de servicios "link in bio" del mercado
> (hero con maqueta de celular, grilla de funciones, estilos, precios, FAQ y CTA).
> Es una creación original: textos, colores y diseño propios, sin uso de marcas
> de terceros.

## ✨ Qué incluye

| Sección | Descripción |
|---|---|
| Hero | Titular + CTA a WhatsApp + maqueta de celular 100% CSS |
| Funciones | 6 tarjetas (links, WhatsApp, estado abierto/cerrado, colores, ubicación, sin comisiones) |
| Cómo funciona | 3 pasos |
| Estilos | 6 paletas: Marino & Celeste, Noche & Azul, Ónix & Oro, Bosque & Menta, Coral & Arena, Violeta & Lilas |
| Precios | Básico (Gs. 0: 4 colores sueltos o paquete con 2 editables) y Full (Gs. 30.000/mes: panel de colores completo) |
| Preguntas | FAQ con `<details>` (sin JavaScript) |
| Footer | Contacto, enlaces y nota de independencia de marca |

## 🗂 Estructura

```
bonmok_web/
├── index.html               # Página completa (HTML semántico y comentado)
├── assets/
│   ├── css/styles.css       # Estilos organizados en 10 secciones
│   └── img/favicon.svg      # Ícono de la pestaña
├── README.md
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

## ✏️ Cómo personalizarla

- **Colores:** editá las variables del bloque `:root` al inicio de `styles.css`.
- **Textos y precios:** todo el contenido está en `index.html`, en orden de sección.
- **Número de WhatsApp:** buscá `wa.me/595985296032` y reemplazalo por el número deseado.
- **Logo:** la "B" es texto dentro de `<span class="brand-mark">`; podés reemplazarla
  por un `<img>` si ya tenés el archivo definitivo.

## 🧩 Relación con el producto

La landing comercializa **Bonmok**, el editor de páginas de enlaces que vive en el
otro proyecto (`bonmok_angelo`): el panel `admin.html` genera las páginas que se
venden desde esta landing.

## 📄 Licencia

MIT — ver [LICENSE](LICENSE).

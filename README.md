# Portafolio Personal — Adam Keyes

Proyecto de portafolio personal desarrollado como práctica de CSS avanzado y diseño responsive. Basado en el diseño de [Frontend Mentor](https://www.frontendmentor.io).

## 🌐 Demo

[Ver sitio publicado](https://TU_USUARIO.github.io/portafolio_2/)

---

## 📸 Preview

| Mobile | Tablet | Desktop |
|--------|--------|---------|
| Diseño en columna centrado | Imagen hero a la derecha del nav | Layout de dos columnas con overlay en proyectos |

---

## 🛠️ Tecnologías

- **HTML5** — estructura semántica
- **SASS / SCSS** — arquitectura 7-1 (abstracts, base, layout, components, pages, themes, vendors)
- **CSS Custom Properties** — variables de color y tipografía
- **Vite** — bundler y servidor de desarrollo
- **GitHub Pages** — despliegue

---

## 📐 Breakpoints

| Nombre | Valor |
|--------|-------|
| Mobile | < 768px |
| Tablet | 768px |
| Tablet horizontal | 1024px |
| Desktop | 1200px |
| Desktop XL | 1440px |

---

## 📁 Estructura del proyecto

```
portafolio_2/
├── index.html
├── vite.config.js
├── package.json
├── images/
│   ├── mobile/
│   ├── tablet/
│   └── desktop/
└── src/
    ├── main.js
    └── styles/
        ├── main.scss
        ├── abstracts/
        │   ├── _variables.scss
        │   ├── _mixins.scss
        │   └── _functions.scss
        ├── base/
        │   ├── _base.scss
        │   ├── _typography.scss
        │   ├── _helpers.scss
        │   └── _fonts.scss
        ├── layout/
        │   ├── _header.scss
        │   ├── _footer.scss
        │   └── _container.scss
        ├── components/
        │   ├── _button.scss
        │   ├── _experience.scss
        │   ├── _projects.scss
        │   └── _formulario.scss
        ├── pages/
        │   └── _home.scss
        ├── themes/
        │   └── _default.scss
        └── vendors/
            └── _normalize.scss
```

---

## 🚀 Instalación y uso local

```bash
# Clonar el repositorio
git clone https://github.com/TU_USUARIO/portafolio_2.git

# Entrar al proyecto
cd portafolio_2

# Instalar dependencias
npm install

# Iniciar servidor de desarrollo
npm run dev

# Generar build de producción
npm run build

# Previsualizar el build
npm run preview
```

---

## 🚢 Despliegue en GitHub Pages

```bash
# Publicar (hace build + sube a rama gh-pages)
npm run deploy
```

El sitio queda disponible en `https://TU_USUARIO.github.io/portafolio_2/`

---

## ✨ Funcionalidades

- Diseño **fully responsive** — mobile first
- **Overlay animado** en tarjetas de proyectos al hacer hover (desktop)
- **Validación de formulario** con mensajes de error y cambio de color en campos inválidos
- **Transiciones suaves** en botones y enlaces con gradiente teal/verde
- Imagen hero adaptativa — versión mobile (SVG) y versión tablet/desktop (PNG)
- Círculo decorativo animado en el hero (desktop)

---

## 🎨 Paleta de colores

| Variable | Color | Uso |
|----------|-------|-----|
| `$black` | `#151515` | Fondo principal |
| `$light-black` | `#242424` | Fondo footer y secundario |
| `$green` | `#4ee1a0` | Acentos y hover |
| `$white` | `#ffffff` | Texto principal |
| `$grey` | `#d9d9d9` | Texto secundario y líneas |

---

## 📝 Licencia

Proyecto de uso educativo. El diseño original pertenece a [Frontend Mentor](https://www.frontendmentor.io).

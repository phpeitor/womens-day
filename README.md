# ✨ International Women's Day ✨👸

[![forthebadge](http://forthebadge.com/images/badges/uses-css.svg)](https://www.linkedin.com/in/drphp/)
[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](https://www.linkedin.com/in/drphp/)

[![Video](https://img.youtube.com/vi/C3ynQCeaq-4/0.jpg)](https://www.youtube.com/watch?v=C3ynQCeaq-4)  
[▶ Ver demo en YouTube](https://www.youtube.com/watch?v=C3ynQCeaq-4)

Tarjeta animada interactiva para celebrar el **8 de marzo - Día Internacional de la Mujer**.  

---

## 🗂 Estructura del proyecto

```
womens-day/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos y animaciones CSS
├── js/
│   ├── script.js       # Lógica de animación (TweenMax timeline)
│   ├── TweenMax.min.js # Librería de animación GSAP
│   └── babel.min.js    # Transpilador Babel (standalone)
├── img/
│   ├── logo_women.png  # Logo en esquina superior izquierda
│   ├── mujer1.jpg      # Retratos utilizados en la animación
│   ├── mujer2.jpg
│   ├── mujer3.jpg
│   ├── balloon.svg     # Iconos SVG animados
│   ├── heart.svg
│   ├── smiling.svg
│   ├── happy.svg
│   └── music-note.svg
└── video/
    └── fondo.mp4       # Video de fondo en bucle
```

---

## 🚀 Cómo ejecutar el proyecto

### Opción 1 — VS Code Live Server (recomendado)

1. Clona el repositorio:

```bash
git clone https://github.com/phpeitor/womens-day.git
cd womens-day
```

2. Instala la extensión **Live Server** en VS Code.
3. Haz clic derecho sobre `index.html` → **Open with Live Server**.  
   Se abrirá automáticamente en `http://127.0.0.1:5500`.

### Opción 2 — Abrir directamente en el navegador

Simplemente abre el archivo `index.html` en tu navegador.

> ⚠️ Algunos navegadores bloquean la reproducción automática del video (`autoplay`) con archivos locales (`file://`). Si el video no reproduce, usa la Opción 1.

---

## 🎨 Personalización

| Elemento | Cómo cambiarlo |
|---|---|
| Nombre de la destinataria | Edita el `<span id="name">` en `index.html` |
| Mensajes de texto | Modifica los párrafos `.idea-*`, `.hbd-chatbox` y `#wishText` en `index.html` |
| Retratos | Reemplaza `img/mujer1.jpg`, `mujer2.jpg`, `mujer3.jpg` con tus propias fotos |
| Logo | Reemplaza `img/logo_women.png` (se puede abrir en lightbox al hacer clic) |
| Video de fondo | Reemplaza `video/fondo.mp4` con tu propio video |
| Colores | Ajusta las variables de color en `css/styles.css` |

---

## ✨ Características

- 🎬 Video de fondo en bucle con overlay semitransparente
- 🎞 Timeline de animaciones orquestadas con **GSAP TweenMax**
- 💬 Efecto de escritura animada (chatbox)
- 🎈 Globos y partículas flotantes
- 🖼 **Lightbox** en el logo: al hacer clic se expande desde la esquina con animación de retorno
- 🔁 Botón para repetir la animación desde el inicio
- 📱 Adaptado para pantallas de escritorio

---

## 🛠 Tecnologías utilizadas

- HTML5 / CSS3
- JavaScript (ES6)
- [GSAP TweenMax](https://greensock.com/tweenmax/) — animaciones
- [Babel Standalone](https://babeljs.io/docs/babel-standalone) — compatibilidad de sintaxis
- [Google Fonts — Work Sans](https://fonts.google.com/specimen/Work+Sans)

---

## 📄 Licencia

Proyecto de uso libre con fines personales y educativos.  
Hecho con 💜 por [phpeitor](https://www.linkedin.com/in/drphp/)

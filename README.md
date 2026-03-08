# ✨ Feliz Día Internacional de la Mujer ✨👸

[![forthebadge](http://forthebadge.com/images/badges/uses-css.svg)](https://www.linkedin.com/in/drphp/)
[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](https://www.linkedin.com/in/drphp/)

[![Video](https://img.youtube.com/vi/C3ynQCeaq-4/0.jpg)](https://www.youtube.com/watch?v=C3ynQCeaq-4)  
[▶ Ver demo en YouTube](https://www.youtube.com/watch?v=C3ynQCeaq-4)

Tarjeta animada interactiva para celebrar el **8 de marzo — Día Internacional de la Mujer**.  

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

### Opción 1 — Apache (recomendado)

1. Clona o copia la carpeta dentro del directorio `htdocs` de Apache:

```bash
git clone https://github.com/phpeitor/womens-day.git C:/Apache24/htdocs/womens-day
```

2. Inicia Apache y abre en el navegador:

```
http://localhost/womens-day/
```

### Opción 2 — VS Code Live Server

1. Instala la extensión **Live Server** en VS Code.
2. Abre la carpeta del proyecto.
3. Haz clic derecho sobre `index.html` → **Open with Live Server**.

### Opción 3 — Abrir directamente en el navegador

> ⚠️ Algunos navegadores bloquean la reproducción automática del video (`autoplay`) cuando se abre un archivo local (`file://`). Se recomienda usar un servidor web local para la mejor experiencia.

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

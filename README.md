# 📖 Mio Cid - Presentación Interactiva HTML

Una presentación web interactiva desarrollada completamente en **HTML, CSS y JavaScript**, diseñada para mostrar contenido multimedia mediante diapositivas dinámicas con una experiencia moderna e intuitiva.

La aplicación permite visualizar imágenes, videos y documentos HTML incrustados, incorporando animaciones, navegación mediante teclado y botones, ampliación de imágenes y visualización de contenido en pantalla completa.

---

# Características principales

## 🎞️ Sistema de presentación

- Generación dinámica de diapositivas.
- Navegación mediante:
  - Botones anterior/siguiente.
  - Indicadores inferiores.
  - Teclas del teclado (← →).
- Diseño responsive.
- Relación de aspecto adaptable (16:9 configurable).
- Centrado automático de la presentación.

---

## 🖼️ Soporte multimedia

La presentación admite diferentes tipos de contenido:

- Imágenes
- Videos
- Documentos HTML incrustados mediante `<iframe>`

Cada tipo de contenido se adapta automáticamente al tamaño de la diapositiva utilizando:

- `object-fit: contain`
- Escalado automático
- Bordes redondeados
- Sombras suaves

---

## 🔍 Zoom inteligente

Las imágenes incluyen un sistema de ampliación mediante:

- Botón de lupa
- Lightbox integrado
- Cierre mediante:
  - tecla ESC
  - clic fuera de la imagen

---

## 🖥️ Pantalla completa para contenido HTML

Cuando una diapositiva contiene un documento HTML:

- puede abrirse en modo pantalla completa;
- utiliza `iframe.srcdoc`;
- decodifica automáticamente contenido Base64;
- mantiene aislamiento mediante `sandbox`.

---

## ✨ Animaciones

Cada transición entre diapositivas selecciona aleatoriamente una animación distinta.

Entre ellas:

- Fade
- Slide Left
- Slide Right
- Slide Up
- Slide Down
- Rotate
- Scale
- Flip X
- Flip Y
- Zoom Blur
- Swing
- Bounce
- Glitch
- Spiral
- Drop
- Unfold
- Skew
- Perspective Flip
- Jack In The Box
- Light Speed

Las animaciones utilizan CSS Keyframes para ofrecer una experiencia fluida sin depender de bibliotecas externas.

---

## 🔗 Enlaces externos

Cada diapositiva puede incluir un enlace opcional.

Cuando existe:

- aparece un badge inferior;
- abre la URL en una ventana independiente;
- mantiene medidas controladas para facilitar la visualización.

---

## 🎯 Indicadores de progreso

La interfaz incorpora indicadores inferiores que permiten:

- conocer la diapositiva actual;
- navegar directamente hacia cualquier diapositiva.

---

## ⌨️ Navegación mediante teclado

La presentación puede controlarse completamente desde el teclado:

| Tecla | Acción |
|--------|---------|
| ← | Diapositiva anterior |
| → | Diapositiva siguiente |
| ESC | Cerrar Lightbox o Pantalla Completa |

---

## 📱 Diseño adaptable

El proyecto ha sido desarrollado utilizando únicamente tecnologías web estándar:

- HTML5
- CSS3
- JavaScript ES Modules

No requiere frameworks externos.

Se adapta correctamente a:

- computadores
- tabletas
- pantallas táctiles
- proyectores
- televisores

---

# Arquitectura

```
HTML
│
├── Presentation Container
├── Slide Container
├── Navigation Buttons
├── Indicators
├── Footer
├── Lightbox
└── Fullscreen Viewer

CSS
│
├── Layout
├── Responsive Design
├── Multimedia Styles
├── Navigation
├── Lightbox
├── Fullscreen
└── 25+ CSS Animations

JavaScript
│
├── Dynamic Slide Generator
├── Navigation Controller
├── Transition Engine
├── Lightbox Manager
├── Fullscreen Manager
├── Keyboard Events
├── Indicator Generator
└── Media Renderer
```

---

# Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript ES6 Modules
- CSS Keyframes Animations
- Base64 Media Embedding
- Responsive Design
- Flexbox

---

# Funcionalidades destacadas

- ✅ Presentaciones completamente offline.
- ✅ Sin dependencias externas.
- ✅ Compatible con imágenes, videos y HTML.
- ✅ Animaciones automáticas.
- ✅ Navegación intuitiva.
- ✅ Zoom para imágenes.
- ✅ Pantalla completa para contenido HTML.
- ✅ Responsive.
- ✅ Preparado para proyectores y pantallas interactivas.

---

# Casos de uso

Este proyecto es ideal para:

- clases interactivas;
- presentaciones educativas;
- contenidos digitales;
- museos virtuales;
- libros interactivos;
- exposiciones;
- material didáctico multimedia;
- proyectos culturales como **El Cantar de Mio Cid**.

---

# Licencia

Este proyecto puede utilizarse como base para la creación de presentaciones educativas interactivas. Se recomienda mantener los créditos correspondientes al autor original cuando el código sea reutilizado o modificado.

---

## Autor

Diseño original de la plantilla:

**Juan Guillermo Rivera Berrío**

Presentación adaptada para contenidos educativos mediante tecnologías web modernas.

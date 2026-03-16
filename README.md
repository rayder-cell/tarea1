
# Estructura del Proyecto

```
product-landing-page/
├── index.html        Página principal
├── css/
│   └── styles.css   → Estilos (variables CSS, modo oscuro)
├── img/             → Imágenes del proyecto
└── README.md        → Este archivo
```

---

## Estructura Semántica HTML5

El proyecto usa etiquetas semánticas para dar significado real al contenido:

| Etiqueta | Uso en el proyecto |
|---|---|
| `<header>` | contiene la barra de navegación fija |
| `<nav>` | Menú principal con enlaces internos |
| `<main>` | Contenido principal de la página |
| `<section>` | Divide el contenido: Hero, Características y preguntas frecuentes |
| `<footer>` | Información de contacto y redes sociales |
| `<details>` / `<summary>` | Preguntas frecuentes interactivas |

### Jerarquía de encabezados

```
h1  Título principal
  h2  características
    h3  Motor y Potencia
    h3  Suspensión y Frenos
    h3  Diseño y Peso
  h2  "Galería de Imágenes"
  h2  "comentarios"
  h2  "Preguntas Frecuentes"
  ------------------------------------------------

Esta jerarquía ayuda a los lectores de pantalla a navegar el contenido correctamente.

---------------------------------------------------------------------------------------------------------------


Prácticas aplicadas en el proyecto:

- **`alt` en imágenes** — Toda imagen tiene texto descriptivo alternativo
- **`aria-label`** — Botones e íconos con texto no visible tienen etiqueta ARIA
- **`aria-label` en navegaciones** — `<nav aria-label="Navegación principal">` y `<nav aria-label="Redes sociales">`
- **`role="list"`** — Aplicado a listas de tarjetas y redes sociales
- **`role="img"`** — En elementos visuales decorativos
---
---
 
## Accesibilidad
 
- **`alt` en imágenes** — Toda imagen tiene texto descriptivo alternativo
- **`aria-label`** — Botones e íconos con texto no visible tienen etiqueta ARIA
- **`aria-label` en navegaciones** — `<nav aria-label="Navegación principal">` y `<nav aria-label="Redes sociales">`
- **`aria-label` en estrellas** — `aria-label="5 de 5 estrellas"` para lectores de pantalla
- **`role="list"`** — Aplicado a listas de tarjetas, galería y redes sociales
- **`role="listitem"`** — En cada elemento de galería y comentarios
- **`role="img"`** — En elementos visuales decorativos

## Secciones añadidas en Lab 02
- **Galería de Imágenes** — `#galeria` con Flexbox y `figcaption` por imagen
- **Testimonios** — `#testimonios` con tarjetas Flexbox y `order` para controlar layout interno
- **Términos y Condiciones** — bloque `.footer-legal` en el footer con Flexbox
 
## Animaciones (Logro 2)
 
- `fadeInUp` — aparición suave desde abajo con `opacity` y `translateY`
- `animation-delay` escalonado: `0.1s · 0.22s · 0.34s` en tarjetas con `.fade-in`
- Transiciones `hover` en botones, imágenes y tarjetas con `transform: translateY`






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
  h2  "Características"
    h3  Nombre de cada característica
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
:





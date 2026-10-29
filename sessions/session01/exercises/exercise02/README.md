# 📝 Enunciado

## 🎯 Objetivo

Crea una **página web con una tabla horaria** de un **ciclo de FP de informática** (elige el tuyo: **DAW**, **DAM** o **ASIX**), aplicando buenas prácticas de **HTML semántico** y de **accesibilidad**.

---

## 📋 Recordatorios importantes

1. **Idioma del documento:** define el idioma en `<html lang="…">` (por ejemplo, `es`, `ca`).
2. **Encabezados y texto:** usa **títulos, subtítulos y párrafos**; **resalta al menos 3 palabras** con sentido (`<strong>`, `<em>`).
3. **Jerarquía de encabezados:** mantén una jerarquía correcta (`<h1>` → `<h2>` → `<h3>`…).
4. **Navegación:** en **cada página** debe haber un **enlace para volver a la página principal**.
5. **Contenedores semánticos HTML5:** organiza las páginas con `<header>`, `<main>`, `<section>`, `<footer>`.
6. **Estructura del proyecto:**

   * Dentro de la carpeta del ejercicio estarán:

     * `index.html` → Página principal con la **tabla horaria**.
     * Carpeta `pages/` → Otras páginas de apoyo (asignaturas).

**Ejemplo de estructura de carpetas:**

```text
mi-horario-fp/
├── index.html              ← Horario principal (tabla)
├── pages/
│  └─ asignaturas.html      ← Listado y descripción de módulos
└── README.md
```

> \[!TIP]
> Usa un solo `<h1>` por página. A partir de ahí, organiza con `<h2>` y `<h3>` según la profundidad de los temas.

---

## 📄 Páginas a crear

### 1️⃣ Página principal — Horario (`index.html`)

Crea una **tabla horaria semanal** con buenas prácticas de semántica y accesibilidad.

**Requisitos de la tabla:**

* Usa **`<caption>`** para el título de la tabla (ej.: “Horario Semanal — 1º \[DAW/DAM/ASIX]”).
* La primera columna indica **franjas horarias** (ej.: `09:00–10:00`, `10:00–11:00`).
* La primera fila contiene los **días** (Lunes a Viernes).
* Usa **`<th scope="col">`** para los días y **`<th scope="row">`** para las horas.
* Incluye al menos **1 fila de descanso** con `colspan`.
* Añade un **pie de tabla (`<tfoot>`)** con una breve nota.
* Organiza la tabla dentro de `<main>` y `<section>`.

---

### 2️⃣ Página de asignaturas (`pages/asignaturas.html`)

* Título claro (ej.: “Módulos del Ciclo”).
* Lista las **asignaturas/módulos** de tu ciclo elegido (**DAW/DAM/ASIX**) con una breve descripción (2–3 líneas).
* **Resalta al menos 3 palabras clave** en todo el documento.
* Incluye un **listado** que relacione **siglas ↔ nombre completo** (ej.: `LM → Lenguajes de Marcas`).
* Enlace para **volver a la página principal**.
* Organiza el contenido con `<header>`, `<main>`, `<section>` y `<footer>`.

---

## 📂 Estructura semántica recomendada

En cada página debe aparecer:

* `<header>` con el título principal.
* `<main>` con el contenido (tabla o listado).
* `<footer>` con créditos o notas.
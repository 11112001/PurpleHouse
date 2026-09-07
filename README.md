# 🟣 Casa Púrpura

> **El placer lento de la flor.**

Casa Púrpura es una landing page conceptual inspirada en la estética de los clubes privados, la cultura cannábica y el diseño editorial contemporáneo.

El proyecto plantea el cannabis recreativo desde una perspectiva **cultural, sensorial e informativa**, evitando presentarlo únicamente como un producto de consumo. La experiencia visual combina tonos oscuros, púrpuras profundos, detalles dorados y tipografía editorial para construir una identidad cercana al lujo discreto.

La página gira alrededor de una idea sencilla:

> *“No abrimos la puerta a cualquiera que quiera fumar rápido. La abrimos a quien quiere entender qué está fumando, por qué, y hasta dónde.”*

---

## ✦ Concepto

**Casa Púrpura** se presenta como un club privado ficticio dedicado a explorar la cultura del cannabis con curiosidad y criterio.

La experiencia está estructurada como una pequeña publicación digital:

* Introducción al concepto del club.
* Un manifiesto de marca.
* Balance entre beneficios y riesgos del consumo recreativo.
* Presentación de **Purple Kush**.
* Recorrido histórico por su supuesto linaje y popularización.
* Notas sensoriales.
* Comparación conceptual con una flor denominada **Regular**.
* Galería dedicada a la cultura pop cannábica.
* Llamado a la membresía.
* Avisos de consumo responsable y legislación.

El objetivo no es crear una tienda virtual, sino construir una **experiencia de marca ficticia**.

---

## 🎨 Dirección visual

La interfaz utiliza una estética denominada internamente como **Dark Botanical / Private Club**.

### Paleta

| Color     | Uso                     |
| --------- | ----------------------- |
| `#0b0f0c` | Fondo principal         |
| `#12170f` | Paneles                 |
| `#171d14` | Superficies secundarias |
| `#5b3a7a` | Púrpura principal       |
| `#3a2450` | Púrpura profundo        |
| `#a980c9` | Acentos violetas        |
| `#b99457` | Dorado                  |
| `#eee6d8` | Texto principal         |
| `#8d9a80` | Texto secundario        |

La combinación busca evitar la estética típica de una página temática de cannabis y acercarla más a una **marca boutique o club privado**.

### Tipografía

El proyecto utiliza dos familias tipográficas:

* **Fraunces** — titulares, citas y elementos editoriales.
* **IBM Plex Sans** — navegación, cuerpo de texto y elementos funcionales.

La combinación serif + sans-serif permite diferenciar claramente el contenido editorial de la información funcional.

---

## 🗂️ Estructura

```text
CasaPurpura/
│
├── index.html
│
└── images/
    │
    ├── hierbas/
    │   ├── purple-kush/
    │   │   └── purple-kush.jpg
    │   │
    │   └── regular/
    │       └── regular.jpg
    │
    └── cultura/
        ├── walking_Cush.png
        ├── MakonhaJoker.jpg
        └── weed_Face.png
```

El proyecto está construido deliberadamente como una experiencia **single-page**, por lo que toda la navegación ocurre dentro de `index.html`.

---

## 🧩 Secciones

### 01 — El club

Hero principal que introduce la identidad de Casa Púrpura y establece el concepto de la experiencia.

Incluye:

* Identidad de marca.
* Descripción conceptual.
* Imagen principal.
* Navegación interna.
* CTAs hacia el contenido.

---

### 02 — Manifiesto

Una sección editorial que funciona como declaración de principios del club.

Su propósito es establecer desde el comienzo que la experiencia gira alrededor del **consumo informado y consciente**, no del consumo impulsivo.

---

### 03 — Luces y sombras

Una sección dividida en dos columnas que presenta:

**Lo que ofrece**

* Relajación.
* Ritual social.
* Experiencia sensorial.
* Percepción y creatividad.

**Lo que exige respeto**

* Alteración del juicio.
* Riesgos asociados al humo.
* Tolerancia y hábito.
* Legislación local.

La estructura visual busca representar deliberadamente el equilibrio entre las dos perspectivas.

---

### 04 — Purple Kush

La variedad protagonista de la identidad visual.

La sección introduce la Purple Kush mediante:

* Imagen a pantalla completa.
* Descripción editorial.
* Referencias a su origen.
* Presentación de su carácter índica.

---

### 05 — Historia

Una línea temporal recorre la narrativa histórica alrededor de Purple Kush:

```text
Landraces
    ↓
Años 90
    ↓
2000s
    ↓
Boom medicinal
    ↓
Hoy
```

La intención es presentar la variedad como parte de una evolución cultural y no únicamente como una descripción de producto.

---

### 06 — Notas de cata

La experiencia de Purple Kush se divide en tres dimensiones:

**Aspecto · Aroma · Efecto**

Esto introduce una lógica similar a la utilizada en productos gastronómicos, café, vino o tabaco premium.

---

### 07 — Regular

La segunda flor presentada dentro del concepto.

Mientras Purple Kush representa una pieza especial de la colección, **Regular** funciona como una alternativa cotidiana y de perfil más convencional.

La comparación permite crear una pequeña jerarquía dentro del universo ficticio de Casa Púrpura.

---

### 08 — Cultura

Una galería dedicada al lado más informal de la cultura cannábica.

Aquí el diseño abandona parcialmente la estética editorial y permite introducir:

* Humor.
* Arte digital.
* Cultura urbana.
* Memes.
* Iconografía cannábica.

La intención es mostrar que la cultura alrededor del cannabis también existe fuera del discurso sofisticado del club.

---

### 09 — Membresía

El cierre de la experiencia utiliza un CTA inspirado en los clubes privados:

> **¿Listo para entrar con calma?**

La membresía es presentada como limitada y por invitación, reforzando la identidad ficticia de exclusividad.

---

## ⚙️ Tecnologías

El proyecto utiliza únicamente tecnologías web fundamentales:

* **HTML5**
* **CSS3**
* **Google Fonts**
* **CSS Grid**
* **CSS Flexbox**
* **Responsive Design**

No utiliza:

* Frameworks.
* JavaScript.
* Backend.
* Base de datos.
* Dependencias externas de NPM.

Esto permite ejecutar el proyecto directamente desde el navegador.

---

## 📱 Responsive Design

La interfaz cuenta con breakpoints para adaptarse a dispositivos móviles.

En pantallas pequeñas:

* La navegación secundaria desaparece.
* El Hero pasa a una sola columna.
* Las imágenes se reorganizan.
* Las columnas de comparación se convierten en bloques verticales.
* La timeline se adapta a un formato móvil.
* La galería pasa de tres columnas a una.
* El footer se reorganiza verticalmente.

También se incluye soporte para:

```css
@media (prefers-reduced-motion: reduce)
```

para respetar las preferencias de usuarios que solicitan reducir animaciones.

---

## 🚀 Ejecución

No es necesario instalar ninguna dependencia.

Simplemente clona el repositorio:

```bash
git clone <URL_DEL_REPOSITORIO>
cd CasaPurpura
```

y abre:

```text
index.html
```

También puede ejecutarse utilizando un servidor local.

Por ejemplo, con Python:

```bash
python3 -m http.server 8000
```

Después visita:

```text
http://localhost:8000
```

---

## 🌐 Deployment

Al ser un proyecto estático, puede desplegarse fácilmente mediante servicios como:

* GitHub Pages
* Netlify
* Vercel
* Cloudflare Pages

No requiere configuración de backend.

---

## 📸 Assets

Las imágenes utilizadas están organizadas según su función:

```text
images/
├── hierbas/
│   ├── purple-kush/
│   └── regular/
│
└── cultura/
```

Esto mantiene separado el contenido relacionado con las variedades del material gráfico utilizado para representar la cultura.

---

## ⚠️ Disclaimer

Casa Púrpura es un **proyecto conceptual y de diseño web** con fines informativos y culturales.

El contenido relacionado con cannabis no constituye asesoramiento médico ni pretende fomentar actividades ilegales. Las leyes relacionadas con cannabis varían según la jurisdicción.

El consumo de sustancias puede implicar riesgos para la salud y la seguridad. La información, la moderación y el cumplimiento de la legislación local son fundamentales.

**Solo para mayores de edad.**

---

## 🧠 Filosofía del proyecto

Casa Púrpura intenta demostrar que una temática que normalmente se representa mediante códigos visuales muy obvios —hojas verdes, colores saturados y estética psicodélica— puede abordarse desde una dirección artística completamente diferente.

En lugar de:

```text
🍃 Cannabis → Verde → Psicodelia
```

el proyecto propone:

```text
Cannabis
   ↓
Cultura
   ↓
Ritual
   ↓
Editorial
   ↓
Dark Luxury
```

El resultado es una identidad más sobria, elegante y narrativa.

---

## 📌 Estado

**Proyecto:** Casa Púrpura
**Tipo:** Landing page conceptual
**Estado:** ✅ Completado
**Arquitectura:** Static / Single Page
**Responsive:** ✅
**JavaScript:** No requerido
**Backend:** No requerido

---

### Made with curiosity, code & a little purple.

**Casa Púrpura — 2026**

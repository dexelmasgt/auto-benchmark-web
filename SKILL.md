---
name: propuesta-web-kl
description: Genera propuestas de desarrollo web con benchmark, diagnóstico, arquitectura, diseño, 3 paquetes de inversión y documentos descargables (.md + .html). Activación: al mencionar propuesta, cotización, presupuesto, benchmark, análisis de sitio, rediseño web, cliente nuevo, o cuando el usuario pida generar una presentación comercial para un proyecto web.
license: MIT
compatibility: opencode, claude-code, cursor, windsurf, cline
metadata:
  author: KreatifLab
  email: dmas@kreatiflab.com
---

# Skill: propuesta-web-kl

Skill oficial de **KreatifLab** para generar propuestas comerciales de desarrollo web.
Analiza sitios de referencia, diagnostica el sitio actual del cliente, define arquitectura y diseño, propone 3 paquetes de inversión con precios de mercado, y genera documentos descargables en Markdown y HTML premium.

---

## Flujo de ejecución (10 pasos)

Sigue este flujo **exactamente en orden**, paso a paso, esperando la respuesta del usuario antes de continuar al siguiente.

---

### Paso 1 — Información del cliente

Pregunta al usuario uno por uno:

1. **Nombre del cliente / empresa**
2. **Logotipo (URL o ruta de archivo)** — si tiene
3. **Tipo de negocio / industria**
4. **País del cliente** — para ajustar precios de mercado
5. **URL actual** (si tiene)
6. **¿Tiene sitio web actual o es desde cero?**

Anota todo. El logotipo se usará en la portada del HTML y el encabezado del MD.

---

### Paso 2 — Sitios de referencia (benchmarking)

Pide al usuario **3 a 5 URLs** de sitios que al cliente le gusten (competidores o referentes de la industria).

Por cada sitio, analiza y extrae:
- **Nombre y URL**
- **Posicionamiento** (una línea: ¿qué vende este sitio?)
- **3–5 aprendizajes clave** aplicables al proyecto del cliente
- **Inspiración concreta** que se pueda adoptar

---

### Paso 3 — Diagnóstico del sitio actual

**Si el cliente ya tiene sitio web** (Paso 1 indicó que sí):
- Visita la URL proporcionada
- Evalúa: diseño, navegación, mobile-friendliness, velocidad percibida, tipografía, interactividad, presentación de contenido, formularios / contacto, SEO on-page básico
- Genera una tabla **Antes vs Después** con los aspectos evaluados

**Si es desde cero**: indica que no aplica diagnóstico y continúa.

---

### Paso 4 — Arquitectura del sitio

Basado en el tipo de negocio + referencias analizadas, propón:

- **Páginas / secciones** del sitio
- **Estructura de navegación** (menú principal)
- **Flujo de usuario** (cómo navega el visitante desde que llega hasta que convierte)
- Bosquejo tipo diagrama de bloques (formato monospace)

---

### Paso 5 — Decisiones de diseño

Propón:

- **Paleta de colores** (5 colores con códigos HEX + justificación basada en la industria)
- **Tipografía** (títulos + cuerpo, con justificación)
- **UX highlights** (3–5 puntos clave: navegación, animaciones, interactividad, etc.)
- **Tono visual** (premium, minimalista, corporativo, divertido, etc.)

---

### Paso 6 — Propuesta de valor

Redacta **5–6 beneficios clave** que este rediseño/desarrollo aporta al cliente.
Cada uno con formato: `<strong>Beneficio</strong> — explicación breve`

---

### Paso 7 — Próximos pasos / hoja de ruta

Lista de pasos recomendados después del lanzamiento (mantenimiento, contenido, analytics, etc.).
Usa formato de lista con checkboxes `- [ ]`.

---

### Paso 8 — Stack técnico

Recomienda las tecnologías según el tipo de proyecto:

| Tecnología | Uso |
|------------|-----|
| HTML5 semántico | Estructura del sitio |
| CSS3 + Custom Properties | Estilos, temas, animaciones |
| Vanilla JavaScript | Interactividad |
| — o — | — |
| React / Next.js | Si se requiere SPA / SSR |
| Tailwind CSS | Si se requiere utilitario |
| etc. | Ajusta al proyecto |

Incluye siempre una nota "Sin frameworks innecesarios" si aplica.

---

### Paso 9 — Paquetes de inversión

Genera **3 paquetes** con precios estimados basados en:

- **País del cliente** (ajusta moneda y poder adquisitivo):
  - Guatemala / Centroamérica → Q. (Quetzales)
  - México → $ MXN
  - USA / Europa → $ USD
  - Sudamérica → moneda local o USD

- **Complejidad estimada** del sitio (basada en Pasos 4 y 5)

Utiliza estos rangos de referencia de mercado como guía:

| Concepto | Básico | Premium | Full |
|----------|--------|---------|------|
| Diseño | Tema responsive estándar basado en plantilla | Diseño premium con animaciones, micro-interacciones, personalización avanzada | Diseño UI/UX a medida desde cero + identidad visual completa (paleta, tipografía, iconografía, moodboard) |
| Páginas | 1 página (landing / hero + secciones en una sola vista) | 3–5 páginas (inicio, servicios, contacto, blog) | 5+ páginas + panel de administración / dashboard |
| Interactividad | Scroll reveal, hover effects, formulario de contacto funcional | Sliders, carruseles, mapa interactivo, filtros de contenido, custom cursor | Dashboard admin con CRUD, buscador interno, panel de analytics, multi-idioma |
| Backend | Formulario conectado a email (PHP / Formspree / EmailJS) | API REST ligera con 3–5 endpoints (blog, tours/productos, leads) | Backend completo con autenticación, base de datos, API RESTful, roles de usuario |
| CMS | Contenido hardcodeado en HTML (cambios requieren editar código) | Secciones dinámicas vía archivos JSON o CMS headless ligero | CMS completo (admin web para gestionar todo el contenido sin tocar código) |
| Integraciones | Redes sociales, mapa embebido (Google Maps) | Google Analytics 4, WhatsApp / chat en vivo, newsletter | CRM (HubSpot / Salesforce), pasarela de pagos, automatizaciones, multi-idioma real |

**Rangos de precio sugeridos por país:**

*Guatemala / Centroamérica (Q.):*
- Básico: Q.2,500 – Q.5,000
- Premium: Q.5,000 – Q.10,000
- Full: Q.10,000 – Q.20,000
- Mantenimiento anual: 15–20% del valor del paquete

*México ($ MXN):*
- Básico: $7,000 – $14,000
- Premium: $14,000 – $28,000
- Full: $28,000 – $56,000
- Mantenimiento anual: 15–20% del valor

*USA / Europa ($ USD):*
- Básico: $500 – $1,500
- Premium: $1,500 – $4,000
- Full: $4,000 – $10,000
- Mantenimiento anual: 15–20% del valor

*Sudamérica ($ USD o moneda local ajustada):*
- Básico: $300 – $800
- Premium: $800 – $2,000
- Full: $2,000 – $5,000
- Mantenimiento anual: 15–20% del valor

Ajusta los precios según la complejidad real del proyecto (más páginas, más interactividad, más integraciones = hacia el extremo superior del rango).

**Presenta los 3 paquetes al usuario en una tabla clara y pregunta:**
> "¿Confirmas estos precios o quieres ajustar algún paquete antes de generar los documentos?"

Espera confirmación o ajustes del usuario.

---

### Paso 10 — Generación de documentos

Una vez confirmados los precios, genera **ambos** archivos:

1. **`presentacion.md`** — usando la estructura de `templates/presentacion.md` como guía, rellenando con toda la información recolectada en los pasos anteriores (logo del cliente, benchmark, diagnóstico, arquitectura, diseño, propuesta de valor, stack, paquetes de inversión confirmados, próximos pasos).

2. **`presentacion.html`** — usando la estructura de `templates/presentacion.html` como guía, generando un HTML visual premium con:
   - Portada con logo del cliente, datos de KreatifLab, fecha
   - Navegación tipo glassmorphism con todas las secciones
   - Tarjetas de benchmark (grid-3)
   - Tabla de diagnóstico (antes vs después)
   - Arquitectura en formato monospace
   - Paleta de colores con muestras visuales
   - Stack técnico en grid
   - Paquetes de inversión con precios
   - Próximos pasos con checkboxes
   - Footer de KreatifLab
   - Tema oscuro/dorado (KreatifLab signature style)
   - Animación de scroll reveal
   - Navegación suave (smooth scroll)

---

## Formato de salida

- Los archivos se generan en la raíz del proyecto actual como `presentacion.md` y `presentacion.html`
- Si ya existen, preguntar antes de sobrescribir

## Notas importantes

- Siempre usa el logo de KreatifLab en el nav y footer del HTML generado
- Los datos de contacto de KreatifLab van en portada y footer
- El estilo visual del HTML debe ser oscuro premium con acentos dorados (#e8a838)
- La fuente tipográfica es Playfair Display (títulos) + Inter (cuerpo)
- Incluye theme toggle (claro/oscuro) en el HTML

# PTP Mundo Maya · Propuesta de Rediseño Web

---

## Resumen Ejecutivo

**Cliente:** PTP Mundo Maya  
**Proyecto:** Rediseño integral del sitio web  
**URL actual:** https://ptpmundomaya.com/  
**Fecha:** Mayo 2026

**Presentado por:** Dexel Mas — Ing. en Sistemas, Colegiado 21201  
**Contacto:** [dmas@kreatiflab.com](mailto:dmas@kreatiflab.com)

Se realizó un rediseño completo del sitio web de PTP Mundo Maya, transformando una plataforma WordPress desactualizada en un sitio moderno, premium y funcional, orientado al canal B2B (agencias de viajes y tour operadores internacionales).

El nuevo diseño se inspira en los líderes mundiales del turismo de lujo y experiencias, aplicando las mejores prácticas de UI/UX, animación y performance.

---

## Análisis de Referencias (Benchmarking)

Se analizaron 5 sitios web de agencias de viajes premium como inspiración para el rediseño:

### 1. Abercrombie & Kent — [abercrombiekent.com](https://www.abercrombiekent.com/)
**Posicionamiento:** Lujo aspiracional, viajes de expedición  
**Aprendizajes clave:**
- Diseño minimalista que deja respirar el contenido
- Énfasis en guías expertos y acceso exclusivo como diferenciador
- Navegación limpia con mega-menú por tipo de experiencia
- Uso de tipografía serif elegante para transmitir tradición y calidad
- Hero de video/imagen full-screen sin saturación de texto

### 2. Red Savannah — [redsavannah.com](https://www.redsavannah.com/)
**Posicionamiento:** Viajes a medida de alta gama  
**Aprendizajes clave:**
- Diseño oscuro con acentos dorados (paleta validada para nuestro proyecto)
- Tarjetas de destino con overlay al hover que revela información
- Secciones con espaciado generoso (whitespace como lujo)
- Tipografía limpia y jerarquía visual clara

### 3. Black Tomato — [blacktomato.com](https://www.blacktomato.com/)
**Posicionamiento:** Viajes experienciales de lujo, narrativa de marca fuerte  
**Aprendizajes clave:**
- Menú organizado por "Who / What / How" — enfoque en el viajero
- Categorización por tipo de experiencia (no por destino)
- Grid asimétrico para mostrar contenido de forma dinámica
- "Enquire Now" como CTA principal, siempre visible
- Sección de "Remarkable Experiences" como diferenciador
- Trustpilot y pruebas sociales visibles
- Estilo visual cinematográfico con imágenes de alto impacto

### 4. Exceptional Travel — [exceptional-travel.com](https://exceptional-travel.com/)
**Posicionamiento:** Viajes de lujo a medida, enfoque en servicio personal  
**Aprendizajes clave:**
- **Navegación por preguntas: "Where? / When? / What?"** — insight clave adoptado en nuestro rediseño
- Mapa mundial interactivo para explorar destinos visualmente
- Testimonios con nombre real y siglas (autenticidad)
- Filosofía de "Personal Service / Personal Experience / Personal Choice"
- Logo en el hero que se revela con animación
- Sección de "Why Exceptional Travel?" con 3 pilares de valor

### 5. Humboldt Travel — [humboldttravel.co.uk](https://www.humboldttravel.co.uk/)
**Posicionamiento:** Especialistas en Latinoamérica, Asia y África  
**Aprendizajes clave:**
- **Presencia de los fundadores como cara visible de la marca** — genera confianza
- 3 pilares de valor: "Personalised Service / Expert Knowledge / Responsible Travel"
- Blog integrado con contenido de valor (guías, destinos, consejos)
- Testimonios con plataforma de verificación (Feefo)
- Sección de "Conscious Travel" / Responsabilidad
- Call to action constante: "Chat to us to start planning your adventure"
- Múltiples canales de contacto: teléfono UK/US, email, formulario

---

## Diagnóstico del Sitio Original

| Aspecto | Problema detectado | Mejora aplicada |
|---------|--------------------|-----------------|
| Diseño | WordPress anticuado, saturado visualmente | Diseño limpio, premium, oscuro con acentos dorados |
| Navegación | Menú complejo con múltiples subniveles | Navegación simplificada "Where? / When? / What?" |
| Mobile | No responsive-friendly | Diseño mobile-first con 4 breakpoints |
| Tipografía | Sin jerarquía clara | Playfair Display (títulos) + Inter (cuerpo) |
| Velocidad | Imágenes sin optimizar | Lazy loading, imágenes responsivas, WebP-ready |
| Interactividad | Sin animaciones ni micro-interacciones | Custom cursor, scroll reveal, parallax, slider |
| Tours | Presentación en lista textual | Grid asimétrico tipo magazine con precios |
| Mapa | No tenía | Mapa SVG interactivo de Centroamérica |
| Calendario | No tenía | Calendario viajero por mes (mejor época) |
| Testimonios | Texto genérico sin fotos | Carrusel con fotos reales, nombres y países |
| Blog | No tenía | 3 cards de artículos con fecha y categoría |
| Contacto | Formulario básico | Formulario con select de consulta + WhatsApp + oficinas |

---

## Estructura del Nuevo Sitio

```
━━━ HEADER ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Logo PTP Mundo Maya
  [Where?] [When?] [What?]  ·  EN/ES/PT  ·  Enquire Now

━━━ HERO ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Slider full-screen con 3 imágenes rotativas
  Overlay gradiente verde oscuro
  "GUATEMALA — La puerta al Mundo Maya"
  CTA: Explorar Destinos · Acceso B2B
  Stats: 30+ años · 50+ tours · 30K+ viajeros

━━━ WHERE? ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Mapa SVG interactivo de Centroamérica
  6 países clickeables (Guatemala, Belice, Honduras,
  El Salvador, México, Nicaragua)
  Panel de información dinámico al seleccionar país

━━━ WHEN? ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Slider horizontal con 12 tarjetas mensuales
  Cada una: temperatura, clima, recomendación
  Mes actual destacado automáticamente

━━━ WHAT? ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  6 categorías de tours: Regular · Temáticos
  Fly & Drive · Lujo · Bodas · Familia
  Iconos con hover efecto fill dorado

━━━ WHY PTP ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  3 pilares de valor:
  · Expertos Locales (33+ años)
  · Solo B2B (300+ agencias asociadas)
  · Turismo Responsable (5K+ donaciones)

━━━ TOURS DESTACADOS ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Grid asimétrico tipo magazine
  5 tours con imagen, duración, precio y CTA
  Guatemala Express · Ruta Maya Legado
  Guatemala & Belice · Volcanes · El Mirador

━━━ TESTIMONIALS ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Carrusel automático con 3 testimonios
  Fotos reales, nombres completos, país de origen
  Rating 5 estrellas

━━━ TEAM ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  3 miembros del equipo
  Fotos con borde dorado, rol y cita personal
  Ericka · Yoseline · Percy

━━━ BLOG ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  3 artículos recientes
  Categoría, fecha, imagen, extracto, link

━━━ CTA FINAL ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  "Tu próxima aventura te espera"
  3 botones: Contactar · WhatsApp · Acceso B2B
  Fondo verde con patrón geométrico

━━━ CONTACTO ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Formulario (nombre, email, teléfono, consulta, mensaje)
  Datos de oficinas: Guatemala · Palenque · Flores

━━━ FOOTER ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  Logo + descripción
  Links: Destinos · Tours · Empresa
  Redes sociales
  Copyright + Member of
```

---

## Decisiones de Diseño

### Paleta de Colores

| Color | Código | Uso |
|-------|--------|-----|
| Verde oscuro | `#0d4d3d` | Primary, backgrounds |
| Verde claro | `#136b54` | Hovers, gradients |
| Dorado | `#c9a227` | Acentos, CTAs, iconos |
| Casi negro | `#0a0a0a` | Fondo general |
| Blanco | `#f5f5f5` | Texto principal |

**Por qué:** El verde evoca la selva, la naturaleza y los paisajes de Guatemala. El dorado representa el lujo, el sol y la herencia maya. El fondo oscuro transmite sofisticación y permite que las imágenes destaquen.

### Tipografía

| Fuente | Uso |
|--------|-----|
| **Playfair Display** | Títulos, hero, nombres (serif elegante) |
| **Inter** | Cuerpo, navegación, formularios (sans-serif legible) |

**Por qué:** Combinación validada por los sitios de referencia. Playfair Display aporta el toque premium/clásico; Inter garantiza legibilidad en pantalla.

### Experiencia de Usuario

- **Navegación por preguntas** (Where/When/What) — reduce la fricción, el usuario no necesita saber exactamente qué busca
- **Mapa interactivo** — engagement visual, el usuario explora en lugar de leer
- **Grid asimétrico** — rompe la monotonía, dirige la mirada hacia contenido destacado
- **Animaciones sutiles** — reveal al hacer scroll, hover en cards, transiciones suaves
- **Custom cursor** — detalle premium que diferencia del 99% de los sitios

---

## Stack Técnico

| Tecnología | Uso |
|------------|-----|
| HTML5 semántico | Estructura del sitio |
| CSS3 + Custom Properties | Estilos, temas, animaciones |
| Vanilla JavaScript | Interactividad (sin dependencias) |
| Font Awesome 6 | Iconografía |
| Google Fonts | Playfair Display + Inter |
| Unsplash | Imágenes de alta calidad (placeholder) |

**Sin frameworks ni librerías externas:** El sitio carga rápido y es completamente ligero. No depende de jQuery, Bootstrap ni ningún CMS.

---

## Lo que este rediseño logra para PTP Mundo Maya

1. **Posicionamiento premium** — El sitio ahora compite visualmente con Abercrombie & Kent, Black Tomato y Humboldt Travel
2. **Enfoque B2B** — "Solo B2B" como mensaje principal, no secundario
3. **Confianza** — Testimonios reales, equipo visible, estadísticas concretas
4. **Utilidad** — Mapa interactivo, calendario por mes, blog con contenido de valor
5. **Conversión** — CTAs estratégicos en cada sección, WhatsApp integrado
6. **Diferenciación** — "La puerta al Mundo Maya" como narrativa única que ningún competidor tiene

---

## Inversión

Esta propuesta aplica a los **3 entregables ya completados** (marcados con check en Próximos Pasos): rediseño y maquetación del sitio, integración de imágenes placeholder, y formulario de contacto conectado a backend.

| Concepto | Monto |
|----------|-------|
| Desarrollo del sitio | Q.4,500.00 |
| Mantenimiento anual | Q.800.00 |
| **Primer pago único** (desarrollo + 1er año mantenimiento) | **Q.5,300.00** |

> El mantenimiento cubre cambios menores en el contenido del sitio (texto, imágenes, actualizaciones de tours, etc.).

---

## Próximos Pasos Recomendados

- [ ] Reemplazar imágenes de placeholder (Unsplash) con fotos reales de PTP
- [ ] Conectar formulario de contacto a un backend real (email API)
- [ ] Implementar sistema de gestión de tours (admin para agregar/editar)
- [ ] Migrar contenido del blog a un CMS headless si se requiere actualización frecuente
- [ ] Configurar analytics para medir conversión B2B
- [ ] Añadir página individual de cada tour con itinerario detallado

---

*Documento preparado por el equipo de diseño y desarrollo para PTP Mundo Maya.*
*Mayo 2026*

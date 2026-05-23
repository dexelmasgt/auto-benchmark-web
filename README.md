# propuesta-web-kl

Skill de **KreatifLab** para generar propuestas comerciales de desarrollo web profesionales.

Analiza sitios de referencia, diagnostica el sitio actual del cliente, define arquitectura y diseño, propone 3 paquetes de inversión con precios ajustados por país, y genera documentos descargables en Markdown y HTML premium.

---

## ¿Qué hace?

1. Recolecta información del cliente (nombre, logo, industria, país, URL)
2. Analiza 3–5 sitios de referencia (benchmarking)
3. Diagnostica el sitio actual del cliente (si tiene)
4. Define la arquitectura del sitio propuesto
5. Propone decisiones de diseño (colores, tipografía, UX)
6. Redacta propuesta de valor
7. Define hoja de ruta / próximos pasos
8. Recomienda stack técnico
9. Genera 3 paquetes de inversión con precios según país
10. Exporta `presentacion.md` y `presentacion.html`

---

## Requisitos

- **opencode** ≥ 1.0 (nativo)
- **Claude Code** (compatible con SKILL.md)
- **Cursor** (compatible como Rules)
- **Windsurf** (compatible)
- **Cline** (compatible)

Funciona en cualquier agente compatible con el formato estándar `SKILL.md`.

---

## Instalación

### Desde GitHub (vía skills CLI)

```bash
npx skills add dexelmasgt/propuesta-web-kl
```

### Manual (copia local)

```bash
git clone https://github.com/dexelmasgt/propuesta-web-kl.git
# Copia la carpeta a tu proyecto:
cp -r propuesta-web-kl .opencode/skills/propuesta-web-kl
```

### En opencode (con slash command)

Agrega esto a tu `opencode.json`:

```json
{
  "command": {
    "propuesta-web-kl": {
      "description": "Genera propuesta web con benchmark, diagnóstico, diseño y 3 paquetes de inversión",
      "prompt": "Activa el skill propuesta-web-kl y ejecuta el flujo completo paso a paso, preguntando al usuario la información necesaria en cada paso."
    }
  }
}
```

Luego ejecuta:

```
/propuesta-web-kl
```

---

## Activación automática

El skill se activa automáticamente cuando mentions palabras como:

- "propuesta", "cotización", "presupuesto"
- "benchmark", "análisis de sitio", "análisis de referencia"
- "rediseño web", "desarrollo web"
- "cliente nuevo"
- "generar presentación"

---

## Estructura de archivos generados

```
proyecto/
├── presentacion.md      ← Documento de propuesta en Markdown
├── presentacion.html    ← Documento de propuesta en HTML visual premium
```

---

## Personalización

Para modificar la estructura o el diseño de las presentaciones generadas, edita los templates en la carpeta `templates/`:

```
.opencode/skills/propuesta-web-kl/templates/
├── presentacion.md      ← Template base Markdown
└── presentacion.html    ← Template base HTML
```

---

## Salida de ejemplo

El HTML generado incluye:

- Portada con logo del cliente y datos de KreatifLab
- Navegación glassmorphism con todas las secciones
- Tarjetas de benchmark en grid
- Tabla de diagnóstico Antes vs Después
- Arquitectura en formato monospace
- Paleta de colores con muestras visuales
- Paquetes de inversión con precios
- Theme toggle (claro/oscuro)
- Animaciones scroll reveal
- Footer de KreatifLab con contacto

---

## Soporte

**KreatifLab**  
Dexel Mas — Ing. en Sistemas, Colegiado 21201  
<dmas@kreatiflab.com>  
<https://kreatiflab.com>

---

## Licencia

MIT — Libre de usar, modificar y compartir.

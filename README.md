# ACP Ingeniería en Sistemas - Sitio Web

Sitio web profesional para ACP Ingeniería en Sistemas - Consultoría en sistemas y automatización de procesos para gobiernos de Argentina.

## Descripción

Landing page moderna y responsive que presenta los servicios de consultoría en sistemas y automatización de procesos. El sitio destaca 30 años de experiencia en el sector público argentino.

## Características

- ✅ Hero section con propuesta de valor clara
- ✅ Sección de valores: Innovación, Calidad, Agilidad
- ✅ Showcase de casos de éxito: SIDICO, SIGNOS, TICKETS
- ✅ Servicios: Consultoría, Automatización, Software a Medida, Acompañamiento
- ✅ Sección "Por Qué Elegirnos" con diferenciadores
- ✅ Formulario de contacto integrado con WhatsApp
- ✅ Diseño responsive (mobile-first)
- ✅ Paleta de colores profesional: Azul + Verde + Gris

## Estructura

```
acp-sistemas-web/
├── index.html     # Sitio web completo (HTML + CSS + JS)
└── README.md      # Este archivo
```

## Publicación en Vercel

### Opción 1: Vercel con GitHub (Recomendado)
1. Los cambios en `main` se despliegan automáticamente en Vercel
2. Ver cambios en vivo en pocos segundos

### Opción 2: Vercel CLI
```bash
npm install -g vercel
vercel login
vercel deploy
```

### Opción 3: Vercel Dashboard
Sube los archivos en https://vercel.com/new

## Personalización

### Cambiar colores
Edita las variables CSS en `index.html` (líneas 14-22):

```css
:root {
    --primary-blue: #0052A3;      /* Color azul principal */
    --accent-green: #2BAE66;      /* Color verde acento */
    --light-gray: #F5F7FA;        /* Gris claro */
    --dark-gray: #2C3E50;         /* Gris oscuro */
    --text-gray: #555555;         /* Color texto */
}
```

### Cambiar logo
Modifica el ícono "A" en la sección `.logo-icon` o reemplaza con una imagen.

### Agregar más casos de éxito
Duplica un `.case-card` en la sección de casos (líneas 666-679).

### Email de contacto
Cambia `ia@acpsistemas.com.ar` en el footer y en el mensaje de WhatsApp.

## Características técnicas

- **HTML5** semántico
- **CSS3** con Grid y Flexbox
- **JavaScript vanilla** para formulario y WhatsApp
- **Responsive design** para todos los dispositivos
- **Optimizado** para buscadores (SEO-friendly)
- **Performance**: Archivo único, carga rápida

## Contacto y Soporte

**Email:** ia@acpsistemas.com.ar
**Ubicación:** Mendoza, Argentina

---

*Desarrollado con Claude AI*
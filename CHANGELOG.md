# 📜 CHANGELOG  
Historial de cambios del proyecto **Newsletter Sign-Up with Success Message**  
Reto de Frontend Mentor

---

## [F1] – Briefing & Análisis (2025-11-29)
- Lectura completa del README del reto.
- Revisión del style-guide y Figma.
- Identificación de vistas: formulario, errores, success.
- Preparación de flujo de trabajo Git (`main`, `dev`, `feature/*`).
- Definición del árbol de archivos limpio sin assets innecesarios.

---

## [F2] – Setup Inicial (2025-11-29)
- Creación del proyecto base.
- Estructura de carpetas profesional (assets, css, scripts, docs).
- Añadido `.gitignore` optimizado.
- Añadido README.md base.
- Enlaces correctos al CSS y JS.
- Primer commit y push a GitHub (`main` + `dev`).

---

## [F3] – Maquetación & Layout (en progreso)
### ✅ Completado hasta ahora
- HTML completo de la vista de formulario y vista de éxito (success) con `hidden`.
- Estructura semántica + accesibilidad básica (`aria-live`, `aria-describedby`, `aria-invalid`).
- Implementación de tokens CSS (colores, tipografía, spacing y radius).
- Estilos mobile-first iniciales para:
  - Tipografía base
  - Lista con iconos
  - Formulario (label, input, botón)
- Ajuste del layout en tablet:
  - Centrado vertical y horizontal de la tarjeta usando `min-height` + grid.
  - La tarjeta deja de ser full-screen en tablet (altura por contenido).
  - Bordes redondeados aplicados a la tarjeta en tablet.
- Preparación del layout desktop:
  - Separación de responsabilidades con modificadores (`card--signup` / `card--success`).
  - Inicio de grid en desktop para `card--signup` (estructura a 2 columnas).

### 🔜 Pendiente dentro de F3
- Ajuste fino de espaciados internos del contenido (consistencia vertical).
- Integración visual completa de la imagen con el radio en tablet/desktop.
- Layout desktop final (proporciones, alineación, altura de imagen, etc.).
- Estados hover/focus/active en inputs y botones.
- Clases y estilos visuales para estado de error.

---

## [F4] – Lógica JavaScript (pendiente)
- Validación de email.
- Estados de error.
- Cambio de vistas (form → success → form).
- Inyección dinámica del email en success message.
- Limpieza y accesibilidad mínima.

---

## [F5] – QA & Deploy (pendiente)
- Pruebas en mobile, tablet y desktop.
- Focus visible y navegación por teclado.
- Limpieza final del código.
- Deploy en GitHub Pages.
- Actualización del README con enlaces finales.

---

## [F6] – Retro Final (pendiente)
- Análisis del proceso.
- Aprendizajes reales.
- Mejoras aplicables al próximo reto.
# Newsletter Sign-Up with Success Message  
Solución al reto de Frontend Mentor.

Este proyecto forma parte de mi ruta profesional en **Frontend Mentor**, centrada en mejorar habilidades de maquetación avanzada, diseño responsive y fundamentos de JavaScript para validación y manejo del DOM.

---

## 📸 Vista previa

![Preview](./preview.jpg)

---

## 🎯 Objetivo del reto

Los usuarios deben poder:

- Introducir un email y enviar el formulario.
- Ver errores si:
  - El campo está vacío.
  - El formato del email no es válido.
- Ver un mensaje de éxito que incluya su email tras un envío correcto.
- Interactuar con la interfaz con estados de **hover**, **focus** y **active**.
- Visualizar el diseño correctamente desde mobile hasta desktop.
- Regresar desde la vista de éxito al formulario mediante **“Dismiss message”**.

---

## 🧩 Tecnologías utilizadas

- **HTML5 semántico**
- **CSS3 / SCSS** (mobile-first, layout responsive, variables, flex/grid)
- **JavaScript** (validación, manipulación del DOM, cambio de vistas)
- **Git / GitHub** (flujo profesional: `main`, `dev`, `feature/*`)
- **Frontend Mentor Starter Pack**

---

## 📂 Estructura del proyecto

```text
/
├─ assets/
│  ├─ fonts/              # Tipografías y licencia
│  └─ images/             # Iconos e ilustraciones usados en la web
│
├─ css/
│  ├─ style.css           # CSS compilado
│  └─ style.scss          # SCSS original
│
├─ scripts/
│  └─ main.js             # Lógica del formulario, validación y vistas
│
├─ docs/
│  └─ style-guide.md      # Tokens y referencias del reto
│
├─ .gitignore
├─ CHANGELOG.md           # Historial de cambios por fases
├─ index.html
├─ preview.jpg            # Vista previa de mi solución.
└─ README.md              # Este documento
```

---

## 🚀 Funcionalidades principales

- Validación manual del email:
  - Campo vacío
  - Formato no válido
- Mensajes de error accesibles con `aria-live`.
- Intercambio dinámico entre dos vistas:
  - **Formulario**
  - **Mensaje de éxito** con email inyectado
- Botón **“Dismiss message”** para volver a empezar.
- Diseño completamente responsive basado en Figma.
- Estados interactivos:
  - `:hover`
  - `:focus-visible`
  - `:active`
- Indicadores visuales de error coherentes con el diseño.

---

## 🧪 Retos enfrentados

- Reproducir los espaciados exactos del diseño (desktop y mobile).
- Controlar correctamente los estados de error y accesibilidad.
- Alternar vistas sin recargar la página.
- Evitar distorsiones en ilustraciones multiformato.
- Mantener el proyecto limpio sin archivos innecesarios del starter pack.

---

## 📚 Lo que aprendí

- Manejo práctico del DOM sin frameworks.
- Validación de formularios con JS moderno.
- Accesibilidad mínima aplicada a formularios.
- Diseño intrínseco y patrones responsive.
- Flujo Git profesional con ramas `main`, `dev` y `feature/*`.

---

## 🔗 Enlaces

Reto en Frontend Mentor:  
https://www.frontendmentor.io/challenges/newsletter-signup-form-with-success-message-3FC1AZbNrv

Solución en Frontend Mentor: *(Se añadirá cuando se suba)*  

Live Demo: *(Se añadirá tras subir repositorio)*

---

## 👤 Autor

**Jorge Luis Muñoz Wunder**  
Desarrollador Frontend en formación  
GitHub: https://github.com/jmunozw
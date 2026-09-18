# Mi Portafolio

Portafolio personal de una sola página, sin frameworks ni build steps: es un único
archivo `index.html` con todo el CSS y JS incluido.

## 1. Personalízalo

Abre `index.html` y edita:

- **Nombre y título**: en `<title>`, la barra de navegación (`~/tu-nombre`) y el `<h1>` del hero.
- **Sección "Sobre mí"**: reemplaza los párrafos y los datos (`ubicación`, `stack`, etc).
- **Proyectos**: cada bloque `<details class="node">` es un proyecto. Cambia el nombre,
  las tecnologías (`<div class="stack">`), la descripción y los enlaces a código/demo.
  Puedes duplicar un bloque `<details>` para agregar más proyectos.
- **Habilidades**: edita las listas dentro de `.skills-grid`.
- **Contacto**: cambia el correo y los enlaces a GitHub/LinkedIn en `#contact`.

## 2. Súbelo a GitHub

```bash
git init
git add .
git commit -m "Primer commit: portafolio personal"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git
git push -u origin main
```

## 3. Actívalo con GitHub Pages

1. Ve a tu repositorio en GitHub → **Settings** → **Pages**.
2. En "Build and deployment", selecciona **Deploy from a branch**.
3. Elige la rama `main` y la carpeta `/ (root)`.
4. Guarda. En un par de minutos tu sitio estará disponible en:
   `https://TU-USUARIO.github.io/TU-REPOSITORIO/`

> Tip: si quieres que el sitio viva en `https://TU-USUARIO.github.io` directamente
> (sin subcarpeta), nombra el repositorio exactamente `TU-USUARIO.github.io`.

## Estructura

```
.
├── index.html   # Todo el sitio: HTML, CSS y JS
└── README.md    # Este archivo
```

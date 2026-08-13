# Portafolio personal — Lázaro Heredia Manso

Sitio web profesional estático creado para GitHub Pages. Incluye perfil, trayectoria, formación, stack tecnológico y una selección de proyectos web publicados.

## Ver localmente

No requiere instalación ni dependencias. Abre `index.html` en el navegador o inicia un servidor local:

```bash
python3 -m http.server 8000
```

Después visita `http://localhost:8000`.

## Publicar en GitHub Pages

1. Sube los cambios a la rama `main`.
2. En GitHub, abre **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Elige la rama `main`, carpeta `/ (root)`, y pulsa **Save**.

El sitio quedará disponible en:

<https://lherediamanso.github.io/blog/>

## Estructura

- `index.html`: contenido y estructura del portafolio.
- `modern.css`: diseño moderno, responsive y animaciones.
- `script.js`: navegación móvil y efectos de entrada.
- `assets/favicon.svg`: icono del sitio.
- `assets/projects/`: logos oficiales de los proyectos destacados.

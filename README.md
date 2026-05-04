# Portafolio — Jose Titto Yampa

Portafolio personal desarrollado con React y Vite. Presenta mi experiencia, stack tecnologico, proyectos y formas de contacto. Diseñado con componentes reutilizables, datos desacoplados de la logica de renderizado y despliegue automatico en GitHub Pages.

Demo en produccion: [JtittoY.github.io/portafolio](https://JtittoY.github.io/portafolio/)

---

## Stack

| Capa         | Tecnologias                          |
|--------------|--------------------------------------|
| Framework    | React 19, Vite 8                     |
| Estilos      | Tailwind CSS 3                       |
| Despliegue   | GitHub Pages, GitHub Actions         |
| Calidad      | ESLint, PostCSS, Autoprefixer        |

---

## Despliegue automatico

El proyecto usa **GitHub Actions** para despliegue continuo. Cada `push` a la rama `main` o `master` desencadena el pipeline que:

1. Instala dependencias con `npm install`
2. Construye el proyecto con `npm run build`
3. Publica la carpeta `dist/` en GitHub Pages

No se necesita ningun comando manual para actualizar la web en produccion.

---

## Ejecucion en local

```bash
# Instalar dependencias
npm install

# Servidor de desarrollo con HMR
npm run dev

# Construir para produccion
npm run build
```

El servidor de desarrollo estara disponible en `http://localhost:5173`.

---

## Contacto

- GitHub: [github.com/JtittoY](https://github.com/JtittoY)
- Correo: jtittoy@gmail.com
- WhatsApp: +591 74059430

---

## Licencia

Codigo abierto y disponible para la comunidad. Puedes usarlo como referencia o base para tu propio portafolio.

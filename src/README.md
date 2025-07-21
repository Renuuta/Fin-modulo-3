# TechDesign Solutions - Sección Clave

Este proyecto implementa una sección clave del portal web de TechDesign Solutions siguiendo las mejores prácticas de desarrollo de interfaces modernas.

## Estructura del Proyecto

```
fin modulo 3/
│
├── src/
│   ├── assets/
│   │   └── img/                # Imágenes
│   ├── styles/
│   │   ├── _variables.scss     # Variables SASS
│   │   ├── _mixins.scss        # Mixins SASS
│   │   ├── _layout.scss        # Estilos de layout
│   │   ├── _components.scss    # Componentes (BEM)
│   │   └── main.scss           # Archivo principal SASS
│   └── index.html              # Página principal
│
├── README.md                   # Explicación del proyecto
```

## Tecnologías Utilizadas
- **Metodología BEM** para la organización de clases CSS.
- **SASS** como preprocesador CSS, con archivos parciales y uso de variables y mixins.
- **Bootstrap 4** para el sistema de grid y componentes responsivos.

## Cómo ejecutar el proyecto
1. Instala SASS si no lo tienes:
   ```powershell
   npm install -g sass
   ```
2. Compila los estilos:
   ```powershell
   sass src/styles/main.scss src/styles/main.css
   ```
3. Abre `src/index.html` en tu navegador.

## Personalización
- Se puede modificar los archivos en `src/styles/` para cambiar colores, fuentes o agregar nuevos componentes siguiendo la metodología BEM.

## Demo
Se sube el proyecto a GitHub y se publica la demo en GitHub Pages para mostrar la funcionalidad.

---

**Autor:** Renata Mardones

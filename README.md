# Proyecto Capalsa 2025

Sitio web corporativo de Capalsa, una empresa de sourcing y abastecimiento integral.

## Tecnologías y Estilo

El proyecto está construido con las siguientes tecnologías y convenciones:

- **Framework**: [Astro](https://astro.build/)
- **Lenguaje**: TypeScript
- **Estilos**: [Tailwind CSS](https://tailwindcss.com/) para el diseño y la interfaz.
- **Tipografía**: La fuente principal es **Inter**, importada desde Google Fonts.
- **Paleta de Colores**:
  - **Primario (Acento)**: Naranja (`#F97316`, `orange-500` en Tailwind).
  - **Neutrales**: Una escala de grises (`neutral-300` a `neutral-600`) para textos y fondos.
  - **Fondo Principal**: Blanco (`#FFFFFF`) y Negro (`#000000`) para secciones específicas como el hero.

## Estado del Proyecto

### Implementado

- **Estructura General**: Se ha definido la estructura completa del sitio, incluyendo el layout principal y las secciones.
- **Componentes Principales**: Todos los componentes de la página de inicio están creados y funcionales:
  - `Header`
  - `Footer`
  - `Hero`
  - `Authority` (sección de clientes)
  - `Divisions` (verticales de negocio)
  - `About` (sección sobre la empresa)
  - `Contact` (formulario de contacto)
- **Páginas**: Se han creado las páginas principales (`index`, `contacto`, `faqs`, `politicas`) y la estructura para el blog.
- **Diseño Responsivo**: El sitio se adapta a diferentes tamaños de pantalla (móvil, tablet y escritorio) gracias a Tailwind CSS.

### Tareas Pendientes

El proyecto se encuentra en una fase avanzada de maquetación, pero requiere de contenido y funcionalidades adicionales para estar completo.

1.  **Contenido Visual (Imágenes)**:
    - **Hero**: Falta una imagen de fondo de alto impacto.
    - **Authority**: Se deben reemplazar los nombres de clientes por sus logotipos oficiales.
    - **Divisions**: Agregar iconos o imágenes que representen cada vertical de negocio.
    - **About**: Incluir una imagen del equipo o de las instalaciones para personalizar la sección.
    - **Blog**: Cada artículo necesitará una imagen destacada.
    *Todas las imágenes deben ser colocadas en la carpeta `public/images`.*

2.  **Contenido Escrito**:
    - **Blog**: La sección del blog es un placeholder. Es necesario escribir y publicar los artículos.
    - **Textos**: Revisar y finalizar todos los textos del sitio para asegurar que el mensaje sea claro y preciso.

3.  **Animaciones y Transiciones**:
    - El sitio es actualmente estático. Se deben agregar animaciones sutiles y transiciones para mejorar la experiencia de usuario (ej. al hacer scroll, en interacciones con botones, etc.).

4.  **Funcionalidad**:
    - **Formulario de Contacto**: Aunque el formulario está integrado con Netlify (`data-netlify="true"`), es necesario configurar y probar el servicio para asegurar que los mensajes se reciban correctamente.
    - **Enlaces**: Algunos enlaces, especialmente en la sección de `Divisions`, son placeholders y deben ser actualizados a sus URLs finales.
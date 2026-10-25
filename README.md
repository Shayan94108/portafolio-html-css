# Portafolio de Jhojan Sebastian

Trabajo final del módulo de HTML/CSS. El sitio presenta un portafolio académico con propuestas de diseño web, un formulario de presupuesto y una página de contacto con datos ficticios.

## Enlaces de entrega

- Repositorio público: https://github.com/Shayan94108/portafolio-html-css
- Web en GitHub Pages: https://shayan94108.github.io/portafolio-html-css/

## Páginas

- `index.html`: presentación, sobre mí, proyectos seleccionados y forma de trabajar.
- `portfolio.html`: galería de seis propuestas ficticias en cuadrícula.
- `presupuesto.html`: formulario con validación nativa de HTML5.
- `contacto.html`: datos de ejemplo, mapa orientativo, aviso legal y privacidad.

Las cuatro páginas comparten menú superior, indicación de la página actual, hoja de estilos y pie de página con enlaces sociales.

## Organización de archivos

```text
portafolio-html-css/
├── index.html
├── portfolio.html
├── presupuesto.html
├── contacto.html
├── README.md
├── .gitignore
├── css/
│   └── estilos.css
└── img/
    ├── proyecto-cafeteria.svg
    ├── proyecto-estudio.svg
    ├── proyecto-galeria.svg
    ├── proyecto-viajes.svg
    ├── proyecto-editorial.svg
    ├── proyecto-formulario.svg
    ├── mapa-contacto.png
    ├── instagram.svg
    ├── linkedin.svg
    └── github.svg
```

## Tecnologías y diseño

Se utilizan únicamente HTML5 y CSS3. No hay JavaScript, frameworks, bibliotecas externas ni fuentes que necesiten descargarse.

La paleta combina azul oscuro (`#132F3A`), verde (`#246B61`) y dorado (`#D8BB7B`), junto con blanco y variaciones de estos tonos. Las distribuciones se realizan con Flexbox y Grid. Las reglas `@media` adaptan las páginas a pantallas pequeñas.

Las miniaturas son ilustraciones SVG de propuestas de práctica. No representan clientes ni trabajos profesionales reales. El mapa PNG muestra una dirección ficticia y no debe utilizarse para orientarse en calles reales.

## Probar el proyecto

1. Descomprimir la carpeta del proyecto.
2. Abrir `index.html` en un navegador.
3. Recorrer las cuatro opciones del menú y los enlaces del pie.
4. En presupuesto, intentar continuar sin rellenar los campos y después con datos ficticios válidos.

También se puede consultar directamente la web de GitHub Pages indicada arriba.

## Validación del formulario

- Nombre: obligatorio, entre 2 y 80 caracteres.
- Email: obligatorio, de tipo `email`.
- Teléfono: obligatorio, exactamente nueve dígitos, sin espacios ni prefijo.
- Información: obligatoria, entre 10 y 1500 caracteres.
- Política de privacidad: casilla de aceptación obligatoria.

El navegador realiza estas comprobaciones antes de continuar. El formulario es una demostración sin servicio de recepción: utiliza GET para volver a la página de presupuesto y mostrar una confirmación con `:target`. Los datos de prueba aparecen en la URL. No se envían correos ni se tramitan presupuestos; se deben usar datos ficticios.

## Modificar el contenido

- Textos y enlaces: editar el HTML de la página correspondiente.
- Colores, tamaños y separación: editar `css/estilos.css`. Sus comentarios separan las zonas del sitio.
- Imágenes: sustituir los archivos de `img/`, manteniendo las rutas o actualizando `src` y `alt` en el HTML.
- Menú o pie: aplicar el mismo cambio a las cuatro páginas y conservar `aria-current="page"` en el enlace de la página actual.
- Datos de contacto: modificar también las secciones de aviso legal y privacidad si el proyecto se convierte en una web real.

## Comprobaciones realizadas

- Validación del HTML de las cuatro páginas mediante Nu HTML Checker de W3C.
- Revisión de enlaces internos, rutas de imágenes, fragmentos y etiquetas de los formularios.
- Pruebas del formulario con campos vacíos, email incorrecto, teléfono incompleto y casilla de privacidad sin marcar.
- Revisión de las vistas de escritorio y móvil.

La validación formal del CSS no se exige en el enunciado. Se ha revisado su presentación y funcionamiento junto con las páginas.

## Entrega al campus

El archivo comprimido se denomina `jhojan_alipour_trabajoHTML.zip`. Este README incluye las dos direcciones que solicita el campus: repositorio público y web publicada en GitHub Pages.

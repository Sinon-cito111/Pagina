# Pagina
# Rueda Libre · sitio principal y campaña Rueda Nocturna

Proyecto de Nodo Digital para **Rueda Libre**, un negocio de alquiler de bicicletas en Medellín. Son dos productos que se conocen entre sí:

- **Sitio principal:** alquiler de bicicletas, tarifas, rutas y reservas (Bootstrap 5.3).
- **Landing "Rueda Nocturna":** campaña de recorridos nocturnos de jueves a sábado, con rutas, planes e inscripción (Tailwind CSS 4, modo claro y oscuro).

## Enlaces publicados

> Confirma la dirección exacta en *Settings > Pages* del repositorio.

| Producto | Enlace |
|---|---|
| Sitio principal | https://sinon-cito111.github.io/Pagina/ |
| Landing Rueda Nocturna | https://sinon-cito111.github.io/Pagina/nocturna/ |
| Kit de componentes | https://sinon-cito111.github.io/Pagina/nocturna/componentes.html |
| Repositorio | https://github.com/Sinon-cito111/Pagina |

## Páginas

| Archivo | Contenido |
|---|---|
| `index.html` | Inicio: portada, rutas, flota, servicios, beneficios y carrusel de promociones |
| `paginas/tarifas.html` | Tablas de tarifas y de tours |
| `paginas/reservas.html` | Formulario de reserva con validación y modal de políticas |
| `nocturna/index.html` | Landing: encabezado, rutas, planes, cómo funciona e inscripción |
| `nocturna/componentes.html` | Kit de componentes: botones, card, alertas y campos |
| `nocturna/prototipo.html` | Prototipo aprobado por diseño (Play CDN, solo desarrollo) |

## Tecnologías

- **HTML semántico** y formularios con validación nativa.
- **Bootstrap 5.3** (CDN) con una hoja propia cargada después, con variables de marca.
- **Tailwind CSS 4** con la CLI de npm: `src/input.css` define los colores y las fuentes con `@theme`; el CSS final está minificado en `nocturna/src/output.css`.
- **Google Fonts:** Montserrat (títulos) y Open Sans (texto).
- **Git y GitHub Pages** para el control de versiones y la publicación.

### Marca (igual en los dos productos)

| Color | Código |
|---|---|
| Verde Ruta | `#1E7A4F` |
| Naranja Pedal | `#F39A2B` |
| Azul Noche | `#14213D` |
| Crema | `#FAF6EF` |
| Gris Asfalto | `#5B6470` |
| Amarillo Farol (campaña) | `#FFD166` |

## Recomendación de framework

> Completa las cifras con tus mediciones (DevTools > Network).

| Criterio | Bootstrap | Tailwind |
|---|---|---|
| Curva de aprendizaje | Rápida: los componentes ya existen (navbar, carrusel, modal, validación). | Más exigente: hay que conocer muchas utilidades y escribir la interacción propia. |
| Personalización | Se sobrescriben variables y clases ya definidas. | El diseño sale de la marca, sin partir de un aspecto predefinido. |
| Tamaño final | CSS: ___ KB · JS: ___ KB | CSS minificado: ___ KB, sin JS |
| Casos de uso | Sitios con componentes interactivos y formularios. | Landings y piezas a medida con diseño propio. |

**Recomendación para Rueda Libre:** mantener el sitio principal en Bootstrap, porque usa carrusel, navbar, modal y validación que ya vienen resueltos, y usar Tailwind en las landings de campaña, donde pesa más el diseño propio y el tamaño. Migrar todo a un solo framework solo se justifica en un rediseño completo.

## Capturas

| Escritorio | Celular (360 px) | Modo oscuro |
|---|---|---|
| ![Escritorio](img/capturas/escritorio.png) | ![Celular](img/capturas/celular.png) | ![Modo oscuro](img/capturas/modo-oscuro.png) |

## Aprendizajes

- La estructura semántica y los textos alternativos se piensan antes de dar estilo.
- Mobile-first: se diseña primero para el celular y se agregan los breakpoints `sm:`, `md:` y `lg:`.
- Con dos frameworks hay que cuidar que la marca sea la misma: mismos códigos de color, fuentes y datos de contacto.
- El contraste se verifica antes de entregar: Verde Ruta no sirve como texto sobre Azul Noche (3,01), así que en modo oscuro se usa Amarillo Farol.
- `@apply` en la capa de componentes evita repetir las listas largas de clases en los botones.
- Lo que no está publicado y documentado, para el cliente no existe.

## Autor

Simon Berrio Bedoya · Nodo Digital
# Pagina

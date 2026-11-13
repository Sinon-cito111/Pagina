# Rueda Libre 🚲

¡Bienvenido al repositorio oficial de **Rueda Libre**, tu servicio de alquiler de bicicletas y recorridos guiados en la ciudad de Medellín! Este proyecto fue desarrollado a lo largo de tres semanas como parte de un proceso de desarrollo web profesional, integrando desde maquetación semántica y CSS nativo hasta frameworks modernos como Bootstrap 5 y Tailwind CSS.

---

## 🔗 Enlaces Publicados
* **Sitio Principal (Bootstrap):** https://sinon-cito111.github.io/Pagina/
* **Landing Page de Campaña (Tailwind):** https://sinon-cito111.github.io/Pagina/nocturna/index.html

---

## 📄 Páginas del Proyecto
* **`index.html`**: Página de inicio principal con carrusel de planes, presentación, flota ampliada, beneficios, sección de contacto y enlaces a la campaña nocturna.
* **`paginas/tarifas.html`**: Consulta de tarifas por hora y acordeón interactivo de rutas y recorridos guiados.
* **`paginas/reservas.html`**: Formulario de reservas completo con validaciones nativas estrictas, modal de políticas y restricciones de negocio.
* **`nocturna/index.html`**: Landing page promocional de la campaña "Rueda Nocturna" diseñada con Tailwind CSS, enfoque *mobile-first*, soporte para modo oscuro y formulario de inscripción dedicado.
* **`nocturna/componentes.html`**: Kit de componentes UI estandarizado para la campaña.

---

## 🛠️ Tecnologías y Herramientas
* **Estructura:** HTML5 semántico (`header`, `nav`, `main`, `section`, `article`, `footer`, `fieldset`).
* **Estilos y Layouts:** 
  * CSS nativo / Vanilla (variables globales, Flexbox, CSS Grid).
  * Bootstrap 5.3 (Grillas, componentes interactivos, Navbar, Modales, Carrusel, Bootstrap Icons).
  * Tailwind CSS (Framework *utility-first*, directiva `@theme`, modo oscuro `dark:`).
* **Control de versiones:** Git y GitHub Pages.

---

## ⚖️ Comparativa de Frameworks: Bootstrap vs. Tailwind (MiniReto 8)
Tras desarrollar partes del sitio con ambos frameworks, aquí tienes la comparativa técnica basada en la experiencia del proyecto:

* **Curva de Aprendizaje:** 
  * *Bootstrap:* Más rápida para ensamblar componentes prefabricados listos para usar (botones, tarjetas, modales).
  * *Tailwind:* Requiere familiarizarse con la nomenclatura *utility-first*, pero ofrece total libertad de diseño sin combatir contra estilos predeterminados.
* **Personalización:**
  * *Bootstrap:* Tiende a mostrar un aspecto estandarizado a menos que se sobrescriban profundamente sus variables SASS/CSS.
  * *Tailwind:* Altamente personalizable mediante la configuración de `@theme`, permitiendo una identidad visual de marca única directamente en el marcado.
* **Tamaño Final:**
  * *Bootstrap:* Carga hojas de estilo y paquetes de JavaScript más robustos que incluyen utilidades no siempre utilizadas.
  * *Tailwind:* Al compilar con la opción `--minify` de la CLI, genera un archivo CSS optimizado que contiene únicamente las clases implementadas.
* **Casos de Uso Recomendados para Rueda Libre:**
  * Se recomienda **Bootstrap** para estructuras corporativas estandarizadas donde se prioriza la velocidad de despliegue mediante componentes estables.
  * Se recomienda **Tailwind CSS** para landing pages promocionales y dinámicas como **Rueda Nocturna**, donde el diseño responsivo a medida y el modo oscuro son fundamentales.

---

## 📸 Capturas de Pantalla

### Vista de Escritorio (Sitio Principal)
*(Inserta aquí la captura de tu vista de escritorio)*

### Vista de Celular (Responsive 360px)
*(Inserta aquí la captura de tu vista en dispositivos móviles)*

### Modo Oscuro (Rueda Nocturna)
*(Inserta aquí la captura del modo oscuro)*

---

## 💡 Aprendizajes Clave
* Dominio avanzado de la arquitectura *Mobile-First* y distribución moderna con CSS Grid y Flexbox.
* Implementación de criterios de accesibilidad web (etiquetas ARIA, contraste de colores validado, navegación fluida por teclado con `Tab`).
* Aplicación de validaciones de formularios nativas y estrictas en HTML5 (patrones para cédula, celular, correos y restricciones temporales).
* Integración fluida entre un ecosistema basado en componentes (Bootstrap) y una landing basada en utilidades (Tailwind).

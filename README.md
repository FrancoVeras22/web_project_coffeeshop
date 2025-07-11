# Triple Espresso

## Nombre del Proyecto:

web project Coffee shop **Triple Espresso**, ubicada en la biblioteca TripleTen.

---

## Descripción Breve del Proyecto:

Este proyecto consiste en una página web diseñada para representar la cafetería **Triple Espresso**. Parte de mi aprendizaje en HTML y CSS avanzado, aplicando la metodología BEM (Block Element Modifier) para organizar las clases de CSS de forma estructurada.

---

## Tecnologías y Técnicas Utilizadas:

- Lenguajes: **HTML5** y **CSS3 (Hojas de estilo en cascada)**
- Metodología: **BEM (Block Element Modifier)**

---

## Descripción Detallada del Proyecto:

#### HEAD:

- Configuración del idioma: Español.
- Adaptación al ancho de pantalla mediante la etiqueta **viewport**.
- Inclusión de etiquetas **meta** con información de descripción, palabras clave (**keywords**) y autor, para mejorar el SEO.
- Título personalizado y favicon.
- Uso de fuentes externas (Google Fonts) con respaldo en caso de error al cargarlas.

#### BODY:

El diseño de la página está estructurado como un **scroll infinito**, presentando cada sección una debajo de otra utilizando **display: flex** en los bloques principales (encabezado, contenido y pie de página).

---

### Encabezado:

- Bienvenida al usuario y presentación general de la cafetería (horario y dirección).
- Ilustración moderna del interior de la cafetería posicionada con `position`.
- Logo de la cafetería insertado con `img` y atributo `alt` para accesibilidad.
- Menú de navegación con tres enlaces: **Recetas**, **Reserva una mesa**, y **Contactos**, organizados en la esquina superior derecha con `display: flex`.
- Efecto `hover` en los enlaces para mejorar la interacción.

---

### Sección Recetas:

- Sección dedicada a compartir contenido educativo sobre café.
- Dos videos insertados mediante etiquetas **iframe**, con estilos definidos en CSS usando metodología BEM.
- Estructura organizada con **divs** y estilos aplicados desde el archivo CSS.

---

### Sección de Reservas:

- Formulario para recibir solicitudes de reserva.
- Campos del formulario:
  - **Texto**: nombre del comensal.
  - **Número**: número de comensales (mínimo 1, máximo 8).
  - **Datetime-local**: selección de fecha y hora.
  - **Email**: validación automática del formato.
  - **Checkbox**: aceptación de términos y condiciones.
- Todos los campos son obligatorios (`required`).
- Botón de envío con efecto `hover` (opacidad disminuida al pasar el cursor).

---

### Pie de Página (Footer):

- Logo de la cafetería.
- Enlaces a redes sociales insertados con la etiqueta `a`.
- Información de derechos de autor.
- Diseño flexible con **display: flex**.
- Elemento decorativo: círculo azul con `border-radius: 100%` y color `#2F80ED`.

---

## Planes de Mejora del Proyecto:

- Fijar el menú de navegación en la parte superior haciendo que el logo triple espresso te lleve al encabezado.
- Bloquear fechas anteriores en el formulario de reserva.

---

## Autor:

**Franco Verastegui**  
Desarrollador Web en curso.
https://francoveras22.github.io/web_project_coffeeshop/

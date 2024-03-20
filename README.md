# Utilitarios de HTML, CSS y JavaScript

Este repositorio contiene una colección de utilitarios comunes implementados en HTML, CSS y JavaScript para agregar funcionalidades interactivas a tus proyectos web. Estos utilitarios incluyen botones, slides, tabs y acordeones, que pueden ser fácilmente integrados y personalizados en tu sitio web.

## Contenido

1. [Botones](#botones)
2. [Slides](#slides)
3. [Tabs](#tabs)
4. [Acordeones](#acordeones)

---

## Botones

Los botones son elementos esenciales en cualquier interfaz de usuario. Este utilitario proporciona una variedad de estilos de botones que puedes utilizar para mejorar la experiencia de usuario en tu sitio web.

Para integrar un botón, simplemente incluye el código HTML correspondiente y aplica los estilos CSS proporcionados.

### Ejemplo de Uso:

```html
<button class="btn primary">Botón Primario</button>
<button class="btn secondary">Botón Secundario</button>
<button class="btn danger">Botón de Peligro</button>
<button class="btn success">Botón de Éxito</button>
```

---

## Slides

Los slides son útiles para presentar contenido de manera dinámica y atractiva. Este utilitario te permite implementar un slider básico para mostrar imágenes o contenido relevante de forma interactiva.

Puedes agregar el slider incluyendo el código HTML necesario y ajustando los estilos CSS según tus preferencias.

### Ejemplo de Uso:

```html
<div class="slider">
  <div class="slide">Contenido del Slide 1</div>
  <div class="slide">Contenido del Slide 2</div>
  <div class="slide">Contenido del Slide 3</div>
</div>
```

---

## Tabs

Los tabs son una excelente manera de organizar contenido en diferentes secciones, permitiendo a los usuarios navegar fácilmente entre ellas. Este utilitario te ofrece una implementación sencilla de tabs que puedes personalizar según tus necesidades.

Simplemente agrega el código HTML para definir las pestañas y su contenido asociado, y utiliza los estilos CSS proporcionados para darles el aspecto deseado.

### Ejemplo de Uso:

```html
<div class="tabs">
  <button class="tablink" onclick="openTab(event, 'Tab1')">Tab 1</button>
  <button class="tablink" onclick="openTab(event, 'Tab2')">Tab 2</button>
  <button class="tablink" onclick="openTab(event, 'Tab3')">Tab 3</button>

  <div id="Tab1" class="tabcontent">
    Contenido del Tab 1
  </div>
  <div id="Tab2" class="tabcontent">
    Contenido del Tab 2
  </div>
  <div id="Tab3" class="tabcontent">
    Contenido del Tab 3
  </div>
</div>
```

---

## Acordeones

Los acordeones son una forma eficaz de mostrar y ocultar contenido de manera organizada. Este utilitario te permite implementar acordeones fácilmente en tu sitio web para mostrar información de forma estructurada y accesible.

Para utilizar un acordeón, simplemente agrega el código HTML correspondiente y personaliza los estilos CSS según tus preferencias.

### Ejemplo de Uso:

```html
<div class="accordion">
  <div class="accordion-item">
    <button class="accordion-header" onclick="toggleAccordion(event)">Acordeón 1</button>
    <div class="accordion-content">
      Contenido del Acordeón 1
    </div>
  </div>
  <div class="accordion-item">
    <button class="accordion-header" onclick="toggleAccordion(event)">Acordeón 2</button>
    <div class="accordion-content">
      Contenido del Acordeón 2
    </div>
  </div>
  <div class="accordion-item">
    <button class="accordion-header" onclick="toggleAccordion(event)">Acordeón 3</button>
    <div class="accordion-content">
      Contenido del Acordeón 3
    </div>
  </div>
</div>
```

---

¡Siéntete libre de utilizar y personalizar estos utilitarios en tus proyectos web! Espero que te sean útiles. Si tienes alguna pregunta o sugerencia, no dudes en abrir un problema o enviar una solicitud de extracción. ¡Gracias por tu interés! 🚀

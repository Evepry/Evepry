# Ejemplo de Incorporación de HTML en Markdown

Este es un ejemplo de cómo puedes agregar HTML en un documento Markdown.

<div id="content">
  <!-- Contenido en Markdown -->
  <textarea id="markdown-content" readonly>

# Hola Mundo

Este es un ejemplo de contenido en Markdown.

- Lista 1
- Lista 2
  </textarea>
</div>

<button onclick="cambiarIdioma()">Cambiar Idioma</button>

<script>
  function cambiarIdioma() {
    // Simplemente como ejemplo, cambiamos el idioma al inglés
    document.documentElement.lang = "en";
    
    // Actualiza el contenido del área de Markdown
    document.getElementById("markdown-content").value = `
# Hello World

This is an example of Markdown content.

- List 1
- List 2
    `;
    // Podrías hacer más acciones aquí para cambiar dinámicamente el contenido
  }
</script>

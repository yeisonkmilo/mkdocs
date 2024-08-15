# DISEÑAR E IMPLEMENTAR ACCESIBILIDAD PARA PERSONAS CON DISCAPACIDADES

------

## Diagrama de Actividades
[Creado con plantuml](https://plantuml.com/es/)

![Image title](./assets/images/macp-17.png){ align=center }

Este diagrama de actividad muestra el proceso de asegurar la accesibilidad web para usuarios con discapacidad visual. Incluye la identificación de elementos clave, la verificación y ajuste de etiquetas ARIA, pruebas con lectores de pantalla, ajustes en contraste y navegación por teclado, y la documentación de resultados para mejoras continuas.
---
###

## Caso de uso historia Interfaz y Experinecia del Usuario
Tenemos la responsabilidad de que La página debe verse bien en cualquier dispositivo de usuarios, parte de eso al momento de ingresar de cargar rápido, y que cada botón sea fácil de encontrar para la comodidad de pepito, es importante dado que pepito es un hombre de mediana edad y debe tener botones de ayuda al usuario por que a la gente mayor se les dificulta las compras en línea,  y como todos cometemos errores, la página va a tener acciones inmediatas y con notificación cuando tenemos una acción inadecuada.

<table id="customers">
  <tr class="idtext principal">
    <td>ID MACP-17</td>
  </tr>
  <tr class="single text">
    <td><strong>Requerimiento</strong>:Implementar accesibilidad para personas con discapacidades ID MACP-17</td>
  </tr>
  <tr class="single gray">
    <td><strong>Historia de usuario</strong></td>
  </tr>
  <tr class="single text">
    <td>Como usuario con discapacidad visual, quiero poder navegar por el sitio web utilizando un lector de pantalla para acceder a toda la información y funcionalidades de la misma.</td>
  </tr>
  <tr class="duo">
    <th class="gray"><strong>Estado de la tarea</strong></th>
    <th>En desarrollo</th>
  </tr>
  <tr class="single gray">
    <td><strong>Caso de uso (Pasos)</strong></td>
  </tr>
  <tr class="single text">
    <td>
        <ol>
            <li>
             <li>El usuario abre el navegador web y accede al sitio web.</li>
             <li>El usuario activa el lector de pantalla.</li>
             <li>El lector de pantalla lee el contenido del sitio web, incluyendo texto, encabezados, imágenes (con texto alternativo), enlaces y formularios.</li>
            <li>El usuario navega por el sitio web utilizando comandos del lector de pantalla para acceder a diferentes secciones y funcionalidades.</li>
            <li>El usuario interactúa con elementos del sitio web como formularios, botones y enlaces, y el lector de pantalla proporciona la información necesaria para completar estas interacciones.</li>
        </ol>
    </td>
  </tr>
  <tr class="single gray">
    <td><strong>Criterios de aceptación</strong></td>
  </tr>
  <tr class="single text">
    <td>
        <ol>
                  <li>Texto Alternativo en Imágenes: Todas las imágenes en el sitio web tienen texto alternativo descriptivo que puede ser leído por el lector de pantalla.</li>
                  <li>Estructura de la Página: El sitio web utiliza correctamente las etiquetas de encabezado para estructurar la información de manera jerárquica y lógica. El lector de pantalla puede identificar y leer los encabezados correctamente para ayudar a la navegación.</li>
                  <li>Navegación por Teclado: Todos los elementos interactivos (enlaces, botones, formularios, etc.) son accesibles mediante navegación por teclado. Los usuarios pueden acceder a todos los elementos y funcionalidades utilizando el teclado sin depender del ratón.</li>
                  <li>Formulario Accesible: Todos los campos de formulario tienen etiquetas adecuadas y asociadas correctamente con los controles de formulario. Los mensajes de error y las instrucciones se presentan de manera clara y son leídos por el lector de pantalla.</li>
                  <li>Contraste de Color: El contraste entre el texto y el fondo cumple con los requisitos de contraste especificados en las pautas WCAG para asegurar que el contenido sea legible para todos los usuarios.</li>
                  <li>Enlaces y Botones: Los enlaces y botones tienen descripciones claras y concisas que proporcionan información sobre su propósito y acción esperada. Las descripciones de enlaces y botones son leídas correctamente por el lector de pantalla.</li>
                  <li>Pruebas de Usuario: Se han realizado pruebas de usuario con personas con discapacidad visual para validar que la implementación cumple con sus necesidades y expectativas.</li>
                  <li>Documentación y Recursos:Se ha proporcionado documentación y recursos adicionales sobre cómo usar el sitio web con tecnologías asistivas para usuarios finales y desarrolladores.</li>
 <tr class="duo">
    <th class="gray"><strong>Calidad</strong></th>
    <th>En desarrollo</th>
  </tr>
  <tr class="duo">
    <th class="gray"><strong>Versionamiento</strong></th>
    <th>En desarrollo</th>
  </tr>
</table>



---
## Diagrama de Caso de uso
[Creado con plantuml](https://plantuml.com/es/)

![Image title](./assets/images/DIAGRAMAS%20DE%20CASO%20DE%20USO/CASO17.png){ align=center }

Este diagrama de casos de uso muestra cómo un "Usuario con Discapacidad Visual" interactúa con un sitio web accesible. Incluye la capacidad de navegar usando un lector de pantalla, acceder a toda la información del sitio y utilizar todas las funcionalidades disponibles, garantizando una experiencia inclusiva y completa.
 
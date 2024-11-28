# IMPLEMENTAR COMENTARIOS DE CLINETES EN PAGINA DE INICIO 

------
## Diagrama de Actividades
[Creado con plantuml](https://plantuml.com/es/)

![Image title](./assets/images/macp10.png){ align=center }

El diagrama de actividad describe el proceso de implementar una barra de búsqueda en una página de inicio. Incluye los pasos para mostrar la barra, recibir y validar términos de búsqueda, mostrar resultados o mensajes de error, y permitir nuevas búsquedas. Gestiona el flujo de interacción entre el usuario y el sistema.
---
###

## Caso de uso historia Crear paginas de Inicio 
El usuario que quiere comprar muebles puede entrar a un menú principal o una página de inicio , el cual tiene enlaces a otras  páginas principales como inicio, catálogos, contactos entre otros más. Dentro de la misma página cuando el usuario pase el ratón sobre las opciones del menú principal se desplegará los submenús con más opciones; la página le proporcionará enlaces rápidos para iniciar sesión o registrarse; si la persona quiere entrar a la página desde su móvil, lo podrá hacer con toda comodidad ya que el menú es responsivo para móviles. También si el usuario quiere consultar las redes sociales lo podrá hacer ya que el menú de inicio tiene enlaces  a las mismas, y no menos importante la capacidad de ver todos los productos recomendados o más vendidos de la página.

<table id="customers">
  <tr class="idtext principal">
    <td>ID MACP-11</td>
  </tr>
  <tr class="single text">
    <td><strong>Requerimiento</strong>: Implementar comentarios de clientes en la página de inicio ID MACP-11</td>
  </tr>
  <tr class="single gray">
    <td><strong>Historia de usuario</strong></td>
  </tr>
  <tr class="single text">
    <td>Como usuario, quiero ver comentarios de otros clientes en la página de inicio para tomar decisiones informadas sobre los productos o servicios ofrecidos..</td>
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
            <li>El usuario accede a la página de inicio.</li>
            <li>El sistema recupera los comentarios de clientes desde la base de datos.</li>
           <li>El sistema muestra una sección de comentarios de clientes en un lugar visible de la página de inicio.</li>
          <li>Cada comentario incluye el nombre del cliente, la calificación, y el texto del comentario.</li>
         <li>El sistema puede mostrar una cantidad fija de comentarios, con la opción de ver más si hay más comentarios disponibles.</li>
        </ol>
    </td>
  </tr>
  <tr class="single gray">
    <td><strong>Criterios de aceptación</strong></td>
  </tr>
  <tr class="single text">
    <td>
        <ol>
                  <li>Visibilidad: La sección de comentarios debe estar ubicada en un lugar prominente en la página de inicio para asegurar que los usuarios puedan verla fácilmente.</li>
                  <li>Formato: Cada comentario debe mostrar al menos el nombre del, el texto del comentario, y, si aplica, una calificación en estrellas o similar. El formato de los comentarios debe ser claro y legible, con una tipografía adecuada y suficiente espaciado entre comentarios.</li>
                  <li>Cantidad de Comentarios: a página de inicio debe mostrar una cantidad predeterminada de comentarios con una opción para cargar más si hay más comentarios disponibles.</li>
                  <li>Interactividad: Si se muestran más comentarios al hacer clic en "Ver más", el sistema debe cargar y mostrar los comentarios adicionales sin necesidad de recargar toda la página.</li>
                  <li>Datos de Comentarios: Los comentarios deben provenir de una fuente confiable y estar actualizados. Si hay una base de datos de comentarios, debe ser consultada en tiempo real o actualizada periódicamente.</li>
                   <li>Rendimiento: La carga de la sección de comentarios no debe afectar negativamente el tiempo de carga de la página de inicio. La implementación debe garantizar que la página siga siendo rápida y eficiente.</li>
                  <li>Accesibilidad: La sección de comentarios debe ser accesible para usuarios con discapacidades, incluyendo la compatibilidad con lectores de pantalla y la navegación mediante teclado.</li>
                  <li>Seguridad y Privacidad: Los comentarios deben ser moderados para evitar la publicación de contenido inapropiado o spam. Deben cumplirse las normativas de privacidad y protección de datos.</li>
    </td>
  </tr>
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

![Image title](./assets/images/DIAGRAMAS%20DE%20CASO%20DE%20USO/CASO11.png){ align=center }

Este diagrama de casos de uso muestra cómo tanto los invitados como los clientes pueden acceder a la funcionalidad "Ver Comentarios de Clientes" en la página de inicio del sitio web. Los invitados tienen acceso para ver comentarios, al igual que los clientes registrados.
---
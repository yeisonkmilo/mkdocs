# GESTION DE PRODUCCIÓN

------

## Diagrama de Actividades
[Creado con plantuml](https://plantuml.com/es/)

![Image title](./assets/images/macp-17.png){ align=center }

Este diagrama de actividad muestra el proceso de asegurar la accesibilidad web para usuarios con discapacidad visual. Incluye la identificación de elementos clave, la verificación y ajuste de etiquetas ARIA, pruebas con lectores de pantalla, ajustes en contraste y navegación por teclado, y la documentación de resultados para mejoras continuas.
---
###

## Caso de uso historia 
Carlos, encargado de producción, recibe una actualización en los detalles de un pedido antes de que inicie la producción. Accede al sistema de gestión de producción y selecciona la opción para modificar la orden pendiente. Carlos actualiza los detalles necesarios, como las cantidades, los recursos o los tiempos de producción, asegurándose de que todo esté correcto antes de comenzar. El sistema guarda los cambios y actualiza la orden, garantizando que los recursos y procesos estén alineados para una producción precisa y eficiente.

  <tr class="idtext principal">
    <td>ID SYN-24</td>
  </tr>
  <tr class="single text">
    <td><strong>Requerimiento</strong>:Modificar órdenes de producción pendientes. ID SYN-24</td>
  </tr>
  <tr class="single gray">
    <td><strong>Historia de usuario</strong></td>
  </tr>
  <tr class="single text">
    <td>Como encargado de producción quiero modificar las órdenes de producción pendientes para actualizar detalles antes de que inicien, asegurando la precisión de los recursos y procesos.
</td>
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
             <li>El encargado accede al módulo "Gestión de Órdenes de Producción".</li>
              <li>Busca la orden de producción en estado pendiente que desea modificar.</li>
              <li>Selecciona la orden y edita los detalles requeridos, como: Productos a fabricar, Cantidades, Fechas estimadas de inicio y fin, Recursos asignados.</li>
              <li>Revisa los cambios realizados y los confirma.</li>
              <li>El sistema actualiza la información de la orden y genera un registro de las modificaciones.</li>
        </ol>
    </td>
  </tr>
  <tr class="single gray">
    <td><strong>Criterios de aceptación</strong></td>
  </tr>
  <tr class="single text">
    <td>
        <ol>
              <li>El sistema debe permitir modificar solo órdenes en estado pendiente.</li>
              <li>Los campos editables deben incluir: Producto o productos a fabricar, Cantidades, Fechas estimadas de inicio y fin, Recursos asignados.</li>
              <li>Los cambios deben ser confirmados por el usuario antes de ser aplicados.</li>
              <li>Cada modificación debe registrarse en un historial, indicando: Usuario que realizó el cambio,Detalles antes y después de la modificación, Fecha y hora de la modificación.</li>
              <li>El sistema debe generar notificaciones automáticas para los responsables de los recursos afectados por los cambios (si aplica).</li>
            </ol>
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
 
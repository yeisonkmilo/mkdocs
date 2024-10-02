# Administración del Sitio MACP-79

------
## Diagrama de Actividades
[Creado con plantuml](https://plantuml.com/es/)

![Image title](./assets/images/DiagramaActividades/MACP-81.png){ align=Center }

"El sistema de gestión de inventarios permite registrar, rastrear y administrar el stock de productos en un almacén. Este diagrama de actividad describe el flujo de trabajo para registrar nuevos productos, actualizar existencias, rastrear niveles de stock y eliminar productos, optimizando la disponibilidad y los costos de inventario."
---

## Escenario MACP-79
Queremos un backend intuitivo para la gestión del sitio, con diferentes niveles de acceso para diferentes tipos de usuarios (admin, editor, etc.) y la capacidad para ofrecer el contenido del sitio en varios idiomas y  copias de seguridad automáticas de la información del sitio. Ejemplo: Backups diarios automatizados. Luego y como para terminar una medidas de seguridad para proteger la información del usuario y del sitio.

<table id="customers">
  <tr class="idtext principal">
    <td>ID MACP-81</td>
  </tr>
  <tr class="single text">
    <td><strong>Requerimiento</strong>: crear gestión de inventarios ID MACP-81</td>
  </tr>
  <tr class="single gray">
    <td><strong>Historia de usuario</strong></td>
  </tr>
  <tr class="single text">
    <td>Como gerente de inventario, quiero un sistema de gestión de inventarios que me permita registrar, rastrear y administrar de manera eficiente el stock de productos en mi almacén, para garantizar la disponibilidad de los productos para los clientes y optimizar los costos de inventario</td>
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
         </ol>
      <li>El gerente accede a la funcionalidad de añadir producto</li>
      <li>Introduce la información del producto (nombre, código, descripción, etc.)</li>
      <li>Guarda la información</li>
      <li>El sistema confirma la adición del producto</li>
        <ol>
    </td>
  </tr>
  <tr class="single gray">
    <td><strong>Criterios de aceptación</strong></td>
  </tr>
  <tr class="single text">
    <td>
        <ol>
Registro de Productos:<td>
<li>El sistema debe permitir ingresar nuevos productos con campos como nombre, código de producto, descripción, categoría, precio, cantidad inicial y ubicación en el almacén.
<li>Debe ser posible cargar información de productos desde archivos CSV o Excel.
<td>
Actualización de Inventario:<td>
<li>El sistema debe permitir la actualización de las cantidades en inventario mediante entradas de stock (recepciones de mercancía) y salidas (ventas, devoluciones, etc.).
<li>Los cambios en el inventario deben reflejarse en tiempo real.
<td>
Consulta y Rastreo de Productos:<td>
<li>El sistema debe ofrecer funcionalidades de búsqueda y filtrado por nombre, código, categoría, ubicación y otras características.
<li>Debe permitir ver el historial de movimientos para cada producto.
<td>
Alertas y Notificaciones:<td>
<li>Debe generar alertas cuando el stock de un producto esté por debajo del umbral mínimo establecido.
<li>El sistema debe enviar notificaciones sobre niveles críticos de inventario y otros eventos relevantes.
<td>
Informes y Análisis<td>
<li>Debe proporcionar informes sobre el estado del inventario, movimientos de productos, rotación de stock y análisis de costos.
<li>Los informes deben poder exportarse en formatos como PDF, Excel, o CSV.
<td>
Control de Acceso:<td>
<li>El sistema debe permitir definir roles y permisos para usuarios (por ejemplo, gerente, empleado de almacén).
<li>Las acciones deben registrarse con un historial de auditoría para seguridad y trazabilidad.
<td>
Interfaz de Usuario<TD>
<li>La interfaz debe ser intuitiva y fácil de usar para los usuarios finales.
<li>Debe ser accesible desde diferentes dispositivos (ordenadores, tabletas) y ser compatible con los navegadores web más comunes.
<td>
Integración<td>
<li>El sistema debe poder integrarse con otros sistemas empresariales existentes, como sistemas de ventas, contabilidad y gestión de pedidos.
        </ol>
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

![Image title](./assets/images/CasosDeUso/MACP-81.png){ align=center }

"El sistema de gestión de inventarios permite a los gerentes registrar, rastrear y administrar el stock de productos de manera eficiente. Facilita la disponibilidad continua de productos para los clientes y optimiza los costos de inventario, asegurando una operación fluida y una toma de decisiones informada."
---

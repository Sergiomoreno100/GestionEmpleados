# GestionEmpleados

Uso de Html.DisplayNameFor y Html.DisplayFor: Se justifica el uso de estas funciones para generar automáticamente etiquetas y valores, lo que mejora la mantenibilidad.
Estructura de la tabla y navegación: Se ha optado por table-responsive, table-striped y table-hover para mejorar la experiencia de usuario en distintas resoluciones.
Enlaces para CRUD: Se maneja la edición, visualización y eliminación con enlaces que usan asp-page y asp-route-id, siguiendo la convención de Razor Pages.
Se sigue el patrón de PageModel en Razor Pages (IndexModel en este caso) para separar la lógica de la presentación.
Se usa Html.DisplayNameFor para los encabezados de la tabla.
Se emplea Html.DisplayFor para mostrar los datos de los empleados. Esta técnica permite que los nombres de los campos se reflejen automáticamente desde el modelo sin necesidad de escribirlos manualmente. 

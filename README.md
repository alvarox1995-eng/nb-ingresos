# NB · Ingresos a tiendas

Interfaz pública para consultar ingresos de calzado New Balance por sucursal y cita de llegada.

## Publicar

En Settings → Pages, elegir Deploy from a branch → main → / (root) → Save.

## Uso

- Filtrar por sucursal y cita de llegada.
- Las fechas de hoy y futuras se marcan en verde (hora de Perú).
- Modelos ordenados por cantidad descendente.
- Calendario actualizado: Cuzco tiene un plazo de 7 días.
- Cargar Excel y fotos desde los botones superiores con la clave de publicación existente.
- Los archivos JPG se relacionan por el modelo en su nombre.

## Almacenamiento

GitHub Pages sirve la interfaz. El reporte y las fotos se conservan en el servicio compartido existente. No se guardan claves, datos del Excel ni credenciales de GitHub en este repositorio. La clave de publicación se introduce en el navegador y se envía por HTTPS al servicio para autorizar las actualizaciones.

Si se usaba un enlace de administración anterior, su clave sigue siendo válida. El acceso de administración también admite el fragmento #admin=CLAVE en la URL, que se retira de la barra y se mantiene solo durante la sesión.

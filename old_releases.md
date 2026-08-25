![](assets/images/toyota_logo_200px.png) ![](assets/images/coyota_200px.png)

---

## Histórico de Versiones de Coyota

### v1.0.0.260725
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Se han añadido a los viajes, los **Comportamientos a la Conducción** del conductor en un trayecto concreto. Dentro del detalle de un viaje, se indica si hay comportamientos a la conducción o no, y cuántos. Y dentro del mapa, se podrá visualizar estos comportamientos y saber cuándo ocurrieron.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Se han añadido a los viajes, la posibilidad de mostrar parte de la ruta en **EV** y en **Combustión** de acuerdo a los datos devueltos por Toyota en cada punto registrado de la ruta.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Al pulsar el botón **Cerrar sesión**, el usuario debe confirmar si realmente quiere cerrar la sesión, para evitar que se haga accidentalmente.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Dentro de la sección **Mantenimientos**, y concretamente en el apartado *Historial de Servicio*, aparece ahora una lista desplegable de *Categorías* para que el usuario filtre los datos por todas las categorías (valor por defecto) o por una categoría concreta.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Ahora, cuando el usuario sitúa el puntero del ratón sobre el *VIN* que aparece a la derecha de la ventana en la barra superior de opciones, aparece la imagen del coche y la matrícula para identificar el vehículo activo.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Los botones de *sincronización* de **Mis Vehiculos** y **Viajes** han sido sustituidos por el botón **Sincronizar** de la barra de opciones.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Cuando el usuario accede sobre la sección **Mantenimientos** por primera vez, y el usuario no ha creado aún ningún taller, todos los talleres diferentes que aparezcan en el *Historial de Servicio*, se generarán automáticamente de forma básica.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Cuando el usuario accede sobre la sección **Mantenimientos** por primera vez, la aplicación generará una serie de valores por defecto para *Tipos*, *Tareas* y *Acciones*.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Se ha creado una nueva sección llamada <srtong>Configuración</srtong>.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Dentro de **Configuración** se podrá indicar la ruta en la que queremos que esté la base de datosde la aplicación.
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Dentro de **Configuración** se podrá ejecutar una *Sincronización Completa* nuevamente, para que la aplicación actualice y descargue los viajes nuevamente.
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Las ventanas emergentes de la aplicación se pueden cerrar ahora no sólo con el botón *Cerrar*, sino también haciendo clic fuera de su área.
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Dentro de la sección **Mis Vehículos**, aparece el listado de vehículos asociados a la cuenta de usuario. Cuando un vehículo está seleccionado, el puntero del ratón es el estándar, y cuando uno de los vehículos del listado no está seleccionado, el puntero cambia para que el usuario sepa también que no está activo o seleccionado.
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) En la sección **Información**, *Etiqueta* se muestra ahora como *Etiqueta Medioambiental*.
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Si los litros consumidos en una distancia eran 0 litros porque sólo se ha circulado en eléctrico, ese dato no aparecía. Ahora aparece aunque su valor sea 0 litros.
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Dentro de la sección **Mantenimientos**, todos los registros de *Talleres*, *Tipos*, *Tareas* y *Addiones*, aparecen ahora ordenados albabéticamente.
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Mejoras visuales en la selección de un viaje de su listado, y de un viaje seleccionado.
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Mejoras visuales en las pantallas de *Tipos*, *Tareas* y *Acciones*.
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) La aplicación ahora, aparece maximizada por defecto.
- ![](https://img.shields.io/badge/Issue-fcd34d?style=for-the-badge) A la hora de crear un **Nuevo repostaje** o editar uno existente, el *Tipo de Combustible* aparece ahora ordenado alfabéticamente.
- ![](https://img.shields.io/badge/Bug-cc5a5a?style=for-the-badge) Arreglado un `bug` por el cuál cuando se editaba un repostaje existente, el título era erróneamente **Nuevo repostaje** en lugar de **Editar repostaje**.

### v.0.7.1 - Julio 2026
- ![](https://img.shields.io/badge/General-c8ccc4?style=for-the-badge) *Publicada una versión de prueba para usuarios Linux para comprobar el correcto funcionamiento de la aplicación.*
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Añadido soporte para crear el paquete de instalación para **Linux (Ubuntu/Debian)**.

### v.0.7.0 - Julio 2026
- ![](https://img.shields.io/badge/General-c8ccc4?style=for-the-badge) *Publicada una versión de prueba para usuarios acotados/testers para comprobar el correcto funcionamiento de la aplicación.*
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) _Coyota Vehicle Manager_ se llama ahora **Coyota**.

### v.0.6.1 - Julio 2026
- ![](https://img.shields.io/badge/General-c8ccc4?style=for-the-badge) Pruebas realizadas sobre **Windows 11**, **macOS Catalina Intel**, y **macOS Tahoe ARM (Apple Silicon) M2** para confirma el correcto funcionamiento de las funcionalidades, y la presentación
- ![](https://img.shields.io/badge/General-c8ccc4?style=for-the-badge) En **macOS ARM (Apple Silicon)** requiere pequeños ajustes en _CSS_, en concreto en la imagen del vehículo en la sección **Mis Vehículos** que distorsionaba la imagen. Después del cambio, esta ventana se presenta correctamente en **Windows 11** y en **macOS ARM (Apple Silicon)**
- ![](https://img.shields.io/badge/General-c8ccc4?style=for-the-badge) En **macOS Catalina**, **WKWebView** es muy antiguo y obsoleto, y afecta en la presentación _CSS_. El coste de implementar personalizaciones sobre _Intel_ requiere reescribir y personalizar gran parte de la aplicación. Por esta razón, se descarta la distribución de **Coyota** en **macOS Intel**

### v.0.6.0 - Julio 2026
- ![](https://img.shields.io/badge/General-c8ccc4?style=for-the-badge) **`Finalización de la versión Beta tras comprobar su estabilización`**
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregada en la sección **Dashboard**, la dirección de última ubicación
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregada en la sección **Dashboard**, la posibilidad de comparar el rendimiento, aceleración y frenada en las agrupaciones mensuales
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregada en la sección **Viajes**, la posibilidad de buscar _viajes en el último mes_
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregada en la sección **Viajes**, la *Velocidad media* dentro de la lista de *viajes*
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregado en la sección **Viajes**, el origen y destino automático a partir la longitud y latitud de ellos, tanto en el listado de *viajes* como en el detalle de un viaje seleccionado
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregados tooltips en cada elemento del listado de **Viajes**
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Añadida alerta al usuario cuando el mantenimiento esté próximo
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Mejoras en el filtrado de datos del **Dashboard** para hacerlo más adecuado al diseño de la aplicación
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Siguiendo la coherencia del resto de funcionalidades dentro de la aplicación, **Estadísticas** está ahora en **Viajes** en lugar de en **Repostajes**

### v.0.5.0 - Julio 2026
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Añadido el **apartado de luces** en las alertas del vehículo
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregada la gestión de tags múltiples, búsqueda por tags y por texto dentro de los viajes
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Cambio y unificación de algunos iconos en todas las ventanas de la aplicación
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Mejoras de diseño en la sección **Información**, y concretamente en **Personalización**
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Rediseño de la sección **Mantenimientos** para unificar criterios
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Rediseño de la sección **Operaciones** de acuerdo a los cambios de la API de Toyota
- ![](https://img.shields.io/badge/Bug-cc5a5a?style=for-the-badge) Actualización de algunas llamadas de la **API de Toyota**, que ha cambiado sin previo aviso e impactaba a la aplicación, dejándola de funcionar en algunas de sus secciones
- ![](https://img.shields.io/badge/Bug-cc5a5a?style=for-the-badge) Resuelto un bug en **Repostajes**. Cuando se editaba un repostaje, la fecha y hora cambiaba a UTC

### v.0.4.0 - Junio 2026
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregada la sección de **Mantenimiento** y gestión de operaciones en taller con el coche
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Creación de la sección **Información**
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Rediseño de la pantalla principal (**Mis Vehículos**)
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Recolocación del **Dashboard** en la aplicación
- ![](https://img.shields.io/badge/Bug-cc5a5a?style=for-the-badge) Resolución de un bug que implicaba que la aplicación no refrescara automáticamente el token de usuario, cuando estando la aplicación abierta, el token caducaba

### v.0.3.0 - Mayo 2026
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregado en la sección **Repostajes** el apartado de **Estadísticas**
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Consolidación final de los bloques principales de la aplicación
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Dentro de la sección **Repostajes**, mejoras en la gráfica de **Precios de la gasolina**
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Estabilización y pequeños reajustes de iconos y de UX
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Mejoras en **Viajes**. Agregado color de fondo y de letra para las **Categorías** de los viajes
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Unificación de **Notificaciones** dentro del **Dashboard**

### v.0.2.0 - Abril 2026
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregada la posibilidad de categorizar los viajes
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Agregada **Velocidad Constante** en los **Viajes** y **Dashboard**
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Ahora se tendrá que crear una gasolinera antes de agregar un consumo, para que cuando el usuario quiera agregar un consumo, tenga que seleccionar una gasolinera existente obligatoriamente
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) En la pantalla inicial, aparecen ahora además de los km del vehículo, los km y % de combustible restante también
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Mejoras para la estabilización de la aplicación
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) Reaplicación de colores para valores por debajo del valor óptimo en **Aceleración**, **Frenada** y **Velocidad constante**

### v.0.1.0 - Marzo 2026
- ![](https://img.shields.io/badge/General-c8ccc4?style=for-the-badge) Primera versión funcional Beta de **Coyota Vehicle Manager**
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Autenticación con cuenta **My Toyota** (_OAuth/ForgeRock de varios pasos_) [autenticación → autorización → obtención del token de usuario]
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Creada la sección **Dashboard** con estado del vehículo, ubicación y rendimiento mensual
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Gestión de repostajes con mapa de ubicaciones
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Información del vehículo: matrícula, etiqueta medioambiental, aseguradora
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Listado y sincronización de viajes con mapas de ruta
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) _Splash screen_ con logo personalizado

### v.0.0.1 - Febrero 2026
- ![](https://img.shields.io/badge/General-c8ccc4?style=for-the-badge) Primera versión _alpha_ de **Coyota Vehicle Manager**
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Creación de estructura general y secciones
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Conexiones a la **API de Toyota**
- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) Gestión de **Login y Token**

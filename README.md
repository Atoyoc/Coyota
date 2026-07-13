![](assets/images/toyota_logo_200px.png) ![](assets/images/coyota_200px.png)

[![](https://img.shields.io/badge/Coyota%20Vehicle%20Manager%20v0.6.1-cc5a5a?style=for-the-badge)](https://github.com/Atoyoc/Coyota_Vehicle_Manager/releases/tag/v0.6.1)
---

> [!IMPORTANT]
> **Aviso importante**
> `Aviso legal y exención de reponsabilidad`:
> 
> **Coyota Vehicle Manager** (aka **Coyota**) es una aplicación no oficial e independiente, sin ninguna afiliación, patrocinio, ni respaldo de Toyota Motor Corporation ni de ninguna de sus filiales.
> 
> El uso de Coyota implica la aceptación de que el autor no se hace responsable de ningún daño directo o indirecto, pérdida de datos, mal funcionamiento del vehículo, ni de cualquier otra consecuencia derivada del uso o mal uso de la misma.
> 
> El desarrollador de Coyota, queda exento de cualquier problema directo o indirecto derivado de su uso. La ejecución y uso de la aplicación, se realiza bajo la entera comprensión de los riestos -si los hubiera-, y la asunción de los mismos por parte del usuario.
> 
> Los datos del vehículo mostrados en Coyota, se obtienen directamente desde los servidores de Toyota mediante las credenciales personales que el usuario introduce, las cuales se almacenan de forma segura en el Keychain del sistema operativo.
> 
> Los datos que el usuario introduce, credenciales y cualquier otro que Coyota pudiera usar o gestionar, nunca se transmiten a terceros ni se usan para fines estadísticos, publicitarios o de cualquier otra índole. Toda la información recogida, por la aplicación, permanece almacenada localmente en el ordenador del usuario, y éste (el usuario) es el responsable de salvaguardar y gestionar dicha información de forma segura.
> 
> Coyota utiliza una API de la propia Toyota (`Toyota EU MyToyota ctpa-oneapi API`), y ésta queda fuera del alcance del desarrollador, por lo que en el caso de que ésta cambiara o Toyota dejara de dar el servicio, podría hacer que Coyota dejara de funcionar.
> 
> Al usar Coyota, el usuario de la misma admite que el autor de la aplicación, no posee obligación de ningún tipo de mejorar, actualizar, modificar o mantener Coyota a lo largo del tiempo, y no se le puede exigir responsabilidad alguna por su uso, matenimiento, soporte, pérdida de datos o cualquier otra circunstancia que ocasionara un perjuicio para el usuario.


## ¿Qué es Coyota Vehicle Manager?
> [!TIP]
> Es una aplicación multiplataforma para `Windows` y `macOS` (procesadores Apple Silicon únicamente), que permite gestionar tus vehículos Toyota y Lexus, `en español`, y **pensada inicialmente para el mercado Europeo de España**.
>
> Coyota no usa ningún paquete de terceros ni intermediarios de ningún tipo para conectarse a la API de Toyota ni gestionar su conectividad. Todo en Coyota está desarrollado desde cero con conexiones directas con Toyota.

> [!NOTE]
> Inicialmente el proyecto nació para dar soporte para `macOS Intel` también, pero la incompatibilidad de algunas funcionalidades a la hora de presentarlas en pantalla, hacía inviable esta vía, por lo que en la v0.6.1 se ha eliminado esa posibilidad y sólo está disponible para **Windows** y **macOS Apple Silicon**.

La aplicación tiene diferentes secciones:
  |Sección|Descripción|
  |--|--|
  |**`Mis Vehículos`**|Listado de los vehículos asociados a tu cuenta de usuario Toyota, y selección del vehículo con el que operar (**por defecto se selecciona el primer vehículo**)|
  |**`Información`**|Información general sobre un vehículo (**VIN, Código Katashiki, Contrato, etc**), y de los datos que Toyota tiene del usuario (**Nombre, Email, Teléfono, etc**)|
  |**`Operaciones`**|Operaciones remotas a realizar sobre el vehículo (**actualmente deshabilitadas hasta poder confirmar su correcta operatibilidad**)|
  |**`Dashboard`**|Muestra el rendimiento mensual y general realizado con el vehículo, la última ubicación conocida del vehículo, y el estado del mismo según los datos devueltos por Toyota|
  |**`Viajes`**|Listado de viajes, sincronización de los mismos, y estadísticas (**si hay datos de repostajes añadidos**)|
  |**`Repostajes`**|Gestión de repostajes, pudiendo agregar gasolineras, registro del repostaje, y visualización de evolución de precios|
  |**`Mantenimientos`**|Historial de servicio de tu vehículo Toyota, de todas las revisiones, de cuando toca realizar el siguiente mantenimiento, posibles problemas detectados, y gestión de entradas al taller para hacer un seguimiento de los costes, tareas, etc|


## `Notas de Releases`

### v.0.6.1 - Julio 2026
- Pruebas realizadas sobre **Windows 11**, **macOS Catalina Intel**, y **macOS Tahoe ARM (Apple Silicon) M2** para confirma el correcto funcionamiento de las funcionalidades, y la presentación
- En **macOS Catalina**, **WKWebView** es muy antiguo y obsoleto, y afecta en la presentación _CSS_. El coste de implementar personalizaciones sobre _Intel_ requiere reescribir y personalizar gran parte de la aplicación. Por esta razón, se descarta la distribución de **Coyota** en **macOS Intel**
- En **macOS ARM (Apple Silicon)** requiere pequeños ajustes en _CSS_, en concreto en la imagen del vehículo en la sección **Mis Vehículos** que distorsionaba la imagen. Después del cambio, esta ventana se presenta correctamente en **Windows 11** y en **macOS ARM (Apple Silicon)**

### v.0.6.0 - Julio 2026
- **`Finalización de la versión Beta tras comprobar su estabilización`**
- Siguiendo la coherencia del resto de funcionalidades dentro de la aplicación, **Estadísticas** está ahora en **Viajes** en lugar de en **Repostajes**
- Agregada la posibilidad de buscar _viajes en el último mes_
- Agregada el origen y destino automático a partir la longitud y latitud de elos, en el listado de **Viajes** y en el detalle de un viaje seleccionado
- Agregada la Velocidad media dentro de la lista de **Viajes**
- Agregados tooltips en cada elemento del listado de **Viajes**
- Agregada la dirección de última ubicación dentro del **Dashboard**
- Mejoras en el filtrado de datos del **Dashboard** para hacerlo más adecuado al diseño de la aplicación
- Agregada en la sección **Dashboard**, la posibilidad de comparar el rendimiento, aceleración y frenada en las agrupaciones mensuales
- Añadida alerta al usuario cuando el mantenimiento esté próximo

### v.0.5.0 - Julio 2026
- Actualización de algunas llamadas de la **API de Toyota**, que ha cambiado sin previo aviso e impactaba a la aplicación, dejándola de funcionar en algunas de sus secciones
- Rediseño de la sección de **Operaciones** de acuerdo a los cambios de la API de Toyota
- Rediseño de la sección **Mantenimientos** para unificar criterios
- Añadido el **apartado de luces** en las alertas del vehículo
- Agregada la gestión de tags múltiples, búsqueda por tags y por texto dentro de los viajes
- Mejoras de diseño en la sección **Información**, y concretamente en **Personalización**
- Cambio y unificación de algunos iconos en todas las ventanas de la aplicación
- Resuelto un bug en **Repostajes**. Cuando se editaba un repostaje, la fecha y hora cambiaba a UTC

### v.0.4.0 - Junio 2026
- Rediseño de la pantalla principal (**Mis Vehículos**)
- Agregada la sección de **Mantenimiento** y gestión de operaciones en taller con el coche
- Recolocación del **Dashboard** en la aplicación
- Creación de la sección **Información**
- Resolución de un bug que implicaba que la aplicación no refrescara automáticamente el token de usuario, cuando estando la aplicación abierta, el token caducaba

### v.0.3.0 - Mayo 2026
- Agregado en **Repostajes** el apartado de **Estadísticas**
- Dentro de **Repostajes**, mejoras en la gráfica de **Precios de la gasolina**
- Mejoras en **Viajes**. Agregado color de fondo y de letra para las **Categorías** de los viajes
- Unificación de **Notificaciones** dentro del **Dashboard**
- Estabilización y pequeños reajustes de iconos y de UX
- Consolidación final de los bloques principales de la aplicación

### v.0.2.0 - Abril 2026
- Mejoras para la estabilización de la aplicación
- Agregada **Velocidad Constante** en los **Viajes** y **Dashboard**
- Reaplicación de colores para valores por debajo del valor óptimo en **Aceleración**, **Frenada** y **Velocidad constante**
- En la pantalla inicial, aparecen ahora además de los km del vehículo, los km y % de combustible restante también
- Ahora se tendrá que crear una gasolinera antes de agregar un consumo, para que cuando el usuario quiera agregar un consumo, tenga que seleccionar una gasolinera existente obligatoriamente
- Agregada la posibilidad de categorizar los viajes

### v.0.1.0 - Marzo 2026
- Primera versión funcional Beta de **Coyota Vehicle Manager**
- Autenticación con cuenta **My Toyota** (_ForgeRock_)
- **Dashboard** con estado del vehículo, ubicación y rendimiento mensual
- Listado y sincronización de viajes con mapas de ruta
- Gestión de repostajes con mapa de ubicaciones
- Información del vehículo: matrícula, etiqueta medioambiental, aseguradora
- _Splash screen_ con logo personalizado

### v.0.0.1 - Febrero 2026
- Primera versión _alpha_ de **Coyota Vehicle Manager**
- Creación de estructura general y secciones
- Conexiones a la **API de Toyota**
- Gestión de **Login y Token**


## Enlaces que pueden ser de interés

### Aplicaciones móviles oficiales Toyota
- [Toyota - MyToyota App para Android](https://play.google.com/store/apps/details?id=com.toyota.oneapp.eu)
- [Toyota - Mytoyota App para iOS](https://apps.apple.com/es/app/mytoyota/id1617623127)

### Aplicaciones móviles de terceros
- [Spritmonitor - para Android](https://play.google.com/store/apps/details?id=de.spritmonitor.smapp_mp&hl=es)
- [Spritmonitor - para iOS](https://apps.apple.com/es/app/spritmonitor-consume-costos/id616137163)

### Documentación de Toyota
- [Toyota - TME Customer REST API Documentation (Europa)](https://consumer-api.toyota-europe.com/docs/?json#tme-customer-rest-api)

### Librerías y aplicaciones de terceros (obsoletas)
- [Pypi.org - mytoyota - Python Client for Toyota Connected Services (sin actualizarse desde febrero del año 2025)](https://pypi.org/project/mytoyota/#history)
- [GitHub - tojota (sin actualizar desde hace más de 2 años)](https://github.com/calmjm/tojota)

### Aplicaciones de terceros que actualmente se mantienen
- [GitHub - ha_toyota (Toyota Europa - usa pytoyoda)](https://github.com/pytoyoda/ha_toyota/)
- [GitHub - ha_toyota_na (Toyota Norteamérica - usa pytoyoda)](https://github.com/widewing/ha-toyota-na)
- [GitHub - pytoyoda (Toyota Europa)](https://github.com/pytoyoda/pytoyoda)

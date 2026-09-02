[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/E1C721AABH)

![](assets/images/toyota_logo_200px.png) ![](assets/images/coyota_200px.png)

[![](https://img.shields.io/badge/Versión%20Actual%20-%20Coyota%20v1.5.0-cc5a5a?style=for-the-badge)](https://github.com/Atoyoc/Coyota/releases/tag/v1.5.0) [![](https://img.shields.io/badge/Notas%20de%20la%20Versión-add16a?style=for-the-badge)](#release_notes)


![](assets/images/coyota_app_01.png)
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
> Inicialmente el proyecto nació para dar soporte para `macOS Intel` también, pero la incompatibilidad de algunas funcionalidades a la hora de presentarlas en pantalla, hacía inviable esta vía, por lo que en la v0.6.1 se decidió eliminar esa posibilidad y sólo está disponible para **Windows**, **Linux** y **macOS Apple Silicon**.

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


## <a name="release_notes"></a>`Notas de Releases`
- [Histórico de Versiones](old_releases.md)

![](https://img.shields.io/badge/Windows-2d8cff?style=for-the-badge&logo=windows&logoColor=black) ![](https://img.shields.io/badge/macOS-A3AAAE?style=for-the-badge&logo=apple&logoColor=black) ![](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

[![](https://img.shields.io/badge/Versión%20Actual%20-%20Coyota%20v1.5.0-cc5a5a?style=for-the-badge)](https://github.com/Atoyoc/Coyota/releases/tag/v1.5.0)

- ![](https://img.shields.io/badge/Nuevo-22c55e?style=for-the-badge) **Viajes** - Agregada la funcionalidad de _Exportar_ tanto una _Ruta_ como una _Ruta con Detalle_. La exportación será en fichero .json, que podrá ser cargada con un visor que estará disponible en la página web de **Coyota**, para visualizar el contenido de forma local en un ordenador, tableta, etc. que soporte el formato HTML del visor (requiere conexión a Internet para una experiencia completa).
- ![](https://img.shields.io/badge/Mejora-29568a?style=for-the-badge) **Precios de carburantes** - La opción _Estadísticas_ que está dentro de **Repostajes**, también aparece ahora dentro de _Precios de carburantes_.
- ![](https://img.shields.io/badge/Bug-cc5a5a?style=for-the-badge) **Viajes** - Al elegír el filtro _Entre fechas..._ y seleccionar un rango de fechas, el filtro no actuaba, y sólo lo hacía al salir de esa parte de la aplicación y volver a entrar refrescando la acción.


## Enlaces que pueden ser de interés

[![](https://img.shields.io/badge/Notas%20de%20versiones%20anteriores-add16a?style=for-the-badge)](old_releases.md)

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

### Precio de carburantes en las gasolineras españolas
- [datos.gob.es](https://datos.gob.es/es/catalogo/e05068001-precio-de-carburantes-en-las-gasolineras-espanolas)

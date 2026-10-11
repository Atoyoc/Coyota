[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/E1C721AABH)

![](assets/images/toyota_logo_200px.png) ![](assets/images/coyota_200px.png)

![Rust](https://img.shields.io/badge/Rust-backend-b7410e?logo=rust&amp;logoColor=white) ![Tauri v2](https://img.shields.io/badge/Tauri-v2-24C8B8?logo=tauri&amp;logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-local%20only-0f80cc?logo=sqlite&amp;logoColor=white)

![macOS](https://img.shields.io/badge/macOS-Apple%20Silicon-0071e3?logo=apple&amp;logoColor=white) ![Windows](https://img.shields.io/badge/Windows-64%20bits-2d8cff?logo=windows&amp;logoColor=white) ![Linux](https://img.shields.io/badge/Linux-64%20bits-fcc624?logo=linux&amp;logoColor=white)

---

[![Version](https://img.shields.io/badge/Versión%20Actual-1.7.1-cc5a5a)](https://github.com/Atoyoc/Coyota/releases/tag/v1.7.1) [![](https://img.shields.io/badge/Notas%20de%20la%20Versión-add16a)](#release_notes) [![](https://img.shields.io/badge/Manual%20de%20Usuario-6a80d1)](help/README.md)

> [!WARNING]
> En la v1.7.1, se ha resuelto un problema debido a un cambio de Toyota, y que impedía recuperar los puntos GPS de la ruta de un viaje.
> 
> Si has sincronizado viajes y el mapa no aparece, debes ir a la **Configuración**, y dentro de la configuración, al apartado **Sincronización**, y dentro de este apartado, pulsar el botón **Sinzronización completa**.
>
> De esta manera, la aplicación buscará los viajes no descargados o que estén incompletos, y podrá actualizar la información correctamente.

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
> Es una aplicación multiplataforma para `Windows`, `Linux` y `macOS` (procesadores Apple Silicon únicamente), `en español`, y que permite gestionar tus vehículos Toyota y Lexus, y **pensada inicialmente para el mercado Europeo de España**.
>
> Coyota no usa ningún paquete de terceros ni intermediarios de ningún tipo para conectarse a la _API de Toyota_ ni gestionar su conectividad. Todo en Coyota está desarrollado desde cero con conexiones directas con Toyota.

> [!NOTE]
> Inicialmente el proyecto nació para dar soporte para `macOS Intel` también, pero la incompatibilidad de algunas funcionalidades a la hora de presentarlas en pantalla, hacía inviable esta vía, por lo que en la v0.6.1 se decidió eliminar esa posibilidad y sólo está disponible para **Windows**, **Linux** y **macOS Apple Silicon**.

Accede al [![](https://img.shields.io/badge/Manual%20de%20Usuario-6a80d1)](help/README.md) para conocer más sobre la aplicación y las diferentes secciones que encontraremos.

## <a name="release_notes"></a>`Notas de Releases`
[![](https://img.shields.io/badge/Notas%20de%20versiones%20anteriores-799e59)](old_releases.md)

---

![Version](https://img.shields.io/badge/Versión%20Actual-1.7.1-cc5a5a)

- ![](https://img.shields.io/badge/Toyota-b14dca) En octubre 2026, Toyota ha cambiado la forma de obtener los datos GPS de un viaje. Se ha actualizado la forma en la que se obtenía esa información en la **API de Toyota**
- ![](https://img.shields.io/badge/Nuevo-22c55e) **Información** - Dentro del apartado **Personalización** hay dos nuevos campos, uno para indicar la _Fecha de pago_, y otro para indicar la fecha de la _Recogida del concesionario_
- ![](https://img.shields.io/badge/Nuevo-22c55e) <strong>Notas</strong> - Agregada una nueva sección para agregar en formato **Markdown**, anotaciones, documentación o cualquier otra información que consideremos útil y que no queramos perder, y que en los campos de notas y observación de **Coyota** no tengan sentido.
- ![](https://img.shields.io/badge/Mejora-29568a) **Repostajes** - Dentro de **Precios de Carburantes**, se puede ordenar el listado tanto por _Precio_, como por _Nombre_. La ordenación por nombre se realiza por _Empresa_ y _Dirección_.
- ![](https://img.shields.io/badge/Mejora-29568a) **Viajes** - Se ha unificado el cálculo de medias e información general con **My Toyota**. En **My Toyota** se produce un redondeo a la cifra más cercana, y en **Coyota** se truncaba. Para evitar posibles malos entendidos entre lo que se muestra en la aplicación oficial y **Coyota**, se ha decidido unificar este criterio. No obstante, hay momentos en los que parece que la aplicación oficial, además de redondear, trunca algunos datos.
- ![](https://img.shields.io/badge/Mejora-29568a) **Viajes** - Cuando se intentan encontrar viajes _Similares_, por defecto, la opción _Incluir Viajes de Vuelta_ aparecerá activada.
- ![](https://img.shields.io/badge/Bug-cc5a5a) **Repostajes** - Si en **Precios de carburantes** el usuario había filtrado algún dato y luego pulsaba en _Actualizar precios_, los filtros después de actualizar se perdían. Ahora si los filtros no han cambiado, los mantiene.


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

### Precio de carburantes en las gasolineras españolas
- [datos.gob.es](https://datos.gob.es/es/catalogo/e05068001-precio-de-carburantes-en-las-gasolineras-espanolas)

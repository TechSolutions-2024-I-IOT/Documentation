# Capítulo III: Requirements Specification

## 3.1 To-Be Scenario Mapping

### 3.1.1 Pasajeros

![To-Be Scenario Mapping de los Pasajeros](../Resources/maps/To-Be%20scenario%20pasajeros.jpg)

### 3.1.2 Empresa de transporte público

![To-Be Scenario Mapping de las Empresas de transporte público](../Resources/maps/To-be%20scenario%20empresas.jpg)

## 3.2 User Stories

<table border="2">
    <tr>
        <td>
           <p style = "font-weight: bold"><b>Epic/Story ID</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Título</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Descripción</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Criterios de aceptación</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Relacionado con (Epic ID)</b></p>
        </td>
    </tr>
    <tr>
        <td>EP01</td>
        <td>Gestión de cuenta</td>
        <td>Como usuario, deseo acceder a mi cuenta para ingresar a la aplicación</td>
        <td> - </td>
        <td> - </td>
    </tr>
    <tr>
        <td>EP02</td>
        <td>Gestión de lineas de transporte</td>
        <td>Como encargado de flota de autobuses, deseo administrar la información en tiempo real de mi flota</td>
        <td> - </td>
        <td> - </td>
    </tr>
    <tr>
        <td>EP03</td>
        <td>Información presentada en el sitio web estático</td>
        <td>Como visitante, deseo encontrar información acerca de la aplicación para conocer si esta me resultará útil</td>
        <td> - </td>
        <td> - </td>
    </tr>
    <tr>
        <td>EP04</td>
        <td>Gestión de dispositivos IOT</td>
        <td>Como desarrollador, quiero configurar los dispositivos IOT a mi sistema</td>
        <td> - </td>
        <td> - </td>
    </tr>
    <tr>
        <td>EP05</td>
        <td>Gestión de suscripciones</td>
        <td>Como pasajero, quiero cambiar mi plan de suscripción</td>
        <td> - </td>
        <td> - </td>
    </tr>
    <tr>
        <td>EP06</td>
        <td>Gestión de servicios</td>
        <td>Como desarrollador, quiero crear endpoints que me ayuden con el desarrollo de mi solución</td>
        <td> - </td>
        <td> - </td>
    </tr>
    <tr>
        <td>EP07</td>
        <td>Información de líneas de transportes</td>
        <td>Como pasajero, quiero obtener información en tiempo real sobre líneas de transporte</td>
        <td> - </td>
        <td> - </td>
    </tr>
    <tr>
        <td>US01</td>
        <td>Visualizar del recorrido de una línea de transporte</td>
        <td>Como pasajero, quiero ver un mapa con el recorrido de la línea, para saber por dónde va el bus
        </td>
        <td>
            <b>Scenario:</b> <br>
            <b>Dado</b> que el pasajero ha seleccionado una línea de transporte<br>
            <b>Cuando</b> el pasajero selecciona la opción "Ver recorrido"<br>
            <b>Entonces</b> se muestra un mapa que incluye la ruta completa de la línea y todas sus paradas
        </td>
    </tr>
  <tr>
        <td>US02</td>
        <td>Buscar una línea de transporte</td>
        <td>Como pasajero, quiero poder buscar una línea por nombre o por número, para encontrar la línea que necesito</td>
        <td>
            <b>Scenario:</b> <br>
            <b>Dado</b> que el pasajero está en la pantalla principal de la aplicación<br>
            <b>Cuando</b> el pasajero introduce el nombre o el número de una línea en el campo de búsqueda<br>
            <b>Y</b> presiona el botón "Buscar"
            <b>Entonces</b> se muestra una lista de las líneas que coinciden con la búsqueda del pasajero
        </td>
        <td></td>
    </tr>
  <tr>
        <td>US03</td>
        <td>Guardar líneas de transporte favoritas</td>
        <td>Como pasajero, quiero poder guardar mis líneas favoritas, para tenerlas a mano y no tener que buscarlas cada vez</td>
        <td>
            <b>Scenario:</b> <br>
            <b>Dado</b> que el pasajero está viendo la información de una línea<br>
            <b>Cuando</b> el pasajero selecciona el botón "Favoritos"<br>
            <b>Entonces</b> la línea se guarda en una lista de favoritos
        </td>
        <td></td>
    </tr>
  <tr>
        <td>US04</td>
        <td>Compartir información de una línea de transporte</td>
        <td>Como pasajero, quiero poder compartir información sobre las líneas con mis amigos y familiares, para ayudarlos a planificar sus viajes</td>
        <td>
            <b>Scenario:</b> <br>
            <b>Dado</b> que el pasajero está viendo la información de una línea<br>
            <b>Cuando</b> el pasajero selecciona el botón "Compartir"<br>
            <b>Y</b> el pasajero selecciona una aplicación para compartir la información<br>
            <b>Entonces</b> la información de la línea se comparte con la aplicación seleccionada
        </td>
        <td></td>
    </tr>
  <tr>
        <td>US05</td>
        <td>Recibir notificaciones de líneas de transporte</td>
        <td>Como pasajero, quiero recibir notificaciones cuando haya cambios en mis líneas favoritas, para estar al tanto de cualquier información importante</td>
        <td>
            <b>Scenario:</b> <br>
            <b>Dado</b> que el pasajero ha guardado una línea como favorita<br>
            <b>Y</b> el pasajero ha activado las notificaciones para las líneas favoritas<br>
            <b>Cuando</b> hay un cambio en la línea favorita del pasajero, como un cambio en el recorrido, el tiempo de viaje o la frecuencia del servicio<br>
            <b>Entonces</b> el pasajero recibe una notificación en su dispositivo
        </td>
        <td></td>
    </tr>
    <tr>
        <td>US06</td>
        <td>Redirección de la landing Page a tiendas de aplicaciones</td>
        <td>Como visitante del segmento pasajero, deseo ser redirigido a la aplicación móvil correspondiente para descargarla en mi dispositivo móvil</td>
        <td>
            <b>Scenario 1: Redirección a Google Play</b> <br>
            <b>Dado</b> que el visitante del segmento pasajero se encuentra en la vista principal de la landing page<br>
            <b>Cuando</b> el visitante haga click en el botón de acción de Google Play<br>
            <b>Entonces</b> el visitante será redirigido a la página de descarga de la aplicación en Google Play<br><br>
            <b>Scenario 2: Redirección a App Store</b> <br>
            <b>Dado</b> que el visitante del segmento pasajero se encuentra en la vista principal de la landing page<br>
            <b>Cuando</b> el visitante haga click en el botón de acción de App Store<br>
            <b>Entonces</b> el visitante será redirigido a la página de descarga de la aplicación en la App Store de iOS
        </td>
        <td>
        <!--
            <b>Criterios de Aceptación:</b><br>
            1. El botón de Google Play en la landing page debe ser funcional y redirigir al usuario a la página de descarga de la aplicación en Google Play Store.<br>
            2. El botón de App Store en la landing page debe ser funcional y redirigir al usuario a la página de descarga de la aplicación en la App Store de iOS.<br>
            3. La redirección debe ser inmediata y sin errores, proporcionando al usuario una experiencia fluida.<br>
            4. Los botones de acción deben ser claramente visibles y distinguibles para el usuario.-->
        </td>
    </tr>
    <tr>
        <td>US07</td>
        <td>Redirección de la landing Page a la aplicación web</td>
        <td>Como visitante del segmento encargado de flota de autobuses, deseo ser redirigido a la aplicación web correspondiente para usarla en mi navegador favorito</td>
        <td>
            <b>Scenario: Redirección a la aplicación web de ChapaTuBus</b> <br>
            <b>Dado</b> que el visitante del segmento encargado de la flota de autobuses se encuentra en la sección de empresa de la landing page<br>
            <b>Cuando</b> el visitante haga click en el botón de redirección a la aplicación web<br>
            <b>Entonces</b> el visitante será redirigido a la aplicación web de ChapaTuBus<br><br>
        </td>
        <td>
        <!--
            <b>Criterios de Aceptación:</b><br>
            1. El botón de redirección en la sección de empresa de la landing page debe ser funcional y redirigir al usuario a la aplicación web de ChapaTuBus.<br>
            2. La redirección debe ser inmediata y sin errores, proporcionando al usuario una experiencia fluida.<br>
            3. El diseño y la estructura de la aplicación web deben ser coherentes con la marca y ofrecer una navegación intuitiva para el usuario.<br>
            4. El botón de redirección debe ser claramente visible y distinguible para el usuario, utilizando un diseño que invite a hacer clic.-->
        </td>
    </tr>
    <tr>
        <td>US08</td>
        <td>Envío de mensaje a través de un formulario de contacto</td>
        <td>Como visitante del segmento pasajero, deseo enviar un mensaje a los desarrolladores para enviar sugerencias, quejas u mensajes con otro motivo que yo desee</td>
        <td>
            <b>Scenario: Envío del formulario exitoso</b> <br>
            <b>Dado</b> que el visitante del segmento pasajero se encuentra en la sección de contacto de la landing page<br>
            <b>Y</b> el visitante llena el formulario de contacto con la información solicitada<br>
            <b>Cuando</b> el visitante haga click en el botón de envío de formulario<br>
            <b>Entonces</b> la información será enviada al correo electrónico de ChapaTuBus<br><br>
        </td>
        <td>
        <!--
            <b>Criterios de Aceptación:</b><br>
            1. El formulario de contacto debe contener campos claros y relevantes para capturar la información necesaria del visitante (nombre, correo electrónico, mensaje, etc.).<br>
            2. Al enviar el formulario, el sistema debe realizar una validación para asegurarse de que todos los campos requeridos estén completos antes de enviar la información.<br>
            3. Después de enviar el formulario con éxito, el visitante debe recibir una confirmación visual o mensaje de éxito en la página, indicando que su mensaje ha sido enviado correctamente.<br>
            4. La información del formulario debe ser enviada de manera segura al correo electrónico de ChapaTuBus, garantizando la privacidad y seguridad de los datos del visitante.<br>-->
        </td>
    </tr>
    <tr>
         <td>US09</td>
        <td>Visualizar paraderos con mayor afluencia</td>
        <td>Como empresa de transporte público, quiero tener información sobre los paraderos donde se sube más gente durante el día, para poder identificar las rutas con mayor demanda
        </td>
        <td>
            <b>Scenario 1: Visualización correcta de datos</b> <br>
            <b>Dado</b> que la empresa de transporte público ha iniciado sesión en la aplicación<br>
            <b>Y</b> selecciona la opción “Visualizar paradas con mayor afluencia”<br>
            <b>Cuando</b> la aplicación carga la información de las paradas<br>
            <b>Entonces</b> se muestra información detallada sobre la afluencia en diferentes momentos del día <br>
            <b>Scenario 2: Filtrado de paradas</b> <br>
            <b>Dado</b> que la empresa de transporte público desea ver solo las paradas con mayor afluencia en un horario específico<br>
            <b>Cuando</b> la empresa de transporte público selecciona un filtro de horario<br>
            <b>Entonces</b> la información detallada de las paradas se actualiza para mostrar solo la información del horario seleccionado
        </td>
        <td>
        </td>
    </tr>
<tr>
         <td>US10</td>
        <td>Visualizar horarios de mayor afluencia</td>
        <td>Como empresa de transporte público, quiero ver un gráfico estadístico con los horarios de mayor afluencia en cada paradero, para poder ajustar la frecuencia de los buses
        </td>
        <td>
            <b>Scenario 1: Visualización correcta del gráfico</b> <br>
            <b>Dado</b> que la empresa de transporte público ha iniciado sesión en la aplicación<br>
            <b>Y</b> selecciona la opción “Visualizar afluencia según horarios”<br>
            <b>Cuando</b> la aplicación carga la información del gráfico<br>
            <b>Entonces</b> se muestra un gráfico con la afluencia de personas en cada paradero<br>
            <b>Scenario 2: Descarga del gráfico</b> <br>
            <b>Dado</b> que la empresa de transporte público desea compartir el gráfico con otros usuarios<br>
            <b>Cuando</b> selecciona la opción de descargar el gráfico<br>
            <b>Entonces</b> se le ofrece la opción de descargar el gráfico en diferentes formatos
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>US11</td>
        <td>Visualizar horarios de mayor afluencia</td>
        <td>Como empresa de transporte público, quiero ver un gráfico estadístico con los horarios de mayor afluencia en cada paradero, para poder ajustar la frecuencia de los buses
        </td>
        <td>
            <b>Scenario 1: Visualización correcta del gráfico</b> <br>
            <b>Dado</b> que la empresa de transporte público ha iniciado sesión en la aplicación<br>
            <b>Y</b> selecciona la opción “Visualizar afluencia según horarios”<br>
            <b>Cuando</b> la aplicación carga la información del gráfico<br>
            <b>Entonces</b> se muestra un gráfico con la afluencia de personas en cada paradero<br>
            <b>Scenario 2: Descarga del gráfico</b> <br>
            <b>Dado</b> que la empresa de transporte público desea compartir el gráfico con otros usuarios<br>
            <b>Cuando</b> selecciona la opción de descargar el gráfico<br>
            <b>Entonces</b> se le ofrece la opción de descargar el gráfico en diferentes formatos
        </td>
        <td>
        </td>
</tr>
    <tr>
         <td>US12</td>
        <td>Visualizar aforo en buses</td>
        <td>Como empresa de transporte público, quiero tener información con la cantidad de personas en cada bus en tiempo real, para poder identificar los buses con mayor ocupación
        </td>
        <td>
            <b>Scenario 1: Visualización correcta del aforo</b> <br>
            <b>Dado</b> que la empresa de transporte público ha iniciado sesión en la aplicación<br>
            <b>Y</b> selecciona la opción “Visualizar aforo”<br>
            <b>Cuando</b> la aplicación carga la información del aforo<br>
            <b>Entonces</b> al seleccionar un bus se muestra información detallada sobre la cantidad de personas a bordo en tiempo real<br>
            <b>Scenario 2: Filtrado de buses</b> <br>
            <b>Dado</b> que la empresa de transporte público desea ver solo los buses con mayor cantidad de personas a bordo en una ruta específica<br>
            <b>Cuando</b> selecciona un filtro de ruta<br>
            <b>Entonces</b> la información detallada de los buses también se actualiza para mostrar solo la información de la ruta seleccionada
        </td>
        <td>
        </td>
</tr>
    <tr>
         <td>US13</td>
        <td>Visualizar ubicación de la flota en tiempo real</td>
        <td>Como empresa de transporte público, quiero ver la ubicación de mi flota en tiempo real, para poder monitorizar el estado del servicio
        </td>
        <td>
            <b>Scenario 1: Visualización correcta de la ubicación</b> <br>
            <b>Dado</b> que la empresa de transporte público ha iniciado sesión en la aplicación<br>
            <b>Y</b> selecciona la opción “Visualizar ubicación en tiempo real”<br>
            <b>Cuando</b> la aplicación carga la información de la ubicación<br>
            <b>Entonces</b> se muestra un mapa con los buses representados por íconos, donde cada ícono indica la ubicación actual del bus<br>
            <b>Scenario 2: Seguimiento de un bus</b> <br>
            <b>Dado</b> que la empresa de transporte público desea seguir el recorrido de un bus específico<br>
            <b>Cuando</b> selecciona la opción “Seguir un bus"<br>
            <b>Entonces</b> el mapa se centra en el bus seleccionado y se actualiza en tiempo real 
        </td>
        <td>
        </td>
</tr>
    <tr>
         <td>US14</td>
        <td>Visualizar estado de los conductores</td>
        <td>Como empresa de transporte público, quiero ver el estado de mis conductores en tiempo real, para poder identificar a los que puedan estar cansados o estresados
        </td>
        <td>
            <b>Scenario 1: Visualización correcta del estado</b> <br>
            <b>Dado</b> que la empresa de transporte público ha iniciado sesión en la aplicación<br>
            <b>Y</b> selecciona la opción “Visualizar estado de conductor”<br>
            <b>Cuando</b> la aplicación carga la información del estado de los conductores<br>
            <b>Entonces</b> se muestra una lista con los conductores y su estado actual<br>
            <b>Scenario 2: Visualizar estado detallado</b> <br>
            <b>Dado</b> que la empresa de transporte público selecciona un conductor<br>
            <b>Cuando</b> la aplicación carga la información del estado del conductor seleccionado<br>
            <b>Entonces</b> se muestra información detallada sobre su estado como ubicación, nivel de fatiga, estado de ánimo, entre otros
        </td>
        <td>
        </td>
</tr>
        <tr>
         <td>US15</td>
        <td>Recibir notificaciones</td>
        <td>Como empresa de transporte público, quiero recibir notificaciones en tiempo real sobre eventos relevantes para estar al tanto de posibles incidentes
        </td>
        <td>
            <b>Scenario 1: Recepción correcta de notificaciones</b> <br>
            <b>Dado</b> que la empresa de transporte público ha iniciado sesión en la aplicación<br>
            <b>Y</b> ha activado las notificaciones<br>
            <b>Cuando</b> se produce un evento relevante (ej. retraso de un bus, accidente, parada no programada)<br>
            <b>Entonces</b> la empresa de transporte público recibe una notificación en tiempo real en la aplicación con el tipo de evento, la ubicación, la hora e información adicional<br>
            <b>Scenario 2: Personalización de notificaciones</b> <br>
            <b>Dado</b> que la empresa de transporte público desea personalizar las notificaciones que recibe<br>
            <b>Cuando</b> selecciona la opción "Personalizar Notificaciones"<br>
            <b>Entonces</b> la empresa de transporte público puede elegir qué tipos de eventos quiere recibir notificaciones (ej. solo retrasos, solo accidentes) <br>
            <b>Y</b> puede elegir cómo quiere recibir las notificaciones (ej. en la aplicación, por correo electrónico, por SMS)
        </td>
        <td>
        </td>
</tr>
    <tr>
         <td>US16</td>
        <td>Cambiar rutas de la flota</td>
        <td>Como empresa de transporte público, quiero poder cambiar las rutas de mi flota en tiempo real, para poder ajustar el servicio a las condiciones del tráfico o a la demanda de pasajeros
        </td>
        <td>
            <b>Scenario 1: Modificación correcta de rutas</b> <br>
            <b>Dado</b> que la empresa de transporte público ha iniciado sesión en la aplicación<br>
            <b>Y</b> ha seleccionado la opción "Cambiar Rutas de la Flota"<br>
            <b>Cuando</b> la empresa de transporte público selecciona un bus<br>
            <b>Y</b> modifica su ruta<br>
            <b>Entonces</b> la ruta del bus se actualiza en tiempo real en el mapa<br>
            <b>Y</b> los pasajeros son notificados del cambio de ruta a través de la aplicación o por mensaje de texto<br>
            <b>Scenario 2: Historial de cambios de ruta</b> <br>
            <b>Dado</b> que la empresa de transporte público desea ver el historial de cambios de ruta que se han realizado<br>
            <b>Cuando</b> selecciona la opción "Ver historial de cambios de ruta"<br>
            <b>Entonces</b> se muestra una lista con todos los cambios de ruta que se han realizado, incluyendo la fecha, hora, bus afectado y ruta original y nueva
        </td>
        <td>
        </td>
</tr>

</tr>
    <tr>
         <td>US13</td>
        <td>Registro de Línea de Bus</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/bus-lines/register que permita el registro de una nueva línea de bus, para que los administradores de flota o dueños de empresas puedan añadir nuevas líneas al sistema de manera eficiente.</td>
        <td>
            <b>Escenario 1: Registro exitoso de una nueva línea de bus</b> <br>
            <b>Dado</b> que el administrador de flota tiene los datos necesarios para registrar una nueva línea de bus,<br>
            <b>Cuando</b> envía una petición POST a /api/bus-lines/register con los detalles de la línea (nombre, ruta, horarios, información del bus, etc.),<br>
            <b>Entonces</b> el sistema debe validar la información proporcionada,<br>
            <b>Y</b> si la información es válida, registrar la nueva línea de bus en la base de datos,<br>
            <b>Y</b> devolver un 201 Created con los detalles de la línea de bus registrada, incluyendo un identificador único asignado por el sistema.<br>
            <b>Escenario 2: Manejar intento de registro con datos incompletos o inválidos</b> <br>
            <b>Dado</b> que el administrador de flota envía una petición POST a /api/bus-lines/register con datos incompletos o inválidos para la línea de bus,<br>
            <b>Cuando</b> el sistema intenta validar la información,<br>
            <b>Entonces</b> el sistema debe identificar los campos que son inválidos o faltantes,<br>
            <b>Y</b> devolver un 400 Bad Request con un mensaje que detalle los problemas encontrados en los datos proporcionados.<br>
            <b>Escenario 3: Prevención de duplicados en el registro de líneas de bus</b> <br>
            <b>Dado</b> que el administrador de flota intenta registrar una línea de bus que ya existe en el sistema,<br>
            <b>Cuando</b> envía una petición POST a /api/bus-lines/register con datos que coinciden con una línea existente,<br>
            <b>Entonces</b> el sistema debe verificar la base de datos para prevenir registros duplicados,<br>
            <b>Y</b> si se encuentra un duplicado, devolver un 409 Conflict indicando que la línea de bus ya está registrada.<br>
            <b>Escenario 4: Confirmación de registro a usuarios interesados</b> <br>
            <b>Dado</b> que una nueva línea de bus ha sido registrada exitosamente,<br>
            <b>Cuando</b> el registro se completa,<br>
            <b>Entonces</b> el sistema debe notificar a los usuarios interesados (por ejemplo, mediante un servicio de mensajería o correo electrónico) sobre la nueva línea de bus disponible,<br>
            <b>Y</b> incluir en la notificación los detalles básicos de la nueva línea para fomentar su utilización.<br>
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr><td colspan="5"> <b>Technical Stories</b> <td></tr>
</tr>
</tr>
    <tr>
         <td>US01</td>
        <td>Listado de Líneas de Buses</td>
        <td>Como desarrollador, quiero implementar un endpoint que devuelva un listado de todas las líneas de buses, para que la aplicación móvil pueda mostrarlas en la sección de explorar.</td>
        <td>
            <b>Scenario 1: Obtener el listado de líneas de buses exitosamente</b> <br>
            <b>Dado</b> que existen líneas de buses registradas en el sistema,<br>
            <b>Cuando</b> el usuario hace una petición GET,<br>
            <b>Entonces</b> el sistema debe devolver un 200 OK con un array de objetos con los detalles de cada línea.<br><br>
            <b>Escenario 2: Manejar la ausencia de líneas de buses</b> <br>
            <b>Dado</b> que no hay líneas de buses registradas en el sistema,<br>
            <b>Cuando</b> el usuario hace una petición GET,<br>
            <b>Entonces</b> el sistema debe devolver un 200 OK con un array vacío para indicar que no hay líneas disponibles.<br><br>
            <b>Escenario 3: Manejar errores en el listado de líneas de buses</b> <br>
            <b>Dado</b> que ocurre un error en el backend mientras se intenta recuperar la lista de líneas de buses,<br>
            <b>Cuando</b> el usuario hace una petición GET,<br>
            <b>Entonces</b> el sistema debe devolver un 500 Internal Server Error para indicar que algo salió mal en el proceso de recuperación de datos.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US02</td>
        <td>Búsqueda de Líneas de Bus</td>
        <td>Como desarrollador, quiero crear un endpoint para buscar líneas de bus por nombre, para que los usuarios puedan encontrar rápidamente las rutas que necesitan.</td>
        <td>
            <b>Escenario 1: Búsqueda exitosa con cadena válida</b> <br>
            <b>Dado</b> que el usuario envía una cadena de búsqueda válida,<br>
            <b>Cuando</b> el sistema procesa la solicitud,<br>
            <b>Entonces</b> el sistema debe devolver un 200 OK con una lista de líneas que coincidan con esa cadena.<br><br>
            <b>Escenario 2: Búsqueda fallida con cadena de búsqueda vacía o inválida</b> <br>
            <b>Dado</b> que el usuario envía una cadena de búsqueda vacía o inválida,<br>
            <b>Cuando</b> el sistema procesa la solicitud,<br>
            <b>Entonces</b> el sistema debe devolver un 400 Bad Request con un mensaje de error de validación.<br><br>
            <b>Escenario 3: Búsqueda sin resultados</b> <br>
            <b>Dado</b> que no hay resultados para la cadena de búsqueda proporcionada por el usuario,<br>
            <b>Cuando</b> el sistema procesa la solicitud,<br>
            <b>Entonces</b> el sistema debe devolver un 200 OK con una lista vacía para indicar que no hay líneas disponibles.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US03</td>
        <td>Gestión de Favoritos</td>
        <td>Como desarrollador, quiero crear un endpoint que permita a los usuarios marcar una línea de bus como favorita, para que puedan acceder rápidamente a sus líneas preferidas desde la sección de favoritos.</td>
        <td>
            <b>Escenario 1: Añadir una línea de bus a favoritos</b> <br>
            <b>Dado</b> que el usuario selecciona una línea de bus para añadir a favoritos y envía una solicitud POST a /api/favorites con el ID de la línea de bus,<br>
            <b>Cuando</b> el sistema procesa la solicitud,<br>
            <b>Entonces</b> el sistema debe añadir la línea de bus a la lista de favoritos del usuario y devolver un 201 Created con una confirmación de la acción.<br><br>
            <b>Escenario 2: Eliminar una línea de bus de favoritos</b> <br>
            <b>Dado</b> que el usuario desea eliminar una línea de bus de su lista de favoritos y envía una solicitud DELETE a con el ID de la línea de bus,<br>
            <b>Cuando</b> el sistema procesa la solicitud,<br>
            <b>Entonces</b> el sistema debe eliminar la línea de bus de la lista de favoritos del usuario y devolver un 200 OK con una confirmación de la acción.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US04</td>
        <td>Listado de Paraderos de una Línea de Bus</td>
        <td>Como desarrollador, quiero crear un endpoint que devuelva la lista de paraderos de una línea de bus específica, para que los usuarios puedan ver todos los paraderos disponibles para esa línea en la aplicación móvil.</td>
        <td>
            <b>Escenario 1: Obtener la lista de paraderos para una línea de bus</b> <br>
            <b>Dado</b> que el usuario envía una petición GET a /api/bus-lines/{lineId}/stops con un ID de línea de bus válido,<br>
            <b>Cuando</b> el sistema procesa la solicitud,<br>
            <b>Entonces</b> el sistema debe devolver un 200 OK con un array de objetos, donde cada objeto contiene al menos el nombre y ubicación del paradero.<br><br>
            <b>Escenario 2: Manejar la solicitud con un ID de línea de bus no existente</b> <br>
            <b>Dado</b> que el usuario envía una petición GET a /api/bus-lines/{lineId}/stops con un ID de línea de bus que no existe,<br>
            <b>Cuando</b> el sistema procesa la solicitud,<br>
            <b>Entonces</b> el sistema debe devolver un 404 Not Found indicando que la línea de bus no existe.<br><br>
            <b>Escenario 3: Manejar la solicitud sin ID de línea de bus</b> <br>
            <b>Dado</b> que el usuario envía una petición GET a /api/bus-lines/{lineId}/stops sin proporcionar un ID de línea de bus,<br>
            <b>Cuando</b> el sistema intenta procesar la solicitud,<br>
            <b>Entonces</b> el sistema debe devolver un 400 Bad Request indicando que falta el ID de la línea de bus en la solicitud.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US05</td>
        <td>Datos de Paraderos y Buses en Tiempo Real</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/real-time/{lineId} que devuelva datos en tiempo real de paraderos y buses para una línea específica, para que los usuarios puedan ver la ubicación del bus en el mapa, el nombre del paradero, y el tiempo estimado de llegada.</td>
        <td>
            <b>Escenario 1: Obtener información en tiempo real de paraderos para una línea de bus</b> <br>
            <b>Dado</b> que existe información en tiempo real disponible para una línea de bus con un ID específico,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/real-time/{lineId},<br>
            <b>Entonces</b> el sistema debe consultar el último estado de los buses de esa línea desde la base de datos en tiempo real o un sistema de mensajería/subscripción como WebSockets o MQTT,<br>
            <b>Y</b> devolver un 200 OK con un array de objetos que representan los paraderos, donde cada objeto contiene el nombre del paradero, la ubicación geográfica, y datos de tiempo estimado de llegada del próximo bus basado en su ubicación actual.<br><br>
            <b>Escenario 2: Obtener información de ubicación del bus para un paradero seleccionado</b> <br>
            <b>Dado</b> que el usuario selecciona un paradero específico y existe información en tiempo real disponible,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/real-time/{lineId}/stops/{stopId},<br>
            <b>Entonces</b> el sistema calcula el tiempo estimado de llegada basándose en la velocidad actual del bus y las condiciones de tráfico,<br>
            <b>Y</b> devolver un 200 OK con un objeto que incluye la ubicación actual del bus y el tiempo estimado de llegada al paradero seleccionado.<br><br>
            <b>Escenario 3: Manejar la ausencia de datos en tiempo real</b> <br>
            <b>Dado</b> que no hay datos en tiempo real disponibles debido a un fallo de sensor o falta de conectividad,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a cualquiera de los endpoints anteriores,<br>
            <b>Entonces</b> el sistema debe devolver un 502 Bad Gateway con un mensaje que indique que la información en tiempo real no está disponible.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US06</td>
        <td>Aforo en Tiempo Real de Buses</td>
        <td>Como desarrollador, quiero implementar un endpoint que devuelva el aforo en tiempo real de un bus específico, para que los usuarios puedan saber cuántas personas hay en el bus antes de que llegue al paradero.</td>
        <td>
            <b>Escenario 1: Obtener el aforo en tiempo real de un bus específico</b> <br>
            <b>Dado</b> que existen cámaras instaladas en un bus específico que están funcionando y enviando datos,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/real-time/bus-capacity/{busId} con un ID de bus válido,<br>
            <b>Entonces</b> el sistema debe consultar la última información de aforo recibida de los sensores,<br>
            <b>Y</b> devolver un 200 OK con el número actual de pasajeros en el bus.<br><br>
            <b>Escenario 2: Manejar buses sin datos de aforo debido a sensores desconectados o en error</b> <br>
            <b>Dado</b> que los sensores de un bus no están enviando datos debido a una desconexión o mal funcionamiento,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/real-time/bus-capacity/{busId},<br>
            <b>Entonces</b> el sistema debe devolver un 503 Service Unavailable con un mensaje que indique que la información de aforo no está disponible temporalmente.<br><br>
            <b>Escenario 3: Manejar ID de bus inválido o inexistente</b> <br>
            <b>Dado</b> que se envía una petición con un ID de bus inválido o inexistente,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/real-time/aforo/{busId},<br>
            <b>Entonces</b> el sistema debe validar el ID del bus,<br>
            <b>Y</b> si el bus no existe, debe devolver un 404 Not Found,<br>
            <b>O</b> si el ID es inválido, debe devolver un 400 Bad Request.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US07</td>
        <td>Datos Históricos de Paraderos por Fecha</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/historical/stops/{date} que devuelva los datos históricos de los paraderos para una fecha específica, para que el dashboard de la aplicación web pueda mostrar un listado de paraderos ordenados según la cantidad de personas que subieron en cada uno en dicha fecha.</td>
        <td>
            <b>Escenario 1: Obtener datos históricos de paraderos por fecha específica</b> <br>
            <b>Dado</b> que existen registros históricos para la fecha proporcionada,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/historical/stops/{date} con una fecha en formato YYYY-MM-DD,<br>
            <b>Entonces</b> el sistema debe consultar la base de datos para esa fecha,<br>
            <b>Y</b> devolver un 200 OK con un array de objetos que representan los paraderos, donde cada objeto contiene el nombre del paradero y el número total de personas que subieron en ese paradero ese día.<br><br>
            <b>Escenario 2: Manejar una fecha sin registros históricos</b> <br>
            <b>Dado</b> que no existen registros históricos para la fecha proporcionada,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/historical/stops/{date},<br>
            <b>Entonces</b> el sistema debe devolver un 204 No Content para indicar que no hay datos disponibles para esa fecha.<br><br>
            <b>Escenario 3: Manejar formato de fecha incorrecto en la solicitud</b> <br>
            <b>Dado</b> que el desarrollador envía una fecha en un formato incorrecto o inválido,<br>
            <b>Cuando</b> hace una petición GET a /api/historical/stops/{date},<br>
            <b>Entonces</b> el sistema debe devolver un 400 Bad Request indicando que el formato de la fecha no es válido.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US08</td>
        <td>Histograma de Afluencia por Paradero</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/stops/{stopId}/passenger-flow que devuelva los datos de afluencia de pasajeros para un paradero específico, para que el dashboard de la aplicación web pueda mostrar un histograma de la hora más concurrida en dicho paradero.</td>
        <td>
            <b>Escenario 1: Obtener datos de afluencia por paradero</b> <br>
            <b>Dado</b> que se han recopilado datos de afluencia para un paradero específico durante el día,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/stops/{stopId}/passenger-flow,<br>
            <b>Entonces</b> el sistema debe recuperar los datos de afluencia del paradero especificado,<br>
            <b>Y</b> devolver un 200 OK con un objeto que contenga una serie de pares clave-valor, donde cada clave es un rango horario y cada valor es el número total de pasajeros que subieron en ese paradero durante ese rango.<br><br>
            <b>Escenario 2: Manejar un paradero sin datos de afluencia</b> <br>
            <b>Dado</b> que no hay datos de afluencia disponibles para el paradero seleccionado,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/stops/{stopId}/passenger-flow,<br>
            <b>Entonces</b> el sistema debe devolver un 204 No Content para indicar que no hay datos disponibles para ese paradero.<br><br>
            <b>Escenario 3: Manejar una solicitud con ID de paradero inválido o inexistente</b> <br>
            <b>Dado</b> que el desarrollador envía un ID de paradero que no existe o es inválido,<br>
            <b>Cuando</b> realiza una petición GET a /api/stops/{stopId}/passenger-flow,<br>
            <b>Entonces</b> el sistema debe devolver un 404 Not Found indicando que el paradero no está registrado o el ID es incorrecto.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US09</td>
        <td>Visualización de Datos de Conductores y Buses</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/drivers-info que devuelva una lista de todos los conductores con sus datos personales y detalles del bus que manejan, para que la aplicación web pueda mostrar esta información en el dashboard y permita a los administradores de flota o dueños de empresas monitorear y gestionar su personal y vehículos de manera efectiva.</td>
        <td>
            <b>Escenario 1: Obtener la lista de conductores y los buses que manejan</b> <br>
            <b>Dado</b> que existen registros de conductores y buses en el sistema,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/drivers-info,<br>
            <b>Entonces</b> el sistema debe consultar la base de datos y devolver un 200 OK con un array de objetos, donde cada objeto contiene la información del conductor (como nombre, número de identificación, etc.) y detalles del bus (como la placa, modelo, y estado actual).<br><br>
            <b>Escenario 2: Manejar la ausencia de conductores o buses</b> <br>
            <b>Dado</b> que no hay conductores o buses registrados en el sistema,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/drivers-info,<br>
            <b>Entonces</b> el sistema debe devolver un 204 No Content para indicar que actualmente no hay datos disponibles.<br><br>
            <b>Escenario 3: Manejar errores inesperados al recuperar información</b> <br>
            <b>Dado</b> que ocurre un error inesperado en el sistema al intentar recuperar la información de los conductores y buses,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/drivers-info,<br>
            <b>Entonces</b> el sistema debe devolver un 500 Internal Server Error indicando que no se pudo procesar la solicitud debido a un problema en el servidor.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US10</td>
        <td>Pulsaciones de Corazón del Conductor</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/drivers/{driverId}/heart-rate que devuelva el rango de pulsaciones de corazón de un conductor específico durante un rango horario dado, para que el dashboard de la aplicación web pueda mostrar estos datos, permitiendo a los administradores de flota monitorear el bienestar de los conductores durante sus turnos.</td>
        <td>
            <b>Escenario 1: Obtener el rango de pulsaciones de corazón del conductor</b> <br>
            <b>Dado</b> que existen registros de las pulsaciones de corazón para un conductor en un rango horario específico,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/drivers/{driverId}/heart-rate con parámetros de consulta para el rango horario,<br>
            <b>Entonces</b> el sistema debe consultar la base de datos y devolver un 200 OK con un array de objetos, cada uno representando un intervalo de tiempo con las pulsaciones mínimas, máximas y promedio registradas en ese período.<br><br>
            <b>Escenario 2: Manejar solicitud de un conductor sin registros de pulsaciones</b> <br>
            <b>Dado</b> que no hay registros de pulsaciones para el conductor en el rango horario solicitado,<br>
            <b>Cuando</b> el desarrollador hace una petición GET a /api/drivers/{driverId}/heart-rate,<br>
            <b>Entonces</b> el sistema debe devolver un 204 No Content para indicar que no hay datos de pulsaciones disponibles para ese conductor en el rango horario especificado.<br><br>
            <b>Escenario 3: Manejar una solicitud con ID de conductor inválido o inexistente</b> <br>
            <b>Dado</b> que el desarrollador hace una petición GET a /api/drivers/{driverId}/heart-rate con un ID de conductor que no existe o es inválido,<br>
            <b>Cuando</b> el sistema intenta recuperar los datos,<br>
            <b>Entonces</b> el sistema debe devolver un 404 Not Found para indicar que el conductor no está registrado en el sistema o el ID proporcionado es incorrecto.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US11</td>
        <td>Alertas de Pulsaciones del Conductor</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/drivers/alerts que monitoree las pulsaciones del corazón de los conductores y genere alertas cuando estas pulsaciones caigan por debajo de un mínimo o superen un máximo predeterminado, para que el sistema de notificaciones pueda informar a los administradores de flota sobre posibles situaciones de riesgo para la salud del conductor.</td>
        <td>
            <b>Escenario 1: Generar alertas por pulsaciones bajas</b> <br>
            <b>Dado</b> que el sistema recibe datos de pulsaciones de un conductor que caen por debajo del mínimo predeterminado,<br>
            <b>Cuando</b> estos datos son procesados por el endpoint /api/drivers/alerts,<br>
            <b>Entonces</b> el sistema debe generar una alerta y devolver un 200 OK con un mensaje de alerta, incluyendo el ID del conductor, la hora del evento y un mensaje indicando que las pulsaciones están anormalmente bajas.<br><br>
            <b>Escenario 2: Generar alertas por pulsaciones altas</b> <br>
            <b>Dado</b> que el sistema recibe datos de pulsaciones de un conductor que superan el máximo predeterminado,<br>
            <b>Cuando</b> estos datos son procesados por el endpoint /api/drivers/alerts,<br>
            <b>Entonces</b> el sistema debe generar una alerta y devolver un 200 OK con un mensaje de alerta, incluyendo el ID del conductor, la hora del evento y un mensaje indicando que las pulsaciones están anormalmente altas.<br><br>
            <b>Escenario 3: Manejar ausencia de datos de pulsaciones</b> <br>
            <b>Dado</b> que no se reciben datos de pulsaciones para un conductor durante un período prolongado,<br>
            <b>Cuando</b> se verifica la actividad del conductor a través del endpoint /api/drivers/alerts,<br>
            <b>Entonces</b> el sistema debe generar una alerta de "sin datos" y devolver un 200 OK con un mensaje indicando la falta de datos de pulsaciones y potencialmente sugerir verificar el dispositivo del conductor.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US12</td>
        <td>Autenticación de Usuarios</td>
        <td>Como desarrollador, quiero implementar un sistema de inicio de sesión que permita a los usuarios autenticarse utilizando su correo y contraseña o su cuenta de Google, para que puedan acceder de manera segura a la aplicación.</td>
        <td>
            <b>Escenario 1: Inicio de sesión con correo y contraseña</b> <br>
            <b>Dado</b> que un usuario desea iniciar sesión proporcionando un correo y contraseña,<br>
            <b>Cuando</b> el usuario envía una petición POST a /api/auth/login con su correo y contraseña,<br>
            <b>Entonces</b> el sistema debe validar las credenciales contra la base de datos,<br>
            Y si las credenciales son correctas, devolver un 200 OK con un token de acceso JWT (JSON Web Token),<br>
            Y si las credenciales son incorrectas, devolver un 401 Unauthorized indicando que el correo o contraseña no son válidos.<br><br>
            <b>Escenario 2: Inicio de sesión con cuenta de Google</b> <br>
            <b>Dado</b> que un usuario desea iniciar sesión utilizando su cuenta de Google,<br>
            <b>Cuando</b> el usuario selecciona la opción de inicio de sesión con Google y autoriza la aplicación a través de la API de Google,<br>
            <b>Entonces</b> el sistema debe recibir un token de Google,<br>
            Y el sistema debe validar el token con los servidores de Google,<br>
            Y si el token es válido, el sistema debe verificar si el usuario ya está registrado con ese correo de Google en la base de datos,<br>
            Si el usuario no está registrado, el sistema debe crear un nuevo usuario con los datos proporcionados por Google y devolver un 200 OK con un token de acceso JWT,<br>
            Si el usuario está registrado, simplemente devolver un 200 OK con un token de acceso JWT.<br><br>
            <b>Escenario 3: Manejar errores en la autenticación con Google</b> <br>
            <b>Dado</b> que ocurre un error al intentar autenticar con Google (por ejemplo, el token de Google es inválido o ha expirado),<br>
            <b>Cuando</b> el sistema intenta validar el token con Google,<br>
            <b>Entonces</b> el sistema debe devolver un 400 Bad Request o 401 Unauthorized indicando el error específico relacionado con la autenticación de Google.<br><br>
            <b>Escenario 4: Recuperación de Contraseña</b> <br>
            <b>Dado</b> que un usuario olvida su contraseña y necesita restablecerla,<br>
            <b>Cuando</b> el usuario solicita una recuperación de contraseña enviando su correo electrónico a /api/auth/recover-password,<br>
            <b>Entonces</b> el sistema debe verificar si el correo electrónico está asociado con una cuenta existente,<br>
            Y si el correo electrónico es válido, enviar un correo electrónico al usuario con un enlace de restablecimiento de contraseña,<br>
            Y si el correo electrónico no está registrado, devolver un 404 Not Found indicando que no se encontró la cuenta.<br><br>
            <b>Escenario 5: Restablecimiento de Contraseña</b> <br>
            <b>Dado</b> que un usuario recibe un enlace de restablecimiento de contraseña y proporciona una nueva contraseña,<br>
            <b>Cuando</b> el usuario envía la nueva contraseña a /api/auth/reset-password junto con el token de restablecimiento obtenido del correo electrónico,<br>
            <b>Entonces</b> el sistema debe validar el token de restablecimiento,<br>
            Y si el token es válido, actualizar la contraseña del usuario en la base de datos y devolver un 200 OK indicando que la contraseña ha sido restablecida con éxito,<br>
            Y si el token no es válido o ha expirado, devolver un 400 Bad Request o 401 Unauthorized indicando el problema con el token de restablecimiento.<br><br>
            <b>Escenario 6: Cierre de Sesión</b> <br>
            <b>Dado</b> que un usuario desea cerrar su sesión activa,<br>
            <b>Cuando</b> el usuario envía una petición POST a /api/auth/logout,<br>
            <b>Entonces</b> el sistema debe invalidar el token JWT actual del usuario, impidiendo su uso futuro para autenticación,<br>
            Y devolver un 200 OK confirmando que el usuario ha cerrado sesión correctamente.
        </td>
        <td>
        </td>
</tr>
</tr>
    <tr>
         <td>US13</td>
        <td>Registro de Línea de Bus</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/bus-lines/register que permita el registro de una nueva línea de bus, para que los administradores de flota o dueños de empresas puedan añadir nuevas líneas al sistema de manera eficiente.</td>
        <td>
            <b>Escenario 1: Registro exitoso de una nueva línea de bus</b> <br>
            <b>Dado</b> que el administrador de flota tiene los datos necesarios para registrar una nueva línea de bus,<br>
            <b>Cuando</b> envía una petición POST a /api/bus-lines/register con los detalles de la línea (nombre, ruta, horarios, información del bus, etc.),<br>
            <b>Entonces</b> el sistema debe validar la información proporcionada,<br>
            <b>Y</b> si la información es válida, registrar la nueva línea de bus en la base de datos,<br>
            <b>Y</b> devolver un 201 Created con los detalles de la línea de bus registrada, incluyendo un identificador único asignado por el sistema.<br>
            <b>Escenario 2: Manejar intento de registro con datos incompletos o inválidos</b> <br>
            <b>Dado</b> que el administrador de flota envía una petición POST a /api/bus-lines/register con datos incompletos o inválidos para la línea de bus,<br>
            <b>Cuando</b> el sistema intenta validar la información,<br>
            <b>Entonces</b> el sistema debe identificar los campos que son inválidos o faltantes,<br>
            <b>Y</b> devolver un 400 Bad Request con un mensaje que detalle los problemas encontrados en los datos proporcionados.<br>
            <b>Escenario 3: Prevención de duplicados en el registro de líneas de bus</b> <br>
            <b>Dado</b> que el administrador de flota intenta registrar una línea de bus que ya existe en el sistema,<br>
            <b>Cuando</b> envía una petición POST a /api/bus-lines/register con datos que coinciden con una línea existente,<br>
            <b>Entonces</b> el sistema debe verificar la base de datos para prevenir registros duplicados,<br>
            <b>Y</b> si se encuentra un duplicado, devolver un 409 Conflict indicando que la línea de bus ya está registrada.<br>
            <b>Escenario 4: Confirmación de registro a usuarios interesados</b> <br>
            <b>Dado</b> que una nueva línea de bus ha sido registrada exitosamente,<br>
            <b>Cuando</b> el registro se completa,<br>
            <b>Entonces</b> el sistema debe notificar a los usuarios interesados (por ejemplo, mediante un servicio de mensajería o correo electrónico) sobre la nueva línea de bus disponible,<br>
            <b>Y</b> incluir en la notificación los detalles básicos de la nueva línea para fomentar su utilización.<br>
        </td>
        <td>
        </td>
</tr>
    <tr>
         <td>US14</td>
        <td>Suscripción Premium</td>
        <td>Como desarrollador, quiero implementar un endpoint /api/subscriptions/premium/purchase que gestione la compra de suscripciones premium por parte de los usuarios, para que los usuarios puedan acceder a funcionalidades avanzadas y mejorar su experiencia con la aplicación.</td>
        <td>
            <b>Escenario 1: Compra exitosa de una suscripción premium</b> <br>
            <b>Dado</b> que un usuario desea adquirir una suscripción premium y tiene los medios de pago válidos,<br>
            <b>Cuando</b> envía una petición POST a /api/subscriptions/premium/purchase con los detalles de su medio de pago y la duración deseada de la suscripción,<br>
            <b>Entonces</b> el sistema debe validar los datos de pago,<br>
            <b>Y</b> si los datos son válidos, procesar el pago a través del sistema de gestión de pagos,<br>
            <b>Y</b> registrar la suscripción premium en la cuenta del usuario, actualizando su estado a premium,<br>
            <b>Y</b> devolver un 200 OK con la confirmación de la compra y los detalles de la suscripción.<br>
            <b>Escenario 2: Fallo en la validación o procesamiento del pago</b> <br>
            <b>Dado</b> que un usuario intenta comprar una suscripción premium pero proporciona datos de pago inválidos o hay un problema en el procesamiento del pago,<br>
            <b>Cuando</b> envía una petición POST a /api/subscriptions/premium/purchase,<br>
            <b>Entonces</b> el sistema debe intentar validar y procesar el pago,<br>
            <b>Y</b> si hay un fallo, devolver un 400 Bad Request o 402 Payment Required con un mensaje detallando el problema específico encontrado.<br>
            <b>Escenario 3: Compra de suscripción premium cuando ya se posee una activa</b> <br>
            <b>Dado</b> que un usuario con una suscripción premium activa intenta comprar otra suscripción premium,<br>
            <b>Cuando</b> envía una petición POST a /api/subscriptions/premium/purchase,<br>
            <b>Entonces</b> el sistema debe verificar el estado de suscripción actual del usuario,<br>
            <b>Y</b> si ya posee una suscripción activa, devolver un 409 Conflict indicando que ya existe una suscripción premium activa y no se requiere una nueva compra.<br>
            <b>Escenario 5: Cancelación exitosa de una suscripción premium</b> <br>
            <b>Dado</b> que un usuario con una suscripción premium activa desea cancelarla,<br>
            <b>Cuando</b> envía una petición POST a /api/subscriptions/premium/cancel con su identificador de usuario,<br>
            <b>Entonces</b> el sistema debe verificar la existencia de una suscripción premium activa para ese usuario,<br>
            <b>Y</b> si encuentra una suscripción activa, procesar la cancelación, lo que implica actualizar el estado de la suscripción a ""cancelada"" y desactivar el acceso a las funcionalidades premium

</tr>





</table>

## 3.3 Impact Mapping

## 3.4 Product Backlog

<table border="2">
    <tr>
        <td>
           <p style = "font-weight: bold"><b># Orden</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>User Story ID</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Título</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Descripción</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Story Points (1/2/3/5/8)</b></p>
        </td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>

</table>

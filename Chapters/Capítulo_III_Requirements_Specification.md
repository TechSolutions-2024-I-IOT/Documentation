# Capítulo III: Requirements Specification

## 3.1 To-Be Scenario Mapping

### 3.1.1 Pasajeros

![To-Be Scenario Mapping de los Pasajeros](../Resources/maps/To-Be%20scenario%20pasajeros.jpg)

### 3.1.2 Empresa de transporte público

![To-Be Scenario Mapping de las Empresas de transporte público](../Resources/maps/To-be%20scenario%20empresas.jpg)

## 3.2 Epics

## 3.3 User Stories

<table border="2">
    <tr>
        <td>
           <p style = "font-weight: bold"><b>Story ID</b></p>
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
</table>

## 3.4 Impact Mapping

## 3.5 Product Backlog

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

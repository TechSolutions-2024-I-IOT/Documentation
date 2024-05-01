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
        <td>Redirección de la landing Page a tiendas de aplicaciones</td>
        <td>Como visitante del segmento pasajero, deseo dirigirme a la aplicación móvil correspondiente para descargarla en mi dispositivo móvil
        </td>
        <td>
            <b>Scenario 1: Aplicación publicada en Google Play</b> <br>
            <b>Dado</b> que el visitante del segmento pasajero se encuentra en la vista principal de la landing page<br>
            <b>Cuando</b> el visitante selecciona descargar la aplicación para Android<br>
            <b>Entonces</b> el visitante es redirigido a la página de descarga de la aplicación en Google Play<br><br> 
            <b>Scenario 2: Aplicación publicada en App Store</b> <br>
             <b>Dado</b> que el visitante del segmento pasajero se encuentra en la vista principal de la landing page<br>
             <b>Cuando</b> el visitante selecciona descargar la aplicación para iOS<br>
             <b>Entonces</b> el visitante es redirigido a la página de descarga de la aplicación en la App Store de iOS<br><br>
             <b>Scenario 3: Aplicación no publicada en la Play Store</b> <br>
            <b>Dado</b> que el visitante del segmento pasajero se encuentra en la vista principal de la landing page<br>
            <b>Y</b> la aplicación no se encuentra publicada en la Play Store<br>
            <b>Cuando</b> el visitante selecciona descargar la aplicación a través de Play Store<br>
            <b>Entonces</b> es redirigido a la página principal de Google Play<br><br>
            <b>Scenario 4: Aplicación no publicada en la App Store</b> <br>
            <b>Dado</b> que el visitante del segmento pasajero se encuentra en la vista principal de la landing page<br>
            <b>Y</b> la aplicación no se encuentra publicada en la App Store<br>
            <b>Cuando</b> el visitante selecciona descargar la aplicación a través de App Store<br>
            <b>Entonces</b> es redirigido a la página principal de la App Store de iOS<br>
        </td>
        <td></td>
    </tr>
<tr>
    <td>US02</td>
        <td>Redirección de la landing Page a la aplicación web</td>
        <td>Como visitante del segmento encargado de flota de autobuses, deseo ingresar a la aplicación web mediante la landing page para acceder a el contenido que ofrece la aplicación</td>
        <td>
            <b>Scenario 1: Redirección exitosa a la aplicación web de ChapaTuBus</b> <br>
            <b>Dado</b> que el visitante del segmento encargado de la flota de autobuses se encuentra en la sección de empresa de la landing page<br>
            <b>Cuando</b> el visitante decide redirigirse a la aplicación web<br>
            <b>Entonces</b> el visitante es redirigido a la aplicación web de ChapaTuBus<br><br>
        </td>
        <td></td>
    </tr>
<tr>
        <td>US03</td>
        <td>Envío de mensaje a través de un formulario de contacto</td>
        <td>Como visitante de cualquier segmento, deseo enviar un mensaje a los desarrolladores para enviar sugerencias, quejas ,mensajes u otro motivo que yo desee</td>
        <td>
            <b>Scenario 1: Enviar el formulario con los campos correctamentes llenados</b> <br>
            <b>Dado</b> que el visitante ha completado los campos de nombre,apellido,correo electrónico y mensaje correctamente<br>
            <b>Cuando</b> los campos son validados<br>
            <b>Y</b> el visitante ordena enviar el formulario<br>
            <b>Entonces</b> el formulario es enviado correctamente al correo electrónico de ChapaTuBus<br><br>
            <b>Scenario 2: Enviar el formulario con un correo electrónico no válido</b> <br>
            <b>Dado</b> El visitante se encuentra en el formulario de contacto<br>
            <b>Y</b> ingresa un formato de coreo electrónico no válido<br>
            <b>Cuando</b> el correo electrónico es revisado<br>
            <b>Y</b> el visitante ordena enviar el formulario<br>
            <b>Entonces</b> el formulario no es enviado<br>
            <b>Y</b> se le muestra un mensaje de error indicando que el correo electrónico no es válido<br><br>
            <b>Scenario 3: Envío fallido por campos incompletos en el formulario</b> <br>
            <b>Dado</b> que el visitante se encuentra en la sección de contacto de la landing page<br>
            <b>Cuando</b> el visitante completa parcialmente los campos requeridos en el formulario de contacto<br>
            <b>Y</b> ordena enviar el formulario<br>
            <b>Entonces</b> se muestra un mensaje de error indicando los campos que aún necesitan ser completados<br><br>
            <b>Scenario 4: Envío del formulario con información vacía</b> <br>
            <b>Dado</b> que el visitante se encuentra en la sección de contacto de la landing page<br>
            <b>Cuando</b> el visitante deja en blanco uno o más campos del formulario de contacto<br>
            <b>Y</b> ordena enviar el formulario<br>
            <b>Entonces</b> se muestra un mensaje de error indicando que debe rellenar los campos vacíos<br><br>
            <b>Scenario 5: Redirección a otra sección tras el envío exitoso</b> <br>
            <b>Dado</b> que el visitante ha enviado con éxito el formulario de contacto<br>
            <b>Cuando</b> el visitante recibe la confirmación del envío exitoso<br>
            <b>Entonces</b> es redirigido automáticamente a una página de agradecimiento o a otra sección relevante de la landing page<br>
        </td>
        <td></td>
    </tr>
<tr>
        <td>US04</td>
        <td>Conocimiento del Equipo desarrollador de la aplicación</td>
        <td> Como visitante, deseo visualizar al equipo que está desarrollando la aplicación para tener una mayor confianza en las personas detrás del proyecto.</td>
        <td>
            <b>Scenario 1: Navegación a la sección de "Nuestro Equipo"</b> <br>
            <b>Dado</b> que el visitante se encuentra en la página principal de la Landing Page<br>
            <b>Cuando</b> el visitante se desplaza hasta la sección de "Nuestro Equipo" <br>
            <b>Entonces</b> el visitante visualiza al equipo colaborador del proyecto.<br><br>
        </td>
        <td></td>
    </tr>
<tr>
        <td>US05</td>
        <td>Sección de Preguntas Frecuentes</td>
        <td>Como visitante, deseo acceder a la sección de Preguntas Frecuentes para resolver mis inquietudes sobre el servicio ofrecido.</td>
        <td>
        <b>Scenario 1: Navegación a la sección de Preguntas Frecuentes</b> <br>
        <b>Dado</b> que el visitante se encuentra en la página principal de la Landing Page<br>
        <b>Cuando</b> el visitante se desplaza hasta la sección de Preguntas Frecuentes<br>
        <b>Entonces</b> el visitante encuentra la sección de Preguntas Frecuentes.<br><br>
        <b>Scenario 2: Acceso a preguntas y respuestas específicas</b> <br>
        <b>Dado</b> que el visitante se encuentra en la sección de Preguntas Frecuentes<br>
        <b>Cuando</b> el visitante selecciona una pregunta de la lista<br>
        <b>Entonces</b> se despliega la respuesta correspondiente de manera clara y concisa.<br>
</td>
        <td></td>
    </tr>
<tr>
        <td>US06</td>
        <td>Navegación y Contenido Informativo en el Footer</td>
        <td>Como visitante ,deseo tener acceso fácil y claro a información relevante y enlaces útiles en el footer para acceder rápidamente a secciones importantes de la Landing Page.</td>
        <td>
    <b>Scenario 1: Acceso a información relevante en el footer</b> <br>
    <b>Dado</b> que el visitante se encuentra en cualquier página del sitio web<br>
    <b>Cuando</b> el visitante desplaza hacia abajo hasta el footer<br>
    <b>Entonces</b> el visitante encuentra información relevante y enlaces útiles claramente organizados y visibles.<br><br>
    <b>Scenario 2: Enlaces a secciones importantes en el footer</b> <br>
    <b>Dado</b> que el visitante está en el footer <br>
    <b>Cuando</b> el visitante busca enlaces a secciones importantes como "Inicio", "Nosotros" y "Contacto"<br>
    <b>Entonces</b> el visitante encuentra estos enlaces de forma clara y directa.<br><br>
    <b>Scenario 3: Acceso rápido a redes sociales</b> <br>
    <b>Dado</b> que el visitante está en el footer del sitio web<br>
    <b>Cuando</b> el visitante selecciona algún ícono de las redes sociales disponibles de ChapaTuBus<br>
    <b>Entonces</b> el visitante es redirigido a la red social elegida<br>
</td>
    </tr>
<tr>
        <td>US07</td>
        <td>Diseño Responsivo de la Landing Page</td>
        <td>Como visitante, deseo que la página se adapte correctamente a diferentes dispositivos y tamaños de pantalla (como móviles, tablets y desktops), para una experiencia de usuario óptima y consistente en cualquier dispositivo que utilice.</td>
        <td>
    <b>Scenario 1: Visualización adecuada en dispositivos móviles</b> <br>
    <b>Dado</b> que el visitante accede a la landing page desde un dispositivo móvil<br>
    <b>Cuando</b> el visitante visualiza la página<br>
    <b>Entonces</b> la página se adapta correctamente al tamaño y resolución de pantalla del dispositivo móvil, manteniendo la legibilidad y la funcionalidad de todos los elementos.<br><br>
    <b>Scenario 2: Visualización adecuada en tablets</b> <br>
    <b>Dado</b> que el visitante accede a la landing page desde una tablet<br>
    <b>Cuando</b> el visitante visualiza la página<br>
    <b>Entonces</b> la página se adapta correctamente al tamaño y resolución de pantalla de la tablet, asegurando que todos los elementos y contenidos sean fácilmente accesibles y legibles.<br><br>
    <b>Scenario 3: Visualización adecuada en desktops</b> <br>
    <b>Dado</b> que el visitante accede a la landing page desde un ordenador de escritorio<br>
    <b>Cuando</b> el visitante visualiza la página<br>
    <b>Entonces</b> la página se presenta de forma óptima, aprovechando el espacio de la pantalla y manteniendo una distribución equilibrada de los elementos.<br><br>
    <b>Scenario 4: Consistencia en la experiencia de usuario</b> <br>
    <b>Dado</b> que el visitante navega por la landing page en diferentes dispositivos<br>
    <b>Cuando</b> el visitante cambia entre dispositivos (móvil, tablet, desktop)<br>
    <b>Entonces</b> la experiencia de usuario es consistente en todos ellos, con una navegación fluida y una presentación coherente de la información y diseño.<br><br>
    <b>Scenario 5: Funcionalidad de los elementos interactivos en todos los dispositivos</b> <br>
    <b>Dado</b> que el visitante interactúa con los elementos de la landing page<br>
    <b>Cuando</b> el visitante realiza acciones como clics, desplazamientos o interacciones táctiles<br>
    <b>Entonces</b> todos los elementos interactivos funcionan correctamente en todos los dispositivos, garantizando una experiencia de usuario sin errores ni fallos.<br>
</td>
    </tr>
<tr>
        <td>US08</td>
        <td>Incorporación de Testimonios en la Landing Page</td>
        <td>Como visitante, deseo tener acceso a testimonios reales de usuarios o clientes para conocer experiencias positivas y comentarios sobre el servicio ofrecido.</td>
        <td>
        <b>Scenario 1: Visualización de testimonios en la landing page</b> <br>
        <b>Dado</b> que el visitante accede a la landing page<br>
        <b>Cuando</b> se desplaza hasta la sección de testimonios<br>
        <b>Entonces</b> se muestran testimonios reales de usuarios o clientes, con nombres, fotos (si están disponibles) y comentarios sobre su experiencia positiva con el servicio.<br><br>
        <b>Scenario 2: Navegación entre testimonios</b> <br>
        <b>Dado</b> que el visitante visualiza múltiples testimonios en la sección de testimonios<br>
        <b>Cuando</b> el visitante utiliza controles de navegación <br>
        <b>Entonces</b> el visitante puede desplazarse fácilmente entre diferentes testimonios para leer las experiencias de distintos usuarios o clientes.<br>
        </td>
    </tr>
<tr>
        <td>US09</td>
        <td>Sección de Características del producto</td>
        <td>Como visitante, quiero tener una sección claramente definida que muestre las características principales del producto o servicio, para entender rápidamente sus funcionalidades y beneficios.</td>
        <td>
    <b>Scenario 1: Visualización de la sección de características</b> <br>
    <b>Dado</b> que el visitante accede a la landing page<br>
    <b>Cuando</b> el visitante busca la sección de características del producto<br>
    <b>Entonces</b> se muestra una sección claramente definida con las características principales del producto o servicio, presentadas de forma organizada y fácil de leer.<br><br>
    <b>Scenario 2: Detalle de las características</b> <br>
    <b>Dado</b> que el visitante visualiza la sección de características del producto<br>
    <b>Cuando</b> el visitante explora cada característica listada<br>
    <b>Entonces</b> se proporciona una descripción detallada de cada característica, explicando sus funcionalidades y beneficios de manera comprensible.<br><br>
    <b>Scenario 3: Iconografía y diseño</b> <br>
    <b>Dado</b> que el visitante visualiza la sección de características del producto<br>
    <b>Cuando</b> el visitante observa la presentación visual de las características (como iconos, imágenes o gráficos)<br>
    <b>Entonces</b> la iconografía y el diseño utilizados son claros, coherentes y facilitan la comprensión rápida de las funcionalidades y beneficios del producto.<br>
</td>
    </tr>
<tr>
        <td>US10</td>
        <td>Sección de Inicio de la Landing Page</td>
        <td>Como visitante , deseo ser recibido con una Hero Section impactante y atractiva en la Landing Page, para que me proporcione una visión clara y concisa del valor y propósito del producto o servicio, capturando mi interés y motivándome a explorar más sobre lo que se ofrece.</td>
        <td>
    <b>Scenario 1: Visualización de la Hero Section</b> <br>
    <b>Dado</b> que el visitante accede a la landing page<br>
    <b>Cuando</b> el visitante carga la página inicial<br>
    <b>Entonces</b> se muestra una Hero Section impactante y atractiva que ocupa un lugar prominente en la página.<br><br>
    <b>Scenario 2: Contenido de la Hero Section</b> <br>
    <b>Dado</b> que el visitante visualiza la Hero Section<br>
    <b>Cuando</b> el visitante lee el contenido presentado<br>
    <b>Entonces</b> el contenido comunica claramente el valor y propósito del producto o servicio, proporcionando una visión concisa y atractiva de lo que se ofrece.<br>
</td>
        <td></td>
    </tr>
<tr>
         <td>US11</td>
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
         <td>US12</td>
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
         <td>US13</td>
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
         <td>US14</td>
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
         <td>US15</td>
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
         <td>US16</td>
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
         <td>US17</td>
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
<tr>
         <td>US18</td>
        <td> Visualizar gráfico de línea con el tiempo de pulso de los conductores</td>
        <td>Como representante de una empresa de transporte, quiero ver un gráfico de línea con el tiempo de pulso de mis conductores en tiempo real, para poder identificar a los que puedan estar bajo estrés o con problemas de salud</td>
        <td>
    <b>Escenario 1: Visualización correcta del gráfico</b> <br>
    <b>Dado</b> que un representante de la empresa de transporte ha iniciado sesión en la aplicación<br>
    <b>Y</b> ha seleccionado la opción "Visualizar gráfico de línea de pulso de conductores"<br>
    <b>Cuando</b> la aplicación carga la información del pulso de los conductores<br>
    <b>Entonces</b> se muestra un gráfico de línea con el tiempo de pulso de cada conductor en tiempo real<br>
    <b>Y</b> el gráfico se actualiza en tiempo real a medida que cambia el tiempo de pulso de los conductores.<br><br>
    <b>Escenario 2: Error al visualizar el gráfico</b> <br>
    <b>Dado</b> que un representante de la empresa intenta acceder a la información del tiempo de pulso con una conexión a internet deficiente<br>
    <b>Cuando</b> la aplicación intenta cargar la información<br>
    <b>Entonces</b> se muestra un mensaje informativo que indica la causa del problema (ej. "No se pudo conectar al servidor. Intente nuevamente más tarde").<br>
    <b>Y</b> se ofrece al usuario la opción de volver a intentar cargar la información.<br><br>
    <b>Escenario 3: Visualización de zonas de pulso</b> <br>
    <b>Dado</b> que un representante de la empresa desea ver zonas de pulso que indiquen posibles estados de salud o estrés<br>
    <b>Cuando</b> se selecciona la opción "Ver zonas de pulso"<br>
    <b>Entonces</b> se superponen al gráfico de línea zonas de colores que indican diferentes estados de salud o estrés (ej. verde para normal, amarillo para elevado, rojo para alto).<br>
</td>
        <td>
        </td>
</tr>
<tr>
         <td>US19</td>
        <td>Registrar empresa de transporte</td>
        <td>Como representante de una empresa de transporte, quiero poder registrar mi empresa en el sistema</td>
        <td>
    <b>Escenario 1: Registro correcto de la empresa</b> <br>
    <b>Dado</b> que un representante de la empresa de transporte ha accedido al portal de registro del sistema<br>
    <b>Cuando</b> el representante introduce la información completa y válida de la empresa en el formulario de registro<br>
    <b>Entonces</b> se valida la información de la empresa en tiempo real (ej. mediante consulta a bases de datos públicas)<br>
    <b>Y</b> se crea una cuenta para la empresa en el sistema<br><br>
    <b>Escenario 2: Error al registrar la empresa</b> <br>
    <b>Dado</b> que un representante introduce información incompleta o inválida en el formulario de registro<br>
    <b>Cuando</b> el sistema detecta un error en la información proporcionada<br>
    <b>Entonces</b> se muestra un mensaje informativo al representante indicando el error y cómo corregirlo<br>
    <b>Y</b> se ofrece al representante la opción de volver a intentar registrar la empresa<br>
</td>
        <td>
        </td>    
</tr>
<tr>
         <td>US20</td>
        <td>Registrar línea de transporte</td>
        <td>Como representante de una empresa de transporte, quiero poder registrar una línea de transporte en el sistema
        </td>
        <td>
    <b>Escenario 1: Registro correcto de la línea de transporte</b> <br>
    <b>Dado</b> que un representante de la empresa de transporte ha iniciado sesión en el sistema<br>
    <b>Y</b> ha seleccionado la opción "Registrar línea de transporte"<br>
    <b>Cuando</b> el representante introduce la información completa y válida de la línea de transporte en el formulario de registro<br>
    <b>Entonces</b> se valida la información<br>
    <b>Y</b> se crea una entrada para la línea de transporte en el sistema<br>
    <b>Y</b> se informa al representante del éxito del registro<br><br>
    <b>Escenario 2: Error al registrar la línea de transporte</b> <br>
    <b>Dado</b> que un representante introduce información incompleta o inválida en el formulario de registro<br>
    <b>Cuando</b> el sistema detecta un error en la información proporcionada<br>
    <b>Entonces</b> se muestra un mensaje informativo al representante indicando el error y cómo corregirlo<br>
    <b>Y</b> se ofrece al representante la opción de volver a intentar registrar la línea de transporte<br><br>
    <b>Escenario 3: Validación de datos</b> <br>
    <b>Dado</b> que el sistema necesita verificar la información de la línea de transporte<br>
    <b>Cuando</b> el representante ingresa la información de la línea de transporte en el formulario de registro<br>
    <b>Entonces</b> el sistema valida la información en tiempo real mediante solicitud de documentación adicional (ej. permisos de operación)<br>
    <b>Y</b> se informa al representante el estado de la validación<br><br>
    <b>Escenario 4: Configuración de la línea de transporte</b> <br>
    <b>Dado</b> que la línea de transporte ha completado el registro<br>
    <b>Cuando</b> el representante accede a la configuración de la línea de transporte<br>
    <b>Entonces</b> la empresa puede configurar la información de la línea de transporte, como nombre de la línea, ruta, horario de servicio, tarifas y paradas<br>
</td>
<td>
        </td>    
</tr>
<tr>
         <td>US21</td>
        <td>Visualizar recorrido de una línea de bus</td>
        <td>Como usuario pasajero, quiero poder buscar y visualizar las rutas de las líneas de autobús, para tener una idea clara de su trayecto y poder planificar mis viajes de manera eficiente.</td>
        <td>
    <b>Scenario 1: Consulta de la línea del bus</b> <br>
    <b>Dado</b> que el usuario quiere conocer la ruta del bus<br>
    <b>Cuando</b> ingresé el nombre de una línea de autobús<br>
    <b>Entonces</b> ve los detalles de la línea del bus, incluyendo paraderos y horario, considerando su ubicación y una dirección de ruta por defecto se mostrará el paradero del bus más cercano.<br><br>
    <b>Scenario 2: Consulta de líneas cercanas</b> <br>
    <b>Dado</b> que el usuario quiere ver las rutas de los buses cercanos sin tener un destino fijo<br>
    <b>Cuando</b> quiera verlos, serán recomendados considerando su ubicación<br>
    <b>Entonces</b> se mostrarán las rutas de los buses que pasen cerca de su posición actual<br><br>
    <b>Scenario 3: Dirección equivocada</b> <br>
    <b>Dado</b> que la aplicación asumió el sentido contrario al destino del usuario pasajero al mostrar los paraderos<br>
    <b>Cuando</b> cambie la dirección de los paraderos<br>
    <b>Entonces</b> la aplicación le mostrará el bus correspondiente a la dirección que desea<br>
</td>
        <td>
        </td>
</tr>
<tr>
         <td>US22</td>
        <td>Distancia del bus</td>
        <td>Como usuario pasajero, quiero conocer la distancia exacta y el tiempo estimado de llegada del próximo bus, para poder gestionar mi tiempo de espera y llegar a tiempo a mis destinos.</td>
        <td>
    <b>Scenario 1: Ubicación precisa del siguiente bus</b> <br>
    <b>Dado</b> que el usuario pasajero observa la ubicación del bus sin precisión<br>
    <b>Cuando</b> seleccione más detalles<br>
    <b>Entonces</b> la aplicación muestra un mapa de la ubicación del bus, su aforo y su tiempo estimado de llegada a su ubicación.<br><br>
    <b>Scenario 2: Bus fuera de servicio</b> <br>
    <b>Dado</b> que el usuario eligió una línea que actualmente no se encuentra circulando<br>
    <b>Cuando</b> quiera ver a detalle la ubicación del bus<br>
    <b>Entonces</b> verá el horario de circulación de la línea<br><br>
    <b>Scenario 3: Detalles de buses próximos</b> <br>
    <b>Dado</b> que el usuario desea ver detalles de los siguientes buses, no solo el más cercano<br>
    <b>Cuando</b> [acción del usuario]<br>
    <b>Entonces</b> [resultado esperado]<br>
</td>
        <td>
        </td>    
</tr>
<tr>
         <td>US23</td>
        <td>Lista de próximos autobuses</td>
        <td>Como usuario pasajero, quiero tener acceso a información sobre los próximos buses de una misma línea, para poder tomar decisiones informadas y optimizar mi experiencia.</td>
        <td>
    <b>Scenario 1: Detalles de los próximos buses</b> <br>
    <b>Dado</b> que un usuario premium ha seleccionado una línea de bus<br>
    <b>Cuando</b> seleccione la opción para ver los siguientes buses,<br>
    <b>Entonces</b> puede visualizar el aforo, el paradero más reciente y el tiempo de llegada aproximado a su posición de los próximos buses.<br><br>
    <b>Scenario 2: Funcionalidad bloqueada</b> <br>
    <b>Dado</b> que un usuario no premium ha seleccionado una línea de bus<br>
    <b>Cuando</b> seleccione la opción para ver los siguientes buses<br>
    <b>Entonces</b> será informado de que para utilizar dicha función necesita cambiar de plan.<br>
</td>
        <td>
        </td>    
</tr>
<tr>
         <td>US24</td>
        <td>Guardar líneas de transporte favoritas</td>
        <td>Como usuario pasajero, quiero guardar mís líneas favoritas para no buscarlas continuamente</td><td>
    <b>Scenario 1: Añadir líneas de bus a favoritos</b> <br>
    <b>Dado</b> que el usuario pasajero está viendo la información de una línea<br>
    <b>Cuando</b> la agregue a favoritos<br>
    <b>Entonces</b> esa línea de bus se guarda en su lista de favoritos.<br><br>
    <b>Scenario 2: Acceso rápido a líneas de bus favoritas</b> <br>
    <b>Dado</b> que el usuario pasajero quiere ver una línea de bus favorita<br>
    <b>Cuando</b> seleccione sus favoritos<br>
    <b>Entonces</b> verá una lista de todas las líneas de bus que ha añadido a favoritos y seleccionará cualquiera de ellas para ver su información detallada.<br>
</td>
        <td>
        </td>    
</tr>
<tr>
         <td>US25</td>
        <td>Recibir notificaciones sobre líneas de bus favoritas</td>
        <td>Como usuario pasajero, quiero recibir notificaciones sobre las líneas de bus que he añadido a mis favoritos, para estar al tanto de cualquier cambio o actualización importante. </td>
        <td>
    <b>Scenario 1: Notificaciones para líneas de bus favoritas</b> <br>
    <b>Dado</b> que el usuario pasajero ha añadido líneas de bus a favoritos<br>
    <b>Cuando</b> active las notificaciones para una línea de bus<br>
    <b>Entonces</b> recibe notificaciones sobre cualquier cambio o actualización importante relacionada con esa línea de bus.<br><br>
    <b>Scenario 2: Ver notificaciones de los favoritos</b> <br>
    <b>Dado</b> que el usuario pasajero ha activado las notificaciones para varias líneas de bus en favoritos<br>
    <b>Cuando</b> abre la sección de favoritos<br>
    <b>Entonces</b> ve una lista de todas las notificaciones que ha recibido.<br>
</td>
        <td>
        </td>    
</tr>

<tr><td colspan="5"> <b>Technical Stories</b> <td></tr>


<tr>
         <td>TS01</td>
        <td>Listado de Líneas de Buses</td>
        <td>Como desarrollador, quiero obtener un listado de todas las líneas de buses mediante un API, para que la aplicación móvil pueda mostrarlas en la sección de explorar.</td>
        <td>
            <b>Scenario 1: Obtener el listado de líneas de buses exitosamente</b> <br>
            <b>Dado</b> que existen líneas de buses registradas en el sistema,<br>
            <b>Y</b> el EndPoint "/buses" está disponible
            <b>Cuando</b> una petición GET es enviada,<br>
            <b>Entonces</b> una respuesta es recibida con estado 200 OK <br>
            <b>Y</b> un listado de recursos Buses es incluída en el ReponseBody.<br>
            <b>Escenario 2: Obtener el listado de líneas de buses sin registros previos</b> <br>
            <b>Dado</b> que el Endpoint "/buses" está disponible,<br>  
            <b>Y</b> no hay líneas de buses registradas en el sistema <br>
            <b>Cuando</b> el usuario hace una petición GET,<br>
            <b>Entonces</b> el sistema debe devolver un 200 OK con un array vacío lo cual indica que no hay líneas disponibles.<br><br>
            <b>Escenario 3: Obtener el listado de buses con el endpoint no disponible</b> <br>
            <b>Dado</b> que el endpoint "/buses" no se encuentra disponible<br>
            <b>Cuando</b> el usuario hace una petición GET,<br>
            <b>Entonces</b> una respuesta es recibida con un 500 Internal Server Error para indicar que algo salió mal en el proceso de recuperación de datos.
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS02</td>
        <td>Búsqueda de Líneas de Bus</td>
        <td>Como desarrollador, quiero buscar líneas de bus por nombre a través del API, para que esté disponible para crear funciones para mi aplicación
        <td>
            <b>Escenario 1: Búsqueda exitosa mediante el nombre</b> <br>
            <b>Dado</b> que el endpoint "/itinerary" se encuentra disponible<br>
            <b>Cuando</b> una solicitud GET es enviada con el valor del nombre a buscar,<br>
            <b>Entonces</b> una respuesta lista de tipo Itinerary es recibida con un estado 200 OK de acuerdo a los nombres coincidientes<br><br>
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
<tr>
         <td>TS03</td>
        <td>Añadir Líneas de Buses como favoritos a través del RESTful API</td>
        <td>Como desarrollador, quiero añadir líneas de buses como favoritas a través del API para que pueda crear funciones para mi aplicación.</td>
        <td>
            <b>Escenario 1: Añadir una línea de bus a favoritos</b> <br>
            <b>Dado</b> que el endpoint "/api/favorites" se encuentra disponible<br>
            <b>Cuando</b> una solicitud POST es enviada con el ID de la línea de bus<br>
            <b>Entonces</b> una respuesta es recibida con estado 201<br>
            <b>Escenario 2: Eliminar una línea de bus de favoritos</b> <br>
            <b>Dado</b> que el endpoint "/api/favorites" se encuentra disponible<br>
            <b>Cuando</b> se envía una solicitud DELETE con el ID de la línea de bus,<br>
            <b>Entonces</b> se recibe una respuesta con estado 200 OK con una confirmación de la acción.
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS04</td>
        <td>Listado de Paraderos de una Línea de Bus a través de la RESTful API</td>
        <td>Como desarrollador, quiero obtener la información de la lista de paraderos de una compañía de transporte específica a través del API, para que pueda realizar features para mi aplicación.</td>
        <td>
            <b>Escenario 1: Obtener la lista de paraderos de una compañía de transporte</b> <br>
            <b>Dado</b> que el endpoint  "/api/bus-lines/{lineId}/stops" se encuentra disponible,<br>
            <b>Cuando</b> una petición GET es enviada con un ID de línea de bus válido,<br>
            <b>Entonces</b> se recibe una respuesta con status 200 OK <br>
            <b>Y</b> un array de objetos es incluído en el ResponseBody, donde cada objeto contiene al menos el nombre y ubicación del paradero.<br><br>
            <b>Escenario 2: Manejar la solicitud con un ID de línea de bus no existente</b> <br>
            <b>Dado</b> el endpoint "/api/bus-lines/{lineId}/stops" está disponible<br>
            <b>Cuando</b> una solicitud GET es enviado junto a un inexistente ID de linea de bus,<br>
            <b>Entonces</b> una respuesta es recibida con estado 404.<br>
            <b>Y</b> un mensaje es incluída en el Response Body, con el valor de "Línea de Bus no encontrada"<br><br>
        </td>
        <td>
        </td>
</tr>
<tr>
    <td>TS05</td>
        <td>Datos de Paraderos y Buses en Tiempo Real a través de la Restful API</td>
        <td>Como desarrollador, quiero obtener datos en tiempo real de paraderos y buses para una línea específica para que los usuarios de la aplicación móvil puedan ver la ubicación del bus en el mapa, el nombre del paradero, y el tiempo estimado de llegada.</td>
        <td>
            <b>Escenario 1: Obtener información en tiempo real de paraderos para una línea de bus</b> <br>
            <b>Dado</b> que el endpoint "/api/real-time/{lineId}" está disponible<br>
            <b>Cuando</b> se envía una petición GET con un ID de línea de bus válido<br>
            <b>Entonces</b> se recibe una respuesta con el estado 200 OK<br>
            <b>Y</b> Y el cuerpo de la respuesta incluye un array de objetos que representan los paraderos, donde cada objeto contiene el nombre del paradero, la ubicación geográfica, y datos del tiempo estimado de llegada del próximo bus basado en su ubicación actual<br><br>
            <b>Escenario 2: Obtener información de ubicación del bus para un paradero seleccionado</b> <br>
            <b>Dado</b> que el endpoint "/api/real-time/{lineId}/stops/{stopId}" se encuentra disponible<br>
            <b>Y</b> existe información en tiempo real disponible<br>
            <b>Cuando</b> se envía una petición GET <br>
            <b>Entonces</b> Entonces se calcula el tiempo estimado de llegada basado en la velocidad actual del bus y las condiciones del tráfico<br>
            <b>Y</b> Y se devuelve una respuesta 200 OK con un objeto que incluye la ubicación actual del bus y el tiempo estimado de llegada al paradero seleccionado<br><br>
            <b>Escenario 3: Manejar la ausencia de datos en tiempo real</b> <br>
            <b>Dado</b> que cualquiera de los endpoints anteriores no presentan datos en tiempo real disponibles debido a un fallo de sensor o falta de conectividad,<br>
            <b>Cuando</b> se envía una petición GET a<br>
            <b>Entonces</b> se debe devolver una respuesta 502 Bad Gateway<br>
            <b>Y</b> un mensaje es incluído con la respuesta, con el valor de "Información en tiempo real no está disponible".
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS06</td>
        <td>Información del aforo en Tiempo Real de Buses a través de la RestfulAPI</td>
        <td>Como desarrollador, quiero obtener el aforo en tiempo real de un bus específico, para que los usuarios puedan saber cuántas personas hay en el bus antes de que llegue al paradero.</td>
        <td>
            <b>Escenario 1: Obtener el aforo en tiempo real de un bus específico</b> <br>
            <b>Dado</b> que existen cámaras instaladas en un bus específico que están funcionando y enviando datos<br>
            <b>Y</b> el endpoint "/api/real-time/bus-capacity/{busId}" se encuentra disponible <br>
            <b>Cuando</b> se realiza una petición GET con un ID de bus válido,<br>
            <b>Entonces</b> se debe consultar la última información de aforo recibida de los sensores<br>
            <b>Y</b> devolver una respuesta con el estado 200 OK indicando el número actual de pasajeros en el bus.<br><br>
            <b>Escenario 2: Manejar buses sin datos de aforo debido a sensores desconectados o en error</b> <br>
            <b>Dado</b> que los sensores de un bus no están enviando datos debido a una desconexión o mal funcionamiento,<br>
            <b>Y</b> el endpoint "/api/real-time/bus-capacity/{busId}" se encuentra disponible<br>
            <b>Cuando</b> el desarrollador hace una petición GET<br>
            <b>Entonces</b> se devuelve una respuesta de estado 503 Service Unavailable <br>
            <b>Y</b> un mensaje en el response body con el valor "La información de aforo no está disponible temporalmente".<br><br>
            <b>Escenario 3: Manejar ID de bus inválido o inexistente</b> <br>
            <b>Dado</b> que se envía una petición con un ID de bus inválido o inexistente,<br>
            <b>Y</b> el endpoint "/api/real-time/aforo/{busId}" se encuentra disponible <br>
            <b>Cuando</b> se realiza una petición GET<br>
            <b>Y</b> se valida el ID del bus
            <b>Entonces</b> se recibe una respuesta de tipo 404 not found en el caso de que no exista<br>
            <b>Y</b> en el caso de que el ID sea inválida, debe devolver un 400 Bad Request<br><br>
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS07</td>
        <td>Datos Históricos de Paraderos por Fecha a través de la RestFull API</td>
        <td>Como desarrollador, quiero obtener los datos históricos de los paraderos para una fecha específica, para que el dashboard de la aplicación web pueda mostrar un listado de paraderos ordenados según la cantidad de personas que subieron en cada uno en dicha fecha.</td>
        <td>
            <b>Escenario 1: Obtener datos históricos de paraderos por fecha específica</b> <br>
            <b>Dado</b> que el endpoint "/api/historical/stops/{date}" se encuentra disponible,<br>
            <b>Y</b> que existen registros históricos para la fecha proporcionada,<br>
            <b>Cuando</b> una petición GET es envíada junto a una fecha en formato YYYY-MM-DD,<br>
            <b>Entonces</b> se recibe una respuesta con status 200 OK,<br>
            <b>Y</b> un array de objetos que representan los paraderos es incluído dentro de la respuesta, donde cada objeto contiene el nombre del paradero y el número total de personas que subieron en ese paradero ese día.<br><br>
            <b>Escenario 2: Manejar una fecha sin registros históricos</b> <br>
            <b>Dado</b> que el endpoint "/api/historical/stops/{date}" se encuentra disponible,<br>
            <b>Y</b> que no existen registros históricos para la fecha proporcionada,<br>
            <b>Cuando</b> se realiza una petición GET <br>
            <b>Entonces</b> se recibe una respuesta 204 No Content para indicar que no hay datos disponibles para esa fecha.<br><br>
            <b>Escenario 3: Manejar formato de fecha incorrecto en la solicitud</b> <br>
            <b>Dado</b> que el endpoint "/api/historical/stops/{date}" se encuentra disponible,<br>
            <b>Cuando</b> hace una petición GET a /api/historical/stops/{date},<br>\
            <b>Y</b> se envía una fecha en un formato incorrecto o inválido,<br>
            <b>Entonces</b> se recibe una respuesta tipo 400 Bad Request <br>
            <b>Y</b> un mensaje es incluído en la respuesta, con el valor "Formato de la fecha no válido" <br><br>
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS08</td>
        <td>Histograma de Afluencia por Paradero</td>
        <td>Como desarrollador, quiero obtener los datos de afluencia de pasajeros para un paradero específico, para que el dashboard de la aplicación web pueda mostrar un histograma de la hora más concurrida en dicho paradero.</td>
        <td>
            <b>Escenario 1: Obtener datos de afluencia por paradero</b> <br>
            <b>Dado</b> que el endpoint "/api/stops/{stopId}/passenger-flow," se encuentra disponible<br>
            <b>Y</b> que se han recopilado datos de afluencia para un paradero específico durante el día,<br>
            <b>Cuando</b> una solicitud GET es envíada <br>
            <b>Entonces</b> se recibe una respuesta con estado 200 OK,<br>
            <b>Y</b> un objeto que contenga una serie de pares clave-valor es inclúido en la respuesta, donde cada clave es un rango horario y cada valor es el número total de pasajeros que subieron en ese paradero durante ese rango.<br><br>
            <b>Escenario 2: Manejar un paradero sin datos de afluencia</b> <br>
            <b>Dado</b> que el endpoint "/api/stops/{stopId}/passenger-flow," se encuentra disponible<br>
            <b>Y</b> hay datos de afluencia disponibles para el paradero seleccionado,<br>
            <b>Cuando</b> la petición GET es enviada <br>
            <b>Entonces</b> se recibe una respuesta 204 No Content para indicar que no hay datos disponibles para ese paradero.<br><br>
            <b>Escenario 3: Manejar una solicitud con ID de paradero inválido o inexistente</b> <br>
            <b>Dado</b> que el endpoint "/api/stops/{stopId}/passenger-flow," se encuentra disponible<br>
            <b>Cuando</b> se envía una petición GET junto con el ID de un paradero<br>
            <b>Y</b> el ID del paradero no existe o es inválido<br>
            <b>Entonces</b> se recibe una respuesta 404 Not Found <br>
            <b>Y un mensaje es incluído en la respuesta, con el valor de "Paradero no registrado o ID incorrecto".</b> 
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS09</td>
        <td>Visualización de Datos de Conductores y Buses</td>
        <td>Como desarrollador, quiero obtener una lista de todos los conductores con sus datos personales y detalles del bus que manejan, para que la aplicación web pueda mostrar esta información en el dashboard y permita a los administradores de flota o dueños de empresas monitorear y gestionar su personal y vehículos de manera efectiva.</td>
        <td>
            <b>Escenario 1: Obtener la lista de conductores y los buses que manejan</b> <br>
            <b>Dado</b> que el endpoint "/api/drivers-info" se encuentra disponible<br>
            <b>Y</b> que existen registros de conductores y buses en la base de datos,<br>
            <b>Cuando</b> una petición GET es enviada <br>
            <b>Entonces</b>se recibe una respuesta 200 OK<br>
            <b>Y un array de objetos es incluído, donde cada objeto contiene la información del conductor (como nombre, número de identificación, etc.) y detalles del bus (como la placa, modelo, y estado actual).</b>
            <b>Escenario 2: Ausencia de conductores o buses</b> <br>
            <b>Dado</b> que el endpoint "/api/drivers-info" se encuentra disponible<br>
            <b>Y</b> no existen conductores o buses registrados en la base de datos,<br>
            <b>Cuando</b> una petición GET es enviada<br>
            <b>Entonces</b> se recibe una respuesta 204 No Content para indicar que actualmente no hay datos disponibles.<br><br>
            <b>Escenario 3: Errores inesperados al recuperar información</b> <br>
            <b>Dado</b> que el endpoint "/api/drivers-info" no se encuentra disponible<br>
            <b>Cuando</b> una petición GET es enviada<br>
            <b>Entonces</b> es recibida una respuesta 500 Internal Server Error.<br>
            <b>Y</b> un mensaje es incluído en la solicitud con el mensaje "Servicio de información de conductores no disponible"<br><br>  
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS10</td>
        <td>Pulsaciones de Corazón del Conductor</td>
        <td>Como desarrollador, quiero obtener el rango de pulsaciones de corazón de un conductor específico durante un rango horario dado, para que el dashboard de la aplicación web pueda mostrar estos datos, permitiendo a los administradores de flota monitorear el bienestar de los conductores durante sus turnos.</td>
        <td>
            <b>Escenario 1: Obtener el rango de pulsaciones de corazón del conductor</b> <br>
            <b>Dado</b> que el endpoint "/api/drivers/{driverId}/heart-rate" se encuentra disponible ,<br>
            <b>Y</b> que existen registros de las pulsaciones de corazón para un conductor en un rango horario específico,<br>
            <b>Cuando</b> una petición GET es enviada junto con parámetros de consulta para el rango horario,<br>
            <b>Entonces</b> se recibe una respuesta 200 OK compuesta por un array de objetos, cada uno representando un intervalo de tiempo con las pulsaciones mínimas, máximas y promedio registradas en ese período.<br><br>
            <b>Escenario 2: Manejo de solicitud de un conductor sin registros de pulsaciones</b> <br>
            <b>Dado</b> que el endpoint "/api/drivers/{driverId}/heart-rate" se encuentra disponible ,<br>
            <b>Y</b> que no existen registros de pulsaciones para el conductor en el rango horario solicitado,<br>
            <b>Cuando</b> la petición GET es enviada junto con parámetros de consulta para el rango horario,<br>
            <b>Entonces</b> se recibe una respuesta de tipo 204 No Content <br>
            <b>Y</b> un mensaje es incluído en el response body con el valor "No existen datos de pulsaciones disponibles para el conductor en el rango horario especificado." <br><br>
            <b>Escenario 3: Manejo de una solicitud con ID de conductor inválido o inexistente</b> <br>
            <b>Dado</b> que el endpoint "/api/drivers/{driverId}/heart-rate" se encuentra disponible ,<br>
            <b>Cuando</b> la petición GET es enviada junto con un ID de conductor<br>
            <b>Y</b> el ID del conductor no existe o es inválido <br>
            <b>Entonces</b> una respuesta de tipo 404 Not Found es recibida <br>
            <b>Y</b> un mensaje es incluído en el response body, con el valor "Conductor no registrado en el sistema o el ID proporcionado es incorrecto." <br><br>
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS11</td>
        <td>Alertas de Pulsaciones del Conductor</td>
        <td>Como desarrollador, quiero monitorear las pulsaciones del corazón de los conductores y generar alertas cuando estas pulsaciones caigan por debajo de un mínimo o superen un máximo predeterminado, para que el sistema de notificaciones pueda informar a los administradores de flota sobre posibles situaciones de riesgo para la salud del conductor.</td>
        <td>
            <b>Escenario 1: Generar alertas por pulsaciones bajas</b> <br>
            <b>Dado</b> que el endpoint  /api/drivers/alerts se encuentra disponible<br>
            <b>Y</b> que el sistema recibe datos de pulsaciones de un conductor que caen por debajo del mínimo predeterminado,<br>
            <b>Cuando</b> se procesan los datos <br>
            <b>Entonces</b> una alerta es generada y un 200 OK es recibido con un mensaje de alerta, incluyendo el ID del conductor, la hora del evento y un mensaje indicando que las pulsaciones están anormalmente bajas.<br><br>
            <b>Escenario 2: Generar alertas por pulsaciones altas</b> <br>
            <b>Dado</b> que el endpoint  /api/drivers/alerts se encuentra disponible<br>
            <b>Y</b> que el sistema recibe datos de pulsaciones de un conductor que superan el máximo predeterminado,<br>
            <b>Cuando</b> estos datos son procesados<br>
            <b>Entonces</b> se genera una alerta y se recibe un 200 OK con un mensaje de alerta, incluyendo el ID del conductor, la hora del evento y un mensaje indicando que las pulsaciones están anormalmente altas.<br><br>
            <b>Escenario 3: Manejar ausencia de datos de pulsaciones</b> <br>
            <b>Dado</b> que el endpoint  /api/drivers/alerts se encuentra disponible<br>
            <b>Y</b> que no se reciben datos de pulsaciones para un conductor durante un período mayor a 4 minutos,<br>
            <b>Cuando</b> se realiza verifica la actividad del conductor ,<br>
            <b>Entonces</b> el sistema se genera una alerta de "sin datos" y es recibida una respuesta 200 OK con un mensaje indicando la falta de datos de pulsaciones y potencialmente sugerir verificar el dispositivo del conductor.
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS12</td>
        <td>Autenticación de Usuarios</td>
        <td>Como desarrollador, quiero autenticar a mis usuarios utilizando su correo y contraseña o su cuenta de Google, para que puedan acceder de manera segura a la aplicación.</td>
        <td>
            <b>Escenario 1: Inicio de sesión con correo y contraseña correctos</b> <br>
            <b>Dado</b> que el endpoint "/api/auth/login" se encuentra disponible<br>
            <b>Y</b> un usuario desea iniciar sesión proporcionando un correo y contraseña,<br>
            <b>Cuando</b> la petición POST es enviada junto a valores para el correo y contraseña,<br>
            <b>Entonces</b> se recibe una respuesta 200 Ok conformada por un token de acceso JWT (JSON Web Token)<br>
            <b>Escenario 2: Inicio de sesión con correo o contraseña incorrectos</b> <br>
            <b>Dado</b> que el endpoint "/api/auth/login" se encuentra disponible<br>
            <b>Y</b> un usuario desea iniciar sesión proporcionando un correo y contraseña,<br>
            <b>Y</b> el correo o contraseña son erróneos,<br>
            <b>Cuando</b> la petición POST es enviada junto a valores para el correo y contraseña,<br>
            <b>Entonces</b> se recibe una respuesta 401 Unauthorized <br>
            <b>Y</b> un mensaje es incluído en la respuesta con el valor de "Correo o contraseña incorrectos" <br><br>
            <b>Escenario 3: Inicio de sesión con cuenta de Google</b> <br>
            <b>Dado</b> que un usuario desea iniciar sesión utilizando su cuenta de Google,<br>
            <b>Cuando</b> el usuario selecciona la opción de inicio de sesión con Google y autoriza la aplicación a través de la API de Google,<br>
            <b>Entonces</b> el sistema debe recibir un token de Google,<br>
            Y el sistema debe validar el token con los servidores de Google,<br>
            Y si el token es válido, el sistema debe verificar si el usuario ya está registrado con ese correo de Google en la base de datos,<br>
            Si el usuario no está registrado, el sistema debe crear un nuevo usuario con los datos proporcionados por Google y devolver un 200 OK con un token de acceso JWT,<br>
            Si el usuario está registrado, simplemente devolver un 200 OK con un token de acceso JWT.<br><br>
            <b>Escenario 4: Manejar errores en la autenticación con Google</b> <br>
            <b>Dado</b> que ocurre un error al intentar autenticar con Google (por ejemplo, el token de Google es inválido o ha expirado),<br>
            <b>Cuando</b> el sistema intenta validar el token con Google,<br>
            <b>Entonces</b> se recibe un 400 Bad Request o 401 Unauthorized indicando el error específico relacionado con la autenticación de Google.<br><br>
            <b>Escenario 5: Recuperación de Contraseña con correo electrónico existente </b> <br>
            <b>Dado</b> que el endpoint "/api/auth/recover-password" se encuentra disponible <br>
            <b>Y</b> que un usuario olvidó su contraseña y necesita restablecerla,<br>
            <b>Cuando</b> el usuario solicita una recuperación de contraseña enviando una solicitud POST con su correo electrónico como valor<br>
            <b>Y</b> si el correo electrónico es válido<br>
            <b>Entonces</b> es enviado un correo electrónico de recuperación de contraseña a la cuenta del usuario <br>
            <b>Escenario 6: Recuperación de Contraseña con correo electrónico inexistente o no relacionado con cuenta</b> <br>
            <b>Dado</b> que el endpoint "/api/auth/recover-password" se encuentra disponible <br>
            <b>Y</b> que un usuario olvidó su contraseña y necesita restablecerla,<br>
            <b>Cuando</b> el usuario solicita una recuperación de contraseña enviando una solicitud POST con su correo electrónico como valor<br>
            <b>Y</b> si el correo electrónico es uno inexistente o no registrado en la aplicaicón<br>
            <b>Entonces</b> es se recibe un 404 Not Found <br>
            <b>Y</b> un mensaje es incluído en el response con el valor "Cuenta inexistente o no registrada".
            <b>Escenario 6: Restablecimiento de Contraseña exitoso</b> <br>
            <b>Dado</b> que el endpoint "/api/auth/reset-password" se encuentra disponible <br>
            <b>Y</b> que un usuario haya recibido un enlace de restablecimiento de contraseña<br>
            <b>Y</b> haya proporcionado una nueva contraseña<br>
            <b>Cuando</b> se envía una solicitud POST junto con la contraseña nueva y el token de restablecimiento obtenido del correo electrónico,<br>
            <b>Y</b> el token de restablecimiento es validado correctamente, 
            <b>Entonces</b> la contraseña es reestablecida<br>
            <b>Y</b> es recibida una respuesta tipo 200 OK conformado por un mensaje con el valor "Contraseña reestablecida correctamente"<br>
            <b>Escenario 7: Restablecimiento de Contraseña inexitoso</b> <br>
            <b>Dado</b> que el endpoint "/api/auth/reset-password" se encuentra disponible <br>
            <b>Y</b> que un usuario haya recibido un enlace de restablecimiento de contraseña<br>
            <b>Y</b> haya proporcionado una nueva contraseña<br>
            <b>Cuando</b> se envía una solicitud POST junto con la contraseña nueva y el token de restablecimiento obtenido del correo electrónico,<br>
            <b>Y</b> el token de restablecimiento es inválidado o expiró, 
            <b>Entonces</b> la contraseña no es reestablecida<br>
            <b>Y</b> es recibida una respuesta tipo 400 Bad Request o 401 Unauthorized <br>
            <b>Y</b> un mensaje es incluído en la respuesta con el valor "Problema con token de reestablecimiento"<br><br>
            <b>Escenario 8: Cierre de Sesión</b> <br>
            <b>Dado</b> que el endpoint "/api/auth/logout" se encuentra disponible<br>
            <b>Y</b> que un usuario desea cerrar su sesión activa,<br>
            <b>Cuando</b> una petición POST es enviada<br>
            <b>Entonces</b> el token JWT actual del usuario es invalidado, impidiendo su uso futuro para autenticación,<br>
            <b>Y es recibido un 200 OK confirmando que el usuario ha cerrado sesión correctamente.<br><br>
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS13</td>
        <td>Registro de Línea de Bus</td>
        <td>Como desarrollador, quiero registrar una nueva línea de bus, para que los administradores de flota o dueños de empresas puedan añadir nuevas líneas al sistema de manera eficiente.</td>
        <td>
            <b>Escenario 1: Registro exitoso de un TransportCompany</b> <br>
            <b>Dado</b> que el endpoint "/api/bus-lines/register" está disponible,<br>
            <b>Cuando</b> la petición POST es enviada junto con valores sobre la línea (nombre, ruta, horarios, información del bus),<br>
            <b>Entonces</b> una respuesta es recibida con estado 201,<br>
            <b>Y</b> un TransportCompany Resurce es incluído en el ResponseBody, incluyendo un identificador único asignado y los valores envíados con anterioridad (nombre,ruta,etc).<br>
            <b>Escenario 2: Datos incompletos o inválidos</b> <br>
            <b>Dado</b> que el endpoint "/api/bus-lines/register" está disponible,<br>
            <b>Cuando</b> la solicitud POST es enviada con datos incompletos o inválidos para la línea de bus,<br>
            <b>Entonces</b> se recibe un 400 Bad Request<br>
            <b>Y</b> un mensaje incluído en el response que detalle los problemas encontrados en los datos proporcionados.<br>
            <b>Escenario 3: Registro de Transport Company ya añadido anteriormente</b> <br>
            <b>Dado</b> que el endpoint "/api/bus-lines/register" está disponible,<br>
            <b>Cuando</b> la solicitud POST es enviada con los valores para nombre, itinerario, horarios e información del bus<br>
            <b>Y</b> el TransportCompany con los mismos datos ya han sido almacenados,<br>,<br>
            <b>Entonces</b> es recibido un error 409 Conflict indicando que la línea de bus ya está registrada<br>
        </td>
        <td>
        </td>
</tr>
<tr>
         <td>TS14</td>
        <td>Suscripción Premium</td>
        <td>Como desarrollador, quiero facilitar la compra de suscripciones premium por parte de los usuarios, para que los usuarios puedan acceder a funcionalidades avanzadas y mejorar su experiencia con la aplicación.</td>
        <td>
            <b>Escenario 1: Compra exitosa de una suscripción premium</b> <br>
            <b>Dado</b> que el endpoint "/api/subscriptions/premium/purchase/stripe" se encuentra disponible <br>
            <b>Cuando</b> envía una petición POST a /api/subscriptions/premium/purchase/stripe con los detalles de su medio de pago y la duración deseada de la suscripción,<br>
            <b>Y</b> la pasarela de pagos Stripe valida y procesa el pago <br>
            <b>Entonces</b> es recibida una respuesta tipo 200 OK conformada con la confirmación de la compra dado por Stripe y los detalles de la suscripción.<br>
            <b>Escenario 2: Fallo en la validación o procesamiento del pago</b> <br>
            <b>Dado</b> que el endpoint "/api/subscriptions/premium/purchase/stripe" se encuentra disponible <br>
            <b>Cuando</b> envía una petición POST a /api/subscriptions/premium/purchase/stripe con los detalles de su medio de pago y la duración deseada de la suscripción,<br>
            <b>Y</b> Stripe invalida el proceso de pago,<br>
            <b>Entonces</b> es recibido un 400 Bad Request o 402 Payment Required <br>
            <b>Y</b> un mensaje es incluído en el response detallando el problema específico encontrado.<br>
            <b>Escenario 3: Compra de suscripción premium cuando ya se posee una activa</b> <br>
            <b>Dado</b> que un usuario con una suscripción premium activa intenta comprar otra suscripción premium,<br>
            <b>Y</b> que el endpoint "/api/subscriptions/premium/purchase/stripe" se encuentra disponible <br>
            <b>Cuando</b> envía una petición POST <br>
            <b>Y</b> el sistema debe verifica el estado de suscripción actual del usuario,<br>
            <b>Y</b> si ya posee una suscripción activa <br>
            <b>Entonces</b> se recibe un 409 Conflict <br>
            <b>Y</b> un mensaje incluído en el response con el valor "Suscripción premium ya activada , no se requiere una nueva compra.<br><br>
            <b>Escenario 5: Cancelación exitosa de una suscripción premium</b> <br>
            <b>Dado</b> que un usuario con una suscripción premium activa desea cancelarla,<br>
            <b>Y</b> que el endpoint "/api/subscriptions/premium/cancel" se encuentra disponible <br>
            <b>Cuando</b> se envía una petición POST con el valor de su identificador de usuario,<br>
            <b>Y</b> el sistema verifica la existencia de una subscripción premium activa para este usuario<br>
            <b>Entonces</b> se procesa la cancelación, lo que implica actualizar el estado de la suscripción a ""cancelada"" y desactivar el acceso a las funcionalidades premium<br><br>

</tr>
<tr>
            <td>TS15</td>
            <td>Interconectar dispositivos Iot</td>
            <td>Como desarrollador del sistema de gestión de transporte público, quiero interconectar los dispositivos IoT, como camaras y pulsómetros, para recopilar datos relevantes en tiempo real.
            </td>
            <td>
                <b>Escenario 1: Conexión de Cámaras IoT</b><br>
                <b>Dado</b> que las cámaras IoT están instaladas en los vehículos del transporte público.<br>
                <b>Cuando</b> se establece una conexión utilizando el protocolo RTSP.<br>
                <b>Entonces</b> la transmisión de video en tiempo real comienza y los datos se pueden visualizar en la plataforma de gestión.<br>

<b>Escenario 2: Conexión de Cámaras IoT Fallida</b><br>
<b>Dado</b> que una cámara  instaladas en los vehículos del transporte público no responde<br>
<b>Cuando</b> se intenta establecer una conexión utilizando el protocolo RTSP.<br>
<b>Entonces</b> se recibe un código de error 404 indicando que la cámara no está disponible.<br>

<b>Escenario 3: Integración de Pulsómetros IoT</b><br>
<b>Dado</b> que los pulsómetros IoT están instalados en los vehículos del transporte público.<br>
<b>Cuando</b> los pulsómetros envían datos utilizando el protocolo MQTT.<br>
<b>Entonces</b> los datos de ritmo cardíaco se reciben y se pueden procesar en tiempo real.<br>

<b>Escenario 4: Pulsómetro deja de enviar datos</b><br>
<b>Dado</b> que el pulsómetro deja de enviar datos.<br>
<b>Cuando</b> se espera recibir datos del pulsómetro.<br>
<b>Entonces</b> después de un tiempo de espera, se recibe un código de error 408 indicando un tiempo de espera excedido.<br>

<b>Escenario 5: Integración con la Plataforma de Gestión IoT</b><br>
<b>Dado</b> que todos los dispositivos IoT están instalados y operativos.<br>
<b>Cuando</b> se establece una conexión utilizando HTTP/REST con la plataforma de gestión IoT.<br>
<b>Entonces</b> los datos de todos los dispositivos se envían y se integran correctamente en la plataforma.<br>

<b>Escenario 6: Dispositivo no puede autenticarse con la plataforma</b><br>
<b>Dado</b> que un dispositivo no puede autenticarse con la plataforma de gestión.<br>
<b>Cuando</b> se intenta establecer una conexión con la plataforma.<br>
<b>Entonces</b> se recibe un código de error 401 indicando que el acceso está prohibido.<br>
            </td>
</tr>
<tr>
<td>TS16</td>
            <td>Conectar dispositivos IoT hacia el Gateway o el Hub</td><br>
            <td>Como desarrollador del sistema de gestión de transporte público, necesito establecer la conexión de los dispositivos IoT, como cámaras y pulsómetros, con el Gateway o Hub correspondiente para facilitar la transmisión de datos hacia el sistema central.
            </td><br>
            <td>
                <b>Escenario 1: Configuración de Cámaras IoT</b><br>
<b>Dado</b> que se han instalado cámaras IoT en estaciones y vehículos del transporte público.<br>
<b>Cuando</b> se asignan direcciones IP a las cámaras y se configuran para utilizar el protocolo RTSP.<br>
<b>Entonces</b> las cámaras están listas para conectarse al Gateway y transmitir datos de video en tiempo real.<br>

<b>Escenario 2: Conexión de Pulsómetros IoT</b><br>
<b>Dado</b> que se han instalado pulsómetros IoT en los vehículos del transporte público.<br>
<b>Cuando</b> se establece una conexión Wi-Fi entre los pulsómetros y el Gateway, utilizando el protocolo MQTT.<br>
<b>Entonces</b> los pulsómetros están conectados y listos para enviar datos de ritmo cardíaco al sistema central.<br>

<b>Escenario 3: Pruebas de Conexión</b><br>
<b>Dado</b> que todos los dispositivos IoT están configurados y listos para conectarse al Gateway o Hub.<br>
<b>Cuando</b> se envían datos de prueba desde los dispositivos IoT al Gateway.<br>
<b>Entonces</b> se verifica la recepción de los datos en el sistema central, confirmando una conexión exitosa.<br>

<b>Escenario 4: Gestión de Errores de Conexión</b><br>
<b>Dado</b> que un dispositivo IoT no puede conectarse al Gateway debido a problemas de configuración.<br>
<b>Cuando</b> se realiza un intento de conexión desde el dispositivo.<br>
<b>Entonces</b> se registran los errores correspondientes y se notifica al administrador del sistema para resolver el problema.<br>
            </td>
            <td>
            </td>
</tr>
<td>TS17</td>
            <td>Enviar la información recopilada en los dispositivos IoT hacia el Gateway</td><br>
    <td>Como desarrollador del sistema de gestión de transporte público, debo implementar la funcionalidad para enviar la información recopilada por los dispositivos IoT, como cámaras y pulsómetros, hacia el Gateway designado para su procesamiento y almacenamiento.</td><br>
            <td>
                <b>Escenario 1: Envío de Video desde Cámaras IoT al Gateway</b><br>
<b>Dado</b> que se recopila video en tiempo real de cámaras IoT instaladas en estaciones y vehículos del transporte público.<br>
      <b>Cuando</b> los datos de video se formatean en formato MPEG-4 y se envían al Gateway utilizando el protocolo RTSP.<br>
      <b>Entonces</b> el Gateway recibe los datos de video y los procesa para su almacenamiento o visualización en el sistema central.

<b>Escenario 2: Envío de Datos de Ritmo Cardíaco desde Pulsómetros IoT al Gateway</b><br>
<b>Dado</b> que se recopila video en tiempo real de cámaras IoT instaladas en estaciones y vehículos del transporte público.<br>
      <b>Cuando</b> los datos de video se formatean en formato MPEG-4 y se envían al Gateway utilizando el protocolo RTSP.<br>
      <b>Entonces</b> el Gateway recibe los datos de video y los procesa para su almacenamiento o visualización en el sistema central.<br>
<b>Escenario 3: Verificación de Recepción de Datos en el Gateway</b><br>
<b>Dado</b> que se envían datos desde dispositivos IoT al Gateway utilizando el protocolo CoAP.<br>
      <b>Cuando</b> los datos se envían correctamente desde un dispositivo IoT.<br>
      <b>Entonces</b> el Gateway envía una confirmación de recepción al dispositivo emisor, junto con un código de estado 200 OK para indicar una recepción exitosa.<br>
<b>Escenario 4: Gestión de Errores de Envío de Datos</b><br>
<b>Dado</b> que un dispositivo IoT intenta enviar datos al Gateway, pero hay un problema de conexión.<br>
      <b>Cuando</b> se realiza un intento de envío de datos desde el dispositivo.<br>
      <b>Entonces</b> el Gateway devuelve un código de estado 503 Service Unavailable para indicar que el servicio no está disponible temporalmente, y el dispositivo IoT intenta enviar los datos nuevamente después de un intervalo de tiempo predeterminado.<br>
            </td>
            <td>
            </td>
</tr>
<tr>
    <td>TS18</td>
    <td>Mandar la información recopilada en el Gateway hacia una plataforma Cloud</td>
    <td>Como desarrollador del sistema de gestión de transporte público, debo desarrollar la funcionalidad para enviar la información recopilada en el Gateway hacia una plataforma Cloud, donde se realizará un procesamiento adicional y se almacenarán los datos de manera segura y accesible.</td><br>
  <td>
    <b>Escenario 1: Envío Exitoso de Datos desde el Gateway hacia la Plataforma en la Nube</b>
    <b>Dado</b> que los datos recopilados en el Gateway están listos para ser enviados a la plataforma en la nube.<br>
      <b>Cuando</b> se establece una conexión segura utilizando el protocolo HTTPS y se envían los datos desde el Gateway hacia la plataforma en la nube.<br>
      <b>Entonces</b> la plataforma en la nube recibe los datos con éxito y envía una confirmación de recepción al Gateway junto con un código de estado HTTP 200 OK.

<b>Escenario 2: Falla en el Envío de Datos debido a una Conexión Perdida</b>
      <b>Dado</b> que se intenta enviar datos desde el Gateway hacia la plataforma en la nube.<br>
      <b>Cuando</b> durante el proceso de envío, se pierde la conexión a Internet.<br>
      <b>Entonces</b> el Gateway no puede establecer la conexión con la plataforma en la nube y recibe un código de error HTTP 503 Service Unavailable. Y el Gateway intentará reenviar los datos cuando la conexión se restablezca.<br>
  <b>Escenario 3: Error de Autenticación con la Plataforma en la Nube</b>
      <b>Dado</b> que se intenta enviar datos desde el Gateway hacia la plataforma en la nube.<br>
      <b>Cuando</b> el Gateway intenta autenticarse con la plataforma en la nube, pero las credenciales proporcionadas son incorrectas.<br>
      <b>Entonces</b> la plataforma en la nube rechaza la conexión y devuelve un código de estado HTTP 401 Unauthorized. Y el Gateway notifica al administrador del sistema sobre el error de autenticación para corregir las credenciales.
    </td>
  </tr>
  <tr>
    <td>TS19</td>
    <td>Conectar la información con el backend</td>
    <td>Como desarrollador del sistema de gestión de transporte público, necesito establecer una conexión entre la información recopilada desde los dispositivos IoT y almacenada en la plataforma Cloud con el backend del sistema, para permitir el procesamiento, análisis y gestión de los datos de manera efectiva.</td><br>
  <td>
    <b>Escenario 1: Obtención Exitosa de Datos desde la Plataforma en la Nube al Backend</b>
      <b>Dado</b> que el backend del sistema necesita obtener datos almacenados en la plataforma en la nube.<br>
      <b>Cuando</b> se establece una conexión con la plataforma en la nube utilizando el protocolo HTTPS y se envían solicitudes para obtener los datos requeridos.<br>
      <b>Entonces</b> la plataforma en la nube responde con los datos solicitados, y el backend del sistema los recibe correctamente para su procesamiento. Se devuelve un código de estado HTTP 200 OK.<br>
<b>Escenario 2: Falla en la Conexión con la Plataforma en la Nube</b>
      <b>Dado</b> que el backend del sistema intenta obtener datos de la plataforma en la nube.<br>
      <b>Cuando</b> durante el proceso de conexión, se produce un error de red o la plataforma en la nube no responde.<br>
      <b>Entonces</b> el backend del sistema no puede establecer la conexión con la plataforma en la nube y recibe un código de error HTTP 503 Service Unavailable. Se notifica al administrador del sistema sobre el problema de conexión.
<b>Escenario 3: Error en la Autorización para Acceder a los Datos</b>
      <b>Dado</b> que el backend del sistema intenta acceder a datos protegidos en la plataforma en la nube.<br>
      <b>Cuando</b> el backend envía una solicitud de acceso, pero las credenciales proporcionadas son incorrectas o insuficientes.<br>
      <b>Entonces</b> la plataforma en la nube rechaza la solicitud y devuelve un código de estado HTTP 401 Unauthorized. El backend del sistema notifica al usuario sobre el error de autorización y solicita credenciales válidas.<br>
    </td>
  </tr>
  <tr>
    <td>TS20</td>
    <td>Conectar dispositivos IoT hacia internet</td>
    <td>Como desarrollador del sistema de gestión de transporte público, debo establecer la conexión de los dispositivos IoT, como cámaras y pulsómetros, a Internet para permitir la transmisión de datos en tiempo real y la comunicación con otros sistemas y servicios externos.</td><br>
    <td>
    <b>Escenario 1: Conexión Exitosa de una Cámara IoT a Internet</b>
      <b>Dado</b> que una cámara IoT está configurada para conectarse a Internet.<br>
      <b>Cuando</b> la cámara se conecta a una red Wi-Fi utilizando el protocolo de seguridad adecuado como WPA2.<br>
      <b>Entonces</b> la cámara adquiere una dirección IP válida y establece una conexión a Internet. Se puede acceder a la cámara desde cualquier dispositivo conectado a la misma red.<br>
<b>Escenario 2: Falla en la Conexión de un Pulsómetro IoT a Internet</b>
      <b>Dado</b> que se intenta conectar un pulsómetro IoT a Internet.<br>
      <b>Cuando</b> el pulsómetro no puede conectarse a la red Wi-Fi debido a una señal débil o una configuración incorrecta.<br>
      <b>Entonces</b> el pulsómetro no adquiere una dirección IP válida y no puede establecer una conexión a Internet. Se genera un mensaje de error en el dispositivo indicando la falla en la conexión.<br>
<b>Escenario 3: Transmisión Exitosa de Datos de una Cámara IoT a un Servidor en la Nube</b>
      <b>Dado</b> que una cámara IoT está conectada a Internet y configurada para transmitir datos a un servidor en la nube.<br>
      <b>Cuando</b> la cámara detecta un evento y comienza a transmitir datos de video al servidor utilizando el protocolo HTTP.<br>
      <b>Entonces</b> el servidor en la nube recibe los datos de video de la cámara y devuelve un código de estado HTTP 200 OK para indicar una transmisión exitosa.<br>
<b>Escenario 4: Error de Protocolo al Transmitir Datos de un Pulsómetro IoT</b>
      <b>Dado</b> que un pulsómetro IoT está conectado a Internet y configurado para transmitir datos a un servidor en la nube.<br>
      <b>Cuando</b> el pulsómetro intenta enviar datos al servidor utilizando un protocolo no compatible.<br>
      <b>Entonces</b> el servidor en la nube rechaza la conexión y devuelve un código de estado HTTP 400 Bad Request para indicar un error de protocolo. El pulsómetro debe ser reconfigurado para utilizar un protocolo válido.
    </td>
  </tr>

</table>

## 3.3 Impact Mapping

<img src="../Resources/maps/impact_map.png" alt="Impact mapping"><br>
[Link: Impact mapping](https://drive.google.com/file/d/1go_Aa0YjQsdT5iDzcisKCAy8dmJg3aCI/view?usp=sharing)

## 3.4 Product Backlog

| # Orden | User Story Id | Título                                                                    | Descripción                                                                                                                                                                                                                                                                                                                                              | Story Points |
| ------- | ------------- | ------------------------------------------------------------------------- |----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| ------------ |
| 1       | US09          | Sección de Características del producto                                   | Como visitante, quiero tener una sección claramente definida que muestre las características principales del producto o servicio, para entender rápidamente sus funcionalidades y beneficios.                                                                                                                                                            | 2            |
| 2       | US10          | Sección de Inicio de la Landing Page                                      | Como visitante , deseo ser recibido con una Hero Section impactante y atractiva en la Landing Page, para que me proporcione una visión clara y concisa del valor y propósito del producto o servicio, capturando mi interés y motivándome a explorar más sobre lo que se ofrece.                                                                         | 3            |
| 3       | US07          | Diseño Responsivo de la Landing Page                                      | Como visitante, deseo que la página se adapte correctamente a diferentes dispositivos y tamaños de pantalla (como móviles, tablets y desktops), para una experiencia de usuario óptima y consistente en cualquier dispositivo que utilice.                                                                                                               | 2            |
| 4       | US01          | Redirección de la landing Page a tiendas de aplicaciones                  | Como visitante del segmento pasajero, deseo dirigirme a la aplicación móvil correspondiente para descargarla en mi dispositivo móvil                                                                                                                                                                                                                     | 1            |
| 5       | US02          | Redirección de la landing Page a la aplicación web                        | Como visitante del segmento encargado de flota de autobuses, deseo ingresar a la aplicación web mediante la landing page para usarla en mi navegador favorito                                                                                                                                                                                            | 1            |
| 6       | US06          | Navegación y Contenido Informativo en el Footer                           | Como visitante, deseo tener acceso fácil y claro a información relevante y enlaces útiles en el footer para una navegación más eficiente e acceder rápidamente a secciones importantes del sitio.                                                                                                                                                        | 2            |
| 7       | US08          | Incorporación de Testimonios en la Landing Page                           | Como visitante, deseo tener acceso a testimonios reales de usuarios o clientes para conocer experiencias positivas y comentarios sobre el servicio ofrecido.                                                                                                                                                                                             | 1            |
| 8       | US03          | Envío de mensaje a través de un formulario de contacto                    | Como visitante de cualquier segmento, deseo enviar un mensaje a los desarrolladores para enviar sugerencias, quejas u mensajes con otro motivo que yo desee                                                                                                                                                                                              | 2            |
| 9       | US05          | Sección de Preguntas Frecuentes                                           | Como visitante, deseo acceder a una sección de Preguntas Frecuentes para resolver mis inquietudes sobre el servicio ofrecido.                                                                                                                                                                                                                            | 2            |
| 10      | US04          | Conocimiento del Equipo desarrollador de la aplicación                    | Como visitante, deseo conocer al equipo que está desarrollando la aplicación para tener una mayor confianza en las personas detrás del proyecto.                                                                                                                                                                                                         | 1            |
| 11      | TS05          | Datos de Paraderos y Buses en Tiempo Real                                 | Como desarrollador, quiero obtener datos en tiempo real de paraderos y buses para una línea específica para que los usuarios de la aplicación móvil puedan ver la ubicación del bus en el mapa, el nombre del paradero, y el tiempo estimado de llegada                                                                                                  | 5            |
| 12      | TS06          | Aforo en Tiempo Real de Buses                                             | Como desarrollador, quiero obtener el aforo en tiempo real de un bus específico, para que los usuarios puedan saber cuántas personas hay en el bus antes de que llegue al paradero                                                                                                                                                                       | 5            |
| 13      | TS07          | Datos Históricos de Paraderos por Fecha                                   | Como desarrollador, quiero obtener los datos históricos de los paraderos para una fecha específica, para que el dashboard de la aplicación web pueda mostrar un listado de paraderos ordenados según la cantidad de personas que subieron en cada uno en dicha fecha.                                                                                    | 4            |
| 14      | TS01          | Listado de Líneas de Buses                                                | Como desarrollador, quiero obtener un listado de todas las líneas de buses mediante un API, para que la aplicación móvil pueda mostrarlas en la sección de explorar                                                                                                                                                                                      | 3            |
| 15      | TS02          | Búsqueda de Líneas de Bus                                                 | Como desarrollador, quiero buscar líneas de bus por nombre a través del API, para que pueda crear features para mi aplicación                                                                                                                                                                                                                            | 2            |
| 16      | TS03          | Añadir Líneas de Buses como favoritos a través del RESTful API                                                      | Como desarrollador, quiero añadir líneas de buses como favoritas a través del API para que pueda crear funciones para mi aplicación.                                                                                                                                                                                                                     | 2            |
| 17      | TS04          | Listado de Paraderos de una Línea de Bus a través de la RESTful API                                 | Como desarrollador, quiero crear un endpoint que devuelva la lista de paraderos de una línea de bus específica, para que los usuarios puedan ver todos los paraderos disponibles para esa línea en la aplicación móvil.                                                                                                                                  | 2            |
| 18      | TS10          | Pulsaciones de Corazón del Conductor                                      | Como desarrollador, quiero obtener el rango de pulsaciones de corazón de un conductor específico durante un rango horario dado, para que el dashboard de la aplicación web pueda mostrar estos datos, permitiendo a los administradores de flota monitorear el bienestar de los conductores durante sus turnos.                                          | 4            |
| 19      | TS11          | Alertas de Pulsaciones del Conductor                                      | Como desarrollador, quiero monitorear las pulsaciones del corazón de los conductores y generar alertas cuando estas pulsaciones caigan por debajo de un mínimo o superen un máximo predeterminado, para que el sistema de notificaciones pueda informar a los administradores de flota sobre posibles situaciones de riesgo para la salud del conductor. | 3            |
| 20      | TS08          | Histograma de Afluencia por Paradero                                      | Como desarrollador, quiero obtener los datos de afluencia de pasajeros para un paradero específico, para que el dashboard de la aplicación web pueda mostrar un histograma de la hora más concurrida en dicho paradero                                                                                                                                   | 5            |
| 21      | TS09          | Visualización de Datos de Conductores y Buses                             | Como desarrollador, quiero obtener una lista de todos los conductores con sus datos personales y detalles del bus que manejan, para que la aplicación web pueda mostrar esta información en el dashboard y permita a los administradores de flota o dueños de empresas monitorear y gestionar su personal y vehículos de manera efectiva.                | 5            |
| 22      | TS15          | Interconectar dispositivos Iot                                            | Como desarrollador del sistema de gestión de transporte público, quiero interconectar los dispositivos IoT, como camaras y pulsómetros, para recopilar datos relevantes en tiempo real.                                                                                                                                                                  | 3            |
| 23      | TS16          | Conectar dispositivos IoT hacia el Gateway o el Hub                       | Como desarrollador del sistema de gestión de transporte público, necesito establecer la conexión de los dispositivos IoT, como cámaras y pulsómetros, con el Gateway o Hub correspondiente para facilitar la transmisión de datos hacia el sistema central.                                                                                              | 3            |
| 24      | TS17          | Enviar la información recopilada en los dispositivos IoT hacia el Gateway | Como desarrollador del sistema de gestión de transporte público, debo implementar la funcionalidad para enviar la información recopilada por los dispositivos IoT, como cámaras y pulsómetros, hacia el Gateway designado para su procesamiento y almacenamiento.                                                                                        | 3            |
| 25      | TS18          | Mandar la información recopilada en el Gateway hacia una plataforma Cloud | Como desarrollador del sistema de gestión de transporte público, debo desarrollar la funcionalidad para enviar la información recopilada en el Gateway hacia una plataforma Cloud, donde se realizará un procesamiento adicional y se almacenarán los datos de manera segura y accesible.                                                                | 5            |
| 26      | TS19          | Conectar la información con el backend                                    | Como desarrollador del sistema de gestión de transporte público, necesito establecer una conexión entre la información recopilada desde los dispositivos IoT y almacenada en la plataforma Cloud con el backend del sistema, para permitir el procesamiento, análisis y gestión de los datos de manera efectiva.                                         | 5            |
| 27      | TS20          | Conectar dispositivos IoT hacia internet                                  | Como desarrollador del sistema de gestión de transporte público, debo establecer la conexión de los dispositivos IoT, como cámaras y pulsómetros, a Internet para permitir la transmisión de datos en tiempo real y la comunicación con otros sistemas y servicios externos.                                                                             | 3            |
| 28      | TS12          | Autenticación de Usuarios                                                 | Como desarrollador, quiero autenticar a mis usuarios utilizando su correo y contraseña o su cuenta de Google, para que puedan acceder de manera segura a la aplicación.                                                                                                                                                                                  | 3            |
| 29      | TS13          | Registro de Línea de Bus                                                  | Como desarrollador, quiero registrar una nueva línea de bus, para que los administradores de flota o dueños de empresas puedan añadir nuevas líneas al sistema de manera eficiente                                                                                                                                                                       | 3            |
| 30      | TS14          | Suscripción Premium                                                       | Como desarrollador, quiero facilitar la compra de suscripciones premium por parte de los usuarios, para que los usuarios puedan acceder a funcionalidades avanzadas y mejorar su experiencia con la aplicación                                                                                                                                           | 4            |
| 31      | US13          | Visualizar aforo en buses                                                 | Como empresa de transporte público, quiero tener información con la cantidad de personas en cada bus en tiempo real, para poder identificar los buses con mayor ocupación                                                                                                                                                                                | 2            |
| 32      | US14          | Visualizar ubicación de la flota en tiempo real                           | Como empresa de transporte público, quiero ver la ubicación de mi flota en tiempo real, para poder monitorizar el estado del servicio                                                                                                                                                                                                                    | 2            |
| 33      | US15          | Visualizar estado de los conductores                                      | Como empresa de transporte público, quiero ver el estado de mis conductores en tiempo real, para poder identificar a los que puedan estar cansados o estresados                                                                                                                                                                                          | 2            |
| 34      | US16          | Recibir notificaciones                                                    | Como empresa de transporte público, quiero recibir notificaciones en tiempo real sobre eventos relevantes para estar al tanto de posibles incidentes                                                                                                                                                                                                     | 2            |
| 35      | US18          | Visualizar gráfico de línea con el tiempo de pulso de los conductores     | Como representante de una empresa de transporte, quiero ver un gráfico de línea con el tiempo de pulso de mis conductores en tiempo real, para poder identificar a los que puedan estar bajo estrés o con problemas de salud                                                                                                                             | 5            |
| 36      | US17          | Cambiar rutas de la flota                                                 | Como empresa de transporte público, quiero poder cambiar las rutas de mi flota en tiempo real, para poder ajustar el servicio a las condiciones del tráfico o a la demanda de pasajeros                                                                                                                                                                  | 3            |
| 37      | US19          | Registrar empresa de transporte                                           | Como representante de una empresa de transporte, quiero poder registrar mi empresa en el sistema                                                                                                                                                                                                                                                         | 2            |
| 38      | US20          | Registrar línea de transporte                                             | Como representante de una empresa de transporte, quiero poder registrar una línea de transporte en el sistema                                                                                                                                                                                                                                            | 2            |
| 39      | US21          | Visualizar recorrido de una línea de bus                                  | Como usuario pasajero, quiero poder buscar y visualizar las rutas de las líneas de autobús, para tener una idea clara de su trayecto y poder planificar mis viajes de manera eficiente.                                                                                                                                                                  | 2            |

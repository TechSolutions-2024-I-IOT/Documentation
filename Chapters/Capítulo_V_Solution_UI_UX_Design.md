# Capítulo V: Solution UI/UX Design

## 5.1 Style Guidelines

### 5.1.1 General Style Guidelines

Para nuestra paleta de colores, hemos seleccionado tonos que evocan una sensación de confianza y profesionalismo. El color primario  transmite una sensación de seguridad y fiabilidad, mientras que el color secundario añade un toque de optimismo y claridad a nuestra interfaz. El color terciario aporta un elemento de calidez y vitalidad. Además de nuestra paleta de colores, hemos definido una tipografía clara y legible que refuerza la experiencia del usuario. Nuestro sistema de iconografía utiliza símbolos intuitivos y reconocibles para mejorar la navegación y comprensión de la interfaz. El sistema de cuadrícula garantiza una disposición ordenada y consistente de los elementos en la pantalla, mientras que el espaciado adecuado proporciona una experiencia visual equilibrada y agradable. Para los selectores, botones y elementos grandes y pequeños, hemos establecido estilos coherentes que aseguran una experiencia de usuario uniforme en toda la aplicación.

<div align="center">
    <img src="../Resources/style_guidelines/Colors.png" width=400>
</div>
<div align="center">
<img src="../Resources/style_guidelines/Headings.png" width=500>
<img src="../Resources/style_guidelines/Body.png" width=500>
</div>
<div align="center">
    <img src="../Resources/style_guidelines/Iconography.png" width=500>
    <img src="../Resources/style_guidelines/Grid system.png" width=500>
</div>
<div align="center">
    <img src="../Resources/style_guidelines/Spacing.png" width=500>
    <img src="../Resources/style_guidelines/Selectors.png" width=500>
</div>
<div align="center">
    <img src="../Resources/style_guidelines/Buttons.png" width=500>
    <img src="../Resources/style_guidelines/Elements.png" width=500>
</div>

### 5.1.2 Web, Mobile and IoT Style Guidelines

En nuestras pautas de estilo para la web, nos centramos en adaptar el diseño para que funcione bien en diferentes dispositivos, desde computadoras de escritorio hasta tabletas. Utilizamos una barra lateral de navegación para organizar los menús y un botón de menú para facilitar la navegación en pantallas más pequeñas.

<div align="center">
    <img src="../Resources/design/web-style-guide.png" width=500>
</div>

Para la versión móvil, nos enfocamos en hacer que la interfaz sea eficiente y fácil de usar en dispositivos móviles, priorizando la disposición y el contenido relevante. Aseguramos que la aplicación funcione en una amplia gama de dispositivos y sistemas operativos.

<div align="center">
    <img src="../Resources/design/mobile-style-guide.png" width=200>
</div>

Para dispositivos IoT, el estilo de diseño se centra en proporcionar una interfaz de usuario intuitiva y clara. Esto implica presentar los datos recopilados de manera dinámica y fácilmente interpretable, ofreciendo retroalimentación visual instantánea sobre cambios en el peso, velocidad o aceleración. Además, se busca permitir la personalización de la visualización de datos y garantizar una navegación sencilla para acceder a diferentes funciones y ajustes. En resumen, el objetivo es brindar una experiencia de usuario informativa y personalizable para el monitoreo y control de los datos capturados por estos dispositivos.

## 5.2 Information Architecture

### 5.2.1 Organization Systems

#### Visual:

Para este campo se decidio una organización jerárquica. Es decir, nos centramos en el diseño de elementos visuales que facilitan la comprensión de la información de manera intuitiva. Los elementos de mayor tamaño representan la jerarquía de primer nivel captando la atención inicial de nuestros usuarios, como el logo, títulos destacados y botones principales. Los elementos de segundo nivel complementan a los de primer orden e incluyen subtítulos, descripciones y campos de entrada de información. Por último, en el tercer nivel, se encuentran elementos independientes o complementarios, como el icono de búsqueda y las imágenes de perfil. Este enfoque garantiza una experiencia de usuario fluida y facilita la navegación intuitiva a través de nuestra plataforma.

#### Esquemas de categorización de contenido:

En esta sección, ofrecemos al usuario de la aplicación web la posibilidad de organizar el contenido mostrado según sus preferencias, mediante los criterios:
<strong>

- Cronológico:</strong> Ver los datos y estadísticas respectivas de los buses o paradas seleccionadas según la hora y fecha más reciente.

<strong>

- Según prioridad:</strong> Se muestran los perfiles de los trabajadores según el nivel de estres detectado o según el número de incidencias recibidas.

### 5.2.2 Labeling Systems

En nuestra interfaz de usuario, empleamos varios sistemas de etiquetado para mejorar la comprensión y la navegación del usuario:

<strong>

- Encabezados (Headings):</strong> Estas etiquetas se utilizan para estructurar y organizar el contenido de manera clara y legible. Permiten a los usuarios comprender rápidamente la información presentada en cada sección.

<strong>

- Etiquetas Textuales:</strong> Estas etiquetas son comunes en nuestra interfaz y se utilizan para identificar y categorizar diferentes secciones o elementos. Proporcionan una guía visual que ayuda a los usuarios a navegar y entender el contenido de manera eficiente.

<strong>

- Etiquetas Icónicas (Iconic Labels):</strong> Utilizamos imágenes o iconos junto con etiquetas textuales para proporcionar una representación visual intuitiva de las funciones o secciones específicas de la interfaz. Esto facilita la identificación rápida y la comprensión del contenido, especialmente para usuarios que prefieren un enfoque visual.

Estos sistemas de etiquetado se implementan de manera coherente en toda nuestra interfaz, incluida la barra de navegación de nuestro mockup, para garantizar una experiencia de usuario intuitiva y sin confusiones.

### 5.2.3 SEO Tags and Meta Tags

#### Para la Landing Page:

- Title:

```html
<title>ChapaTuBus | Solución IoT para Monitoreo de Buses</title>
```

- Meta Tags Description:

```html
<meta
  name="description"
  content="Descubre cómo nuestra tecnología IoT revoluciona el transporte público. Monitoreo de posición de buses, conductore y aforo en tiempo real. ¡Optimiza tus rutas o mejora la gestion con nuestras aplicaciones móviles y web!"
/>
```

- Meta Tags Keywords:

```html
<meta
  name="keywords"
  content="IoT, transporte público, monitoreo de buses, seguridad, aplicaciones móviles, aplicaciones web, aforo en tiempo real, dashboard, tecnología"
/>
```

- Autor:

```html
<meta name="author" content="TechSolutions" />
```

- Copyright:

```html
<meta name="copyright" content="© TechSolutions, 2024" />
```

#### Para la Aplicación Web (Dashboard):

- Title:

```html
<title>ChapaTuBus | BusMonitor</title>
```

- Meta Tags Description:

```html
<meta
  name="description"
  content="Optimiza tus rutas y mejora la seguridad con BusMonitor. Monitorea el pulso de los conductores, el aforo de los buses y recibe alertas en tiempo real. Planifica mejor tus servicios con nuestros análisis detallados y gráficos interactivos."
/>
```

- Meta Tags Keywords:

```html
<meta
  name="keywords"
  content="IoT, transporte público, monitoreo, buses, seguridad, dashboard, pulso del conductor, aforo en tiempo real, análisis de datos"
/>
```

- Author:

```html
<meta name="author" content="TechSolutions" />
```

- Copyright:

```html
<meta name="copyright" content="© TechSolutions, 2024" />
```

### 5.2.4 Searching Systems

En esta sección del informe, nos enfocamos en definir la arquitectura de la información para facilitar a los usuarios la búsqueda de datos dentro de nuestra aplicación móvil y dashboard. Después de un análisis exhaustivo, hemos observado que nuestro sistema alberga una gran cantidad de información. Por ejemplo, un usuario puede buscar ofertas de trabajo según diferentes criterios, como años de experiencia requeridos, rango salarial y habilidades necesarias.

Para mejorar la experiencia de búsqueda, hemos implementado las siguientes características:

**Aplicación móvil (para pasajeros):**

- Barra de búsqueda: Permite a los usuarios buscar líneas de autobús específicas, lo que les facilita encontrar información relevante de manera rápida y sencilla.
- Funcionalidad de búsqueda de paradas: Los usuarios pueden ubicar la parada de autobús más cercana utilizando su ubicación actual o seleccionando una parada específica. Además, hemos agregado la opción de cambiar la dirección del viaje con un simple botón, ofreciendo mayor flexibilidad a los usuarios en sus desplazamientos.

**Dashboard (para empresas de autobuses):**

- Selección por línea de autobús: Permite a las empresas acceder a estadísticas detalladas de una línea de autobús en particular, lo que les ayuda a comprender mejor el rendimiento y la eficiencia de sus servicios.
- Filtrado por día: Capacidad de visualizar datos estadísticos basados en un día específico dentro de un plazo de doce meses, lo que les permite realizar análisis detallados y tomar decisiones informadas.
- Vista por mayor aforo: Se mostrara por defecto la vista en la que se ordenara por una línea de buses, según la cantidad de personas que abordaron por paradero.
- Selección por autobús y conductor: Ofrece la posibilidad de visualizar datos relacionados con un autobús específico y el conductor asignado.

Nuestro enfoque en segmentar y categorizar la información tiene como objetivo principal garantizar una navegación fluida dentro de la aplicación. Nos esforzamos por proporcionar a nuestros usuarios las herramientas necesarias para encontrar fácilmente la información que están buscando, ya sea para planificar su viaje como pasajeros o para gestionar eficientemente su flota de autobuses como empresas de transporte.

<!-- Mencionar a más detalle como buscaran y se mostraraon los datos del dashboard -->

### 5.2.5 Navigation Systems

A través de nuestras aplicaciones, hemos implementado sistemas de navegación que permiten a los usuarios moverse de manera intuitiva y eficiente por todas las secciones disponibles. Esto se logra mediante:

<!-- TO REVIEW -->

**1. Uso de lenguaje claro y conciso:** Cada sección está etiquetada con términos comprensibles y directos, lo que facilita la identificación de las funcionalidades que ofrece la aplicación.

**2. Íconos representativos:** Los usuarios pueden hacer clic en los íconos correspondientes a cada sección para acceder directamente a la funcionalidad deseada. Estos íconos están diseñados de manera intuitiva para reflejar claramente el contenido de cada sección.

**3. Botones desplegables para interconectar secciones:** Implementamos botones desplegables que permiten a los usuarios explorar y acceder fácilmente a secciones relacionadas entre sí. Estos botones facilitan la navegación entre diferentes áreas de la aplicación y fomentan nuevas interacciones.

**4. Navegación aleatoria:** Los usuarios tienen la flexibilidad de explorar el contenido de manera aleatoria, lo que les permite acceder a cualquier sección en el momento que lo requieran. Esto ofrece una experiencia más dinámica y personalizada, adaptada a las necesidades individuales de cada usuario.

**5. Prioridad de páginas de registro e inicio de sesión:** En caso de que un usuario no esté registrado o no haya iniciado sesión, las páginas de registro o inicio de sesión siempre se muestran primero. Esto garantiza que los usuarios puedan acceder fácilmente a estas funciones esenciales y asegura una experiencia coherente para todos los usuarios, independientemente de su estado de inicio de sesión.

## 5.3. Landing Page UI Design

Nuestra propuesta se basa en las decisiones de diseño y arquitectura de la información definidas previamente, asegurando una experiencia de usuario coherente y efectiva en todas las plataformas.

Los principios de diseño aplicados son: 

- **Simplicidad**: La interfaz se mantendrá simple y fácil de navegar, con elementos claros y concisos.
- **Claridad**: El mensaje principal de la empresa se transmitirá de manera clara y directa.
- **Consistencia**: Los elementos de diseño, la terminología y las interacciones serán consistentes en todas las plataformas.
- **Accesibilidad**: La interfaz se diseñará para ser accesible para todos los usuarios, independientemente de sus habilidades o limitaciones.
- **Estética**: El diseño será atractivo, profesional y acorde con la identidad de la marca.

Los elementos de diseño aplicados son:

- **Tipografía**: Se utilizará una tipografía legible y adaptable a diferentes tamaños de pantalla.
- **Colores**: La paleta de colores se basará en los colores de la marca y se utilizará de manera consistente en toda la interfaz.
- **Imágenes**: Se utilizarán imágenes de alta calidad que representen el valor y la propuesta de la empresa.
- **Iconos**: Se utilizarán iconos para representar las características y beneficios de la empresa de manera visual.
- **Botones**: Se utilizarán botones claros y fáciles de pulsar para realizar acciones.

En relación a nuestra arquitectura de la información, se plantea:

- **Jerarquía visual**: La información se organizará de forma jerárquica, utilizando diferentes tamaños de tipografía, colores y pesos para destacar los elementos más importantes.
- **Agrupación lógica**: Los elementos relacionados se agruparán de manera lógica para facilitar la comprensión.
- **Etiquetado claro**: Los elementos se etiquetarán de manera clara y concisa para que los usuarios puedan comprender su función fácilmente.

### 5.3.1. Landing Page Wireframe

Juntos, hemos trabajado en equipo utilizando la herramienta de diseño colaborativo Figma para crear los wireframes de nuestra landing page. Se consideraron nuestros dos segmentos objetivos para el planteamiento del diseño.

**Desktop Web Browser:**
- Cabecera: Logotipo, menú de navegación y botón de llamada de acción.
- Sección principal: Imagen de fondo, título principal, subtítulo y botón de llamada de acción.
- Sección de características: Íconos o cuadros de texto con descripciones.
- Sección de equipo: Equipo de desarrollo con nombres y fotos.
- Sección de FAQ: Lista de preguntas y respuestas.
- Pie de página: Información de contacto y redes sociales.

**Mobile Web Browser:**
- Cabecera: Logotipo y menú de hamburguesa.
- Sección principal: Imagen de fondo, título principal, subtítulo y botón de llamada de acción.
- Secciones de características y equipo: Acordeones (opcional).
- Sección de FAQ: Lista de preguntas con enlaces a respuestas.
- Pie de página: Información de contacto y redes sociales.

<div align="center">
    <img src="../Resources/design/landing-page-wireframe.png">
</div>

Enlace de Figma: https://www.figma.com/file/97DXUycS74gm7Bu99vor2j/IOT?type=design&node-id=124%3A3&mode=design&t=mj2qihRGU3ibILKb-1

### 5.3.2. Landing Page Mock-up

Juntos, hemos trabajado en equipo utilizando la herramienta de diseño colaborativo Figma para crear el diseño Mock-up de nuestra landing page. Se consideraron nuestros dos segmentos objetivos para el planteamiento del diseño.

**Desktop Web Browser:**
- Cabecera: Logotipo ubicado en la esquina superior izquierda, con un tamaño y color que lo hagan destacar. Utilizamos una paleta de colores consistente con la marca de la empresa.
- Sección principal: Una imagen de alta calidad que represente el valor principal de la empresa, transmitiendo una sensación de profesionalismo y confianza, un texto breve y conciso que resuma la propuesta de valor de la empresa, utilizando una tipografía grande y llamativa y botón de llamada de acción visible y accesible.
- Sección de características: Diseños visuales que representen las características principales de la empresa, utilizando colores y formas que sean fácilmente reconocibles.
- Sección de equipo: Imágenes de alta calidad de los miembros del equipo de desarrollo, mostrando una sonrisa natural y una actitud profesional.
- Sección de FAQ: Listado de preguntas comunes sobre los servicios de la empresa, utilizando un lenguaje claro y conciso, utilizamos una tipografía legible y un tamaño de letra adecuado para una lectura cómoda.
- Pie de página: Información de contacto y redes sociales, utilizar una tipografía legible y un tamaño de letra.

**Mobile Web Browser:**
- Cabecera: Logotipo ubicado en la esquina superior izquierda, con un tamaño y color que lo hagan destacar y menú de hamburguesa llamativo.
- Sección principal: Una imagen de alta calidad que represente el valor principal de la empresa, transmitiendo una sensación de profesionalismo y confianza, un texto breve y conciso que resuma la propuesta de valor de la empresa, utilizando una tipografía grande y llamativa y botón de llamada de acción visible y accesible.
- Secciones de características y equipo: Diseños visuales en forma de acordeon que representen las características principales de la empresa, utilizando colores y formas que sean fácilmente reconocibles.
- Sección de FAQ: Lista de preguntas con enlaces a respuestas.
- Pie de página: Información de contacto y redes sociales, utilizar una tipografía legible y un tamaño de letra.

<div align="center">
    <img src="../Resources/design/landing-page-mockup.png">
</div>

Enlace de Figma: https://www.figma.com/file/97DXUycS74gm7Bu99vor2j/IOT?type=design&node-id=124%3A3&mode=design&t=mj2qihRGU3ibILKb-1

## 5.4. Applications UX/UI Design

### 5.4.1. Applications Wireframes

### 5.4.2. Applications Wireflow Diagrams

En esta sección, presentamos los diagramas de flujo de nuestra aplicación web, elaborados por nuestro equipo. Estos diagramas reflejan el comportamiento de la aplicación en función de las interacciones esperadas de nuestros usuarios. Hemos desarrollado un diagrama de flujo para cada objetivo del usuario, teniendo en cuenta los perfiles de usuario (empleador y empleado) para cada funcionalidad de la aplicación. Antes de crear los diagramas de flujo, realizamos flujos de tareas para establecer las rutas típicas que seguirá el usuario en la aplicación. En los diagramas de flujo, mostramos los cambios en la pantalla a medida que el usuario interactúa con la aplicación, añadiendo pasos con representaciones visuales del nuevo estado. Utilizamos la herramienta Figma para crear estos diagramas de flujo, y para cada uno de ellos hemos incluido el objetivo del usuario correspondiente y una explicación detallada del flujo.

**TaskFlow**

- Registrarse en la aplicación
- Iniciar sesión
- Registrar ruta de transporte
- Ver reporte de paraderos con mayor afluencia de pasajeros
- Ver reporte de horarios con mayor afluencia de pasajeros
- Ver cantidad de pasajeros que abordaron en un paradero
- Ver información de flota
- Ver notificaciones de flota
- Buscar información de una línea de transporte
- Añadir ruta a favoritos
- Ver rutas de líneas de transporte

**Pasajero**

- UG01: Registrarse en la aplicación
  
  El pasajero accede a la aplicación y selecciona la opción de registro, completa el formulario de registro proporcionando su información personal, como nombre, correo electrónico y contraseña, luego onfirma la creación de su cuenta al hacer clic en el botón de registro y recibe una notificación de confirmación de registro y es redirigido a la pantalla de inicio de sesión para iniciar sesión con sus nuevas credenciales.

<div align="center">
    <img src="../Resources/design/crear-cuenta-mobile.png">
</div>
  
- UG02: Iniciar sesión

  El pasajero abre la aplicación y selecciona la opción de iniciar sesión, ingresa su correo electrónico y contraseña en los campos correspondientes, presiona el botón de inicio de sesión para verificar sus credenciales y si la información ingresada es correcta, el usuario es autenticado y dirigido a la pantalla principal de la aplicación.

<div align="center">
    <img src="../Resources/design/iniciar-sesion-mobile.png">
</div>
  
- UG03: Buscar información de una línea de transporte

  Después de iniciar sesión, el pasajero accede a la función de búsqueda en la pantalla principal de la aplicación, ingresa el nombre o número de la línea de transporte que desea buscar y selecciona la línea de transporte deseada de los resultados de búsqueda. Finalmente, visualiza la información detallada de la línea de transporte, como horarios, rutas y paradas disponibles.

<div align="center">
    <img src="../Resources/design/buscar-info-linea-mobile.png">
</div>

- UG04: Añadir ruta a favoritos

  Mientras revisa la información de una línea de transporte, el pasajero encuentra una ruta que le interesa, selecciona la opción para añadir esa ruta a sus favoritos y la ruta seleccionada se guarda en la lista de favoritos del pasajero para un acceso rápido y fácil en el futuro.

  <div align="center">
    <img src="../Resources/design/añadir-favorito-mobile.png">
</div>
  
- UG05: Ver rutas de líneas de transporte

  Desde la pantalla principal de la aplicación, el pasajero accede a la sección de rutas de líneas de transporte, explora la lista de todas las rutas disponibles, organizadas por línea de transporte y selecciona una línea de transporte específica para ver las rutas asociadas y la información detallada de cada una.

  <div align="center">
    <img src="../Resources/design/ver-rutas-mobile.png">
</div>

**Encargado de la empresa de transporte**

- UG01: Registrarse en la aplicación

  El encargado accede a la aplicación web y selecciona la opción de registro, completa el formulario de registro proporcionando la información solicitada, incluyendo los datos de la empresa y de la línea de transporte, adjunta la información requerida y confirma el registro de la empresa y la línea de transporte al hacer clic en el botón de registro. Finalmente, recibe una notificación de confirmación y es redirigido a la pantalla de inicio de sesión para acceder a su cuenta recién creada.

  <div align="center">
    <img src="../Resources/design/registro-web.png">
</div>
  
- UG02: Iniciar sesión

  El encargado abre la aplicación web y selecciona la opción de iniciar sesión, ingresa su correo electrónico y contraseña en los campos correspondientes, presiona el botón de inicio de sesión para autenticarse.
Si los datos ingresados son correctos, el administrador es autenticado y dirigido al panel de control (dashboard) de la aplicación.

<div align="center">
    <img src="../Resources/design/iniciar-sesion-web.png">
</div>

- UG03: Registrar ruta de transporte

  Después de iniciar sesión, el encargado accede al panel de control y selecciona la opción de registrar ruta de transporte, completa el formulario de registro proporcionando los detalles de la nueva ruta, como el número de ruta, horarios y paraderos, adjunta la información adicional requerida, como fotos de los paraderos y horarios de inicio y fin, confirma el registro de la nueva ruta al hacer clic en el botón correspondiente. Finalmente, recibe una notificación de confirmación y la nueva ruta se agrega al sistema.

  <div align="center">
    <img src="../Resources/design/registrar-ruta-web.png">
</div>
  
- UG04: Ver reporte de paraderos con mayor afluencia de pasajeros

  Desde el panel de control, el encargado accede a la sección de informes y selecciona el reporte de paraderos con mayor afluencia de pasajeros, visualiza la lista de paraderos ordenados por la cantidad de pasajeros que abordaron en cada uno y puede explorar los detalles de cada paradero, incluyendo la cantidad de pasajeros y el horario de mayor afluencia.

  <div align="center">
    <img src="../Resources/design/reporte-paraderos-web.png">
</div>
  
- UG05: Ver reporte de horarios con mayor afluencia de pasajeros

  Desde el panel de control, el encargado accede a la sección de informes y elige el reporte de horarios con mayor afluencia de pasajeros, visualiza la lista de horarios de salida ordenados por la cantidad de pasajeros que abordaron en cada uno y puede explora los detalles de cada horario, incluyendo la cantidad de pasajeros y los paraderos asociados.

  <div align="center">
    <img src="../Resources/design/reporte-horarios-web.png">
</div>

- UG06: Ver cantidad de pasajeros que abordaron en un paradero

  Desde el panel de control, el encargado accede a la sección de informes y selecciona la opción de ver la cantidad de pasajeros que abordaron en un paradero específico, selecciona el paradero de interés de una lista desplegable, visualiza la cantidad de pasajeros que abordaron en ese paradero en un período de tiempo determinado.

   <div align="center">
    <img src="../Resources/design/reporte-cantidad-pasajeros-web.png">
</div>
  
- UG07: Ver información de flota

  Desde el panel de control, el encargado accede a la sección de flota y selecciona la opción de ver información de la flota, visualiza la lista de conductores asociados a la empresa de transporte, junto con sus detalles personales y de contacto y explora la información detallada de cada conductor, incluyendo su historial de trabajo y evaluaciones.

  <div align="center">
    <img src="../Resources/design/flota-web.png">
</div>

- UG08: Ver notificaciones de flota

  Desde el panel de control, el encargado accede a la sección de notificaciones y selecciona la opción de ver notificaciones de flota, visualiza la lista de notificaciones recibidas relacionadas con la flota de conductores y explora cada notificación para obtener más detalles y tomar las acciones necesarias, como asignar nuevos horarios o realizar seguimientos.

    <div align="center">
    <img src="../Resources/design/notificaciones-web.png">
</div>

**Enlace Lucidchart: https://lucid.app/lucidchart/461bbd3c-2e35-460e-8052-00e3969a6755/edit?viewport_loc=-4961%2C-4348%2C37337%2C16036%2C0_0&invitationId=inv_2728ed2a-389d-4c05-959e-571d48f86cd5**

### 5.4.2. Applications Mock-ups

### 5.4.3. Applications User Flow Diagrams

En este apartado hemos documentado visualmente el flujo de interacción que los usuarios siguen al utilizar la aplicación. Estos diagramas nos muestran las diferentes pantallas y pasos que un usuario atraviesa desde que inicia la aplicación hasta que completa una acción o tarea específica. Nos sirven como una herramienta visual para comprender y analizar cómo los usuarios interactúan con la aplicación, identificar posibles problemas o áreas de mejora en la experiencia del usuario, y guiar el diseño y desarrollo de la interfaz de usuario para optimizar la usabilidad y la satisfacción del usuario. Hemos considerado nuestros dos segmentos objetivos y sus respectivos User Goals.

**Pasajero**

- UG01: Registrarse en la aplicación
  
  El pasajero accede a la aplicación y selecciona la opción de registro, completa el formulario de registro proporcionando su información personal, como nombre, correo electrónico y contraseña, luego onfirma la creación de su cuenta al hacer clic en el botón de registro y recibe una notificación de confirmación de registro y es redirigido a la pantalla de inicio de sesión para iniciar sesión con sus nuevas credenciales.

<div align="center">
    <img src="../Resources/design/pasajero-ug01-user-flow.png">
</div>
  
- UG02: Iniciar sesión

  El pasajero abre la aplicación y selecciona la opción de iniciar sesión, ingresa su correo electrónico y contraseña en los campos correspondientes, presiona el botón de inicio de sesión para verificar sus credenciales y si la información ingresada es correcta, el usuario es autenticado y dirigido a la pantalla principal de la aplicación.

<div align="center">
    <img src="../Resources/design/pasajero-ug02-user-flow.png">
</div>
  
- UG03: Buscar información de una línea de transporte

  Después de iniciar sesión, el pasajero accede a la función de búsqueda en la pantalla principal de la aplicación, ingresa el nombre o número de la línea de transporte que desea buscar y selecciona la línea de transporte deseada de los resultados de búsqueda. Finalmente, visualiza la información detallada de la línea de transporte, como horarios, rutas y paradas disponibles.

<div align="center">
    <img src="../Resources/design/pasajero-ug03-user-flow.png">
</div>

- UG04: Añadir ruta a favoritos

  Mientras revisa la información de una línea de transporte, el pasajero encuentra una ruta que le interesa, selecciona la opción para añadir esa ruta a sus favoritos y la ruta seleccionada se guarda en la lista de favoritos del pasajero para un acceso rápido y fácil en el futuro.

<div align="center">
    <img src="../Resources/design/pasajero-ug04-user-flow.png">
</div>
  
- UG05: Ver rutas de líneas de transporte

  Desde la pantalla principal de la aplicación, el pasajero accede a la sección de rutas de líneas de transporte, explora la lista de todas las rutas disponibles, organizadas por línea de transporte y selecciona una línea de transporte específica para ver las rutas asociadas y la información detallada de cada una.

<div align="center">
    <img src="../Resources/design/pasajero-ug05-user-flow.png">
</div>

**Encargado de la empresa de transporte**

- UG01: Registrarse en la aplicación

  El encargado accede a la aplicación web y selecciona la opción de registro, completa el formulario de registro proporcionando la información solicitada, incluyendo los datos de la empresa y de la línea de transporte, adjunta la información requerida y confirma el registro de la empresa y la línea de transporte al hacer clic en el botón de registro. Finalmente, recibe una notificación de confirmación y es redirigido a la pantalla de inicio de sesión para acceder a su cuenta recién creada.

<div align="center">
    <img src="../Resources/design/encargado-ug01-user-flow.svg">
</div>
  
- UG02: Iniciar sesión

  El encargado abre la aplicación web y selecciona la opción de iniciar sesión, ingresa su correo electrónico y contraseña en los campos correspondientes, presiona el botón de inicio de sesión para autenticarse.
Si los datos ingresados son correctos, el administrador es autenticado y dirigido al panel de control (dashboard) de la aplicación.

<div align="center">
    <img src="../Resources/design/encargado-ug02-user-flow.png">
</div>

- UG03: Registrar ruta de transporte

  Después de iniciar sesión, el encargado accede al panel de control y selecciona la opción de registrar ruta de transporte, completa el formulario de registro proporcionando los detalles de la nueva ruta, como el número de ruta, horarios y paraderos, adjunta la información adicional requerida, como fotos de los paraderos y horarios de inicio y fin, confirma el registro de la nueva ruta al hacer clic en el botón correspondiente. Finalmente, recibe una notificación de confirmación y la nueva ruta se agrega al sistema.

<div align="center">
    <img src="../Resources/design/encargado-ug03-user-flow.svg">
</div>
  
- UG04: Ver reporte de paraderos con mayor afluencia de pasajeros

  Desde el panel de control, el encargado accede a la sección de informes y selecciona el reporte de paraderos con mayor afluencia de pasajeros, visualiza la lista de paraderos ordenados por la cantidad de pasajeros que abordaron en cada uno y puede explorar los detalles de cada paradero, incluyendo la cantidad de pasajeros y el horario de mayor afluencia.

<div align="center">
    <img src="../Resources/design/encargado-ug04-user-flow.svg">
</div>
  
- UG05: Ver reporte de horarios con mayor afluencia de pasajeros

  Desde el panel de control, el encargado accede a la sección de informes y elige el reporte de horarios con mayor afluencia de pasajeros, visualiza la lista de horarios de salida ordenados por la cantidad de pasajeros que abordaron en cada uno y puede explora los detalles de cada horario, incluyendo la cantidad de pasajeros y los paraderos asociados.

<div align="center">
    <img src="../Resources/design/encargado-ug05-user-flow.svg">
</div>

- UG06: Ver cantidad de pasajeros que abordaron en un paradero

  Desde el panel de control, el encargado accede a la sección de informes y selecciona la opción de ver la cantidad de pasajeros que abordaron en un paradero específico, selecciona el paradero de interés de una lista desplegable, visualiza la cantidad de pasajeros que abordaron en ese paradero en un período de tiempo determinado.

<div align="center">
    <img src="../Resources/design/encargado-ug06-user-flow.svg">
</div>
  
- UG07: Ver información de flota

  Desde el panel de control, el encargado accede a la sección de flota y selecciona la opción de ver información de la flota, visualiza la lista de conductores asociados a la empresa de transporte, junto con sus detalles personales y de contacto y explora la información detallada de cada conductor, incluyendo su historial de trabajo y evaluaciones.

<div align="center">
    <img src="../Resources/design/encargado-ug07-user-flow.png">
</div>

- UG08: Ver notificaciones de flota

  Desde el panel de control, el encargado accede a la sección de notificaciones y selecciona la opción de ver notificaciones de flota, visualiza la lista de notificaciones recibidas relacionadas con la flota de conductores y explora cada notificación para obtener más detalles y tomar las acciones necesarias, como asignar nuevos horarios o realizar seguimientos.

<div align="center">
    <img src="../Resources/design/encargado-ug08-user-flow.png">
</div>

**Enlace Lucidchart: https://lucid.app/lucidchart/461bbd3c-2e35-460e-8052-00e3969a6755/edit?viewport_loc=-13175%2C-5150%2C46975%2C20175%2CrPhwHx3GG._Y&invitationId=inv_2728ed2a-389d-4c05-959e-571d48f86cd5**

## 5.5. Applications Prototyping

Nuestros principales criterios para el sistema de navegación y los tipos de interacciones seleccionadas fueron:

- Claridad: Interacciones intuitivas para una navegación sencilla y acciones comprensibles.
- Consistencia: Interacciones uniformes en todo el sitio web para evitar confusiones.
- Eficiencia: Interacciones que permiten completar tareas de forma rápida y sencilla.
- Accesibilidad: Interacciones accesibles para todos los usuarios, independientemente de sus habilidades.
- Atracción visual: Interacciones atractivas que generen una experiencia positiva.

Relación con la arquitectura de información:

- Sistema de navegación fácil de usar y con etiquetas claras para encontrar información rápidamente.
- Tipos de interacciones adecuadas para el contenido y las acciones deseadas (botones para acciones, enlaces para navegación).

Lo que se desarrolló en base a eso en nuestro diseño fue:

- Botones de de llamada de acción estratégicamente ubicados para máxima visibilidad y fácil acceso por parte del usuario.
- Menú de navegación desplegable en dispositivos móviles para optimizar el espacio en la pantalla.
- Acordeones en secciones de características y equipo para organizar la información de forma compacta y accesible.
- Descripciones emergentes al pasar el cursor sobre elementos para ofrecer información adicional sin saturar la interfaz.
- Respuestas a preguntas frecuentes desplegables para ahorrar espacio y mejorar la legibilidad.

**Web Application**

Se describe el flujo que el encargado de la empresa de transporte hace en nuestra aplicación web. Desde el registro donde debe ingresar sus datos, información verídica de la empresa e información sobre su ruta, hasta el  acceso a la información detallada de sus buses y conductores.

<div align="center">
    <img src="../Resources/design/web-prototyping.png">
</div>

Enlace de video: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202115862_upc_edu_pe/ETx1skpbruFLiLz3RD1zm0EByHqYI-5c63HsFg0MuOEHyw?e=U1Xqet

**Mobile Application**

Se describe el flujo que el pasajero realiza en nuestra aplicación móvil, desde registrarse donde debe ingresar sus datos, hasta ver la información detallada sobre los buses más cercanos a su ubicación, su aforo, el tiempo de llegada, entre otros.

<div align="center">
    <img src="../Resources/design/mobile-prototyping.png">
</div>

Enlace de video: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202115862_upc_edu_pe/EQs2xh1eya5LuYON8-AIUFABmOJBd3_87TksVqxq6VU7ow?e=QFpv8Q

# Capítulo VI: Product Implementation, Validation & Deployment

## 6.1. Software Configuration Management

### 6.1.1. Software Development Environment Configuration.

- **Project Management**:
  
  Para las actividades de Project Management se ha elegido hacer uso de Jira que es una herramienta de gestión de trabajo para los equipos de software que deben organizar y hacer un seguimiento de su trabajo. Se eligió
  esta herramienta por su flexibilidad y porque nos brinda la opción de personalizarla de acuerdo al flujo de trabajo del equipo.
  
  **Enlace:** https://www.atlassian.com/es/software/jira
  
- **Requirements Management**

  Para el manejo de requerimientos se eligió Pivotal Tracker pues es una herramienta gratuita de gestión de proyectos ágiles que se enfoca en la gestión de la pila de producto y métricas como la velocidad.
  Es esencial para nosotros como equipo pues nos permite trabajar de manera descentralizada.

  **Enlace:** https://www.pivotaltracker.com/
  
- **Product UX/UI Design**

  Para temas de diseño UX/UI de nuestro producto se eligió Figma pues es una herramienta donde podemos crear distintos conceptos como wireframes, diseños de webs y diseños de aplicaciones de manera gratuita. Nos es útil
   ya que nos brinda un amplio menú de funcionalidades y utilidades.

  **Enlace:** https://www.figma.com
  
- **Software Development**

  Para el desarrollo de software, se han elegido las siguientes herramientas:

  Para el desarrollo de nuestra Landing Page, Web Application y Mobile Application se eligió **Visual Studio Code** pues es un software de amplia compatibilidad con lenguajes y frameworks y potentes herramientas de depuración y pruebas.
  Además de que cuenta con integración nativa con Git y control de versiones y se adapta a nuestras necesidades.

  **Enlace**: https://visualstudio.microsoft.com/es/#vscode-section

  Para el desarrollo de nuestro Backend Service se eligió **IntelliJ IDEA** pues nos permite dedicar más tiempo a diseñar y crear productos, en lugar de a repetir código, identificar errores y resolverlos. Nos ayuda a
  trabajar de manera más eficaz y cuenta con una interfaz intuitiva.

  **Enlace**: https://www.jetbrains.com/idea/
  
- **Software Testing**

  En relación a Testing, se ha decidido usar las siguientes herramientas:

  Para el testing de la aplicación web, se eligió **SELENIUM IDE**, puesto que es una herramienta de código abierto con la cual resulta sencillo realizar casos de prueba.

  **Enlace**: https://chromewebstore.google.com/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd

  Para el testing de nuestro backend se decidieron utilizar **JUnit** y **Mockito** debido a que son bibliotecas populares de SpringBoot que permiten realizar un testing rápido y eficiente.

  **Enlace**:https://junit.org/junit5/
  **Enlace**:https://site.mockito.org/

- **Software Deployment**

  Para el deployment de nuestras soluciones hemos decidio usar:

  **Github pages** para el despliegue de nuestra Landing Page pues soporta sitios web estáticos y es gratuito.

  **Enlace**: https://pages.github.com/

  **Netlify** para el despliegue de nuestra Web Application pues es una plataforma intuitiva y fácil de usar.

  **Enlace**: https://www.netlify.com/

  **Render** para el despliegue de nuestro backend pues nos brinda un hosting rápido, sencillo e intuitivo.

  **Enlace:** https://render.com/
  
- **Software Documentation**

  La documentación de nuestro software desde el punto de vista de desarrollador será realizada en **Github** a través de un readme (informe), se usará github puesto que es una plataforma de código gratuita y con gran uso en el mundo del software.

  **Enlace:** https://github.com/

### 6.1.2. Source Code Management.

**Repositorios** 

Se creó una organización llamada TechSolutions-2024-I-IOT en Github, en la cual el equipo cuenta con los repositorios donde se trabajarán las soluciones propuestas.

Enlace de la organización: https://github.com/TechSolutions-2024-I-IOT

<table border="2">
    <tr>
        <td>
           <p style = "font-weight: bold"><b>Solución</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Nombre del repositorio</b></p>
        </td>
        <td>
          <p style = "font-weight: bold"><b>Enlace</b></p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Landing Page</p>
        </td>
        <td>
          <p>Landing-Page</p>
        </td>
        <td>
          <p>https://github.com/TechSolutions-2024-I-IOT/Landing-Page.git</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Frontend Web Application</p>
        </td>
        <td>
          <p>Frontend</p>
        </td>
        <td>
          <p>https://github.com/TechSolutions-2024-I-IOT/Frontend.git</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Web Services</p>
        </td>
        <td>
          <p>Backend</p>
        </td>
        <td>
          <p>https://github.com/TechSolutions-2024-I-IOT/Backend.git</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Mobile Application</p>
        </td>
        <td>
          <p>ChapaTuBus-Mobile</p>
        </td>
        <td>
          <p>https://github.com/TechSolutions-2024-I-IOT/ChapaTuBus-Mobile.git</p>
        </td>
    </tr>
</table>

**Gitflow**

<div align="center">
  <img src="../Resources/images/gitflow.png" width=500 alt="Gitflow">
</div>

Para la implementación del flujo de trabajo Gitflow, usando la herramienta de control de versiones Git, se usó de referencia la entrada de blog “A successful Git branching model” de Vincent Driessen, que nos ayudó a detallar las siguientes convenciones que se usarán en el proyecto:

- **Main  branch**
La Main branch es la principal rama de desarrollo del proyecto. En esta rama se encontrará el código que se encuentra actualmente en producción. 
**Notación:** main 

- **Develop branch**
La Develop branch será la rama que contendrá las últimas actualizaciones y cambios agregados que se entregarán en la siguiente versión del proyecto. 
**Notación:** develop 
**Creación:** git checkout -b develop main

- **Feature branches**
Las Feature branches se usarán para desarrollar nuevas características del producto que se agregarán en versiones futuras. Estas funcionalidades se deberán reunir o juntar eventualmente a la rama Develop. 
  - Debe derivarse de la rama Develop. 
  - Debe fusionarse de vuelta a la rama Develop. 
**Notación:** feature/[name of feature] 
**Creación:** git checkout -b feature/[name of feature] develop 

- **Conventional Commits**
Para la redacción de las siguientes convenciones de commits se utilizó de referencia el artículo Conventional Commits 1.0.0. 
Se debe seguir la siguiente estructura para un commit:  
git commit -m “<type>[optional scope]: <title>“ -m “<description>”

Types: 

  - add: se usará para indicar que se añadieron archivos o carpetas. 
  - fix: este tipo de commit se utilizará para la confirmación de una corrección de un error en el código. 
  - feat: este tipo de commit se utilizará para la confirmación de que se ha añadido una nueva funcionalidad. 
  - test: se usará para indicar que se añadieron archivos de test .
  - docs: se usará para indicar que se añadieron actualizaciones a la documentación
  - BREAKING CHANGE: este tipo de commit se utilizará para confirmar la introducción de un cambio importante en el código.

### 6.1.3. Source Code Style Guide & Conventions.

### Guía de Estilo y convenciones de codificación HTML

Para las convenciones de codificación HTML, adoptaremos las pautas delineadas en las referencias "Guía de Estilo y Convenciones de Codificación HTML" y "Guía de Estilo HTML/CSS de Google". Aquí algunos puntos clave:

**Convenciones de Nomenclatura:**

- Aplicar nomenclatura en inglés
- Utilizar letras minúsculas para todos los nombres de elementos HTML.
- Separar palabras en nombres de ID y clases con guiones (-).
- Utilizar nombres significativos y descriptivos para IDs y clases.

**Formato:**

- Sangrar elementos anidados para mejorar la legibilidad.
- Utilizar comillas dobles para los valores de atributos.
- Emplear etiquetas auto-cerradas para elementos.

**Comentarios:**

- Agregar comentarios para explicar secciones complejas o proporcionar contexto a futuros desarrolladores.
- Utilizar la sintaxis de comentarios HTML <!-- -->.

### Guía de Estilo y convenciones de codificación CSS

Para las convenciones de codificación CSS, seguiremos las pautas proporcionadas en la referencia "Google HTML/CSS Style Guide". Aquí tienes algunos puntos clave:

**Convenciones de nomenclatura:**

- Aplicar nomenclatura en inglés
- Usa letras minúsculas para todos los selectores CSS y nombres de propiedades.
- Separa palabras en nombres de clases con guiones (-).
- Utiliza nombres significativos y descriptivos para las clases.

**Formato:**

- Indenta estilos anidados para mejorar la legibilidad.
- Utiliza un estilo de indentación consistente, como dos espacios.
- Usa propiedades abreviadas cuando sea posible para mantener el código conciso.

**Comentarios:**

- Agrega comentarios para explicar estilos complejos o proporcionar contexto para futuros desarrolladores.
- Utiliza la sintaxis de comentarios CSS /* */.

### Guía de Estilo y convenciones de codificación JavaScript/TypeScript

Para las convenciones de codificación JavaScript/TypeScript, adoptaremos las pautas proporcionadas en las referencias "Google JavaScript Style Guide" y "Google TypeScript Style Guide". Aquí tienes algunos puntos clave:

**Convenciones de nomenclatura:**

- Aplicar nomenclatura en inglés
- Utiliza camelCase para nombres de variables y funciones.
- Utiliza PascalCase para nombres de clases.
- Utiliza letras mayúsculas para constantes.

**Formato:**

- Utiliza un estilo de indentación consistente, como dos o cuatro espacios.
- Utiliza punto y coma al final de las sentencias.
- Evita el uso de variables globales siempre que sea posible.

**Comentarios:**

- Agrega comentarios para explicar lógica compleja o proporcionar contexto para futuros desarrolladores.
- Utiliza la sintaxis de comentarios JavaScript/TypeScript // para comentarios de una sola línea y /* */ para comentarios de varias líneas.

### Guía de Estilo y convenciones de codificación Java

Para las convenciones de codificación Java, nos adheriremos a las pautas descritas en la referencia "Google Java Style Guide". Aquí tienes algunos puntos clave:

**Convenciones de nomenclatura:**

- Aplicar nomenclatura en inglés
- Utiliza camelCase para nombres de variables y métodos.
- Utiliza PascalCase para nombres de clases.
- Utiliza letras mayúsculas para constantes.

**Formato:**

- Utiliza un estilo de indentación consistente, como cuatro espacios.
- Coloca las llaves de apertura en la misma línea que la declaración.
- Utiliza nombres significativos para variables y métodos para mayor claridad.

**Comentarios:**

- Agrega comentarios para explicar algoritmos complejos o proporcionar contexto para futuros desarrolladores.
- Utiliza la sintaxis de comentarios Java // para comentarios de una sola línea y /* */ para comentarios de varias líneas.

### 6.1.4. Software Deployment Configuration.

**Despliegue de la landing page en GitHub Pages**

- Ir a la configuración del repositorio

<div align="center">
  <img src="../Resources/deployment/deployment-landing-1.png" width=500 alt="Landing page deployment">
</div>

- Seleccionar la opción "Pages"

<div align="center">
<img src="../Resources/deployment/deployment-landing-2.png" width=500 alt="Landing page deployment">
</div>

- Elegir la rama que se desea desplegar y dar click en "Save"

<div align="center">
<img src="../Resources/deployment/deployment-landing-3.png" width=500 alt="Landing page deployment">
</div>

- Luego de unos segundos se mostrará el enlace de la página en la parte superior

[Enlace a nuestro landing page desplegado](https://techsolutions-2024-i-iot.github.io/chapatubus-landingpage.github.io/)
  
**Despliegue de web application en netlify**

- Elegimos la opción "Add new site"

<div align="center">
  <img src="../Resources/deployment/deployment-frontend-1.png" width=500 alt="Web app deployment">
  </div>
  
- Elegimos importar un projecto existente

<div align="center">
  <img src="../Resources/deployment/deployment-frontend-2.png" width=500 alt="Web app deployment">
  </div>
  
- Seleccionamos la opción "Deploy with github"
  
<div align="center">
  <img src="../Resources/deployment/deployment-frontend-3.png" width=500 alt="Web app deployment">
  </div>
   
- Elegimos el repositorio

<div align="center">
  <img src="../Resources/deployment/deployment-frontend-4.png" width=500 alt="Web app deployment">
  </div>
  
- Revisamos las configuraciones

<div align="center">
  <img src="../Resources/deployment/deployment-frontend-5.png" width=500 alt="Web app deployment">
  </div>
   
- Damos click en deploy

**Despliegue de web service en railway**

**Paso 1: Crear un esquema de MySQL en railway**

- Seleccionar Start a New Project

<div align="center">
  <img src="../Resources/deployment/deployment-backend-1.png" width=500  alt="Web service deployment">
    </div>
  
- Buscar MySql y seleccionarlo

<div align="center">
  <img src="../Resources/deployment/deployment-backend-2.png" width=500  alt="Web service deployment">
    </div>
   
- Se crea la instancia y luego se selecciona en Connect, donde se encontrarán las variables para poder conectarnos a la base de datos.

<div align="center">
  <img src="../Resources/deployment/deployment-backend-3.png" width=500  alt="Web service deployment">
    </div>

**Paso 2: Despliegue de la API**

- En el mismo entorno con click derecho y seleccionamos GitHub Repo

<div align="center">
  <img src="../Resources/deployment/deployment-backend-4.png" width=500  alt="Web service deployment">
    </div>
   
- Luego de ello nos abrirá una ventana pop-up y seleccionaremos el repositorio que queremos desplegar
  
- Luego vamos Settings y generamos el dominio de nuestro servicio

<div align="center">
  <img src="../Resources/deployment/deployment-backend-5.png" width=500  alt="Web service deployment">
    </div>
  
- En la sección Git Repository podemos elegir la rama desde donde queremos que se haga el deploy. Los cambios realizados en esta rama de GitHub se enviarán automáticamente a este entorno.

**Despliegue de mobile application en Firebase**

- Lo primero que debemos hacer es registrar nuestra aplicación en Firebase.

<div align="center">
  <img src="../Resources/deployment/deployment-mobile-1.png" width=500 alt="Mobile deployment">
   </div>
  
- Seleccionamos el tipo de aplicación que deseamos desplegar.

<div align="center">
  <img src="../Resources/deployment/deployment-mobile-2.png" width=500 alt="Mobile deployment">
   </div>

- Vamos a seleccionar la opción de Hosting en el menú lateral izquierdo.

<div align="center">
  <img src="../Resources/deployment/deployment-mobile-3.png" width=500 alt="Mobile deployment">
   </div>

- Procedemos a instalar el CLI de Firebase

<div align="center">
  <img src="../Resources/deployment/deployment-mobile-4.png" width=500 alt="Mobile deployment">
   </div>

- El siguiente paso será situarnos en la carpeta de nuestro proyecto, autenticarnos e inicializarlo.
  
- Una vez hayamos inicializado firebase el siguiente paso será realizar el deploy. Para ello ejecutamos el siguiente comando.

<div align="center">
  <img src="../Resources/deployment/deployment-mobile-5.png" width=500 alt="Mobile deployment">
   </div>
  
## 6.2. Landing Page, Services & Applications Implementation.

### 6.2.1. Sprint 1

#### 6.2.1.1. Sprint Planning 1.

<table border="2">
    <tr>
        <td>
           <p style = "font-weight: bold"><b>Sprint #</b></p>
        </td>
        <td>
          <p style = "font-weight: bold">Sprint 1</p>
        </td>
    </tr>
  <tr>
        <td  colspan="2">
           <p><b>Sprint Planning Background</b></p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Date</p>
        </td>
        <td>
          <p>29-04-2024</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Time</p>
        </td>
        <td>
          <p>21:00</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Location</p>
        </td>
        <td>
          <p>Reunión virtual vía Discord</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Prepared By</p>
        </td>
        <td>
          <p>Tania Sadith Vasquez Sal Y Rosas</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Attendees (to planning meeting)</p>
        </td>
        <td>
          <p>Tania Sadith Vasquez Sal Y Rosas, Andrea Sofia Alfaro Salinas, Diego Martin Merino Mas, Axel Joshue Fiestas Santisteban, Rafael Wimmer Primo Estrada</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Sprint 0 – 1 Review Summary</p>
        </td>
        <td>
          <p>-</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Sprint 0 – 1 Retrospective Summary</p>
        </td>
        <td>
          <p>-</p>
        </td>
    </tr>
   <tr>
        <td  colspan="2">
           <p><b>Sprint Goal & User Stories</b></p>
        </td>
    </tr>
   <tr>
        <td>
           <p>Sprint 1 Goal</p>
        </td>
        <td>
          <p>Desarrollar la landing page y primera versión de la aplicación web del proyecto y lanzarlas a producción</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Sprint 1 Velocity</p>
        </td>
        <td>
          <p>30</p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Sum of Story Points</p>
        </td>
        <td>
          <p>30</p>
        </td>
    </tr>
</table>

#### 6.2.1.2. Sprint Backlog 1.

El objetivo principal del sprint 1 es tener la landing page finalizada y una primera versión
de la aplicación web. Asimismo, tener ambos productos de software desplegados en la internet
también forma parte del alcance del sprint 1, de manera que cualquier persona con acceso a 
internet pueda acceder a la landing page y a la aplicación web.

A continuación, se presenta un screenshot del sprint 1 en desarrollo realizado en Jira por
el equipo:

<div align="center">
  <img src="../Resources/jira-sprints/JiraSprint1Screenshot.png" alt="Jira Sprint 1 Screenshot">
</div>

Asimismo, se presenta la tabla de nuestro primer sprint con las respectivas user stories a trabajar:

| Sprint #   | Sprint 1                                                 |    |       |             |                    |             ||
|:-----------|:---------------------------------------------------------|:---|:------|:------------|:-------------------|:------------| :- |
| User Story | Work-Item /Task                                          |    |       |             |                    |             ||
| Id         | Title                                                    | Id | Title | Description | Estimation (Hours) | Assigned To |Status (To-do / In-Process/ To-Review / Done)|
| US01       | Redirección de la landing Page a tiendas de aplicaciones | 1  | Title | Descripción | 1                  | Persona     |To-Do|
| US02       | Redirección de la landing Page a la aplicación web       | 2  | Title | Descripción | 1                  | Persona     |To-Do|
| US03       | Envío de mensaje a través de un formulario de contacto   | 3  | Title | Descripción | 1                  | Persona     |To-Do|
| US04       | Conocimiento del Equipo desarrollador de la aplicación   | 4  | Title | Descripción | 1                  | Persona     |To-Do|
| US05       | Sección de Preguntas Frecuentes                          | 5  | Title | Descripción | 1                  | Persona     |To-Do|
| US06       | Navegación y Contenido Informativo en el Footer          | 6  | Title | Descripción | 1                  | Persona     |To-Do|
| US07       | Diseño Responsivo de la Landing Page                     | 7  | Title | Descripción | 1                  | Persona     |To-Do|
| US08       | Incorporación de Testimonios en la Landing Page          | 8  | Title | Descripción | 1                  | Persona     |To-Do|
| US09       | Sección de Características del producto                  | 9  | Title | Descripción | 1                  | Persona     |To-Do|
| US10       | Sección de Inicio de la Landing Page                     | 10  | Title | Descripción | 1                  | Persona     |To-Do|


#### 6.2.1.3. Development Evidence for Sprint Review.

#### 6.2.1.4. Testing Suite Evidence for Sprint Review.

| Repository  | Branch  | Commit ID   | Commit Message  | Commit Message Body | Commited on (Date) |
|:-----------|:---------------------------------------------------------|:---|:------|:------------|:-------------------|
| TestingSuite | main | 31836ee | update: sprint 1 testing | -  | 03/05/2023 | 

Para la revisión del Sprint 1, presentamos los Testing Suite Evidence, los cuales se desarrollaron utilizando Gherkin. Esta elección se basó en la simplicidad del proyecto, que consiste en el desarrollo del landing page y la primera versión del front-end. Gherkin proporcionó una forma clara y legible de especificar los comportamientos esperados del sistema a través de escenarios escritos en un lenguaje natural. Esto facilitó la colaboración entre el equipo de desarrollo y los stakeholders al definir y comprender los criterios de aceptación del sprint.

<div align="center">
  <img src="../Resources/sprint-1/testing-1.png" width=500 alt="Testing">   
  <img src="../Resources/sprint-1/testing-2.png" width=500 alt="Testing">
</div>

**Enlace del repositorio:** https://github.com/TechSolutions-2024-I-IOT/TestingSuite

#### 6.2.1.5. Execution Evidence for Sprint Review.

- **Landing Page**

Para el Sprint 1, se logró el desarrollo completo de la landing page, cumpliendo con los objetivos establecidos en cuanto a diseño y funcionalidad. Se implementaron las características acordadas, como la estructura de navegación, la disposición del contenido y la integración de elementos visuales. Además, se realizó una revisión exhaustiva para garantizar la coherencia del diseño y la correcta visualización en diferentes dispositivos y navegadores. El equipo también llevó a cabo pruebas de usabilidad para asegurar una experiencia de usuario fluida y satisfactoria. 

<div align="center">
  <img src="../Resources/sprint-1/development.png" width=500 alt="Execution">   
</div>

- **Web Application**

#### 6.2.1.6. Services Documentation Evidence for Sprint Review.

#### 6.2.1.7. Software Deployment Evidence for Sprint Review.

- **Landing Page**

Para el despliegue de nuestra Landing Page, se eligió Pages pues es una herramienta de GitHub integrada que facilita la publicación de sitios web estáticos directamente desde los repositorios de GitHub. Esto permite una implementación rápida y sencilla sin la necesidad de configurar servidores adicionales ni preocuparse por la infraestructura de alojamiento. Además, Pages es altamente configurable y compatible con dominios personalizados, lo que permite una mayor personalización y profesionalismo en la presentación de nuestro sitio web.

<div align="center">
  <img src="../Resources/sprint-1/pages-1.png" width=500 alt="Mobile deployment">
</div>

Vamos a Pages y en el apartado de "Build and Deployment" elegimos la rama y la carpeta que deseamos desplegar y le damos a "Save"

<div align="center">
  <img src="../Resources/sprint-1/pages-2.png" width=500 alt="Mobile deployment">
</div>

Finalmente se nos muestra el enlace de nuestra Landing Page desplegada con el dominio de GitHub.

<div align="center">
  <img src="../Resources/sprint-1/pages-3.png" width=500 alt="Mobile deployment">
</div>

- **Web Application**

Para el Sprint 1, se avanzó significativamente en el desarrollo del Web Application al implementar las primeras funcionalidades clave. Esto incluyó la creación de la interfaz de usuario inicial, la configuración de la navegación básica y la integración de componentes principales. Además, se llevó a cabo con éxito el despliegue de la primera versión del Web Application en el entorno de producción. Este hito marcó un paso importante hacia el objetivo final del proyecto. Se logró cumplir con los objetivos planteados al inicio del sprint, estableciendo así una base sólida para el desarrollo continuo y la expansión de la aplicación.

#### 6.2.1.8. Team Collaboration Insights during Sprint.

- **Contributors**

<div align="center">
  <img src="../Resources/sprint-1/contributors-sprint-1.png" width=500 alt="Contributors Sprint 1">
</div>

- **Pulse**

<div align="center">
  <img src="../Resources/sprint-1/pulse-sprint-1.png" width=500 alt="Pulse Sprint 1">
</div>

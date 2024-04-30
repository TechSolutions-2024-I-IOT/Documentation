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
           <p>Backend Services</p>
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



### 6.1.3. Source Code Style Guide & Conventions.

### 6.1.4. Software Deployment Configuration.

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
        <td>
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
        <td>
           <p><b>Sprint Goal & User Stories</b></p>
        </td>
    </tr>
   <tr>
        <td>
           <p>Sprint 1 Goal</p>
        </td>
        <td>
          <p></p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Sprint 1 Velocity</p>
        </td>
        <td>
          <p></p>
        </td>
    </tr>
  <tr>
        <td>
           <p>Sum of Story Points</p>
        </td>
        <td>
          <p></p>
        </td>
    </tr>
</table>

#### 6.2.1.2. Sprint Backlog 1.

#### 6.2.1.3. Development Evidence for Sprint Review.

#### 6.2.1.4. Testing Suite Evidence for Sprint Review.

#### 6.2.1.5. Execution Evidence for Sprint Review.

#### 6.2.1.6. Services Documentation Evidence for Sprint Review.

#### 6.2.1.7. Software Deployment Evidence for Sprint Review.

#### 6.2.1.8. Team Collaboration Insights during Sprint.

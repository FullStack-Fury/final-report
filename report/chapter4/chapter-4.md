# Capítulo IV: Product Design
## 4.1. Style Guidelines.

Debido al enfoque de nuestra solución web en la gestión de espacios educativos y administrativos, es necesario que tenga un estilo profesional y organizado, que facilite la navegación y promueva la eficiencia en las tareas de los administradores y docentes.

### 4.1.1. General Style Guidelines.

**Branding design**
<br>
Para la creación del logo de nuestro producto EduSpace, se ha optado por un diseño moderno, utilizando una tipografía clara y legible acompañada por un icono que simboliza la educación, organización y gestión eficiente. </br>

<br> 
<div style="text-align: center;"> 
<img src="https://github.com/user-attachments/assets/5b3c85a9-e4eb-47ab-bfd0-3a2451f85e46" alt="Branding"> 
</div>
</br>


**Colores** 
<br> EduSpace se enfoca en mantener un estilo limpio y profesional, utilizando colores que transmiten confianza y profesionalismo. Estos colores facilitan la lectura y navegación, creando un ambiente visual que apoya la productividad y organización en la gestión educativa. </br>

<br> 
<div style="text-align: center;"> 
<img src="https://github.com/user-attachments/assets/d9f5f793-282f-4652-8035-fcdfc7547daf" alt="Colors"> 
</div>
</br>

**Iconos**
<br> Dado que EduSpace está diseñado para administradores, docentes y personal de apoyo, hemos desarrollado una colección de íconos específicos para mejorar la interfaz del sistema. Estos íconos están destinados a hacer la navegación más intuitiva y alineada con los objetivos del servicio, proporcionando una experiencia visualmente coherente y relevante.</br>

<br> 
<div style="text-align: center;"> 
<img src="https://github.com/user-attachments/assets/847b4f1b-c682-464d-a95f-34be286179ca" alt="icons"> 
</div>
</br>

**Typography**
<br> Para garantizar una apariencia uniforme en el desarrollo de nuestro aplicativo, utilizaremos la fuente Poppins. Elegimos Poppins por su legibilidad, espaciado equilibrado y diseño sin serifas, lo que proporciona una flexibilidad óptima y una experiencia de lectura clara y coherente en todas las plataformas de EduSpace.</br>

<br> 
<div style="text-align: center;"> 
<img src="https://github.com/user-attachments/assets/a0127489-d88b-4281-a7e1-bc0ebda8f0fd" alt="Typography"> 
</div>
</br>

**Spacing**
<br> El espaciado de la plataforma web es importante debido a que no queremos abrumar a nuestros usuarios, ya que nuestra aplicación tiene como objetivo ofrecer una experiencia de usuario sencilla y agradable. Un diseño limpio y organizado mejora la usabilidad y reduce la carga cognitiva del usuario, permitiéndole interactuar de manera eficiente con las diferentes funciones y secciones de la aplicación.</br>

<br>
<div style="text-align: center;"> 
<img src="https://github.com/user-attachments/assets/6ff7fea3-2c58-47c1-9075-9e9d99499bf6" alt="Spacing"> 
</div>
</br>

**Tono de comunicación y lenguaje** 

<br> El tono de comunicación y lenguaje de EduSpace es profesional, claro y directo. Queremos que los usuarios se sientan cómodos al navegar por nuestra plataforma, por lo que utilizamos un lenguaje preciso y accesible que resuene con sus necesidades laborales. Nos dirigimos a ellos con un enfoque que respalda su trabajo, proporcionando la información y herramientas que necesitan para gestionar de manera efectiva sus responsabilidades.</br>


### 4.1.2. Web Style Guidelines.

Para EduSpace, estamos desarrollando una plataforma web que implementará un diseño adaptable (Web Responsive Design) con el objetivo de optimizar la presentación de información en cualquier dispositivo. Esto asegurará que el contenido sea de fácil acceso y navegación, mejorando en última instancia la experiencia del usuario.

Hemos establecido un sistema en el que la información se organiza de manera jerárquica (Visual Hierarchy), particularmente en las secciones principales de la plataforma. Los elementos se disponen dando prioridad a la información más relevante, utilizando tamaños, colores y posiciones distintivas para resaltar los elementos clave.

También utilizaremos un sistema de categorización matricial para la gestión de recursos, permitiendo a los usuarios filtrar resultados según sus necesidades, como la disponibilidad de espacios o el estado de reportes, proporcionando una experiencia más eficiente y personalizada.

Como equipo, hemos optado por incorporar el patrón de diseño en forma de Z en nuestro sitio web. Esta técnica de diseño web es altamente efectiva para mejorar la experiencia del usuario, guiando su atención hacia los elementos clave y potenciando la eficacia del contenido en la página. Por lo general, colocamos el logotipo en la esquina superior izquierda, asegurándonos de que sea lo primero que llame la atención del usuario. Justo enfrente, en la esquina superior derecha, ubicamos la barra de navegación, acompañada de un llamado a la acción destacado.

## 4.2. Information Architecture.

En base a nuestra aplicación, hemos decidido que nuestro diseño y organización visual será jerárquico, para que los usuarios puedan distinguir claramente la importancia de cada funcionalidad de la app. Al mismo tiempo, utilizamos un sistema moderno y sencillo para atraer a los usuarios.

### 4.2.1. Organization Systems.

**Landing Page**

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;"> 
    <tr> 
        <th>Tópico</th> 
        <th>Descripción</th>   
    </tr> 
    <tr> 
        <td>Home</td> 
        <td>La página de inicio muestra una vista general del servicio y destaca las características clave de EduSpace.</td> 
    </tr> 
    <tr> 
        <td>About Us</td> 
        <td>En esta sección, EduSpace explica nuestro compromiso con la gestión eficiente de espacios educativos. También proporcionamos ejemplos de la información detallada que la app web ofrece, como el control de inventario, la automatización de cálculos salariales, y la organización de recursos.</td> 
    </tr> 
    <tr> 
        <td>Packages</td> 
        <td>La página ofrece una descripción detallada de los planes disponibles: un plan para pequeñas infraestructuras y un plan premium para grandes infraestructuras, destacando las funcionalidades avanzadas de cada uno.</td> 
    </tr>  
    <tr> 
        <td>Contact</td> 
        <td>Esta sección proporciona información de contacto para soporte y consultas</td>
    </tr> 
    <tr> 
        <td>Sign In</td> 
        <td>La página para que el usuario ingrese a su cuenta. Aquí se solicitan las credenciales de inicio de sesión y se ofrece la opción de recuperar la contraseña en caso de olvido.</td> 
    </tr> 
    <tr>   
        <td>Sign Up</td> 
        <td>La página para que el usuario se registre en EduSpace. Incluye un formulario para ingresar información básica como nombre, correo electrónico y contraseña, así como la opción de aceptar los términos y condiciones del servicio.</td> 
    </tr> 
</table>

**App web**

App Web

* Tabla de Organización para Administradores

<table border="1" cellpadding="10" cellspacing="0" style="margin-left: auto; margin-right: auto;">
  <tr>
    <th>Feature</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>Home</td>
    <td>Página principal con un resumen de datos clave, como informes recientes, estado de espacios, y notificaciones urgentes.</td>
  </tr>
  <tr>
    <td>Registro de Ambientes</td>
    <td>Registro de espacios deportivos, aulas y otros ambientes, incluyendo detalles como el equipamiento y el docente responsable.</td>
  </tr>
  <tr>
    <td>Gestión de Cambios de Aula y Reuniones</td>
    <td>Permite gestionar y registrar cambios de aula o reuniones, notificando a los docentes y otros usuarios afectados.</td>
  </tr>
  <tr>
    <td>Gestión de Datos de Trabajadores</td>
    <td>Acceso y administración de la información de docentes, personal de limpieza y otros trabajadores, incluyendo datos personales y profesionales.</td>
  </tr>
  <tr>
    <td>Gestión del Personal a Cargo</td>
    <td>Asignación y reasignación de personal responsable de cada espacio, con opciones para reasignar en caso de ausencias.</td>
  </tr>
  <tr>
    <td>Automatización de Cálculos Salariales</td>
    <td>Automatización del cálculo de salarios, incluyendo bonificaciones, descuentos, y retenciones, con opción para visualizar y modificar registros.</td>
  </tr>
  <tr>
    <td>Notificaciones</td>
    <td>Sistema de notificaciones que alerta sobre cambios en los espacios, reportes pendientes, y actualizaciones importantes.</td>
  </tr>
  <tr>
    <td>Perfil</td>
    <td>Acceso a la información personal y profesional del administrador, con opciones para editar datos y visualizar historial de salarios y bonificaciones.</td>
  </tr>
  <tr>
    <td>Cerrar Sesión</td>
    <td>Opción para cerrar sesión de manera segura.</td>
  </tr>
</table>

* Tabla de Organización para Docentes

<table border="1" cellpadding="10" cellspacing="0">
  <tr>
    <th>Feature</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>Home</td>
    <td>Página principal con un resumen de tareas, notificaciones, y un calendario de actividades asignadas.</td>
  </tr>
  <tr>
    <td>Notificaciones de Cambios de Aula o Reuniones</td>
    <td>Alertas sobre cambios de aula o reuniones, incluyendo detalles del nuevo espacio, hora y participantes.</td>
  </tr>
  <tr>
    <td>Reserva de Espacios Deportivos y Ambientes</td>
    <td>Sistema para reservar espacios deportivos y ambientes compartidos, con información sobre disponibilidad y reglas de uso.</td>
  </tr>
  <tr>
    <td>Reporte de Averías en Equipos</td>
    <td>Herramienta para reportar averías o problemas con equipos o recursos del ambiente, con seguimiento del estado de resolución.</td>
  </tr>
  <tr>
    <td>Visualización de Salarios y Bonificaciones</td>
    <td>Acceso a la información sobre salarios, bonificaciones, descuentos y retenciones, con un historial de pagos recibidos.</td>
  </tr>
  <tr>
    <td>Visualización de Espacios Disponibles</td>
    <td>Consulta de los espacios libres, ocupados y sus fechas de disponibilidad, facilitando la planificación de actividades.</td>
  </tr>
  <tr>
    <td>Perfil</td>
    <td>Información personal y profesional del docente, con opciones para editar datos y visualizar historial de salarios y otras compensaciones.</td>
  </tr>
  <tr>
    <td>Cerrar Sesión</td>
    <td>Opción para cerrar sesión de manera segura.</td>
  </tr>
</table>

### 4.2.2. Labeling Systems.

En esta sección, se explica las estrategias empleadas para etiquetar y organizar la información dentro de la plataforma wev EduSpace, buscando mantener la simplicidad y evitar la confusión para los visitantes y usuarios. Las etiquetas se diseñan para ser claras y concisas, utilizando el mínimo número de palabras necesario para representar eficazmente los conjuntos de información y sus asociaciones.

Principios de Etiquetado:

- Claridad: Cada etiqueta debe ser fácilmente comprensible por todos los usuarios, independientemente de su rol (administrador o docente).
- Consistencia: Se mantiene un lenguaje uniforme en todas las secciones de la aplicación para evitar confusión.
- Brevedad: Las etiquetas se formulan con el menor número de palabras posibles sin perder claridad o precisión.

Etiquetas para Administradores:

- Home: Resumen y acceso rápido a funciones clave.
- Environments and Equipment: Registro y gestión de ambientes (aulas, deportivos, etc.).
- Classroom Changes and Meetings: Administración de cambios de aulas o reuniones.
- Personal Data: Gestión de datos y roles de trabajadores.
- Personnel Management: Asignación y reasignación de personal responsable de cada espacio. 
- Salary Calculation: Automatización y visualización de cálculos salariales.
- Notifications: Alertas y actualizaciones importantes.
- Profile: Información personal y profesional del administrador.
- Log Out: Opción para cerrar sesión.

Etiquetas para Docentes:

- Home: Resumen de tareas y calendario de actividades.
- Notifications: Notificaciones sobre cambios de aula o reuniones.
- Reservations: Reserva de espacios deportivos y aulas.
- Breakdown Reports: Reporte de averías en equipos o recursos.
- Wages: Visualización de salarios y bonificaciones.
- Availability: Consulta de espacios disponibles y ocupados.
- Profile: Información personal y profesional del docente.
- Log Out: Opción para cerrar sesión.


Estas etiquetas están diseñadas para facilitar la navegación y comprensión de la plataforma, asegurando que los usuarios puedan acceder rápidamente a las funciones que necesitan, sin tener que interpretar términos complicados o ambiguos. La simplicidad en el etiquetado también ayuda a minimizar el tiempo de aprendizaje y maximiza la eficiencia en el uso de la aplicación.

### 4.2.3. SEO Tags and Meta Tags

Las meta etiquetas nos permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las leen. Estas etiquetas facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido. Además, influyen en el posicionamiento de nuestra página en los motores de búsqueda

- Title: 

<div style="text-align: center;">

```html
<title>EduSpace</title>
```

</div>

- Meta Description: 

<div style="text-align: center;">

```html
<meta name="description" content="Platform that simplifies the management of educational infrastructures."/>
```

</div>


- Meta Keyboard: 

<div style="text-align: center;">

```html
<meta name="keywords" content="Management, platform, optimization, automation, coordination, inventory, reservation, infrastructure, communication"/>
```

</div>

- Meta Author: 

<div style="text-align: center;">

```html
<meta name="author" content="Los ProDevs"/>
<meta name="copyright" content="Copyright EduSpace team" />
```

</div>

### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.


## 4.3. Landing Page UI Design.

EduSpace ha sido diseñado con un enfoque en la simplicidad, claridad y facilidad de navegación para el usuario. A continuación, se detalla cómo se han implementado las decisiones de diseño y la arquitectura de contenido para ofrecer una experiencia intuitiva y fluida a los usuarios: https://www.figma.com/design/Q3cqQ43xjgSDNbMcEt9jFp/Untitled?node-id=0-1&t=Emd2juyWQeysGjnS-1 

### 4.3.1. Landing Page Wireframe.

En esta sección se mostrará una representación de la landing page para Desktop Web Browser y Web Mobile Browser

**Landing Page para Desktop Web Browser:**
<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/e7c861f3-781f-4dc2-bc7a-210a4762b4a0" alt="LP-desktop">
</div>
</br>

**Web Mobile Browser**

<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/016beaa8-5e38-4253-9c81-37a91eb1a3fc" alt="LP-webmobile">
</div>
</br>

### 4.3.2. Landing Page Mock-up.

En esta sección se presentará una representación de la landing page tanto para Desktop Web Browser y Web Mobile Browser

**Landing Page para Desktop Web Browser:**

<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/776cf9ab-2347-4ca2-b9c4-1f5ff35f3ee7" alt="LandingPage">
</div>
</br>

**Web Mobile Browser**

<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/bd85d9ed-7d92-4e22-854b-3ec0c96f0de5" alt="LandingPage">
</div>
</br>

## 4.4. Web Applications UX/UI Design.

El diseño de la experiencia de usuario (UX) y la interfaz de usuario (UI) de EduSpace ha sido desarrollado meticulosamente para ofrecer una plataforma eficiente y fácil de usar tanto para administradores como para docentes. En esta etapa, nos hemos centrado en asegurar una navegación intuitiva, mejorar la accesibilidad y organizar los elementos visuales de manera que simplifiquen la interacción con las múltiples funciones de la plataforma. La elaboración de mockups y wireframes se encuentra en el siguiente link: https://www.figma.com/design/Q3cqQ43xjgSDNbMcEt9jFp/Untitled?node-id=1-906&t=Emd2juyWQeysGjnS-1

### 4.4.1. Web Applications Wireframes.

En esta sección se presentan los wireframes iniciales de la aplicación web de EduSpace, los cuales actúan como una referencia visual para la estructura y el diseño de los elementos en la interfaz. Estos prototipos brindan una visión detallada sobre la disposición de los componentes principales y las interacciones del usuario en distintas pantallas.

<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/38e8e4eb-daac-4c71-9261-168969442799" alt="Web App">
    <img src="https://github.com/user-attachments/assets/59728800-39e0-470d-9850-1990d8c59d75" alt="Web App">
</div>
</br>


### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.


A continuación se exhiben los mock-ups de la aplicación web de EduSpace, que ilustran el diseño visual detallado de las pantallas principales. Estos diseños reflejan la apariencia definitiva de las interfaces para los usuarios, incluyendo el proceso de registro e inicio de sesión, así como los paneles tanto para administradores como para docentes.

**Sign Up and Sign In**

<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/d361d2dd-7a6c-46f1-bd61-1099bc82b459" alt="Web App">
</div>
</br>

**Dashboard Admin**

<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/057a4816-13e9-48fa-ab9b-bfb4e6792343" alt="Web App">
    <img src="https://github.com/user-attachments/assets/2e1c09f1-3107-4eb5-b8a1-ce30c0e2b38b" alt="Web App">
</div>
</br>

**Dashboard Admin**
<br>
<div style="text-align: center;">
    <img src="https://github.com/user-attachments/assets/98214b30-34d2-4506-96bb-9811bed528a4" alt="Web App">
</div>
</br>

### 4.4.3. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.





## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.
### 4.6.2. Software Architecture Container Diagrams.
### 4.6.3. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
### 4.7.2. Class Dictionary.
## 4.8. Database Design.
### 4.8.1. Database Diagram.

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1 Software Configuration Management
A continuación, presentaremos el proceso por el cual organizamos, gestionamos y controlamos los cambios en el desarrollo de este proyecto.
### 5.1.1. Software Development Environment Configuration.
Requirements Management
1. Trello: Es una herramienta utilizada para gestionar el flujo de trabajo de proyectos principalmente basados en marcos de
   trabajos ágiles. Será empleado para visualizar y actualizar el estado actual de las tareas e historias de usuario
   pertenecientes al sprint a desarrollar.  
   Ruta de referencia: https://trello.com/es


Product UX/UI Design

1. Figma: Plataforma de elaboración de prototipos y edición gráfica, principalmente utilizado para el diseño digital. En el
   caso del proyecto, será utilizado para el prototipado de la aplicación y sus versiones de Desktop y Mobile Web Browser.

   Ruta de referencia: https://www.figma.com/login
2. Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de wireflows, user-flows y el diagrama de
   clases asociado a la aplicación.

   Ruta de referencia: https://www.lucidchart.com/


Software Development
1. WebStorm: Entorno de desarrollo integrado elegido por su soporte completo para tecnologías web como JavaScript, HTML, CSS y frameworks como React y Angular. Ofrece refactorización avanzada, depuración, integración con Git y la posibilidad de agregar plugins. Es compatible con varios sistemas operativos, facilitando la colaboración en equipo.

   Ruta de referencia: https://www.jetbrains.com/webstorm/
   <br>
2. HTML5: HyperText Markup Language, o por sus siglas HTML, es un lenguaje de etiquetado para páginas web. Será
   empleado en el desarrollo del proyecto para la presentación del contenido en la aplicación.

   Ruta de referencia: https://www.w3schools.com/html/html5_syntax.asp   
   <br>
3. CSS: Cascading Style Sheets es un lenguaje que maneja el diseño y presentación de las páginas web, el cual va de la mano
   con HTML.

   Ruta de referencia: https://google.github.io/styleguide/htmlcssguide.html
   <br>
   <br>
4. JavaScript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz de
   usuario dentro de la aplicación.

   Ruta de referencia: https://developer.mozilla.org/es/docs/Web/JavaScript

 <br>

5. Git: Una herramienta de control de versiones que facilita el registro y la gestión de las distintas versiones del programa. Su propósito es mantener un historial de cambios y simplificar la corrección de errores. Los integrantes del equipo
   accederán a través de la línea de comandos en sus sistemas locales.

Ruta de referencia: https://git-scm.com/
<br>
<br>
Software Documentation and Project Management
6. Github: Una plataforma en la nube que hospedará los repositorios de código del proyecto. Permitirá la colaboración en
   tiempo real y la revisión de contribuciones de cada miembro del equipo. Los integrantes del equipo podrán acceder a través de sus navegadores web.

   Ruta de referencia: https://github.com/

<br>

Software Deployment

1. Github Pages: GitHub Pages es un servicio de alojamiento web que permite a los usuarios crear y publicar sitios web estáticos directamente desde sus repositorios de GitHub. Es especialmente útil para proyectos personales, portafolios, documentación de proyectos o blogs.

Ruta de referencia: https://pages.github.com/

2. Vercel: es una plataforma que optimiza el proceso de desarrollo y despliegue de aplicaciones web, especialmente con frameworks como Next.js y React. Proporciona un entorno colaborativo que agiliza los despliegues rápidos y genera previsualizaciones automáticas con cada commit, lo que facilita la revisión de modificaciones antes de su publicación.

Ruta de referencia: https://vercel.com/

### 5.1.2. Source Code Management.
El proyecto seguirá las convenciones del flujo de trabajo establecido por el modelo GitFlow para el control de versiones, empleando GitHub como plataforma y sistema de control de versiones. A continuación, se describirá la implementación de GitFlow como un flujo de trabajo para el control de versiones, junto con el enlace del Landing Page.

Repositorio de GitHub:
- Enlace para acceder a la organización en GitHub: https://github.com/pro-devs-SI730
- Enlace para acceder al repositorio de la landing Page: https://github.com/pro-devs-SI730/landing-page
- Enlace para acceder al repositorio del reporte final: https://github.com/pro-devs-SI730/final-report
- Enlace para acceder al repositorio del front end: https://github.com/pro-devs-SI730/eduspace-frontend

Flujo de trabajo GitFlow

El flujo de trabajo a ser implementado para el desarrollo del proyecto se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".

![Flujo-de-trabajo](https://github.com/user-attachments/assets/5e799894-102b-4e74-9200-ca70a21c72a6)

Estructura de branches (Ramas):
1. Master branch (Rama principal): Esta rama servirá como la principal para la aplicación, alojando versiones estables y finales del desarrollo. Únicamente se aceptarán cambios que hayan sido previamente probados y verificados en los features y de ahí en Developer.
2. Develop branch (Rama de desarrollo): El propósito de esta rama es facilitar los avances del proyecto en equipo y mantener los archivos centrales del desarrollo continuo.
3. Feature branch(Ramas de funcionalidad): Cada capitulo desarrollado por el equipo, o separada del enfoque actual del desarrollo, tendrá su propia rama. Una vez que una funcionalidad esté completamente trabajada, se fusionará con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón descriptivo y único, por ejemplo, "feature/chapter-#".
### 5.1.3. Source Code Style Guide & Conventions.
HTML: Algunas de las prácticas que deben de seguirse para alcanzar un código coherente, sostenible y ordenado son las
siguientes:
1. Cerrar todos los elementos HTML: Por ejemplo, <p>Esto es un párrafo.</p>
2. Siempre declarar el tipo de documento en la primera línea del documento, para
   HTML es "<!DOCTYPE html>”.
3. Escribir en una línea los comentarios cortos.
4. Utilizar comillas en caso de que los atributos contengan espacios entre sí.
5. Procurar especificar el texto alt y las dimensiones width y height de las imágenes, ya que de esta manera se facilitará la
   disponibilidad del contenido. Por ejemplo:   <img src="abc.img" alt="image name"  
   style="width:128px;height:128px">
6. Se nos recomienda no usar el espacio al momento de utilizar los signos porque
   es más fácil de leerlo de esta forma.  
   <br>
   HTML: (https://www.w3schools.com/html/html5_syntax.asp)

CSS: Entre las prácticas empleadas se menciona:

1. Se nos recomienda tener una sangría por 2 espacios a la vez, no debemos
   utilizar tabulaciones ni mezclarlas tabulaciones con espacios para la sangría.
2. Todo el código debe estar en minúscula.
3. Eliminar los espacios en blanco.
4. Usar comentarios para explicar el código.
5. Utilizar nombres de clase significativos o genéricos, nombres que reflejen el
   propósito de su elemento.  
   <br>

   CSS: (https://google.github.io/styleguide/htmlcssguide.html)

JavaScrip: Algunas de las mejores prácticas para programar incluyen:

1. Utilizar nombres de variables claros: Es importante que los nombres reflejen el propósito de la variable.
2. Ser consistente con las comillas: Elegir entre comillas simples o dobles y mantener esa elección a lo largo del código.
3. Incluir comentarios explicativos: Usar comentarios para aclarar bloques de código, especialmente en secciones complejas, facilita la comprensión.
4. Minimizar el uso de variables globales: Limitar el ámbito de las variables para evitar conflictos y mejorar la mantenibilidad del código.
5. Encapsular lógica en funciones: Mantener el código modular y reutilizable mediante el uso de funciones.
6. Seguir un estilo de codificación uniforme: Mantener un formato consistente mejora la legibilidad del código.

   JS: (https://www.w3schools.com/js/DEFAULT.asp)

Vue.js: Para asegurar que el código en Vue.js sea claro y eficiente, se recomiendan las siguientes prácticas:

1. Estructura de carpetas organizada: Mantener una estructura clara para components, pages, model y services.
2. Crear componentes reutilizables: Diseñar componentes que puedan ser utilizados en diversas partes de la aplicación.
3. Separar lógica de negocio de la vista: Utilizar métodos y propiedades computadas para mantener la lógica separada de la presentación.
4. Emplear Vue Router para la navegación: Usar Vue Router para gestionar eficazmente la navegación entre vistas.
5. Documentar componentes: Incluir comentarios y documentación sobre props, eventos y métodos dentro de los componentes.

Vue: (https://vuejs.org/guide/introduction)

### 5.1.4. Software Deployment Configuration.
### Landing page deployment:

Para el despliegue de nuestra Landing Page, empleamos GitHub Pages como herramienta de deployment. Creamos un repositorio en GitHub llamado "landing-page" donde alojamos todo el código de la página, realizando el despliegue directamente desde la rama "main". Esta integración permitió un proceso ágil y automatizado, asegurando que cualquier actualización en el código de la rama principal se reflejara inmediatamente en la página en producción.

![](../../assets/Github_Repositorio.PNG)


## GithubPages

Después de crear el repositorio, accedemos a la configuración y seleccionamos la sección de Pages. Allí, ingresamos los datos requeridos, como la fuente del branch que se utilizará para el deployment. Finalmente, GitHub Pages nos proporciona un enlace y publica nuestra Landing Page en la web. Enlace del Landing Page: https://pro-devs-si730.github.io/landing-page/

![](../../assets/Github_Pages.PNG)


### Web App deployment:
Para el despliegue de nuestra web app, utilizamos Vercel como plataforma de hosting y deployment. 
Esta herramienta nos permitió desplegar la aplicación de manera rápida y eficiente, integrándose de
forma sencilla con nuestro repositorio de GitHub.

Primero, creamos un repositorio llamado "eduspace-frontend" en GitHub donde alojamos todo el código de nuestra
aplicación. Luego, vinculamos este repositorio con Vercel, lo que automatiza el proceso de despliegue.
Cada vez que realizamos un push en la rama principal del repositorio, Vercel ejecuta automáticamente el build 
y despliega la nueva versión de la aplicación.

![](../../assets/vercel.PNG)

Después de conectar el repositorio, configuramos
los ajustes de deployment en el panel de Vercel. Especificamos 
la rama "master" como fuente del build. Una vez completado el proceso de deployment, la plataforma
nos proporciona una URL pública donde nuestra web app es accesible 
al público. El enlace para acceder a la web app es:
https://eduspace-frontend-omega.vercel.app

![](../../assets/vercel1.PNG)


### 5.2. Landing Page, Services & Applications Implementation.

## 5.2. Landing Page, Services & Applications Implementation
En esta sección se explicará y evidenciará el proceso de implementación, pruebas,
documentación y despliegue del Landing Page.

### 5.2.1. Sprint 1

### 5.2.1.1. Sprint Planning 1

Para este primer sprint nos enfocaremos en los tasks para la
elaboración de la Landing Page. Nos dividiremos entre nosotros cada
una de las tareas identificadas para el sprint.


| Sprint #                        | Sprint 1                                                                                                                                                         |
|---------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Sprint Planning Background      |                                                                                                                                                                  |
| Date                            | 30/08/2024                                                                                                                                                       |
| Time                            | 06:00 PM                                                                                                                                                         |
| Location                        | Servidor de Discord del Equipo                                                                                                                                   |
| Prepared By                     | Franz Escalante                                                                                                                                                  |
| Attendees (to planning meeting) | Franz Escalante/ Randel Ventura / Gustavo Huanca / Camila Espinoza / Alheli Huapaya                                                                              |
| Sprint 1 Review Summary         | En esta primera seccion se planteo el desarrollo de la Landing Page para el proyecto                                                                             |
| Sprint 1 Retrospective Summary  | En esta seccion todos los integrantes mencionaron tener aciertos en partes del codigo y en otras partes poder mejorar sus habilidades realizando la Landing Page |
| Sprint Goal & User Stories      |
| Sprint 1 Goal                   | Desarrollar, desplegar y hacer visible la landing page con todos sus componentes y similar a los mockup de la aplicación.                                        |
| Sprint 1 Velocity               | 4 Velocity                                                                                                                                                       |
| Sum of Story Points             | 6 Story Points.                                                                                                                                                  |



### 5.2.1.2. Sprint Backlog 1

| User Story Id | User Story Title                                  | Work-Item/Task Id | Work-Item/Task Title                                    | Description                                                                                                  | Estimation | Assigned To | Status |
|---------------|---------------------------------------------------|-------------------|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|------------|-------------|--------|
| US02          | Encontrar información del propósito de la aplicación | UT01              | Barra de tareas con principales propósitos               | Añadir una barra de tareas sencilla y que dirija a las secciones importantes del Landing page                 | 1          | Franz       | Done   |
| US03          | Visualización de imágenes y gráficos relevantes    | UT02              | Añadir header con su imagen                              | Añadir el header con su imagen.                                                                               | 1          | Franz       | Done   |
| US03          | Visualización de imágenes y gráficos relevantes    | UT03              | Añadir sección de características de la aplicación       | Añadir el dashboard de características de la aplicación de administrador y docente                            | 2          | Gustavo     | Done   |
| US04          | Tipografía cómoda y agradable estéticamente        | UT04              | Añadir tipografía con colores verdes y amarillos         | Añadir tipografía que cumpla con lo mostrado en el prototipado                                                | 1          | Franz       | Done   |
| US02          | Encontrar información del propósito de la aplicación | UT05              | Añadir las etiquetas tools                               | Añadir la información sobre las herramientas que proporciona nuestra aplicación.                              | 1          | Ariana      | Done   |
| US01          | Accesibilidad de la aplicación en diferentes dispositivos | UT06              | Crear el diseño del responsive                           | Crear el responsive que garantice una visualización óptima en distintos dispositivos y tamaños de pantalla     | 1          | Camila      | Done   |
| US03          | Visualización de imágenes y gráficos relevantes    | UT07              | Añadir la sección de planes                              | Crear una sección dedicada a dar información sobre los planes de servicio                                     | 1          | Camila      | Done   |
| US02          | Encontrar información del propósito de la aplicación | UT08              | Añadir formulario                                        | Crear una sección dedicada para el Contact Us de la landing page                                              | 1          | Randel      | Done   |

### 5.2.1.3. Development Evidence for Sprint Review

En esta sección se presentan los avances de implementación con relación a los productos desarrollados en el presente Sprint. La implementación que se desarrolló fue la primera version del Landing Page, se implementaron las distintas secciones para conocer más sobre nuestra plataforma. Con ello completamos el primer sprint de implementación.

| Repository | Branch | Commit Id | Commit Message | Commit message body | Committed on |
|------------|--------|-----------|----------------|---------------------|--------------|
| pro-devs-SI730/landing-page | main | 41170e | fix(html): header picture name modified | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | 14c9fbc | feat: button for language added | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | 7b28f6d | feat: spanish html added | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | 4217571 | feat: button for i18n and styles added | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | 4bd2f5a | Merge remote-tracking branch 'origin/develop' into ariana | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | 47ee00e | fix(html): cards position fixed | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | e591222 | fix(landing-page): tools | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | 832490d | feat(dashboard): dashboards added. | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | 870ef91 | feat(landing-page): tools | - | Sep 8, 2024  |
| pro-devs-SI730/landing-page | main | ac9421c | fix(html): camila's section modified | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 6891dca | Merge remote-tracking branch 'origin/randel' into develop | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 8a62faa | feat(footer): added footer section. | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 14ae088 | feat(contact-us): added contact-us form section. | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 2f1f09e | feat(membership/customers): advance customers section in index.html, styles.css and main.js | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | bf43c8b | feat(css): About us styles | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 9cad35c | feat(css): about section finished | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | ea8503f | feat(css): all css | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 5f8a664 | fix(html): title of hero fixed | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 70e2564 | feat(html): footer, contactus and plan section added | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 71c8e7e | feat(html): abut section added | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 7592218 | feat(html): hero added | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 6b8c528 | feat(html): navbar styles added | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | 1d8c5db | feat(html): navbar added | - | Sep 7, 2024  |
| pro-devs-SI730/landing-page | main | bea1a65 | chore: first commit | - | Sep 7, 2024  |



### 5.2.1.4. Testing Suite Evidence for Sprint Review

Para la entrega de este primer Sprint no se realizo testeo de la landing page.

### 5.2.1.5. Execution Evidence for Sprint Review

Para este primer entregable, hemos elaborado la Landing Page del proyecto de "EduSpace". De tal modo, se podrá visualizar la información relevante sobre nuestra plataforma. En el siguiente enlace se tendra el video que ilustre y explique la visualización y navegación logrados en este Sprint: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202214572_upc_edu_pe/EWCZa2Zz0h9EskkkItqhT_oBbx0Z7EluzJkLUkluMIJ2zA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=xMGbtN

US02-Encontrar información del propósito de la aplicación

![](../../assets/landing1.PNG)

US02-Encontrar información del propósito de la aplicación

![](../../assets/landing2.PNG)

US04-Tipografía cómoda y agradable estéticamente

![](../../assets/landing3.PNG)


US03-Visualización de imágenes y gráficos relevantes

![](../../assets/landing5.PNG)

![](../../assets/landing4.PNG)

US01-Accesibilidad de la aplicación en diferentes dispositivos

![](../../assets/landing6.PNG)

US03-Visualización de imágenes y gráficos relevantes

![](../../assets/landing7.PNG)

US02-Encontrar información del propósito de la aplicación

![](../../assets/landing8.PNG)

### 5.2.1.6. Services Documentation Evidence for Sprint Review

En el presente sprint solo se desarrollo la Landing Page.

### 5.2.1.7. Software Deployment Evidence for Sprint Review

<p> Utilizamos Github Pages para el despligue de la <a href="https://pro-devs-si730.github.io/landing-page/">Landing Page de la Aplicación.</a></p>
<p> Link URL de la Landing Page : <a href="https://pro-devs-si730.github.io/landing-page/">https://pro-devs-si730.github.io/landing-page/</a></p>

![URL](https://github.com/user-attachments/assets/6720aa9a-fa10-41f4-9649-acdf33786c04)

![alt text](../../assets/screen-lp.png)

### 5.2.1.8. Team Collaboration Insights during Sprint

Para el desarrollo de este primer sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.

Colaboraciones de cada miembro del equipo:

<table>
   <tr>
      <th><strong>Alumno</th>
      <th><strong>Actividad</th>
   </tr>
   <tr>
      <td>Janiel Franz Escalante Baygorrea</td>
      <td>Implementación del encabezado y vista Brief Introduction y About Us</td>
   </tr>
   <tr>
      <td>Huapaya Buitron, Ariana Alheli</td>
      <td>Implementación de la sección tools y vista de Planes</td>
   </tr>
   <tr>
      <td>Huanca Navarro Gustavo Esau</td>
      <td>Imlementación de la vista Dashboard Admin y Education</td>
   </tr>
   <tr>
      <td>Camila Leonor, Espinoza Vivas</td>
      <td>Imlpementación de la vista Valoraciones y Vista de Planes</td>
   </tr>
   <tr>
      <td>Randel Russell Ventura Allasi</td>
      <td>Implementación de la sección Contact Us y Footer</td>
   </tr>   
</table>

Commits:

![alt text](../../assets/Insights.PNG)

Analiticas de Colaboración:

![alt text](../../assets/AnaliticasLanding.PNG)







### 5.2.2. Sprint 2

### 5.2.2.1. Sprint Planning 2

Para este segundo sprint


| Sprint #                        | Sprint 2                                                                             |
|---------------------------------|--------------------------------------------------------------------------------------|
| Sprint Planning Background      |                                                                                      |
| Date                            | 22/09/2024                                                                           |
| Time                            | 06:00 PM                                                                             |
| Location                        | Servidor de Discord del Equipo                                                       |
| Prepared By                     | Franz Escalante                                                                      |
| Attendees (to planning meeting) | Franz Escalante/ R andel Ventura / Gustavo Huanca / Camila Espinoza / Alheli Huapaya |
| Sprint 1 Review Summary         |                                                                                      |
| Sprint 1 Retrospective Summary  |                                                                                      |
| Sprint Goal & User Stories      |
| Sprint 1 Goal                   |                                                                                      |
| Sprint 1 Velocity               | 4 Velocity                                                                           |
| Sum of Story Points             | 4 Story Points.                                                                      |



### 5.2.2.2. Sprint Backlog 2

<table>
  <tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 2</th>
  </tr>
  <tr>
    <td colspan="3">User Story</td>
    <td colspan="10">Work-Item/Task</td>
  </tr>
  <tr>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="1">Id</td>
    <td colspan="2">Title</td>
    <td colspan="3">Description</td>
    <td colspan="1">Estimation</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status (To-do /InProcess /To-Review /Done)</td>
  </tr>
  <tr>
    <td colspan="1">US08</td>
    <td colspan="2">Registro de información personal del docente</td>
    <td colspan="1">TSK001</td>
    <td colspan="2">Formulario de registro</td>
    <td colspan="3">Desarrollar un formulario que permita a los docentes ingresar su información personal, incluyendo nombre, apellidos, etc.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
  <tr>
    <td colspan="1">US09</td>
    <td colspan="2">Registro de información de acceso del docente</td>
    <td colspan="1">TSK002</td>
    <td colspan="2">Gestión de credenciales</td>
    <td colspan="3">Implementar un sistema para que los administradores creen y gestionen los credenciales de acceso al sistema para los docentes.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
  <tr>
    <td colspan="1">US10</td>
    <td colspan="2">Registro de salones</td>
    <td colspan="1">TSK003</td>
    <td colspan="2">Registro de aulas</td>
    <td colspan="3">Crear un módulo para registrar y gestionar información sobre las aulas disponibles, incluyendo capacidad y equipamiento.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
   <tr>
    <td colspan="1">US11</td>
    <td colspan="2">Registro de espacios compartidos</td>
    <td colspan="1">TSK004</td>
    <td colspan="2">Módulo de espacios</td>
    <td colspan="3">Desarrollar un módulo que permita el registro de espacios compartidos y su disponibilidad.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
   <tr>
    <td colspan="1">US12</td>
    <td colspan="2">Registro de horarios de espacios compartidos</td>
    <td colspan="1">TSK005</td>
    <td colspan="2">Gestión de horarios</td>
    <td colspan="3">Implementar un sistema para registrar los horarios de uso de los espacios compartidos y su disponibilidad.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
   <tr>
    <td colspan="1">US13</td>
    <td colspan="2">Registro de la hora y lugar de la reunión</td>
    <td colspan="1">TSK006</td>
    <td colspan="2">Registro de reuniones</td>
    <td colspan="3">Desarrollar un formulario para que los administradores registren la hora y lugar de las reuniones que organizan.</td>
    <td colspan="1">5</td>
    <td colspan="2">Camila Espinoza</td>
    <td colspan="1">Done</td>
  </tr>
   <tr>
    <td colspan="1">US14</td>
    <td colspan="2">Registro de invitados de la reunión</td>
    <td colspan="1">TSK007</td>
    <td colspan="2">Módulo de invitados</td>
    <td colspan="3">Implementar un sistema para que los administradores registren los invitados a las reuniones, con sus datos de nombre.</td>
    <td colspan="1">2</td>
    <td colspan="2">Camila Espinoza</td>
    <td colspan="1">Done</td>
  </tr>
   <tr>
    <td colspan="1">US24</td>
    <td colspan="2">Visualización de espacios compartidos</td>
    <td colspan="1">TSK008</td>
    <td colspan="2">Vista de espacios</td>
    <td colspan="3">Desarrollar una vista que permita a los docentes visualizar los espacios compartidos disponibles y su estado.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
   <tr>
    <td colspan="1">US25</td>
    <td colspan="2">Registro de salones</td>
    <td colspan="1">TSK009</td>
    <td colspan="2">Sistema de registro de salones</td>
    <td colspan="3">Crear un sistema que permita a los administradores registrar salones</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
   <tr>
    <td colspan="1">US25</td>
    <td colspan="2">Reserva de espacios compartidos</td>
    <td colspan="1">TSK010</td>
    <td colspan="2">Sistema de reservas</td>
    <td colspan="3">Crear un sistema que permita a los docentes reservar espacios compartidos de forma sencilla y eficiente.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
   <tr>
    <td colspan="1">US19</td>
    <td colspan="2">Ingreso de salarios del docente</td>
    <td colspan="1">TSK011</td>
    <td colspan="2">Registro de salarios</td>
    <td colspan="3">Desarrollar un módulo que permita el ingreso y actualización de los salarios de los docentes.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
    <tr>
    <td colspan="1">US20</td>
    <td colspan="2">Envío de salarios a docentes</td>
    <td colspan="1">TSK012</td>
    <td colspan="2">Sistema de envío de salarios</td>
    <td colspan="3">Crear un sistema que facilite el envío de salarios a los docentes de manera automatizada.</td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
</table>


### 5.2.2.3. Development Evidence for Sprint Review

En esta sección se presentan los avances de implementación con relación a los productos desarrollados en el presente Sprint.


| Repository | Branch | Commit Id | Commit Message | Commit message body | Committed on |
|------------|--------|-----------|----------------|---------------------|--------------|
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |        |           |                |                     |              |
|            |


### 5.2.2.4. Testing Suite Evidence for Sprint Review

Para la entrega de este primer Sprint no se realizo testeo de la landing page.

### 5.2.2.5. Execution Evidence for Sprint Review

Para este segundo entregable, hemos elaborado el front-end del proyecto de "EduSpace".



### 5.2.2.6. Services Documentation Evidence for Sprint Review

En el presente sprint solo se desarrollo la Landing Page.

### 5.2.1.7. Software Deployment Evidence for Sprint Review



### 5.2.2.8. Team Collaboration Insights during Sprint

Para el desarrollo de este segundo sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.

Commits:


Analiticas de Colaboración:











# Conclusiones

- El equipo trabajó de manera efectiva tanto en sesiones presenciales como remotas. La participación activa de todos los miembros en reuniones indica un fuerte compromiso con el proyecto. La delegación clara de responsabilidades y la asignación de tareas específicas, muestran un enfoque organizado que permite que cada miembro aporte su experiencia y habilidades de manera óptima.

- Se establecieron medios de comunicación efectivos, lo que permitió mantener a todos los miembros del equipo informados y alineados. Esto fue fundamental para el trabajo donde la coordinación y la colaboración son clave. Las revisiones continuas de los avances y la retroalimentación constructiva indicaron un ambiente de aprendizaje donde cada miembro tuvo la oportunidad de mejorar y contribuir al desarrollo del trabajo.

- La planificación de tareas desde el principio y el establecimiento de metas claras reflejan un enfoque proactivo. Esto no solo ayuda a mantener el rumbo, sino que también permite hacer ajustes en función del progreso observado. La organización de la documentación principal y la estructura del informe del trabajo demuestran un compromiso con la claridad y la calidad, aspectos importantes para la presentación final del proyecto.

# Bibliografia
- Conne, M(2024). The Markdown Guide. MarkdownGuide. Recuperado de: https://www.markdownguide.org/
- Facilio. (2024). Facilio: Platform for facilities management. Recuperado de https://facilio.com/
- FMX. (2024). Facilities Management eXpress: Software para la gestión de instalaciones. Recuperado de https://www.gofmx.com/
- Archibus. (2024). Archibus: Complete facilities management platform. Recuperado de https://archibus.com/

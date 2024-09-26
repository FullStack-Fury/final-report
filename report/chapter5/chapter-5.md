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


### 5.1.2. Source Code Management.
El proyecto seguirá las convenciones del flujo de trabajo establecido por el modelo GitFlow para el control de versiones, empleando GitHub como plataforma y sistema de control de versiones. A continuación, se describirá la implementación de GitFlow como un flujo de trabajo para el control de versiones, junto con el enlace del Landing Page.

Repositorio de GitHub:
- Enlace para acceder a la organización en GitHub: https://github.com/pro-devs-SI730
- Enlace para acceder al repositorio de la landing Page: https://github.com/pro-devs-SI730/landing-page
- Enlace para acceder al repositorio del reporte final: https://github.com/pro-devs-SI730/final-report

Flujo de trabajo GitFlow

El flujo de trabajo a ser implementado para el desarrollo del proyecto se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".

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



### 5.1.4. Software Deployment Configuration.
### Landing page deployment:

Para el despliegue de nuestra Landing Page, empleamos GitHub Pages como herramienta de deployment. Creamos un repositorio en GitHub llamado "landing-page" donde alojamos todo el código de la página, realizando el despliegue directamente desde la rama "main". Esta integración permitió un proceso ágil y automatizado, asegurando que cualquier actualización en el código de la rama principal se reflejara inmediatamente en la página en producción.

![](../../assets/Github_Repositorio.PNG)
   

## GithubPages

Después de crear el repositorio, accedemos a la configuración y seleccionamos la sección de Pages. Allí, ingresamos los datos requeridos, como la fuente del branch que se utilizará para el deployment. Finalmente, GitHub Pages nos proporciona un enlace y publica nuestra Landing Page en la web. Enlace del Landing Page: https://pro-devs-si730.github.io/landing-page/

![](../../assets/Github_Pages.PNG)

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

<table>
<tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 1</th>
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
    <td colspan="1"> Estimation</td>
    <td colspan="2">Assigned To</td>
    <td colspan="1">Status(To-do /InProcess /To-Review /Done)</td>
</tr>
  <tr>
    <td colspan="1">US02</td>
    <td colspan="2">Encontrar información del propósito de la aplicación</td>
    <td colspan="1">1</td>
    <td colspan="2">Añadir información relevante de la aplicación</td>
    <td colspan="3">Como visitante de la Landing Page, quiero encontrar fácilmente la información que explique el propósito de la aplicación para comprender cómo puede ser útil para mí.</td>
    <td colspan="1">2</td>
    <td colspan="2">Franz, Gustavo, Camila, Ariana,Randel </td>
    <td colspan="1">Done</td>
  </tr>
  <tr>
    <td colspan="1">US03</td>
    <td colspan="2">Visualización de imágenes y gráficos relevantes</td>
    <td colspan="1">2</td>
    <td colspan="2">Añadir imágenes y gráficos relevantes</td>
    <td colspan="3">Como visitante de la Landing Page, quiero que las imágenes y gráficos sean claros y visualmente atractivos para captar mi interés y comprender mejor el contenido.</td>
    <td colspan="1">1</td>
    <td colspan="2">Franz</td>
    <td colspan="1">Done</td>
<tr>
    <td colspan="1">US04</td>
    <td colspan="2">Tipografía cómoda y agradable estéticamente</td>
    <td colspan="1">3</td>
    <td colspan="2">Añadir una tipografía fácil de leer y con un tamaño adecuado</td>
    <td colspan="3">Como visitante de la Landing Page, quiero que la tipografía de la misma sea legible y estéticamente agradable para facilitar la lectura y la navegación.</td>
    <td colspan="1">1</td>
    <td colspan="2">Camila</td>
    <td colspan="1">Done</td>
</tr>
</table>

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

Para este primer entregable, hemos elaborado la Landing Page del proyecto de "EduSpace". De tal modo, se podrá visualizar la información relevante sobre nuestra plataforma.

Sección de Inicio: Se implementó el Header y la página principal de nuestra Landing Page.

![](../../assets/landing1.PNG)

Sección de About Us: Se implementó la sección de la About Us detallando el propósito del proyecto.

![](../../assets/landing2.PNG)

Sección Tools: Se implementó la sección de las herramientas ofrecidas.

![](../../assets/landing3.PNG)


Sección de Dashboard: Se implementó la sección de ver los dashboards del administrado y docente.

![](../../assets/landing5.PNG)

![](../../assets/landing4.PNG)

Sección de What our customers saying: Se añadió la sección de reseñas.

![](../../assets/landing6.PNG)

Sección Plans: Se implementó la sección de los planes disponibles.

![](../../assets/landing7.PNG)

Sección Contact Us: Se implementó la sección que permite contactarnos.

![](../../assets/landing8.PNG)

### 5.2.1.6. Services Documentation Evidence for Sprint Review

En el presente sprint solo se desarrollo la Landing Page.

### 5.2.1.7. Software Deployment Evidence for Sprint Review

<p> Utilizamos Github Pages para el despligue de la <a href="https://pro-devs-si730.github.io/landing-page/">Landing Page de la Aplicación.</a></p>
<p> Link URL de la Landing Page : <a href="https://pro-devs-si730.github.io/landing-page/">https://pro-devs-si730.github.io/landing-page/</a></p>

![alt text](../../assets/screen-lp.png)

### 5.2.1.8. Team Collaboration Insights during Sprint

Para el desarrollo de este primer sprint, todos los miembros del equipo desarrollaron y colaboraron de manera activa y continua. De tal modo, se muestra como evidencia los insights de cada miembro del equipo.

Commits:

![alt text](../../assets/Insights.png)

Analiticas de Colaboración:

![alt text](../../assets/AnaliticasLanding.png)







### 5.2.2. Sprint 2

### 5.2.2.1. Sprint Planning 1

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



### 5.2.2.2. Sprint Backlog 1

<table>
  <tr>
    <th colspan="3">Sprint #</th>
    <th colspan="10">Sprint 1</th>
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
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="3"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
  <tr>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="3"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
  </tr>
  <tr>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="1"></td>
    <td colspan="2"></td>
    <td colspan="3"></td>
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


En conclusión, EduSpace

# Bibliografia
- Conne, M(2024). The Markdown Guide. MarkdownGuide. Recuperado de: https://www.markdownguide.org/

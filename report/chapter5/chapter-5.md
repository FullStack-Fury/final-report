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
   
3. Lucidchart: Aplicación para diagramar flujos. Será empleado para el diseño de wireflows, user-flows y el diagrama de
   clases asociado a la aplicación.

   Ruta de referencia: https://www.lucidchart.com/


Software Development

1. WebStorm: Entorno de desarrollo integrado elegido por su soporte completo para tecnologías web como JavaScript, HTML, CSS y frameworks como React y Angular. Ofrece refactorización avanzada, depuración, integración con Git y la posibilidad de agregar plugins. Es compatible con varios sistemas operativos, facilitando la colaboración en equipo.

   Ruta de referencia: https://www.jetbrains.com/webstorm/
   
3. HTML5: HyperText Markup Language, o por sus siglas HTML, es un lenguaje de etiquetado para páginas web. Será
   empleado en el desarrollo del proyecto para la presentación del contenido en la aplicación.

   Ruta de referencia: https://www.w3schools.com/html/html5_syntax.asp   

5. CSS: Cascading Style Sheets es un lenguaje que maneja el diseño y presentación de las páginas web, el cual va de la mano
   con HTML.

   Ruta de referencia: https://google.github.io/styleguide/htmlcssguide.html

7. JavaScript: Es un lenguaje de programación interpretado y orientado a objetos. Se utilizará para elaborar la interfaz de
   usuario dentro de la aplicación.

   Ruta de referencia: https://developer.mozilla.org/es/docs/Web/JavaScript

9. Git: Una herramienta de control de versiones que facilita el registro y la gestión de las distintas versiones del programa. Su propósito es mantener un historial de cambios y simplificar la corrección de errores. Los integrantes del equipo
   accederán a través de la línea de comandos en sus sistemas locales.

   Ruta de referencia: https://git-scm.com/

Software Deployment

1. Github Pages: GitHub Pages es un servicio de alojamiento web que permite a los usuarios crear y publicar sitios web estáticos directamente desde sus repositorios de GitHub. Es especialmente útil para proyectos personales, portafolios, documentación de proyectos o blogs.

   Ruta de referencia: https://pages.github.com/

3. Vercel: es una plataforma que optimiza el proceso de desarrollo y despliegue de aplicaciones web, especialmente con frameworks como Next.js y React. Proporciona un entorno colaborativo que agiliza los despliegues rápidos y genera previsualizaciones automáticas con cada commit, lo que facilita la revisión de modificaciones antes de su publicación.

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
3. Feature branch(Ramas de funcionalidad): Cada capitulo desarrollado por el equipo, o separada del enfoque actual del desarrollo, tendrá su propia rama. Una vez que una funcionalidad esté completamente trabajada, se fusionará con la rama de desarrollo del proyecto. Las convenciones para nombrar las ramas de funcionalidad seguirán un patrón descriptivo y único, por ejemplo, "".

### 5.1.3. Source Code Style Guide & Conventions.
HTML: Algunas de las prácticas que deben de seguirse para alcanzar un código coherente, sostenible y ordenado son las
siguientes:
1. Cerrar todos los elementos HTML: Por ejemplo, `<p>Esto es un párrafo.</p>`.
2. Siempre declarar el tipo de documento en la primera línea del documento, para
   HTML es `<!DOCTYPE html>`.
3. Escribir en una línea los comentarios cortos.
4. Utilizar comillas en caso de que los atributos contengan espacios entre sí.
5. Procurar especificar el texto alt y las dimensiones width y height de las imágenes, ya que de esta manera se facilitará la
   disponibilidad del contenido. Por ejemplo: `<img src="abc.img" alt="image name" style="width:128px;height:128px">`
6. Se nos recomienda no usar el espacio al momento de utilizar los signos porque
   es más fácil de leerlo de esta forma.  

   HTML: (https://www.w3schools.com/html/html5_syntax.asp)

CSS: Entre las prácticas empleadas se menciona:

1. Se nos recomienda tener una sangría por 2 espacios a la vez, no debemos
   utilizar tabulaciones ni mezclarlas tabulaciones con espacios para la sangría.
2. Todo el código debe estar en minúscula.
3. Eliminar los espacios en blanco.
4. Usar comentarios para explicar el código.
5. Utilizar nombres de clase significativos o genéricos, nombres que reflejen el
   propósito de su elemento.  

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

![URL](https://github.com/user-attachments/assets/6720aa9a-fa10-41f4-9649-acdf33786c04)


## GithubPages

Después de crear el repositorio, accedemos a la configuración y seleccionamos la sección de Pages. Allí, ingresamos los datos requeridos, como la fuente del branch que se utilizará para el deployment. Finalmente, GitHub Pages nos proporciona un enlace y publica nuestra Landing Page en la web. Enlace del Landing Page: https://pro-devs-si730.github.io/landing-page/

![](../../assets/Github_Pages.PNG)


# Conclusiones

- El equipo trabajó de manera efectiva tanto en sesiones presenciales como remotas, lo que sugiere una buena dinámica de trabajo en equipo. La participación activa de todos los miembros en reuniones indica un fuerte compromiso con el proyecto. La delegación clara de responsabilidades y la asignación de tareas específicas, muestran un enfoque organizado que permite que cada miembro aporte su experiencia y habilidades de manera óptima.

- Se establecieron medios de comunicación efectivos, lo que permitió mantener a todos los miembros del equipo informados y alineados. Esto fue funadmental para proyectos donde la coordinación y la colaboración fueron  clave. Las revisiones continuas de los avances y la retroalimentación constructiva indican un ambiente de aprendizaje donde cada miembro tiene la oportunidad de mejorar y contribuir al desarrollo del proyecto.

- La planificación de tareas desde el principio y el establecimiento de metas claras reflejan un enfoque proactivo. Esto no solo ayuda a mantener el rumbo, sino que también permite hacer ajustes en función del progreso observado. La organización de la documentación principal y la estructura del informe del trabajo demuestran un compromiso con la claridad y la calidad, aspectos importantes para la presentación final del proyecto.

# Bibliografía 

Conne, M(2024). The Markdown Guide. MarkdownGuide. Recuperado de: https://www.markdownguide.org/

Facilio. (2024). Facilio: Platform for facilities management. Recuperado de https://facilio.com/

FMX. (2024). Facilities Management eXpress: Software para la gestión de instalaciones. Recuperado de https://www.gofmx.com/

Archibus. (2024). Archibus: Complete facilities management platform. Recuperado de https://archibus.com/



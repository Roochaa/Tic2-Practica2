Tic2-Practica1
 
Estudios Post-Bachillerato


1. OBJETIVO DEL PROYECTO
El objetivo de esta web es comparar tres grados universitarios relacionados con el ámbito de la salud: Medicina, Enfermería y Odontología.


La página permite conocer la duración de cada carrera, las asignaturas principales, los requisitos de acceso, las notas de corte de referencia y las posibles salidas profesionales. La información está centrada en universidades públicas de Galicia, principalmente la Universidade de Santiago de Compostela (USC) y la Universidade da Coruña (UDC).


2. OPCIONES ELEGIDAS


* Medicina: Grado en Medicina de la USC, en Santiago de Compostela.
* Enfermería: Grado en Enfermería de la UDC, en Ferrol.
* Odontología: Grado en Odontología de la USC, en Santiago de Compostela.


3. ESTRUCTURA DE LOS ARCHIVOS
El proyecto está organizado de la siguiente manera:


* index.html: Portada de la web, presentación, tarjetas de los tres grados y acordeón con competencias, ventajas y desventajas.
* opciones.html: Acceso a la universidad, notas de corte, tabla comparativa adaptativa y fichas breves de las carreras.
* salidas.html: Salidas profesionales detalladas, recorridos de acceso en tres pasos y conclusión comparativa.
* css/estilos.css: Hoja de estilos propia para definir la identidad visual sanitaria, los espacios, los tamaños, el modelo de caja, el foco de accesibilidad y las media queries.
* img/: Carpeta con las imágenes y símbolos gráficos utilizados en las páginas.
* evidencias/: Carpeta para guardar las capturas de pantalla de las pruebas de la web en diferentes anchos de pantalla.


4. CÓMO ABRIR LA WEB
Para abrir el proyecto, hay que descargar o clonar el repositorio y abrir la carpeta tic2-practica02 en el ordenador.


Después, se puede abrir el archivo index.html con un navegador web moderno (como Google Chrome o Microsoft Edge). Las otras páginas se pueden consultar de forma fluida mediante el menú superior de navegación. Se necesita conexión a Internet para cargar Bootstrap desde su CDN oficial.


5. VERSIÓN DE BOOTSTRAP Y USO DE LA BIBLIOTECA
Se utiliza Bootstrap 5.3.8, cargado mediante CDN oficial. En las páginas HTML se incluye el enlace a la hoja de estilos CSS y el archivo JavaScript correspondiente (bootstrap.bundle.min.js) para garantizar el correcto funcionamiento del menú desplegable en dispositivos móviles.


¿Qué aporta Bootstrap y qué se ha hecho de forma propia?


* Lo que aporta Bootstrap: Proporciona la retícula adaptativa (container, row, col), los componentes visuales ya estructurados (como las tarjetas card, los botones btn y el menú desplegable navbar), y clases de utilidad para que elementos complejos como la tabla comparativa se adapten mediante table-responsive.
* Lo que se ha hecho de forma propia (Alumno): El diseño visual personalizado e identidad cromática de la web (paleta de tonos clínicos y sanitarios limpios), el control detallado del modelo de caja (margin, padding, border), la adaptación responsiva mediante reglas media queries, la mejora de la accesibilidad con contornos de foco visibles para teclado (:focus-visible), así como la redacción, selección y estructuración de todos los contenidos académicos y fuentes oficiales.


6. FUENTES OFICIALES
Las fuentes utilizadas para investigar la información son las páginas oficiales de las universidades y organismos correspondientes.


Medicina


1. USC - Grado en Medicina:
[https://www.usc.gal/es/estudios/grados/ciencias-salud/grado-medicina](https://www.usc.gal/es/estudios/grados/ciencias-salud/grado-medicina)
2. USC - Indicadores del Grado en Medicina:
[https://assets.usc.gal/es/centro/facultad-medicina-odontologia/calidad/indicadores/grado-medicina](https://assets.usc.gal/es/centro/facultad-medicina-odontologia/calidad/indicadores/grado-medicina)


Enfermería
3. UDC - Plan de estudios de Enfermería:


[https://www.udc.gal/fep/planestudos/enfermaria/](https://www.udc.gal/fep/planestudos/enfermaria/)
4. UDC - Materias del Grado en Enfermería:


[https://www.udc.gal/es/biblioteca.oza/BR/br_enfermeria/](https://www.udc.gal/es/biblioteca.oza/BR/br_enfermeria/)


Odontología
5. USC - Grado en Odontología:


[https://www.usc.gal/es/estudios/grados/ciencias-salud/grado-odontologia](https://www.usc.gal/es/estudios/grados/ciencias-salud/grado-odontologia)
6. USC - Documentación complementaria de Odontología:


[https://assets.usc.gal/sites/default/files/paragraphs/links/2025-04/grao-en-odontologia-requisitos-mobilidade-in.pdf](https://assets.usc.gal/sites/default/files/paragraphs/links/2025-04/grao-en-odontologia-requisitos-mobilidade-in.pdf)


Información adicional


* Comisión Interuniversitaria de Galicia (CIUG) para admisión y notas de corte:
[https://www.ciug.gal/admision-sug](https://www.ciug.gal/admision-sug)
(Nota: Las cifras de notas de corte se presentan como referencias históricas del curso de referencia y deben comprobarse en las publicaciones oficiales de cada convocatoria).


7. CRÉDITOS Y LICENCIAS
Las ilustraciones y recursos gráficos de la carpeta img/ se han adaptado para este proyecto. Los textos se han redactado y estructurado para una actividad educativa a partir de la información consultada en las páginas oficiales universitarias. No se han incorporado fotografías de terceros con restricciones de autoría.
8. DECISIONES TÉCNICAS


* HTML: Uso riguroso de etiquetas semánticas (header, nav, main, section, footer), encabezados ordenados jerárquicamente, párrafos, listas y tablas estructuradas con caption, thead, tbody y celdas con scope.
* CSS: Hoja de estilos externa propia (css/estilos.css) estructurada mediante selectores de etiqueta, clase y descendientes, demostrando el manejo del modelo de caja, colores adaptados al sector sanitario y accesibilidad por teclado.
* Bootstrap: Implementación uniforme de la versión 5.3.8 en las tres pantallas para garantizar consistencia y usabilidad en dispositivos móviles y de escritorio.


9. PRUEBAS DE LA WEB
Antes de la entrega final, se han verificado los siguientes puntos de control:


* La portada y las tres páginas se visualizan correctamente.
* El menú superior permite acceder sin errores a todas las secciones.
* Los enlaces a las fuentes oficiales de la USC, UDC y CIUG funcionan.
* Las imágenes se muestran proporcionadas y unificadas en tamaño.
* La tabla comparativa cuenta con desplazamiento horizontal en móvil (table-responsive).
* El menú desplegable funciona de forma táctil en dispositivos móviles.
* Se ha comprobado la visualización a 390 px (móvil), 768 px (tableta) y 1280 px (escritorio).
* Se ha comprobado la accesibilidad mediante la navegación por teclado (Tab).
* Se ha validado la correcta estructura de los documentos HTML.


10. ERRORES CORREGIDOS


* Se corrigieron las rutas relativas de la hoja de estilos en los tres archivos HTML para asegurar la carga correcta de css/estilos.css.
* Se implementó la clase table-responsive en la página de opciones para evitar que la tabla comparativa provocara un desplazamiento horizontal indeseado en toda la página en pantallas pequeñas.


11. USO DE HERRAMIENTAS EXTERNAS
Se ha empleado asistencia de inteligencia artificial como herramienta de apoyo para organizar la estructura de contenidos, redactar borradores y revisar aspectos técnicos del código. Todo el código ha sido verificado, adaptado y comprendido íntegramente por el alumno para cumplir con los objetivos académicos de la materia.


12. GITHUB Y ENTREGA
El proyecto se encuentra alojado en un repositorio de GitHub bajo el nombre tic2-practica02, contando con un historial de al menos cinco commits reales que reflejan las distintas fases de desarrollo.


La entrega consta de:


1. El enlace al repositorio de GitHub.
2. Un archivo comprimido .zip con la misma versión del proyecto.
3. La carpeta evidencias/ con las capturas de pantalla correspondientes a las pruebas en distintos anchos de pantalla y en dispositivos móviles.

Estudios Post-Bachillerato

1. OBJETIVO DEL PROYECTO
El objetivo de esta web es comparar tres grados universitarios relacionados con el ámbito de la salud: Medicina, Enfermería y Odontología.

La página permite conocer la duración de cada carrera, las asignaturas principales, los requisitos de acceso, las notas de corte de referencia y las posibles salidas profesionales. La información está centrada en universidades públicas de Galicia, principalmente la Universidade de Santiago de Compostela (USC) y la Universidade da Coruña (UDC).

2. OPCIONES ELEGIDAS
- Medicina: Grado en Medicina de la USC, en Santiago de Compostela.
- Enfermería: Grado en Enfermería de la UDC, en Ferrol.
- Odontología: Grado en Odontología de la USC, en Santiago de Compostela.

3. ESTRUCTURA DE LOS ARCHIVOS
El proyecto está organizado de la siguiente manera:
- index2.html: Portada de la web, presentación, tarjetas de los tres grados y acordeón con competencias, ventajas y desventajas.
- opciones.html: Acceso a la universidad, notas de corte, tabla comparativa adaptativa y fichas breves de las carreras.
- salidas.html: Salidas profesionales detalladas, recorridos de acceso en tres pasos y conclusión comparativa.
- css/estilos.css: Hoja de estilos propia para definir la identidad visual sanitaria, los espacios, los tamaños, el modelo de caja, el foco de accesibilidad y las media queries.
- img/: Carpeta con las imágenes y símbolos gráficos utilizados en las páginas.
- evidencias/: Carpeta para guardar las capturas de pantalla de las pruebas de la web en diferentes anchos de pantalla.

4. CÓMO ABRIR LA WEB
Para abrir el proyecto, hay que descargar o clonar el repositorio y abrir la carpeta tic2-practica01 en el ordenador.

Después, se puede abrir el archivo index2.html con un navegador web moderno (como Google Chrome o Microsoft Edge). Las otras páginas se pueden consultar de forma fluida mediante el menú superior de navegación. Se necesita conexión a Internet para cargar Bootstrap desde su CDN oficial.

5. VERSIÓN DE BOOTSTRAP Y USO DE LA BIBLIOTECA
Se utiliza Bootstrap 5.3.8, cargado mediante CDN oficial. En las páginas HTML se incluye el enlace a la hoja de estilos CSS y el archivo JavaScript correspondiente (bootstrap.bundle.min.js) para garantizar el correcto funcionamiento del menú desplegable en dispositivos móviles.

¿Qué aporta Bootstrap y qué se ha hecho de forma propia?
- Lo que aporta Bootstrap: Proporciona la retícula adaptativa (container, row, col), los componentes visuales ya estructurados (como las tarjetas card, los botones btn y el menú desplegable navbar), y clases de utilidad para que elementos complejos como la tabla comparativa se adapten mediante table-responsive.
- Lo que se ha hecho de forma propia (Alumno): El diseño visual personalizado e identidad cromática de la web (paleta de tonos clínicos y sanitarios limpios), el control detallado del modelo de caja (margin, padding, border), la adaptación responsiva mediante reglas media queries, la mejora de la accesibilidad con contornos de foco visibles para teclado (:focus-visible), así como la redacción, selección y estructuración de todos los contenidos académicos y fuentes oficiales.

6. FUENTES OFICIALES (CON FECHA DE CONSULTA)
Las fuentes utilizadas para investigar la información son las páginas oficiales de las universidades y organismos correspondientes. Fecha de consulta: 26 de octubre de 2026.

Medicina
1. USC - Grado en Medicina:
https://www.usc.gal/es/estudios/grados/ciencias-salud/grado-medicina
2. USC - Indicadores del Grado en Medicina:
https://assets.usc.gal/es/centro/facultad-medicina-odontologia/calidad/indicadores/grado-medicina

Enfermería
3. UDC - Plan de estudios de Enfermería:
https://www.udc.gal/fep/planestudos/enfermaria/
4. UDC - Materias del Grado en Enfermería:
https://www.udc.gal/es/biblioteca.oza/BR/br_enfermeria/

Odontología
5. USC - Grado en Odontología:
https://www.usc.gal/es/estudios/grados/ciencias-salud/grado-odontologia
6. USC - Documentación complementaria de Odontología:
https://assets.usc.gal/sites/default/files/paragraphs/links/2025-04/grao-en-odontologia-requisitos-mobilidade-in.pdf

Información adicional
- Comisión Interuniversitaria de Galicia (CIUG) para admisión y notas de corte:
https://www.ciug.gal/admision-sug
(Nota: Las cifras de notas de corte se presentan como referencias históricas del curso de referencia y deben comprobarse en las publicaciones oficiales de cada convocatoria).

7. CRÉDITOS Y LICENCIAS (ATRIBUCIÓN DE IMÁGENES Y CONTENIDOS)
Los textos han sido redactados y estructurados de forma propia a partir de la información académica disponible en los portales oficiales de la USC, UDC y CIUG para uso exclusivamente educativo.

Atribución detallada de las imágenes de la carpeta img/:

- Imagen 1: Signo medicina.webp
  * Título: Vara de Esculapio / Símbolo de Medicina
  * Autor: Vector de dominio público
  * Fuente: Wikimedia Commons (https://commons.wikimedia.org)
  * Licencia: Dominio público / CC0
  * Cambios realizados: Recorte proporcional y optimización de formato a WebP.

- Imagen 2: Lámpara de Florence Nightingale.jpg
  * Título: Lámpara de Florence Nightingale / Símbolo de Enfermería
  * Autor: Archivo histórico de salud
  * Fuente: Wikimedia Commons (https://commons.wikimedia.org)
  * Licencia: Dominio público / CC0
  * Cambios realizados: Ajuste de brillo y recorte a proporción 1:1 mediante CSS.

- Imagen 3: simbolo odontologia.jpg
  * Título: Símbolo de Odontología
  * Autor: Ilustración técnica de Ciencias de la Salud
  * Fuente: Repositorio gráfico libre
  * Licencia: Dominio público / CC0
  * Cambios realizados: Redimensión de resolución para optimizar la carga.

- Imagen 4: Facultad de medicina.jpg
  * Título: Facultad de Medicina de Santiago de Compostela
  * Autor: Servicio de comunicación de la USC
  * Fuente: Portal web oficial de la USC (https://www.usc.gal)
  * Licencia: Uso institucional educativo sin fines comerciales
  * Cambios realizados: Redimensión horizontal a 180 px de altura para tarjetas.

- Imagen 5: Facultad de enfermeria.jpg
  * Título: Facultad de Enfermería del Campus de Esteiro (Ferrol)
  * Autor: Servicio de comunicación de la UDC
  * Fuente: Portal web oficial de la UDC (https://www.udc.gal)
  * Licencia: Uso institucional educativo sin fines comerciales
  * Cambios realizados: Recorte responsivo adaptado al contenedor de la nota de corte.

- Imagen 6: Facultad de odontología.webp
  * Título: Facultad de Odontología de la USC
  * Autor: Servicio de comunicación de la USC
  * Fuente: Portal web oficial de la USC (https://www.usc.gal)
  * Licencia: Uso institucional educativo sin fines comerciales
  * Cambios realizados: Adaptación de formato de imagen y compresión.

8. DECISIONES TÉCNICAS
- HTML: Uso riguroso de etiquetas semánticas (header, nav, main, section, footer), encabezados ordenados jerárquicamente, párrafos, listas y tablas estructuradas con caption, thead, tbody y celdas con scope.
- CSS: Hoja de estilos externa propia (css/estilos.css) estructurada mediante selectores de etiqueta, clase y descendientes, demostrando el manejo del modelo de caja, colores adaptados al sector sanitario y accesibilidad por teclado.
- Bootstrap: Implementación uniforme de la versión 5.3.8 en las tres pantallas para garantizar consistencia y usabilidad en dispositivos móviles y de escritorio.

9. PRUEBAS DE LA WEB Y DOCUMENTACIÓN DE PÁGINAS

Pruebas en la portada (index2.html):
- Verificación a 390 px (móvil): El menú se colapsa en botón hamburguesa y las tarjetas de carreras se ordenan en 1 sola columna sin desbordamiento horizontal.
- Verificación a 768 px (tableta): Las tarjetas se organizan limpiamente en 2 columnas.
- Verificación a 1280 px (escritorio): El menú se despliega completo y las tarjetas ocupan 3 columnas paralelas.
- Acordeón de competencias: Se comprobó que los tres desplegables de ventajas y desventajas se abren y cierran sin errores mediante JavaScript de Bootstrap.

Pruebas en la página de opciones (opciones.html):
- Tabla comparativa en móvil (390 px): La clase table-responsive permite desplazar lateralmente la tabla de forma fluida sin romper el ancho del cuerpo de la página.
- Enlaces de notas de corte: Todos los enlaces externos dirigen correctamente a los portales oficiales de la USC, UDC y CIUG.

Pruebas en la página de salidas (salidas.html):
- Disposición de tarjetas horizontales: Los bloques de salidas y recorridos en tres pasos mantienen la legibilidad tanto en escritorio como en dispositivos móviles.
- Menú de navegación común: Se comprobó que la clase .active señala correctamente la página actual en las tres pantallas.

10. ERRORES CORREGIDOS
- Se corrigieron las rutas relativas de la hoja de estilos en los tres archivos HTML para asegurar la carga correcta de css/estilos.css.
- Se implementó la clase table-responsive en la página de opciones para evitar que la tabla comparativa provocara un desplazamiento horizontal indeseado en toda la página en pantallas pequeñas.
- Se unificaron los enlaces del menú de navegación en opciones.html y salidas.html para que apunten a index2.html.

11. USO DE HERRAMIENTAS EXTERNAS Y DECLARACIÓN DE IA
Se ha empleado asistencia de inteligencia artificial (ChatGPT / Gemini) como herramienta de apoyo para organizar la estructura de contenidos, redactar borradores de código y revisar aspectos técnicos. Todo el código resultante ha sido verificado, adaptado, comprendido e integrado íntegramente por los alumnos para cumplir con los objetivos académicos de la materia de TIC II en 2.º de Bachillerato.

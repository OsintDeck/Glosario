## **Listado de términos clave para glosario**

### **Conceptos OSINT y Ciberseguridad**

| Término | Definición |
| :--- | :--- |
| **OSINT (Open Source Intelligence)** | Inteligencia de Fuentes Abiertas. Se refiere al conjunto de técnicas y herramientas para recopilar, analizar y correlacionar información pública disponible en Internet con fines de investigación e inteligencia. |
| **Inteligencia de Fuentes Abiertas** | Traducción al español de OSINT. Es la disciplina que utiliza datos de acceso público (redes sociales, foros, registros públicos) para generar conocimiento útil. |
| **Investigación digital** | Proceso metódico de búsqueda y análisis de evidencia o información en entornos digitales (computadoras, redes, internet) para esclarecer hechos o identificar amenazas. |
| **Recolección de información** | Primera fase del ciclo de inteligencia donde se buscan y obtienen datos brutos desde diversas fuentes antes de ser procesados. |
| **Análisis de información** | Proceso de examinar, interpretar y estructurar los datos recolectados para convertirlos en información útil y comprensible para la toma de decisiones. |
| **Correlación de datos** | Técnica que consiste en conectar diferentes fragmentos de información (como un correo, una IP y un nombre de usuario) para encontrar relaciones y patrones que no son evidentes por separado. |
| **Ingeniería social** | Técnica de manipulación psicológica utilizada por ciberdelincuentes para engañar a las personas y obtener información confidencial o acceso a sistemas. |
| **Spearphishing** | Una variante de phishing altamente dirigida y personalizada, donde el atacante investiga a la víctima previamente para hacer el engaño más creíble. |
| **Malware Link** | Enlace malicioso diseñado para descargar software dañino (virus, troyanos) en el dispositivo de la víctima o redirigirla a sitios fraudulentos. |
| **Validación de datos** | Proceso para asegurar que la información recolectada es correcta, auténtica y útil antes de incluirla en un informe o análisis. |
| **Automatización** | Uso de software y scripts para realizar tareas repetitivas de forma rápida y sin intervención humana constante, optimizando el tiempo de investigación. |
| **Detección automática** | Capacidad del sistema (como OSINT Deck) para identificar por sí mismo qué tipo de dato ha ingresado el usuario (ej. saber si es un email o una IP) sin necesidad de selección manual. |
| **Técnicas OSINT** | Métodos específicos utilizados para buscar información, como el uso de operadores de búsqueda avanzada (Dorks), análisis de metadatos o búsqueda inversa de imágenes. |
| **Herramientas OSINT** | Software o aplicaciones web diseñadas para facilitar la recolección y análisis de información de fuentes abiertas. |
| **Directorios OSINT** | Listados organizados de recursos y herramientas OSINT, que sirven como guía para que los investigadores encuentren la utilidad adecuada para cada caso. |
| **Dispersión de recursos** | Problema común donde las herramientas necesarias para investigar están repartidas en muchos sitios diferentes, dificultando el acceso rápido a ellas. |
| **Pérdida de tiempo operativo** | Tiempo valioso que un investigador pierde buscando herramientas o configurando entornos en lugar de estar analizando información. |
| **Flujo de trabajo** | Secuencia ordenada de pasos que sigue un investigador para realizar su tarea de manera eficiente, desde la recolección hasta el reporte. |
| **Métricas de uso** | Datos estadísticos que muestran cómo se utiliza el sistema, por ejemplo, qué herramientas son las más populares o cuántas búsquedas se realizan por día. |
| **Control de abusos** | Mecanismos de seguridad para evitar que un usuario utilice el sistema de forma excesiva o malintencionada, protegiendo la estabilidad de la plataforma. |
| **Seguridad en el desarrollo** | Práctica de escribir código seguro desde el inicio para prevenir vulnerabilidades y ataques futuros. |
| **Sanitización de entradas** | Proceso de limpieza de los datos ingresados por el usuario para eliminar caracteres peligrosos que podrían ser usados para atacar el sistema. |
| **Validación de entradas** | Verificación de que los datos ingresados cumplen con el formato esperado (ej. que un correo tenga una @) antes de procesarlos. |
| **Análisis estático** | Revisión del código fuente del software sin ejecutarlo, buscando errores de programación o fallos de seguridad. |
| **Integridad de datos** | Garantía de que la información no ha sido alterada o dañada de forma no autorizada durante su almacenamiento o transmisión. |
| **Escalabilidad** | Capacidad del sistema para crecer y manejar más usuarios o datos sin perder rendimiento ni calidad en el servicio. |
| **Estabilidad del sistema** | Capacidad del software para funcionar correctamente de manera continua, sin fallos, cuelgues o interrupciones inesperadas. |
| **Vulnerabilidades** | Fallos o debilidades en un sistema informático que pueden ser explotados por atacantes para comprometer la seguridad. |

### **Tecnologías utilizadas**

| Término | Definición |
| :--- | :--- |
| **WordPress** | Sistema de gestión de contenidos (CMS) muy popular y fácil de usar, sobre el cual está construido el plugin OSINT Deck. |
| **Plugin** | Complemento de software que se instala en un programa principal (como WordPress) para añadirle nuevas funciones específicas. |
| **Shortcode** | Código breve y simple (ej. `[osint_deck]`) que permite insertar funciones complejas en las páginas de WordPress sin necesidad de programar. |
| **PHP** | Lenguaje de programación del lado del servidor, utilizado para crear la lógica y el funcionamiento interno de WordPress y del plugin. |
| **JavaScript** | Lenguaje de programación que se ejecuta en el navegador del usuario, permitiendo crear interactividad y dinamismo en la página web. |
| **AJAX** | Tecnología que permite actualizar partes de una página web sin tener que recargarla por completo, mejorando la velocidad y la experiencia del usuario. |
| **Nonces** | "Números usados una sola vez". Son tokens de seguridad que protegen las acciones en WordPress contra ataques de falsificación de solicitudes (CSRF). |
| **jQuery** | Librería de JavaScript que simplifica la escritura de código, facilitando la manipulación de elementos de la página y las animaciones. |
| **Chart.js** | Librería gráfica para crear diagramas y estadísticas visuales (barras, líneas, tortas) de manera sencilla y atractiva. |
| **Axios** | Librería ligera para realizar peticiones HTTP (conectar con servidores) desde el navegador, usada para cargar datos dinámicamente. |
| **FontAwesome** | Colección de iconos vectoriales y logotipos que se pueden usar fácilmente en sitios web para mejorar la interfaz visual. |
| **Apache** | Servidor web de código abierto, muy robusto y utilizado, encargado de entregar las páginas web a los usuarios. |
| **MySQL** | Sistema de gestión de bases de datos relacional, donde WordPress guarda toda la información (usuarios, configuraciones, contenido). |
| **LAMP** | Acrónimo de la infraestructura web clásica: Linux (sistema operativo), Apache (servidor web), MySQL (base de datos) y PHP (lenguaje). |
| **Ubuntu Server** | Distribución del sistema operativo Linux, optimizada para funcionar en servidores, conocida por su estabilidad y seguridad. |
| **OpenSSH** | Herramienta para conectarse y administrar servidores de forma remota y segura a través de una línea de comandos encriptada. |
| **Visual Studio Code** | Editor de código fuente moderno y potente, utilizado por los desarrolladores para escribir y depurar el software. |
| **Git** | Sistema de control de versiones que permite registrar los cambios en el código y colaborar con otros desarrolladores sin perder el trabajo previo. |
| **WinSCP** | Programa para Windows que permite transferir archivos de forma segura entre la computadora local y el servidor. |
| **Composer** | Gestor de dependencias para PHP (mencionado en el proyecto como una alternativa que se evaluó pero se descartó). |
| **CDN (Content Delivery Network)** | Red de servidores distribuidos globalmente que entregan contenido (imágenes, scripts) al usuario desde la ubicación más cercana para acelerar la carga. |

### **Infraestructura OSINT Deck**

| Término | Definición |
| :--- | :--- |
| **Decks** | "Mazos" o grupos de herramientas organizadas. Es la metáfora central del proyecto para agrupar utilidades según su propósito. |
| **Cards** | "Cartas". Representación visual individual de cada herramienta dentro del mazo, mostrando su nombre, descripción y botón de acceso. |
| **Catálogo de herramientas** | Base de datos completa de todas las herramientas OSINT disponibles en el sistema. |
| **JSON** | Formato ligero de intercambio de datos, fácil de leer para humanos y máquinas, usado para importar y exportar las configuraciones de las herramientas. |
| **Panel de administración** | Área privada del sistema donde los administradores pueden configurar el plugin, gestionar herramientas y ver estadísticas. |
| **Interfaz de usuario (UI)** | Todo aquello con lo que el usuario interactúa visualmente en la pantalla (botones, menús, colores, diseño). |
| **Frontend** | La parte del sitio web que ven los visitantes. Es la "cara" del sistema donde se realizan las búsquedas y se ven los resultados. |
| **Backend** | La parte "trasera" del sistema que no ve el usuario. Es donde ocurre la lógica, el procesamiento de datos y la conexión con la base de datos. |
| **Arquitectura modular** | Diseño de software dividido en partes independientes (módulos) que pueden funcionar, actualizarse o reemplazarse sin afectar al resto del sistema. |
| **Sistema de hooks** | Mecanismo de WordPress que permite "enganchar" código personalizado en puntos específicos de la ejecución para modificar su comportamiento sin tocar el núcleo. |
| **Actions** | Tipo de hook que permite ejecutar una acción o función en un momento determinado (ej. "enviar un correo cuando se registra un usuario"). |
| **Filters** | Tipo de hook que permite modificar datos antes de que sean mostrados o guardados (ej. "cambiar el texto de un título"). |
| **Logs** | Registros detallados de la actividad del sistema. Sirven para auditoría, depuración y entender qué ha ocurrido en caso de error. |
| **Registro de eventos** | Grabación sistemática de acciones importantes (quién hizo qué y cuándo) para seguridad y control. |
| **Módulos** | Componentes funcionales del sistema que agrupan características relacionadas. |
| **Componentes** | Partes más pequeñas y reutilizables de la interfaz o del código (ej. un botón, un formulario). |
| **Detección de tipo de dato** | Funcionalidad inteligente que analiza el texto ingresado para determinar si es un correo, una IP, un dominio, etc. |
| **IP (Internet Protocol)** | Dirección numérica única que identifica a un dispositivo en una red o en Internet (ej. 192.168.1.1). |
| **Dominio** | Nombre legible que identifica a un sitio web (ej. google.com), facilitando el acceso sin recordar la IP numérica. |
| **Subdominio** | Parte que precede al dominio principal y organiza secciones de un sitio (ej. **blog**.sitio.com). |
| **Correos electrónicos** | Sistema de mensajería digital y también el dato que identifica a una casilla de correo (ej. usuario@dominio.com). |
| **Hashes (MD5, SHA1, SHA256)** | Cadenas de caracteres generadas matemáticamente que sirven como "huella digital" única de un archivo o texto. Se usan para verificar integridad. |
| **ASN (Autonomous System Number)** | Número que identifica a una gran red administrada por una sola organización (como un proveedor de internet o una gran empresa) en el enrutamiento global. |
| **URL (Uniform Resource Locator)** | Dirección completa de un recurso específico en internet (ej. https://www.sitio.com/pagina.html). |
| **Coordenadas geográficas** | Datos numéricos (latitud y longitud) que permiten ubicar un punto exacto en el mapa terrestre. |

### **Metodología y enfoque académico**

| Término | Definición |
| :--- | :--- |
| **Metodología ágil** | Enfoque de gestión de proyectos que prioriza la flexibilidad, la entrega rápida de avances y la adaptación a los cambios. |
| **Iteraciones** | Ciclos cortos de trabajo donde se desarrolla, prueba y mejora una parte del proyecto antes de pasar a la siguiente. |
| **Diseño funcional** | Definición de *qué* debe hacer el sistema para satisfacer las necesidades del usuario, sin entrar en detalles técnicos de programación. |
| **Diseño técnico** | Definición de *cómo* se construirá el sistema, detallando tecnologías, estructuras de datos y algoritmos. |
| **Revisión continua** | Proceso constante de evaluación y mejora del trabajo realizado para asegurar la calidad. |
| **Investigación aplicada** | Tipo de investigación que busca resolver problemas prácticos y concretos utilizando conocimientos teóricos. |
| **Análisis comparativo** | Estudio que contrasta diferentes soluciones o herramientas para identificar sus ventajas, desventajas y similitudes. |
| **Validación de hipótesis** | Proceso de comprobar si las suposiciones iniciales del proyecto son correctas mediante pruebas y evidencia. |
| **Pruebas funcionales** | Verificación de que el software hace lo que se supone que debe hacer (ej. que el botón de "Buscar" realmente busque). |
| **Pruebas de regresión** | Pruebas para asegurar que los cambios nuevos no han roto funcionalidades que ya existían y funcionaban bien. |
| **Pruebas de carga** | Evaluar cómo se comporta el sistema cuando recibe una cantidad normal o esperada de usuarios simultáneos. |
| **Pruebas de estrés** | Someter al sistema a una carga extrema, superior a la normal, para ver hasta dónde resiste antes de fallar. |
| **Selenium WebDriver** | Herramienta para automatizar navegadores web, usada para realizar pruebas automáticas de la interfaz de usuario. |
| **JMeter** | Herramienta diseñada para realizar pruebas de carga y medir el rendimiento del software. |
| **Análisis cualitativo** | Análisis enfocado en la calidad, opiniones y características no numéricas de los datos. |
| **Análisis cuantitativo** | Análisis basado en números, estadísticas y datos medibles. |
| **Encuesta autoadministrada** | Cuestionario que el encuestado responde por sí mismo, sin la intervención de un entrevistador. |
| **Muestra no probabilística** | Selección de participantes para un estudio basada en criterios no aleatorios (ej. conveniencia o disponibilidad). |
| **Segmentación** | División de un grupo grande (como los usuarios) en subgrupos más pequeños con características similares para analizarlos mejor. |
| **Interpretación de resultados** | Fase final donde se da sentido a los datos obtenidos en la investigación para extraer conclusiones. |

### **Partes del TFI / Documentación**

| Término | Definición |
| :--- | :--- |
| **Resumen del proyecto** | Breve descripción que sintetiza qué es el proyecto, qué problema resuelve y cuáles son sus resultados principales. |
| **Justificación** | Explicación de *por qué* es necesario e importante realizar este proyecto. |
| **Planteamiento del problema** | Descripción detallada de la situación negativa o necesidad que el proyecto busca resolver. |
| **Objetivo general** | La meta principal y global que se quiere alcanzar con el proyecto. |
| **Objetivos específicos** | Metas parciales y concretas que, sumadas, permiten alcanzar el objetivo general. |
| **Hipótesis** | Suposición inicial que el proyecto intentará demostrar como verdadera o falsa. |
| **Marco teórico** | Fundamentación teórica y conceptual que respalda la investigación, citando autores y estudios previos. |
| **Metodología** | Explicación detallada de los métodos, técnicas y procedimientos usados para desarrollar el proyecto. |
| **Cronograma** | Planificación temporal que muestra cuándo se realizarán las diferentes actividades del proyecto. |
| **Anexos** | Material complementario (gráficos, tablas, códigos extra) que se adjunta al final del documento principal. |
| **Referencias** | Listado de fuentes bibliográficas (libros, artículos, webs) citadas en el trabajo. |
| **Documentación técnica** | Manuales y guías dirigidos a desarrolladores o administradores que explican cómo funciona el sistema internamente. |
| **README** | Archivo de texto ("Léeme") que suele ser la portada de un proyecto de software, explicando qué es, cómo se instala y cómo se usa. |
| **Despliegue** | Proceso de poner el software en funcionamiento en un entorno real (servidor) para que los usuarios puedan utilizarlo. |

### **Perfiles de usuario**

| Término | Definición |
| :--- | :--- |
| **Investigadores** | Profesionales dedicados a la búsqueda y análisis de información para resolver casos o generar conocimiento. |
| **Periodistas** | Profesionales de la comunicación que usan OSINT para verificar datos, investigar hechos y encontrar fuentes. |
| **Analistas** | Expertos encargados de procesar datos brutos y convertirlos en inteligencia accionable. |
| **Profesionales de ciberseguridad** | Técnicos encargados de proteger sistemas y redes, que usan OSINT para identificar amenazas externas. |
| **Fuerzas de seguridad** | Miembros de la policía o agencias gubernamentales que utilizan estas técnicas para investigaciones criminales. |
| **Estudiantes** | Personas en formación académica que utilizan la herramienta para aprender sobre OSINT y ciberseguridad. |
| **Comunidad OSINT** | Grupo global de entusiastas, profesionales y expertos que comparten conocimientos y herramientas sobre inteligencia de fuentes abiertas. |

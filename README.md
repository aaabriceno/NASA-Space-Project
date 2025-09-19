# NASA-Space-Project-
Proyecto NASA SPACE Embiggen Your Eyes!
📜 Antecedentes
Las misiones de la NASA capturan imágenes del universo con una resolución cada vez mayor. Una foto de 10 megapíxeles de un teléfono no es nada en comparación con las imágenes de 10 gigapíxeles del espacio o los conjuntos de datos visuales de 10 terapíxeles disponibles. Explorar esta cantidad de información es un desafío, ya que las herramientas actuales no nos permiten asimilarla toda de una vez.

Por ejemplo:

La imagen más grande del Hubble es una foto de 2.5 gigapíxeles de la galaxia de Andrómeda.

El Mars Color Imager (MRO) proporciona un mapa global de Marte a nivel de gigapíxeles cada día.

Sitios como EarthData y Solar System Treks ofrecen vistas increíbles, pero se necesitan nuevas ideas para hacer que la exploración de estos datos, especialmente los que cambian con el tiempo, sea más rápida, fluida e intuitiva.

Imagina poder hacer zoom en una tormenta de polvo en Marte o comparar imágenes detalladas de una galaxia tomadas con años de diferencia. Las herramientas actuales son poco amigables o solo muestran fragmentos. Este proyecto busca dar vida a estos enormes conjuntos de datos.

🎯 Objetivos
El objetivo de esta plataforma es desarrollar y demostrar un método para explorar cantidades masivas de datos visuales de la NASA. La solución debe ser:

Intuitiva: Permitir a los usuarios navegar (zoom y paneo) por imágenes gigantescas de forma fluida.

Interactiva: Facilitar el etiquetado de características conocidas y el descubrimiento de nuevos patrones.

Comparativa: Ofrecer herramientas para comparar lugares dentro de una misma imagen o el mismo lugar en diferentes imágenes (tomadas en distintos momentos o con diferentes instrumentos).

Versátil: Ser útil tanto para el público general en un museo de ciencias como para investigadores que realizan estudios detallados.

✨ Características Principales
Búsqueda Avanzada: Permitir la búsqueda dentro de una imagen mediante:

Coordenadas.

Nombres de características (ej. "Cráter Gale").

Búsqueda por descripción de texto impulsada por IA (ej. "buscar formaciones rocosas de color rojizo y estratificadas").

Superposición de Capas: Dar a los usuarios la opción de superponer conjuntos de datos relacionados y explorarlos simultáneamente (ej. mapa visible + mapa de altímetro láser).

Exploración Temporal: Proveer capacidades interactivas para explorar imágenes de vídeo o secuencias de imágenes tanto en el espacio como en el tiempo.

Etiquetado Colaborativo: Permitir a los usuarios añadir etiquetas y notas a las imágenes, creando una capa de conocimiento generado por la comunidad.

🛠️ Enfoque Técnico
Almacenamiento y Entrega de Datos: La plataforma se ejecutará en línea con un sistema de servicio adaptativo de imágenes. En lugar de descargar terabytes de datos de una sola vez, la aplicación cargará únicamente las "teselas" (pequeños trozos) de la imagen que sean visibles para el usuario en su nivel de zoom actual. Esto garantiza una experiencia rápida y fluida sin importar el tamaño de la imagen original.

Ensamblaje de Datos: Aunque muchos conjuntos de datos vienen en fragmentos, el enfoque de este proyecto no es resolver el problema del ensamblaje, sino visualizar los datos ya ensamblados de manera eficiente. La plataforma estará diseñada para consumir mosaicos pre-procesados.

Gestión de Datos Diversos: La plataforma manejará diferentes productos de datos mediante un sistema de capas. El usuario podrá activar, desactivar y ajustar la opacidad de diferentes vistas:

Imágenes en diferentes espectros de luz (visible, infrarrojo, UV).

Conjuntos de datos de diferentes misiones (Hubble, MRO, LRO).

Datos no visuales representados como capas de color (altimetría, temperatura).

🖼️ Ejemplo de Uso: Comparando el Deshielo Polar en Marte
Selección de Datos: Un investigador abre el "Explorador Cósmico" y busca "Polo Norte de Marte". La plataforma carga un mosaico de imágenes de 5 gigapíxeles del Mars Reconnaissance Orbiter (MRO).

Exploración Temporal: El investigador utiliza un control deslizante de tiempo para ver imágenes de la misma región tomadas en diferentes años.

Descubrimiento: Al comparar una imagen de 2018 con una de 2024, nota un retroceso significativo en una sección de la capa de hielo.

Anotación y Medición: Utiliza la herramienta de polígono para delinear el borde del hielo en ambas imágenes. La plataforma calcula automáticamente el área perdida en kilómetros cuadrados.

Etiquetado: Añade una etiqueta pública: "Evidencia de deshielo acelerado en el casquete polar norte", adjuntando sus mediciones y una breve nota. Otros usuarios e investigadores ahora pueden ver y comentar sobre este descubrimiento.

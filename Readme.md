Grupo de trabajo de automatización CVE Git Pilot
El Grupo de trabajo de automatización de CVE está probando el uso de git para compartir información sobre vulnerabilidades públicas. El objetivo es aprender no solo qué funciones son necesarias para respaldar la "plomería" del envío y la recepción de datos, sino también qué atributos y metadatos se necesitan en el formato CVE para respaldar la automatización.

Consulte Cómo contribuir para obtener detalles sobre cómo participar en este piloto.

Este repositorio contiene información incluida en la lista CVE formateada con el formato CVE JSON .

El uso de la información de CVE en este repositorio está sujeto a los Términos de uso de CVE .

Descripción general del repositorio
La información sobre cada ID de CVE se almacena como un archivo único en el repositorio en un subdirectorio basado en el año, así como en la parte numérica de la ID, truncada por 1,000. Por lo tanto, 2017 / 3xxx es para CVE-2017-3000 - CVE-2017-3999, y 2017 / 1002xxx es para CVE-2017-1002000 - CVE-2017-1002999.

El equipo CVE actualiza estos archivos automáticamente cada hora utilizando información de la lista CVE, siempre que haya habido cambios. El trabajo de sincronización comienza en la parte superior de la hora y debería completarse en 5 minutos.

Para los identificadores que se han completado, los archivos contienen la descripción y las referencias que aparecen en la lista CVE . También pueden contener información sobre los productos afectados y los tipos de problemas, que las CNA han estado proporcionando al realizar asignaciones durante el año pasado, pero que no está incluida en la Lista CVE. Y en el futuro, se espera que contengan una colección más rica de información sobre la vulnerabilidad, respaldada por el esquema CVE JSON completo.

Contacto
Dirija sus preguntas, comentarios o inquietudes sobre el uso de este repositorio al equipo de CVE mediante el formulario web de solicitud de CVE .

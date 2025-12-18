DESCRIPCIÓN GENERAL DEL PROYECTO
Este proyecto consiste en el diseño y validación de un sistema de información basado en XML
para representar el catálogo de contenidos de una plataforma de streaming.
El sistema incluye series y películas con sus datos básicos,
asegurando una estructura clara, ordenada y coherente.

ESTRUCTURA DEL XML (ENTRE LOS DOS)
El archivo datos.xml tiene como elemento raíz <plataformaStreaming>.
Dentro de este elemento se incluyen varios contenidos de tipo <serie> y <pelicula>.
Cada contenido posee un atributo identificador obligatorio y subelementos
que describen sus características principales.

PARTE REALIZADA POR CARLOS – DTD
Carlos se encargó del diseño y desarrollo del archivo estructura.dtd.
En esta parte se definió la estructura lógica del documento XML,
estableciendo el orden obligatorio de los elementos,
el uso de repeticiones mediante el operador “+”
y la obligatoriedad de ciertos atributos para garantizar la validez del XML.

PARTE REALIZADA POR DANI – XSD
Dani fue responsable del diseño y desarrollo del archivo esquema.xsd.
En esta parte se definieron los tipos de datos,
las secuencias de elementos,
las restricciones de repetición mediante maxOccurs
y los atributos obligatorios, asegurando una validación más estricta del documento XML.

QUÉ VALIDA EL DTD
El DTD valida la estructura general del documento XML,
el orden de los elementos,
la repetición de series y películas
y la existencia de atributos obligatorios.

QUÉ VALIDA EL XSD
El XSD valida la estructura completa del XML,
los tipos de datos utilizados (xs:string y xs:integer),
los atributos obligatorios
y la coherencia entre todos los elementos definidos.

DIFICULTADES ENCONTRADAS
La principal dificultad fue coordinar el trabajo en grupo
para mantener la coherencia total entre el XML, el DTD y el XSD,
asegurando que los cambios realizados por cada integrante
se reflejaran correctamente en todo el proyecto.

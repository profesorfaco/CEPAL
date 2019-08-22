# CEPAL | visualización de datos

| Felipe Cortez            |  Ricardo Vega           |
|:-------------------------|:------------------------|
| profesor@faco.cl         | rivegam@uc.cl           |
| http://profesor.faco.cl/ | http://www.ricardov.cl/ | 

**Jueves 22 de agosto, 2019**

De modo práctico, vamos a revisar:

- herramientas en línea para prototipar visualizaciones de datos (9.40 a 10.20 hrs.);

- referencias en línea para definir el tipo de visualización de datos pertinente según su función comunicacional (10.20 a 10.50 hrs.); y

- bibliotecas de JavaScript para la visualización de datos, con énfasis en D3.js (11.00 a 12.50 hrs.)

- - - - - - - - -

## Herramientas en línea para prototipar visualizaciones de datos

### DATAMATIC
https://datamatic.io/

Un servicio que permite elegir una plantilla de visualización de datos, para luego personalizarla y, posteriormente, publicarla. Se necesita una cuenta “GMAIL” para poder utilizarla. Se propone seleccionar una plantilla y modificarla con datos reales, sobre algún asunto de interés.

### RAWGraphs
https://rawgraphs.io/learning/ 

Un servicio que facilita la representación visual de datos complejos, ofreciendo un espacio para ingresar datos, distintas opciones de gráficos y un espacio de configuración dependiente de la opción seleccionada. Se propone realizar un “Alluvial diagram” con datos sobre las Visas otorgadas período 2018, [datos publicados por el Departamento de Extranjería y Migración](https://www.extranjeria.gob.cl/estadisticas-migratorias/).

### WORD CLOUD GENERATOR 
https://www.jasondavies.com/wordcloud/ 

Un servicio que permite generar una nube de palabras desde un texto. Se propone tomar [la segunda Cuenta Pública de Piñera (2019)](https://prensa.presidencia.cl/discurso.aspx?id=96642), copiarlo y pegarlo en el espacio para texto de https://www.jasondavies.com/wordcloud/  y visualizar las 250 palabras más utilizadas.

- - - - - - - - -

## Referencias en línea para definir el tipo de visualización de datos pertinente según su función comunicacional

### FROM DATA TO VIZ
https://www.data-to-viz.com/

Este proyecto presenta, en forma de un árbol de decisión, un conjunto de visualizaciones que resultan más apropiadas al formato de datos de entrada.

Este proyecto es desarrollado por dos franceses. El analista de datos Yan Holtz y el diseñador Conor Healy.

### CATÁLOGO DE DATAVIZ
https://datavizcatalogue.com/ES/

Este es un proyecto doble, con una biblioteca de diferentes técnicas de visualización y un blog, ambos desarrollados por Severino Ribecca; su biblioteca puede explorarse de dos maneras:

- a través de [búsqueda por función](https://datavizcatalogue.com/ES/buscar.html): ¿Qué se desea mostrar?

- a través de [listas, que agrupan](https://datavizcatalogue.com/ES/ver_por_lista.html): Gráficos/Tramas, Diagramas, Tablas, Varios, Mapas/Geográficos

### VISUAL LITERACY
http://www.visual-literacy.org/

En la sección Books & Maps, es posible encontrar:

- una [tabla periódica](http://www.visual-literacy.org/periodic_table/periodic_table.html) de los métodos de visualización de datos; y

- una [escalera hacia la excelencia visual](http://www.visual-literacy.org/stairs_of_viz/stairs_of_viz.html) 

Consultando [esta tabla periódica](http://www.visual-literacy.org/periodic_table/periodic_table.html) podrán aprender, por ejemplo, que un “Iceberg” es una metáfora visual (Metaphor Visualization) que puede ofrecer una vista general (Overview) de una estructura (Structure Visualization), mientras que un “Diagrama de Flujo” es una visualización de información (Information Visualization) que puede ofrecer, a la vez, vista general y detallada (Detail AND Overview) de un proceso (Process Visualization). 

> En grupos, imaginen el (auto)encargo de una visualización de datos. Pónganle un título a este (auto)encargo. Luego seleccionen el tipo o método de visualización más adecuado para el caso imaginado, y justifiquen la selección con la información ofrecida en la tabla periódica y en el catálogo de visualización de datos. Para presentarlo, hagan un boceto rápido (muy rápido). Contando con una decisión informada y un boceto (como un acuerdo en papel; lo mismo a la vista de todos), podemos dar un primer paso en la escalera hacia la excelencia visual, la que nos llevará hasta una visualización de datos que podría llamar la atención, motivar hacia la comprensión y resultar (positivamente) memorable.

- - - - - - - - -

## Bibliotecas de JavaScript para la visualización de datos, con énfasis en D3.js

### JavaScript

JavaScript es un lenguaje de programación que se utiliza principalmente para crear páginas web dinámicas: páginas que se modifican como respuesta a nuestra interacción de ellas.

Estas modificaciones no implican cambios del código fuente con el que se describe la página web. Lo que sí implican son cambios en la representación estructurada conforme al estándar del DOM (Modelo de Objetos del Documento o Modelo en Objetos para la Representación de Documentos).

Podemos cambiar la representación de esta misma página escribiendo lo siguiente en la Consola de JavaScript del Navegador Web* que estén utilizando:

`document.write("bye!");`

**Para asomarse a la consola correspondiente:**

Si usas Chrome en PC, presiona Ctrl + Shift + J. Si estás usando el mismo navegador en Mac, presiona Cmd + Alt + J

Si usas Firefox en PC, presiona Ctrl + Shift + K. Si estás usando el mismo navegador en Mac, presiona: Cmd + Alt + K

Si usas Safari, presiona: Cmd + Alt + C (aunque no es recomendable seguir trabajando con este navegador web, favor descarga uno de los anteriores)

### Mapas

https://leafletjs.com/

Leaflet es la biblioteca de JavaScript que permite programar mapas interactivos.

### Data Driven Documents

https://d3js.org/

D3 es una biblioteca de JavaScript que permite visualizar datos utilizando estándares web.

### Simplificando D3.js

https://d3plus.org/ · https://c3js.org/

D3plus y C3 son bibliotecas de JavaScript que extienden D3.js, permitiendo la creación rápida de gráficos.

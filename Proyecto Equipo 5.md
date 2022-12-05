# **Código que facilita los cálculos de una nivelación topográfica**

*Code to facilitate topographic leveling calculations*

**Tejeda Campos Dayra Nataly (1) Vargas Méndez Ilse Lilith (2)**

(1) Facultad de Ingeniería Civil, Campus Coquimatlán, Colima - Coquimatlán Kilómetro 9, Jardines del Llano, 28400 Coquimatlán, Col. dtejeda1@ucol.mx, (2) ivargas@ucol.mx.

*Tejeda Campos Dayra Nataly; Vargas Méndez Ilse Lilith. Título: Código que facilita los cálculos de una nivelación topográfica. Equipo #5*


**Resumen** 

En el presente trabajo se producirá un código de Python que tendrá como finalidad leer datos obtenidos previamente en campo de una nivelación topográfica, para la facilitación de sus cálculos para así lograr obtener, la altura de instrumento, cotas y principalmente el desnivel.

**Palabras clave:** Código, nivelación, cálculos, desnivel.

**Abstract** 

In the present work a Python code will be produced with the purpose of reading data previously obtained in field of a topographic leveling, for the facilitation of its calculations to obtain the instrument height, elevations and mainly the slope.

**Keywords:** Code, leveling, calculations, slope.


- # **Introducción**
La nivelación topográfica, es un método altimétrico, que tiene como objetivo obtener la cota de uno o varios puntos, a través de observaciones topográficas como ángulos, desniveles, distancias y un conjunto de mediciones y cálculos para asignar a un punto de cota, con relación a un plano de referencia determinado. En este trabajo se elaborará un código que facilite los cálculos de una nivelación para obtener la altura del instrumento, cotas y el desnivel. Para ello, se hará una breve investigación de los cálculos de cada punto a obtener en el código de Python.

#
- # **Desarrollo**
Python es un lenguaje de programación de alto nivel, interpretado y de alto propósito; es uno de los lenguajes más usados para el desarrollo de software.

La elección de Python se debe a que se trata de un lenguaje de programación fácil de aprender y potente. Tiene eficaces estructuras de datos de alto nivel y una solución de programación orientada a objetos eficaz. La elegante sintaxis de Python, su gestión de tipos dinámica y su naturaleza interpretada hacen de él el lenguaje ideal para guiones (scripts) y desarrollo rápido de aplicaciones, en muchas áreas y en la mayoría de las plataformas.

Python ofrece una amplísima colección de módulos (bibliotecas). Hay módulos para cualquier actividad imaginable: escritura de CGI, gestión de correo electrónico, desarrollo de interfaces gráficas de usuario, análisis de documentos HTML o XML, acceso a bases de datos, trabajo con expresiones regulares, etc.

**Materiales**

Los materiales utilizados para la realización de este proyecto son:

- Computadora
- Google Colaboratory
- Excel (datos de nivelación)

**Pasos** 

1. Registramos los datos de una nivelación en un archivo csv.

![Aspose Words 28664117-5689-49a4-8ca2-d6dab88f2dc9 001](https://user-images.githubusercontent.com/119512794/205556993-1f168926-2e3f-4970-9cf5-40d27c1bfb77.png)

Figura #4. Archivo csv de una nivelación. 


2. En Google Colab abrimos un cuaderno nuevo para empezar a instalar las librerías que no teníamos necesitadas para el código.

![Aspose Words 28664117-5689-49a4-8ca2-d6dab88f2dc9 002](https://user-images.githubusercontent.com/119512794/205557247-cbe608d2-0f8c-4c09-957f-909459d55894.png)

Figura #2. Instalación de librerías.

3. Importamos las librerías requeridas.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 003](https://user-images.githubusercontent.com/119512794/205752260-acefaaa7-67e7-4440-be91-a4e068aca042.png)

Figura #3. Importación de librerías.

4. Del archivo csv que contiene los datos de una nivelación leemos los datos y los convertimos en un arreglo.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 004](https://user-images.githubusercontent.com/119512794/205752372-f65ad826-91f7-4688-b611-8c37905ef214.png)

Figura #4. Lectura del archivo csv y arreglo de datos.

5. Obtenemos la cota del puto de liga, la altura de aparato y calculamos el desnivel.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 005](https://user-images.githubusercontent.com/119512794/205752454-13a5979f-0ec7-48a0-9af3-9be6571512ba.png)

Figura #5. Calculo de la cota, altura del aparato y desnivel

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 006](https://user-images.githubusercontent.com/119512794/205752516-3bcbd81e-07e8-4c71-ad23-0e611ecb7965.png)

Figura #6. Resultado del código para la obtención del desnivel, cota y altura de instrumento. 

6. Importamos librerías requeridas para un nuevo proceso. 

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 007](https://user-images.githubusercontent.com/119512794/205752585-ae7cd0e7-4711-4971-8563-fba43b8a5c7c.png)

Figura #7 Importación de librerías.

7. Procesamos coordenadas para poderlas representar en un mapa.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 008](https://user-images.githubusercontent.com/119512794/205752640-2b2bcb99-bc67-4df9-84ca-8525df27319e.png)

Figura #8. Procesamiento de coordenadas para la obtención de un mapa

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 009](https://user-images.githubusercontent.com/119512794/205752708-73c27ac5-5655-4136-979e-d0d3f875e64e.png)

Figura #9. Resultado del mapa con las coordenadas de la nivelación.
- # **Manejo de datos**
Este concepto hace referencia al conjunto de implementos funcionales que te ayudarán a codificar todo este lenguaje de programación para crear una interfaz independiente. 

Las librerías de Python son amplias y cuentan con gran cantidad de producciones en contenidos. Constan de diversos módulos que permiten el acceso de funcionalidades específicas del sistema como entrada y salida de archivos, soluciones estandarizadas a problemas de programación, etc.

Además, dependiendo del sistema operativo que tengas, puedes conseguir diferentes funciones de cada una de las librerías de Python. Por ejemplo, para el sistema Windows se incluye la biblioteca estándar completa junto con componentes adicionales.

Un plus para las librerías de Python es que cuentan con una colección de componentes como, por ejemplo, programas individuales, módulos, paquetes, frameworks, aplicaciones y más funciones que puedes encontrar en [Python Package Index](https://pypi.org/)..

Adentrandonos a las librerías que utilizaremos son las siguientes:

- *Map* 

*C++ map estándar*

Map es un contenedor asociativo para contener en orden una lista de parejas de valores únicos asociados como clave/valor.
En orden de poder crear objetos maps en nuestros programas deberemos incluir el uso de la clase map mediante la expresión:
Otro aspecto que se debe de entender acerca de la estructura map es que esta está organizada para contener elementos asociados en parejas, de ahí, la necesidad de entender el comportamiento de la plantilla pair.

*C++ pair estándar*

pair es una plantilla cuyo propósito es contener una pareja de valores.

los miembros de pair son dos, first es el nombre del primero de ellos y el segundo se llama second. Cada uno de los miembros de pair pueden ser de tipos diferentes. Para poder

usar la plantilla pair en nuestro programa se debe de incluir la directiva: pair es una estructura independiente y puede ser usada con diversos fines, sin embargo, la importancia de pair radica en el hecho de que esta es usada como estructura elemental para construir contenedores tipo MAPS.

Antes de mostrar ejemplos de map mostraremos un par de ejemplos del uso de la estructura pair. Así, el siguiente programa utiliza pair para crear una pareja de valores asociados como (cadena, numero). 

- *Basemap*

La librería Basemap para producir mapas con Python

Con este conjunto de herramientas podremos representar información geográfica vectorial y ráster sobre gráficos 2D. Funciona sobre diversas librerías además de Matplotlib como Proj4, Generic Mapping Tools y GEOS.

- *Matplotlib*

Es una de las principales librerías para visualización y análisis de datos de cualquier tipo, también espaciales.

Matplotlib es una librería de Python especializada en la creación de gráficos en dos dimensiones.

Permite crear y personalizar los tipos de gráficos más comunes, entre ellos:

- Diagramas de barras
- Histograma
- Diagramas de sectores
- Diagramas de caja y bigotes
- Diagramas de violín
- Diagramas de dispersión o puntos
- Diagramas de líneas
- Diagramas de áreas
- Diagramas de contorno
- Mapas de color

y combinaciones de todos ellos.

En la siguiente galería de gráficos pueden apreciarse todos los tipos de gráficos que pueden crearse con esta librería.

*Creación de gráficos con matplotlib*

Para crear un gráfico con matplotlib es habitual seguir los siguientes pasos:

1. Importar el módulo pyplot.
1. Definir la figura que contendrá el gráfico, que es la region (ventana o página) donde se dibujará y los ejes sobre los que se dibujarán los datos. Para ello se utiliza la función subplots().
1. Dibujar los datos sobre los ejes. Para ello se utilizan distintas funciones dependiendo del tipo de gráfico que se quiera.
1. Personalizar el gráfico. Para ello existen multitud de funciones que permiten añadir un título, una leyenda, una rejilla, cambiar colores o personalizar los ejes.
1. Guardar el gráfico. Para ello se utiliza la función savefig().
1. Mostrar el gráfico. Para ello se utiliza la función show().
- *Pandas*

Pandas es una muy popular librería de código abierto dentro de los desarrolladores de Python, y sobre todo dentro del ámbito de Data Science y Machine Learning, ya que ofrece unas estructuras muy poderosas y flexibles que facilitan la manipulación y tratamiento de datos.

![](Aspose.Words.28664117-5689-49a4-8ca2-d6dab88f2dc9.010.png)Pandas surgió como necesidad de aunar en una única librería todo lo necesario para que un analista de datos pudiese tener en una misma herramienta todas las funcionalidades que necesitaba en su día a día, como son: cargar datos, modelar, analizar, manipular y prepararlos.

Las principales características de esta librería son:

- Define nuevas estructuras de datos basadas en los arrays de la librería NumPy pero con nuevas funcionalidades.
- Permite leer y escribir fácilmente ficheros en formato CSV, Excel y bases de datos SQL.
- Permite acceder a los datos mediante índices o nombres para filas y columnas.
- Ofrece métodos para reordenar, dividir y combinar conjuntos de datos.
- Permite trabajar con series temporales.
- Realiza todas estas operaciones de manera muy eficiente.

Tipos de datos de Pandas

Pandas dispone de tres estructuras de datos diferentes:

- Series: Estructura de una dimensión.
- DataFrame: Estructura de dos dimensiones (tablas).
- Panel: Estructura de tres dimensiones (cubos).

import pandas as pd

s = pd.Series(['Matemáticas', 'Historia', 'Economía', 'Programación', 'Inglés'], dtype='string')

print(s)

Matemáticas

Historia

Economía

Programación

Inglés


Estas estructuras se construyen a partir de arrays de la librería NumPy, añadiendo nuevas funcionalidades.

*La clase de objetos Series*

Son estructuras similares a los arrays de una dimensión. Son homogéneas, es decir, sus elementos tienen que ser del mismo tipo, y su tamaño es inmutable, es decir, no se puede cambiar, aunque si su contenido.

Dispone de un índice que asocia un nombre a cada elemento de la serie, a través de la cual se accede al elemento.

Ejemplo. La siguiente serie contiene las asignaturas de un curso.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 011](https://user-images.githubusercontent.com/119512794/205754622-8e94344c-868f-49a2-ba73-698b8c522c7c.png)

Creación de series

*Creación de una serie a partir de una lista*

- Series (data=lista, index=indices, dtype=tipo): Devuelve un objeto de tipo Series con los datos de la lista lista, las filas especificadas en la lista índices y el tipo de datos indicado en tipo. Si no se pasa la lista de índices se utilizan como índices los enteros del 0 al n-1, done n es el tamaño de la serie. Si no se pasa el tipo de dato se infiere.

*Creación de una serie a partir de un diccionario*

- Series (data=diccionario, index=indices): Devuelve un objeto de tipo Series con los valores del diccionario diccionario y las filas especificadas en la lista indices. Si no se pasa la lista de índices se utilizan como índices las claves del diccionario.

import pandas as pd

s = pd.Series({'Matemáticas': 6.0,  'Economía': 4.5, 'Programación': 8.5})

print(s)

Matemáticas     6.0

Economía        4.5

Programación    8.5

Folium es una librería de Python que se usa para visualizar mapas, Folium nace de la unión de otro lenguaje muy utilizado en SIG llamado JavaScript que es usado en entornos web y su librería Leaflet y el lenguaje Python. Mediante Folium podemos manipular dichos mapas de Leaflet con Python.

Respecto a su funcionamiento, Folium crea el vínculo entre Datasets que contienen datos cartográficos de diferentes objetos que son manipulados con Python y Leaflet que permiten generar la visual de la cartografía. También es posible, por ejemplo, ubicar en un mapa las diferentes ubicaciones de un restaurante en una ciudad usando un dataset que contenga sus coordenadas de GPS. Los mapas producidos de esta forma contienen una capa de base y otras capas generadas por Folium que se superponen.

La cantidad y variedad de objetos que se pueden visualizar con Folium es muy grande. Entre ellos podemos mencionar, mapas de diferentes tipos, igual de numerosos que los objetos de tipo vectoriales (círculo, polígono, rectangular, pin, etc), o incluso grillas que permiten crear ciertos bordes, por ejemplo. 

Folium es una de las librerías más asequibles para análisis y representación geoespacial, por la sencillez de la sintaxis.

Una de las características que más atrae es que no necesita convertir el DataFrame en un GeoDataFrame. Solo teniendo una serie con la latitud y otra serie con la longitud del punto espacial, es suficiente para que Folium lo represente en un mapa.

En cualquiera de las representaciones con Folium el primer paso es desarrollar el mapa sobre el que se va a pintar el resto de la información. Para ello, hay que centrarlo en un punto con latitud y longitud.

Folium utiliza por defecto como tipo de mapa base OpenStreetMap, pero hay otras opciones (es el parámetro que corresponde a “tiles”).

Normalmente, se selecciona el primer registro del dataset como referencia del centro del mapa.

Usando folium.Map() , crearemos un mapa base y lo almacenaremos en un objeto. Esta función toma coordenadas de ubicación y valores de zoom como argumentos.

Sintaxis: folium.Map ( ubicación, mosaicos = “OpenStreetMap” zoom\_start = 4 )

Parámetros:

- Ubicación: lista de coordenadas de ubi-cación
- Mosaicos: el valor predeterminado es OpenStreetMap. Otras Opciones: Tamen Terrain, Stamen Toner, Mapbox Bright, etc.
- Zoom\_start: int

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 013](https://user-images.githubusercontent.com/119512794/205755162-db371be3-cdef-4fef-8c95-180eb13fb5ec.png)

Figura #10. Código que utiliza la librería Folium.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 014](https://user-images.githubusercontent.com/119512794/205755196-f933e08a-2261-4b91-b4bd-344d7ed2b959.png)

Figura #11. Resultado del código que utiliza la Liberia Folium. 

- # **Resultados** 

Después de obtener nuestra serie de datos en campo después de una nivelación, nos dimos a la tarea de diseñar un código que nos facilitara los cálculos que hacemos normal-mente para obtener tanto la altura del instrumento, cotas e incluso el desnivel.

Antes de empezar instalamos todas las librerías que vamos a utilizar en cada una de las partes.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 015](https://user-images.githubusercontent.com/119512794/205755278-0e0e8e45-ced9-4700-b439-664f8f34428e.png)

Figura #12. Resultado de instalar las librerías correspondientes. 

Lo primero que vamos a hacer es leer nuestros datos previamente registrados en Excel, nos damos cuenta de que nos hacen falta las dos columnas que son las que vamos a obtener que son la I.H y la cota, más aparte que obtendremos el desnivel.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 016](https://user-images.githubusercontent.com/119512794/205755319-e926c6e4-09df-4868-8bab-3b1b1f46d506.png)

Figura #13. Obtención de la I.H. y Cota 

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 020](https://user-images.githubusercontent.com/119512794/205755377-a269099d-2117-427e-8c2b-912d2b2d7f28.png)

Figura #14. Código para la obtención del desnivel 

Nuestro código principal empieza dándonos una ruta, que es lo primero que tenemos que hacer es crearla para obtener la lectura y extracción de datos de nuestro archivo de Excel. Se hace esta lectura, pero nuestro código se diseño para que pueda leer otro tipo de archivo, tanto como csv o txt siempre y cuando tenga la información ordenada y adecuada. De donde vamos a extraer el archivo estaremos utilizando la librería os donde ya vienen bloques programados para leer este tipo de archivos.

Continuando con el código nuestro primer atributo es el nombre que se insertara como Sting, pero si en dado caso de que se encuentre en otro sitio se debe poner una nueva ruta a ello.

El segundo atributo es acerca de las columnas que se estarán utilizando.

El tercer atributo es para saltar filas, en nuestro caso se omitirá la primera fila que es de encabezados.

Nuestro cuarto atributo es el índice de la hoja a usar que en este caso es 0 para la primera, 

Teniendo en cuenta que ya tenemos nuestra variable datos la vamos a convertir en un arreglo. 

Luego obtenemos el número de lecturas, y prosigue a sacar los cálculos de las columnas restantes. Como se puede observar se obtuvo el desnivel y ya los resultados de nuestras partes faltantes.

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 017](https://user-images.githubusercontent.com/119512794/205755572-4134e58e-4a1b-4dbe-892d-c3dac157ea40.png)

Figura #15. Faltante del código y resultados de las columnas y el desnivel.

Integrando un poco la librería Folium decidimos agregar un mapa que nos muestre con detalle y especificamente donde se realizo la nivelacion, para ello debemos de insertar las cooredenas lo mas precisas posibles de nuestro primer punto. Que es 19.210330,-103.802482

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 018](https://user-images.githubusercontent.com/119512794/205755618-62c62b94-4e59-4854-a555-e6fa75f82af5.png)

Figura #16. Código para la obtención del punto con nuestras coordenadas. 

Teniendo como resultado nuestro punto exacto expresado en el mapa:

![Aspose Words 57d98f14-f4d1-4713-95e2-fdc5281b9e14 019](https://user-images.githubusercontent.com/119512794/205755661-00ca5300-56fe-4156-a912-81044dbb805b.png)

Figura #17. Mapa con el punto con nuestras coordenadas. 

- # **Conclusiones** 

La programación trasciende todos los lenguajes, sobre todo porque también es una excelente herramienta para la resolución de problemas mediante la lógica y el ingenio. Es el arte de desarrollar soluciones a paradigmas complejos desde cero, basándose en el pensamiento estructural, lógico y creativo.

Con la realización de este proyecto podemos concluir que la programación puede ser de mucha utilidad a la hora de querer realizar cálculos para la obtención de información que sea de gran utilidad para nosotros a la hora de realizar algún trabajo topográfico en un futuro siendo Ingenieros Topógrafos Geomáticos.

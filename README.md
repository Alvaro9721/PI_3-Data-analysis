<p align=center><img src=https://assets.soyhenry.com/logos/LOGO-HENRY-04.png><p>

# <h1 align=center> **PROYECTO INDIVIDUAL Nº3** </h1>

# <h1 align=center>**`Data Analyst`**</h1>
*Alvaro Enrique Beleño Contreras*

*Ingeniero Industrial*

*Data Sciencie(In progress)*
<p align="center">
<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/What_is_Data_Analysis.jpg"height=300>

</p>



<hr>  
Este trabajo consiste en realizar un análisis completo del comportamiento del sector de telecomunicaciones de una empresa Argentina que brinda servicios de conectividad a internet, la cual sugiere utilizar una API de *Enacom* que posee datos históricos del mercado, oferta, demanda y cobertura de los servicios de conectividad.

<hr>

## **Descripción del problema**

<p align="center">
<img src="https://mirianblog26w.files.wordpress.com/2018/09/mirian-informatica.jpg?w=640"height=320>

La industria de las telecomunicaciones ha jugado un papel fundamental en el desarrollo del mercado y con ello permitiendo el crecimiento de nuevas empresas, que en su mayoría dependen de estos servicios.

En comparación con la media mundial, Argentina está a la vanguardia del desarrollo de las telecomunicaciones, teniendo para el 2020 un total de 62,12 millones conexiones, debido a esto es necesario hacer un análisis global del comportamiento de esta industria, con el fin de encontrar nuevas tendencias y tomar decisiones acorde a la demanda.


​

<hr> 

## **Pasos para la elaboración del proyecto**
**1. Conexión a la API de Enacom**

Para conectarse a dicha api es fundamental tener claro cómo armar el request y sus requerimientos los cuales son:

* **Llave de acceso :** Esta es la clave del paso 1, la necesitarás para cada request, se encuentra en el siguiente [link_llave](https://datosabiertos.enacom.gob.ar/developers/).

* **Numero Guid :** (**NUMER-GEOGR**) el GUID del dataset que estás accediendo, este GUID lo puedes encontrar en la página del detalle de la vista, haciendo una búsqueda de la vista a través de la API y en muchos otros lugares.


<hr>


## **2. Recolección de datos**

La API brinda 16 dataset que contienen información relacionada a la conectividad en las diferentes provincias de Argentina, como se muestaran a continuación:

* **Penetración de Internet fijo (accesos por cada 100 hogares) :**  Número de accesos al servicio de Internet fijo por cada 100 hogares por provincia.

* **Penetración por hogares nacional de Internet fijo :** Serie trimestral de la penetración del Internet fijo en la métrica por cada 100 hogares.

* **Total nacional de accesos a Internet fijo por banda ancha y banda angosta :** Número total de accesos al servicio de Internet fijo por banda ancha y banda angosta (trimestral).

* **Accesos a banda ancha y banda angosta por provincia :** Número de accesos al servicio de Internet fijo por banda ancha y banda angosta en cada provincia (trimestral).

* **Serie trimestral de accesos a Internet fijo por tecnología :** Número de accesos al servicio de Internet fijo por tipo de tecnología. Total nacional (trimestral).

* **Acceso a Internet fijo por tecnología y provincia :** Número de accesos al servicio de Internet fijo por tipo de tecnología en cada provincia (trimestral).

* **Velocidad Media de bajada de Internet fijo :** Serie histórica de la velocidad media de descarga de Internet nacional (trimestral).

* **Velocidad media de bajada de Internet fijo por provincia :** Serie histórica de la velocidad media de descarga de Internet por provincia (trimestral).

* **Distribución de los accesos totales nacionales a Internet fijo por velocidad :** Distribución de los accesos totales nacionales a Internet fijo por velocidad de bajada (último trimestre disponible).

* **Acceso a Internet Fijo por rangos de velocidad de bajada y provincia :** Número de accesos al servicio de Internet fijo por velocidad de bajada en cada provincia (trimestral).

* **Accesos a Internet fijo por velocidad bajada y provincia :** Número de accesos al servicio de Internet fijo por velocidad de bajada en cada provincia.

* **Ingresos trimestrales por la prestación del servicio de Internet fijo :** Ingresos trimestrales de los operadores por el servicio de Internet fijo.

* **Accesos a Internet fijo por velocidad de bajada y localidad :** Número de accesos al servicio de Internet fijo por velocidad de bajada en cada localidad declarada.

* **Accesos a Internet fijo por tecnología y localidad :** Número de accesos al servicio de Internet fijo por tecnología en cada localidad declarada Categoría.

* **Listado de localidades con conectividad a internet :**
 Listado de localidades con conectividad a internet, con detalle por tipo de conexión.

* **Conectividad al servicio de Internet :** Consulta las tecnologías disponibles en tu localidad para acceder al servicio de Internet fijo y móvil.

<hr>

## **3. EDA**


<p align=center>
<img src = 'Imagenes\EDA.PNG' height=><p>

Para realizar el análisis exploratorio se utilizó la herramienta **Power BI**, la cual estaba conectada a la API, una vez descargados los dataset se procede a analizarlos con la finalidad de distinguir los datos que tenían y a partir de ello escoger cuales serían más convenientes; posterior a esto se determina que solo se trabajaran con 6 dataset que manejan información general y de esta manera se evita redundancia en los datos, dichos dataset son:

* **Penetración de Internet fijo (accesos por cada 100 hogares).**

* **Accesos a banda ancha y banda angosta por provincia.** 

* **Ingresos trimestrales por la prestación del servicio de Internet fijo.**

* **Acceso a Internet fijo por tecnología y provincia.**

* **Velocidad media de bajada de Internet fijo por provincia.**

* **Distribución de los accesos totales nacionales a Internet fijo por velocidad.**

Teniendo claro con que datos se trabajará, se procede a ralizar la limpeza y correción de los mismos, eliminando valores vacíos, cambiando datos erróneos  y creando las relaciones entre las diferentes tablas. 
<hr>

## **3. Creación de visualizaciones**
<p align=center>
<img src = 'Imagenes\Captura.PNG' height=300><p>

Para crear las visualizaciones se utlizó la herramienta Power BI, en la cual se crearon las relaciones de cardinalidad entre las diferentes tablas, buscando crear interacciones entre las mismas y crear un Dashboard interactivo como sepude observar en el siguiente [archivo](), como tambien se relizó un informe donde se analiza el [tablero_de_control]().











<hr>







<p align=center>
<img src = 'https://blog.soyhenry.com/content/images/2021/05/PRESENTACION-3.jpg' height=250><p>


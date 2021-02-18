<p><center> <img src="https://github.com/Alexanderariza/Analysis_CO2_level_Atm/blob/main/Img/logo_heat.png" width="1000"/> </p></center>

# Técnicas y Aplicaciones de Teledetección: Cambio Climático-Riesgos y Desastres

***

## Cambio climático: Análisis de niveles de CO2 en la atmósfera
En este cuaderno vamos a explorar parte del contenido de la **Unidad II. Integración de información para explicar relaciones causa y efecto.** Mediante el análisis de los cambios en las temperaturas medias globales, así como el aumento de las concentraciones de CO2 en la atmósfera.

## ¿Como funciona?
1. Puede [descargar](Analysis_of_CO2_levels_in_the_atmosphere.ipynb) el cuaderno de Jupyter Notebook y utilizar los recursos de computación de su PC. 
2. Otra opción alternativa, es el de [**Google Colab**]( https://colab.research.google.com). Como entorno de computación en la nube para cuadernos de Jupyter, la cual aprovecha los recursos técnicos externos, permitiendo que esta herramienta se pueda aplicar en dispositivos con una potencia de computo más limitada, incluidos dispositivos móviles como teléfonos y tabletas, en áreas con escaso ancho de banda. Para ello puede acceder a esta versión directamente haciendo clic en el icono de abajo.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alexanderariza/Analisis_nivel_CO2_-atm-sfera/blob/main/Colab/An%C3%A1lisis_nivel_CO2_en_la_atmosfera.ipynb)

## Acerca de este conjunto de datos:
## 1. Dióxido de Carbono CO2 - Observatorio Mauna Loa:<p><left> <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/Mauna_Loa_Solar_Observatory.jpg" width="600"/> </p></left> 
El registro de dióxido de carbono del Observatorio Mauna Loa, conocido como la **“Curva de Keeling”**, es el registro ininterrumpido más largo del mundo de concentraciones de dióxido de carbono atmosférico (CO2). Los científicos realizan mediciones atmosféricas en lugares remotos para tomar muestras de aire que es representativo de un gran volumen de la atmósfera terrestre y está relativamente libre de influencias locales.
<center> <img src="https://ichef.bbci.co.uk/news/640/cpsprodpb/1E63/production/_106197770_grafico_dioxido_de_carbono-nc.png" width="600"/> </p></center> 

## Contenido
Este conjunto de datos incluye una observación mensual de las concentraciones atmosféricas de dióxido de carbono (o CO2) del Observatorio Mauna Loa (Hawái) a una latitud de 19,5, una longitud de -155,6 y una elevación de 3397 metros.<br> 
Adicionalmente, trabajaremos con una compilación más reciente elaborada por **Berkeley Earth** , afiliado al Laboratorio Nacional Lawrence Berkeley. El estudio de temperatura de la superficie terrestre de Berkeley combina 1.600 millones de informes de temperatura de 16 archivos preexistentes. Está muy bien empaquetado y permite dividirlo en subconjuntos interesantes (por ejemplo, por país). Publican los datos de origen y el código de las transformaciones que aplicaron. También utilizan métodos que permiten incluir observaciones meteorológicas de series de tiempo más cortas, lo que significa que se deben desechar menos observaciones.

Columnas 1-3: proporcione la fecha en los siguientes formatos redundantes: año, mes y fecha decimal
Columna 4: Concentraciones mensuales de CO2 en partes por millón (ppm) medidas en la escala de calibración 08A y recolectadas a las 24:00 horas del día quince de cada mes.
Columna 5: La quinta columna proporciona los mismos datos después de un ajuste estacional, que implica restar de los datos un ajuste de 4 armónicos con un factor de ganancia lineal para eliminar el ciclo estacional de las mediciones de dióxido de carbono.
Columna 6: La sexta columna proporciona los datos sin ruido, generado a partir de una función spline cúbica rígida más funciones de 4 armónicos con ganancia lineal
Columna 7: La séptima columna son los mismos datos con el ciclo estacional eliminado.
## Referencia
Los datos de dióxido de carbono fueron recopilados y publicados por la Institución de Oceanografía Scripps de la Universidad de California bajo la supervisión de Charles David Keeling con el apoyo del Departamento de Energía de EE. UU., Redes de la Tierra y la Fundación Nacional de Ciencias.

## Preguntas a resolver:
<i>¿Cómo han cambiado los niveles de dióxido de carbono atmosférico en los últimos sesenta años?<br> 
¿Cómo cambian las concentraciones de dióxido de carbono estacionalmente?<br> 
¿Qué crees que causa este ciclo estacional?<br> 
¿Cuándo superarán los niveles de dióxido de carbono las 450 ppm partes por millón?<br></i>
  
[![License: Creative Commons Zero v1.0 Universal](https://lh3.googleusercontent.com/proxy/1Lf-mS_lKbHvQvL9Y1e7Oq9f2TVJfIcqzAVYPpWozaSvnfGDKto6_H1XpT7Jw83Z3FGZQ_cWlAP-Y7kw7YZ_WciVl7irUctxti5RuTW1x3-jB1P0N8FXhYWsGLiz02Q)](https://creativecommons.org/publicdomain/zero/1.0/)

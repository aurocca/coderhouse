# Introducción

La temática se basa en el análisis de precios del mercado inmobiliario sobre publicaciones hechas desde enero a junio de 2021 de Argentina, Uruguay, Brasil y EEUU. extraídos de un csv generado por <https://www.properati.com.ar/data/>.

Se quiere analizar las principales variables que determinan la evolución del mercado inmobiliario, considerando al “precio” como target.


# Objetivo (a definir):

Que se puede hacer con el target (precio) según tipo de propiedad, zona geográfica.

predecir el precio en las distintas áreas?

Con qué sector trabajaremos, solo Argentina?

El precio tiene un desvío alto, tenemos outliers que podemos analizar, ya que puede haber tipos de propiedades con precios fuera del target que alteren el análisis.

Idem que el anterior, pero con la superficie cubierta y total en los cuales debe existir un tipo de propiedad (seguramente un lote o terreno) que hace disparar los valores.


# Transformación de datos:

- Se filtran las Ventas en dólares.
- Se redondean los valores de rooms, bedrooms, bathrooms ya que son enteros para agrupar los valores.
- Se redondean los valores de Superficie Total y Superficie Cubierta. 
- Creación de una nueva columna sobre el rango de precios para comprar rangos y no valores.
- Eliminación de las propiedades sin tipificación cargada.

![](Aspose.Words.815cebd1-94a6-400b-a9be-fa8421002e34.001.png)

- Instalación de sidetable, se eliminan las propiedades de diferentes monedas y tipos de operación

# Visualización de los datos:

## Tipos de propiedades

![](Aspose.Words.815cebd1-94a6-400b-a9be-fa8421002e34.002.png)

Analisis de correlacion![](Aspose.Words.815cebd1-94a6-400b-a9be-fa8421002e34.003.png)

## Rango de precios por tipo de propiedad

![](Aspose.Words.815cebd1-94a6-400b-a9be-fa8421002e34.004.png)

## Análisis de relación

![](Aspose.Words.815cebd1-94a6-400b-a9be-fa8421002e34.005.png)






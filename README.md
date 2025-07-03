# Análisis de Facturación de Empresa de Bebidas

### Descripción del Proyecto

En este proyecto, me enfoqué en analizar el comportamiento de la facturación y los métodos de pago de una empresa internacional de bebidas refrescantes que opera en diversos países de América Latina. El objetivo principal fue entender las tendencias de facturación y las preferencias de pago de los consumidores en las diferentes regiones donde la empresa distribuye sus productos.


### Objetivos:

    * Estudiar y validar los datos de facturación.
    * Agrupar eventos de facturación para identificar patrones.
    * Visualizar los resultados del análisis para comprender el comportamiento de la facturación.

### Metodología:

El proyecto se basó en el análisis de un conjunto de datos de facturación de la empresa de bebidas, cargado desde un archivo Excel. Se realizó un análisis exploratorio de los datos. Las columnas de los datos se normalizaron cambiando sus nombres a minúsculas y renombrando algunas para mayor claridad (por ejemplo, 'país' a 'pais' y 'tamaño' a 'tamano'). Se agregó una columna para extraer el año de la fecha de facturación. Se contaron las facturas por ciudad y las formas de pago utilizadas para obtener una visión general. Se agruparon los datos para obtener la suma total de ventas por tienda, por forma de pago, y por la combinación de tienda y forma de pago. Finalmente, los datos agrupados se exportaron a un archivo Excel y se crearon visualizaciones gráficas para el análisis.

### Conclusiones:

Guadalajara fue la ciudad con mayor número de facturas emitidas, con 13,483 operaciones, seguida por Santiago de Chile (13,075) y Buenos Aires (12,344). Ciudad de México, Bogotá y Medellín se ubicaron en cuarto, quinto y sexto lugar, respectivamente.

Se identificaron cuatro métodos de pago principales: Crédito, Débito, Efectivo y Nequi.

En todas las visualizaciones realizadas, se observó una tendencia consistente en la preferencia de los usuarios por el pago con tarjeta. La tarjeta de crédito fue el método preferido, seguida de cerca por la tarjeta de débito. El efectivo ocupó el tercer lugar, y Nequi, una tecnología de pago más reciente, fue la menos utilizada.

### Lenguajes y herramientas principales:

    - Python 
    - Pandas (para manipulación de datos) 
    - Plotly Express (para visualizaciones) 
    - Openpyxl (para trabajar con archivos Excel) 

Este análisis proporcionó una comprensión clara del comportamiento de facturación y las preferencias de pago de los clientes en las diversas ubicaciones de la empresa, lo que puede servir como base para decisiones estratégicas en ventas y marketing.
COMPORTAMIENTO DE LOS CLIENTES VENTAS
PLANTEAMIENTO DEL PROBLEMA EMPRESARIAL 
 
Una empresa líder del sector minorista desea comprender mejor el comportamiento 
de compra de sus clientes para mejorar las ventas, la satisfacción del cliente y la 
fidelidad a largo plazo. El equipo directivo ha observado cambios en los patrones de 
compra según datos demográficos, categorías de productos y canales de venta (en 
línea frente a tiendas físicas). Les interesa especialmente descubrir qué factores —
como descuentos, reseñas, estacionalidad o preferencias de pago— impulsan las 
decisiones de los consumidores y las compras recurrentes. 
Se le ha encomendado la tarea de analizar el conjunto de datos sobre el 
comportamiento del consumidor de la empresa para responder a la siguiente 
pregunta empresarial fundamental: 
«¿Cómo puede la empresa aprovechar los datos de compra de los consumidores 
para identificar tendencias, mejorar la vinculación con el cliente y optimizar las 
estrategias de marketing y producto?» 
Entregables 
1. Preparación y modelado de datos (Python): Limpiar y transformar el conjunto de 
datos original para su análisis. 
2. Análisis de datos (SQL): Organizar los datos en un formato estructurado, simular 
transacciones comerciales y ejecutar consultas para extraer información clave sobre 
segmentos de clientes, fidelidad y factores que impulsan la compra. 
3. Visualización y hallazgos (Power BI): Crear un panel interactivo que destaque los 
patrones y tendencias clave, permitiendo a las partes interesadas tomar decisiones 
basadas en datos. 
4. Informe y presentación: Redactar un informe claro del proyecto que resuma los 
hallazgos principales y las recomendaciones empresariales. Preparar una 
presentación que comunique visualmente los hallazgos y las recomendaciones 
prácticas a las partes interesadas. 
5. Repositorio de GitHub: Incluir todos los scripts de Python, consultas SQL y 
archivos del panel en un repositorio bien estructurado.
DESCRICION GENERAL DEL PROYECTO 
Este proyecto analiza el comportamiento de compra de los clientes utilizando datos 
transaccionales de 3,900 compras en diversas categorías de productos. El objetivo 
es identificar patrones de gasto, segmentos de clientes, preferencias de productos 
y comportamiento de suscripción para apoyar la toma de decisiones estratégicas

RESUMEN DEL CONJUNTO DE DATOS 
 
Filas: 3,900 
Columns: 18 
 
CARACTERÍSTICAS CLAVE: 
Datos demográficos del cliente (edad, género, ubicación, estado de la suscripción) 
Detalles de la compra (artículo adquirido, categoría, importe de la compra, 
temporada, talla, color) 
Comportamiento de compra (descuento aplicado, código promocional utilizado, 
compras anteriores, frecuencia de compra, valoración de la reseña, tipo de envío) 
Datos faltantes: 37 valores en la columna de valoración de la reseña 
 
ANÁLISIS EXPLORATORIO DE DATOS CON PYTHON 
 
Se debe preparar y limpiar de los datos en Python. 
 
Exploración inicial: obtener estadísticas descriptivas. 
 
Gestión de datos faltantes: verificar los valores nulos e imputar los valores 
faltantes en la columna `Review Rating` utilizando la mediana. 
 
Estandarización de columnas: renombrar las columnas a formato snake_case para 
una mejor legibilidad y documentación. 

Ingeniería de características:  crear una columna nueva  agrupando las edades de 
los clientes. 
 
Verificación de consistencia de datos.


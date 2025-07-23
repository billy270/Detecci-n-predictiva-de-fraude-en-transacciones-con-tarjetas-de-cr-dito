Detección Predictiva de Fraude en Transacciones con Tarjetas de Crédito
1. Nombre de la investigación
Detección predictiva de fraude en transacciones con tarjetas de crédito

2. Descripción del dataset
La base de datos utilizada es el Credit Card Transactions Dataset, publicada en Kaggle por Priyam Choksi. Contiene aproximadamente 1,295,600 registros de transacciones con tarjetas de crédito, clasificadas como fraudulentas o no fraudulentas.

Cada transacción incluye variables como:

trans_date_trans_time: Fecha y hora de la transacción

cc_num: Número de tarjeta de crédito

merchant: Comercio donde ocurrió la transacción

category: Categoría de la transacción (entretenimiento, supermercado, etc.)

amt: Monto de la transacción

first, last: Nombre y apellido del titular de la tarjeta

gender: Género del titular

street, city, state, zip: Dirección del titular

lat, long: Coordenadas geográficas de la transacción

city_pop: Población de la ciudad de la transacción

job: Ocupación del titular

dob: Fecha de nacimiento del titular

trans_num: ID único de la transacción

unix_time: Fecha en formato Unix

merch_lat, merch_long: Coordenadas del comercio

merch_zipcode: Código postal del comercio

is_fraud: Indicador binario de fraude (1 = fraude, 0 = legítimo)


3. Motivo de selección del dataset
Este conjunto de datos fue seleccionado por las siguientes razones:

Representa un problema real en el ámbito financiero: la detección de fraude en transacciones electrónicas.

Es un tema de alto interés, especialmente porque he trabajado con elementos similares y me gustaría profundizar en el análisis del comportamiento fraudulento.

Permite aplicar técnicas de aprendizaje supervisado, incluso en contextos de datos altamente desbalanceados, lo cual plantea un reto técnico interesante.

4. Introducción al contexto
El fraude financiero en transacciones electrónicas es una amenaza constante para instituciones financieras, comercios y usuarios. Según Q-Vision, los bancos panameños reportaron pérdidas de 14.2 millones de dólares en 2024 debido al fraude sintético.

Tradicionalmente, la detección de fraude se ha basado en reglas estáticas, las cuales no son efectivas ante el cambio dinámico en los patrones de comportamiento fraudulento. Por esta razón, los modelos de Machine Learning supervisado se han convertido en herramientas eficaces para detectar patrones anómalos con mayor precisión y adaptabilidad.

Esta investigación tiene como objetivo explorar, entrenar y evaluar modelos de clasificación capaces de detectar transacciones fraudulentas de forma eficiente, incluso cuando las variables están parcialmente anonimizadas. Se busca que el resultado sea replicable, interpretable y útil para futuras aplicaciones en entornos reales.

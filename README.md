# alura_desafio_2_pra
Proyecto "Churn de Clientes". Análisis ficticio de una empresa de telefonía y servicios de Internet que enfrenta una alta tasa de cancelaciones y busca entender los factores que le generan esas cancelaciones. 

# **Challenge ONE Data Science – Telecom X**

## Propósito del análisis realizado
En este proyecto se realiza la etapa de limpieza y análisis de datos de clientes de la empresa proveedora de telefonía e Internet “Telecom X”, apuntando a entender los factores que conducen a la renuncia o “churn” de los clientes. Asimismo se procura extraer algunas conclusiones e Insights del análisis preliminar de los datos y brindar recomendaciones a efectos de mejorar la retención de los clientes.  

## Estructura del proyecto y organización de los archivos.

1. El proyecto se basa en los datos de clientes provistos por la empresa, en formato json.
Enlace de archivos: 'https://raw.githubusercontent.com/alura-cursos/challenge2-data-science-LATAM/refs/heads/main/TelecomX_Data.json'

3. Los campos que componen la base se presentan en el siguiente “Diccionario de datos”.
   
*Diccionario de datos*
* •	customerID: número de identificación único de cada cliente
* •	Churn: si el cliente dejó o no la empresa
* •	gender: género (masculino y femenino)
* •	SeniorCitizen: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
* •	Partner: si el cliente tiene o no una pareja
* •	Dependents: si el cliente tiene o no dependientes
* •	tenure: meses de contrato del cliente
* •	PhoneService: suscripción al servicio telefónico
* •	MultipleLines: suscripción a más de una línea telefónica
* •	InternetService: suscripción a un proveedor de internet
* •	OnlineSecurity: suscripción adicional de seguridad en línea
* •	OnlineBackup: suscripción adicional de respaldo en línea
* •	DeviceProtection: suscripción adicional de protección del dispositivo
* •	TechSupport: suscripción adicional de soporte técnico, menor tiempo de espera
* •	StreamingTV: suscripción de televisión por cable
* •	StreamingMovies: suscripción de streaming de películas
* •	Contract: tipo de contrato
* •	PaperlessBilling: si el cliente prefiere recibir la factura en línea
* •	PaymentMethod: forma de pago
* •	Charges.Monthly: total de todos los servicios del cliente por mes
* •	Charges.Total: total gastado por el cliente


4. Los análisis realizados se presentan en el archivo ‘TelecomX_Latam_Pra.ipynb’ con el código para ejecutar en Colab. 
En dicho archivo se han realizado principalmente:

* ✅ ETL (Extracción, Transformación y Carga) en la preparación de los datos. Analizando: duplicados, valores vacíos, valores nulos, tipos de datos, valores atípicos o outliers, consistencia y validez de datos categóricos, normalización de datos.
* ✅ Visualizaciones para identificar patrones, tendencias, correlaciones de los datos
* ✅ Análisis Exploratorio de Datos (EDA) a partir del análisis visual y del uso de algunos tests para variables numéricas y categóricas se presentan algunos resultados relevantes, su interpretación y se sugieren ciertas acciones para reducir el abandono. 

## Tecnologías Utilizadas
* •	Python 
* •	Librerias Pandas / Matplotlib.pyplot / Seaborn / numpy   /scipy.stats
* •	Google Colab 

## Guía de Instalación y Ejecución
La notebook puede ejecutarse en Google Colab. Las librerías utilizadas están incluidas en el código. 
Para ejecutar seguir los siguientes pasos:
* 1. Abrir el archivo ‘TelecomX_Latam_Pra.ipynb’ en Google Colab.
* 2. Ejecutar las celdas de código desde la primera a la última. Es importante seguir la secuencia pues deben instalarse librerías e importarse los datos de la base. Además se realizan transformaciones necesarias en pasos subsiguientes. 
* 3. En el Colab se puede visualizar el código y los resultados como tablas y gráficos.
* 4. El apartado “Informe Final” en el colab presenta los resultados el análisis. 

# Análisis de criptomonedas

El objetivo de este trabajo es recomendar 10 criptomonedas como potenciales activos de inversión que una empresa ofrecera a sus clientes y es el primer acercamiento de la empresa al mundo de las criptomonedas. 

Para la realización de este trabajo utilice Python con las siguientes librerias y/o herramientas:

* Jupyter Note Books: para realizar mi EDA
* Pandas: para el manejo de dataframes y analisis de los mismos
* Matplotlib y seaborn: para la visualización de los datos
* pycoingecko: para obtener los datos necesarios para el análisis de criptomonedas desde la API de CoinGecko
* sqlalchemy: para conectar mi base de datos mysql a Python
* docker: para virtualizar aplicaciones (mysql, phpmyadmin)
* mysql(contenedor): para alojar mis datos en un servidor
* phpmyadmin(contenedor): para manejar la base de datos
  
Para acceder a phpmyadmin se utilizan los siguientes datos:

* usuario: root
* ip address: 172.19.0.2
* contraseña: naitais

Para acceder e importar las tablas hacia PowerBI utilizando como conexion el contenedor de Docker con MySQL:

* Servidor: localhost:3306
* Base de datos: criptomonedas

DISCLAIMER: Tuve que instalar el siguiente conector de MySQL para poder realizar la conexion:
* Me sirvio la 8.0.28
https://downloads.mysql.com/archives/c-net/

Dejo link del informe:

https://docs.google.com/document/d/1MAs2yQH-5Fit2iPd_nDZh_lDzxjvtTkYZRD7rsedg_U/edit?usp=sharing


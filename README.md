<div style="text-align: center;">
# Análisis de Criptomonedas
</div>

![imagen animada Galicia duda sobre criptomonedas](galicia_duda_imagen_readme.png)

<div style="text-align: justify;">
El objetivo de este trabajo es recomendar 10 criptomonedas como potenciales activos de inversión que una empresa ofrecerá a sus clientes cuando es el primer acercamiento de la empresa al mundo de las criptomonedas. Accediendo a los datos brindados por la libreria y [API de CoinGecko](https://www.coingecko.com/es/api "Sitio oficial de la API de CoinGecko"), recupere la información necesaria y según las KPIs detalladas en el siguiente [informe](https://docs.google.com/document/d/1MAs2yQH-5Fit2iPd_nDZh_lDzxjvtTkYZRD7rsedg_U/edit?usp=sharing "Informe del análisis para la Empresa Galicia"), realice este análisis para la empresa Galicia.

Para la realización de este trabajo utilice las siguientes librerias y/o herramientas:

* Jupyter Notebooks: para realizar mi EDA
* Pandas: para el manejo de dataframes y análisis de los mismos
* Matplotlib y Seaborn: para la visualización de los datos
* pycoingecko: para obtener los datos necesarios desde la [API de CoinGecko](https://www.coingecko.com/es/api "Sitio oficial de la API de CoinGecko")
* SQLAlchemy: para conectar mi base de datos MySQL a Python
* Docker: para virtualizar aplicaciones (MySQL, phpMyAdmin)
* MySQL (contenedor): para alojar mis datos en un servidor
* phpMyAdmin (contenedor): para manejar la base de datos

La estructura del proyecto es la siguiente:

* Carpeta con dashboard de PowerBI con imágenes utilizadas
* Carpeta con los datasets en caso de no poder acceder al servidor MySQL
* Carpeta de Docker: con el archivo .yml para hacer un docker-compose up de phpMyAdmin y el servidor MySQL
* README.md
* Archivo EDA.ipynb con el análisis exploratorio de los datos
* SQLAlchemy_bridge.ipynb donde se muestra la primera conexión al servidor, testeo y creación de la tabla principal en MySQL

Para acceder a phpMyAdmin se utilizan los siguientes datos:

* Usuario: root
* IP address: 172.19.0.2/172.19.0.3 (la IP no está seteada, así que a veces cambia)
* Contraseña: naitais

Para acceder e importar las tablas hacia PowerBI utilizando como conexión el contenedor de Docker con MySQL:

* Servidor: localhost:3306
* Base de datos: criptomonedas

DISCLAIMER: Tuve que instalar el siguiente [conector](https://downloads.mysql.com/archives/c-net/ "Conector para MySQL") de MySQL para poder realizar la conexión (Versión 8.0.28).

[Link del informe](https://docs.google.com/document/d/1MAs2yQH-5Fit2iPd_nDZh_lDzxjvtTkYZRD7rsedg_U/edit?usp=sharing "Informe del análisis para la Empresa Galicia") para la empresa Galicia donde explico a detalle mi análisis, su fundamento y la conclusión.
</div>






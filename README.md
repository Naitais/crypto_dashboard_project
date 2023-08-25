
# <div align="center">Análisis de Criptomonedas</div>


![imagen animada Galicia duda sobre criptomonedas](galicia_duda_imagen_readme.png)

El objetivo de este trabajo es recomendar 10 criptomonedas como potenciales activos de inversión que una empresa ofrecerá a sus clientes cuando es el primer acercamiento de la empresa al mundo de las criptomonedas. Accediendo a los datos brindados por la libreria y [API de CoinGecko](https://www.coingecko.com/es/api "Sitio oficial de la API de CoinGecko"), recupere la información necesaria y según las KPIs detalladas en el siguiente [informe](https://docs.google.com/document/d/1MAs2yQH-5Fit2iPd_nDZh_lDzxjvtTkYZRD7rsedg_U/edit?usp=sharing "Informe del análisis para la Empresa Galicia"), realice este analisis para la empresa Galicia.


Para la realización de este trabajo utilice [Python](https://www.python.org "Sitio oficial de Python") con las siguientes librerias y/o herramientas:


* Jupyter Notebooks: para realizar mi EDA
* Pandas: para el manejo de dataframes y análisis de los mismos
* Matplotlib y seaborn: para la visualización de los datos
* pycoingecko: para obtener los datos necesarios para el análisis de criptomonedas desde la [API de CoinGecko](https://www.coingecko.com/es/api "Sitio oficial de la API de CoinGecko")
* sqlalchemy: para conectar mi base de datos mysql a [Python](https://www.python.org "Sitio oficial de Python")
* [docker](https://www.docker.com "Sitio oficial de Docker"): para virtualizar aplicaciones (mysql, phpmyadmin)
* mysql(contenedor): para alojar mis datos en un servidor
* phpmyadmin(contenedor): para manejar la base de datos


La estructura del proyecto es la siguiente:


* Carpeta con dashboard de PowerBI con imágenes utilizadas
* Carpeta con los datasets en caso de no poder acceder al servidor [MySQL](https://www.mysql.com "Sitio oficial de MySQL")
* Carpeta de [docker](https://www.docker.com "Sitio oficial de Docker"): con el archivo .yml para hacer un docker-compose up de phpmyadmin y el servidor [MySQL](https://www.mysql.com "Sitio oficial de MySQL")
* README.md
* Archivo EDA.ipynb con el análisis exploratorio de los datos
* SQLAlchemy_bridge.ipynb donde se muestra la primera conexión al servidor, testeo y creación de la tabla principal en   [MySQL](https://www.mysql.com "Sitio oficial de MySQL")


Para acceder a phpmyadmin se utilizan los siguientes datos:


* usuario: root
* ip address: 172.19.0.2/172.19.0.3 (la ip no esta seteada así que a veces cambia)
* contraseña: naitais


Para acceder e importar las tablas hacia PowerBI utilizando como conexión el contenedor de Docker con MySQL:


* Servidor: localhost:3306
* Base de datos: criptomonedas


DISCLAIMER: Tuve que instalar el siguiente [conector](https://downloads.mysql.com/archives/c-net/ "Conector para MySQL") de MySQL para poder realizar la conexión:
* Me sirvio la versión 8.0.28


[Link del informe](https://docs.google.com/document/d/1MAs2yQH-5Fit2iPd_nDZh_lDzxjvtTkYZRD7rsedg_U/edit?usp=sharing "Informe del análisis para la Empresa Galicia") para la empresa Galicia donde explico a detalle mi análisis, su fundamento y la conclusión.
</div>
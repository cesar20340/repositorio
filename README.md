# Control de Inventario

## Indice

| Ítem | Enlace | Descripción  |
|:----:|:-------|:------------:|
| Diseño base de datos | [Enlace](https://github.com/cesar20340/Repositorio/blob/master/Dise%C3%B1o%20de%20base%20de%20datos.jpg) | UML o similar con el diseño de la base de datos|
| Mockups | [Enlace](https://github.com/cesar20340/Repositorio/tree/master/Mockup) | Diseño de las vistas|
| Diagramas UML| [Enlace](https://github.com/cesar20340/Repositorio/blob/master/Diagrama.png)|Casos de usos de alto nivel y detallados, diagrama de secuencias,etc|
| Código | [Enlace](https://github.com/cesar20340/Repositorio/tree/master/Codigo_Control%20de%20Inventario/c_stock) | Carpeta que contiene el código fuente|
| Pruebas de aplicación| [Enlace]|resultados y scripts|

## Instrucciones
Lo primero es conectarnos a la base de datos con el siguiente comando:

mysql -u <username> -p <database>
  
Donde remplazas <username> por tu nombre de usuario y <database> por el nombre de la base de datos (vacía) en la que vas a importar tu backup. Entonces se te pedirá el password.
  
Una vez dentro ejecutas el siguiente comando

source <database.sql>

Donde remplazas <database.sql> por la ruta al backup. En mi caso, uso la ruta completa partiendo desde C:/ aunque la ruta relativa a tu instalación de MySQL también debería funcionar.

Se debe copiar la carpeta del codigo c_stock en la carpeta htdocs de XAMPP
luego hacer la conexion correcta con los puertos a ocupar, dentro del codigo, en el archivo db.php segun los datos correspondientes de la base de dato con la cual se requiere hacer conexion.

## Conclusiones del proyecto

Si bien el local comercial consta de un manejo de inventario en forma de “Excel” este no es suficiente para poder combatir con la problemática actual de la institución, puesto que al realizar cualquier compra o venta de activos la digitación de los productos se debe realizar de forma manual, haciendo que el proceso sea mucho más tedioso y lento de lo que fuera si es que tuviera un software dedicado a solucionar este problema. Por lo cual este software ayudaria a optimizar ese proceso 

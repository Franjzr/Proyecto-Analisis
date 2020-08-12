# Proyecto-Analisis MYF



## Comenzando 🚀

Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.


### Pre-requisitos 📋

Que cosas necesitas para instalar el software y como instalarlas

Nesecitas visual studio 2019 link para que lo puedas descargar https://visualstudio.microsoft.com/es/downloads/
Una cuenta de github para clonar el repositorio 
La base de datos local en sql server 2017 link para descargar https://www.microsoft.com/es-es/sql-server/sql-server-downloads



### Instalación 🔧

**Instalacion del repositorio en visual studio 2019**

1-Abra Visual Studio 2019.
En la ventana de inicio, elija Clonar o desproteger código.

2-Especifique o escriba la ubicación del repositorio y, luego, elija Clonar.

3-Visual Studio abre el proyecto desde el repositorio.
Si hay disponible un archivo de solución, aparecerá en el menú emergente "Soluciones y carpetas". Elíjalo y Visual Studio abrirá la solución.

**Instalacion de la base de datos local Sql server 2017**

1-De las opciones de instalación, hacer clic en Nueva instalación stand-alone de Microsoft SQL Server 2017 y esperar que acabe de arrancar el asistente.

2-Página de licencia, hacer clic en Siguiente para continuar.

3-Comprobación de prerrequisitos, si todo está correcto continúa. Y posibilidad de hacer el Windows Update. De momento dejamos el checkbox sin marcar. Hacer clic en el botón Siguiente.

4-Instalación de los archivos de instalación. Valga la redundancia. Y comprobación de las reglas de instalación, en que será normal que advierta de la configuración del cortafuegos que haremos al finalizar la misma. Hacer clic en el botón Siguiente.

5-Instalación de aplicaciones, aquí seleccionar según las necesidades del servidor de bases de datos. Como que el objetivo de esta entrada es sólo el servidor de base de datos básico, se marca sólo el checkbox del motor de base de datos. Cambiar la ubicación de la instancia y aplicaciones compartidas en la unidad correspondiente. En mi caso la unidad E. Hacer clic en el botón Siguiente para continuar.

6-Seleccionar el tipo de autenticación de usuarios sobre el SQL Server. Personalmente me gusta dejar las dos: Windows y SQL Server, por lo tanto, seleccionar modo mixto. Especificar una contraseña fuerte (que nos conocemos) para el usuario administrador de SQL Server (sa). Haciendo clic en el botón Añadir nos permite añadir el grupo de usuarios administradores de SQL Server del Active Directory como administradores de SQL Server, es la opción recomendada.






## Construido con 🛠️
LINQ https://www.completecsharptutorial.com/mvc-articles/add-missing-linq-sql-class-vs-2017-2019.php

.NetFramwework 4.7.2

MVC Visual Studio

SQL Server 2017

## Autores ✒️

Francisco Zúñiga Rojas  
Brayan Rojas Chaves  
Julio Valverde Mora  
André Cruvelier Aguilar 



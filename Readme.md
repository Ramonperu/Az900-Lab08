# Implementacion de Azure Functions
*Noviembre 25 de 2022*, Ramón Peinado Ruiz



Seleccionamos Funcion App, tras buscarlo en Home dentro del portal,

​	<img src="/img/1ºimagenn.png" alt="2ºimagenn" style="zoom:80%;" />

Creamos una con los siguientes parámetros, los demás se dejaran en predeterminado o vacíos al no ser obligatorios

| Settings          | Value                                             |
| ----------------- | ------------------------------------------------- |
| Subscription      | the name of your Azure subscription               |
| Resource group    | the name of a new resource group **myRGFunction** |
| Function App name | **function-xxxx**                                 |
| Publish           | **Code**                                          |
| Runtime stack     | **.NET**                                          |
| Version           | **3.1**                                           |
| Region            | **East US**                                       |

<img src="/img/2ºimagenn.png" alt="2ºimagenn" style="zoom:80%;" />

Comprobamos que se haya desplegado bien volviendo a **Home > Function App**

<img src="/img/3ºimagenn.png" alt="3ºimagenn" style="zoom:80%;" />

Una vez dentro de nuestra Function App seleccionamos Functions y añadimos una nueva

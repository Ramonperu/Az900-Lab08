# Implementación de Azure Functions
Enero 16 de 2023*, Ramón Peinado Ruiz

Vamos a crear una Función que nos devuelva un mensaje tras una solicitud HTTPS

------

Seleccionamos Function App, tras buscarlo en Home dentro del portal,

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

<img src="/img/4ºimagenn.png" alt="3ºimagenn" style="zoom:80%;" />

Dentro de las opciones de desarrollador vamos a **CODE+TEST** obtenemos el link para la funcion con la **KEY DEFAULT**

<img src="/img/5ºimagenn.png" alt="3ºimagenn" style="zoom:80%;" />

 https://function-rpr.azurewebsites.net/api/HttpTrigger1?code=qhlSfJ3M-lElV2eyQiQt0Q10y54VHz8bd71QKdsmZO1bAzFuElAoIg== 

Hay varias maneras de modificar esta solicitud, una de ellas es añadir al final del link &name="nombre"

Dando como respuesta lo siguiente

<img src="/img/6ºimagenn.png" alt="6ºimagenn" style="zoom:80%;" />

O modificando el codigo:

<img src="/img/7ºimagenn.png" alt="7ºimagenn" style="zoom:80%;" />

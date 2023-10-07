## Programa de capacitacion
### Tarea 3
Práctica de algoritmos de digestión:
- Guardamos como valor la URL https://api.binance.com/api/v1/ticker/24hr?symbol=XRPBTC en un archivo llamado json.txt 
![](/Tarea3/imagenes/echo.png)

- Obtenemos el contenido de la URL https://api.binance.com/api/v1/ticker/24hr?symbol=XRPBTC
![](/Tarea3/imagenes/wget.png)


- Validamos el contenido del archivo 24hr?symbol=XRPBTC generado con wget:  
![](/Tarea3/imagenes/cat_wget.png)

- Generamos el SHA del archivo json.txt
![](/Tarea3/imagenes/sha_echo.png)

- Generamos el SHA del archivo 24hr?symbol=XRPBTC
![](/Tarea3/imagenes/sha_wget.png)

El SHA es compltamente diferente debido a que en el archivo json.txt solo generamos una cadena con los caracteres que componen la URL, sin embargo el archivo 24hr?symbol=XRPBTC fué formado con el contenido json de la URL


Validación de URL con Postman:

Cuando damos de alta la URL https://api.binance.com/api/v1/ticker/24hr?symbol=XRPBTC podmos ver la respuesta JSON mediante una petición GET
![](/Tarea3/imagenes/get.png)
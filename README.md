Este proyecto corresponde a la cátedra "Desarrollo de Software", y tiene como objetivo construir el MVP de una aplicación que permite gestionar delivery de comida de restaurantes y rotiserías. 
La aplicación tiene dos tipos de usuarios, vendedores (los restaurantes o rotiserías) y compradores.  

Los vendedores pueden ingresar al sistema para:
* Gestionar sus datos.  
* Gestionar menú de platos y bebidas que ofrecen.
* Revisar la lista de pedidos recibidos por parte de los clientes. 
* Actualizar el estado de un pedido, desde que es recibido, aceptado, preparado, hasta enviado. 

Los compradores pueden ingresar al sistema para:
* Gestionar sus datos.
* Crear un pedido indicando para un restaurante en particular que seleccione, cuales platos solicitará y la forma de pago. El precio de un pedido se calcula diferente según la forma de pago. 
* Ver su historial de pedidos. 

Este proyecto fue realizado utilizando Java Spring Boot. Para las interfaces se utilizó HTML, CSS y Thymeleaf. La base de datos es MySQL.

En la carpeta ```pantallas``` se pueden visualizar las distintas pantallas del sistema. Por simplicidad, se nos solicitó simular un administrador (es decir, que puede gestionar clientes, vendedores, items menú y pedidos).
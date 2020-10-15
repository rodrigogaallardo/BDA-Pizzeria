# BDA-Pizzeria

La base de datos consiste en una aplicación en donde el cliente puede hacer un pedido, este lo generara junto a su ticket con un detallado de la enmienda.
La  entendida “Cliente” consta de: usuario, password, nombre y apellido, email, teléfono, domicilio. A su vez el “Pedido” incorporara el  usuario que realiza la petición, generara el id de la demanda, el / los productos que desea adquirir junto con su cantidad, más la hora en que se realizó la petición y el precio total de la compra.
La entidad “Pedido” tiene relación directa con las entidades “Productos” y “Ticket”, en la primera se encuentran todos los productos de la pizzería; mientras que en ticket solo aparecerán su propia ID, la ID del pedido y fecha – hora del momento en cual se despacha hacia el cliente.
La pizzería cuenta con la entidad “Producto”, en donde cada pizza cuenta con un ID, nombre, descripción y precio final.

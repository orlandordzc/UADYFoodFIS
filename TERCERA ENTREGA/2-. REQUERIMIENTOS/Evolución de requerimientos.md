Al ser la comunicación dentro de la cafetería, el principal problema, planteamos diferentes soluciones, teniendo apoyo de nuestro maestro y estando en continua comunicación con nuestros clientes, enumeramos 7 funcionalidades esenciales que el sistema debería cumplir para satisfacer las necesidades y resolver el problema planteado. 
La cafetería mencionó que el principal problema de comunicación surgía al momento de hacer llegar las órdenes a cocina, en muchas ocasiones el intercambio de información se daba por medio de gritos, por lo que nosotros buscábamos la forma de que esa información se transmitiera de forma más rápida y eficiente, es decir que las ordenes proporcionadas en la caja se reflejaran con el personal de cafetería sin la necesidad de un intercambio verbal. 

Con lo antes mencionado se enumeraron 4 funcionalidades principales: 

Reflejar pedido  
Esto nos permitiría pasar los pedidos realizados en la caja al personal de cocina, sin la necesidad de una comunicación oral entre ellos. 

Clasificar productos 
Se tenía pensado en organizar los productos en existencia haciendo de un código formado por diferentes caracteres asociados al nombre de dicho producto y el precio por unidad. 

Registrar pedido 
Para poder reflejar un pedido, en primer lugar, el sistema debe poder registrar una orden, para posteriormente trasladarla a cocina, con lo que esta funcionalidad era una de las principales que debíamos tener en cuenta. 

Organización 
Relacionado con lo anterior, para poder realizar una orden, el sistema tener disponible el menú de los productos con los que cuenta la cafetería, es decir, el personal puede agregar y eliminar cada uno de los productos de su inventario. 

Como funcionalidades que no son de primera necesidad tomamos en cuenta las siguientes:

Editar pedido 
Esto en caso de que alguno de los clientes proporcione mal algún dato relacionado o que quiera agregar o eliminar algún producto. 

Clasificar pedidos 
Nuestro sistema debía clasificar los productos mediante su tipo, es decir, que sean embotellados, galletas, frituras, comidas, entre otros. 

Pedido entregado 
Luego de una fase de validación, en donde presentamos las primeras interfaces que se basaron con estos primeros requerimientos, estos sufrieron algunos cambios: 

La opción de clasificar los productos mediante un código fue descartada, debido a que tomamos en cuenta que este sistema puede ser utilizado por personas ajenas a la cafetería y en principio podrían realizar las tareas ya enumeradas, y con los códigos, se necesitaría un conocimiento previo, de cual código se relaciona con que producto. 

Se descartó clasificar los productos mediante su tipo, ya que veíamos innecesario incluir productos que no requieren intervención de las partes ya mencionada como lo son la caja y la cocina, estos están a la mano del personal de caja y solo requieren comunicación con el cliente, con todo lo anterior mencionado, nuestro sistema se centraría únicamente en productos preparados por cocina, dejando a un lado a los que son de consumo instantáneo. 
Incluimos un requerimiento al cual le dimos suma importancia, la opción de agregar especificaciones, en caso de que algún cliente quiere un producto sin un ingrediente, esto se puede hacer agregando una especificación al producto de su preferencia. 
Agregamos la clasificación de los pedidos según su estado, es decir, si están en espera de ser preparados, si ya su preparación ya está en proceso y si el pedido se completó. 

Luego de los cambios, nuestros requerimientos evolucionaron a lo siguiente:

•	Clasificar productos 
El sistema deberá permitir organizar los productos disponibles. 

•	Ordenar 
El sistema permitirá al personal encargado de la caja y/o a los clientes, realizar una serie de pedidos. 

•	Generar número y monto total del pedido 
El sistema, al concluir el proceso de ordenar, se encargará de generar un número de pedido en donde se encuentre el monto de compra, esto con el fin de que el alumnado pueda monitorear el estado del pedido. 

•	Reflejar pedido 
El sistema permitirá al personal encargado de la cocina y a la clientela, leer el pedido y monitorear el estado de este mediante el número proporcionado anteriormente. 

•	Editar pedido 
El sistema permitirá la opción de editar el pedido, una vez reflejado en la cocina. 

•	Clasificar pedidos 
El sistema permitirá agrupar los pedidos en tres apartados, siendo estos, “pedidos completados”, “pedidos en proceso” y “pedidos pendientes”. 

•	Pedido entregado 
El sistema permitirá una vez concluido, la opción de mover el pedido desde la sección de “pedidos pendientes” a la sección de “pedidos completados”. 

•	Eliminar pedido completado 
El sistema permitirá a la cajera, la opción de eliminar el pedido de la sección de “pedidos completados” una vez que se haya entregado éste al cliente. 

•	Especificaciones del pedido 
El sistema presentará los aditamentos del pedido, permitiendo que el usuario se encargue de seleccionarlos a su gusto.

Para concluir los con los requerimientos de nuestra última entrega, cabe mencionar, que no hubo modificación alguna en estos, debido a que los comentarios realizados ya estaban contemplados dentro de las interfaces, únicamente faltaba su habilitación. 

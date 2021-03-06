# U-Food

![Imgur](http://i.imgur.com/TczM920.jpg)

## Descripcion
UFood es una solución integral que evita las largas esperas en los restaurantes.
Integra 4 aplicaciones que solucionan las distintas fases de la preparación de la comida, su entrega y su cobro.

La idea es que este sistema no solo logre una mejor gestión de la comida y las filas si no que ofrezca una forma eficiente de realizar pagos y ordenar comida aun estando lejos del restaurante.


![Imgur](http://i.imgur.com/h3tcaA0.jpg)


Cada pedido realizado será enviado a un panel web en tiempo real una vez que el cliente haya realizado un check in en el lugar de esta manera podemos llevar un control de los pedidos diarios así como de los activos de cada negocio por parte del cajero, además cada preparador de comida verá en tiempo real las ordenes que debe preparar y las podrá marcar como listas para que pasen a la zona de entrega, todo esto por medio de sockets

![Imgur](http://i.imgur.com/IGia2gP.jpg)


## API REST
El código para la API REST se encuentra en [Github](https://github.com/siulpolb/PayU).  
La implementación de la API se encuentra en [Openshift](http://payu-siulpolb.rhcloud.com/api/)

El servicio web será el encargado de manejar la información de los usuarios, los menus y los pedidos.
Además alimentará las aplicaciones web y recibirá datos de las aplicaciones móviles. Este tipo de tecnología permite expandir el funcionamiento del servicio sin afectar las aplicaciones existentes, así como incluir más dispositivos y servicios de manera sencilla


## App Android
El código para la app de android se encuentra en el [Repo Github](https://github.com/javpoblano/payu-android)

![Imgur](http://i.imgur.com/djZH5qe.jpg)

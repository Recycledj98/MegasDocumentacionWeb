---
title: Formas de Pago
weight: 1
math: true
---
Permite definir las diferentes formas de pago, tanto para clientes como para proveedores.

Cuando accedemos a esta pantalla se nos mostrará una ventana con todas las formas de pago definidas al igual que los botones relativos a las acciones que podremos realizar. 

![FormaDePago](/docs/images/FormasDePago/FormadePago.png)

A la hora de crear una forma de pago podremos hacerlo mediante la botonera usando el botón de alta o mediante el atajo de teclado (Ctrl+A) lo cual nos abrirá una ventana con los siguientes campos.

![FormaDePagoAlta](/docs/images/FormasDePago/AltaForma.png)

* **Codigo de pago C**: Código de la forma de pago. Es un campo alfanumérico.
* **Forma de pago**: Nombre de la forma de pago.
* **Número de vencimientos**: Número **total** de vencimientos.
* **Desplazamiento 1-Vto**: Número de días que sumará a la fecha de factura para conformar el primer vencmiento.
* **Días entre Vencimientos**: Días que habrá entre vencimientos en el caso de que haya más de uno.

* **Emitir Recibo**: Si la forma de pago lleva asociada la impresión de un recibo elegiremos
la opción S, si no hay recibo asociado dejaremos la opción por defecto N.
* **% Entrada**: Porcentaje del total de la factura/albarán que se dará por cobrado automáticamente a la emisión del documento (albarán o factura).
* **% DTO PP**: Porcentaje de descuento por pronto pago. Se aplicará automáticamente en
las facturas de los clientes que tengan asociado la forma de pago.
* **Cuenta Contable**: Cuenta de contrapartida a la que se destinará el cobro.
* **Descripción**: Descripción del pago. Esta descripción aparecerá automáticamente al dar el pago de un vencimiento de una factura.
* **Total a/cta Vto**: Total a cuenta vencimiento, indica si el total del vencimiento 

* **Recargo**: Porcentaje de recargo antes de impuestos.

* **Riesgo Dias/Num**: Riesgo en días o número de albaranes o facturas permitidas para esta forma de pago.

{{< callout type="info">}}
En el caso de que estipulemos 10 días de riesgo para albaranes o facturas, si el cliente con esa forma de pago tiene pagos pendientes de más de 10 días, se le inhabilita para la venta hasta que se paguen esos documentos. Lo mismo aplica para los días.

{{< /callout>}}

* **RETENC_PAG**:
* **Cobra Representante**: Permite la posibilidad de que el representante pueda realizar cobros bajo esta forma de pago.



{{< callout type="info">}}
Ejemplo de formas de pago
{{< /callout>}}
![fondo](/images/fondo.png)
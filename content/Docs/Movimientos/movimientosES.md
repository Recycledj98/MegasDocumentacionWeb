---
title: Movimientos E/S almacén
weight: 1
---

Desde esta pantalla podemos observar los movimientos de los artículos tanto de entrada como
de salida, entre almacenes y hasta los cambios de estado que lleguen a alcanzar.
Cada albarán de venta genera una serie de movimientos que afectan al stockage, cada albarán
de compra también genera movimientos y todos ellos aparecerán automáticamente en esta
pantalla. Para generar movimientos entre almacenes por ejemplo, tenemos que dar de alta
nosotros mismos esos movimientos desde esta pantalla.

La pantalla de movimientos tiene el siguiente aspecto

![ESALMA](/docs/images/ESALMA.png)

* **Referencia**: Código numérico generado automáticamente por la aplicación con el fin de llevar un registro.
* **Artículo**: Código del artículo.
* **TI**: Tipo de movimiento:
  * CA: Cambio de almacén.
  * CR: Cambio de ruta.
  * E: Entrada proveedor.
  * FR: Falta rutas.
  * I: Intercambio entre almacenes.
  * MU: Muestras.
  * NE: Nevera.
  * PR: Promociones.
  * RA: Roturas almacén.
  * RE: Regalo.
  * RR: Rotas Rutas.
  * S: Venta reparto.
  * SA: Sobra almacén.
  * SR: Sobra Rutas.
  * VA: Venta almacén.

{{< callout type="info">}}
Cada uno de estos tipos de movimientos afecta a una operación distinta dentro del programa. Por ejemplo CA (Cambio de almacén) mueve el producto de un almacén a otro.
{{< /callout>}}

* **Descripción**: Apunte que se hace con el movimiento.
* **O**: Indica el almacén de Origen.
* **D**: Indica el almacén de Destino.
* **Unidades**: Indica el total de unidades implicadas en el movimiento.
* **Precio**: Indica el precio del artículo en el momento del movimiento.
* **Fecha**: Indica la fecha del movimiento.


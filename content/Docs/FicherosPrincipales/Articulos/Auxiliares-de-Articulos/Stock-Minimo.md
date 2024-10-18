---
title: Asignar Stock Minimo automáticamente
weight: 14
---

El programa cuenta con un sistema de gestión de almacenes que permite definir un stock mínimo, el cual representa el margen de seguridad de producto que debe mantenerse en el inventario. Cuando el nivel de stock alcanza esta cantidad mínima, el sistema emitirá avisos automáticos cada vez que se realice una venta, informando sobre la cantidad insuficiente de producto disponible. 

El programa ofrece una funcionalidad para realizar una **previsión de compras** basada en el **consumo registrado** durante un rango de fechas determinado y considerando un número de días de previsión.


![Previsión de comrpas](/docs/images/Articulos/AsignaStock.png)

Nos permite filtar por código de proveedor, código de artículo, familia y tipo.

- Fecha Inicial y Final: Nos permite seleccionar el rango de fechas el cual se usará para calcular el stock minimo en función del consumo. Como recomendación se aconseja usar las fechas del año anterior.

- Dias previsión: Número de días a calcular en función de las fechas anteriormente introducidas, por defecto 5.

- Almacen: Almacén a calcular.

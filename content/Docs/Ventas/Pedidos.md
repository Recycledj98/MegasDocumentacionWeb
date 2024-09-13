---
title: Pedidos
weight: 1
---

## Pantalla Pedidos

Desde este apartado se podrán visualizar, dar de alta o realizar las operaciones pertinentes sobre los pedidos de preventa.

No tienen ninguna connotación a efectos prácticos sobre el almacén o programa más allá de ser una anotación guardada.

La pantalla de pedidos tiene el siguiente aspecto

![Pedidos](/docs/images/Pedido.png)

En la imagen podremos apreciar datos censurados, corresponen a los datos fiscales del cliente, nombre, dirección, código postal y población y nombre comercial.

### Cabecera pedido

En la cabecera del pedido encontramos los siguientes campos:

- **Nº de pedido**: Campo generado automáticamente. Corresponde al número de pedido.
- **Nº de cliente**: Código de cliente. Campo obligatorio, es decir, el programa nos pedirá introducir un código o seleccionar de la lista mediante el comodín asterisco.
- **Tipo de pedido**: En la imagen aparece "C", que corresponde a la serie por defecto de facturación. Es un campo automático, sólo se puede modificar si tenemos el módulo de series activo.
- **Nº Almacén**: Número de almacén del cual se realizará la retirada de género. Al ser un pedido no tiene impacto sobre el stock.
- **Fecha**: Fecha de alta del pedido.
- **Albarán**: En el caso de que pase a albarán se rellena automáticamente.
- **Rut-P**: Código de la ruta de preventa. En caso de dejar en blanco el programa nos mostrará una lista con las rutas de preventa disponibles.
- **Rut-P**: Códdigo de la ruta de distribución. En caso de dejar en blanco el programa nos pedirá lo mismo que con la ruta de preventa.
- **Nota**: Campo para observación.
- **F1-5**: Campos destinados para las funciones. F1 es obligatorio, el programa nos mostrará una pantalla con las funciones disponibles para elegir una.

### Datos Cliente

Inmediatamente a la derecha de la cabecera del pedido encontramos los datos fiscales del cliente, se rellenan automáticamente desde la ficha del cliente, aunque mediante el botón de modificar (Ctrl+M) podremos modificarlos.

### Cuerpo Pedido

Una vez rellenada la cabecera el programa nos moverá automáticamente al cuerpo del pedido donde podremos dar de alta las lineas del pedido.

- **Referencia**: Código del artículo. Podremos buscar por comodín asterisco, o introduciendo parte del código o nombre del artículo.

Los siguientes campos se rellenan de forma automática desde la ficha del artículo.

### Descripción botonera del cuerpo de pedidos

|Botón|Descripción|
|-------|---------|
|![GENERAR](/docs/images/BotoneraPedido/COMISIONES.png)| *Accede a la pestaña de comisiones del representante*|
|![GENERAR](/docs/images/BotoneraPedido/HISTORICO.png)| *Accede al histórico de PVP del artículo*|
|![GENERAR](/docs/images/BotoneraPedido/COSTE.png)| *Accede a la pestaña de coste*|
|![GENERAR](/docs/images/BotoneraPedido/TARIFAPRECIO.png)| *Nos lleva a la carga de distribucion asociada al pedido*|
|![GENERAR](/docs/images/BotoneraPedido/INSERTARLINEA.png)| *Añade una línea nueva*|
|![GENERAR](/docs/images/BotoneraPedido/GENERARENVASES.png)| *Genera los envases asociados al artículo*|
|![GENERAR](/docs/images/BotoneraPedido/IMPORTAREXCEL.png)| *Importa el pedido desde excel*|
|![GENERAR](/docs/images/BotoneraPedido/PEDIDOAUTOMATICO.png)| *Genera el pedido de compra en base al consumo del cliente.*|

### Botonera general de la pantalla de pedidos

En cuanto a la botonera explicaremos únicamente los botones diferentes de esta pantalla ya que los generales siguen mantiendo la misma funcionalidad.

|Botón|Descripción|
|-------|---------|
|![GENERAR](/docs/images/BotoneraPedido/GENERARPEDIDO.png)| *Genera un pedido de compra con las lineas de artículo introducidas*|
|![GENERAR](/docs/images/BotoneraPedido/RETENER.png)| *Retiene el pedido*|
|![GENERAR](/docs/images/BotoneraPedido/CONVERTIRALB.png)| *Convierte el pedido en albarán*|
|![GENERAR](/docs/images/BotoneraPedido/IRCARGA.png)| *Nos lleva a la carga de distribucion asociada al pedido*|
|![GENERAR](/docs/images/BotoneraPedido/CAF.png)| *Convierte el pedido a la serie F o viceversa*|
|![GENERAR](/docs/images/BotoneraPedido/CAMBIOCLIENTE.png)| *Permite cambiar datos del pedido (Véase sección anexo)*|

### Pie Pedido

![PIE](/docs/images/PIEPEDIDO.png)

Una vez rellenado el cuerpo del pedido, mediante la tecla ESC(Escape) el programa nos pedirá si deseamos generar los envases, pasada la ventana emergente nos situará automáticamente en el píe del pedido donde nos pedirá la introducción del porcentaje de descuento sobre albarán y la entrega a cuenta al igual que la forma de pago.

- **F/PAGO**: Código de la forma de pago (Ficha del cliente).
- **0.00%**: Porcentaje de descuento general aplicado al pedido (por revisar)
- **A cuenta**: Total en euros entregados al momento del pedido.
- **E**: Tipo de entrega, siendo E entrega, T tarjeta etc...
- **Neto**: Total NETO del pedido.

### Anexo

1. Cambio de datos
    ![cambio de datos](/docs/images/PEDIDOCAMBIO.PNG)

Mediante el botón de cambio de datos se nos mostrará la pantalla de cambio donde podremos modificar algunos datos relacionados con el pedido.

- **Cliente**: Modifica el código de cliente al que está asociado el pedido.
- **Documento**: Modifica el código de pedido. Tiene que ser un código que esté libre.
- **Serie**: Modifica la serie del pedido. El módulo ha de estar previamente activado.
- **Carga(-1=no)**: Asocia el pedido a una carga de preventa/distribución. Introduciendo "-1" eliminamos la asociación.
- **Factura Proveedor**: Permite asociar una factura de compra al pedido.
- **Observación**: Modifica la observación del pedido.
- **Alb. Entrega**: Por rellenar
- **Ord.Suministro**: Por rellenar
- **Num. pedido**: Por rellenar
- **Canal**: Establece el canal del pedido.
- **Servido**: Modifica el estado del pedido.
- **Num Albarán (-1=no)**: Modifica el código de albarán asociado. Introduciendo "-1" eliminamos la asociación.

2. Porcentajes de tarifa

    ![Porcentajes](/docs/images/PORCENTAJES.png)

***Requiere previa activación por parte del personal técnico de Megas.***
Muestra los márgenes por tarifa, tanto de venta como de compra y su variación de PVP.

3. Kilogramos totales

    ![Kilogramos](/docs/images/KILOS.png)
***Requiere previa activación por parte del personal técnico de Megas.***
Muestra los kilogramos totales del albarán. Previamente hemos de rellenar el peso por unidad en la ficha del artículo.

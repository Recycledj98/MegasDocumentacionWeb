---
title: Funciones Artículos
weight: 3
---


## Funciones de la pantalla Artículos

En este apartado profundizaremos acerca de las diversas opciones y funcionalidades que el sistema permite realizar referente a nuestros artículos.

### Extracto de entradas y salidas de almacen

Mediante el botón de extractos de almacen ![Btnextracto](/docs/images/botonera/BTN_ESALMA.png) nos mostrará por pantalla un filtro donde podremos especificar el rango de fechas que deseamos consultar, al igual que el tipo de movimiento y los almacenes de origen y destino.

![Extracto](/docs/images/ES_ALMA.png)
Permite a su vez realizar un filtro más exhaustivo mediante el contenido de lote o especificando un cliente.

Marcando la opción "Rentabilidad" el programa realizará un cálculo de la rentabilidad del artículo sobre las fechas indicadas y nos mostrará un informe por pantalla con los resultados.

![Extracto-Rentabilidad](/docs/images/ES_ALMA_LIS.png)

En la siguiente pantalla se muestra el extracto de movimientos de almacén sobre un artículo.
En la parte inferior izquierda se nos mostrará de forma rápida el total de unidades de entrada y salida correspondientes a la fecha marcada, al igual que el importe total de compra y venta.
También se muestra el precio medio de compra y venta.

### Envases

Podremos asignar mediante el botón de envases ![Btn_Envase](/docs/images/Botonera/BTN_ENVASE.png) los envases asociados al artículo.

Se nos mostrará por pantalla una sección en la cual podremos realizar las distintas operaciones.

![Pantalla-Envase](/docs/images/ENVASE_PANTA.png)

Podremos añadir o eliminar registros mediante los botones de Alta (**Ctrl+A**) o Baja (**Ctrl+B**).

{{< callout type="info">}}
Deberemos tener previamente el artículo envase correspondiente creado
{{< /callout>}}

* **Código Artículo**: Campo automático.
* **Código Artículo Envase (Cod.Artiuculo)**: Código de artículo correspondiente al envase a asociar.
* **Unidad**: Unidades a asociar.
* **%Descuento**: Tanto por ciento de descuento que se aplica al envase.
* **Descuento en euros por unidad**: Descuento en euros por unidad de envase.
* **Precio**: Precio de venta del envase. *Siempre sin IVA*
* **Precio Coste**: Precio de compra del envase. *Siempre sin IVA*
* **Código Promoción**: Código de promoción a aplicar si procede.
* **Observación**: Campo libre.

Una vez rellenados los campos, cada vez que cerremos un pedido/albarán de venta o compra, el sistema nos pedirá si deseamos generar los envases.
Si tenemos correctamente rellenados los campos se generarán de forma automática los envases.

### Lotes o artículos tipo Cesta

El programa nos permite crear artículos tipo lote o cesta, para ello primeramente el artículo ha de ser tipo Lote (L) y mediante el botón de lotes ![lotes](/docs/images/botonera/BTN_LOTE.png) se nos mostrará una pantalla parecia a la del punto anterior en la cual podremos asignar los artículos que incluye la cesta.

Estos artículos irán desgolsados linea por linea en el albaran/factura.

### Datos Acumulados por Mes

Tenemos la posibilidad de obtener un gráfico de consumo por meses y año del artículo mostrado en pantalla.

![PantallaGrafico](/docs/images/VentasComprasMeses.png)

### Campo MEMO

Al usar esta opción se nos mostrará una pantalla donde podremos redactar toda la información relacionada a nuestro artículo de carácter interno.

### Códigos de barra Adicionales

Al usar esta opcíon se nos mostrará una pantalla donde podremos introducir aquellos códigos adicionales de barras que nos suministra el proveedor.
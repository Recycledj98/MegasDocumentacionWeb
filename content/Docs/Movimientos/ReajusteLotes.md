---
title: Reajuste de Lotes
Weight: 5
---

Este proceso regulariza el stock del artículo con el stock de lotes.

{{< callout type="info">}}
En caso de que el artículo no tenga lotes asociados, se crea el stock a partir de las unidades disponibles en el almacen por defecto. Normalmente se utiliza cuando se da comienzo con el módulo de trazabilidad.

El código del lote creado es el código del artículo más la fecha de caducidad en formato AAAA/MM/DD

{{< /callout>}}

- **Ajustar**: Elimina lotes en negativo y añade las unidades eliminadas al stock positivo más antiguo.

- **Borrar Lotes 0**: Borra los lotes sin stock.

- **Agrupar Sueltos**: Agrupa lotes con picos en lotes más grandes y los elimina.
  - Opción usada sobretodo en artículos de pesaje
    - Se agrupan aquellos que el peso es menor que el peso marcado en la ficha del artículo. En caso de que este sea cero se usa el que se pide en la pantalla de selección.

![Seleccion](/docs/images/Ajustelotes.png)

- **Proveedor Incial - Final**: Código de proveedor Incial y Final.
- **Artículo Inicial - Final**: Código de artículo Incial y Final.
- **Familia Inicial - Final**: Código de familia Inicial y Final.
- **Tipo Artículo**: Tipo de artículo a filtar.
- **Pico Minimo**: Especifica el mínimo de pico a calcular.
- **Fecha Caducidad**: Especifica la fecha de caducidad a asignar. (Solo para lotes NUEVOS)
- **Almacén**: Especifica el almacén de origen y destino.

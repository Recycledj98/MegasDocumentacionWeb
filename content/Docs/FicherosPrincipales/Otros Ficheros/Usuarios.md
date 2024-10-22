---
title: Usuarios
weight: 3
---

## Manteinimiento de Usuarios

Permite definir los usuarios, claves de acceso y restricciones.

{{< callout type=info >}}
Por norma general se utiliza el usuario "MASTER" sin contraseña para acceder a la aplicación, pero es recomendable dar de alta todos los usuarios que tendrán acceso a la aplicación y aplicarles las restricciones necesarias en caso correspondiente.
{{< /callout >}}

![Mantenimiento De Usuarios](/docs/images/empre/Usuario.png)

Los campos de mantenimiento son los siguientes:

- Usuario: Código alfanumérico, indica el usuario y es el que se introducirá en la pantalla de acceso.

- Nombre de Usuario: Campo de texto destinado al nombre de usuario.

- Password: Contraseña de usuario, es un campo alfanumérico.

- Tipo C/F: Establece a que tipo de facturas se tiene acceso. En blanco ambas (C y F).

- Op. No permitida: Establece las opciónes que no se permiten al usuario, introduciendo el código numérico, precedido de coma si se desean introducir varios, que se encuentran en los títulos de los menús.
  - Por ejemplo: Introduciendo 42 bloqueamos el acceso a los albaranes.
- Solo Acceso TPV: Solo se permite el acceso a la aplicación desde una máquina de autoventa.

- Cobrar Parcial: (S) por defecto permite cobrar parcialmente albaranes, en caso de introducir (N) no permitirá el cobro parcial (Se deberá introducir 0 en el total neto).

- Equivale Master: Indica si el usuario tiene los mismos permisos que el usuario Master.

- Entrada Rápida: 
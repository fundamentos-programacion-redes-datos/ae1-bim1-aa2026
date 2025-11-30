# ae1-bim1-abril-agosto-2026

# Problemática

Un cine desea optimizar su sistema de facturación y análisis de ventas de entradas. Para ello, se requiere desarrollar un programa que cumpla con los siguientes requisitos:


## Entrada de datos:

* Ingresar el nombre y apellido del cliente.
* Ingresar la cantidad de entradas que desea comprar el cliente.
* Cada entrada tiene un mismo precio unitario, que también debe ser ingresado por el usuario (por ejemplo, entrada normal, entrada 3D, etc.).

## Cálculo de descuentos:

* El cine aplica descuentos según la cantidad de entradas compradas en una misma compra:
* Si se compra 1 entrada, se aplica un 10% de descuento.
* Si se compran 2 o 3 entradas, se aplica un 20% de descuento.
* Si se compran 4 o 5 entradas, se aplica un 30% de descuento.
* Si se compran 6 o más entradas, se aplica un 40% de descuento.

## Cálculo de totales:

Para cada compra registrada se debe:

* Calcular el subtotal antes del descuento (cantidad de entradas × precio unitario).
* Calcular el monto del descuento aplicado.
* Calcular el total a pagar después de aplicar el descuento.

## Registro de múltiples clientes:

* El sistema debe permitir registrar la compra de entradas de varios clientes, usando un ciclo while.
* Antes de iniciar el ciclo se debe preguntar cuántas ventas se van a registrar (número de clientes).
* Para cada cliente se realiza todo el proceso: entrada de datos, cálculo de descuentos y cálculo de totales.

## Almacenamiento de datos en estructuras de datos adecuadas:

Se deben usar arreglos unidimensionales paralelos para almacenar la información de cada venta:

* Un arreglo para registrar el nombre de cada cliente.
* Un arreglo para registrar el apellido de cada cliente.
* Un arreglo para registrar la cantidad de entradas compradas.
* Un arreglo para registrar el precio unitario de la entrada en esa venta.
* Un arreglo para registrar el total a pagar de cada cliente.

Las posiciones se corresponden:

* La posición 0 de cada arreglo representa la primera venta,
* La posición 1 representa la segunda venta, y así sucesivamente.

## Reporte Final

Al finalizar el registro y el cálculo de datos, el programa debe:

* Mostrar la información detallada de cada compra registrada (nombre, apellido, cantidad de entradas, precio unitario, total a pagar).
* Calcular y mostrar el promedio de ventas realizadas (promedio de los totales).
* Determinar y mostrar la venta de mayor monto y la venta de menor monto.

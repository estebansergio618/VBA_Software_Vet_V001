# VBA_Software_Vet_V001
Lenguaje usado: Visual Basic for Applications
En este repositorio se encontrará la primera versión de un software que funcionó desde el 01-Feb-2022 hasta el 15-Jun-2022 en una clinica veterinaria.

Problematicas:
- El diseño de la BD es poca ventajosa y limitada.
- Los analisis sobre los datos se vuelve tedioso pues debe escribirse multiples algoritmos para reestructurar la tabla.
- Los algoritmos escritos con el crecimiento de la BD serán lentos pues tiene O(n^2).
- Solo soporta por pedido registrado 14 productos como máximo.
- Solo soporta 11 métodos de pago distintos.
- No maneja la deuda que pueda tener un cliente.
- No controla inventario de productos.

Ventajas:
- Guarda un historial de las atenciones diarias por cliente.
- Guarda los egresos y motivo de egreso diariamente de la empresa.
- Mantiene el flujo diario de la caja chica de la empresa con precisión.
- Las problematicas mencionadas se convierten en ventaja en veterinarias con poco volumen de clientes.

Base de datos utilizada: Microsoft Acces
Interfaz utilizada: Formularios de Microsoft Excel

## Interfaz principal
![Cuaderno](https://user-images.githubusercontent.com/67118105/175780364-5e24c87e-caa2-431b-a29a-f0fc928df286.jpg)

## Metodos de pago

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
- Permite distintos métodos de pago a un mismo cliente.

Base de datos utilizada: Microsoft Acces (T-SQL)  
Interfaz utilizada: Formularios de Microsoft Excel (VBA)  

Se escondió apellidos y números de teléfono de los clientes como el nombre de la empresa.  

## Interfaz principal
![Cuaderno_1](https://user-images.githubusercontent.com/67118105/175780471-e1f3de32-a5a1-45d5-850a-80ba73b81d36.jpg)

## Metodos de pago
![WhatsApp Image 2022-06-25 at 10 24 49 AM (1)](https://user-images.githubusercontent.com/67118105/175780501-1e4c6fb2-30de-4903-bbbb-63fe0749b61c.jpeg)

## Busqueda inteligente de clientes e historiales clínicos
![buscadorInteligente](https://user-images.githubusercontent.com/67118105/175780506-8114f295-b9de-46d8-b40e-06a4a481c8b7.jpg)

Diseño de interfaz gráfica, Formularios, Modulos y Diseño de relaciones en la BD los cree desde cero, si les sirve esta versión coloquen mi nombre o github así las personas seguirán viendo mi trabajo :)  

La versión 2 incluye:
- **Arqueos de caja** (Link para que sepan de que se trata: https://www.gestiopolis.com/que-es-arqueo-de-caja/)  
- Soluciona los problemas mencionados y se perfila a ser la última versión

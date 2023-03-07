## Descripcion de los datos
Este conjunto de datos contiene información transaccional de un grupo de 2,500 clientes los cuales son compradores frecuentes en una tienda retail. La historia de los datos es de 2 años.

## Objetivo del análisis
Describir los clientes de la tienda en base a su información transaccional

## Tareas por hacer
1. Describir a los clientes según su frecuencia de compra.
2. Describir a los clientes según el gasto realizado.
3. Describir a los clientes según las variables demográficas.
4. ¿Qué categorías de productos generan aproximadamente el 80% de las ventas?
5. ¿Cuántos clientes generan aproximadamente el 80% de las ventas?
6. ¿Cuál es el periodo o rango semanal donde se registra mayor actividad(transacciones) por parte de los clientes?
7. Cualquier otro insights que se haya descubierto y sea interesante presentar.
8. Sugerencia de posibles desarrollos que se puedan realizar a partir de los datos analizados y de los resultados obtenidos.

## Indicaciones
1. Entregar un notebook(ipynb) con los resultados obtenidos (gráficas, tablas, etc.). También incluir todo el código desarrollado.
2. Sustentar los resultados lo más detallado posible.
3. Explicación detallada de los diferentes descubrimientos que se han encontrado.

**Nota**: 
1. Es preferible que el notebook final esté organizado como si estuvieras contando una historia, es decir, que siga un hilo que se pueda entender a medida que se avance en la lectura.

## Descripción de las variables
1. transaction_data.csv
    * household_key: Identificación única del cliente.
    * BASKET_ID: Identificación única de la  transacción.
    * PRODUCT_ID: Identificación única del producto.
    * QUANTITY: Cantidad de productos comprados.
    * SALES_VALUE: Monto en dolares de la compra.
    * STORE_ID: Identificación única de cada tienda.
    * WEEK_NO: Semana en que se realizó la transacción (1 - 102)
2. product.csv
    * PRODUCT_ID: Identificación única del producto.
    * MANUFACTURER: Código del proveedor.
    * DEPARTMENT: Departamento al cual pertenece un producto .
    * BRAND: Indica si la marca del producto es internacional o nacional.
    * COMMODITY_DESC:Categoría al que pertenece el producto.
3. hh_demographic.csv
    * AGE_DESC: Rango de edad estimado.
    * MARITAL_STATUS_CODE: Estado marital del cliente.
    * INCOME_DESC: Ingresos del cliente.
    * household_key: ID por cada cliente.
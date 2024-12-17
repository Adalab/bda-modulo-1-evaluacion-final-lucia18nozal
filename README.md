# bda-modulo-1-evaluacion-final-lucia18nozal

## Primer ejercicio de evaluación
Este proyecto es el ejercicio individual de evaluación del módulo 1 del temario de este bootcamp.

El ejercicio está planteado en dos partes: 
- La primera parte es la clase TiendaOnline que engloba diferentes funcionalidades; se pueden agregar productos, ver el inventario, buscar productos específicos, actualizar su stock, eliminar productos, y calcular el valor total del inventario. Además, registra las ventas totales realizadas. 
- La segunda parte es la función menu, desde donde te permite interactuar con la clase y decidir qué quieres hacer a través de un usuario.

### Funcionalidades
-Agregar productos: Permite agregar nuevos productos al inventario o actualizar la cantidad de un producto si ya existe.
-Ver inventario: Muestra todos los productos en el inventario con su nombre, precio y cantidad disponible.
-Buscar productos: Permite buscar un producto específico en el inventario por su nombre.
-Actualizar stock: Permite actualizar la cantidad de un producto específico (puedes sumar o restar unidades).
-Eliminar productos: Permite eliminar un producto del inventario.
-Calcular valor del inventario: Calcula el valor total del inventario sumando el valor de todos los productos (precio x cantidad).

### Atributos
- inventario (list): Almacena los productos en la tienda. Cada producto es representado por un diccionario con las claves:
    · nombre: Nombre del producto (string).
    · precio: Precio del producto (float).
    · cantidad: Cantidad disponible del producto (int).
- ventas_totales (float): Registra el total de las ventas realizadas.

### Métodos
- agregar_producto(self, nombre, precio, cantidad): Este método agrega un producto al inventario o actualiza su cantidad si ya existe. Recibe tres parámetros: nombre, precio y cantidad.
- ver_inventario(self): Muestra todos los productos en el inventario con su nombre, precio y cantidad disponible.
- buscar_producto(self, nombre): Busca un producto en el inventario por nombre y muestra sus detalles si se encuentra.
- actualizar_stock(self, nombre, cantidad): Actualiza la cantidad de un producto en el inventario. Puede ser usado tanto para agregar como para restar unidades.
- eliminar_producto(self, nombre): Elimina un producto del inventario por su nombre.
- calcular_valor_inventario(self): Calcula el valor total del inventario, sumando el valor de todos los productos (precio * cantidad).

### Uso
El proyecto incluye un menú interactivo que permite al usuario seleccionar las acciones que desea realizar, que son las siguientes:
- Agregar un producto
- Ver el inventario
- Buscar un producto
- Actualizar el stock
- Eliminar un producto
- Calcular el valor total del inventario
- Salir del programa

## Autor:
- Lucía Nozal Benito.

## Tecnologías Usadas:
- Python.
- GitHub.


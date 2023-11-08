### Implementación de Tabla Hash para control de stock

**Objetivo:** En este trabajo, debe implementar un programa que ayude a llevar el control de stock de un supermercado.

**Descripción del problema:** Implemente el programa para el control de stock de un supermercado usando una Tabla Hash. La misma se utilizará para almacenar información sobre los productos disponibles en el supermercado y la cantidad de unidades disponibles. Se debe permitir la inserción, eliminación y búsqueda de productos. La Tabla Hash debe resolver sus colisiones con encadenamiento. Además se deben implementar algunas funciones de estadísticas de uso de la tabla.

Tenga en cuenta que el supermercado vende normalmente más de $40000$ productos. Cada producto tiene un código alfanumérico de $10$ caracteres, por ejemplo "AAN1235465", "123ABCDE12".

### Requerimientos
- Escriba una función apropiada para transformar las claves del problema a valores numéricos.
- Implemente una tabla hash para almacenar los productos disponibles. Debera:

  - incluir el método constructor.
  - utilizar una función hash apropiada - puede elegir el método del resto, el método de la multiplicación o bien proponer otro que haya investigado.
  - debe permitir la inserción, eliminación y búsqueda de productos en la tabla hash.
  - la tabla hash debe soportar resolución de colisiones mediante encadamiento, puede utilizar para ello una lista enlazada o una lista de Python, a su preferencia.
  
- Además debe implementar los siguientes métodos:

  - `__len__` Este método sobrecarga la función incluida `len`. Debe devolver la cantidad de elementos insertados en la tabla.
  - `_load_factor`: Este método debe calcular y devolver el factor de carga de la tabla hash.
  - `_longest_list`: Este método debe calcular y devolver el tamaño de la lista más larga.

# Proyecto-prog2

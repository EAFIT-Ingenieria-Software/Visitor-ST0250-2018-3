# Visitor-ST0250-2018-2
### *Tienda que se repite*
# Visitor Pattern
### Nombre de Integrantes
-Sebastian Bustamante
-Jhon Fernado Oquendo
-Juan Pablo Ramirez

### Explicación de la Problemática
Considere un escenario en el que necesitamos realizar cierto tipo de operaciones sin modificar las clases reales. Por ejemplo, al crear un pedido, queremos realizar un conjunto de operaciones en todos los artículos (por ejemplo, aplicar descuentos, calcular impuestos, etc.). Podemos agregar los métodos getTax () y getDiscount () a las clases reales, pero esto contamina la clase y requiere un cambio en la firma de la clase cada vez que se necesita agregar o eliminar una operación. Podemos evitar estos problemas utilizando la función de doble delegación del patrón de visitante.
## Modelo de Clases
![enter image description here](https://lh3.googleusercontent.com/JwfC5XjOC0L4UJlrAIvkfpjGNrutrqJOoKcidH11nKND6qzXGxcxlfzZ3xYzI4hzFDJSKbcsk66O)
![enter image description here](https://lh3.googleusercontent.com/TH5tKsS9gChRKfLbr4cgQYO8teHNkn70p1QWHs1cAz1iwgkTTxhhfB19lQWHzARRdo-tWDhpjFhV)

### Lenguaje Java
### Ejecución del Código
Ejecutar el main en la clase VisitorClient

### Referencias Bibliográficas
App Desing Patterns(Gof)
wikipedia.org

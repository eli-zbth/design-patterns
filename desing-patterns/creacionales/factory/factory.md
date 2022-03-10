# Factory method

Proporciona una interfaz para la creación de objetos en una superclase, mientras que permite a las subclases alterar el tipo de objetos que se crearán

## Ejemplo de problema
Se crea una aplicación de gestión logística, cuya primera versión es capaz de manejar el transporte en camión, por lo que la mayor parte del código se encuentra dentro de la clase Camión.

Al cabo de un tiempo, la aplicación se vuelve bastante popular y se deben integrar otros medios de transporte, pero todo el código está acoplado.
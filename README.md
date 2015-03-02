# ejercicio 2 - 
Interfaces.
Considera el siguiente código fuente Java:
package edu.upc.eetac.dsa.exercises.java.lang;
public class AppInheritance {
public static void main(String[] args) {
    Shape[] shapes = new Shape[2];
    shapes[0] = new Circle(2.5);
    shapes[1] = new Rectangle(3, 5);
    for (Shape shape : shapes)
System.out.println(shape + " with area = " + shape.area());
	}
}

Completa el código para que la salida por consola sea:
I'm a circle with area = 0.0
I'm a rectangle with area = 15.0




## Installation
Ejecutar simplemente.

El resultado que yo tengo está corregido, es decir, el áera del círculo no me da 0.0 como en la respuesta que se da, ya que he creido que es un error, y lo he corregido.

Si no era un error solo se tendría que cambiar una línea de código this.radius=radius dentro del constructor círculo.
# TareaVP
1. Identifique las clases y lo que éstas representan. Luego, establezca una descripción textual breve del contexto problema.

Clase Calculadora: Es la representacion simple de una calculadora que realiza 2 operaciones basicas, sumar y multiplicar.
- Atributos: tiene como atributos a n1 y n2 que son numeros enteros
- Metodos: sumar() para sumar n1 y n2, multiplicar() para multiplicar n1 y n2, y setN1(int num1) y setN2(int num2) para establecer los valores de n1 y n2, respectivamente.

Clase CarroCompra: Representa a un carro de compras con una lista predefinida de productos, cada uno con una cantidad y un precio. Permite calcular el total de la compra y mostrarlo.
- Atributos:productos Representa una matriz de productos con dos filas y cinco columnas. La primera fila contiene cantidades y la segunda fila contiene precios.
- Metodos: calcularTotal() para calcular el total de la compra, subTotal(int cant, int precio) para calcular el subtotal de cada producto utilizando la clase Calculadora, y mostrarTotal() para imprimir el total de la compra.

2. Analice los atributos y métodos de cada clase, luego, identifique las relaciones existentes entre las clases identificadas y establezca una descripción textual breve del contexto problema..
- En el ejercicio planteado vemos que en el metodo subTotal de la clase CarroCompra se utiliza el metodo multiplicar de la clase Calculadora.

3. De lo anterior, establezca una representación detallada del código fuente, usando un diagrama de clases UML y la herramienta de modelado Visual Paradigm.
![Screenshot 2023-10-11 182332](https://github.com/LeandroEsteban/TareaVP/assets/127903058/867edd22-528c-4921-a5e4-723915c19246)

4. Genere un código fuente Java a partir de su modelo de clases.
- Codigo generado de la clase Calculadora
![Screenshot 2023-10-11 182422](https://github.com/LeandroEsteban/TareaVP/assets/127903058/79805c5b-8e50-44f3-a477-0edee9f24e53)
- Codigo generado de la clase CarroCompra
![Screenshot 2023-10-11 182442](https://github.com/LeandroEsteban/TareaVP/assets/127903058/464b0336-5c22-4177-8f3b-8e507b8f6118)

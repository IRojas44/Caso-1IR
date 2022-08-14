# Caso-1IR
# Manera de Suministrar los datos
Al iniciar el programa se le solicitará que ingrese la cantidad de regiones que desee, inmediatamente se le solicitará el número identificador de la región y su color,
posteriormente, se le solicitará que ingrese la cantidad de regiones adyacentes que tiene dicha región, luego de digitar cuantas regiones desea se le solicitará que 
ingrese el número de dicha región.

# Estructura de datos para la solución del caso
Para la solución se utilizó un struct con tres variables en su estructura: id(entero identificador de la región), color(entero que se relaciona con un color según corresponda)
y adyacentes(arreglo de enteros que contiene los adyacentes de la región).
Para solucionar el caso se utiliza la funcion verificarTeorema() que recibe a las regiones como parámetro. La función consiste en ciclos for, condicionales y una variable de tipo
booleano inicializada en true, esto verifica que el color de la región x al momento del ciclo y sus adyacentes no tengan el mismo color, de esto ser contrario la variable 
cumple cambiará a false.
Por último se evalúa la variable cumple y se imprime según corresponda.

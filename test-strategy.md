Errores de sintaxis
1) Se corrigieron los errores de "addeventListener" que aparecía en varias líneas. La solucion fue colocar "Event" con mayúscula.
2) línea 79 entrabá en error debido a que en línea 49 al declarar el "querySelector" no se definió si "lowOrHi" es una clase o un ID, como en este caso es clase con la que se trabaja se corrigió el error colocando un punto antes de la palabra de la siguiente forma '.lowOrHi'.

Errores logicos
1) línea 46 debe de ser remplazado por 10 intentos porque estaba en 5 intentos.
2) el número que se almacena en la variable randomNumber es decimal y no entero por lo que se procede a usar la función "parseInt()" para poder convertirlo a entero.
3) Se cambian de posición los mensajes que se le muestran al usuario cuando pierde o gana, esto porque se encontraban en condiciones donde no debían estar.
4) Se cambia de color en línea 71 por el verde para que se muestre como se solicita.
5) línea 74 y 75 se deben de integrar dentro de las condiciones que evalúan si el número es menor o mayor.
6) En la línea 58 agregamos parseInt() para capturar el valor en entero y no como Sting.
7) Para que el número sea aleatorio hasta el 100 debemos de multiplicar, en la línea 44, por 100.
8) Se agrega otra condición que evalúe si el número es un entero o decimal y se muestre la alerta.
9) Se agrega otra condición para que el valor que no es entero no se guarde.

Nota:se agregaron comentarios en el código para que puedan visualizar donde fue que se agregó código para completar el programa.
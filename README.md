# Proyecto-Final

Funcionamiento 
 Ingreso de datos: El sistema recibe la edad del asegurado, el estado civil (casado o no), la edad del cónyuge (si aplica) y el número de hijos.
 Verificación de edad: Si la edad del asegurado es menor a 18, el sistema devuelve un mensaje indicando que no se puede realizar la cotización.
 Cálculo de recargos por edad: Se calcula un porcentaje adicional sobre el precio base según los rangos de edad establecidos (10%, 20% o 30%).
Cálculo de recargos por cónyuge: Si el asegurado está casado, se verifica si el cónyuge es mayor de edad y se calcula el recargo correspondiente.
Cálculo de recargos por hijos: Por cada hijo, se agrega un recargo del 20% sobre el precio base.
 Cálculo del precio total: El precio total es la suma del precio base más los recargos por edad del asegurado, del cónyuge y los hijos.
Resultado: El sistema devuelve la cotización final detallando los recargos.

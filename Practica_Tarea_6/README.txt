TAREA 6
reloj

Modificar el contador anterior para construir un reloj que se
muestre en el LCD en formato hh:mm:ss.
Utilizar la salida clock_1hz del divisor de reloj.
SW2 a SW17 se utilizarán el bloques de 4 para la precarga
de horas y minutos. Los segundos no tienen precarga
(empiezan en 00).
El contador debe implementarse encadenando contadores
decimales de distintos módulos. Por ejemplo, unidades de
segundo será un contador módulo 10, mientras que
decenas de segundo será un contador módulo 6.
Debe modificarse LCD_Display para que muestre 6 dígitos
hexadecimales (en lugar de 2).
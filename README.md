# CotizadorAutomatico
## Genera cotizaciones automáticas

El programa consiste en solicitar los datos al usuario:
1. nombre
2. edad
3. es casado(a)?
4. tiene hijos?
5. tiene propiedades?
6. salario?

- Se solicita la edad del cónyuge **sólo si es casado**
- Se solicita el número de hijos **sólo si tiene hijos**
- Se solicita el número de propiedades **sólo si tiene propiedades**

Se hará un recargo en porcentaje del precio base de la cotización, por los siguientes conceptos:
edad 
edad del cónyuge
No. de hijos
No. de propiedades

Se hará un recargo en porcentaje del monto del salario.

**Se suman todos los recargos y se agregan al precio base de la cotización para obtener el precio
final que pagará el cliente/asegurado.**

Problemas que pueden presentarse:
- Si el usuario en lugar de digitar números en edad, No. de hijos, No. de propiedades y salario, ingresa letras.
- Se deben convertir a número los valores devueltos por la función prompt, ya que lo que devuelve esta función es una cadena.

Se podría mejorar la salida del programa en cuanto a detallar el valor de cada recargo, para darle claridad a la información.











**Variables and Names**

Se puede imprimir cosas con print y puedes hacer matemáticas.

El siguiente paso es aprender sobre las **variables**.

**Variable**: Es un nombre para algo, similar a mi nombre "Olivia" es un nombre para
"El humano que escribió este repo".

Los programadores usan estos nombres de variables para hacer que su código. Deben usar buenos nombres para las cosas o nos perderíamos cuando intentaramos leer el código nuevamente.

**=** `(es igual a)` y su propósito es dar datos  (números, cadenas, etc.) o nombres (cars, cars_driven, pasajeros, etc).

Debe agregar espacio alrededor de operadores como este para que sea más fácil de leer.

```
x = 100
```

Recuerda que `_` es un carácter que se utiliza en vez de dejar espacios.

```
PCR_Batch = PCR1
```

**Recuerda los trucos que te han enseñado hasta ahora para encontrar diferencias y enfocarte en los detalles:**

1. Escriba un comentario sobre cada línea explicando lo que hace en inglés.
2. Lea su archivo .py al revés (De abajo hacia arriba).
3. Lea su archivo .py en voz alta, incluso los caracteres.

Ex.4.py:

```
cars = 100
space_in_a_car = 4
drivers = 30
passengers = 90
cars_not_driven = cars - drivers
cars_driven = drivers
carpool_capacity = cars_driven * space_in_a_car
average_passengers_per_car = passengers / cars_driven

print("There are", cars, "cars available.")
print("There are only", drivers, "drivers available.")
print("There will be", cars_not_driven, "empty cars today.")
print("We can transport", carpool_capacity, "people today.")
print("We have", passengers, "to carpool today.")
print("We need to put about", average_passengers_per_car, "in each car.")
```

**What You Should See:**

```
$ python3 ex4.py
There are 100 cars available.
There are only 30 drivers available.
There will be 70 empty cars today.
We can transport 120.0 people today.
We have 90 to carpool today.
We need to put about 3.0 in each car.
```

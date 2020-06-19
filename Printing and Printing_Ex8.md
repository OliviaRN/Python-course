
# Printing, Printing

Ahora veremos cómo hacer un formateo más complicado de una cadena.

En este ejercicio estoy usando el  **llamado de una función"** para convertir la variable del formateador en otras cadenas. Cuando me veas escribir **formatter.format (...)** le digo a python que haga lo siguiente:

1. Toma la cadena de formato definida en línea 1.

2. Llama el formato de esa función, que es similar a decirle que haga un comando de línea de comando llamado formato.

3. Pasar los 4 argumentos de `formatter`, que coinciden con los cuatro {} en la variable del formateador. Esto es como pasar argumentos al formato del comando de línea de comando.

4. El resultado de llamar a la información del formato es una nueva cadena de caracteres que tiene las `{}` reemplazadas por las cuatro variables como 1,2,3,4 o TRUE,FALSE, TRUE,FALSE y esto es lo que `print` ahora está imprimiendo.


#Se define la variable `formatter` con 4 argumentos

```
formatter = "{} {} {} {}"
```

#Imprime la variable formatter con el  formato ```**(.format syntax)**`` 1,2,3,4 para cada uno de los argumentos.

```
print(formatter.format(1, 2, 3, 4))
```

#Imprime la variable formatter con el  formato (.format syntax)  "one", "two", "three", "four"

```
print(formatter.format("one", "two", "three", "four"))
```

#Imprime la variable formatter con el  formato (.format syntax) True, False, False, True

```
print(formatter.format(True, False, False, True))
```

#Imprime la variable formatter con el  formato (.format syntax) formatter, formatter, formatter, formatter. En total 16 {} por cómo está definida la variable.

```
print(formatter.format(formatter, formatter, formatter, formatter))
```

#Imprime la variable formatter con el  formato (.format syntax) "Try your", "Own text here", "Maybe a poem", "Or a song about fear"

```
print(formatter.format(
    "Try your",
    "Own text here",
    "Maybe a poem",
    "Or a song about fear"
))
```

## Me saldría lo mismo si lo  escribiera así veamos :)

```
print(formatter.format("Try your", "Own text here", "Maybe a poem", "Or a song about fear"))
```

## Print one part of one of my favorites songs

```
print(formatter.format(
    "We could steal time",
     "Just for one day",
     "We can be heroes",
     "For ever and ever",
     "What would you say"
     ))
```

##NOTA: 

**¿Por qué tengo que ingresar citas alrededor de "uno" pero no alrededor de Verdadero o Falso?**

Python reconoce True y False como palabras clave que representan el concepto de `verdadero`y `falso`. Si se pone comillas alrededor de ellas, se convierten en cadenas y NO funcionarán.


**LO QUE SE VE EN LA TERMINAL:**

$ python3 ex8.py

1234

one two three four

True False False True

{} {} {} {} {} {} {} {} {} {} {} {} {} {} {} {}

Try your Own text here Maybe a poem Or a song about fear

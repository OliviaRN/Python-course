
# Printing, Printing

Ahora veremos cómo hacer un formateo más complicado de una cadena.

En este ejercicio estoy usando algo llamado **"función"** para convertir la variable del formateador en otras cadenas. Cuando me veas escribir **formatter.format (...)** le digo a python que haga lo siguiente:

1. Tome la cadena de formato definida en línea 1.

2. Llame a su función de formato, que es similar a decirle que haga un comando de línea de comando llamado formato.

3. Pasar por los argumentos del formulario, que coinciden con los cuatro {} en la variable del formateador. Esto es como pasar argumentos al formato del comando de línea de comando.

4. El resultado de llamar a la información del formato es una cadena de caracteres que tiene {} reemplazada por las cuatro variables. Esto es lo que la impresión ahora está imprimiendo.


#Se define la variable formatter con 4 argumentos

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

#### Print one part of one of my favorites songs

```
print(formatter.format(
    "We could steal time",
     "Just for one day",
     "We can be heroes",
     "For ever and ever",
     "What would you say"
     ))
```

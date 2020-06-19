# More Printing


Imprime Mary had a little lamb

```
print("Mary had a little lamb.")
```

*Se hace un string y se utiliza la sintaxis `.format()` para este string.*

Imprimirá su lana es blanca como la nieve. {} las usamos para referirnos y llenar el espacion con snow. Aquí *snow* es un string NO una variable

```
print("Its fleece was white as {}.".format('snow'))
print("And everywhere that Mary went.")
print("." * 10) # what'd that do?  ##Coloca 10 puntos. PARA HACERLO-Realiza la multiplicación de 1 punto por 10
```

*DE LAS PALABRAS CHEESE BURGER Se definen cada una de las letras como variables end1= C, end2=H, ....end12 = r*

```
end1 = "C"
end2 = "h"
end3 = "e"
end4 = "e"
end5 = "s"
end6 = "e"
end7 = "B"
end8 = "u"
end9 = "r"
end10 = "g"
end11 = "e"
end12 = "r"
```

### watch `end = ' ' ` at the end. try removing it to see what happens

## Con el `end=' '` **NO** **se hace un salto de línea y el sistema operativo coloca en la misma línea el prompt**

```
print(end1 + end2 + end3 + end4 + end5 + end6, end=' ')
```

### Sin el end=' ' SI se imprime un salto de línea y el prompt me aparece en otra línea.

```
print(end7 + end8 + end9 + end10 + end11 + end12)
```

## *NOTA:*


print(end1 + end2 + end3 + end4 + end5 + end6) ##Quitando el end = ' '  ### Este me imprimió Cheese


###Errores. NO COPIAR BIEN. TUVE TYPOS , NO CIERRO COMILLAS y parentesis, 

**LO QUE SE VE EN LA TERMINAL**

```
$ python3 ex7.py
Mary had a little lamb.
Its fleece was white as snow.
And everywhere that Mary went.
..........
Cheese Burger
```

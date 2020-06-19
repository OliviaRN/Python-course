# Printing, Printing, Printing

Veremos øtra manera de imprimir un texto es empleando triples comillas `"""`, de esta manera es más fácil de entender nuestro código.

Las **comillas triples** de Python permiten que las cadenas abarquen varias líneas
Las **comillas triples** no son comentarios. Son literales de cadena que abarcan varias líneas e incluyen esos saltos de línea en la cadena resultante.

# Ex9.py

# Here's some new strange stuff, remember type it exactly.

#Definimos las variables days y months
```
days = "Mon Tue Wed Thu Fri Sat Sun"
months = "\nJan\nFeb\nMar\nApr\nMay\nJun\nJul\nAug"  ##La (\n) pone cada mes en una nueva línea
```

#Imprimimos las variables anteponiendo una como para separar cada día y cada mes
```
print("Here are the days: ", days)
print("Here are the months: ", months)
```

#øtra manera de imprimir un texto es empleando """ , de esta manera es más fácil de entender nuestro código.

```
print(" " "
There's something going on here.
With the three double-quotes.
We'll be able to type as much as we like.
Even 4 lines if we want, or5, or6.
" " )
```

###Otra opción es asi, pero es más difícil de leer porque hace la cadena muuuuyyy larga.

```
print("\nThere's something going on here.\nWith the three double-quotes.\nWe'll be able to type as much as we like.\nEven 4 lines if we want, or5, or6.")
```

# NOTA:

**¿Por qué sale un error cuando ingreso espacios entre las dos comillas dobles?**

Tienes que escribirlos como `"""` y no `" " "`, que significa sin espacios entre cada uno.

**¿Qué pasa si quiero comenzar los meses en una nueva línea?**

Simplemente comienza la cadena con `\n` así dará un salto de línea. 

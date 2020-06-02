
# *Strings and Text*


Una **cadena** suele ser un poco de texto que se desea mostrar a alguien o "exportar" fuera del programa que está escribiendo. 

Python sabe que quieres que algo sea una cadena cuando pones "(comillas dobles) o '(comillas simples) alrededor del texto.

Las cadenas pueden contener cualquier cantidad de variables que estén en su script Python.

Recuerda que una **variable** es cualquier línea de código donde establece un nombre = (igual) a un valor. 

En el código para este ejercicio, ```types_of_people = 10``` crea una variable llamada types_of_people y la establece = (igual) a 10.
Puede poner eso en cualquier cadena con {types_of_people}. 

También ve que tengo que usar un tipo especial de cadena para "formatear"; se llama **"f-string"** y tiene este aspecto:

### **f”cuaquier cosa aquí {variable}”**

Python también tiene otro tipo de formato usando la sintaxis **.format ()** que se usa a veces cuando se quiere aplicar un
formato a una cadena ya creada, como en un bucle (Loop). 

**Ejemplo6 (ex6.py)**

#Definimos la variable types_of people y le asignamos un  valor

```types_of_people = 10```

#Se realiza un string y se usa la funcion f de format. 

```x = f"There are {types_of_people} types of people."```

#Definir las variables binary y do_not

```
binary = "binary"
do_not = "don't"
```

#Se realiza un segundo string con las variables que se definieron

```
y = f"Those who know {binary} and those who {do_not}."
```

#Se imprimirá en la terminal lo que indican los strings x y y

```
print(x)
print(y)
```

#Se coloca un tercer string 

```
print(f"I said: {x}")
print(f"I also said: '{y}'")
```

#Se define la variable hilarious como Falsa

```
hilarious = False
```

#Se define la variable Joke_evaluation y realiza un cuarto string y se imprime en la terminal las variables definidas . El .format sustituye a la f

```
NOTA: No está permitido que las llaves estén fuera de las comillas y estas se utilizan para rellenar algo en este caso lo de hilarious.

joke_evaluation = "Isn't that joke so funny?! {}"  

print(joke_evaluation.format(hilarious))
```

#Se definieron las variables w + e

```
w = "This is the left side of..."
e = "a string with a right side."
```

#Se realiza un 5to string y se suman, esto hace que obtengamos un string más largo 

```
print(w + e)
```

## NOTA: En todas las que tenemos las variables definidas hay strings dentro de strings

## Puedo utilizar lo de comillas dobres o simples,  es un poco más de estilo del programador.

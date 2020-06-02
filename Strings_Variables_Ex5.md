# **More variables and Printing **


**Strings (Cadenas)**

Cada vez que pones "(comillas dobles) " alrededor de un texto, has estado haciendo una **cadena**

Una **cadena** es cómo haces algo que tu programa podría darle a un humano. Imprime cadenas, guarda cadenas en archivos, envía cadenas a servidores web y muchas otras cosas.

También se pueden incrustar variables dentro de una cadena utilizando una secuencia especial **{}** y luego colocando la variable que desee dentro de los caracteres {}.

También debo comenzar la cadena con la letra f para "formato", como en **f "Hola {somevar}"**.

Esta pequeña f antes de "(comillas dobles) y los caracteres {} le dicen a Python:

*"Hey, esta cadena necesita ser formateada. Ponga estas variables allí "*.

Ejemplo **ex5.py** :

#Defino las variables y luego las imprimo:

my_name = 'Zed A. Shaw'

my_age = 35

my_height = 74

my_weight = 90

print(f"Let's talk about {my_name}.")

print(f"He's {my_height} inches tall.")

print(f"He's {my_weight} pounds.")

print(f"His teeth are usually {my_teeth} depending on the coffee.")

this line is tricky, try to get it exactly right

total = my_name + my_height + my_weight

print(f"If I add {my_age}, {my_height} and {my_weight} I get total")

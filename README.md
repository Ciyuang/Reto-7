# RETO 7 🤨

## Ejercicio 1
- Imprimir un listado con los números del 1 al 100 cada uno con su respectivo cuadrado.
```python
# Recorre los números del 1 al 100 (inclusive)
for i in range(1,101):
    # Calcula el cuadrado de cada número
    cuadrado = i**2
    # Imprime el número y su cuadrado
    print(i, cuadrado)
```

## Ejercicio 2
- Imprimir un listado con los números impares desde 1 hasta 999 y seguidamente otro listado con los números pares desde 2 hasta 1000.
```python
# Recorre los números del 1 al 999
for i in range(1,1000):
    # Condición para verificar si el número es impar
    if i%2 != 0:
        # Imprime el número impar y el siguiente número que es par
        print(f"impares {i}, pares {i+1}")
```

## Ejercicio 3
- Imprimir los números pares en forma descendente hasta 2 que son menores o iguales a un número natural n ≥ 2 dado
```python
# Solicita al usuario un número mayor o igual que 2
n = int(input("Ingrese un numero mayor o igual que 2: "))
print("↓ Pares desde ese numero hasta dos ↓")

# Recorre hacia atrás desde el número ingresado hasta 2, de dos en dos
for i in range(n, 1, -2):
    # Imprime solo los números pares descendentes
    print(i)
```

## Ejercicio 4
- Imprimir los números de 1 hasta un número natural n dado, cada uno con su respectivo factorial.
```python
#variable de entrada por el usuario
n = int(input("Ingrese un numero natural: "))
#variable para realizar el incremento
factorial=1
#bucle for en un rando de 1 a n+1 para incluir el valor del usuario
for i in range(1,n+1):
    factorial= factorial*i
    #impresion 
    print(f"{i},factorial: {factorial}")
```

## Ejercicio 5
- Calcular el valor de 2 elevado a la potencia n usando ciclos for.
```python
# Solicita al usuario un exponente natural para la base 2
n = int(input("Ingrese un exponente (natural) para 2: "))

# Verifica que el exponente sea natural (no negativo)
if n < 0:
    print("el exponente no es natural")
else:
    # Calcula 2 elevado al exponente ingresado
    for i in range(n):
        exp = 2**n
        # Imprime el resultado de 2^n
        print(f"2 elevado a la {n} es: {exp}")
        break  # Sale del ciclo después de la primera iteración
```

## Ejercicio 6
- Leer un número natural n, leer otro dato de tipo real x y calcular x^n usando ciclos for. Disclaimer: Trate de no utilizar el operador de potencia (**).
```python
import math

# Solicita al usuario un número natural
n = int(input("Ingrese un numero natural: "))

# Solicita un número real
x = int(input("Ingrese un numero real: "))

# Recorre solo una vez (es un bucle innecesario aquí, pero se mantiene como está)
for i in range(n, n+1):
    # Verifica que el número natural sea mayor que 0
    if n > 0:
        # Calcula x elevado a la x
        potencia = x**x
        # Imprime el resultado
        print(f"{potencia}")
```

# Autor 🤖
- [Juan Carlos Polania Bolivar](https://github.com/Ciyuang)

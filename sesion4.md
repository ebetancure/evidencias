<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4

#### Calculadora Básica: Crea una función llamada calculadora que tome tres argumentos: dos números y un operador (+, -, *, /). La función debe realizar la operación indicada en los dos números y devolver el resultado.

```python:
def calculadora(num1, num2, op):
    if (op == '+'):
        return (num1 + num2)
    elif (op == '-'):
        return (num1 - num2)
    elif (op == '*'):
        return (num1 * num2)
    elif (op == '/'):
        return (num1 / num2)
    
resultado = calculadora(5, 3, '+')  # Debe devolver 8
print('El resultado es: ',resultado )
    
```
#### Conteo de Vocales: Crea una función llamada contar_vocales que tome una cadena como argumento y devuelva el número de vocales (a, e, i, o, u) que contiene la cadena.

```python:
def contar_vocales(frase):
    vocales = "aeiouAEIOU"
    contador_vocales=0
    for caracter in frase:
        if caracter in vocales:
            contador_vocales=contador_vocales+1
    return contador_vocales

num_vocales = contar_vocales("Hola, mundo!")  # Debe devolver 4
print('El numero de vocales son', num_vocales)
```

#### Primo o No Primo: Escribe una función llamada es_primo que tome un número entero positivo como argumento y determine si es un número primo (es decir, solo es divisible por 1 y por sí mismo). La función debe devolver True si es primo y False si no lo es.
```python:
def es_primo(num):
    if num <= 1:
        return False
    elif (num % 2 ==0):
        return False
    if num == 2:
        return True
    for divisor in range(3,num):
        if num % divisor == 0:
            return False
    return True

resultado = es_primo(17)  # Debe devolver True
print (resultado)
```

#### Contador de Palabras: Escribe una función llamada contar_palabras que tome una cadena como argumento y devuelva el número de palabras en esa cadena. Supón que las palabras están separadas por espacios.

```python:
def contar_palabras(frase):
    palabras = frase.split()
    return len(palabras)

num_palabras = contar_palabras("Hola, este es un ejemplo.")  # Debe devolver 5
print('El número total de palabras en la frase es: ', num_palabras)
```

#### Cálculo de Potencia: Escribe una función llamada potencia que tome dos números enteros como argumentos, uno como base y otro como exponente, y devuelva el resultado de elevar la base al exponente.

```python:
def potencia(bas, expo):
    return (bas ** expo)

resultado = potencia(2, 3)  # Debe devolver 8 (2^3 = 2 * 2 * 2)
print('el resultado es', resultado)
```
<!-- Su documentación aquí -->







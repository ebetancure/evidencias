<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2

#### Ciclos While

#### Solicita al usuario que ingrese una lista de números y encuentra el número mayor y el menor.
```python:
lista = input("Ingresa una lista de números separados por comas: ")
lista = lista.split(",")
i = 0
num = float('inf')
num2 = 0

while i < len(lista):
    if int(lista[i]) < num:
        num = int(lista[i])
    elif int(lista[i]) > num2:
        num2 = int(lista[i])
    i += 1

print ("el numero menor es ",num)
print ("el numero mayor es ",num2)
```

#### Solicita al usuario un número e imprime la suma de los números pares entre 1 y ese número.

```python:
i = 0
num2=0
num = input("digite un numero ")
while i < int(num)+1:
    if i % 2 == 0:
        num2 += i 
    i+=1

print ("la suma de los numeros pares entre 1 y ", num, " es ",num2)
```

#### Solicita al usuario una cadena e imprime cuántas vocales contiene.
```python:
cadena = input("Ingresa una cadena: ")
vocales = 'aeiouAEIOU'
i = 0
contador = 0
while i < len(cadena):
    if cadena[i] in vocales:
        contador += 1
    i += 1
print("La cadena tiene", contador, "vocales.")
```

#### Solicita al usuario un número y muestra su tabla de potencias desde 1 hasta 10.

```python:
num = input ("ingrese un numero ")
i = 1

while i <= 10:
    expo=int ( num )**i
    print(num,"^",i,"=",expo)
    i+=1
```

#### Solicita al usuario una lista de números y calcula la media aritmética.
```python:
lista = input("Ingresa una lista de números separados por comas: ")
lista = lista.split(",")
i=0
suma = 0
while i < len(lista):
    suma += int(lista[i])
    i+=1

media = suma / len(lista)
print ("la media aritmetica de la lista es ", media)
```

#### Ciclos for

#### Solicita al usuario una lista de números y calcula la suma de sus elementos.
```python:
lista = input("Ingresa una lista de números separados por comas: ")
lista = lista.split(",")
suma = 0
for i in lista:
    suma += int(i)
    
print ("la media aritmetica de la lista es ", suma)
```

#### Solicita al usuario una lista de números e imprime cuántos de ellos son pares.
```python:
lista = input("Ingresa una lista de números separados por comas: ")
lista = lista.split(",")
par = 0
for i in lista:
    if int(i) % 2 == 0:
        par += 1

print(par,"son pares")
```

#### Solicita al usuario un número y muestra su tabla de multiplicar usando range().
```python:
num=input("ingrese un numero ")

for i in range(1, 11):
    print(num, "x", i, "=", int(num)*i)`

#### Solicita al usuario un número e imprime los números pares desde 2 hasta ese número.
`num = int(input("ingrese un numero "))

for i in range (2,num + 1):
    if i % 2 == 0:
        print(i)
```

#### Solicita al usuario un número y muestra la secuencia de números pares desde 2 hasta ese número.
```python:
num = int(input("ingresa un número: "))

secue = []
for i in range(2, num + 1):
    if i % 2 == 0:
        secue.append(i)

print("Secuencia de números pares:", secue)
```

#### Captura de comandos git
![captura](https://firebasestorage.googleapis.com/v0/b/eviden-56fc7.appspot.com/o/sesion2.jpg?alt=media&token=fc891154-df2d-4e2a-954f-2e7381063d89)

<!-- Su documentación aquí -->







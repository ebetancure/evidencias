<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 

#### Listas
```python:
lista = [1,3,2,4,6,5,7,9,8,10]
print(lista)
lista.sort()
print(lista)
lista.reverse()
print(lista)
pequeno = min(lista)
print("El número más pequeño en la lista es:", pequeno)
grande = max(lista)
print("El número más grande en la lista es:", grande)
print("la cantidad de 5 son:", lista.count(5))
lista.remove(5)
print(lista)
lista.append(11)
print(lista)
```

#### Tuplas
```python:
tupla = ('Hola','mundo', 'Python')
print(tupla)
tuplaordenada = tuple(sorted(tupla))
print(tuplaordenada)
print(tuplaordenada[0])
print(tuplaordenada[2])
print(len(tuplaordenada))
lista2 = list(tuplaordenada)
lista2.pop()
tupla = tuple(lista2)
print(tupla)
lista2 = list(tupla)
lista2.append('Hola')
tupla = tuple(lista2)
print(tupla)
```
#### Conjuntos
```python:
conjunto = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
print(conjunto)
conjunto.add(11)
print(conjunto)
conjunto.remove(5)
print(conjunto)
print(len(conjunto))
print(5 in conjunto)
print(11 in conjunto)
conjunto2 = {'Hola','mundo', 'Python'}
print(conjunto2)
print('Hola' in conjunto2)
print('mundo' in conjunto2)
```

#### Diccionarios
```python:
semana = {'lunes': 1, 'martes': 2, 'miércoles': 3, 'jueves': 4, 'viernes': 5, 'sábado': 6, 'domingo': 7
}
print(semana)
print(semana['lunes'])
print(semana.values())
numero = 2
for dia, numerodia in semana.items():
    if numerodia == numero:
        print(dia)
        break
del semana['lunes']
print(semana)
```
<!-- Su documentación aquí -->







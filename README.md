# Reto-No.4

## 1. Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.

```python
numero = int(input("Ingrese el numero: "))

vocal = chr(numero)

if vocal == "a" or vocal == "e" or vocal == "i" or vocal == "o" or vocal == "u":
    print(f"El numero {numero} corresponde al codigo ASCII de una vocal minúscula")

else:
    print(f"El numero {numero} NO corresponde al codigo ASCII de una vocal minúscula")
```

## 2. Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.

```python
cadena = str(input("Ingrese su carácter: "))

if len(cadena) != 1:
    print("La cadena tiene mas de un carácter")

else:
    codigo_ascii = ord(cadena)

    if codigo_ascii % 2 == 0:
        print("El código ASCII del caracter es par")

    else:
        print("El código ASCII del caracter NO es par")
```

## 3. Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```python
caracter = str(input("Escriba su caracter: "))

if caracter=="0" or caracter=="1" or caracter=="2" or caracter=="3" or caracter=="4" or caracter=="5" or caracter=="6" or caracter=="7" or caracter=="8" or caracter=="9":
    print(f"El caracter {caracter} es un digito")

else:
    print(f"El caracter {caracter} NO es un digito")
```

## 4. Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso se debe imprimir el texto que se especifica a continuación:

### Positivo: "El número x es positivo"

### Negativo: "El número x es negativo"

### Cero (0): "El número x es el neutro para la suma"

## 5. Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.

## 6. Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

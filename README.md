# Comparative Programming Languages (Javascript, TypeScript, Python). Rapid Guide

## Descripción

## Tabla de contenidos

- [Comparative Programming Languages (Javascript, TypeScript, Python). Rapid Guide](#comparative-programming-languages-javascript-typescript-python-rapid-guide)
  - [Descripción](#descripción)
  - [Tabla de contenidos](#tabla-de-contenidos)
  - [Instalación](#instalación)
  - [Resumen](#resumen)
  - [Variables y Tipos de Datos](#variables-y-tipos-de-datos)
    - [JavaScript](#javascript)
    - [TypeScript](#typescript)
    - [Python](#python)
  - [Estructuras de Control](#estructuras-de-control)
    - [JavaScript](#javascript-1)
    - [TypeScript](#typescript-1)
    - [Python](#python-1)
  - [Funciones](#funciones)
    - [JavaScript](#javascript-2)
    - [TypeScript](#typescript-2)
    - [Python](#python-2)
  - [Objetos](#objetos)
    - [JavaScript](#javascript-3)
    - [TypeScript](#typescript-3)
    - [Python](#python-3)
  - [Referencias](#referencias)

## Instalación

## Resumen

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

<table>
<tr>
<th align="center"><b>Características</b></th>
<th align="center"><b>Javascript</b></th>
<th align="center"><b>TypeScript</b></th>
<th align="center"><b>Python</b></th></tr>
<tr><td><b> Tipado Dinámico</b></td><td>

```javascript
let variable = 10
```

</td><td>

```typescript
let variable: number = 10
```

</td><td>

```python
variable = 10

```

</td></tr>
<tr><td><b>Tipado Estático</b> 
</td><td>
No 
</td><td>
Sí 
</td><td>
No 
</td><td>
<tr><td><b>Compilación</b> 
</td><td>
No 
</td><td>
Sí 
</td><td>
No 
</td><td>
<tr><td><b>Declaración de Variables</b></td><td>

```javascript
var x = 5
```

</td><td>

```typescript
let x: number = 5
```

</td><td>

```python
x = 5

```

</td></tr>
<tr><td><b>Funciones Anónimas</b></td><td>

```javascript
;() => {
  return 42
}
```

</td><td>

```typescript
;() => {
  return 42
}
```

</td><td>

```python
lambda: 42

```

</td></tr>
<tr><td><b>Manejo de Errores</b></td><td>

```javascript
try {
  /* código */
} catch (e) {
  /* manejo de error */
}
```

</td><td>

```typescript
try {
  /* código */
} catch (e) {
  /* manejo de error */
}
```

</td><td>

```python
try:
    # código
except Exception as e:
    # manejo de error

```

</td></tr>
<tr><td><b>Iteración sobre Arrays</b></td><td>

```javascript
for (let i of array) {
  /* código */
}
```

</td><td>

```typescript
for (let i of array) {
  /* código */
}
```

</td><td>

```python
for i in array:
    # código

```

</td></tr>
<tr><td><b>Uso de Promesas</b></td><td>

```javascript
fetch(url)
  .then((response) => response.json())
  .then((data) => console.log(data))
```

</td><td>

```typescript
fetch(url)
  .then((response) => response.json())
  .then((data) => console.log(data))
```

</td><td>

```python
import requests;
response = requests.get(url);
data = response.json();
print(data)

```

</td></tr>
<tr><td><b>Uso de Clases</b></td><td>

```javascript
class Persona {
  constructor(nombre) {
    this.nombre = nombre
  }
  saludar() {
    console.log('Hola, ' + this.nombre)
  }
}
```

</td><td>

```typescript
class Persona {
  constructor(public nombre: string) {}
  saludar() {
    console.log('Hola, ' + this.nombre)
  }
}
```

</td><td>

```python
class Persona:
    def __init__(self, nombre):
        self.nombre = nombre def saludar(self):
        print(f'Hola, {self.nombre}')

```

</td></tr>
<tr><td><b>Manejo de Strings</b></td><td>

```javascript
let nombre = 'John'
let mensaje = `Hola, ${nombre}!`
```

</td><td>

```typescript
let nombre: string = 'John'
let mensaje: string = `Hola, ${nombre}!`
```

</td><td>

```python
nombre = 'John';
mensaje = f'Hola, {nombre}!'

```

</td></tr>
<tr><td><b>Manejo de Arrays</b></td><td>

```javascript
let array = [1, 2, 3]
array.push(4)
```

</td><td>

```typescript
let array: number[] = [1, 2, 3]
array.push(4)
```

</td><td>

```python
array = [1, 2, 3];
array.append(4)

```

</td></tr>
<tr><td><b>Manejo de Objetos</b></td><td>

```javascript
let persona = {
  nombre: 'Ana',
  edad: 30,
}
```

</td><td>

```typescript
let persona: { nombre: string; edad: number } = {
  nombre: 'Ana',
  edad: 30,
}
```

</td><td>

```python
persona = {'nombre': 'Ana', 'edad': 30}

```

</td></tr>
<tr><td><b>Uso de Módulos</b> 
</td><td>
Antes de ES6, a través de convenciones. En ES6 y posteriores, se introdujeron módulos. 
</td><td>
Sí, mediante `import` y `export`. 
</td><td>
Sí, mediante `import` y `from`. 
</td><td>
<tr><td><b>Manejo de Asincronía</b></td><td>

```javascript
setTimeout(() => {
  console.log('Hola')
}, 1000)
```

</td><td>

```typescript
setTimeout(() => {
  console.log('Hola')
}, 1000)
```

</td><td>

```python
import time;
time.sleep(1);
print('Hola')

```

</td></tr>
<tr><td><b>Comprensión de Listas</b> 
</td><td>
No 
</td><td>
No 
</td><td>

```python
[x**2 for x in range(10)]`

```

</td><td>
<tr><td><b>Manejo de Diccionarios</b></td><td>

```javascript
let diccionario = { clave: 'valor' }
```

</td><td>

```typescript
let diccionario: { [clave: string]: string } = {
  clave: 'valor',
}
```

</td><td>

```python
diccionario = {'clave': 'valor'}

```

</td></tr>
<tr><td><b>Manejo de Sets</b> 
</td><td>
No 
</td><td>
No 
</td><td>

```python
conjunto = {1, 2, 3}

```

</td><td>
<tr><td><b>Decoradores</b> 
</td><td>
No 
</td><td>
Sí, mediante el uso de `@ 
</td><td></td><td>
<tr><td><b>Manejo de Nulos y Undefines</b></td><td>

```javascript
let x = null
```

</td><td>

```typescript
let x: null = null
```

</td><td>

```python
x = None

```

</td></tr>

<tr><td><b>Export e Import</b></td>
<td>

```javascript
// Export
export const variable = 42

// Import
import { variable } from './archivo'
```

</td><td>

```typescript
// Export
export const variable: number = 42

// Import
import { variable } from './archivo'
```

</td><td>

```python
# Export
variable = 42

# Import
from archivo import variable
```

</td></tr>

<tr><td><b>Operador Condicional (Ternario)</b></td>
<td>

```javascript
let resultado = condicion ? 'verdadero' : 'falso'
```

</td><td>

```typescript
let resultado: string = condicion ? 'verdadero' : 'falso'
```

</td><td>

```python
resultado = 'verdadero' if condicion else 'falso'

```

</td></tr>

<tr><td><b>Funciones Flecha (Arrow Functions)</b></td>
<td>

```javascript
const sumar = (a, b) => a + b
```

</td><td>

```typescript
const sumar = (a: number, b: number): number => a + b
```

</td><td>

```python
sumar = lambda a, b: a + b

```

</td></tr>

<tr><td><b>Parámetros Predeterminados (Default Values)</b></td>
<td>

```javascript
function saludar(nombre = 'Usuario') {
  console.log(`Hola, ${nombre}!`)
}
```

</td><td>

```typescript
function saludar(nombre: string = 'Usuario'): void {
  console.log(`Hola, ${nombre}!`)
}
```

</td><td>

```python
def saludar(nombre='Usuario'):
    print(f'Hola, {nombre}!')

```

</td></tr>

<tr><td><b>Template Literals</b></td>
<td>

```javascript
let nombre = 'John'
let mensaje = `Hola, ${nombre}!`
```

</td><td>

```typescript
let nombre: string = 'John'
let mensaje: string = `Hola, ${nombre}!`
```

</td><td>

```python
nombre = 'John'
mensaje = f'Hola, {nombre}!'

```

</td></tr>

<tr><td><b>Propiedades Abreviadas</b></td>
<td>

```javascript
let nombre = 'John'
let edad = 30
let persona = { nombre, edad }
```

</td><td>

```typescript
let nombre: string = 'John'
let edad: number = 30
let persona: { nombre: string; edad: number } = {
  nombre,
  edad,
}
```

</td><td>

```python
nombre = 'John'
edad = 30
persona = {'nombre': nombre, 'edad': edad}

```

</td></tr>

<tr><td><b>La Desestructuración</b></td>
<td>

```javascript
let persona = { nombre: 'John', edad: 25 }
let { nombre, edad } = persona
```

</td><td>

```typescript
let persona: { nombre: string; edad: number } = {
  nombre: 'John',
  edad: 25,
}
let { nombre, edad } = persona
```

</td><td>

```python
persona = {'nombre': 'John', 'edad': 25}
nombre, edad = persona['nombre'], persona['edad']

```

</td></tr>

<tr><td><b>Métodos de Array: map, filter, find</b></td>
<td>

```javascript
let numeros = [1, 2, 3, 4, 5]
let cuadrados = numeros.map((num) => num ** 2)
let pares = numeros.filter((num) => num % 2 === 0)
let encontrado = numeros.find((num) => num === 3)
```

</td><td>

```typescript
let numeros: number[] = [1, 2, 3, 4, 5]
let cuadrados: number[] = numeros.map((num) => num ** 2)
let pares: number[] = numeros.filter((num) => num % 2 === 0)
let encontrado: number | undefined = numeros.find((num) => num === 3)
```

</td><td>

```python
numeros = [1, 2, 3, 4, 5]
cuadrados = list(map(lambda num: num ** 2, numeros))
pares = list(filter(lambda num: num % 2 == 0, numeros))
encontrado = next((num for num in numeros if num == 3), None)

```

</td></tr>

<tr><td><b>Sintaxis Spread</b></td>
<td>

```javascript
let array1 = [1, 2, 3]
let array2 = [...array1, 4, 5]
```

</td><td>

```typescript
let array1: number[] = [1, 2, 3]
let array2: number[] = [...array1, 4, 5]
```

</td><td>

```python
array1 = [1, 2, 3]
array2 = [*array1, 4, 5]

```

</td></tr>

<tr><td><b>Operador Rest</b></td>
<td>

```javascript
function sumar(...numeros) {
  return numeros.reduce((total, num) => total + num, 0)
}
```

</td><td>

```typescript
function sumar(...numeros: number[]): number {
  return numeros.reduce((total, num) => total + num, 0)
}
```

</td><td>

```python
def sumar(*numeros):
    return sum(numeros)

```

</td></tr>

<tr><td><b>Expresiones Regulares</b></td>
<td>

```javascript
const regex = /patrón/
const resultado = regex.test('cadena')
```

</td><td>

```typescript
const regex: RegExp = /patrón/
const resultado: boolean = regex.test('cadena')
```

</td><td>

```python
import re
regex = re.compile("patrón")
resultado = bool(regex.match("cadena"))

```

</td></tr>

<tr><td><b>Operaciones de Cadena</b></td>
<td>

```javascript
const cadena = '   Hola, Mundo!   '
const sinEspacios = cadena.trim()
const reemplazada = cadena.replace('Mundo', 'Universo')
const contiene = cadena.includes('Hola')
const indice = cadena.indexOf('Mundo')
const mayusculas = cadena.toUpperCase()
const minusculas = cadena.toLowerCase()
const subcadena = cadena.substring(5, 9)
const longitud = cadena.length
```

</td><td>

```typescript
const cadena: string = '   Hola, Mundo!   '
const sinEspacios: string = cadena.trim()
const reemplazada: string = cadena.replace('Mundo', 'Universo')
const contiene: boolean = cadena.includes('Hola')
const indice: number = cadena.indexOf('Mundo')
const mayusculas: string = cadena.toUpperCase()
const minusculas: string = cadena.toLowerCase()
const subcadena: string = cadena.substring(5, 9)
const longitud: number = cadena.length
```

</td><td>

```python
cadena = "   Hola, Mundo!   "
sin_espacios = cadena.strip()
reemplazada = cadena.replace("Mundo", "Universo")
contiene = "Hola" in cadena
indice = cadena.find("Mundo")
mayusculas = cadena.upper()
minusculas = cadena.lower()
subcadena = cadena[5:9]
longitud = len(cadena)

```

</td></tr>

<tr><td><b>Sort</b></td>
<td>

```javascript
const array = [3, 1, 4, 1, 5, 9, 2, 6, 5]
const sortedArray = array.sort()
```

</td><td>

```typescript
const array: number[] = [3, 1, 4, 1, 5, 9, 2, 6, 5]
const sortedArray: number[] = array.sort()
```

</td><td>

```python
array = [3, 1, 4, 1, 5, 9, 2, 6, 5]
sorted_array = sorted(array)

```

</td></tr>

<tr><td><b>Sort con Números</b></td>
<td>

```javascript
const array = [3, 1, 4, 1, 5, 9, 2, 6, 5]
const sortedArray = array.sort((a, b) => a - b)
```

</td><td>

```typescript
const array: number[] = [3, 1, 4, 1, 5, 9, 2, 6, 5]
const sortedArray: number[] = array.sort((a, b) => a - b)
```

</td><td>

```python
array = [3, 1, 4, 1, 5, 9, 2, 6, 5]
sorted_array = sorted(array)

```

</td></tr>
</table>

<hr>

---

<details>

<summary>Más</summary>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

<tr><td><b></b></td>
<td>

```javascript

```

</td><td>

```typescript

```

</td><td>

```python

```

</td></tr>

</details>

## Variables y Tipos de Datos

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript
// JavaScript no tiene tipos de datos estáticos
let nombre = 'Juan'
let edad = 25
let esEstudiante = true
let arrayEjemplo = [1, 2, 3]
let objetoEjemplo = { nombre: 'Maria', edad: 30 }
```

### TypeScript

```typescript
// TypeScript tiene tipos de datos estáticos
let nombre: string = 'Juan'
let edad: number = 25
let esEstudiante: boolean = true
let arrayEjemplo: number[] = [1, 2, 3]
let objetoEjemplo: { nombre: string; edad: number } = {
  nombre: 'Maria',
  edad: 30,
}
```

### Python

```python
# Python es de tipado dinámico
nombre = "Juan"
edad = 25
es_estudiante = True
lista_ejemplo = [1, 2, 3]
diccionario_ejemplo = {"nombre": "Maria", "edad": 30}
```

## Estructuras de Control

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript
if (edad >= 18) {
  console.log(`${nombre} es mayor de edad`)
} else {
  console.log(`${nombre} es menor de edad`)
}

for (let i = 0; i < 5; i++) {
  console.log(i)
}
```

### TypeScript

```typescript
if (edad >= 18) {
  console.log(`${nombre} es mayor de edad`)
} else {
  console.log(`${nombre} es menor de edad`)
}

for (let i: number = 0; i < 5; i++) {
  console.log(i)
}
```

### Python

```python
if edad >= 18:
    print(f"{nombre} es mayor de edad")
else:
    print(f"{nombre} es menor de edad")

for i in range(5):
    print(i)

```

## Funciones

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript
function saludar(nombre) {
  return `Hola, ${nombre}!`
}

let mensaje = saludar('Ana')
console.log(mensaje)
```

### TypeScript

```typescript
function saludar(nombre: string): string {
  return `Hola, ${nombre}!`
}

let mensaje: string = saludar('Ana')
console.log(mensaje)
```

### Python

```python
def saludar(nombre):
    return f"Hola, {nombre}!"

mensaje = saludar("Ana")
print(mensaje)
```

## Objetos

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript
let persona = {
  nombre: 'Carlos',
  edad: 28,
  saludar: function () {
    console.log(`Hola, soy ${this.nombre}`)
  },
}

console.log(persona.nombre)
persona.saludar()
```

### TypeScript

```typescript
type Persona = {
  nombre: string
  edad: number
  saludar: () => void
}

let persona: Persona = {
  nombre: 'Carlos',
  edad: 28,
  saludar: function () {
    console.log(`Hola, soy ${this.nombre}`)
  },
}

console.log(persona.nombre)
persona.saludar()
```

### Python

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def saludar(self):
        print(f"Hola, soy {self.nombre}")

persona = Persona("Carlos", 28)
print(persona.nombre)
persona.saludar()
```

## Referencias

- https://github.com/midudev/preguntas-entrevista-react#qu%C3%A9-javascript-necesito-para-aprender-react

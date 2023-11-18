# Comparative Programming Languages (Javascript, TypeScript, Python). Rapid Guide

## Descripción

## Tabla de contenidos

- [Comparative Programming Languages (Javascript, TypeScript, Python). Rapid Guide](#comparative-programming-languages-javascript-typescript-python-rapid-guide)
  - [Descripción](#descripción)
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
  - [](#)
    - [JavaScript](#javascript-4)
    - [TypeScript](#typescript-4)
    - [Python](#python-4)
  - [](#-1)
    - [JavaScript](#javascript-5)
    - [TypeScript](#typescript-5)
    - [Python](#python-5)
  - [](#-2)
    - [JavaScript](#javascript-6)
    - [TypeScript](#typescript-6)
    - [Python](#python-6)
  - [](#-3)
    - [JavaScript](#javascript-7)
    - [TypeScript](#typescript-7)
    - [Python](#python-7)
  - [](#-4)
    - [JavaScript](#javascript-8)
    - [TypeScript](#typescript-8)
    - [Python](#python-8)
  - [](#-5)
    - [JavaScript](#javascript-9)
    - [TypeScript](#typescript-9)
    - [Python](#python-9)
  - [](#-6)
    - [JavaScript](#javascript-10)
    - [TypeScript](#typescript-10)
    - [Python](#python-10)
  - [](#-7)
    - [JavaScript](#javascript-11)
    - [TypeScript](#typescript-11)
    - [Python](#python-11)
  - [](#-8)
    - [JavaScript](#javascript-12)
    - [TypeScript](#typescript-12)
    - [Python](#python-12)
  - [](#-9)
    - [JavaScript](#javascript-13)
    - [TypeScript](#typescript-13)
    - [Python](#python-13)
  - [](#-10)
    - [JavaScript](#javascript-14)
    - [TypeScript](#typescript-14)
    - [Python](#python-14)
  - [](#-11)
    - [JavaScript](#javascript-15)
    - [TypeScript](#typescript-15)
    - [Python](#python-15)
  - [](#-12)
    - [JavaScript](#javascript-16)
    - [TypeScript](#typescript-16)
    - [Python](#python-16)
  - [](#-13)
    - [JavaScript](#javascript-17)
    - [TypeScript](#typescript-17)
    - [Python](#python-17)
  - [](#-14)
    - [JavaScript](#javascript-18)
    - [TypeScript](#typescript-18)
    - [Python](#python-18)
  - [](#-15)
    - [JavaScript](#javascript-19)
    - [TypeScript](#typescript-19)
    - [Python](#python-19)
  - [](#-16)
    - [JavaScript](#javascript-20)
    - [TypeScript](#typescript-20)
    - [Python](#python-20)
  - [](#-17)
    - [JavaScript](#javascript-21)
    - [TypeScript](#typescript-21)
    - [Python](#python-21)
  - [](#-18)
    - [JavaScript](#javascript-22)
    - [TypeScript](#typescript-22)
    - [Python](#python-22)
  - [](#-19)
    - [JavaScript](#javascript-23)
    - [TypeScript](#typescript-23)
    - [Python](#python-23)

## Instalación

## Resumen

| Característica                  | JavaScript                                                                                                           | TypeScript                                                                                                   | Python                                                                                                             |
| ------------------------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| **Tipado Dinámico**             | `let variable = 10;`                                                                                                 | `let variable: number = 10;`                                                                                 | `variable = 10`                                                                                                    |
| **Tipado Estático**             | No                                                                                                                   | Sí                                                                                                           | No                                                                                                                 |
| **Compilación**                 | No                                                                                                                   | Sí                                                                                                           | No                                                                                                                 |
| **Declaración de Variables**    | `var x = 5;`                                                                                                         | `let x: number = 5;`                                                                                         | `x = 5`                                                                                                            |
| **Funciones Anónimas**          | `() => { return 42; }`                                                                                               | `() => { return 42; }`                                                                                       | `lambda: 42`                                                                                                       |
| **Manejo de Errores**           | `try { /* código */ } catch (e) { /* manejo de error */ }`                                                           | `try { /* código */ } catch (e) { /* manejo de error */ }`                                                   | `try: # código except Exception as e: # manejo de error`                                                           |
| **Iteración sobre Arrays**      | `for (let i of array) { /* código */ }`                                                                              | `for (let i of array) { /* código */ }`                                                                      | `for i in array: # código`                                                                                         |
| **Uso de Promesas**             | `fetch(url).then(response => response.json()).then(data => console.log(data));`                                      | `fetch(url).then(response => response.json()).then(data => console.log(data));`                              | `import requests; response = requests.get(url); data = response.json(); print(data)`                               |
| **Uso de Clases**               | `class Persona { constructor(nombre) { this.nombre = nombre; } saludar() { console.log('Hola, ' + this.nombre); } }` | `class Persona { constructor(public nombre: string) {} saludar() { console.log('Hola, ' + this.nombre); } }` | `class Persona: def __init__(self, nombre): self.nombre = nombre def saludar(self): print(f'Hola, {self.nombre}')` |
| **Manejo de Strings**           | `` let nombre = 'John'; let mensaje = `Hola, ${nombre}!`; ``                                                         | `` let nombre: string = 'John'; let mensaje: string = `Hola, ${nombre}!`; ``                                 | `nombre = 'John'; mensaje = f'Hola, {nombre}!'`                                                                    |
| **Manejo de Arrays**            | `let array = [1, 2, 3]; array.push(4);`                                                                              | `let array: number[] = [1, 2, 3]; array.push(4);`                                                            | `array = [1, 2, 3]; array.append(4)`                                                                               |
| **Manejo de Objetos**           | `let persona = { nombre: 'Ana', edad: 30 };`                                                                         | `let persona: { nombre: string, edad: number } = { nombre: 'Ana', edad: 30 };`                               | `persona = {'nombre': 'Ana', 'edad': 30}`                                                                          |
| **Uso de Módulos**              | Antes de ES6, a través de convenciones. En ES6 y posteriores, se introdujeron módulos.                               | Sí, mediante `import` y `export`.                                                                            | Sí, mediante `import` y `from`.                                                                                    |
| **Manejo de Asincronía**        | `setTimeout(() => { console.log('Hola'); }, 1000);`                                                                  | `setTimeout(() => { console.log('Hola'); }, 1000);`                                                          | `import time; time.sleep(1); print('Hola')`                                                                        |
| **Comprensión de Listas**       | No                                                                                                                   | No                                                                                                           | `[x**2 for x in range(10)]`                                                                                        |
| **Manejo de Diccionarios**      | `let diccionario = { 'clave': 'valor' };`                                                                            | `let diccionario: { [clave: string]: string } = { 'clave': 'valor' };`                                       | `diccionario = {'clave': 'valor'}`                                                                                 |
| **Manejo de Sets**              | No                                                                                                                   | No                                                                                                           | `conjunto = {1, 2, 3}`                                                                                             |
| **Decoradores**                 | No                                                                                                                   | Sí, mediante el uso de `@                                                                                    |                                                                                                                    |
| **Manejo de Nulos y Undefines** | `let x = null;                                                                                                       | `let x: null = null`                                                                                         | `x = None`                                                                                                         |

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

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

<details>

<summary>Recursos para ver</summary>

[Ver en PythonTutor](https://pythontutor.com/javascript.html#code=${encodeURIComponent(`let nombre = "Juan"; let edad = 25; let esEstudiante = true; let arrayEjemplo = [1, 2, 3]; let objetoEjemplo = { nombre: "Maria", edad: 30 };`)})

##

**Ver en:** [PythonTutor]() | [Repl.it](https://replit.com/) | [TypeScript Playground](https://www.typescriptlang.org/)

### JavaScript

```javascript

```

### TypeScript

```typescript

```

### Python

```python

```

</details>

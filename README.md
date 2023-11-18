# Comparative Programming Languages (Javascript, TypeScript, Python). Rapid Guide

## Descripción

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

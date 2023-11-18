# Comparative Programming Languages Essentials (Javascript, TypeScript, Python). Rapid Guide

## Description

## Installation

## Variables y Tipos de Datos

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

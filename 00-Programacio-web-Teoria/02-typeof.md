# Operador `typeof`

El operador `typeof` se utiliza para conocer el **tipo de dato** que almacena una variable o un valor.

Su sintaxis es muy sencilla:

```javascript
typeof variable
```

---

## Ejemplo 1

```javascript
let nombre = "Antonella";

console.log(typeof nombre);
```
**Resultado:**

```text
string
```

---

## Ejemplo 2

```javascript
let edad = 26;

console.log(typeof edad);
```

**Resultado:**

```text
number
```

---

## Ejemplo 3

```javascript
let esProfesor = true;

console.log(typeof esProfesor);
```

**Resultado:**

```text
boolean
```

---

## Más ejemplos

```javascript
console.log(typeof "Hola");
console.log(typeof 10);
console.log(typeof 3.14);
console.log(typeof false);
console.log(typeof undefined);
console.log(typeof null);
```

**Salida**

```text
string
number
number
boolean
undefined
object
```

> **Importante:** `typeof null` devuelve `object`. Es un comportamiento histórico de JavaScript.

---

## Resumen

| Código | Resultado |
|---------|-----------|
| `typeof "Hola"` | `string` |
| `typeof 10` | `number` |
| `typeof true` | `boolean` |
| `typeof undefined` | `undefined` |
| `typeof null` | `object` |
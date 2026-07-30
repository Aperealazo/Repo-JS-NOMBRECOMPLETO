# Constantes (`const`)

Una constante es una variable cuyo **valor no puede cambiar** después de ser creada.

Para declarar una constante se utiliza la palabra reservada `const`.

---

## Sintaxis

```javascript
const nombreVariable = valor;
```

---

## Ejemplo

```javascript
const PI = 3.1416;

console.log(PI);
```

**Resultado**

```text
3.1416
```

---

## Intentar modificar una constante

```javascript
const PI = 3.1416;

PI = 3;
```

**Resultado**

```text
TypeError: Assignment to constant variable.
```

---

## ¿Cuándo utilizar `const`?

Usá `const` cuando el dato **no debe cambiar** durante la ejecución del programa.

Por ejemplo:

- El valor de PI.
- El nombre de una empresa.
- La URL de una página.
- Un color principal.
- Una configuración del sistema.

---

## Ejemplo

```javascript
const empresa = "CEN Devs";
const pais = "Argentina";
const anio = 2026;

console.log(empresa);
console.log(pais);
console.log(anio);
```

---

## Diferencia entre `let` y `const`

```javascript
let edad = 20;
edad = 21; //Se puede modificar

const PI = 3.1416;
// PI = 3;Error
```

---

## Resumen

| Palabra | ¿Puede cambiar su valor? |
|----------|--------------------------|
| `let` | Sí |
| `const` | No |
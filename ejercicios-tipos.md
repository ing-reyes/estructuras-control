15 ejercicios enfocados en tipar variables, funciones, objetos literales y arreglos en TypeScript, donde todo está tipado como `any` para que ustedes lo tipen correctamente.

```markdown
# Ejercicios de Tipado en TypeScript

A continuación se presentan 15 ejercicios para practicar el tipado de variables, funciones, objetos literales y arreglos en TypeScript. Cada ejercicio tiene la palabra clave `any` para que ustedes puedan tipar correctamente las variables, funciones y estructuras de datos.
```

---

## Ejercicio 1: Tipar una variable de tipo número
Declara una variable con el tipo `any` y asígnale un valor numérico. Luego, cambia el tipo de la variable a al que corresponde.

```ts
let numero: any = 10; // Tipado incorrecto, cambiarlo por el correcto.'
```

---

## Ejercicio 2: Tipar una variable de tipo cadena
Declara una variable con el tipo `any` y asígnale un valor de tipo cadena. Luego, cambia el tipo de la variable al que corresponde.

```ts
let texto: any = "Hola mundo"; // Tipado incorrecto, cambiarlo por el correcto.
```

---

## Ejercicio 3: Tipar una función que suma dos números
Crea una función que reciba dos parámetros tipados como `any`, los sume y retorne el resultado como un número.

```ts
function sumar(a: any, b: any): any {
  return a + b; // Tipado incorrecto, cambiarlo por el correcto.
}
```

---

## Ejercicio 4: Tipar un objeto literal
Declara un objeto literal con tipo `any` que contenga las propiedades `nombre` (string) y `edad` (número). Luego, cambia el tipo del objeto y las propiedades adecuadamente.

```ts
let persona: any = {
  nombre: "Juan",
  edad: 30
}; // Tipado incorrecto, cambia a un tipo adecuado para el objeto
```

---

## Ejercicio 5: Tipar un arreglo de números
Declara una variable de tipo `any` que sea un arreglo de números. Luego, cambia el tipo a un arreglo del tipo que le corresponda.

```ts
let numeros: any = [1, 2, 3, 4, 5]; // Tipado incorrecto, cambiarlo por el correcto.
```

---

## Ejercicio 6: Tipar una función que recibe un objeto
Crea una función que reciba un objeto como parámetro (tipado como `any`) y acceda a una de sus propiedades.

```ts
function saludar(persona: any): void {
  console.log(`Hola, ${persona.nombre}`); // Tipado incorrecto, cambia a un tipo adecuado
}
```

---

## Ejercicio 7: Tipar una función que retorna un arreglo de cadenas
Crea una función que retorne un arreglo de cadenas de texto tipado como `any[]`, y luego cámbialo al tipo que le corresponda.

```ts
function obtenerNombres(): any[] {
  return ["Juan", "Pedro", "Maria"]; // Tipado incorrecto, cambiarlo por el correcto.
}
```

---

## Ejercicio 8: Tipar un arreglo de objetos
Declara una variable que sea un arreglo de objetos, cada uno con propiedades `nombre` y `edad`, tipados como `any`. Luego, cambia el tipo a un arreglo de objetos con el tipo adecuado.

```ts
let personas: any = [
  { nombre: "Ana", edad: 25 },
  { nombre: "Luis", edad: 30 }
]; // Tipado incorrecto, cambia a un tipo adecuado
```

---

## Ejercicio 9: Tipar una función con retorno de objeto
Crea una función que retorne un objeto con propiedades `nombre` (string) y `edad` (número). Tipalo como `any` y cámbialo a un tipo adecuado.

```ts
function crearPersona(): any {
  return {
    nombre: "Carlos",
    edad: 28
  }; // Tipado incorrecto, cambia a un tipo adecuado
}
```

---

## Ejercicio 10: Tipar una función que recibe un arreglo de números
Crea una función que reciba un arreglo de números como parámetro (tipado como `any[]`) y retorne la suma de todos los elementos.

```ts
function sumarNumeros(numeros: any[]): any {
  return numeros.reduce((acc, num) => acc + num, 0); // Tipado incorrecto, cambiarlo por el correcto.
}
```

---

## Ejercicio 11: Tipar una función que maneja un objeto con múltiples tipos
Declara una función que reciba un objeto de tipo `any` con propiedades `id` (número) y `nombre` (cadena). Luego, cámbialo a un tipo adecuado.

```ts
function procesarObjeto(obj: any): void {
  console.log(`ID: ${obj.id}, Nombre: ${obj.nombre}`); // Tipado incorrecto, cambia a un tipo adecuado
}
```

---

## Ejercicio 12: Tipar una función que recibe una cadena
Crea una función que reciba un parámetro de tipo `any` (cadena) y lo imprima en consola. Luego, cambia el tipo de parámetro al que le corresponda.

```ts
function imprimirMensaje(mensaje: any): void {
  console.log(mensaje); // Tipado incorrecto, cambiarlo por el correcto.
}
```

---

## Ejercicio 13: Tipar una variable que contiene un booleano
Declara una variable tipada como `any` y asígnale un valor booleano. Luego, cambia el tipo de la variable al tipo que le corresponda.

```ts
let esActivo: any = true; // Tipado incorrecto, cambiarlo por el correcto.
```

---

## Ejercicio 14: Tipar un arreglo de objetos con diferentes tipos
Crea un arreglo que contenga objetos con diferentes tipos de propiedades, y tipalo como `any[]`. Luego, cambia el tipo del arreglo a uno adecuado.

```ts
let items: any[] = [
  { nombre: "Item 1", precio: 100 },
  { nombre: "Item 2", precio: 150, descuento: 10 }
]; // Tipado incorrecto, cambia a un tipo adecuado
```

---

## Ejercicio 15: Tipar un objeto con funciones como propiedades
Declara un objeto con propiedades de tipo `any` que contengan funciones. Luego, cambia el tipo del objeto y las funciones adecuadamente.

```ts
let calculadora: any = {
  sumar: function(a: any, b: any) {
    return a + b;
  },
  restar: function(a: any, b: any) {
    return a - b;
  }
}; // Tipado incorrecto, cambia a un tipo adecuado
```

---

No olvides que el tipo `any` se debe cambiar por un tipo adecuado para cada variable, función, o estructura.
***La estructura de control en TypeScript es fundamental para la lógica de cualquier programa. Permite que el flujo de ejecución se modifique en función de ciertas condiciones.***

## Estructuras de Control en TypeScript

Las estructuras de control son como las señales de tráfico en un programa: indican el camino que debe seguir la ejecución. En TypeScript, las más comunes son:

### 1. **Condicionales**
* **if-else:** Ejecuta un bloque de código si una condición es verdadera, y otro si es falsa.
  ```typescript
  let numero = 10;
  if (numero > 0) {
      console.log("El número es positivo");
  } else {
      console.log("El número es negativo o cero");
  }
  ```
* **switch:** Evalúa una expresión y ejecuta diferentes bloques de código basados en el valor de esa expresión.
  ```typescript
  let diaSemana = "lunes";
  switch (diaSemana) {
      case "lunes":
          console.log("¡Es hora de trabajar!");
          break;
      case "viernes":
          console.log("¡Fin de semana! pero me toca programar XD");
          break;
      default:
          console.log("Día cualquiera");
  }
  ```

### 2. **Bucles**
* **for:** Ejecuta un bloque de código un número específico de veces.
  ```typescript
  for (let i = 0; i < 5; i++) {
      console.log(i);
  }
  ```
* **while:** Ejecuta un bloque de código mientras una condición sea verdadera.
  ```typescript
  let contador = 0;
  while (contador < 10) {
      console.log(contador);
      contador++;
  }
  ```
* **do-while:** Ejecuta un bloque de código al menos una vez, y luego lo repite mientras una condición sea verdadera.
  ```typescript
  let numeroAleatorio = Math.random();
  do {
      console.log(numeroAleatorio);
      numeroAleatorio = Math.random();
  } while (numeroAleatorio < 0.5);
  ```

### 3. **Otros**
* **break:** Sale de un bucle o de un bloque switch.
* **continue:** Salta a la siguiente iteración de un bucle.

## ¿Por qué son importantes las estructuras de control?

* **Toma de decisiones:** Permiten que el programa tome decisiones basadas en diferentes condiciones.
* **Repetición de tareas:** Automatizan tareas repetitivas a través de los bucles.
* **Control del flujo:** Controlan el orden en que se ejecutan las instrucciones.

## Ejemplos más complejos

* **Validación de datos:** Verificar si un usuario ingresó un correo electrónico válido antes de enviarlo.
* **Procesamiento de arreglos:** Iterar sobre un arreglo para encontrar un elemento específico o realizar cálculos.
* **Creación de menús:** Presentar un menú al usuario y ejecutar diferentes acciones según la opción seleccionada.

## Consideraciones adicionales en TypeScript

* **Tipado:** Las estructuras de control en TypeScript se benefician del tipado estático, lo que ayuda a prevenir errores comunes.
* **Interfaces:** Las interfaces pueden utilizarse para definir la estructura de los datos que se utilizan en las estructuras de control.
* **Funciones de flecha:** Las funciones de flecha pueden simplificar la sintaxis de las estructuras de control.

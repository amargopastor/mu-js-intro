---
title: JS intro
---

# mu-js-intro

1. Objetivos:

- Entender el lenguaje JS
- Declarar variables
- Expresiones lógicas
- Introducción a funciones

2. Contenidos:

- Tipos de datos
- Condicionales
- Bucles
- Funciones

3. Materiales:

- Navegador
- Editor de código
- replit.com

4. Requisitos:

- conocimientos básicos de HTML y CSS

## 1.Introducción

JS: uno de los lenguajes de programación más empleados en el desarrollo web, móvil, juegos, etc.

JavaScript (abreviado comúnmente JS) es un lenguaje de programación interpretado, dialecto del estándar ECMAScript. Se define como orientado a objetos,​ basado en prototipos, imperativo, débilmente tipado y dinámico.

## 2.Añadir el JS

- Incluir JS en HTML:

```html
<body>
  <script>
    console.log("hola mundo");
  </script>
</body>
```

- Usar vincular un archivo `script.js` justo antes del cierre del cuerpo.

## 3.console.log()

La función console.log indica al programa que debe imprimir un texto por consola, tambien llamada salida de programa.

```js
console.log("Hello world");
```

## 4.Herramientas de desarrollo

JavaScript se ejecuta en el lado del cliente de la web.

Google `chrome dev tools`: console y network para detectar nuestros errores o enviar mensajes.

## 5.Variables

```js
let mi_masa = 70;
let Tierra = 1;
let Marte = 3.71;
let Jupiter = 23.12;

console.log(mi_masa * Tierra);
console.log(mi_masa * Marte);
console.log(mi_masa * Jupiter);

let intro = "Mi nombre es Marcos y en este planeta peso ";
console.log(typeof intro);

let data = mi_masa - mi_masa * Tierra * equipo;
console.log(typeof data);

console.log(intro, data);

// Errores
let Tierra = 1.87;
// let Tierra2 = 1.87;
console.log(mi_masa - mi_masa * Tierra * equipo);
// Uncaught SyntaxError: Identifier 'Tierra' has already been declared
```

## 6.Expresiones lógicas &6 boleans & Condiciones if() {} else if() {} else {}

```js
let oxigeno = true;

if (oxigeno) {
  console.log("Puedo respirar!");
} else {
  console.log("Ayudagghghghg!");
}

console.log(typeof equipo);
console.log(typeof data);
console.log(typeof intro);
console.log(typeof oxigeno);
```

## 7.array + push() + pop()

Una lista o array es una secuencia ordenada de datos. Estos datos pueden ser de x tipos.

[Métodos de los arrays](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array#).

```js
let listado = [];
let listado2 = new Array();

let listadoPlanetas = [
  "Mercurio",
  "Venus",
  "Tierra",
  "Marte",
  "Júpiter",
  "Saturno",
  "Urano",
  "Neptuno",
  "Plutón",
];

console.log(listadoPlanetas.length);
console.log(listadoPlanetas);
console.log(listadoPlanetas[0]);
console.log(listadoPlanetas[2]);
```

## 8.Comentarios

Indican al navegador que texto debe ser obviado.

## 9.Funciones

Una función es una sintaxis que usamos para encapsular un programa (entran unos datos y salen otros datos).

`function` es una palabra reservada de javascript.

- Reutilizar código
- Abstracción
- `arguments`
- parámetros vs argumentos

```js
console.log(
  "Mi nombre es Marcos y estoy de visita en el planeta",
  listadoPlanetas[0],
);
console.log(
  "Mi nombre es Marcos y estoy de visita en el planeta",
  listadoPlanetas[1],
);
console.log(
  "Mi nombre es Marcos y estoy de visita en el planeta",
  listadoPlanetas[2],
);

function reporte(i) {
  console.log(i);
  console.log(
    "Mi nombre es Marcos y estoy de visita en el planeta",
    listadoPlanetas[i],
  );
}

reporte(8);
```

## 10.bucle for

```js
for (let i = 0; i < 9; i++) {
  console.log(i);
  reporte(i);
}
```

```js
function reporte2(i) {
  if (i >= 0 && i < 9) {
    console.log(
      "Mi nombre es Marcos y estoy de visita en el planeta",
      listadoPlanetas[i],
    );
  } else {
    console.log("Usted ha abandonado el Sitema Solar");
  }
}

for (let i = 0; i < 10; i++) {
  console.log(i);
  reporte2(i);
}
```

## Documentación

### An introduction for new programmers

- [jsforcats](http://jsforcats.com/)
- [Métodos de los arrays](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array#)

### Noticias JS

- [Ecma-international](https://www.ecma-international.org/)
- [stateJS](https://2020.stateofjs.com/en-US/)

### Entornos de desarrollo

- [brackets.io](http://brackets.io/)
- [atom.io](https://atom.io/)
- [sublimetext.com](http://www.sublimetext.com/)
- [visualstudio.com](https://code.visualstudio.com/Download)
- [lighttable](http://lighttable.com/)

### Tools

- [checkVarNames](https://mothereff.in/js-variables)

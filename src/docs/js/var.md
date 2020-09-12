---
title: '1. Variáveis de tipos de dados'
description: '-'
---

## O que é uma variável?

São atributos que servem para armazenar valores.

## Como declarar uma variável?

Declarando um variável sem atribuir valor.

```js
> var x
x // undefined
```

Como não foi declarado nenhum valor, ela retorna undefined (indefinido).
Para atribuir um valor a uma variável é preciso utilizar o sinal de igual.

```js
> x = 10;
```

## Tipos de dados
- `String`
- `Number`
- `Boolean`
- `null`
- `undefined`
- `Object {}`
- `Array[]`

### String
Representa um valor dentro de aspas simples ou duplas.

```js
var name = 'Nome'
var example = "Exemplo"
```

### Boolean

Representado por um valor `true` ou `false`. Verdadeiro ou Falso.

```js
var loading = true
```

### null

Significa que não possui nenhum valor.

```js
var x = null
```

### undefined

Ausência de valor.

```js
var x
undefined
```

### Number

```js
var number = 42
```

### Object

Representação literal dos objetos. Objetos tem propriedades e métodos.

```js
var person = {
  height: 1.78,
  weight: 70
}
```

Para acessar as propriedades do objeto é preciso utilizar a notação de ponto.

```js
person.height // 1.78
```

Também pode ser acessada com a notação de array

```js
person['height'] // 1.78
```

*Obs: a notação de objetos é mais rápida*

Para sobrescrever as propriedades do método

```js
person.height = 1.80
```

### Array

Lista de valores

```js
var numbers = [1, 2, 3];
```

Para acessar os valores do array, é preciso saber que ele possui os índices.
Que são números iniciados a partir do zero. A primeira posição do array é 0.
Para acessar o primeiro valor precisaria utilizar o `nome_do_array[índice]`.

```js
> numbers[0] // 1
```

*Obs: No JavaScript os arrays são objetos*
---
title: '2. Operadores'
description: '-'
---

Vamos estudar sobre alguns operadores do JS

- [Operadores aritméticos](#operadores-aritméticos)
- [Operadores de comparação](#operadores-de-comparação)
- Operadores lógicos

## Operadores aritméticos 

São operadores básicos da matemática.

- Adição `+`
- Subtração `-`
- Multiplicação `*`
- Divisão `/`

```js
1 + 2 // 3
```

## Operadores aritméticos abreviados

- Incrementar valor `++`
- Decrementar um valor `--`
- Mais igual `+=`
- Menos igual `-=`
- Dividido igual `/=`
- Multiplicado igual `*=`

Incrementar
```js
var number = 1

x++ // 1
x // 2 pós-incremento

++x // 3 pré-incremento
```

Decrementar
```js
var number = 2
--number // 1 pré-decremento

number-- // 1
number // pós-decremento
```

Mais igual
```js
var number = 4
number += 2 // 6
```

Menos igual 
```js
var number = 5
number -= 3 // 2
```

Dividido igual

```js
var number = 10
number /= 5 // 2
```

Multiplicado igual

```js
var number = 3
3 *= 3 // 9
```

## Operadores de comparação

- Igual a `==`
- Diferente de `!=`
- Maior que `>`
- Menor que `<`
- Maior ou igual que `>=`
- Menor ou igual que `<=`

Servem para testar os valores se são iguais ou diferentes.
```js
1 == 1 // true
2 != 2 // false
```

- Igual a, e do mesmo tipo `===`
- Diferente de, e do mesmo tipo `!==`

```js
1 == '1' // true
/*
  Retorna true, devido a linguagem JavaScript é uma linguagem
  fraca e de tipagem dinâmica. Antes de ela testar ela converte
  o valor '1' que é uma string em número.
*/

1 === '1' // false
/*
  Retorna false pois está verificando o tipo da variável também.
*/
```

Maior (ou igual) que, Menor (ou igual) que
```js
5 > 5 // false
5 >= 5 // true

5 < 4 // false
3 <= 4 // true
```
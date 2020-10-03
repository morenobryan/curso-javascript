# Arrays

Listas de elementos. Pode ser qualquer tipo de elemento: objetos, inteiros, strings, ou todos ao
mesmo tempo

```javascript
let lista = []
lista = [1, 2, 3]
lista = [{ nome: "Bryan", sobrenome: "Moreno"}, 90, "banana", 3.14]
lista =
```

## Arrays são objetos

Por baixo do capô eles são objetos, contendo atributos e métodos como qualquer outro objeto. Porém,
a sintaxe que usamos para criar essas listas é um pouco diferente da de um objeto.

## Criando arrays

Através de literals (sintaxe de colchetes)

```javascript
let lista = [1, 2, 3];
```

Através do construtor do array

```javascript
let lista = new Array(1, 2, 3);
```

## Acessando valores

```javascript
let lista = ["banana", "maçã", "tomate"];
console.log(lista[0]);
// banana

console.log(lista[-1]);
// Não funciona

console.log(lista.length - 1);
// tomate
```

## Principais funções para arrays

### Filter

### Map

### Reduce

### Slice

### Splice

### Pop

### Push

### From

### Concat

### Every

### Find

### Includes

### IndexOf

### Join

### Reverse

### Some

### Unshift

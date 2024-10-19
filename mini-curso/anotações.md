# Tipos Primitivos no JavaScript

- string
- number (inteiro e flutuante)
- boolean
- array
- Objeto 

### Dicas
- Utilize ponto no lugar de virgula para numeros
- Usar ou não ; no javascript?
- não usar acentuações em nomes de variáveis

# Operadores Aritméticos

```Javascript

// SOMAR
let soma = 10 + 10
console.log(soma)

// SUBTRAIR
let subtrair = 10 - 5
console.log(subtrair)

// MULTIPLICAR
let multiplicar = 5 * 5
console.log(multiplicar)

// DIVISÃO
let divisao = 7/2
console.log(divisao)

```
---

# Operadores de comparação

```javascript

const comparacao1 = 3 > 6
console.log(comparacao1)


const comparacao2 = 3 < 6
console.log(comparacao2)


const comparacao3 = 6 <= 6
console.log(comparacao3)

const comparacao4 = 0 >= 6
console.log(comparacao4)

const comparacao5 = 6 === 6 // USO DE UM = , == , ===
console.log(comparacao5)

const comparacao6 = 6 === "6" 
console.log(comparacao6)

const comparacao7 = 6 == "6" 
console.log(comparacao7)

```

# Condicionais

```Javascript
const idade = 17

if(idade < 18) {
    console.log('é menor de idade')  // EXEMPLO UTILIZANDO  ||
} else if (idade >= 18 && idade <= 60) {
    console.log('é adulto')
} else {
    console.log('idoso')
}


```
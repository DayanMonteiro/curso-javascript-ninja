# Desafio Semana #1

```js

// Declarar uma variável chamada `myvar`, sem valor.
var myvar;

// Após declarada, atribua o valor 10 à variável `myvar`.
myvar = 10;

// Declare uma nova variável chamada `soma`, e adicione uma instrução somando os valores 15 e 8.
var soma = 15 + 8;
console.log(soma); // 23

// Atribua à variável `soma` todo o valor dela, somando 1, usando o operador de soma abreviado.
var soma = soma + 1;
console.log(soma); // 24
// Atribua à variável `soma` todo o valor dela, multiplicando por 3, usando o operador de multiplicação abreviado.
var soma = soma * 3;
console.log(soma); // 72

// Qual é o valor da variável `soma` até aqui?
72

// Declare uma variável chamada `souninja`, atribuindo à ela o valor booleano que representa `verdadeiro`.
var souninja = true;

// Declare uma variável chamada `comida` que recebe um array com os valores 'arroz', 'feijão' e 'ovo'.

var array = ['arroz', 'feijão', 'ovo'];

// Digite a instrução que imprime o valor de 'feijao', que está na variável `comida`.

var comidaEscolhida = array.find(item => item === 'feijão');

console.log(comidaEscolhida); // feijão
// Digite o código que verifica se a variável `soma' é igual a variável `myvar` (testando também o tipo).
soma == myvar


// Digite o código que verifica se a variável `myvar` é menor ou igual à variável `soma`.
myvar <= soma
// Crie uma função chamada `divisao` que receba como parâmetro dois números, e retorne o resultado da divisão entre eles.
var numero1 = 20;
var numero2 = 5;

var divisao = numero1 / numero2;
console.log(divisao); //4

// Invoque a função criada acima, passando os parâmetros 10 e 2.
function divisao1(num1,num2) {

    var resultado1 = num1 / num2;

    return resultado1;
  }

  console.log( divisao1(10,2) );
```

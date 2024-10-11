# Caderno virtual - Lógica da Programação e Algoritmos
Meu caderno virtual, não sei muito bem oque eu to fazendo mas to fazendo algo 


## Conteúdo Técnico
1. Switch
2. Array
3. Introdução do JavaScript
4. String
5. Number
6. Boolean
7. Variavel
8. Function

## **JavaScript**
### Variaveis
- **Var**: É como uma caixinha mais antiga. Ela é um pouco mais flexível, mas também pode causar alguns problemas se você não tomar cuidado.

~~~javascript
>var nomeDoHeroi = "Alex";
~~~~

* **Let**: É como uma caixinha mais moderna. Ela é mais segura e fácil de usar do que a var.

~~~javascript
>let pontuacao = 0;
~~~~

+ **Const**: É como uma caixinha trancada. Você coloca algo dentro dela, mas depois não pode mais mudar o que está lá.

~~~javascript
 const PI = 3.14; 
 console.log(PI); // Imprime "3.14" 
 PI = 3.15; // Irá gerar um erro, pois o valor de uma constante não pode ser alterado
~~~~

### String
 Strings são sequências de caracteres alfanuméricos (letras, números e/ou símbolos) amplamente usadas em programação. Em Javascript, uma string sempre estará entre aspas.
 ~~~javascript
 const frase = "Mergulhando em tecnologia com Alura";
~~~~

 String que nos permite criar ou converter um tipo em uma string, veja o exemplo abaixo:

~~~javascript
const numero = 256
const convertidoEmString = new String(numero)
~~~
 A concatenação de strings é o processo de unir duas ou mais strings em uma única. Em várias linguagens de programação, isso pode ser feito de maneiras diferentes. Aqui estão alguns exemplos:

~~~javascript
let string1 = "Olá";
let string2 = "Mundo";
let resultado = string1 + " " + string2;
console.log(resultado);
~~~

### Number
 O objeto JavaScript Number é um objeto encapsulado que permite você trabalhar com valores numéricos. Um objeto Number é criado utilizando o construtor Number(). Os principais usos para o objeto Number são: 
 Se o objeto não pode ser convertido para um número, é retornado NaN.
 Fora do contexo de um construtor (Ex., Sem o operador new, Number pode ser utilizador para realizar uma conversão de tipo.

~~~javascript
let a = 10;
let b = 5;

// Adição
let soma = a + b;          // 15

// Subtração
let subtracao = a - b;    // 5

// Multiplicação
let multiplicacao = a * b; // 50

// Divisão
let divisao = a / b;      // 2

// Módulo (resto da divisão)
let modulo = a % b;       // 0
~~~

### Boolean
 O valor passado como primeiro parâmetro é convertido para um valor boleano, se necessário. Se o valor é omitido ou é 0, -0, null, false, NaN, undefined ou é uma string vazia(""), o objeto terá um valor inicial de false. Todos outros valores, incluindo qualquer objeto ou string "false", criam um objeto com valor inicial true.

### Operadores lógicos e comparativos
 Os operadores lógicos são elementos fundamentais da linguagem de programação JavaScript. Eles permitem realizar operações de comparação e combinação de valores booleanos, ou seja, valores que podem ser verdadeiros (true) ou falsos (false). Basta colocar o sinal && entre as duas expressões que precisam ser comparadas.
~~~javascript
const a = true;
const b = false;
console.log(a && b); // false
~~~

### Array 
 Os arrays são estruturas que servem para guardar dados, e organizá-los. Seu objetivo é ser um espaço fixo na memória do computador que armazena elementos. Esses elementos podem ser acessados por um tipo de indicação, que chamamos de índice. Você pode guardar seus chapéus na gaveta 1, suas calças na gaveta 2 e as meias na gaveta 3, e sempre que precisar de calças, chapéus ou meias, vai saber em que gaveta buscar.
 
~~~javascript
var listaDeFrutas = ['Maçãs','Uvas','Bananas','Abacaxi','Morangos'];
//declarar o array
~~~

### Métodos Array
### *.forEach()*
 Caso você precise executar algum código para cada elemento do Array, executar um forEach é muito mais simples do que criar um for ou while, já que não precisamos declarar variáveis de controle. O .forEach() irá jogar cada um dos elemetos do Array no primeiro parâmetro, o índice do elemento no segundo e o Array original no terceiro.

### *.push()*
 Adicionar um ou mais elementos no final do array.
~~~javascript
let frutas = ['maçã', 'banana'];
frutas.push('laranja', 'uva');
console.log(frutas);  // Saída: ['maçã', 'banana', 'laranja', 'uva']
~~~~

### *.pop()*
 Remover o último elemento do array.
~~~javascript
let frutas = ['maçã', 'banana', 'laranja'];
let ultimaFruta = frutas.pop();
console.log(ultimaFruta); // Saída: 'laranja'
console.log(frutas);      // Saída: ['maçã', 'banana']
~~~~

### *.shift()*
 Remover o primeiro elemento do array.
~~~javascript
let frutas = ['maçã', 'banana', 'laranja'];
let primeiraFruta = frutas.shift();
console.log(primeiraFruta); // Saída: 'maçã'
console.log(frutas);        // Saída: ['banana', 'laranja']
~~~~

### *.unshift()*
 Adicionar um ou mais elementos ao início do array.
~~~~javscript
let frutas = ['banana', 'laranja'];
frutas.unshift('maçã', 'uva');
console.log(frutas); // Saída: ['maçã', 'uva', 'banana', 'laranja']
~~~~

### *.slice()*
 Retorna uma cópia do array , passando dois parâmetros:
 O primeiro onde deve começar.
 O segundo onde dever terminar.
~~~javascript
let frutas = ['maçã', 'banana', 'laranja', 'uva'];
let fatia = frutas.slice(1, 3);
console.log(fatia); // Saída: ['banana', 'laranja']
~~~~

### *.indexOf()*
 Retorna o primeiro index do elemento encontrado no array.
~~~javascript
let frutas = ['maçã', 'banana', 'laranja'];
let indice = frutas.indexOf('banana');
console.log(indice); // Saída: 1
~~~~

### *.includes()*
 Verificar se o elemento existe no array - retorna um boleano.
~~~javascript
let frutas = ['maçã', 'banana', 'laranja'];
let existe = frutas.includes('laranja');
console.log(existe); // Saída: true
~~~~

### Switch Case
 O comando switch case controla o fluxo do programa permitindo ao programador especificar código diferente para ser executado em várias condições. Em particular, um comando switch compara o valor de uma variável aos valores especificados nos comandos case.
~~~javascript
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
~~~

### Function
 Funções são blocos de construção fundamentais em JavaScript. Uma função é um procedimento de JavaScript - um conjunto de instruções que executa uma tarefa ou calcula um valor. Para usar uma função, você deve defini-la em algum lugar no escopo do qual você quiser chamá-la.

~~~javascript
let tartaruganinja = ["Donatelo", "Michelangelo", "Leonardo", "Rafael"]
function adicionar() {
  let digite = prompt("Surgiu uma nova tartaruga, que nome você dará a ela")
  return tartaruganinja.push(digite)
}
>alert(tartaruganinja)
~~~


## Atividades desenvolvidas
### Links das atividades no codepen
[Vídeo tik tok](https://drive.google.com/file/d/12-3PfLQqS4azbVkw05RTXPh5Z-d4sfwO/view?usp=sharing)

[Variaveis](https://codepen.io/Nats-the-animator/pen/RwzZVyv).

[Pedido](https://codepen.io/Nats-the-animator/pen/ZEdJPLv).

[Prompt](https://codepen.io/Nats-the-animator/pen/MWMvxzX).

[Números](https://codepen.io/Nats-the-animator/pen/wvLqZPm).

[Pedido Livro](https://codepen.io/Nats-the-animator/pen/PorOWyq).

[Loja Livros](https://codepen.io/Nats-the-animator/pen/zYVPZwe).

[Fundamentos JavaScript](https://codepen.io/Nats-the-animator/pen/eYwyZpo).

[Loja Livros 2](https://codepen.io/Nats-the-animator/pen/dyBdBEe).

[Function tartaruga ninja](https://codepen.io/Nats-the-animator/pen/xxvRYqq)

[Function inverter](https://codepen.io/Nats-the-animator/pen/RwXGjNX)

[Function meses](https://codepen.io/Nats-the-animator/pen/GRVZwwM)

[Function calculadora](https://codepen.io/Nats-the-animator/pen/oNrVvBg)

[Array 2D](https://codepen.io/Nats-the-animator/pen/dyBdBEe)

[Jogo](https://codepen.io/ed-the-scripter/pen/ExqYYvm)


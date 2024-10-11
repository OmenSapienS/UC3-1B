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

**Exemplo**
>var nomeDoHeroi = "Alex";

* **Let**: É como uma caixinha mais moderna. Ela é mais segura e fácil de usar do que a var.

**Exemplo**
>let pontuacao = 0;

+ **Const**: É como uma caixinha trancada. Você coloca algo dentro dela, mas depois não pode mais mudar o que está lá.

**Exemplo**
> const PI = 3.14;
> 
> console.log(PI); // Imprime "3.14"
> 
> PI = 3.15; // Irá gerar um erro, pois o valor de uma constante não pode ser alterado

### String
 Strings são sequências de caracteres alfanuméricos (letras, números e/ou símbolos) amplamente usadas em programação. Em Javascript, uma string sempre estará entre aspas.
> const frase = "Mergulhando em tecnologia com Alura";

 String que nos permite criar ou converter um tipo em uma string, veja o exemplo abaixo:

> const numero = 256
> 
> const convertidoEmString = new String(numero)

### Number
 O objeto JavaScript Number é um objeto encapsulado que permite você trabalhar com valores numéricos. Um objeto Number é criado utilizando o construtor Number(). Os principais usos para o objeto Number são: 
 Se o objeto não pode ser convertido para um número, é retornado NaN.
 Fora do contexo de um construtor (Ex., Sem o operador new, Number pode ser utilizador para realizar uma conversão de tipo.

### Boolean
 O valor passado como primeiro parâmetro é convertido para um valor boleano, se necessário. Se o valor é omitido ou é 0, -0, null, false, NaN, undefined ou é uma string vazia(""), o objeto terá um valor inicial de false. Todos outros valores, incluindo qualquer objeto ou string "false", criam um objeto com valor inicial true.

### Operadores lógicos e comparativos
 Os operadores lógicos são elementos fundamentais da linguagem de programação JavaScript. Eles permitem realizar operações de comparação e combinação de valores booleanos, ou seja, valores que podem ser verdadeiros (true) ou falsos (false). Basta colocar o sinal && entre as duas expressões que precisam ser comparadas.
> const a = true;
> 
>const b = false;
>
>console.log(a && b); // false

### Array 
 Os arrays são estruturas que servem para guardar dados, e organizá-los. Seu objetivo é ser um espaço fixo na memória do computador que armazena elementos. Esses elementos podem ser acessados por um tipo de indicação, que chamamos de índice. Você pode guardar seus chapéus na gaveta 1, suas calças na gaveta 2 e as meias na gaveta 3, e sempre que precisar de calças, chapéus ou meias, vai saber em que gaveta buscar.

>var listaDeFrutas = ['Maçãs','Uvas','Bananas','Abacaxi','Morangos'];
>
>//declarar o array

### Métodos Array
### *.forEach()*
 Caso você precise executar algum código para cada elemento do Array, executar um forEach é muito mais simples do que criar um for ou while, já que não precisamos declarar variáveis de controle. O .forEach() irá jogar cada um dos elemetos do Array no primeiro parâmetro, o índice do elemento no segundo e o Array original no terceiro.

### *.push()*
 Adicionar um ou mais elementos no final do array.

### *.pop()*
 Remover o último elemento do array.

### *.shift()*
 Remover o primeiro elemento do array.

### *.unshift()*
 Adicionar um ou mais elementos ao início do array.

### *.slice()*
 Retorna uma cópia do array , passando dois parâmetros:
 O primeiro onde deve começar.
 O segundo onde dever terminar.

### *.indexOf()*
 Retorna o primeiro index do elemento encontrado no array.

### *.includes()*
 Verificar se o elemento existe no array - retorna um boleano.

### Switch Case
 O comando switch case controla o fluxo do programa permitindo ao programador especificar código diferente para ser executado em várias condições. Em particular, um comando switch compara o valor de uma variável aos valores especificados nos comandos case.
>switch(expression) {
>  case x:
>
>    // code block
>
>    break;
>
>  case y:
>
>    // code block
>
>    break;
>
>  default:
>
>    // code block
>
>}

### Function
 Funções são blocos de construção fundamentais em JavaScript. Uma função é um procedimento de JavaScript - um conjunto de instruções que executa uma tarefa ou calcula um valor. Para usar uma função, você deve defini-la em algum lugar no escopo do qual você quiser chamá-la.

>let tartaruganinja = ["Donatelo", "Michelangelo", "Leonardo", "Rafael"]
>
>function adicionar() {
>  let digite = prompt("Surgiu uma nova tartaruga, que nome você dará a ela")
>
>  return tartaruganinja.push(digite)
>
>}
>
>alert(tartaruganinja)


## Atividades desenvolvidas
### Links das atividades no codepen
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


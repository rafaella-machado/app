## Linguagem de programação

Maneira de dar instrução ao computador.
Como um lego, você irá utilizar peças para criar algorítmos, ou seja, para resolver problemas.

**Algorítmo**: Sequência de passos lógica e finita para resolução de um problema.

## Peças de uma linguagem 

- [x]Comentários 
- Declaração de variáveis (const, let)
    - const -> o valor da variável não pode ser alterado
    - let -> o valor da variável pode ser alterado a qualquer momento
    EX:
    // hello word
     let mensagem = "hello, world!"
     console.log(mensagem);
     console.log(mensagem);
     console.log(mensagem);
     console.log(mensagem);
- Operadores (atribuição, concatenação, matemáticos, lógicos)
- Tipos de dados (string, number, boolean)
- Estrutura de dados (functions, object, array) 
EX1:
// arrays, objetos
let metas = ["rafaella", "alo"] //indices 0,1
console.log(metas[0]) // retorno -> rafaella
console.log(metas[0]+ metas[1]) // -> concatena, ou seja, junta os valores, o resultado neste caso fica: rafaellaalo
console.log(metas[1] + ", " + metas[0]) // -> concatena, ou seja, junta os valores, o resultado neste caso fica: alo, rafaella

EX2:
// arrays, objetos
let meta = { // todo objeto tem uma propriedade e valor
    value: 'Ler um livro por mês',
    checked: false // boleano
    log: (info) => {
        console.log(info)
    }

}

console.log(meta.value)

//function // arrow function atribuindo (sinal da flexa) a constante: criarMeta
const criarMeta = () => {}

function criarMeta() {}

- Controle de fluxo (if/else)
- Estrutura de repetição (for,while)

## Fases da resolução de um problema

Coletar os dados
Processar os dados (manipular, alterar...)
Apresentar os dados

## Escopo e variáveis:

- [x] Variáveis globais e locais -> O que estiver dentro de {} são vairáveis locais e o que estiver fora das chaves é variável global

- [x] Constantes 

## Tipos de dados:

- [x] Strings (textos): "" '' ``
- [x] Number: 2 1.4
- [x] Boolean: true,false

## Operadores

- [x] Operadores de atribuição de valor --> Representado pelo sinal de =
- [x] Operador de contatenação -> representa o sinal +

## Estruturar dados:

## Arrays:

- [x] Uma lista que contém qualquer tipo de dado

### Objetos:

- [x] Atributos e métodos
    -  o método é a mesma coisa que a function. Método está dentro do objeto e a função está fora do objeto   
- [x] Criação e manipulação de objetos
- [x] Acesso a propriedades de objetos

### Functions

- [x] criar, passar argumento
- [x] executar
- [x] arrow function / named function 

## Estrutura de repetição 
- [x] While

## Condicionais 
- [x] switch

## Modulos em Node.js
- [x] importação de módulos (require, commonJs)
- [x] biblioteca 'inquirer' para criar prompts interativos

## Programação assíncrona e Promises:
- [x]Uso de funções assíncronas (async/await)


## Anotações da aula

- While --> Estrutura de repetição
- return --> Dentro de qualquer função, ele para a execução da função

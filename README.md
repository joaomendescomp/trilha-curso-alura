# trilha-curso-alura
Repositório João Mendes - Projeto Trilhas ( Front End )

#### Desafio 1 - Respostas (12/02/2025)

Para o desafio 1 abaixo, utilize sua IDE e envie os códigos em um arquivo em .pdf ou link do Github. Responda as perguntas utilizando códigos em JavaScprit. 


1)	Crie uma variável chamada nome e atribua seu nome a ela. Em seguida, exiba o valor dessa variável.

```js
//Variavel chamada nome
let nome; 

//Atribuindo meu nome a variavel
nome = "João Pedro";

//Exibindo o valor da variavel
alert(`Olá, meu nome é ${nome}`);
```


2) Crie duas variáveis: uma chamada idade e outra chamada altura. Atribua a idade o valor 25 e a altura o valor 1.75. Exiba ambos os valores.

```js
//Criando duas variaveis idade e altura
let idade; 
let altura; 

//Atribuindo valores as variaveis
idade = 25;
altura = 1.75;

//Exibindo o valores das variaveis
alert("Idade: " + idade + ".\nAltura: " + altura);
```


3) Crie uma variável chamada preco com o valor 50 e uma variável desconto com o valor 0.2 (20%). Calcule o preço com desconto e exiba o valor final.

```js
//Criando duas variaveis preço e desconto
let preco = 50; 
let desconto = 0.2; 

//Criando variavel final e calculando o preco com desconto
let valorFinal;
valorFinal = preco-(preco*desconto);

//Exibindo o valor final
alert(`O valor Final com Desconto é : R\$ ${valorFinal}`);
```


4) Crie uma variável chamada temperatura e atribua o valor 30. Se a temperatura for maior que 25, exiba a mensagem "Está calor!". Caso contrário, exiba "Está fresco!".

```js
//Criando variavel temperatura 
let temperatura = 30; 

//Se a temperatura for maior que 25, exiba a mensagem "Está calor!"
if(temperatura > 25){
    alert('Está Calor');
    
} 
//Caso contrário, exiba "Está fresco!"
else{
    alert('Está Fresco ');
}
```


5) Crie uma variável idade e atribua um valor. Se a pessoa for maior de idade (18 ou mais), exiba "Você é maior de idade". Caso contrário, exiba "Você é menor de idade".

```js
//Criando variavel idade 
let idade = prompt('Digite a idade: ');

//Se for maior ou igual a 18 (maior de idade), se não (Menor de idade)
if (idade >= 18) {
    alert('Você é maior de idade'); 
} 
    else{

    alert('Você é menor de idade'); 
}
```


6) Crie uma variável chamada nota e atribua um valor entre 0 e 10. Se a nota for maior ou igual a 7, exiba "Aprovado". Se for entre 5 e 6, exiba "Recuperação". Caso contrário, exiba "Reprovado".

```js
//Criando variavel nota
let nota = prompt('Digite uma nota de 0 a 10: ');

//Se a nota for maior ou igual a 7 (aprovado)
if (nota >= 7) {
    alert('Aprovado'); 

    //Se a nota for entre 5 e 6 (Recuperaçao)
} else if(nota>= 5 && nota<=6 )
    
    {
     alert('Recuperação'); 
     
     //Senão (reprovado)
} else{

    alert('Reprovado'); 
}
```


7) Crie duas variáveis, numero1 e numero2, e atribua valores a elas. Verifique se os dois números são iguais e, caso sejam, exiba "Os números são iguais". Caso contrário, exiba "Os números são diferentes".

```js
//Criando duas variaveis número 1 e número 2
let numero1 = prompt('Digite número 1: ');
let numero2 = prompt('Digite número 2: ');

if (numero1 == numero2) {
    alert('Os números são iguais'); 
   
} else{

    alert('Os numeros são diferentes'); 
}
```


8) Crie uma variável chamada nome e uma variável chamada idade. Exiba a mensagem "Olá, meu nome é [nome] e eu tenho [idade] anos", utilizando concatenação.

```js
//Criando uma variavel nome e idade
let nome = prompt('Digite seu nome: ');
let idade = prompt('Digite sua idade: ');

alert (`Olá, meu nome é ${nome} e eu tenho ${idade} anos`);

//* Outra forma * //
//alert ("Olá, meu nome é "+nome+" e eu tenho " +idade+ " anos");
```


9) Crie um loop que imprima os números de 1 a 10 na tela.

```js
//Criando um loop que imprima os números de 1 a 10
let loop = 1;

while (loop <= 10) {

    alert(`Número: ${loop}`);

    loop++;
}
```


10) Crie um loop que peça ao usuário para digitar um número até que ele digite o número 5.

```js
//Crie um loop digitar um numero até digitar 5
let loop;

do {
  loop = prompt('Digite um número:');  
} while (loop != 5);  

alert('FIM : Você digitou o número 5!');  
```


11) Crie um loop que imprima a tabuada do número 7, de 1 a 10.

```js
// loop que imprima a tabuada do número 7, de 1 a 10.  
let n = 1;

while (n <= 10) {
let tabuada = 7 * n;
   
alert (`Tabuada: 7 x ${n} = ${tabuada}`);
n++;  
}
```


12) Crie um loop que exiba todos os números pares de 0 a 20.

```js
// loop para imprimir numero pares do 0 ao 20.  
let n = 0;

while (n <= 20) {

  alert(n); 

  n += 2;  
}
```


13) Escreva um código que calcule a área de um círculo. Utilize uma função para realizar o cálculo. A função deve receber o raio como parâmetro e retornar a área.

```js
// Calcular área de um círculo
let raio = prompt('Digite o raio de um círculo: '); 
let area = calcularArea(raio); //chamando a função

alert(`A área do círculo é: ${area}`);  

//Função para calcular a área
function calcularArea(raio) {

    return (3.14 * raio * raio); // Fórmula da área do círculo: Pi * r² 
}
```


14) Comente seu código explicando o que cada parte faz. Crie um programa simples que calcule a soma de dois números e imprima o resultado.

```js
// Programa para somar dois numeros e mostrar resultado

let numero1 = parseInt(prompt('Digite número 1: ')); // cria a variavel para guarda o primeiro numero

let numero2 = parseInt(prompt('Digite número 2: ')); // cria a variavel para guarda o segundo numero

let soma = (numero1 + numero2); // realiza a soma dos dois numeros e salva na variavel soma

alert(`O resultado da soma é: ${soma}`);  // imprime o resultado na tela
```


15) Refatore o código abaixo para que seja mais legível, usando boas práticas de nomenclatura e separando o código em funções:

```js
// Inicia o programa chamando a função principal
CalculaNumero(); 

function CalculaNumero(){
    let num1= 10;
    let num2 = 20;
    let resultado = somar(num1, num2);
    MostrarResultado(resultado); // chama a função pra imprimir
}

// função para imprimir
function MostrarResultado(resultado){
    console.log("A soma é : " +resultado);
}

// Função para somar dois números
function somar(numero1, numero2) {
    return numero1 + numero2;
  }
```

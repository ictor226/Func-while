// Se o paulo ver isso, eu dei uma boa explicada na 05 pois tive bastante duvida e tambem para eu ver futuramente :)


// - ATIVIDADE 01
// for (cont = 10; cont > -1; cont = cont - 1){
//   console.log(cont)
// }

// - ATIVIDADE 02
// var NumEsc = 0
// var NumEsc = prompt("Escolha um numero para sua tabuada: ")
// var NumEsc = parseInt(NumEsc)
//
// var resultado = 0
// for (tabuada = 1; tabuada <= 10; tabuada = tabuada + 1){
//   resultado = NumEsc + " x " + tabuada + " = " + (NumEsc * tabuada)
//   console.log(resultado)
// }
// console.log(resultado)
// O JAO PAULO AJUDOU DEU UMAS DICA NESSA 

// - ATIVIDADE 03
// soma = 0
//
// for (conta = 1; conta <= 100; conta = conta + 1) {
//     soma = soma + conta
// }
// console.log("A soma de todos os números de 1 a 100 é: " + soma)
// ryan ajudou muito nessa :)

// - ATIVIDADE 04
// for (par = 1; par <= 20; par = par + 1){
//   if (par % 2 == 0){
//     console.log(par)
//   }
// } 
// dei uma olhada em umas atv que eu usei a logica do par
  
// - ATIVIDADE 05 

var numEsc = parseInt(prompt("DIGITE UM NUMERO: "));

var fibonacci01 = 0;
var fibonacci02 = 1;


console.log(fibonacci01);// Ele Exibe o primeiro número da sequência que seia emdiante

// o for usa um loop para gerar a sequência de Fibonacci que faz ele nao acabar
for (var fibonacci = fibonacci02; fibonacci <= numEsc; ) {
    console.log(fibonacci); // aqui vai exibir o número atual da sequência, dar continuidade
    
    
var nextFibo = fibonacci01 + fibonacci02;// bom aqui vai calcular o próximo número na sequência que seria o resultado

// aqui vai atualizar os valores para a próxima iteração
fibonacci01 = fibonacci02;
fibonacci02 = nextFibo;
    
  //a variável vai farzer um loop
  fibonacci = fibonacci02;
}


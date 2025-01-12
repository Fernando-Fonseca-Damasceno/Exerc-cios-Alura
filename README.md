//Parte 1

let diaDaSemana = prompt("Qual é o dia da semana?");

if (diaDaSemana == "Sábado") {
    alert("Bom fim de semana!");
} else if (diaDaSemana == "Domingo") {
    alert("Bom fim de semana!");
} else {alert("Boa semana!");

}

//Parte 2

numero = prompt("Digite um número positivo ou negativo");

if(número > 0) {
    alert("Numéro positivo!");
} else {
    alert("Número negativo!");
}

//Parte 3

pontuação = 105;

if(pontuação >= 100) {
    console.log("Parabéns, você venceu!");
} else{
    console.log("Tente novamente para ganhar.");
}

//Parte 4

let saldoConta = 500; //exemplo de saldo
alert(`Seu daldo é de R$${saldoConta}.`);

//Parte 5

let nome = prompt("Qual é o seu nome?");
alert(`Boas vindas ${nome}`);

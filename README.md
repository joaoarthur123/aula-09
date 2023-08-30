// this is a js file
// joao arthur

let seuNome = prompt("qual o seu nome?");
let cor = prompt("qual sua cor preferida?");

console.log("a cor favorita de " + seuNome + "é" + cor);
console.log(` à cor favorita de ${seuNome} é ${cor} `);

console.log(seuNome.length);

const frase = "OieEeEee!";
const fraseMinuscula = frase.toLowerCase();
console.log(fraseMinuscula);
const fraseMaiuscula = frase.toUpperCase();
console.log(fraseMaiuscula);
const email = " mika@gmail.com";
console.log(email.trim());

const frase2 = "hoje comi peixe";
console.log(frase2.includes("peixe"));
console.log(frase2.includes("carne"));
const novaFrasee = frase2.replaceAll("peixe" , "ovo");
console.log(novaFrasee);

//exercicio2
const frase5 = "salve salve dex";
const frase6 = frase5.toUpperCase();
console.log(frase6);
const frase7 = "vamos jogar bola?";
const frase8 = frase7.replaceAll("o", "i");
console.log(frase8);
console.log(frase8.length);

const listaDeCompras = ["batata", "alface", "queijo"];
const listaDeNumeros = [2, 13, 26, 35, 41, 60];
const meuArray =["banana", 15, true];

const listaDeComprass =["abacate", "banana", "tomate"];
const segundoItem = listaDeCompras[2];
console.log(segundoItem);

const array = ["pitbull", "xiwawa", "pinscher", "pastor alemao"];
let cachorro = array[Number(prompt("escolha um numero 0 a 4"))];
console.log(cachorro);
const pokemon = ["bulbasauro", "aquirlete", "charmender"];
console.log(pokemon.length);
 
const seriesBoas = ["brooklyn99","cobra kai"];
console.log(seriesBoas.includes("cobra kai"));
console.log(seriesBoas.includes("ragnarok"));

const numeros = [1, 2, 3];
numeros.push(4);
console.log(numeros);
numeros.push(5, 6, 7);
console.log(numeros);

const meusPeixes = ["palhaço", "mandarim", "esturjao"];
meusPeixes.pop();
console.log(meusPeixes);

const letras = ["a", "b", "c" ,"d" ,"e", "f", "g", "h"];
letras.splice(2, 1);
console.log(letras);
letras.splice(3, 2);
console.log(letras);

const array7 = [1, 2, 3, 4, 5, 6];
console.log(array7.length);
array7.push(7);
console.log(array7);
array7.splice(3, 2);
console.log(array7);
console.log(array7.length);

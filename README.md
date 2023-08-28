# aula8
aula-8
*
//Exercicio 1

let nome = prompt("Qual seu nome?");
let cor = prompt("Qual a sua cor favorita?");

console.log("A cor favorita de " + nome +  " é "  +  cor);
console.log(`A cor favorita de ${nome} é ${cor}` );


//Retornar o numero de caracteries em uma string;
console.log(nome.length);

//Retornar a string convertida para minusculo;
console.log(nome.toLowerCase());

//Retornar a string convertida para maiusculo;
console.log(nome.toUpperCase());

//Retira os espaços ao redor da string;
console.log(nome.trim());

//Metodo para buscar determinado texto dentro de uma string;
console.log(nome.includes("Cenoura"));

//Troca o texto da string pelo texto fornecido;
//replaceALL("texto antigo"."texto novo");
console.log(nome.replaceAll("cenoura","batata"));


//Exercicio 2
let frase = prompt("Esceva uma frase?");

console.log(frase.toUpperCase());
console.log(frase.replaceAll("o","i"));
console.log(frase.length);


//Arrays 
let ListaDeExercicios = ["elevacao lateral", "supino", "voador"];
console.log(ListaDeExercicios[0]);
console.log(ListaDeExercicios[1]);
console.log(ListaDeExercicios[2]);
console.log(ListaDeExercicios);


//Exercicio 2
let RacasDeCachorros = ["Poodle", "Golden", "Chihuahua", "Chow-chow", "Yorkshire"];
let numero = Number(prompt("insira um numero de 0 a 4?"));
console.log(RacasDeCachorros[numero]);


 const pokemon = ["Bulbasauro", "squirtle", "charmader"];
 console.log(pokemon.length);
 console.log(pokemon[0].length);

 //--------

  const seriesBoas = ["Breaking bad", "Brooklyn Nine-nine"];
  console.log(seriesBoas.includes("Breaking bad"));
  console.log(seriesBoas.includes("Gema of Thrones")); //false 


let instrumentos = ["violao", "guitarra", "bateria"];
console.log(instrumentos);
instrumentos.push("teclado");
console.log(instrumentos);
instrumentos.pop();
console.log(instrumentos);
instrumentos.splice(2, 2);
console.log(instrumentos);


//Exercicio 4
let numeros = [1,2,3,4,5,6];
console.log(numeros);
console.log(numeros.length);
numeros.push(7);
console.log(numeros);
numeros.splice(3, 2);
console.log(numeros);
console.log(numeros.length);



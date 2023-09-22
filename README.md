# EscritaECodigo
//Exercicios De Escrita De Codigo
//a) A função não deve receber nenhum parâmetro e deve imprimir uma mensagem falando algumas informações sobre você, como: 
//Ola eu me chamo Marcelo Mafra, tenho 15 anos, moro em Rio Grande Do Sul e sou estudante;

const nome = prompt("digite seu nome:");
const idade = Number(prompt("digite sua idade:"))
const cidade = prompt("qual a sua cidade:")
const profissão = prompt("qual sua profissão:")
const frase = " meu nome é " + nome + " e tenho " + idade + " anos, " + " moro na cidade " + cidade + " e sonho em um dia me tornar um " + profissão

alert(frase);

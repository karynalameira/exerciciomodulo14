# exerciciomodulo14

1. Resolva as operações:
10 +  15 = 25
"10" + 2 = 12
"10" * 2 = 20
"10" / 3 = 3,33333333
"10" % 3 = 1
10 + true = 11
10 == "10" = true
10 === "10" = false
10 < 11 = true
10 > 12 = false
10 <= 10.1 = true
10 > 9.99 = true
10 != "dez" = true
10 + true = deztrue
10 + false = 10
10 * false = 0
true + true = true
10++ = 11
10-- = 9
1 & 1 = 1
1 & 0 = 0
0 & 0 = 0
1 & 0 = 0
0 / 1 = 0
5 + 5  == 10 = true
"5" + "5" == 10 = false
"5" * 2 > 9 = true
(10 + 10) * 2 = 40
10 + 10 * 2 = 30

2. Responda as perguntas de acordo com as variáveis.
var branco = "preto";
var preto = "cinza";
var cinza = "branco";
var carro = "preto";
var valor = "30000";
var prestacao = "750";

a) branco == "branco" false
b) branco == cinza false
c) carro === branco falso
d) var cavalo = carro == "preto" ? "cinza" : "marron; true
e) Quantas prestações são necessárias para pagar o valor do carro com uma entrada de 3.000? Demonstre a operação.

Resposta:

var valorCarro = 30000;
var valorPrestacao = 750;
var valorEntrada = 3000;

var valorQuantidadePrestacoes = (valorEntrada / valorPrestacao);
var quantidadeParcelas = (valorCarro / valorPrestacao);

console.log(valorQuantidadePrestacoes);
console.log(quantidadeParcelas);


https://jsfiddle.net/karynalameira/Lx4mf98b/4/

f) Somando as variáveis de cores é formada uma string de quantos caracteres?

16 caracteres

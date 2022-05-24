# SubtraçãoDeElementos
repositorio criado para documentar o algoritimo de subtração
================================================================
algoritmo "Subtração"

var
num1, num2: real

funcao SubtracaoElementos (elemento1, elemento2: real): real
var
subtracao : real
inicio
 subtracao <- elemento1 - elemento2
 
 retorne subtracao
fimfuncao
inicio
// Seção de Comandos
escreval ("Insira o numero 1: ")
leia (num1)
escreval ("Insira o numero 2: ")
leia (num2)

escreval ("A subtração dos dois elementos é igual a: ", SubtracaoElementos(num1, num2))
fimalgoritmo

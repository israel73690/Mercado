Algoritmo "MERCADO"

Var
   opcao, quantidade: inteiro
   total: real


Inicio
   escreval("===== Mercado =====")
   escreval("1- Arroz (R$5)")
   escreval("2- Feijão (R$4)")
   escreval("3- Leite (R$3)")
   escreval("4- Pão (R$1)")
   
   escreva("Escolha o produto: ")
   Leia(opcao)
   
   escreva("Digite a quantidade: ")
   Leia(quantidade)
   
   se opcao = 1 entao
   total <- quantidade * 5
   
   senao se opcao = 2 entao
   total <- quantidade * 4
   
   senao se opcao = 3 entao
   total <- quantidade * 3
   
   senao se opcao = 4 entao
   total <- quantidade * 1
   
   senao
   escreval("Produto inválido")
   
   fimse
   
   escreval("Total da compra: R$", total)


Fimalgoritmo

# Simulador-Bancario
Algoritmo Simulador Bancário 
Algoritmo "Banco"
Var
   SaldoDisponivel:real
   ValorDosaque:Real
   MSG:Caractere
   Nome:Caractere
Inicio
   SaldoDisponivel:=2000//Assumimos que há 2000 de saldo na conta disponivel
   MSG<-"   BANCO LEGAL FEITO PRA VOCÊ  "
   Escreval(" Bom Dia ",MSG)
   Escreva("Digite seu nome: ")
   leia(nome)
   Escreva(" Muito prazer ",Nome)
   escreva("        informe o valor do Saque:        ")
   Leia(ValordoSaque)
   SE (ValorDoSaque)<= SaldoDisponivel ENTAO
      SaldoDisponivel := SaldoDisponivel-ValorDoSaque
      Escreval("      Sancando R$ ",ValorDoSaque,"."    )
   SENAO
      Escreval(" O valor Solicitado é maior que o valor Disponivel para sangue!")
   fimse
   Escreval("    Saldo Disponivel:R$   ", SaldoDisponivel)
Fimalgoritmo

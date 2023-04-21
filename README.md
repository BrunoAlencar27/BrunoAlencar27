Algoritmo "SomaParesImparesMediaParesImpares"
// Disciplina   : [Lógica de programação] 
// Professor   : Bruno Alencar Alves
Var
cont:real
soma:real
media:real
maior:real
menor:real
aluno:caractere
q:real
nota:real
Inicio
Escreva ("Quanto alunos serão calculado: ")
        Leia(q)
        cont<-1
        soma<-0
enquanto cont<=q faca
         Escreva ("Qual o nome do", cont, "o. aluno: ")
         Leia (aluno)
         Escreva ("Qual a nota de ", aluno, ": ")
         Leia (nota)
se cont=1 então
         menor<-nota
         maior<-nota
fimse
          se nota>maior então
         maior<-nota
fimse
        se nota<menor então
        menor<-nota
fimse
        soma<-soma+nota
        media<-soma/cont
cont<-cont+1
fimenquanto
       Escreval ("A maior nota foi ", maior)
       Escreval ("A menor nota foi ", menor)
       Escreval ("A média dessas notas foi", media)
Fimalgoritmo

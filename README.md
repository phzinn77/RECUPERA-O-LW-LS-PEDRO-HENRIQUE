# RECUPERA-O-LW-LS-PEDRO-HENRIQUE

algoritmo "Exemplo16"
// Função:
// Autor : 
// Data : 
// Seção de Declarações
var
 nome : caractere
 nota1, nota2, nota3, media : real
inicio
// Seção de Comandos
escreval ("Informe o nome do aluno: ")
leia (nome)
escreval ("Informe a primeira nota: ")
leia (nota1)
escreval ("Informe a segunda nota: ")
leia (nota2)
escreval ("Informe a terceira nota: ")
leia (nota3)
media <- (nota1 + nota2 + nota3) / 3
se media >= 7 entao
escreval ("O aluno ", nome, " está aprovado. A média foi: ", media)
fimse
se media <= 5 entao
escreval ("O aluno ", nome, " está reprovado. A média foi: ", media)
fimse
se (media >= 5.1) e (media <= 6.9) entao
escreval ("O aluno ", nome, " está de recuperação. A média foi: ", media)
fimse
fimalgoritmo
variavel = "valor"
variavel2 = 20

# ler valores
nome = input("Texto")

# ler numero
numero = int(input("Texto"))

# condicional

if numero > 100:
	#codigo do if
	print("Dentro de if")

elif numero > 50:
	#outra condicao

else:
	#resto do if


# loop de 1 a 10

#imprime: 0, 1, 2, 3, 4, 5, 6, 7, 8, 9
for i in range(0, 10):
	print(i)


# array
valores = [1, 2, 3]

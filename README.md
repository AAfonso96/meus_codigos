# meus_codigos
Códigos pessoais de estudo

#DESCOBRIR SE UM NÚMERO É PRIMO(python)

a = int(input("digite um número: "))
div = 0
for x in range(1, a+1):
  resto = a % x
  if resto == 0:
    div += 1

if div == 2:
  print(a, "É um número primo.")
else:
  print(a, "Não é um número primo.")

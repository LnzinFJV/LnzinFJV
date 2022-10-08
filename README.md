Questão 3 lista 2 

numero = float(input("Digite um número: "))
if numero % 1 == 0:
    print("Inteiro")
else:
    print("Decimal")
   
  
Questão 2 da lista 2 


numero = float(input('Digite um número para saber se é par ou impar:'))
resto = numero % 2

if resto == 0:
    print('Número é par')
else:
    print('Número é impar')
    
    
Questão 4 lista 1



tamanho = int(input( ‘ tamanho em metros quadrados: ,))
litros = tamanho / 3

If tamanho % 54 == 0:
               latas = tamanho / 54
else:
               latas = int(tamanho / 54) + 1

preco = latas * 80
print ( ‘%d latas’ % latas)
print ( ‘R$ %. 2f’ % preco)


Questão 2  lista 1
peso_peixes = eval(input(‘ Digite o peso dos peixes’))
If peso_peixes > 50:
  peso_excesso = peso_peixes-50
  multa = 4 * peso_excesso
  print(f’ Hoje João pescou {peso_peixes} Kg de peixes, {peso_excesso}Kg a mais que o estabelecido pelo regulamento  é isso gerou uma multa de R${multa:.2f}’)
else:
   print(f’Hoje Joao pescou {peso_peixes}kg de peixes, esta dentro do limite estabelecido pelo regulamento’)
   
   
   Questão 5  lista 1


import math

medida = float(input(“Digite quantos metros quadrados: “))
litros = medida / 6
latas = math.ceil(litros / 18
galões = math.ceil(litros / 3.6)
preco _latas = latas * 80
preco_galoes = galoes * 25
combinação = (litros // 18) * 80 + math.ceil(((litros % 18) / 3.6)) * 25

print(“o preco so com latas e:, preco_latas)
print(“o preco so com galoes e:, preco_galoes)
print(“o preco so com a combinacao e:”, combinacao)

Questão 5 da  lista 2
soma_dos_quadrados = 0
for i in range(10):
    soma_dos_quadrados += int(input(f"Digite o {i+1}º numero inteiro: ")) ** 2
print(f"A soma dos quadrados dos numeros digitados é {soma_dos_quadrados}")



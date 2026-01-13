# Variáveis
Velocidade_internet = 400
print (Velocidade_internet)

# Número inteiros(int)
idade = 15

# Número decimais(Float)
nota = 8.5

# Textos(strings)(str)
nome_completo = 'Denis de Souza'

# Booleanos(True ou False)(Bool)
pode_entrar = False

print (type(pode_entrar))

# Problema 1 - Valor hora
# Escreva um programa que retorna o valor hora de um funcionário
# com base no seu salário mensal e horas trabalhadas por mês.

# Método 5Q's para montar um algorítimo:

# Análise criticamente o problema e descubra:
# (Tente explicar este problema para você mesmo em voz alta e peça mais informações/investigue mais até você comprrender completamente o problema.)

# 1. Quais são os dados da entreda necessários?
    # Salário mensal
    # Qunatidade de horas trabalhadas

# 2. O que deve fazer com estes dados?
    # Calcular o valor hora

# 3. Quais são as restrições deste problema?
    # Precisa ter um valor do salário mensal
    # Precisa ter um valor da qunatidade de horas trabalhadas

# 4. Qual é o resultado esperado?
    # Exibir o valor hora da pessoa, com base no cálculo de valor hora

# 5. Qual a sequência de passos a ser feita para chegar ao resultado esperado? (pseudocódigo)
    # Receber salário mensal
    # Receber quantidade de horas trabalhadas
    # Valor hora = salário mensal / quantidade de horas de trabalho
    # Exibir valor hora

# Modelo inserir

salario_mensal = input('Qual é o seu salário mensal: ')
horas_trabalhadas = input ('Quantas horas você trabalha pro mês: ')
valor_hora = float (salario_mensal) / float (horas_trabalhadas)
print (valor_hora)

# Modelo manual

nome_completo = 'Pedro Santos'
valor_hora = 19 
quantidade_de_horas = 180
print (valor_hora * quantidade_de_horas)

# Parte 2
# E ae Jhonatan, bora dar uma saida hoje?
# Se eu terminar meu trabalho aqui eu consigo.

trabalho_terminado = False
if trabalho_terminado == True:
    print ('Acabei meu trabalho, boraa!!')
else:
    print('Não posso sair...')


conseguir_dinheiro = True
if conseguir_dinheiro == False:
    print ('Não consegui o dinheiro...')
else:
    print ('Consegui o dinheiro!!!')


trabalhar = input('Você foi trabalhar? s/n ')
if trabalhar == 's':
    print ('Consegui o dinheiro!!')
else:
    print ('Não consegui o dinheiro...')

# sintaxe 
#   if condição:
#       / código se verdadeiro
#   else
#       / código em qualquer outro caso


# Eu cheguei atrasado na aula. Ainda posso entrar?
# Se for a primeira ou segunda vez que você chega atrasado, pode sim.
# Mas se for a terceira vez, você sera suspenso.

atrasos = int(input('Quantas faltas você tem? '))
if atrasos >= 3:
    print('Você está suspenso! ')
elif atrasos == 2:
    print('Mais uma falta você está suspenso! ')
elif atrasos == 1:
    print('Mais duas falta você está suspenso! ')
else:
    print('Pode entrar! ')

# Crie um programa que recebe dois valores e exibe qual é o maior entre eles.

valor_1 = 200
valor_2 = 100
if valor_1 < valor_2:
    print('Valor 1 é o maior')
else:
    print('Valor 2 é o maior')


valor_1 = int(input('Qual o valor 1: '))
valor_2 = int(input('Qual o valor 2: '))
if valor_1 > valor_2:
    print('Valor 1 é o maior')
elif valor_1 == valor_2:
    print('Os valores são iguais')
else:
    print('Valor 2 é o maior')

#laços de repetição

for item in range (5):
  print(item)

for item in range (5):
    print (item) 

#Lista de nomes

nomes = ['joao, amanda, pedro']
dados = ['1', 'rafael', 'true', '2.5']
for nome in nomes:
    print(nome)
for dado in dados:
    print(dado)


# Exiba somente os maiores de idade na tela~

idades = [13, 15, 18, 50, 30, 35]
for idade in idades: 
    if idade >= 18:
        print(f' {idade} é maior de idade' )
    else:
        print(f' {idade} é menor de idade' )


# len(variavel) -> quantidade de caracteres
# lem(senha) -> 6 ou não

senhas = ['dezembro', 'seguradora 123', '12345', 'python 123', 'dia' ]
for senha in senhas:
    if len(senha) >= 6:
        print(f'Senha {senha} válida')
    else:
        print(f'A senha {senha} deve possuir no mínimo 6 caracteres')

# Cria um programa que permite 3 tentativas, antes de fechar

tentativas = 0
while tentativas < 3:
    print('tente novamente')
    tentativas = tentativas + 1

# Quando queremos que uma ação continue acontecendo ate 
# que um critério seja satisfatório
# So pode logar, se digitar a senha correta

senha = ''
while senha != '123456':
    senha = input('Digite a senha correta: ')

print('Bem vindo ao sistema! ')

# garantir que algo esteja preenchido
# Só deve continuar, quando o usuário informar seu nome

nome = ''
while nome == '':
    nome = input('Digite seu nome: ')
print(f'Bem vindo {nome}')

# Contadores dentro do while
# Ser avisado as 17hrs do por do sol
# Contar de hora em hora até chegar as 17hrs
# Ao chegar as 17hrs, exibir: 'hora de ver o por do sol'

horario = 0
while horario <= 17:
    print(horario)
    horario = horario + 1
print('hora de ver o por do sol')

usuario = ''
senha = ''
tentativas = 0

while (usuario != 'pedro' and senha != '1020'):
    tentativas < 3
    usuario = input('Digite seu usuário: ')
    senha = input('Digite sua senha: ')
    tentativas += 1
if usuario != 'pedro' and senha != '1020':
    print ("Aguarde 30 minutos para tentar novamente.")
else:
    print('Login feito com sucesso!')

#listas
# Encontar índice automaticamente

preços = [20, 50, 100]
print(preços[1])

nomes = ['Brasil', 'EUA', 'Canadá']
print (nomes[2])
print (nomes.index('EUA'))

# Manipular - add novos itens

salarios = [2500, 4000, 5000]
salario_usuario = float(input('Qual é o seu salário: '))
salarios.append(salario_usuario)
print(salarios)

salarios = [2500, 950, 5000, 7500]
total = 0
for salario in salarios:
    total = total + salario
print(total)

# Projeto 1 - Fatorial de um número
# Crie um programa que recebe um número e imprime o seu fatorial

numero = int(input('Digite o fatorial que deseja calcular: '))
if numero > 0 and type(numero) == int:
    fatorial = 1
    for item in range(1, numero + 1):
        print(f'{fatorial} * {item}')
        fatorial = fatorial * item
        print(f'{fatorial}')
    print(f'o faotrial de {numero} é {fatorial} ')
else:
    print('favor informar un número inteiro e positivo')

# Projeto 2 - Chute o número

import random

valor_aleatorio = random.randint(1,10)
acertou = False

while acertou == False:
    chute = int(input('Chute um número: '))
    if chute > valor_aleatorio:
        print('Chute um valor mais baixo')
    elif chute < valor_aleatorio:
        print('Chute um valor mais alto')
    else:
        print('Você acertou!')
        acertou = True

# Calcule a velocidade

velocidade = float(input('Digite a velocidade: '))
velocidade_maxima = 80
if velocidade <= velocidade_maxima:
    print('Não houve multa')
elif velocidade <= velocidade_maxima + 10:
    print('Multa leve')
elif velocidade <= velocidade_maxima + 20:
    print('Multa grave')
elif velocidade <= velocidade_maxima +30:
    print ('Multa gravissíma')
else:
    print('Multa gravíssima com suspensão de carteira') 

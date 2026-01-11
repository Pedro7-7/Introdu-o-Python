# # Variáveis
# Velocidade_internet = 400
# print (Velocidade_internet)
# # Número inteiros(int)
# idade = 15
# # Número decimais(Float)
# nota = 8.5
# # Textos(strings)(str)
# nome_completo = 'Denis de Souza'
# # Booleanos(True ou False)(Bool)
# pode_entrar = False

# print (type(pode_entrar))

# # Problema 1 - Valor hora
# # Escreva um programa que retorna o valor hora de um funcionário
# # com base no seu salário mensal e horas trabalhadas por mês.

# # Método 5Q's para montar um algorítimo:

# # Análise criticamente o problema e descubra:
# # (Tente explicar este problema para você mesmo em voz alta e peça mais informações/investigue mais até você comprrender completamente o problema.)

# # 1. Quais são os dados da entreda necessários?
#     # Salário mensal
#     # Qunatidade de horas trabalhadas

# # 2. O que deve fazer com estes dados?
#     # Calcular o valor hora

# # 3. Quais são as restrições deste problema?
#     # Precisa ter um valor do salário mensal
#     # Precisa ter um valor da qunatidade de horas trabalhadas

# # 4. Qual é o resultado esperado?
#     # Exibir o valor hora da pessoa, com base no cálculo de valor hora

# # 5. Qual a sequência de passos a ser feita para chegar ao resultado esperado? (pseudocódigo)
#     # Receber salário mensal
#     # Receber quantidade de horas trabalhadas
#     # Valor hora = salário mensal / quantidade de horas de trabalho
#     # Exibir valor hora

# # Modelo inserir
# salario_mensal = input('Qual é o seu salário mensal: ')
# horas_trabalhadas = input ('Quantas horas você trabalha pro mês: ')
# valor_hora = float (salario_mensal) / float (horas_trabalhadas)
# print (valor_hora)

# # Modelo manual
# nome_completo = 'Pedro Santos'
# valor_hora = 19 
# quantidade_de_horas = 180
# print (valor_hora * quantidade_de_horas)

# # Parte 2
# # E ae Jhonatan, bora dar uma saida hoje?
# # Se eu terminar meu trabalho aqui eu consigo.

# trabalho_terminado = False
# if trabalho_terminado == True:
#     print ('Acabei meu trabalho, boraa!!')
# else:
#     print('Não posso sair...')


# conseguir_dinheiro = True
# if conseguir_dinheiro == False:
#     print ('Não consegui o dinheiro...')
# else:
#     print ('Consegui o dinheiro!!!')


# trabalhar = input('Você foi trabalhar? s/n ')
# if trabalhar == 's':
#     print ('Consegui o dinheiro!!')
# else:
#     print ('Não consegui o dinheiro...')

# # sintaxe 
# #   if condição:
# #       / código se verdadeiro
# #   else
# #       / código em qualquer outro caso


# # Eu cheguei atrasado na aula. Ainda posso entrar?
# # Se for a primeira ou segunda vez que você chega atrasado, pode sim.
# # Mas se for a terceira vez, você sera suspenso.

# atrasos = int(input('Quantas faltas você tem? '))
# if atrasos >= 3:
#     print('Você está suspenso! ')
# elif atrasos == 2:
#     print('Mais uma falta você está suspenso! ')
# elif atrasos == 1:
#     print('Mais duas falta você está suspenso! ')
# else:
#     print('Pode entrar! ')

# # Crie um programa que recebe dois valores e exibe qual é o maior entre eles.

# # valor_1 = 200
# # valor_2 = 100
# # if valor_1 < valor_2:
# #     print('Valor 1 é o maior')
# # else:
# #     print('Valor 2 é o maior')


# valor_1 = int(input('Qual o valor 1: '))
# valor_2 = int(input('Qual o valor 2: '))
# if valor_1 > valor_2:
#     print('Valor 1 é o maior')
# elif valor_1 == valor_2:
#     print('Os valores são iguais')
# else:
#     print('Valor 2 é o maior')

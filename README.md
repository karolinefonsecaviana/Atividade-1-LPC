# Atividade-1-LPC
#ETE PORTO DIGITAL
#LPC - introdução a pynton
#Prof. Cloves Rocha
#Estudante: Karoline Fonseca

A="olá mundo"
print(A)

numero = int(input('Digite um número:'))
print(f'O número informado foi {numero}.')
print(type(numero))

num1 = int(input('Digite um número:'))
num2 = int(input('Digite outro número:'))
X = num1+num2
print(X)

N1 =  float (input('Digite sua primeira nota:'))
N2 =  float (input('Digite sua segunda nota'))
N3 =  float (input('Digite sua terceira nota'))
N4 =  float (input('Digite sua quarta nota'))
X = N1+N2+N3+N4
Media = X/4
print(Media)

Metros = float(input('Digite quantos metros:'))
centrimetros = Metros*100 
print(centrimetros)

R = float(input('Digite o raio do círculo:'))
pi = 3.14
X = pi*R**2
print(X)

lado = float(input('Digite o lado do quadrado:'))
A = lado**2
X = 2*A
print(X)

g = float(input('Digite o quanto ganha por hora:'))
h = int(input("Digite o número de horas que trabalha no mês"))
X = g*h
print(X)

num = int(input('Digite um número:'))
if num>0:
  print('Este número é positivo')
else:
  print('Este número é negativo')

sexo = input('Digite uma letra (em maiúsculo):')
if sexo == 'F':
   print('sexo feminino')
elif sexo == 'M':
  print('sexo masculino')
else:
  print('sexo inválido')

letra = input('Digite uma letra (em maiúsculo):')
if letra == 'A' or letra == 'E' or letra == 'I' or letra == 'O' or letra == 'U':
    print('Esta letra é uma vogal')
else:
    print('Esta letra é uma consoante')

# CALCULO-DO-IMC2
nome = 'João Paulo'
idade = 29
altura = 1.80
peso = 140
imc = peso/altura**2

nome = input('Digite seu nome ')
idade = input('Sua idade  ')
altura = float(input('Digite sua altura '))
peso = float(input('Digite seu peso '))
imc = peso/altura**2
print(f"'Seu imc é  {imc:.2f}")

if (imc > 40.0 ):
  print('Obesidade grau III')
  print('Obrigado pelas informações')
elif (imc > 35.0 and imc < 39.9):
  print('Obesidade grau II')
  print('Obrigado pelas informações')
elif (imc > 30.0 and imc <34.9):
  print('Obesidade grau I')
  print('Obrigado pelas informações')
elif (imc > 25.0 and imc < 29.9):
  print('Sobrepeso')
  print('Obrigado pelas informações')
elif (imc > 18.6 and imc <24.9):
  print('Normal')
  print('Obrigado pelas informações')
elif (imc < 18.5):
  print('Abaixo do Normal')
  print('Obrigado pelas informações')
else:
  print('Obrigado pelas informações')

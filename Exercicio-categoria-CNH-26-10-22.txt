## Entrada de dados com atribuição de variáveis e
## Conversão de string para numerico ##
print("Por favor responda abaixo as perguntas do veículo")
rodas   = int(input("Quantidade de rodas: "))
pessoas = int(input("Quantidade de pessoas no veículo: "))
peso    = int(input("Peso bruto em Kg: "))
## Inicio da estrutura condicional e
## saída de Dados
if (rodas == 2 or rodas == 3):
  print ("Habilitação categoria A")
elif (rodas == 4 and pessoas <= 8 and peso <= 3500):
  print ("Habilitação categoria B")
elif (rodas >= 4 and (peso >= 3500 and peso <= 6000)):
  print ("Habilitação categoria C")
elif (rodas >= 4 and pessoas > 8 and peso <=6000):
  print ("Habilitação categoria D")
elif (rodas >= 4 and peso > 6000):
  print ("Habilitação categoria E")
# folha-de-pagamento
import math 
salario=float(input("digite o seu salario: "))
valevale=input("descontar o vale transporte?")
if salario <1320: 
  inss= salario*0.075
  print (f"calculo do INSS r${inss}")
  print ("Seu salario liquido é de: R$",(salario-inss))
elif salario <2571:
  inss=salario*0.09
  print (f"calculo do INSS R${inss}")
  print ("Seu salario liquido é de: R$ ",(salario-inss))
elif salario <3856:
    inss=salario*0.012
    print (f"calculo do INSS R${inss}")
    print ("Seu salario liquido é de: R$ ",(salario-inss))
elif salario >7507:
    inss=salario*0.014 
    print(f"calculo do INSS R${inss}")
    print ("Seu salario é de: R$",(salario-inss))
elif salario >3856.95:
    inss = 876.95
    print (f"Calculo do INSS R${inss}")
    print ("Seu salario liquído é de: R$", (salario-inss))
if salario == "s" or valevale == "S":
   valevale= salario-salario*valevale
   print(f"desconto de vale transporte é de: R${valevale}")
   print ("seu salario liquido é de: R$")
   

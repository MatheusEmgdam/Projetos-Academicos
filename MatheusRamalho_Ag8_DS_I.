#Biblioteca
import os

#Variáveis e funções
def clear():
     os.system('cls' if os.name == 'nt' else 'clear')

excelente = 0 
ruim = 0
entrevistados = 10

for i in range(entrevistados):
    #INPUT
    nome=input("Digite o seu nome: ")
    while True:
        try: 
            idade=int(input("Digite sua idade: "))
            if 0<idade<120:
                break
            else:
                print("Digite uma idade entre 1 e 120 anos")
        except ValueError:
            print("Digite um número válido como idade")
    print("Como foi seu atendimento?\n")
    feedback=input("1-Excelente\n2-Bom\n3-Ruim\n")
    clear()
    
    #Avaliação do Feedback
    match feedback.lower():
        case "1" | "excelente":
            excelente+=1
        case "3" | "ruim":
            ruim+=1
        case _:
            pass

#OUTPUT
print(f"Feedback de Avaliações:\n Excelentes:{excelente}\nRuins:{ruim}")

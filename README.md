import random
numero_secreto = random.randint(1, 100)
tentativas = 0

while True:
    palpites = int(input("Tente adivinhar um número de (1 a 100): "))
    tentativas += 1
    if palpites == numero_secreto:
        print(f"Parabéns! Você acertou em {tentativas} tentativas.")
        break
    elif palpites < numero_secreto:
     print("o número é maior.")
    else:
     print("o número é menor")

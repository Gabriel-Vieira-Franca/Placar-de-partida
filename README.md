# Placar-de-partida
timeA= input( "Nome do time A: ")
golstimeA= int(input ("Quantos gols o time A fez: "))
timeB= input( "Nome do tima B: ")
golstimeB = int(input ("Qunatos gols o time B fez: "))

if golstimeA > golstimeB:
    print (f"{timeA} venceu com diferença de {golstimeA- golstimeB} gols.")
elif golstimeA < golstimeB:
    print (f" {timeB} venceu com diferença de {golstimeB-golstimeA} gols.")
elif golstimeA == golstimeB:
    print ("O jogo terminou empatado.")

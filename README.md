#Codigo Creado Por Ramirez Torres Angel Manuel De 3°W
- Escribe un programa que almacene un número y pida al usuario adivinarlo.
![image](https://github.com/user-attachments/assets/59c1ed28-c1a1-4d6b-b96f-0bad6d9f120d)
![image](https://github.com/user-attachments/assets/eb294695-219b-4de0-ad54-2bb4813c0a98)

import random
print(" ")#Espacio entre texto 
print("Ramirez Torres Angel Manuel 3°W trabajos_en_clase")
print(" ")#Espacio entre texto 

print("-INSTRUCCIONES-")#Muestra las instrucciones del programa
print("Escribe un programa que almacene un número y pida al usuario adivinarlo")

#Genera un numero aleatorio entre el 1 y el 100
numero_secreto = int(random.randrange(1, 100))

#Inicia el numero de intentos 
intentos = 3

print("Se ha seleccionado un numero entre el 1 y el 100 ")
print("!IMTENTA ADIVINARLO¡")

#Aqui pide al usuario que intente adivinar el numero 
while True:
    adivinanza = int(input("Introduce el numero que crees que sea: "))
    intentos += 0
        #Verifica el numero que escogiste
    if adivinanza < numero_secreto:
        print("Demasiado bajo tu numero. Vuelve a intentar")
    elif adivinanza > numero_secreto:
        print("Demasiado alto tu numero. Vuelve a intentar")
    else:
        print("!FELICIDADES¡ Adivinaste el numero {numero_secrto} en {intentos} intentos.")

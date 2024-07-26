import random
Characters = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

password = int(input("Introduce la longitud de la contraseña: "))

count = ""
for i in range(password):
    letra = random.choice(Characters)
    count = count + letra
    
print("La contraseña generada es:",count)



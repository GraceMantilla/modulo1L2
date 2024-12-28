# modulo1L2
import random
carac_esp = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
longitud = int(input('Ingrese la longitud de de la contraseña:'))
contra = ''
for i in range (longitud):
    contra += random.choice(carac_esp)
print(contra)

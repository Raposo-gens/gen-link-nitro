import random
import string

def gerar_codigo(codigos_gerados):
    letras_numeros = string.ascii_letters + string.digits

    while True:
        codigo = ''.join(random.choices(letras_numeros, k=8))

        if codigo not in codigos_gerados:
            return codigo

def gerar_codigos(quantidade):
    codigos_gerados = set()
    while len(codigos_gerados) < quantidade:
        codigos_gerados.add(gerar_codigo(codigos_gerados))
    return codigos_gerados

print("bem vindo ao: (welcome to:)")
print("--------------------------------------------------------------")
print("░█░░░█░██░█░█░█░")
print("░█░░░█░█░██░██░░")
print("░███░█░█░░█░█░█░")
print("░██░░░█░█░█████░███░░░███░░░░░░████░░████░██░░░█░")
print("░█░█░░█░█░░░█░░░█░░█░█░░░█░░░░█░░░░░░█░░░░█░█░░█░")
print("░█░░█░█░█░░░█░░░███░░█░░░█░░░░█░░██░░███░░█░░█░█░")
print("░█░░█░█░█░░░█░░░█░░█░█░░░█░░░░█░░░█░░█░░░░█░░█░█░")
print("░█░░░██░█░░░█░░░█░░█░░███░░░░░░███░░░████░█░░░██░")

print("by sr.raposo on viniciusrinaldi")
print("--------------------------------------------------------------")

print("how many nitro link you want generate?")
quantidade = int(input("Quantas key steam você gostaria de gerar? "))
codigos_gerados = gerar_codigos(quantidade)

dc = "https://discord.gg//"

for codigo in codigos_gerados:
    print(dc + codigo)
    
if quantidade == 1:
    print(quantidade, "link de nitro foi gerado com sucesso!")
else:
    print(quantidade, "links de nitro foram geradas com sucesso!")

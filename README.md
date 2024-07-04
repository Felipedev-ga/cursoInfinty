
numeros = []
pares = []
impares = []


for i in range(10):
    valor = int(input(f"Digite o {i+1}º valor: "))
    numeros.append(valor)


for numero in numeros:
    if numero % 2 == 0:
        pares.append(numero)
    else:
        impares.append(numero)


quantidade_pares = len(pares)
quantidade_impares = len(impares)
soma_pares = sum(pares)
soma_impares = sum(impares)

print(f"Números pares: {pares}")
print(f"Números ímpares: {tuple(impares)}")
print(f"Quantidade de números pares: {quantidade_pares}")
print(f"Quantidade de números ímpares: {quantidade_impares}")
print(f"Soma dos números pares: {soma_pares}")
print(f"Soma dos números ímpares: {soma_impares}")

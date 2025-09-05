

# exercicios.py

# 1. Função dobro
def dobro(numero):
    return numero * 2

# Testes da função dobro
print("Dobro de 5:", dobro(5))
print("Dobro de 10:", dobro(10))
print("Dobro de -3:", dobro(-3))


# 2. Mensagem personalizada
nome = input("Digite seu nome: ")
idade = input("Digite sua idade: ")
print(f"Seja bem-vindo(a), {nome}! Você tem {idade} anos.")


# 3. Lista de frutas
frutas = ["Maçã", "Banana", "Laranja", "Morango", "Abacaxi"]
print("As três primeiras frutas da lista são:", frutas[:3])


# 4. Dicionário livro
livro = {
    "título": "1984",
    "autor": "George Orwell",
    "ano": 1949
}
print("Autor do livro:", livro["autor"])


# 5. Soma dos números pares
def soma_pares(lista):
    return sum(numero for numero in lista if numero % 2 == 0)

# Teste da função soma_pares
numeros = [1, 2, 3, 4, 5, 6]
print("Soma dos números pares:", soma_pares(numeros))

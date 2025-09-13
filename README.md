[Calcular_media_simples.py](https://github.com/user-attachments/files/22314821/Calcular_media_simples.py)

# Calcular media simples
"""
Este script solicita ao usuário três notas, calcula a média simples entre elas e exibe o resultado.

Fluxo:
1. Solicita ao usuário que digite três notas (valores numéricos).
2. Calcula a média aritmética das três notas.
3. Exibe a média calculada.
4. Exibe a mensagem "FIM" ao final da execução.

Uso:
Execute o script e insira os valores solicitados quando solicitado.


"""

nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))
nota3 = float(input("Digite a terceira nota: "))

media = (nota1 + nota2 + nota3) / 3

print("A média é:", media)

print("FIM")

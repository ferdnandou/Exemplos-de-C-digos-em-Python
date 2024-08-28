# Calculadora Básica

Este script realiza operações matemáticas básicas (adição, subtração, multiplicação, divisão) entre dois números fornecidos pelo usuário.

## Código

```python
# Leitura dos números e operação
numero1 = float(input("Digite o primeiro número: "))
numero2 = float(input("Digite o segundo número: "))
operacao = input("Digite a operação (+, -, *, /): ")

# Realização da operação
if operacao == '+':
    resultado = numero1 + numero2
elif operacao == '-':
    resultado = numero1 - numero2
elif operacao == '*':
    resultado = numero1 * numero2
elif operacao == '/':
    if numero2 != 0:
        resultado = numero1 / numero2
    else:
        resultado = "Erro: Divisão por zero"
else:
    resultado = "Operação inválida"

# Exibição do resultado
print(f"Resultado: {resultado}")

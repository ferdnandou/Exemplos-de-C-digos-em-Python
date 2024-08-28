```markdown
# Cálculo de Salário Líquido

Este script calcula o salário líquido de um usuário após a dedução de um imposto de 10%.

## Código

```python
# Leitura do salário bruto
salario_bruto = float(input("Digite o salário bruto: R$"))

# Cálculo do imposto e salário líquido
imposto = salario_bruto * 0.10
salario_liquido = salario_bruto - imposto

# Exibição do salário líquido
print(f"Salário líquido: R${salario_liquido:.2f}")

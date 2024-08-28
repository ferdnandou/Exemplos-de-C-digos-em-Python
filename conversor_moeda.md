```markdown
# Conversor de Moeda

Este script converte um valor em reais (R$) para dólares (USD) utilizando uma taxa de câmbio fixa.

## Código

```python
# Taxa de câmbio
taxa_cambio = 5.0  # 1 dólar = 5 reais

# Leitura do valor em reais
valor_reais = float(input("Digite o valor em reais: R$"))

# Conversão para dólares
valor_dolares = valor_reais / taxa_cambio

# Exibição do valor convertido
print(f"Valor em dólares: ${valor_dolares:.2f}")

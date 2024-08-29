
---

### 11. Função para Calcular Média

```markdown
# Função para Calcular Média

Este script define uma função para calcular a média de três notas e exibe o resultado.

## Código

```python
def calcular_media(nota1, nota2, nota3):
    return (nota1 + nota2 + nota3) / 3

# Leitura das notas
nota1 = float(input("Digite a primeira nota: "))
nota2 = float(input("Digite a segunda nota: "))
nota3 = float(input("Digite a terceira nota: "))

# Chamada da função
media = calcular_media(nota1, nota2, nota3)

# Exibição da média
print(f"A média das notas é: {media:.2f}")

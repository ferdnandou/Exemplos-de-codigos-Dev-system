
---

### 12. Função para Calcular Perímetro

```markdown
# Função para Calcular Perímetro

Este script define uma função que calcula o perímetro de um retângulo a partir de sua largura e altura.

## Código

```python
def calcular_perimetro(largura, altura):
    return 2 * (largura + altura)

# Leitura das dimensões
largura = float(input("Digite a largura do retângulo: "))
altura = float(input("Digite a altura do retângulo: "))

# Chamada da função
perimetro = calcular_perimetro(largura, altura)

# Exibição do perímetro
print(f"O perímetro do retângulo é: {perimetro:.2f}")

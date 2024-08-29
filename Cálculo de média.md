
---

### 8. Cálculo de Média

```markdown
# Cálculo de Média

Este script calcula a média de três notas fornecidas pelo usuário.

## Código

```python
notas = []
for i in range(3):
    nota = float(input(f"Digite a nota {i+1}: "))
    notas.append(nota)

# Cálculo de média
media = sum(notas) / len(notas)

# Exibição da média
print(f"A média das notas é: {media:.2f}")

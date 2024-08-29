
---

### 3. Classificação de Nota

```markdown
# Classificação de Nota

Este script lê uma nota de 0 a 10 e classifica como "Ótimo", "Bom", "Suficiente" ou "Insuficiente".

## Código

```python
# Leitura da nota
nota = float(input("Digite a nota: "))

# Classificação da nota
if nota >= 9:
    classificacao = "Ótimo"
elif nota >= 7:
    classificacao = "Bom"
elif nota >= 5:
    classificacao = "Suficiente"
else:
    classificacao = "Insuficiente"

# Exibição da classificação
print(f"A nota é classificada como: {classificacao}")


---

### 2. Verificação de Faixa Etária

```markdown
# Verificação de Faixa Etária

Este script lê a idade do usuário e determina em qual faixa etária ele se encontra.

## Código

```python
# Leitura da idade
idade = int(input("Digite a sua idade: "))

# Verificação da faixa etária
if idade <= 12:
    faixa_etaria = "Criança"
elif idade <= 17:
    faixa_etaria = "Adolescente"
elif idade <= 64:
    faixa_etaria = "Adulto"
else:
    faixa_etaria = "Idoso"

# Exibição da faixa etária
print(f"Você está na faixa etária: {faixa_etaria}")

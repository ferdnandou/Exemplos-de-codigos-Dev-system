
---

### 7. Gerador de Tabuada

```markdown
# Gerador de Tabuada

Este script gera a tabuada de multiplicação de um número fornecido pelo usuário.

## Código

```python
# Leitura do número
numero = int(input("Digite um número para gerar a tabela de multiplicação: "))

# Loop para gerar a tabela de multiplicação
for i in range(1, 11):
    print(f"{numero} x {i} = {numero * i}")

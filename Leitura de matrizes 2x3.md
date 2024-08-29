
---

### 9. Leitura de Matriz 2x3

```markdown
# Leitura de Matriz 2x3

Este script lê valores para preencher uma matriz 2x3 e exibe a matriz resultante.

## Código

```python
# Inicialização da matriz
matriz = []

# Leitura dos valores para uma matriz 2x3
for i in range(2):
    linha = []
    for j in range(3):
        valor = float(input(f"Digite o valor para posição ({i+1},{j+1}): "))
        linha.append(valor)
    matriz.append(linha)

# Exibição da matriz
print("Matriz digitada: ")
for linha in matriz:
    print(linha)

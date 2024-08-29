
---

### 14. Função para Adicionar Elemento à Lista

```markdown
# Função para Adicionar Elemento à Lista

Este script define uma função que adiciona um elemento a uma lista.

## Código

```python
def adicionar_elemento(lista, elemento):
    lista.append(elemento)

# Inicialização da lista
minha_lista = []

# Leitura do elemento a ser adicionado
elemento = input("Digite um elemento para adicionar à lista: ")

# Chamada da função
adicionar_elemento(minha_lista, elemento)

# Exibição da lista modificada
print("Lista após adição do elemento:", minha_lista)

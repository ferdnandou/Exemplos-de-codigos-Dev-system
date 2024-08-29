
---

### 4. Calculadora Simples

```markdown
# Calculadora Simples

Este script permite ao usuário escolher uma operação matemática (adição, subtração, multiplicação ou divisão) e realizar o cálculo.

## Código

```python
# Exibição do menu
print("Escolha uma operação:")
print("1. Adição")
print("2. Subtração")
print("3. Multiplicação")
print("4. Divisão")

# Leitura da escolha do usuário
opcao = int(input("Digite o número da opção escolhida: "))

# Leitura dos números
numero1 = float(input("Digite o primeiro número: "))
numero2 = float(input("Digite o segundo número: "))

# Realização da operação com base na escolha
if opcao == 1:
    resultado = numero1 + numero2
elif opcao == 2:
    resultado = numero1 - numero2
elif opcao == 3:
    resultado = numero1 * numero2
elif opcao == 4:
    if numero2 != 0:
        resultado = numero1 / numero2
    else:
        resultado = "Erro: Divisão por zero"
else:
    resultado = "Opção inválida"

# Exibição do resultado
print(f"Resultado: {resultado}")

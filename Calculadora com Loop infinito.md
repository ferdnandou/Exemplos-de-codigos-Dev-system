# Calculadora com Loop Infinito

Este script é uma calculadora que executa operações matemáticas continuamente até que o usuário escolha sair.

## Código

```python
while True:
    # Leitura dos números e operação
    numero1 = float(input("Digite o primeiro número: "))
    numero2 = float(input("Digite o segundo número: "))
    operacao = input("Digite a operação (+, -, *, /) ou 'sair' para encerrar: ")

    # Verificação para encerrar o Loop
    if operacao == 'sair':
        break

    # Realização da operação
    if operacao == '+':
        resultado = numero1 + numero2
    elif operacao == '-':
        resultado = numero1 - numero2
    elif operacao == '*':
        resultado = numero1 * numero2
    elif operacao == '/':
        if numero2 != 0:
            resultado = numero1 / numero2
        else:
            resultado = "Erro: divisão por zero"
    else:
        resultado = "Operação inválida"

    # Exibição do resultado
    print(f"Resultado: {resultado}")

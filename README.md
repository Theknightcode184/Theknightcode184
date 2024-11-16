   escolha = input("Digite a opção (1/2/3/4): ")

  if escolha in ('1', '2', '3', '4'):
        num1 = float(input("Digite o primeiro número: "))
        num2 = float(input("Digite o segundo número: "))
    if escolha == '1':
            print(f"O resultado é: {num1 + num2}")
        elif escolha == '2':
            print(f"O resultado é: {num1 - num2}")
        elif escolha == '3':
            print(f"O resultado é: {num1 * num2}")
        elif escolha == '4':
            if num2 != 0:
                print(f"O resultado é: {num1 / num2}")
            else:
                print("Erro: Divisão por zero não é permitida.")
    else:
        print("Opção inválida.")

calculadora()

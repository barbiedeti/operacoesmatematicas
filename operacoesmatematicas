import textwrap

def menu ():
    selecao_menu = """ \n
    ===================== MENU =====================
    [1] - \tVerifique se um número é par ou ímpar
    [2] - \tMultiplicação de dois números
    [3] - \tDivisão de dois números
    [4] - \tRaiz quadrada de um número
    [5] - \tElevar um número a uma potência
    [6] - \tSair
    ================================================
    """
    return input(textwrap.dedent(selecao_menu))

def par_ou_impar ():
    num = int(input("Digite um número para verificar se é par ou ímpar: "))
    if num % 2 == 0:
        print(f"O número {num} é par.")
    else:
        print(f"O número {num} é ímpar.")

def multiplicacao ():
    num1 = int(input("Digite o primeiro número: "))
    num2 = int(input("Digite o segundo número:"))
    resultado = round(num1 * num2, 1) 
    print(f"O resultado da multiplicação de {num1} por {num2} é {resultado}.")

def divisao ():
    num1 = int(input("Digite o primeiro número: "))
    num2 = int(input("Digite o segundo número: "))
    if num2 == 0:
        print("Não é possível dividir por zero.")
    else:
        resuldvid = round(num1 / num2, 1)
        print(f"O resultado da divisão de {num1} por {num2} é {resuldvid}.")

def raiz_quadrada ():
    num = int(input("Digite um número para calcular a raiz quadrada: "))
    resulraiz = round(num ** 0.5, 1)
    print(f"A raiz quadrada de {num} é {resulraiz}.")

def potencia ():
    num = int(input("Digite um número para elevar a uma potência: "))
    pot = int(input("Digite a potência: "))
    resulpot = round(num ** pot, 1)
    print(f"O resultado de {num} elevado a {pot} é {resulpot}.")

def main ():
    while True:
        opcao = menu()
        if opcao == "1":
            par_ou_impar()
        elif opcao == "2":
            multiplicacao()
        elif opcao == "3":
            divisao()
        elif opcao == "4":
            raiz_quadrada()
        elif opcao == "5":
            potencia()
        elif opcao == "6":
            print("Obrigado por usar nosso sistema! Até a próxima!")
            break
        else:
            print("Opção inválida. Tente novamente.")

if __name__ == "__main__":

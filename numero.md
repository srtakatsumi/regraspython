Estou apredendo a programar, então se estive alguma informação incorreta, por favor deixe a explicação correta nos comentários.


Exercicio: Calcule dois números a operação deverá ser com números inteiros e fracionados


No Python podemos usar duas formas para informar que se trata de número.

int = número inteiro positivos ou negativos
	Exemplo: 2 e -2


float = ponto flutuante são notaveis porque eles têm um ponto decimal neles
	Exemplo: 4E2 ou 4*10**2(4x10elevado2) ou 1.2

# INT

    num1 = int(input("Digite o 1° número: ")
    num2 = int(input("Digite o 2° número: ")

    total = num1 + num2print = ("O valor total dos números é: " + total)

Como o código aparecerá para o usuário:


    Digite o 1º número: 2
    Digite o 2° número: 2


    O valor total dos números é: 4


OU


    Digite o 1º número: a
    Digite o 2° número: b


    Irá dar erro


OU


    Digite o 1º número: 2,5
    Digite o 2° número: 2,5


    Irá dar erro pois o int é somente para número inteiros


Explicação do código:


    num1 = int(input("Digite o 1° número: ") """variável num1 criada para armazenar 1º valor que o usuário inserir"""

    num2 = int(input("Digite o 2° número: ")"""variável num1 criada para armazenar 2º valor que o usuário inserir"""

    total = num1 + num2"""variável para armazenar o valor total"""print = ("O valor total dos números é: " + total)"""imprime uma mensagem para o usuário"""



OU FLOAT


    num1 = float(input("Digite o 1° número: ")
    num2 = float(input("Digite o 2° número: ")

    total = num1 + num2print = ("O valor total dos números é: " + total)

Como o código aparecerá para o usuário:


    Digite o 1º número:2,5
    Digite o 2° número:2,5

    O valor total dos números é: 5


OU


    Digite o 1º número:a
    Digite o 2° número:b

    Irá dar erro


OU


    Digite o 1º número:6
    Digite o 2° número:4

    O valor total dos números é: 10


    No caso do float ele irá calcular o interio e os que possuem decimais


Explicação do código:

    num1 = float(input("Digite o 1° número: ") """variável num1 criada para armazenar 1º valor que o usuário inserir"""

    num2 = float(input("Digite o 2° número: ")"""variável num1 criada para armazenar 2º valor que o usuário inserir"""

    total = num1 + num2"""variável para armazenar o valor total"""

    print = ("O valor total dos números é: " + total)"""imprime uma mensagem para o usuário"""

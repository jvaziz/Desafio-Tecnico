# Desafio-Tecnico
Desafio tecnico da vaga da Target de Ribeirão Preto

Realizado em Python

'''
Questão 1
'''

def fibonacci(n):
    a, b = 0, 1
    if n == 0 or n == 1:
        return True
    while b <= n:
        if b == n:
            return True
        a, b = b, a + b
    return False

numero = int(input("Informe um número para verificar se pertence à sequência de Fibonacci: "))

if fibonacci(numero):
    print(f"O número {numero} pertence à sequência de Fibonacci.")
else:
    print(f"O número {numero} NÃO pertence à sequência de Fibonacci.")


'''
Questão 2
'''

def verificar_letra_a(string):
    count_a = string.lower().count('a')
    
    if count_a > 0:
        print(f"A letra 'a' aparece {count_a} vez(es) na string.")
    else:
        print("A letra 'a' não aparece na string.")

texto = input("Informe uma string: ")
verificar_letra_a(texto)


'''
Questão 3

Ao executar este código, o valor de SOMA ao final será 77.

'''

INDICE = 12
SOMA = 0
K = 1

while K < INDICE:
    K = K + 1
    SOMA = SOMA + K


print(SOMA)


'''
Questão 4

4) Descubra a lógica e complete o próximo elemento:

O padrão é adicionar 2 a cada número anterior.
a) 1, 3, 5, 7, '9'

O padrão é multiplicar o número anterior por 2.
b) 2, 4, 8, 16, 32, 64, '128'

O padrão é elevar ao quadrado a sequência de números naturais 
começando com 0
c) 0, 1, 4, 9, 16, 25, 36, '49'

Essa sequência representa os quadrados dos números 2, 4, 6 e 8, respectivamente.
d) 4, 16, 36, 64, '100'

Essa é a sequência de Fibonacci, onde cada número é a soma dos dois números anteriores.
e) 1, 1, 2, 3, 5, 8, '13'

Para esta sequência, não há um padrão aritmético ou geométrico claro. 
No entanto, parece que os números vão de 2 a 19 com alguns intervalos:
f) 2,10, 12, 16, 17, 18, 19, '20'
'''


'''
Questão 5

Primeiro, ligue o Interruptor A e deixe-o ligado por 10 a 15 minutos. Depois, desligue o Interruptor A e ligue o Interruptor B. 
Em seguida, vá até a sala das lâmpadas. Na sala, observe as lâmpadas: a lâmpada que está acesa é controlada pelo Interruptor B. 
Toque nas lâmpadas que estão apagadas; a lâmpada que está quente, mas apagada, é controlada pelo Interruptor A, pois estava ligada anteriormente. 
A lâmpada fria é controlada pelo Interruptor C, que nunca foi ligado.
'''

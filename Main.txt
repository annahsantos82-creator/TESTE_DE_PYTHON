#quando eu preciso que o progama entenda que é uma palavra eu coloco entre aspas""
# str significa string, que é texto 
# codigos booleanos existem somente em duas condicoes, True or False
# str = string-texto   int = inteiro   float = decimal    bool = booleano

nome = "Ana"
idade = 20
nota = 8.5
aprovado = True

print(type(nome).__name__)
print(type(idade).__name__)
print(type(nota).__name__)
print(type(aprovado).__name__)

import math

a = 1
b = -5
c = 6
delta = b**2 - 4*a*c

# args significa argumentos, ou seja, parametros que podem ser passados para a função

def equacao2grau(a, b, c):
    x1 = -b + math.sqrt(b**2 - 4*a*c) / (2*a)
    return x1
def equacao2grau2(a, b, c):
    x2 = -b - math.sqrt(b**2 - 4*a*c) / (2*a)
    return x2

print (f"o resultado de x1 é:{equacao2grau(a, b, c)}")
print (f"o resultado de x2 é:{equacao2grau2(a, b, c)}")


# para importar variaveis ou funcoes dentro do python devemos utilizar chaves {}


print(equacao2grau(a, b, c))

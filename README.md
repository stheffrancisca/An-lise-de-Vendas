# An-lise-de-Vendas
Análise de Vendas

Vamos fazer uma "análise simples" de atingimento de Meta.

Temos uma lista com os vendedores e os valores de vendas e queremos identificar (printar) quais os vendedores que bateram a meta e qual foi o valor que eles venderam.


meta = 10000
vendas = [
    ['João', 15000],
    ['Julia', 27000],
    ['Marcus', 9900],
    ['Maria', 3750],
    ['Ana', 10300],
    ['Alon', 7870],
]
#seu código aqui
for item in vendas:
    if item[1] >= meta:
        print('Vendedor {} bateu a meta. Fez {} vendas'.format(item[0], item[1]))

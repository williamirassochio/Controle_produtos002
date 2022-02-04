```python
#criar um programa para categorizar os produtos de uma revendedora de bebidas.
#Cada produto tem um código. O tipo de produto é dado pelas 3 primeiras letras do código.

#Ex:
#Vinho -> BEB12302
#Cerveja -> BEB12043
#Vodka -> BEB34501

#Guaraná -> BSA11104
#Coca -> BSA54301
#Sprite -> BSA34012
#Água -> BSA09871

##Crie um programa que analise uma lista de produtos e envie instruções dos podutos que devem ser separados

```


```python
produtos = ['beb46275','TFA23962','TFA64715','TFA69555','TFA56743','BSA45510','TFA44968','CAR75448','CAR23596','CAR13490','BEB21365','BEB31623','BSA62419','BEB73344','TFA20079','BEB80694','BSA11769','BEB19495','TFA14792','TFA78043','BSA33484','BEB97471','BEB62362','TFA27311','TFA17715','BEB85146','BEB48898','BEB79496','CAR38417','TFA19947','TFA58799','CAR94811','BSA59251','BEB15385','BEB24213','BEB56262','BSA96915','CAR53454','BEB75073']
#Tratar Referências com letra Maiúsculas
def produtosBEB(a):
    if 'BEB' in a:
        return True
    else:
        return False
listaBEB = []
for produto in produtos:
    produto = produto.upper()
    if produtosBEB(produto):
        print('Separar este produto para setor de bebidas alcoólicas, {}.'.format(produto))
        produtoBEB = produto
        listaBEB.append(produtosBEB)
print('Ao total são {} produtos alcoólicos'.format(len(listaBEB)))
#Análisa e separar bebidas alcoolicas
bebidavenda = input('digite o código da bebida:')
if bebidavenda in produtos:
    print('Este é seu cógigo {}'.format(bebidavenda))
else:
    print('Código {} não existe, tente novamente!'.format(bebidavenda))
bebidavenda = bebidavenda.upper()

```

    Separar este produto para setor de bebidas alcoólicas, BEB46275.
    Separar este produto para setor de bebidas alcoólicas, BEB21365.
    Separar este produto para setor de bebidas alcoólicas, BEB31623.
    Separar este produto para setor de bebidas alcoólicas, BEB73344.
    Separar este produto para setor de bebidas alcoólicas, BEB80694.
    Separar este produto para setor de bebidas alcoólicas, BEB19495.
    Separar este produto para setor de bebidas alcoólicas, BEB97471.
    Separar este produto para setor de bebidas alcoólicas, BEB62362.
    Separar este produto para setor de bebidas alcoólicas, BEB85146.
    Separar este produto para setor de bebidas alcoólicas, BEB48898.
    Separar este produto para setor de bebidas alcoólicas, BEB79496.
    Separar este produto para setor de bebidas alcoólicas, BEB15385.
    Separar este produto para setor de bebidas alcoólicas, BEB24213.
    Separar este produto para setor de bebidas alcoólicas, BEB56262.
    Separar este produto para setor de bebidas alcoólicas, BEB75073.
    Ao total são 15 produtos alcoólicos
    digite o código da bebida:o-
    Código o- não existe, tente novamente!
    


```python

```

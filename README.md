# Cad Jobel
Repositório de demonstração do meu app para a distribuidora de alimentos Jobel.
O sistema é composto de um painel admin para web e um app android desenvolvido em JAVA. O sistema também conta com um banco de dados MySQL que é compartilhado pelo app e o painel.


## Página de login

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909423-f06aa680-bd52-11e9-8f60-2f9b2d334ea4.gif">
</p>

Página de login com o logo que altera para se ajustar a tela quando o teclado é mostrado.

## Dashboard

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909420-eea0e300-bd52-11e9-95e2-95d03ff9a1cc.png">
</p>

A home do app conta com um informativo sobre o valor da receita obtida no ultimo mês, o número de pedidos, os clientes, os produtos cadastrados no estoque e o total de funcionários.

## Inputs com sugestões

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909360-a84b8400-bd52-11e9-9ff9-9250a27234f5.gif">
</p>

Alguns inputs como o nome do cliente e o nome do produto geram logo abaixo um dropdown com sugestões, baseado no que o usuário digita. Tanto as informações dos clientes quanto dos produtos são obtidas por meio de um banco de dados MySQL através de uma api em PHP.

## Editar/remover produto e concluír pedido

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909419-ee084c80-bd52-11e9-9eb9-4ea44a000882.gif">
</p>

Depois de adicionar o produto ao pedido o usuário ainda tem a possibilidade de editar o valor, a quantidade e o nome do produto.


## Procurar produto no pedido

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909428-f2cd0080-bd52-11e9-8711-a7ad8fbce141.gif">
</p>

Caso a quantidade de produtos no pedido seja muito grande, existe a opção de fazer uma busca pelo produto dentro do pedido.

## Editar pedido

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909418-ee084c80-bd52-11e9-9b43-814873003f1a.gif">
</p>

Após o pedido ser feito, há a possibilidade de editá-lo, mudando status, cliente, endereço e total.

## Procurar pedido no historico

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909425-f2346a00-bd52-11e9-9a9c-c97068cbc4a0.gif">
</p>

Pedidos podem ser buscados pelo número ou nome do cliente.

## Clientes

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909413-e9439880-bd52-11e9-9360-47aecf434469.gif">
</p>

O app conta com uma lista de clientes obtida do banco de dados. Assim como no histórico de pedidos, há também a possibilidade de buscar por um cliente através da barra de busca.

## Perfil

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62909424-f1033d00-bd52-11e9-9c5e-f8bbe346c41f.png">
</p>

Cada funcionário conta com um perfil, previavemente cadastrado no painel admin. Além das informações pessoais, o perfil do usuário conta com o número de vendas e a comissão gerada através das mesmas. A porcentagem de comissão pode ser alterada no perfil do funcionário através do painel.


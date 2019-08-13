# Cad Jobel
Repositório de demonstração do meu sistema para a distribuidora de alimentos Jobel.
O sistema é composto de um painel admin para web e um app android desenvolvido em JAVA. O sistema também conta com um banco de dados MySQL que é compartilhado entre o app e o painel.

# Aplicativo android

Aplicativo usado para anotar pedidos e gerenciar os mesmos, abandonando assim o papel e a caneta usados comumente. 
O app possui responsividade, se adequando as mais diversas dimensões de telas de dispositivos. O app possuí algumas funções como notificações (enviadas através do painel), capacidade de guardar um pedido em andamento para o caso do vendedor fechar a aplicação e quiser continuar mais tarde, mudança de tema (configurada através do painel), entre outras.

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

## Notificações

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62964643-c7d9bf80-bdd9-11e9-9d92-77b99d2cb833.png">
</p>

O app e o painel contam com um sistema de notificações, onde o painel envia e o app recebe. Há possibilidade de enviar notificações criadas na hora e também usar templates previamente definidos.

## Temas

<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966538-9ebb2e00-bddd-11e9-9528-b66b0e50358e.png"> <img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966540-9ebb2e00-bddd-11e9-9e38-edef4871897c.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966542-9f53c480-bddd-11e9-875a-451ca086959f.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966543-9fec5b00-bddd-11e9-91e7-18b652f5105b.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966547-9fec5b00-bddd-11e9-9794-befbd5748ee2.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966548-a084f180-bddd-11e9-99b0-978b33c6831c.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966552-a11d8800-bddd-11e9-939c-43c3a3da9d3b.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966554-a1b61e80-bddd-11e9-9c1b-11a99d0fdfbd.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966556-a24eb500-bddd-11e9-9f1d-5154d2d4957b.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966557-a24eb500-bddd-11e9-89d0-06baa06d07fe.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62966558-a2e74b80-bddd-11e9-93ee-a53d536a67b2.png">
<img width="200" height="355" src="https://user-images.githubusercontent.com/53953275/62967437-556bde00-bddf-11e9-9764-7ee3c3f9787f.png">

O app possui no 12 temas no total, incluindo o padrão, que podem ser alterados via painel.

## Resposividade

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62963059-9e6b6480-bdd6-11e9-89c7-7cf59cea0ce1.png">
</p>

O app se adapta a diversas telas, desde telas pequenas de 4 polegadas até telas maiores de 7 polegadas usadas em tablet.

# Painel admin

É através do painel que acontecem os cadastros de produtos, clientes e funcionários, controle e cadastro de pedidos, controle de estoque, envio de notificações e diversas outras configurações como o tema do painel e do app.

Nota: O controle de estoque também ocorre de forma automática após cada pedido feito tanto no app quanto no painel.

## Página de login

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62969986-ceb9ff80-bde4-11e9-9dc8-d401773d480d.png">
</p>

Autenticação do painel. Apenas administradores cadastrados poderão ter acesso.

## Home

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62969906-a7fbc900-bde4-11e9-809c-f93200625126.png">
</p>

Assim como o app, o painel também conta com uma dashboard contendo algumas estatísticas.

## Pedidos

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62969984-ce216900-bde4-11e9-888c-d731df4d2385.png">
</p>

Na página de pedidos estão disponíveis ações como editar, remover, visualizar e enviar notificação rápida ao vendedor relacionada ao pedido.

## Estoque

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62970174-42f4a300-bde5-11e9-83e8-6727beb08f5a.png">
</p>

Página reponsável pelo gerenciamento de produtos no estoque.

## Clientes

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62970173-42f4a300-bde5-11e9-871b-5f80171a5cec.png">
</p>

Página reponsável pelo gerenciamento de clientes.

## Notificações

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62969899-a3371500-bde4-11e9-9dbc-7f8e8d0f366b.png">
</p>

Nesta página o administrador pode enviar para todos funcionários modelos de notificações previamente adicionadas ou criar novos. Notificações com imagens também são possíveis.

## Funcionários

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62970170-425c0c80-bde5-11e9-9164-534bcd98a2ef.png">
</p>

Aqui é onde será registrado os funcionários que terão acesso ao app. Informações do perfil, login e senha, poderão ser alterados a qualquer momento.

## Administradores

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62970168-425c0c80-bde5-11e9-9de0-45230c6b4db8.png">
</p>

Nesta página fica a função de alterar, remover ou adicionar novos administradores.

## Configurações

<p align="center">
<img src="https://user-images.githubusercontent.com/53953275/62972923-7e926b80-bdeb-11e9-9b26-37a6ea310b57.png">
</p>

Nesta página é onde se encontra as diversas configurações do painel e do app.

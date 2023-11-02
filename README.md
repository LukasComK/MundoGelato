# Mundo Gelato - O que é?
O Aplicativo Mundo Gelato é um software programado em visual basic com postgreSQL, que tem como objetivo forncecer um controle geral no seu estabelecimento de seroveteria que possui diversas funções desde logins por cargo/nivel á registro de acesso desses funcionarios.
# Login - Como Funciona?
Temos 3 niveis de login , temos o administrador , o funcionário e o diretor , cada um tem suas respectivas funções.
por exemplo funcionario não tem permissão de adicionar um novo produto e também de não adicionar funcionarios, já o diretor e o administrador tem essa função.
![Login](https://github.com/LukasComK/MundoGelato/assets/70048434/d22ba18a-0646-4eaa-b905-4d486f7db9f6)
# Menu - Tela Principal
Nesta tela é aonde é possivel ver as funções de cada cargo.
![Tela Principal](https://github.com/LukasComK/MundoGelato/assets/70048434/9d6a09dc-0155-4645-af40-982bd92242fc)
# Gerenciador de Produtos
Nesse Menu é aonde temos a possibilidade de adicionar produtos e gerencia-los! 
ela é divida em 2 partes como:
- Adicionar Produto
Aonde é feito a Inserção do produto ao sistema, onde é possivel gerar um codigo aleatorio para este produto (opcional) e adicionar, preço, nome, marca e quantidade, e automaticamente isso ja é calculado o preço total do estoque.
![Adicionar Produto](https://github.com/LukasComK/MundoGelato/assets/70048434/545a8179-9a4a-4c15-9e7e-2590ad4801ca)
- Controle Geral
tem a função de nós conseguimos administrar os produtos inseridos no aplicativo, e aqui aonde conseguimos ver produtos cadastrados e temos o poder de editar ou deletar esses produtos.
![Administrar Produtos](https://github.com/LukasComK/MundoGelato/assets/70048434/28b36cd0-efb9-4e56-8d61-f6046c3920ff)
# Gerenciador de Funcionários
a logica e parecida para o do gerenciador de produtos, porém aqui onde conseguimos adicionar os funcionarios e gerencia-los
- Adicionar Funcionário
  Aqui deve ser colocado algumas informações cruciais, como nome,CPF, data de nascimento, endereço e o cargo.
  atravez do cargo que vai ser definido as funções deste funcionário no programa, e também as sua informações de login.
  o login e gerado de maneira automatica e usada os seguinte criterios:
  - Login é definido pelo primeiro Nome e os 6 primerios digitos do CPF / Exemplo:  Lukas123456
  - Senha é Definido Pelas 3 Primeiras Iniciais e sua data de nascimento / Exemplo: Luk27042005
![CadastrarFuncionario](https://github.com/LukasComK/MundoGelato/assets/70048434/ef606682-cfc7-4f3e-a239-f00e6980ff7e)
- Administrar Funcionários
  Aqui onde o admnistrador e Diretor possuem acesso para gerenciar os funcionários e dando opções de alterar,excluir e ver o login de cada funcionario.
  Claramente neste Tela o administrador não tem acesso a conta do diretor neste menu, já que ele tem um cargo maior.
  ![Administração de funcionarios](https://github.com/LukasComK/MundoGelato/assets/70048434/adff4dc8-a189-41ba-aeb8-15be65f5f451)
# Relatórios - Menu
nesse menu esta as funções mais relevantes na parte financeira e de registro de acesso dos funcionários
![image](https://github.com/LukasComK/MundoGelato/assets/70048434/7fcc6126-711d-48e3-9d42-cde436629213)
# Registro de Acessos
O objetivo desse Forms e dar orientação aos diretores e administradores em relação aos funcionario em questão ao tempo de acesso no aplicativo.
o tempo ja é contado quando se faz ao login até o fechamento do programa.
os funcionarios so podem ver seus proprios acessos, administradores de todos funcionarios e o seu, e os diretores pode ver de todos que estão cadastrados no aplicativo
![Registro de Acessos](https://github.com/LukasComK/MundoGelato/assets/70048434/7dc01707-964d-47ba-b7d1-40a9567ce8c3)
# Relatório de Pedidos
Tem a função de mostrar todos os pedidos feitos da área de PDV, e nela que conseguimos ver que funcionario executou o pedido assim nos forncecendo informações da quantidade, do valor total e quando ele foi finalizado.
![Relatorio de Pedidos](https://github.com/LukasComK/MundoGelato/assets/70048434/a04d3cb9-4d08-457f-b6a8-c958f8c9c970)
 - Relatório de Pedidos Detalhado
   Aqui é aonde conseguimos ver quais produtos foram adicionado nos pedidos.
   ![Relatorio de Pedidos Detalhado](https://github.com/LukasComK/MundoGelato/assets/70048434/659379fb-b101-477d-a360-a87a338caabf)
# Relatório de Vendas
Ao entrar nesse relatório deparamos inicialmente com os produtos mais venndidos mostrando sua quantidade, na caixa de texto aparece todas as data que houveram pedidos, e nela que conseguimos ver especificadamente o que vendeu mais naquele dia.
![Relatorio De Vendas](https://github.com/LukasComK/MundoGelato/assets/70048434/4475c288-252d-4195-8c96-702dd02d2f32)
o botão de "mudar grafico" ele muda para o tipo Pie (Grafico de Setores) , em alguns situações ela pode ser  bem mais aproveitada
![Relatorio De Vendas Other Graphics](https://github.com/LukasComK/MundoGelato/assets/70048434/de091d57-512e-4b22-a4d4-20ba44745850)
# Relatório de Venda Dos Funcionários
Tem a mesma ideia e função do Relatório de Vendas, porém aqui é baseado em Funcionários, onde nos conseguimos visualizar inicialmente os funcionarios que mais venderam, onde mostra o nome e em seguida o valor vendido.
![Relatorio de Venda dos Funcionarios](https://github.com/LukasComK/MundoGelato/assets/70048434/dc43d3a0-1ca2-4883-b34f-e495d5cd29bd)
# PDV - Cargo Chefe do App
Nesta tela é aonde conseguimos fazer nossos pedidos!
antes para começar a usar o Ponto de venda e necessário clicar no botão "Prod. N/Selecionado" para adicionar um produto que um cliente deseja.
OBS: não é possivel adicionar produtos com a linha vermelha, pois não existe no estoque!
![Adicionar Produto PDV](https://github.com/LukasComK/MundoGelato/assets/70048434/ee24d262-ada4-4187-be42-67bdaa121b49)
após adicionar o produto, as caixas de texto iram se completar automaticamete com as informações daquele produto, assim habilitando a caixa de texto de quantidade.
assim que voce adicionar a quantidade será possivel adiciona-lo ao "Cupom ficticio".
quando se é adicionado um produto ele automaticamente sai do estoque, como se estivesse em utilização, evitando assim que outros pontos de venda causem divergencias.
para deletar um produto, caso o cliente tenha desistido ou escolhido outra opção, é so clicar no produto dentro do cupom ficticio.
para a finalização do pedido , deve-se clicar em "fechar pedido", so assim será possivel fazer a contabilização de venda dos funcionarios, e de registro de pedidos
![PDV Pedido Fechado](https://github.com/LukasComK/MundoGelato/assets/70048434/e258da44-82c3-40d8-9521-8d8c0abcf14c)
após a finalização dos pedidos, todos os botões estaram bloqueados, so seram habilitados novamente ao clicar em "novo pedido"










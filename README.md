## Mundo Gelato - Descrição do Aplicativo

O Aplicativo Mundo Gelato é um software desenvolvido em Visual Basic com PostgreSQL, projetado para oferecer um controle abrangente no gerenciamento de estabelecimentos de sorveteria. Este aplicativo apresenta diversas funcionalidades, desde diferentes níveis de acesso por cargo até o registro de atividades dos funcionários.

### Login - Funcionamento

Existem três níveis de acesso: administrador, funcionário e diretor, cada um com suas responsabilidades específicas. Por exemplo, os funcionários não possuem permissão para adicionar novos produtos nem incluir outros funcionários. Por outro lado, tanto o diretor quanto o administrador possuem essa permissão.
![Login](https://github.com/LukasComK/MundoGelato/assets/70048434/80b09fa9-cc9f-47e0-8a3e-4eef2d2e60ac)

### Menu - Tela Principal

Nesta tela, é possível visualizar as funcionalidades disponíveis para cada nível de acesso.
![Tela Principal](https://github.com/LukasComK/MundoGelato/assets/70048434/0a9cacb7-7be4-47b6-8999-b67cc4356898)


### Gerenciador de Produtos

Neste menu, é viável adicionar e gerenciar produtos, dividindo-se em duas seções:

- **Adicionar Produto:** Aqui, é possível inserir um produto no sistema, com a opção de gerar um código aleatório (opcional) e adicionar informações como preço, nome, marca e quantidade. Automaticamente, o aplicativo calcula o valor total do estoque.
![Adicionar Produto](https://github.com/LukasComK/MundoGelato/assets/70048434/230f5674-37b0-49c4-a3c9-f4517d7402fd)


- **Controle Geral:** Esta função permite a administração dos produtos cadastrados, oferecendo a possibilidade de editar ou excluir os produtos.
![Administrar Produtos](https://github.com/LukasComK/MundoGelato/assets/70048434/7a1fcb55-b129-4abc-b3e0-8d00ddbea0dd)


### Gerenciador de Funcionários

A lógica é semelhante à do gerenciador de produtos, permitindo a adição e administração de funcionários.

- **Adicionar Funcionário:** Nesta seção, são inseridas informações cruciais, como nome, CPF, data de nascimento, endereço e cargo. O cargo determina as funções do funcionário no programa, assim como suas informações de login, geradas automaticamente seguindo critérios específicos.
Exemplo: Login é definido pelo primeiro Nome e os 6 primerios digitos do CPF Exemplo: Lukas123456
Senha é Definido Pelas 3 Primeiras Iniciais e sua data de nascimento Exemplo: Luk27042005

 ![CadastrarFuncionario](https://github.com/LukasComK/MundoGelato/assets/70048434/0f505710-6799-4643-992c-728cbb6d7b0e)


- **Administrar Funcionários:** Aqui, administradores e diretores têm acesso para gerenciar os funcionários, com opções de alterar, excluir e visualizar o login de cada um.
![Administração de funcionarios](https://github.com/LukasComK/MundoGelato/assets/70048434/4b4d902e-4611-4d8d-a562-7951d96259e1)


### Relatórios - Menu

Este menu contém as funções mais relevantes financeiramente e os registros de acesso dos funcionários.
![image](https://github.com/LukasComK/MundoGelato/assets/70048434/a3c18cac-8978-46da-9c2f-e21de6f3af6f)


### Registro de Acessos

Este formulário tem como objetivo orientar diretores e administradores sobre o tempo de acesso dos funcionários ao aplicativo, contabilizando o tempo desde o login até o encerramento do programa.
![Registro de Acessos](https://github.com/LukasComK/MundoGelato/assets/70048434/3ba7527c-edd2-42b0-abe9-30575efc1e7f)


### Relatório de Pedidos

Mostra todos os pedidos feitos na área de PDV, exibindo informações como quantidade, valor total e a identificação do funcionário responsável pela execução do pedido.
![Relatorio de Pedidos](https://github.com/LukasComK/MundoGelato/assets/70048434/3aa4832c-4970-48b3-a3e4-03ec6b596979)


- **Relatório de Pedidos Detalhado:** Esta seção detalha os produtos incluídos nos pedidos.
![Relatorio de Pedidos Detalhado](https://github.com/LukasComK/MundoGelato/assets/70048434/a3d9559e-1440-46b8-af68-fe7b83bd9956)


### Relatório de Vendas

Apresenta os produtos mais vendidos e as datas em que houve pedidos. Oferece uma visão específica das vendas por dia, com a possibilidade de alternar para um gráfico do tipo "Pie" em situações pertinentes.
![Relatorio De Vendas](https://github.com/LukasComK/MundoGelato/assets/70048434/07a96aa4-3824-4d59-822a-79491bc8e84e)
![Relatorio De Vendas Other Graphics](https://github.com/LukasComK/MundoGelato/assets/70048434/c5d93647-69d0-48cd-a4c8-fc94491cabf0)


### Relatório de Vendas dos Funcionários

Semelhante ao relatório de vendas, mas com foco nos funcionários, mostrando quem vendeu mais, apresentando nome e valor total vendido.
![Relatorio de Venda dos Funcionarios](https://github.com/LukasComK/MundoGelato/assets/70048434/6a335140-6c2d-4237-a089-0f56c53cc4a6)


### PDV - Ponto de Venda

Esta tela é destinada à realização de pedidos. Antes de iniciar, é necessário clicar no botão "Prod. N/Selecionado" para adicionar um produto desejado pelo cliente. É importante ressaltar que produtos com linha vermelha não estão disponíveis no estoque e, portanto, não podem ser adicionados.
![Adicionar Produto PDV](https://github.com/LukasComK/MundoGelato/assets/70048434/97355f4d-b2f4-4176-869e-e0ad25f23285)


Após adicionar o produto, as informações correspondentes são preenchidas automaticamente, permitindo a inserção da quantidade. Ao adicionar a quantidade desejada, ela é incluída no "Cupom fictício". É importante notar que o produto é automaticamente retirado do estoque ao ser adicionado, evitando conflitos em outros pontos de venda.

Para cancelar um produto, basta clicar nele no cupom fictício. Ao finalizar o pedido clicando em "Fechar Pedido", a venda é contabilizada e registrada.
![PDV Pedido Fechado](https://github.com/LukasComK/MundoGelato/assets/70048434/0746ce36-8041-4c28-a117-7e5a26820716)
Após a finalização do pedido, todos os botões são bloqueados e só são habilitados novamente ao clicar em "Novo Pedido".


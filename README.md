# API Arquitetura RESTful
O commit com as rotas para o CRUD de clientes.
````
git add <conteudo>
git commit -m "ADS: <sua_matricula> REST-cli"
````
### Objetivo das rotas.
````
Nessa etapa rotas de cliente deve incluir apenas os principais métodos, tais como GET, POST, PUT e DELETE.
````
# Banco de dados:
O commit com as tabelas ou as configurações de acesso ao seu banco de dados com o CRUD completo.
````
git add <conteudo>
git commit -m "ADS: <sua_matricula> DB"
````

### Objetivo do Armazenamento.
````
Na fase atual, ao utilizar SQL ou as funções já implementadas, de acordo com a
lógica de armazenamento de dados, como ORM e migrações, ou o banco de dados Firebase.
````

### Tabela de Clientes:

````
Ambas as tabelas estão relacionadas, onde cada ordem de serviço está vinculada
a um cliente específico através do ID do cliente.
Tem que permitir um gerenciamento integrado e eficiente de todas as informações
relacionadas aos clientes e suas ordens de serviço.

````
#### Como um usuário, eu quero ser capaz de:

1. Adicionar novos clientes:
````
Eu devo ser capaz de inserir o nome, endereço, telefone e e-mail do cliente na tabela.
````
2. Atualizar informações dos clientes:
````
Eu devo ser capaz de modificar o nome, endereço, telefone e e-mail do cliente conforme necessário.
````
3. Visualizar detalhes dos clientes:
````
Eu devo ser capaz de ver todos os detalhes de um cliente específico, incluindo seu nome, endereço, telefone e e-mail.
````
4. Excluir clientes:
````
Eu devo ser capaz de remover um cliente da base de dados, se necessário.
````
### Tabela de Ordens de Serviço:

#### Como um usuário, eu quero ser capaz de:

1. Registrar novas ordens de serviço:
````
Eu devo ser capaz de criar uma nova entrada para uma ordem de serviço, incluindo o cliente associado,
a data da ordem, a descrição do serviço, o custo estimado e quaisquer observações relevantes.
````
2. Atualizar status e custo das ordens de serviço: 
````
Eu devo ser capaz de atualizar o status da ordem de serviço (como "Em andamento", "Concluído", etc.)
e inserir o custo final da ordem de serviço à medida que ela progride.
````
3. Visualizar detalhes das ordens de serviço:
````
Eu devo ser capaz de ver todos os detalhes de uma ordem de serviço
específica, incluindo o cliente associado, a data da ordem, a descrição do serviço, o custo estimado, o custo final,
o status e quaisquer observações adicionais.
````
4. Excluir ordens de serviço:
````
Eu devo ser capaz de remover uma ordem de serviço da base de dados, se necessário.
````

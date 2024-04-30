# Framework next.js
O commit com as primeiras configurações do projeto deve incluir as configurações iniciais do Framework Next.js.
````
git add <conteudo>
git commit -m "ADS: <sua_matricula> Next-js"
````
### Objetivo do INIT.
````
Nessa etapa, quero que inicie do zero assim que baixar o projeto, para garantir a evolução do mesmo.
A escolha do repositório é livre. Quero ver o histórico de commits e poder visualizar o código-fonte.
````
# Iniciando o projeto:
````
Todos os arquivos criados devem conter a data, nome e matrícula, além de uma breve descrição sobre o documento.
````
### Exemplo
````js
/**
 * Nome do arquivo: exemplo.js
 * Data de criação: 30/04/2024
 * Autor: João Silva
 * Matrícula: 123456
 *
 * Descrição:
 * Este arquivo JavaScript é responsável por implementar as funcionalidades
 * de interação do usuário com a interface gráfica do módulo de vendas.
 * Aqui são tratados eventos de cliques, validações de entrada e comunicação
 * com APIs para envio e recebimento de dados.
 *
 * Este script é parte o curso de ADS.
 */

````
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

# Deploy do projeto
O commit com as configurações para o Deploy
````
git add <conteudo>
git commit -m "ADS: <sua_matricula> Deploy-js"
````
### Objetivo para o Deploy.
````
Nessa etapa, são realizados os testes e configuradas as variáveis de ambiente de acordo com a hospedagem escolhida.
````

# Página com o CRUD de clientes
O commit com a logica da page de clientes
````
git add <conteudo>
git commit -m "ADS: <sua_matricula> clientes-hmtl"
````
### Objetivo da page clientes.
````
Quero que crie uma tabela HTML com todas as funcionalidades de um CRUD de maneira funcional
````
![image](https://github.com/FranciscoWallison/desafio-back-end/assets/19413241/5e52578f-1dec-49a6-b0d1-9ded6203e68f)


# Readme 
O commit com as configurações para rodar o projeto
````
git add <conteudo>
git commit -m "ADS: <sua_matricula> Readme-md"
````
### Objetivo para do Readme.
````
Nessa etapa, o objetivo é adicionar fotos ou gifs explicando o projeto e como quem for testar pode acessar o link e entender seu objetivo.
````

# DOC da Collection 
Faça o commit do arquivo da _collection da sua API na raiz do projeto, aquivo tem que ter o nome da sua matricula.
EXP: <matricula>_collection.json
````
git add <conteudo>
git commit -m "ADS: <sua_matricula> Collection"
````
A configuração de cabeçalho não é necessário para para os arquivos do tipo .json.


## Serão zerados caso os critérios de commit não sejam sequidos e se os arquivos criados pelo autor não contiverem suas credenciais.

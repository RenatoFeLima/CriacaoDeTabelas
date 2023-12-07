# CriacaoDeTabelas
Conceitos de criação de tabelas dentro do DataBase, uso de primary key e foreign key

BANCO DE DADOS DE UMA LOJA DE VENDA DE SUCOS.

TABELA_DE_CLIENTES:
Armazena informações sobre os clientes, como CPF, nome, endereço, data de nascimento, sexo, etc.
A chave primária é o CPF, garantindo unicidade.

TABELA_DE_PRODUTOS:
Contém detalhes sobre os produtos, como código, nome, embalagem, preço de lista, etc.
A chave primária é o código do produto, assegurando unicidade.

TABELA_DE_VENDEDORES:
Registra dados sobre os vendedores, incluindo matrícula, nome, percentual de comissão, data de admissão, etc.
A chave primária é a matrícula, garantindo unicidade.

NOTAS_FISCAIS:
Armazena informações sobre as notas fiscais, como número, CPF do cliente, matrícula do vendedor, data de venda, imposto, etc.
A chave primária é o número da nota fiscal.
Inclui chaves estrangeiras que fazem referência às tabelas TABELA_DE_CLIENTES e TABELA_DE_VENDEDORES.

ITENS_NOTAS_FISCAIS:
Mantém detalhes sobre os itens em cada nota fiscal, como número da nota, código do produto, quantidade, preço, etc.
A chave primária é uma combinação de número da nota e código do produto.
Inclui chaves estrangeiras que fazem referência às tabelas TABELA_DE_PRODUTOS e NOTAS_FISCAIS.

Softwares & Ferramentas utilizadas nesse projeto
 MySQL
 Git
 

 

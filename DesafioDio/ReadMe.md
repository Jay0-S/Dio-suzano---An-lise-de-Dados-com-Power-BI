Desafio 1 Ecommerce

O diagrama representa um sistema de e-commerce, representando as entidades e seus relacionamentos de forma visual.

Fornecedor: Representa as empresas que fornecem produtos para a loja virtual. 
Vendedor Terceiro: Representa vendedores externos que comercializam produtos na plataforma.
Produto: Representa os produtos vendidos na loja virtual. 
Cliente: Representa os clientes da loja virtual. 
Pedido: Representa os pedidos realizados pelos clientes. 
Estoque: Representa os produtos em estoque. 
Formas de Pagamento: Representa as diferentes formas de pagamento aceitas pela loja virtual. 
Entrega: Representa as entregas realizadas.

Os relacionamentos entre as entidades são representados por linhas. 

Um fornecedor pode disponibilizar um ou mais produtos.
Um produto pode ser disponibilizado por um ou mais fornecedores.
Um pedido pode conter um ou mais produtos.
Um produto pode estar em um ou mais pedidos.
Pode ter mais de uma forma de pagamento.
Possui status e código de rastreio.

![esquema conceitual para o cenário de E-commerce](https://github.com/user-attachments/assets/49d46238-d371-4334-a17e-95ea4720b8d1)

Desafio 2 Oficina

O diagrama representa o modelo de dados de uma oficina mecânica, destacando as seguintes entidades principais e seus relacionamentos:
Cliente: Contém informações dos clientes, como nome, CPF, endereço, e contato.
Relaciona-se com Veículo (1 cliente possui 1 ou mais veículos).
Veículo: Contém informações do veículo, como marca, modelo, cor, placa e chassi.
Associado ao Cliente e à Ordem de Serviço (1 veículo pode ter várias ordens de serviço).
Ordem de Serviço: Armazena informações sobre serviços realizados, como tipo, data de emissão, status e orçamento.
Relaciona-se com Veículo, Mecânico, Serviço, e Peça/Estoque.
Mecânico: Registra informações dos mecânicos, incluindo nome, código e especialidade.
Associado à Ordem de Serviço (1 mecânico pode atender várias ordens).
Serviço: Representa os serviços disponíveis, com descrição e preço.
Relaciona-se com a tabela intermediária Ordem de Serviço_has_Serviço (vários serviços podem ser associados a uma ordem).
Peça/Estoque: Contém informações sobre peças disponíveis, como descrição, quantidade, fabricante e valor.
Relaciona-se com a tabela intermediária para vincular peças às ordens de serviço.
Ordem de Serviço_has_Serviço: É uma tabela intermediária que conecta Ordem de Serviço e Serviço. Também permite vincular peças específicas às ordens de serviço.

O modelo reflete o fluxo de trabalho da oficina, associando clientes, veículos, serviços, mecânicos e peças de forma estruturada.

![Diagrama conceitual oficina](https://github.com/user-attachments/assets/a955d4a0-c565-4009-b16c-5c2b36c85a4b)

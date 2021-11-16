# TrabalhoProgDispMov

Alunos: 	
Guilherme Pecois Arakaki 		RGA: 2019.1906.026-0
e 
José Paulo Camilotti de Oliveira	RGA: 2016.1905.017-0

Visão Geral: 
O Software é voltado para o controle de estoque. Ele permite o cadastro de produtos, funcionários, vendas e compras.

Papéis:
Administrador=> Cadastrar ou alterar ou excluir usuários, cadastrar ou alterar ou excluir produtos, cadastrar ou alterar ou excluir vendas, cadastrar ou  alterar ou excluir compras
 
Gerente=> Cadastrar ou alterar produtos, cadastrar ou alterar vendas, cadastrar ou alterar compras
 
Estocador=> Cadastrar ou alterar compras

Vendedor=> Cadastrar ou alterar vendas

Requisitos Funcionais:
	
	Usuários:
	1 - O Software permite ao Administrador cadastrar, alterar ou remover funcionários, produtos, compras e vendas.
	2 - O Software permite ao Gerente cadastrar, alterar produtos, compras e vendas.
	3 - O Software permite ao Vendedor cadastrar ou alterar vendas.
	4 - O Software permite ao Estocador cadastrar ou alterar vendas.
	
	Saídas e relatórios:
	5 - O Software permite ao Administrador ter uma lista de funcionários, produtos, vendas e compras
	6 - O Software permite ao Gerente ter uma lista de produtos, vendas e compras
	7 - O Software permite ao Estocador ter uma lista compras
	8 - O Software permite ao Vendedor ter uma lista de vendas 
	
	Processamento:
	9 - Para o cadastro de funcionários é necessário possuir o Nome Completo, id, Cargo
	10 - Para o cadastro de produtos é necessário possuir o Nome do produto, id, valor e quantidade, Id do funcionário
	11 - Para o cadastro de vendas é necessário possuir o Id do funcionário, id da venda, Nome do Cliente, Data de venda, Id do produto e Quantidade do Produto
	12 - Para o cadastro de compras é necessário possuir o Id do funcionário, id da compra, nome do fornecedor, Data de compra, Id do produto e Quantidade do Produto
	13 - A cada cadastro de funcionário é notificado ao gerente

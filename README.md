# FSwIP-AD1

#### 1. Desenvolver rotina para importação de um cadastro de produtos e serviços a partir de um arquivo texto delimitado por tamanho (largura fixa). O arquivo de origem, bem como o arquivo de layout estão na pasta arquivos.
Premissas:
>- Deverão ser importados apenas produtos ativos cuja data de cadastro seja posterior a junho de 2002.
- Todos os produtos deverão ter como data de cadastro, no destino, a data da execução da rotina.
- Os produtos incluídos via essa rotina deverão ter um flag no destino informando que foram cadastrados via importação automática.
- Prever rotina de consistência com informação em tela para o usuário para um eventual ajuste no arquivo.
- Produtos com o campo COR não preenchidos na origem deverão apresentar no destino o dado “N/A”.
- Ao final da importação bem-sucedida, a rotina deve apresentar uma mensagem com o número de produtos importados.
- Não utilizar SQL.

#### 2. Desenvolver rotina para exportar 1 arquivo, em formato DBF/CTREE, com informações do cabeçalho e dos itens de pedidos de vendas.
Requisitos:
>- Grupo de Perguntas (Pedido De... Pedido Até).
- DBF deve conter as seguintes colunas:
	- Número do pedido
	- Nome do cliente
	- Data de emissão
	- Quantidade total de itens
	- Valor total dos itens (soma dos Itens)
	- Preço médio unitário dos itens
	- Quantidades de volumes dos produtos
- Não utilizar SQL.

#### 3. Desenvolver rotina para exportar 3 arquivos, em formato DBF/CTREE, com informações do cabeçalho e dos itens de pedidos de compra.
Requisitos:
>- Grupo de Perguntas (Pedido De... Pedido Até).
- DBF/CTREE 01 deve conter as seguintes colunas (cabeçalho):
	- Número do pedido
	- Nome do fornecedor
	- Data de emissão
	- Valor total dos itens (soma dos Itens)
- DBF/CTREE 02 deve conter as seguintes colunas (itens):
	- Código do produto
	- Item
	- Preço unitário
	- Quantidade
	- Valor total
- DBF/CTREE 03 deve conter as seguintes colunas (produtos):
	- Código do produto
	- Descrição produto
	- Preço unitário do produto
- Utilizar SQL.

Tempo máximo para solução dos exercícios: 16 horas.

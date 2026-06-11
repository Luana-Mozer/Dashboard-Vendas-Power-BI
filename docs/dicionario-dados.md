# Dicionário de Dados

Base utilizada: `Vendas.xlsx`

## Tabela de vendas

| Coluna | Descrição |
| --- | --- |
| Data da Venda | Data em que a venda foi realizada. |
| Produto | Nome do produto vendido. |
| Categoria | Categoria do produto. |
| PrecoUnitario | Valor unitário de venda do produto. |
| Custo Unitário | Custo unitário do produto. |
| Marca | Marca do produto vendido. |
| Qtd. Vendida | Quantidade de itens vendidos. |
| Nome Cliente | Nome do cliente relacionado à venda. |
| Localidade | País e continente relacionados à venda. |

## Campos utilizados para análise

Além das colunas originais, a base foi preparada para permitir análises como:

- Vendas por período.
- Vendas por produto.
- Vendas por categoria.
- Vendas por marca.
- Vendas por cliente.
- Vendas por localidade.
- Comparação entre preço, custo e lucro.

## Observações de tratamento

- Campos vazios foram analisados e removidos quando não contribuíam para a análise.
- Registros duplicados foram eliminados para evitar distorções nos indicadores.
- Textos foram padronizados para reduzir erros de agrupamento.
- Nomes no formato `Sobrenome, Nome` foram tratados para melhorar a leitura no dashboard.

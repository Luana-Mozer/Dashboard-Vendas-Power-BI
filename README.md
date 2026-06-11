# Dashboard - Power BI

Projeto de análise de vendas desenvolvido no Power BI a partir de uma base em Excel. O objetivo foi transformar uma tabela bruta de vendas em uma base limpa, organizada e pronta para gerar um dashboard completo, com indicadores, filtros e visualizações para apoiar a leitura dos resultados.

## Sobre o projeto

Neste projeto, trabalhei a base `Vendas.xlsx` no Power BI, fazendo a limpeza e a modelagem dos dados antes da construção do dashboard. A tabela original tinha problemas comuns em bases reais, como colunas vazias, linhas vazias, nomes de clientes invertidos, registros repetidos e informações que precisavam ser padronizadas.

A partir desse tratamento, a base foi transformada em uma super tabela de vendas, reunindo informações de data, produto, categoria, preço, custo, marca, quantidade vendida, cliente e localidade.

## Arquivos do projeto

- `Dashboard.pbix`: arquivo principal do Power BI com o dashboard final.
- `Vendas.xlsx`: base original utilizada no projeto.
- `docs/dicionario-dados.md`: descrição das principais colunas da base.
- `docs/processo-tratamento-dados.md`: resumo das etapas de limpeza e transformação.

## Ferramentas utilizadas

- Power BI Desktop
- Power Query
- Excel
- GitHub

## Etapas desenvolvidas

### 1. Importação da base

A base de vendas foi importada do Excel para o Power BI. A partir dela, iniciei a análise da estrutura dos dados para identificar inconsistências e pontos de melhoria.

### 2. Limpeza dos dados

Durante o tratamento no Power Query, foram realizadas etapas como:

- Remoção de colunas vazias.
- Remoção de linhas vazias.
- Exclusão de registros duplicados.
- Padronização de textos.
- Correção de espaços extras em campos como marca e cliente.
- Ajuste de nomes de clientes que estavam invertidos no formato `Sobrenome, Nome`.

### 3. Organização da tabela de vendas

Depois da limpeza, a tabela foi organizada para facilitar a análise. As principais colunas trabalhadas foram:

- Data da venda
- Produto
- Categoria
- Preço unitário
- Custo unitário
- Marca
- Quantidade vendida
- Nome do cliente
- Localidade

Também foi possível estruturar a base para análises de vendas por produto, categoria, cliente, marca, período e região.

### 4. Criação do dashboard

Com os dados tratados, construí o dashboard no Power BI para apresentar os principais resultados de vendas de forma visual e objetiva.

O dashboard permite acompanhar:

- Total de vendas.
- Quantidade vendida.
- Custo dos produtos.
- Lucro estimado.
- Desempenho por categoria.
- Desempenho por marca.
- Vendas por localidade.
- Evolução das vendas ao longo do tempo.

## Resultado

O resultado final foi um dashboard completo de vendas, criado a partir de uma base que passou por limpeza, padronização e transformação. O projeto mostra como uma tabela bruta pode ser preparada no Power BI para gerar análises mais claras, confiáveis e profissionais.

## Como visualizar

1. Baixe ou clone este repositório.
2. Abra o arquivo `Dashboard.pbix` no Power BI Desktop.
3. Caso necessário, atualize a origem dos dados apontando para o arquivo `Vendas.xlsx`.
4. Explore os filtros e gráficos do dashboard.

## Aprendizados

Com este projeto, pratiquei:

- Tratamento de dados no Power Query.
- Limpeza de bases com inconsistências.
- Padronização de nomes e textos.
- Remoção de dados vazios e repetidos.
- Organização de uma tabela de vendas.
- Criação de dashboard no Power BI.
- Apresentação de análise de dados em portfólio no GitHub.

---

Projeto desenvolvido para portfólio de análise de dados.

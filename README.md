# Dashboard - Power BI

Esse projeto foi feito para mostrar todo o processo de transformação de uma base de vendas em um dashboard completo no Power BI.

A ideia foi pegar uma planilha que ainda precisava de tratamento, organizar os dados no Power Query e, depois disso, montar uma visualização mais clara para acompanhar faturamento, produtos vendidos, categorias e vendas por país.

## Base utilizada

A base original estava em Excel e tinha informações de vendas como data, produto, categoria, preço unitário, custo, marca, quantidade vendida, cliente e localidade.

Antes de montar o dashboard, eu fiz uma análise da tabela para entender quais ajustes seriam necessários.

![Planilha original no Excel](Imagens/Planilha%20do%20Excel.png)

## O que eu tratei nos dados

No Power Query, fiz a limpeza da base para deixar os dados mais organizados e confiáveis para a análise.

Alguns dos tratamentos feitos foram:

- removi colunas vazias;
- removi linhas vazias;
- ajustei nomes que estavam invertidos;
- tirei espaços extras nos textos;
- corrigi informações repetidas;
- padronizei campos como marca, cliente e localidade;
- organizei a tabela para trabalhar melhor com vendas, custo e quantidade.

Depois dessa etapa, a base ficou pronta para virar uma tabela de vendas mais completa e fácil de analisar.

## Dashboard final

Com os dados tratados, montei o dashboard no Power BI pensando em deixar a leitura simples e direta.

Nele eu acompanho:

- faturamento total;
- faturamento por período;
- produtos mais vendidos;
- vendas por país;
- categorias de produtos;
- distribuição das vendas por região.

![Dashboard de vendas no Power BI](Imagens/Dashboard%20Vendas.png)

## Ferramentas utilizadas

- Power BI Desktop
- Power Query
- Excel
- GitHub

## Arquivos do projeto

- `Dashboard.pbix`: arquivo do Power BI com o dashboard final.
- `Vendas.xlsx`: planilha usada como base do projeto.
- `Imagens/`: prints da base original e do dashboard pronto.
- `docs/dicionario-dados.md`: descrição das colunas da base.
- `docs/processo-tratamento-dados.md`: resumo do tratamento feito nos dados.

## Como visualizar

1. Baixe este repositório.
2. Abra o arquivo `Dashboard.pbix` no Power BI Desktop.
3. Se o Power BI pedir, atualize o caminho da base para o arquivo `Vendas.xlsx`.
4. Explore os gráficos e filtros do dashboard.

## O que aprendi com esse projeto

Esse projeto me ajudou a praticar melhor o processo completo de uma análise no Power BI, desde a limpeza dos dados até a construção do dashboard.

Também foi uma forma de reforçar a importância de preparar bem a base antes de criar os gráficos, porque dados desorganizados podem atrapalhar muito a leitura dos resultados.

---

Projeto desenvolvido para meu portfólio de análise de dados.

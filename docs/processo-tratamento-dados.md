# Processo de Tratamento dos Dados

Este documento resume as principais etapas realizadas para transformar a base bruta de vendas em uma tabela pronta para análise no Power BI.

## 1. Análise inicial

A base `Vendas.xlsx` foi analisada para identificar a estrutura da tabela, os tipos de dados disponíveis e os principais problemas de qualidade.

Foram encontradas informações de vendas com colunas como data, produto, categoria, preço, custo, marca, quantidade, cliente e localidade.

## 2. Limpeza da base

No Power Query, a base passou por um processo de limpeza para melhorar a qualidade dos dados.

Principais ajustes realizados:

- Remoção de linhas vazias.
- Remoção de colunas vazias.
- Remoção de registros repetidos.
- Correção de espaços extras nos textos.
- Padronização de campos de texto.
- Ajuste dos nomes de clientes que estavam invertidos.

## 3. Padronização dos nomes

Alguns clientes estavam no formato:

```text
Sobrenome, Nome
```

Esses nomes foram tratados para ficarem mais legíveis no dashboard, facilitando filtros, segmentações e análises por cliente.

## 4. Organização da tabela final

Depois do tratamento, a base foi estruturada como uma tabela de vendas mais completa, permitindo análises por:

- Tempo.
- Produto.
- Categoria.
- Marca.
- Cliente.
- Localidade.
- Quantidade vendida.
- Receita.
- Custo.
- Lucro.

## 5. Construção do dashboard

Com a tabela limpa e organizada, foram criadas visualizações no Power BI para acompanhar os principais indicadores de vendas.

O dashboard final apresenta uma visão mais clara da performance comercial, permitindo entender melhor os resultados por produto, categoria, marca, cliente e região.

# 📊 Dashboard de Vendas Semanais | Power BI

## 🎓 Sobre o Projeto

Este dashboard foi desenvolvido **durante uma aula do curso de Power BI do Senac**, com o objetivo de aplicar na prática conceitos de **Business Intelligence, Power Query, modelagem de dados, DAX e visualização de informações**.

O projeto simula um cenário de vendas de uma rede de lojas (Contoso), permitindo acompanhar o faturamento semanal, identificar os principais vendedores e produtos, analisar a evolução das vendas ao longo dos dias e comparar o desempenho entre diferentes categorias de produtos.

## 🎯 Objetivo do Projeto

Desenvolver um dashboard interativo para acompanhar e analisar as vendas semanais, permitindo identificar os principais vendedores e produtos, acompanhar a evolução das vendas ao longo dos dias e comparar o desempenho entre diferentes categorias de produtos.

O objetivo é transformar os dados de vendas em informações visuais que facilitem o acompanhamento do desempenho comercial e auxiliem na tomada de decisões.

## 📂 Bases de Dados Utilizadas

O projeto utiliza duas bases de dados em Excel para alimentar o dashboard:

### 📋 cadastro_lojas.xlsx
Contém o cadastro das lojas da rede Contoso, com informações estruturais e de localização.

| Coluna | Descrição |
|--------|-----------|
| ID_LOJA | Identificador único da loja |
| Nome_Loja | Nome da loja |
| CNPJ | Cadastro Nacional da Pessoa Jurídica |
| Bairro | Bairro de localização |
| Cidade | Cidade da loja |
| Estado | Estado (UF) |
| Região | Região geográfica do Brasil |
| Data_Abertura | Data de inauguração da loja |
| Contato | Telefone para contato |
| Tipo_Loja | Classificação da loja (Física) |

**Dados disponíveis:**
- Loja Centro (Niterói/RJ) - Abertura: 15/03/2021
- Loja Icaraí (Niterói/RJ) - Abertura: 20/08/2023

---

### 📋 planilha_vendas.xlsx

#### Planilha1 - Vendas
Contém os registros de vendas realizadas, com detalhes de produtos, clientes e vendedores.

| Coluna | Descrição |
|--------|-----------|
| ID_LOJA | Identificador da loja (relacionamento com cadastro_lojas) |
| ID_VENDA | Identificador único da transação |
| Data | Data da venda |
| ID_PRODUTO | Código do produto |
| Produto | Nome do produto |
| Categoria | Categoria do produto |
| Subcategoria | Subcategoria do produto |
| Valor (R$) | Valor unitário do produto |
| Qtd | Quantidade vendida |
| Meio_Pagamento | Forma de pagamento (PIX, Cartão, Dinheiro) |
| ID_CLIENTE | Código do cliente |
| Nome_Cliente | Nome do cliente |
| Nome_Vendedor | Nome do vendedor responsável |
| ID_VENDEDOR | Código do vendedor |

**Principais produtos comercializados:**
- Notebook, Mouse, Teclado, Monitor, Headset, Webcam, Impressora, SSD 1TB, Cadeira Gamer

**Formas de pagamento:** PIX, Cartão de Crédito, Cartão de Débito, Dinheiro

---

#### Planilha2 - Produtos
Contém o catálogo de produtos com informações complementares.

| Coluna | Descrição |
|--------|-----------|
| Produto | Nome do produto |
| Categoria | Categoria do produto |
| Subcategoria | Subcategoria do produto |
| Preço (R$) | Preço sugerido |
| Prioridade | Classificação (Essencial/Desejável/Opcional) |
| Estoque | Disponibilidade em estoque (Sim/Não) |
| Observações | Informações adicionais sobre o produto |

> **Observação:** os arquivos estão disponíveis para download e podem ser utilizados para fins de estudo e reprodução do projeto.

## Perguntas de Negócio 📌

💰 **Desempenho de Vendas**

* Qual é o total de vendas no período?
* Qual é o faturamento total?
* As metas estabelecidas foram atingidas?
* Quanto ainda falta para atingir a meta?

📅 **Análise Temporal**

* Como as vendas evoluem ao longo dos dias?
* Quais dias apresentam maior volume de vendas?
* Existe variação significativa das vendas entre os dias da semana?
* Como as vendas atuais se comparam com períodos anteriores?

🏷️ **Produtos**

* Quais produtos possuem maior volume de vendas?
* Quais produtos representam maior impacto no faturamento?
* Existem produtos com aumento significativo de vendas?

👤 **Vendedores**

* Qual vendedor concentra maior volume de vendas?
* Como as vendas estão distribuídas entre os vendedores?
* Existem diferenças relevantes no comportamento dos vendedores?

📈 **Indicadores**

* Qual é o valor acumulado das vendas no período?
* Qual foi a variação das vendas em relação ao período anterior?
* Qual foi o desempenho por categoria de produto?
* Como está o desempenho em relação às metas estabelecidas?

## Processo 📍

* Importação e organização da base de dados
* Tratamento e padronização das informações
* Modelagem dos dados
* Criação de relacionamentos
* Criação de medidas e cálculos utilizando **DAX**
* Desenvolvimento de KPIs de vendas
* Criação de análises temporais
* Desenvolvimento de ranking por vendedores
* Desenvolvimento de ranking por produtos
* Desenvolvimento de filtros interativos
* Construção de layout estratégico e visual profissional

## 📸 Visualizações do Dashboard

### Página 1

![Dashboard de Vendas Semanais - Página 1](Capturar.JPG)

## 📥 Downloads

[**⬇️ Baixar Dashboard de Vendas Semanais (.pbix)**](Relatório_Vendas_V2.pbix)

[**⬇️ Baixar Base de Dados - cadastro_lojas.xlsx**](cadastro_lojas.xlsx)

[**⬇️ Baixar Base de Dados - planilha_vendas.xlsx**](planilha_vendas.xlsx)

> **Observação:** para abrir o arquivo `.pbix`, é necessário ter o **Power BI Desktop** instalado. As bases de dados em Excel podem ser abertas em qualquer editor de planilhas.

## 🛠️ Tecnologias Utilizadas

* **Power BI**
* **DAX**
* **Power Query**
* **Excel**

## 💡 Insights do Projeto

* Identificação dos produtos com maior volume de vendas (Notebooks, Monitores e Impressoras)
* Análise da evolução das vendas ao longo dos dias (01 a 06 de agosto)
* Comparação das vendas entre diferentes lojas (Centro e Icaraí)
* Identificação dos vendedores com maior participação nas vendas
* Análise do desempenho por categoria de produto
* Acompanhamento do faturamento total no período
* Monitoramento do desempenho em relação às metas estabelecidas
* Identificação dos dias com maior e menor volume de vendas
* Análise das formas de pagamento mais utilizadas

## 📊 Conclusão

Este projeto demonstra a aplicação prática de conceitos de **Business Intelligence, Power Query, modelagem de dados, DAX e visualização de informações**, desenvolvidos durante o **curso de Power BI do Senac**.

O dashboard permite uma visão geral das vendas e possibilita análises mais detalhadas por período, vendedor e produto, contribuindo para um melhor acompanhamento do desempenho comercial e para uma tomada de decisão baseada em dados.

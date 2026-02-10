📊 Projeto – Análise de Dados e Dashboards no Google Sheets
📌 Introdução

Este projeto consiste na análise de dados financeiros e operacionais utilizando Google Sheets, com foco em organização, tratamento dos dados, geração de estatísticas e criação de painéis analíticos para apoiar a interpretação e a tomada de decisão.

Os dados utilizados referem-se a operações de mercado de ações, permitindo explorar métricas estatísticas, comportamento de clientes e classificação de perfis com base em suas operações.

🎯 Objetivo

O objetivo do projeto é:

Organizar e tratar dados financeiros

Extrair métricas estatísticas relevantes

Criar análises dinâmicas por cliente

Classificar perfis de clientes com base no volume de operações

Desenvolver uma base sólida para visualizações e dashboards

🛠️ Ferramentas Utilizadas

Google Sheets

Funções estatísticas

Funções de data

Fórmulas condicionais

Validações e referências dinâmicas entre páginas

🗂️ Estrutura da Planilha

A planilha foi organizada em múltiplas páginas, cada uma com um propósito específico:

mercado_acoes: base principal de dados

estatística: cálculos estatísticos sobre os preços

cliente: análise individualizada por cliente

(outras páginas serão descritas conforme os requisitos seguintes)

✅ Requisitos Atendidos – Etapa Inicial
🔹 Preparação dos Dados

Carregamento do arquivo operacoes_mercado_acoes

Renomeação da página para mercado_acoes

Ajuste correto dos tipos de dados em todas as colunas

Análise das estatísticas de coluna para compreensão dos dados

🔹 Página “estatística”

Criação de uma página dedicada à análise estatística dos preços, contendo os seguintes cálculos:

Soma

Valor mínimo

Valor máximo

Média

Mediana

Moda

🔹 Tratamento de Datas

Na página mercado_acoes, foram criadas colunas auxiliares:

dia

mês

ano

Essas colunas extraem informações diretamente da coluna data, facilitando análises temporais.

🔹 Página “cliente”

Criação de uma página interativa onde:

O usuário pode inserir o e-mail do cliente

São exibidas automaticamente:

Contagem de operações de compra e venda

Soma das operações realizadas

Média de operações

🔹 Classificação de Perfil do Cliente

Com base no número de operações realizadas, o cliente é classificado automaticamente como:

Perfil Agressivo: mais de 20 operações

Perfil Moderado: entre 5 e 19 operações

Perfil Conservador: entre 0 e 4 operações

🔹 Normalização dos Dados

Normalização dos valores da coluna preço na página mercado_acoes, permitindo análises comparativas e redução de distorções causadas por escalas diferentes.

🔹 Filtros Dinâmicos

Criação de visualizações de filtro para facilitar a análise dos dados:

Filtro de operações de compra

Filtro de operações de venda

Esses filtros permitem segmentar rapidamente os dados conforme o tipo de operação.

🔹 Identificação de Cliente por Código

Implementação de campos dinâmicos onde, ao digitar o código do cliente:

Na página cliente:

Exibição automática do nome

Exibição automática do e-mail

Na página estatística:

Exibição automática do nome

Exibição automática do e-mail

🔹 Estatística Avançada

Na página estatística, além das métricas já existentes, foram adicionadas:

Variância do preço

Desvio padrão do preço

Essas métricas permitem avaliar a dispersão dos valores e a volatilidade dos preços.

🔹 Análise de Tendência Temporal

Criação da página tendencia_temporal, contendo:

Quantidade de operações realizadas em cada mês do ano de 2023

Visualização clara do comportamento mensal das operações

🔹 Previsão de Operações

Realização de uma previsão da quantidade de operações do mês 12

A previsão foi baseada no intervalo de dados do mês 1 ao mês 11

Cálculo do erro da previsão, subtraindo:

valor previsto – valor real do mês 12

Essa etapa demonstra a aplicação de conceitos básicos de previsão e validação de resultados.

🔹 Página “compra_venda”

Criação de uma tabela dinâmica a partir dos dados da página mercado_acoes

A tabela dinâmica exibe:

Quantidade de operações de compra e venda

Valor total somado de cada tipo de operação

Essa visualização permite entender rapidamente o volume e o valor financeiro movimentado por tipo de operação.

🔹 Página “cliente_compra_venda”

Criação de uma nova tabela dinâmica baseada nos dados de mercado_acoes

Para cada cliente, são apresentados:

Quantidade de operações de compra e venda

Valor total somado de cada tipo de operação

Essa análise facilita a comparação do comportamento de compra e venda entre diferentes clientes.

🔹 Página “cliente_lucro_prejuizo”

Criação de uma tabela dinâmica que apresenta:

Tickers da bolsa

Valor somado das operações de compra e venda

Aplicação de filtros dinâmicos por:

Ticker

E-mail do cliente

Essa estrutura permite análises personalizadas de desempenho financeiro por cliente e ativo.

🔹 Análise de Lucro por Cliente

Na página cliente_lucro_prejuizo, foram aplicados os seguintes filtros:

E-mail do cliente: gabriela.pereira87@exemplo.com

Tickers selecionados:

HAPV3

ITUB4

JBSS3

MGLU3

PETR4

SANB11

Com base nesses filtros, foi calculado o lucro total da cliente, considerando que:

Lucro = Total de Vendas – Total de Compras

Ou seja, o lucro não corresponde apenas ao valor vendido, mas sim ao resultado líquido entre compras e vendas para os ativos selecionados.

🔹 Página “gráficos”

Criação de uma página exclusiva chamada gráficos

Utilização dos dados consolidados da planilha entregue no módulo anterior

Organização visual focada em análise e interpretação dos dados

📈 Gráficos Criados

Foi desenvolvido um gráfico para cada uma das páginas abaixo, respeitando os critérios de:

Título em todos os gráficos

Tipos de gráficos sem repetição

Seleção de dados relevantes para cada contexto de análise

Os gráficos foram criados a partir das seguintes páginas:

estatística
Visualização de métricas estatísticas como média, mínimo, máximo, variância e desvio padrão.

tendencia_temporal
Gráfico representando a evolução da quantidade de operações ao longo dos meses, facilitando a análise de comportamento temporal.

compra_venda
Gráfico comparativo entre operações de compra e venda, evidenciando volume e valores totais.

cliente_compra_venda
Gráfico demonstrando o comportamento de compra e venda por cliente.

cliente_lucro_prejuizo
Gráfico focado no resultado financeiro (lucro ou prejuízo), considerando a diferença entre vendas e compras.

mercado_acoes
Gráfico baseado nos dados brutos do mercado de ações, permitindo uma visão geral das operações.

🎯 Resultado Final

A página gráficos consolida visualmente todas as análises realizadas ao longo do projeto, funcionando como um dashboard analítico, facilitando a compreensão dos dados e apoiando a tomada de decisão.

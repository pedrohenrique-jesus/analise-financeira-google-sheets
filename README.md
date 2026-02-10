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

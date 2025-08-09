# 🌟 Análise de Evasão de Clientes (Churn) na TelecomX 📊

![Status](https://img.shields.io/badge/status-concluído-brightgreen)

Análise exploratória de dados para identificar os principais fatores de evasão de clientes (churn) em uma empresa de telecomunicações e propor estratégias de retenção baseadas em evidências.

## 📖 Índice

- [O Problema de Negócio]
- [Tecnologias Utilizadas]
- [Pipeline da Análise]
- [Principais Descobertas (Insights)]
- [Recomendações Estratégicas]
- [Autora]

## 📌 O Problema de Negócio

A TelecomX, como toda empresa de telecomunicações, enfrenta um desafio crítico para seu crescimento sustentável: a **evasão de clientes (churn)**. Perder clientes não só impacta a receita, mas também gera custos elevados para adquirir novos.

O objetivo central deste projeto é mergulhar nos dados da empresa para responder à pergunta: **"Quais são os principais fatores que levam um cliente a cancelar seu contrato?"**. Ao identificar esses fatores, podemos fornecer à TelecomX insights acionáveis para desenvolver estratégias de retenção mais eficazes.

## 🛠️ Tecnologias Utilizadas

-   **Linguagem:** `Python 3`
-   **Bibliotecas:** `Pandas`, `Matplotlib`, `Seaborn`, `Numpy`
-   **Ambiente:** `Jupyter Notebook` / `Google Colab`
-   **Fonte de Dados:** Arquivo JSON com dados de clientes.

## 🚀 Pipeline da Análise

O projeto seguiu uma metodologia estruturada em três fases principais:

1.  **Coleta e Tratamento (ETL):** Os dados foram carregados de um arquivo JSON. Na sequência, foi realizada uma limpeza rigorosa, que incluiu a tradução de colunas, a transformação de variáveis categóricas em numéricas e o tratamento de valores inconsistentes e nulos, garantindo a qualidade e a confiabilidade dos dados.

2.  **Análise Exploratória de Dados (EDA):** Nesta fase, investigamos a fundo as variáveis. Analisamos a distribuição da variável alvo (`Churn`) e exploramos as relações entre a evasão e os diversos atributos dos clientes, como dados demográficos, tipos de contrato, métodos de pagamento e serviços contratados. A análise de correlação também foi utilizada para identificar relações lineares entre as variáveis numéricas.

3.  **Visualização de Dados:** Foram criados múltiplos gráficos (histogramas, box plots, countplots) com Matplotlib e Seaborn para ilustrar as distribuições, comparar segmentos de clientes e comunicar os insights de forma clara e visual.

## 💡 Principais Descobertas (Insights)

A análise revelou padrões claros no comportamento dos clientes que evadem:

-   **Taxa de Churn:** A base de dados revela uma taxa de churn de **26.6%**, um valor significativo que demanda atenção.
-   **Tipo de Contrato:** Contratos **mensais (Month-to-month)** são o principal fator de risco, apresentando uma taxa de evasão muito superior a contratos de longo prazo.
-   **Método de Pagamento:** O pagamento via **cheque eletrônico (Electronic check)** é um forte preditor de churn, sugerindo possíveis atritos nesse processo.
-   **Serviço de Internet:** Clientes com **fibra óptica (Fiber optic)**, apesar de ser um serviço premium, têm uma taxa de evasão mais alta, o que pode indicar problemas de qualidade, preço ou concorrência.
-   **Fidelidade e Gasto:** A evasão é **maior nos primeiros meses** de contrato e entre clientes com **contas mensais mais altas**, indicando sensibilidade a preço e valor percebido no início da jornada.

## 🎯 Recomendações Estratégicas

Com base nas descobertas, recomendamos as seguintes ações para a TelecomX:

1.  **Onboarding para Novos Clientes:** Desenvolver um programa de boas-vindas e suporte intensivo durante os primeiros três a seis meses, período mais crítico para a evasão.
2.  **Fidelização por Contrato:** Criar incentivos e ofertas agressivas para a migração de clientes de contratos mensais para planos anuais ou bianuais, aumentando a barreira de saída.
3.  **Otimização de Pagamentos:** Investigar o fluxo de pagamento com "cheque eletrônico" para identificar e remover atritos, além de incentivar a migração para métodos mais convenientes como débito automático.
4.  **Auditoria do Serviço de Fibra:** Realizar uma análise de qualidade e satisfação focada nos clientes de fibra óptica para entender as causas da alta evasão e melhorar a experiência do serviço.
5.  **Estratégias de Precificação:** Desenvolver ofertas e pacotes de retenção para clientes com contas mensais elevadas, demonstrando o valor dos serviços agregados e reforçando o custo-benefício.

## ✍️ Autora

Desenvolvido por **Evelyn Batista**.

https://github.com/evelyn-batista

# Análise de Evasão de Clientes (Churn) - Telecom X

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)

## 📖 Descrição do Projeto

Este projeto consiste em uma análise exploratória de dados (EDA) sobre a evasão de clientes (Churn) de uma empresa de telecomunicações fictícia, a **Telecom X**. O objetivo principal é mergulhar nos dados dos clientes para identificar os principais fatores e padrões que levam ao cancelamento dos serviços, transformando dados brutos em insights acionáveis para a área de negócio.

## 🎯 Problema de Negócio

O Custo de Aquisição de Cliente (CAC) é consistentemente mais alto do que o custo para manter um cliente existente. Portanto, a retenção de clientes é uma prioridade estratégica para a Telecom X. Com uma taxa de evasão de **25.72%** identificada na base de dados, a empresa enfrenta uma perda significativa de receita e base de clientes. A solução é entender **quem** está saindo e **por quê**, para que a empresa possa desenvolver estratégias de retenção proativas e eficazes.

## 🗂️ Metodologia

A análise foi conduzida utilizando um Jupyter Notebook em Python, seguindo as etapas padrão de um projeto de Data Science:

1.  **Extração de Dados**: Carregamento dos dados a partir de um arquivo `TelecomX_Data.json`.
2.  **Transformação e Limpeza**: Os dados, originalmente em formato aninhado, foram "achatados" para um formato tabular. Foram realizados tratamentos de tipos de dados e de valores ausentes (11 registros na coluna `TotalCharges` foram preenchidos com a mediana).
3.  **Análise Exploratória de Dados (EDA)**: Investigação estatística e visual dos dados para entender a distribuição das variáveis e a relação entre elas.
4.  **Visualização de Dados**: Foram criados gráficos interativos e estáticos (histogramas, gráficos de pizza e de barras) para visualizar a taxa de churn em relação a diferentes características demográficas, de contrato e de serviços.
5.  **Geração de Insights e Relatório Final**: Consolidação de todas as descobertas em um relatório estruturado, apontando as principais causas do churn e recomendando ações estratégicas.

## 💡 Principais Descobertas e Insights

A análise revelou perfis e fatores de risco claros para o churn:

* **Tipo de Contrato é Crucial**: Clientes com contrato **Mês a Mês** têm uma taxa de churn alarmante de **41.3%**, em comparação com apenas **2.8%** para clientes com contrato de dois anos.
* **Tempo de Casa (Tenure) Fideliza**: A evasão é massivamente concentrada nos **clientes novos**. Quanto mais tempo um cliente permanece, menor a sua chance de sair.
* **Serviço de Fibra Óptica em Alerta**: Clientes com **Fibra Óptica** evadem significativamente mais (taxa de **40.6%**) do que os com DSL. Isso pode indicar problemas de preço, qualidade ou instabilidade do serviço.
* **Faturamento e Forma de Pagamento**: Clientes com cobranças mensais mais altas (na faixa de R$70-100) e que pagam via **cheque eletrônico** (taxa de churn de 43.8%) são mais propensos a cancelar.

## 🚀 Recomendações de Negócio

Com base nas descobertas, as seguintes ações são recomendadas para reduzir o churn:

1.  **Foco na Migração de Contratos**: Criar campanhas agressivas com descontos e benefícios para incentivar clientes do plano "Mês a Mês" a migrarem para contratos de 1 ou 2 anos.
2.  **Atenção aos Clientes de Fibra**: Realizar uma investigação aprofundada (pesquisas de satisfação, análise técnica) para entender a alta evasão no serviço de Fibra Óptica e agir na causa-raiz.
3.  **Programa de Onboarding**: Implementar um programa de boas-vindas e acompanhamento nos primeiros 3 meses de contrato para melhorar a experiência inicial do cliente e reduzir o churn precoce.
4.  **Incentivo a Pagamentos Automáticos**: Oferecer pequenos descontos para clientes que cadastrarem o pagamento em débito automático ou cartão de crédito, reduzindo o atrito e a evasão associada ao "cheque eletrônico".

## 🛠️ Tecnologias Utilizadas

* **Linguagem**: Python 3
* **Bibliotecas**: Pandas, NumPy, Matplotlib, Seaborn, Plotly
* **Ambiente**: Visual Studio Code

## ✍️ Autor
* Projeto desenvolvido po Bruno H. Cavasana, resultado do Challenge Telecom X: análise de evasão de clientes, parte da Especialização em Data Science, parte do **Programa ONE: Oracle Next Education** em parceria com a **Alura**.

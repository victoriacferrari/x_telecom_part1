# 📊 Análise de Churn em Empresa de Telecomunicações

## Descrição

Este projeto realiza uma análise exploratória de dados (EDA) para identificar fatores associados à **evasão de clientes (churn)** em uma empresa de telecomunicações. O objetivo é entender o comportamento dos clientes que cancelam o serviço e propor **estratégias de retenção e fidelização**.

O notebook está estruturado para:

* Carregar dados diretamente de um arquivo JSON hospedado no GitHub.
* Limpar e transformar dados para análise.
* Explorar métricas descritivas de variáveis numéricas e categóricas.
* Visualizar padrões de churn por contrato, serviço de internet, método de pagamento, antiguidade e gasto.
* Gerar insights e recomendações estratégicas.

---

## Tecnologias e Bibliotecas

* **Python 3**
* **Pandas**: manipulação e limpeza de dados
* **Requests**: download de arquivos JSON do GitHub
* **Matplotlib / Seaborn**: visualização de dados

---

## Estrutura do Notebook

1. **Importação de bibliotecas**
2. **Carregamento dos dados** do arquivo JSON
3. **Exploração inicial** (shape, colunas, valores nulos)
4. **Limpeza e transformação** (conversão de tipos, criação de coluna de faturamento diário)
5. **Análise Exploratória (EDA)**

   * Métricas descritivas de variáveis numéricas
   * Frequência e análise de variáveis categóricas
   * Visualizações de churn por diferentes variáveis
6. **Insights e Recomendações**

---

## Insights Principais

* Clientes com **contratos mensais** têm maior churn do que contratos de 1 ou 2 anos.
* **Clientes novos** (0–6 meses) e de **baixo gasto** são mais propensos a abandonar o serviço.
* Usuários de **Fibra Óptica** e métodos de pagamento como **cheque eletrônico** apresentam maior risco de churn.
* Os primeiros meses do cliente são críticos para estratégias de retenção.

---

## Recomendações Estratégicas

1. Incentivar contratos de longo prazo com benefícios adicionais.
2. Criar plano de fidelização nos primeiros meses do cliente.
3. Monitorar clientes de baixo tenure e baixo gasto com alertas e campanhas.
4. Melhorar a experiência de usuários de Fibra Óptica.
5. Otimizar métodos de pagamento, incentivando opções automáticas e seguras.
6. Implementar modelos preditivos de churn para ações preventivas.

---


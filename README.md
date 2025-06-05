# Projeto Churn de Clientes - Telecom X

Este projeto faz parte da iniciativa da empresa Telecom X para compreender e reduzir a evasão de clientes (churn). A análise é conduzida em três camadas: Bronze (Extração), Silver (Transformação) e Gold (Análise e Visualização).

## Objetivo

Identificar padrões e fatores associados à evasão de clientes, gerando insights valiosos para a equipe de Data Science, que poderá utilizá-los na construção de modelos preditivos.

## Tecnologias Utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn

## Etapas do Projeto

### ✨ Camada Bronze - Extração

* Importação dos dados via API ou fonte JSON.
* Conversão dos dados para um DataFrame Pandas.
* Expansão de colunas aninhadas (ex: `customer`, `phone`, `internet`, `account`).

### 🌟 Camada Silver - Transformação

* Verificação e tratamento de dados ausentes, duplicados e inconsistências.
* Criação da coluna `Contas_Diarias` (valor do faturamento mensal / 30).
* Conversão de variáveis categóricas (ex: "Sim" / "Não") para formato binário (1 / 0).
* Renomeação e padronização de colunas para clareza.

### 🔍 Camada Gold - Análise e Visualização

* Análise descritiva (média, mediana, desvio padrão, etc.).
* Visualização da proporção de clientes que cancelaram e os que permaneceram.
* Estudo de churn por variáveis categóricas: gênero, contrato, pagamento.
* Análise por variáveis numéricas: total gasto, tempo de contrato.
* (Opcional) Análise de correlação entre variáveis e churn.

![Matriz de correlaçao](https://github.com/user-attachments/assets/48ed7b9b-e0ad-46ad-ab23-33d7e7053661)



## Recomendações

* Verificar se todas as etapas estão completas, especialmente as transformações de dados.
* Confirmar a criação da coluna `Contas_Diarias`.
* Avaliar se as visualizações estão claras e explicativas.
* Considerar adicionar uma matriz de correlação para identificar relações relevantes.

---

Este projeto foi desenvolvido com foco em boas práticas de ETL e Data Analysis.



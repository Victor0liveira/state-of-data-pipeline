# state-of-data-pipeline
Pipeline de Big Data Analytics com AWS — POSTECH Fase 3
# 🏗️ State of Data Brasil — Pipeline AWS

Pipeline completo de Big Data Analytics com AWS para análise do mercado
brasileiro de dados. Projeto da Fase 3 do curso DTAT — POSTECH.

## 🎯 Objetivo
Construir uma solução de Engenharia de Dados e Analytics para analisar
o perfil dos profissionais de dados no Brasil (2021–2023), apoiando uma
Instituição Financeira na tomada de decisão sobre contratação e investimentos.

## 🏛️ Arquitetura AWS


## 📁 Estrutura
├── notebooks/
│   └── state_of_data_pipeline.ipynb  # Pipeline PySpark completo
├── assets/
│   ├── arquitetura_aws.png           # Diagrama Draw.io
│   ├── crescimento_mercado.png       # Gráficos de análise
│   └── salarios_2023.png
└── README.md

## 📊 Dataset
- Fonte: [State of Data Brasil — Kaggle/Data Hackers](https://www.kaggle.com/datahackers/datasets)
- 3 pesquisas: 2021, 2022 e 2023
- Total: 12.209 respondentes

## 🔍 Principais Insights

| Indicador | Resultado |
|---|---|
| Crescimento de respondentes | +107% (2021→2023) |
| Gênero masculino | 75,1% |
| Gênero feminino | 24,4% |
| Cargo mais comum | Analista de Dados |
| Faixa salarial mais frequente | R$ 8.001 a R$ 12.000/mês |
| Senioridade dominante | Sênior (36,8%) |

## ☁️ Serviços AWS Utilizados
- **Amazon S3** — Data Lake (camadas Bronze, Silver e Gold)
- **AWS Glue** — ETL e catalogação com PySpark
- **Amazon Athena** — Consultas analíticas SQL
- **AWS Glue Data Catalog** — Catalogação das tabelas

## 🛠️ Tecnologias
Python · PySpark · AWS Glue · Amazon S3 · Amazon Athena · Draw.io

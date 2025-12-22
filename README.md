# Projeto Final — IAA 2025/2026
## Consumo Energético — Clustering e Previsão

### Autores
- **110942** — Luís Lourenço  
- **101018** — Miguel Bento  

## Descrição

Este repositório contém o código, notebook e materiais associados ao **Projeto Final da unidade curricular Introdução à Aprendizagem Automática (IAA)**.

O objetivo do projeto é analisar consumos energéticos de edifícios institucionais do Município da Maia, recorrendo a técnicas de **clustering** e **previsão de séries temporais**, com foco na interpretabilidade dos resultados e na avaliação da previsibilidade por perfil energético.

Foram abordados:
- **Clustering**: K-Means e DBSCAN  
- **Modelos de previsão**:  
  - Baseline semanal  
  - ARIMA  
  - Random Forest  
  - XGBoost  

## Estrutura do Repositório
.
├── IAA_notebook_final.ipynb # Notebook principal do projeto
├── IAA_relatorio_markdown.pdf # Relatório final (PDF, sem código)
├── figures/ # Figuras utilizadas no relatório
├── *.pkl # Caches intermédias (modelos e resultados)
└── README.md # Descrição do projeto

## Reprodutibilidade

Todo o código, análises, figuras e resultados intermédios estão documentados e podem ser reproduzidos a partir do notebook principal:

- `IAA_notebook_final.ipynb`

O relatório em PDF **não contém código**, sendo complementado pelo notebook disponível neste repositório.

## Dependências Principais

O notebook foi executado num ambiente Python padrão para ciência de dados, utilizando principalmente:

- `pandas`
- `numpy`
- `scikit-learn`
- `statsmodels`
- `xgboost`
- `matplotlib`

## Nota Final

Este projeto segue o processo **CRISP-DM** (sem fase de deployment), com especial foco na coerência entre:
- caracterização dos dados,
- segmentação energética,
- e desempenho dos modelos de previsão por cluster.

Os resultados obtidos demonstram que a previsibilidade do consumo energético varia significativamente entre edifícios, estando fortemente ligada ao perfil energético identificado na fase de clustering.

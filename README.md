<div align="left">
  
## 🏠 Predição de Preços de Imóveis (King County)
Este projeto realiza um estudo comparativo de diversos algoritmos de Machine Learning para regressão, utilizando o dataset House Sales in King County, USA. O objetivo é prever o valor de venda de imóveis com base em suas características físicas e localização.

## 🚀 O que este projeto faz?
- Análise Exploratória: Investigação de 21 atributos de mais de 21 mil imóveis.

- Pré-processamento: Limpeza de dados, remoção de colunas irrelevantes e tratamento de variáveis.

- Modelagem Comparativa: Teste de múltiplos algoritmos para identificar o melhor desempenho.

- AutoML: Experimentos com aprendizado de máquina automatizado.

## 🛠️ Tecnologias Utilizadas
- Linguagem: Python

- Manipulação de Dados: Pandas e NumPy

- Machine Learning: Scikit-Learn

- AutoML: Auto-Sklearn

## 📊 Comparativo de Modelos
A tabela abaixo resume os experimentos realizados e o desempenho relativo de cada abordagem.

## 🤖 Modelos Aplicados

| Modelo Aplicado     | Tipo de Algoritmo        | Desempenho / Status              |
|---------------------|--------------------------|----------------------------------|
| Random Forest       | Ensemble (Árvores)       | 🏆 Melhor Resultado              |
| KNN Regressor       | Baseado em Distância     | ✅ Concluído (Baseline)          |
| Regressão Linear    | Linear                   | ✅ Concluído (Baseline)          |
| Decision Tree       | Árvore de Decisão        | ✅ Concluído                     |
| SVM                 | Vetor de Suporte         | ✅ Concluído                     |
| AutoML              | Automatizado             | ⚠️ Requer mais recursos         |

## 📈 Resultados Finais

| Modelo              | R²       | MAE        | MSE              | RMSE        |
|---------------------|----------|------------|------------------|-------------|
| KNN Regressor       | 0.7915   | 93,907     | 28,821,924,310   | 169,770     |
| Regressão Linear    | 0.7013   | 126,731    | 41,284,147,130   | 203,185     |
| SVR                 | -0.0510  | 221,281    | 145,268,789,903  | 381,141     |
| Decision Tree       | 0.7185   | 100,239    | 38,907,246,083   | 197,249     |
| **Random Forest**   | **0.8800** | **70,005** | **16,585,234,011** | **128,784** |




</div>

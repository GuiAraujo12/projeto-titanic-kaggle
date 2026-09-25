# 🚢 Titanic Machine Learning - Kaggle

Projeto em Python para prever a sobrevivência dos passageiros do Titanic utilizando Machine Learning.

## 🛠️ O que foi feito
1. **Limpeza de Dados:** Tratamento de valores nulos nas colunas de idade, cabine e porto de embarque.
2. **Engenharia de Atributos:** Criação do tamanho da família (`FamilySize`), conversão da cabine em binária (`Has_Cabin`) e extração de títulos dos nomes (`Title`).
3. **Modelagem:** Testes com Regressão Logística e Random Forest.
4. **Subscrição:** Geração do ficheiro `submission.csv` para submissão no Kaggle.

## 🚀 Tecnologias e Ferramentas
* Python, Pandas, Scikit-Learn e Jupyter Notebook.
* **[Dash Analyzer](https://github.com/GuiAraujo12/projeto-analise-de-dados):** Aplicação própria em Flask, Pandas e Plotly utilizada para a geração dos gráficos de análise exploratória.

## 📁 Estrutura
* `titanic_ml.ipynb`: Notebook principal com o código e pipeline.
* `submission.csv`: Previsões finais submetidas no Kaggle.
* `analise_imagens/`: Pasta com os gráficos da análise.
# Rossmann Store Sales Prediction

Este projeto visa prever as vendas diárias das lojas Rossmann com várias semanas de antecedência para auxiliar na tomada de decisões estratégicas.

## Dados
Os dados utilizados estão disponíveis publicamente no Kaggle:
- [Rossmann Store Sales](https://www.kaggle.com/c/rossmann-store-sales/data)

## Requisitos
- Python 3.7+
- Bibliotecas listadas em `requirements.txt`

## Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/rossmann-sales-prediction.git
   cd rossmann-sales-prediction

------------------------------------
Metodologia: <br>
- Análise Exploratória: Compreensão dos dados e identificação de padrões<br>

- Pré-processamento: Limpeza, transformação e engenharia de features<br>

- Modelagem: Treinamento e avaliação de modelos de machine learning<br>

- Avaliação: Métricas de performance e análise de feature importance<br>

- Impacto Financeiro: Cálculo do retorno sobre o investimento<br><br>

Resultados:<br>
- O modelo XGBoost obteve os melhores resultados com:

- RMSE: 1,045.23 (11.2% da média de vendas)

- Principais features: Dia da semana, promoções, distância da competição

- Impacto financeiro estimado:

- Economia/ganho anual para a rede: €2,850,000


- numpy==1.21.5<br>
- pandas==1.3.5<br>
- matplotlib==3.5.1<br>
- seaborn==0.11.2<br>
- scikit-learn==1.0.2<br>
- xgboost==1.5.2<br>
- jupyter==1.0.0<br>
- statsmodels==0.13.2<br>

---------------------------------------------
🛠️ Ferramentas e Tecnologias Utilizadas<br><br>
Linguagens e Bibliotecas:<br>
- Python 3.8+

Bibliotecas Principais:<br>

- pandas - Manipulação de dados

- numpy - Cálculos numéricos

- matplotlib e seaborn - Visualização de dados

- scikit-learn - Modelos de machine learning e métricas

- xgboost - Implementação do algoritmo XGBoost

- statsmodels - Análise estatística

- joblib - Serialização do modelo<br><br>

Ambiente de Desenvolvimento:<br>
- Jupyter Notebook - Para exploração interativa e desenvolvimento

- Google Colab (opcional) - Ambiente em nuvem alternativo

Controle de Versão:<br>
- Git - Versionamento do código

- GitHub - Hospedagem do repositório

Pré-processamento de Dados:<br>
- Engenharia de Features:

- Criação de variáveis temporais (dia da semana, mês, ano)

- Transformação de variáveis categóricas (one-hot encoding)

- Tratamento de valores nulos

- Cálculo de features derivadas (tempo desde abertura da concorrência)

Modelagem Preditiva
Algoritmos Implementados:

- Random Forest Regressor

- XGBoost Regressor

Validação:<br>

- Train-Test Split (80/20)

- Métricas de avaliação (MAE, MSE, RMSE)

Visualização e Análise<br>
- Gráficos de distribuição (histogramas, KDE)

- Boxplots para análise comparativa

- Série temporal das vendas

- Feature importance (importância das variáveis)

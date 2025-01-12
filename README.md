# <h1 align="center"># Metricas_de_Avaliacao_de_Desempenho</h1>

![Python](https://img.shields.io/badge/language-Python-blue.svg)
![Versão](https://img.shields.io/badge/version-1.0.0-blue.svg)
![GitHub last commit](https://img.shields.io/github/last-commit/Danieltandrade/Metricas_de_Avaliacao_de_Desempenho)
![GitHub](https://img.shields.io/github/license/Danieltandrade/Metricas_de_Avaliacao_de_Desempenho.svg)
![GitHub repo file or directory count](https://img.shields.io/github/directory-file-count/Danieltandrade/Metricas_de_Avaliacao_de_Desempenho)


Este repositório contém um projeto de **classificação de e-mails** utilizando o algoritmo **Naive Bayes** para prever se um e-mail é **spam** ou **ham** (não spam). O objetivo principal deste projeto é acadêmico, focando em demonstrar as principais **métricas de avaliação de modelos de classificação**, como **Matriz de Confusão**, **Acurácia**, **Sensibilidade**, **Especificidade**, **Precisão**, **F1-Score** e **Curva ROC**.

## Objetivo

O classificador é treinado com um conjunto de dados de e-mails contendo duas categorias: **spam** e **ham**. Utilizando o algoritmo **Naive Bayes Multinomial**, o modelo é treinado para aprender padrões a partir dos textos dos e-mails, e posteriormente classificar e-mails novos. As métricas de avaliação ajudam a entender a qualidade do modelo e a eficácia do classificador.

## Estrutura do Repositório


## Como Executar

### Requisitos

1. **Python 3.x**: Certifique-se de ter o Python instalado. Você pode verificar a versão do Python com o comando:
   ```bash
   python --version

Instalar as dependências: O projeto utiliza as bibliotecas descritas no arquivo requirements.txt. Para instalar as dependências, utilize o seguinte comando:

pip install -r requirements.txt

## Bibliotecas Utilizadas
pandas: Para manipulação de dados e pré-processamento.
scikit-learn: Para construção do modelo de classificação Naive Bayes e avaliação das métricas.
matplotlib e seaborn: Para visualização de gráficos como a Matriz de Confusão e a Curva ROC.
kagglehub: Para download do conjunto de dados diretamente do Kaggle.

## Métricas de Avaliação
O modelo é avaliado com as seguintes métricas:

- Acurácia: Proporção de previsões corretas em relação ao total de exemplos.
- Sensibilidade (Recall): A capacidade do modelo de identificar e-mails spam corretamente.
- Especificidade: A capacidade do modelo de identificar e-mails não spam corretamente.
- Precisão: Proporção de e-mails classificados como spam que são realmente spam.
- F1-Score: A média harmônica entre a Precisão e a Sensibilidade, útil em cenários com classes desbalanceadas.
- Curva ROC: Visualiza a taxa de verdadeiros positivos (TPR) versus a taxa de falsos positivos (FPR), e a Área Sob a Curva (AUC), que indica a performance do modelo.

## Contribuições
Se você quiser contribuir para este projeto, fique à vontade para abrir issues ou pull requests. Todos os tipos de contribuição são bem-vindos!

## Licença
Este projeto está licenciado sob a MIT License.
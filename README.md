# Classificador de E-mails Spam/Ham com Métricas de Avaliação de Desempenho

## Objetivo

O objetivo deste projeto é desenvolver um classificador de e-mails spam/ham utilizando o algoritmo Naive Bayes e avaliar seu desempenho com métricas de avaliação de desempenho.

## Estrutura do Repositório

```bash
.
├── notebooks
│   └── Metricas_Avaliacao_de_Desempenho.ipynb
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```
* `notebooks`: Pasta contendo os notebooks do projeto.
* `requirements.txt`: Arquivo contendo as dependências do projeto.

## Como Executar

Para executar o script, você pode usar o Google Colab ou Jupyter Notebook. Basta seguir os passos abaixo:

1. Abra o Google Colab ou Jupyter Notebook.
2. Clone o repositório ou faça o upload do arquivo `Metricas_Avaliacao_de_Desempenho.ipynb` para o Colab ou Jupyter Notebook.
3. Execute o script `Metricas_Avaliacao_de_Desempenho.ipynb` para treinar o modelo e avaliar seu desempenho.

> [!IMPORTANT]
> No arquivo "Metricas_Avaliacao_de_Desempenho.ipynb" há um exemplo de como executar o download do dataset direto do Kaggle dentro do ambiente do Google Colab, mas este código deverá ser modificado para o caso de outro ambiente de desenvolvimento.

## Métricas de Avaliação

* Acurácia: Proporção de previsões corretas em relação ao total de exemplos.
* Sensibilidade (Recall): A capacidade do modelo de identificar e-mails spam corretamente.
* Especificidade: A capacidade do modelo de identificar e-mails não spam corretamente.
* Precisão: Proporção de e-mails classificados como spam que são realmente spam.
* F1-Score: A média harmônica entre a Precisão e a Sensibilidade, útil em cenários com classes desbalanceadas.
* Curva ROC: Visualiza a taxa de verdadeiros positivos (TPR) versus a taxa de falsos positivos (FPR), e a Área Sob a Curva (AUC), que indica a performance do modelo.

Os cálculos de avaliação são feitos com base nos valores extraídos da matriz de confusão e foram executados em várias partes de forma manual para melhor entendimento dos resultados, com exeção da curva ROC, que se demonstrou mais complexa e foi realizada com o uso de uma biblioteca scikit-learn, utilizando o módulo `sklearn.metrics`.

## Dataset

O dataset utilizado neste projeto foi obtido do Kaggle e pode ser encontrado no seguinte link:

* [Spam Email Classification](https://www.kaggle.com/datasets/ashfakyeafi/spam-email-classification)

## Projeto no Colab

Este projeto foi realizado no Google Colab e pode ser encontrado no seguinte link:

* [Metricas de Avaliação de Desempenho](https://colab.research.google.com/drive/1tAzR0jGypBXUgbz4M1rVUukUYLvTXweb#scrollTo=k55AHaaupAro)

## Agradecimentos

Gostaria de agradecer ao criador do dataset, [Ashfak Yeafi](https://www.kaggle.com/ashfakyeafi), por disponibilizar o dataset de classificação de e-mails spam.

## Contribuições

Se você quiser contribuir para este projeto, fique à vontade para abrir issues ou pull requests. Todos os tipos de contribuição são bem-vindos!

## Licença

Este projeto está licenciado sob a MIT License. Veja o arquivo `LICENSE` para mais detalhes.

## Conclusão

O classificador de e-mails spam/ham foi desenvolvido utilizando o algoritmo Naive Bayes e demonstrou um resultado satisfatório, mas creio que com ajustes nos hiperparametros ou com o uso de outras tecnicas de classificação, poderia ser melhorado ainda mais. Grande abraço a todos.
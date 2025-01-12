# <h1 align="center">Classificador de E-mails Spam/Ham com Métricas de Avaliação de Desempenho</h1>

## Objetivo

Este projeto visa desenvolver um classificador de e-mails spam/ham utilizando o algoritmo Naive Bayes e avaliar seu desempenho com métricas de avaliação de desempenho.

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

## Métricas de Avaliação

* Acurácia: Proporção de previsões corretas em relação ao total de exemplos.
* Sensibilidade (Recall): A capacidade do modelo de identificar e-mails spam corretamente.
* Especificidade: A capacidade do modelo de identificar e-mails não spam corretamente.
* Precisão: Proporção de e-mails classificados como spam que são realmente spam.
* F1-Score: A média harmônica entre a Precisão e a Sensibilidade, útil em cenários com classes desbalanceadas.
* Curva ROC: Visualiza a taxa de verdadeiros positivos (TPR) versus a taxa de falsos positivos (FPR), e a Área Sob a Curva (AUC), que indica a performance do modelo.

## Contribuições

Se você quiser contribuir para este projeto, fique à vontade para abrir issues ou pull requests. Todos os tipos de contribuição são bem-vindos!

## Licença

Este projeto está licenciado sob a MIT License.
# wine-quality-classification_Cibele


Claro. Para um projeto acadêmico como esse, o README pode ser mais enxuto e direto:

# 🍷 Classificação da Qualidade de Vinhos com Machine Learning

## Objetivo

Desenvolver um modelo de Machine Learning capaz de prever a qualidade de vinhos a partir de características físico-químicas.

A variável qualidade foi transformada em classificação binária:

- Alta Qualidade (nota ≥ 7)
- Baixa/Média Qualidade (nota < 7)

## Dataset

**Wine Quality Dataset**

Fonte: https://www.kaggle.com/datasets/yasserh/wine-quality-dataset

## Etapas Desenvolvidas

- Análise exploratória dos dados (EDA)
- Análise de correlações
- Identificação de outliers
- Avaliação do balanceamento das classes
- Pré-processamento dos dados
- Treinamento dos modelos
- Avaliação de desempenho

## Modelos Utilizados

- Regressão Logística
- Random Forest

## Resultados

| Modelo | Accuracy | Precision | Recall | F1-Score |
|----------|----------:|----------:|----------:|----------:|
| Regressão Logística | 86,46% | 52,38% | 34,38% | 41,51% |
| Random Forest | 91,27% | 75,00% | 56,25% | 64,29% |

### Modelo Selecionado

✅ Random Forest

Apresentou o melhor desempenho em todas as métricas, sendo escolhido como modelo final para previsão da qualidade dos vinhos.

## Principais Insights

- O teor alcoólico foi uma das variáveis mais relevantes.
- A acidez volátil apresentou correlação negativa com a qualidade.
- Sulfatos e ácido cítrico contribuíram positivamente para a classificação.
- O Random Forest apresentou maior capacidade de identificar vinhos de alta qualidade.

## Estrutura do Projeto

```text
data/
notebooks/
results/
presentation/
video/
```

## Tecnologias

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Autora

Cibele Dinorah dos Reis

Tech Challenge – Fase 2 | FIAP



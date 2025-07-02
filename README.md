# Classificação de Avaliação de Veículos

Este projeto realiza uma análise detalhada do Car Evaluation Dataset da UCI, com o objetivo de identificar padrões entre atributos técnicos e funcionais de veículos que influenciam sua classificação final. O trabalho segue uma abordagem estruturada de análise exploratória, validação de hipóteses e pré-processamento dos dados, visando a futura aplicação de modelos de classificação.

## Estrutura do Projeto

A estrutura do projeto está organizada da seguinte maneira:

- `MVP_Puc_Final.ipynb`: Notebook principal com todas as etapas documentadas — desde a introdução e formulação do problema, análise exploratória dos dados, validação de hipóteses e codificação ordenada das variáveis.
- `car.csv`: Arquivo com o conjunto de dados original, extraído da UCI Machine Learning Repository.
- `requirements.txt`: Lista de bibliotecas usadas no notebook, caso queira recriar o ambiente localmente.

## Como Executar

1. Clone o repositório

```bash
git clone https://github.com/Szyfman/MVP_Puc_Final.git
cd MVP_Puc_Final
```

2. Abra o notebook no Google Colab ou localmente:

**Google Colab**:  
Acesse diretamente pelo link abaixo, com todos os dados já conectados:  
[Executar no Google Colab](https://colab.research.google.com/github/Szyfman/MVP_Puc_Final/blob/main/MVP_Puc_Final.ipynb)

**Localmente (opcional)**:
Se preferir executar localmente, certifique-se de ter o Jupyter Notebook instalado:

```bash
jupyter notebook MVP_Puc_Final.ipynb
```

## Resultados do Projeto

A análise revelou que atributos como **segurança**, **capacidade de passageiros** e **custo de manutenção** são fortemente associados à avaliação final do veículo, enquanto outros como o tamanho do porta-malas têm menor impacto. O dataset apresentou um desbalanceamento significativo da variável alvo, com predominância da classe `unacc`.

Com o pré-processamento finalizado, o dataset está pronto para ser utilizado em modelos de machine learning supervisionados, respeitando a ordem natural dos atributos categóricos.

## Aprendizados e Próximos Passos

- **Aprendizados**: A importância de explorar hipóteses de forma guiada, realizar visualizações específicas para atributos categóricos e respeitar a semântica dos dados no pré-processamento.
- **Próximos Passos**:
  - Aplicar modelos de classificação como Decision Trees, Random Forest e Gradient Boosting.
  - Avaliar o impacto do desbalanceamento da variável alvo em diferentes métricas.
  - Explorar estratégias de balanceamento (ex: oversampling, under-sampling).
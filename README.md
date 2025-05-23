# Classificação da Qualidade do Leite com Aprendizado Semi-Supervisionado 🥛🧠

[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)

Este repositório apresenta uma análise e classificação da qualidade de amostras de leite, com ênfase em técnicas de **aprendizado semi-supervisionado**. O objetivo é identificar automaticamente amostras de boa ou má qualidade utilizando tanto dados rotulados quanto não rotulados, potencializando o valor das bases de dados parciais e otimizando o controle de qualidade na cadeia produtiva do leite.

---

## 🌟 Relevância do Aprendizado Semi-Supervisionado

Em muitos cenários reais, especialmente no agronegócio e na indústria alimentícia, **apenas uma parte dos dados é rotulada**, devido a custos ou limitações laboratoriais. O **aprendizado semi-supervisionado** permite:

- **Aproveitar grandes volumes de dados não rotulados**, comuns em laboratórios e fazendas.
- **Reduzir custos com rotulagem**, já que modelos podem aprender padrões gerais a partir dos poucos exemplos rotulados e refinar suas decisões com os não rotulados.
- **Aumentar a precisão e robustez** dos sistemas de classificação, principalmente em situações de variabilidade de dados.
- **Promover inovação no controle de qualidade**, democratizando o uso de inteligência artificial mesmo em contextos com poucos rótulos disponíveis.

---

## 🎯 Objetivos do Projeto

- Analisar e explorar dados de amostras de leite coletados.
- Demonstrar a aplicação prática de **modelos semi-supervisionados** para classificação de qualidade do leite.
- Comparar resultados com abordagens supervisionadas tradicionais.
- Avaliar desempenho, vantagens e limitações dos métodos semi-supervisionados.
- Disponibilizar um **notebook interativo** para experimentação, adaptação e replicação.

---

## 🗂️ Etapas do Projeto

1. **Carregamento dos dados** (`qualidade_leite.csv`), incluindo exemplos rotulados e não rotulados.
2. **Limpeza, análise e pré-processamento** dos dados.
3. **Exploração dos dados** (visualizações, estatísticas, padrões).
4. **Construção de modelos semi-supervisionados** (ex: Label Propagation, Label Spreading, Semi-Supervised SVM).
5. **Treinamento, avaliação e comparação** com modelos supervisionados.
6. **Discussão dos ganhos e limitações** do aprendizado semi-supervisionado para o problema.

---

## 📚 Tecnologias Utilizadas

- [Python 3.8+](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Scikit-learn](https://scikit-learn.org/) — Modelos semi-supervisionados e supervisionados
- [Matplotlib](https://matplotlib.org/) e [Seaborn](https://seaborn.pydata.org/) — Visualização

---

## ⚡ Como Rodar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/Joaovmir/classificacao_qualidade_leite.git
cd classificacao_qualidade_leite
````

### 2. Instale as dependências

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 3. Estrutura dos Dados

A pasta `dados/` deve conter:

* `qualidade_leite.csv`
  Base de dados com atributos físico-químicos e/ou microbiológicos das amostras, com algumas linhas rotuladas quanto à qualidade e outras não.

### 4. Execute o notebook

Abra e execute o arquivo `classificacao_amostras_leite.ipynb` em seu ambiente Jupyter, VS Code ou Colab.

---

## 📁 Estrutura do Projeto

```
classificacao_qualidade_leite/
├── classificacao_amostras_leite.ipynb
├── dados/
│   └── qualidade_leite.csv
├── README.md
```

---

## 🔎 Possíveis Expansões

* Ajuste fino dos hiperparâmetros dos modelos.
* Análise da sensibilidade conforme a quantidade de rótulos disponíveis.
* Adaptação do pipeline para outras cadeias produtivas agroindustriais.

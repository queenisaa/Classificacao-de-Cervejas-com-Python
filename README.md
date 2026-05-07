# Classificao-de-Cervejas-com-Python

# 🍺 Classificação da Qualidade de Cervejas com Ciência de Dados

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como trabalho acadêmico da disciplina de Ciência de Dados, com o objetivo de aplicar técnicas de análise de dados e Machine Learning para classificar a qualidade de cervejas a partir de avaliações presentes em uma base de dados pública.

O projeto utiliza Python para realizar todo o processo de:

* Coleta e carregamento dos dados
* Tratamento e limpeza da base
* Análise exploratória
* Visualização de dados
* Criação da variável alvo
* Treinamento de modelos de classificação
* Avaliação dos resultados

---

## 📂 Base de Dados

A base utilizada foi o dataset **Beer Reviews Dataset**, disponível no Kaggle:

🔗 [https://www.kaggle.com/datasets/rdoume/beerreviews](https://www.kaggle.com/datasets/rdoume/beerreviews)

A base contém avaliações de cervejas realizadas por usuários, incluindo informações como:

* Aroma
* Aparência
* Paladar
* Teor alcoólico
* Nota geral
* Estilo da cerveja

---

## 🎯 Objetivo

O objetivo principal do projeto é classificar cervejas entre:

* **Excelente (1):** nota maior ou igual a 4.0
* **Comum (0):** nota menor que 4.0

A classificação foi realizada utilizando atributos numéricos relacionados às avaliações sensoriais das cervejas.

---

## 🛠️ Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 📊 Etapas do Projeto

### 1. Importação das Bibliotecas

Foram utilizadas bibliotecas para manipulação, visualização e modelagem de dados.

### 2. Carregamento da Base

O dataset foi carregado automaticamente no ambiente do Google Colab.

### 3. Amostragem dos Dados

Como a base original possui muitos registros, foi utilizada uma amostra de 1% dos dados para reduzir o custo computacional.

### 4. Análise Exploratória

Foram analisados:

* Estrutura da base
* Tipos de dados
* Valores ausentes
* Distribuição das variáveis

### 5. Tratamento dos Dados

Incluiu:

* Renomeação de colunas
* Tratamento de valores ausentes
* Criação da variável alvo

### 6. Modelagem

Foram utilizadas técnicas de aprendizado supervisionado para prever a qualidade das cervejas.

### 7. Avaliação

Os modelos foram avaliados utilizando métricas de classificação.

---

## 📈 Resultados

O projeto demonstrou como técnicas de Ciência de Dados podem ser utilizadas para identificar padrões em avaliações de cervejas e realizar classificações automáticas com base em características sensoriais.

---

## 🚀 Como Executar

### 1. Clone o repositório

```bash
git clone <URL_DO_REPOSITORIO>
```

### 2. Acesse a pasta do projeto

```bash
cd nome-do-repositorio
```

### 3. Instale as dependências

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 4. Execute o notebook

Abra o arquivo `.ipynb` no Google Colab ou Jupyter Notebook.

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conceitos de:

* Ciência de Dados
* Análise Exploratória de Dados (EDA)
* Pré-processamento de dados
* Visualização de dados
* Machine Learning
* Classificação supervisionada

---

## 👩‍💻 Autora

Projeto desenvolvido por Isabela Martins Bandeira como atividade acadêmica da disciplina de Ciência de Dados.

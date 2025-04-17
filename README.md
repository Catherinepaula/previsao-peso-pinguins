# 📊 Previsão de Peso de Pinguins com Regressão Linear

Este projeto faz parte do curso de Análise de Dados da EBAC, onde aplicamos conceitos de **modelagem preditiva com regressão linear** utilizando a base de dados de pinguins da biblioteca Seaborn.

---

## 🎯 Objetivo

Prever o peso de um pinguim (`body_mass_g`) com base em atributos físicos e geográficos, como:

- Espécie (`species`)
- Ilha de origem (`island`)
- Comprimento e profundidade do bico
- Comprimento da nadadeira
- Sexo do pinguim

---

## 🧰 Tecnologias utilizadas

- Python 🐍
- Pandas
- Seaborn
- Scikit-learn
- Google Colab

---

## 🔎 Etapas do Projeto

1. **Análise Exploratória dos Dados**  
   Gráficos por sexo, espécie e ilha para identificar padrões e relações com o peso.

2. **Pré-processamento**  
   - Tratamento de valores nulos  
   - Padronização de variáveis numéricas (`_std`)  
   - Codificação de variáveis categóricas (`_nom`)

3. **Treinamento do modelo**  
   Utilização de Regressão Linear com 2/3 dos dados para treino e 1/3 para teste.

4. **Avaliação do modelo**  
   Cálculo do RMSE:  
   `≈ 296g`, representando um erro de aproximadamente 7% do peso médio.

5. **Predição**  
   Aplicação do modelo a um novo pinguim com características específicas.

---

## 🐧 Resultado da Predição

Foi previsto o peso de um novo pinguim com as seguintes características:

| Atributo                   | Valor     |
|----------------------------|-----------|
| Espécie                    | Adélia    |
| Ilha                       | Biscoe    |
| Comprimento do bico (mm)   | 38.2      |
| Profundidade do bico (mm)  | 18.1      |
| Comprimento da nadadeira   | 185.0     |
| Sexo                       | Macho     |

**➡ Peso previsto: ~3786g**

---

## 📂 Como visualizar o notebook

Você pode abrir o notebook no Google Colab clicando abaixo:

[![Abrir no Colab]https://colab.research.google.com/drive/1diQb2TaVlACZF-29qVMRqnRAENHgdP8E?usp=sharing
https://colab.research.google.com/drive/1Ctrtqtofm6bZ3VR0lmSsKfx3uDsxOANQ?usp=sharing



>

---

## 👩‍💻 Autora

[Catherine (Cathe)
Estudante de Ciência da Computação | Análise de Dados pela EBAC  
📍 Xaxim - SC

---

## 📬 Contato

📧 catherinepaula100@gmail.com

---


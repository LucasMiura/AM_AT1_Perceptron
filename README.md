# 📈 AM_AT1_Perceptron

## 📌 Sobre o Projeto

Este projeto foi desenvolvido para a atividade AT1 da disciplina de Aprendizado de Máquina.

O objetivo é implementar um **Perceptron manual**, sem o uso de bibliotecas como numpy, aplicando o modelo em um cenário real:
👉 previsão de comportamento do preço de ações.

---

## 🎯 Problema Proposto

O projeto busca prever se o preço da ação da empresa McDonald's (MCD) irá **subir ou não no próximo dia**, com base em dados históricos do mercado financeiro.

A saída do modelo é:

* 📈 1 → preço sobe
* 📉 0 → preço não sobe

---

## 📊 Dataset

O dataset foi obtido na plataforma Kaggle e contém dados históricos das ações da empresa McDonald's.

📁 Local:

```
data/raw/mcd.csv
```

### Variáveis disponíveis:

| Variável | Descrição           |
| -------- | ------------------- |
| Date     | Data da negociação  |
| Open     | Preço de abertura   |
| High     | Maior preço do dia  |
| Low      | Menor preço do dia  |
| Close    | Preço de fechamento |
| Volume   | Volume negociado    |

---

## 🧠 Construção do Problema

Foi criada uma variável alvo (`target`) para transformar o problema em classificação binária:

* 1 → o preço de fechamento do próximo dia é maior
* 0 → o preço não aumenta

Isso foi feito comparando o valor atual com o próximo dia.

---

## ⚙️ Modelo Utilizado

Foi implementado um **Perceptron do zero**, contendo:

* 2 entradas (features)
* 1 bias
* Função de ativação degrau
* Treinamento por ajuste de pesos

🚫 Sem uso de numpy
🚫 Sem uso de bibliotecas de machine learning

---

## 🔎 Variáveis de Entrada

As variáveis escolhidas para o modelo foram:

* 📊 Open → preço de abertura
* 📦 Volume → volume de negociações

Essas variáveis influenciam diretamente o comportamento do mercado.

---

## 📈 Visualização dos Dados

Foi utilizado gráfico de dispersão para observar a separação entre as classes.

---

## 📁 Estrutura do Projeto

```
AM_AT1_Perceptron/
│
├── data/
│   └── raw/
│       └── mcd.csv
│
├── notebooks/
│   └── AT1_Perceptron.ipynb
│
├── main.py
├── pyproject.toml
└── README.md
```

---

## 🚀 Como Executar

1. Clone o repositório:

```
git clone https://github.com/seu-usuario/AM_AT1_Perceptron.git
```

2. Acesse a pasta:

```
cd AM_AT1_Perceptron
```

3. Instale as dependências:

```
pip install pandas matplotlib notebook
```

4. Execute o notebook:

```
jupyter notebook
```

---

## 📊 Objetivo Acadêmico

Este projeto tem como objetivo compreender na prática:

* Funcionamento do Perceptron
* Classificação binária
* Ajuste de pesos
* Aplicação em dados reais

---

## 💡 Aplicação Prática

O modelo pode ser utilizado como base para:

* Análise de tendências do mercado
* Sistemas de apoio à decisão
* Estudos iniciais de previsão financeira

---

## 👨‍💻 Autor

Lucas Miura

---

## 🧠 Observação

Este projeto possui caráter didático e foi desenvolvido com fins educacionais na área de Machine Learning.

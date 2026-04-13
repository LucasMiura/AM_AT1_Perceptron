# 🎯 AM_AT1_Perceptron

## 📌 Sobre o Projeto

Este projeto foi desenvolvido para a atividade AT1 da disciplina de Aprendizado de Máquina.

O objetivo é implementar um **Perceptron manual**, sem o uso de bibliotecas como numpy, aplicando o modelo em um cenário prático:
👉 prever se uma pessoa irá comparecer a um evento.

---

## 🧠 Problema Proposto

A proposta simula uma situação real de plataformas de eventos (como o VaiVale), onde é necessário prever o comportamento do usuário.

O modelo utiliza variáveis como:

* 🎟️ Interesse no evento
* 📍 Distância até o local
* 💰 Preço
* 👥 Presença de amigos

Saída:

* ✅ Vai ao evento
* ❌ Não vai ao evento

---

## 📊 Dataset

O dataset foi **criado manualmente**, simulando decisões reais de usuários.

📁 Local:

```
data/raw/eventos.csv
```

### Variáveis:

| Variável  | Descrição                        |
| --------- | -------------------------------- |
| interesse | Nível de interesse (0 a 10)      |
| distancia | Distância até o evento           |
| preco     | Valor do ingresso                |
| amigos    | Se amigos vão (0 ou 1)           |
| vai       | Resultado (1 = vai, 0 = não vai) |

---

## 🧠 Modelo Utilizado

Foi implementado um **Perceptron do zero**, contendo:

* 2 entradas (features)
* 1 bias
* Função de ativação degrau
* Treinamento por ajuste de pesos

🚫 Sem uso de bibliotecas de machine learning
🚫 Sem uso de numpy

---

## 📁 Estrutura do Projeto

```
AM_AT1_Perceptron/
│
├── data/
│   └── raw/
│       └── eventos.csv
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

## 📈 Objetivo Acadêmico

Este projeto tem como foco compreender na prática:

* Funcionamento do Perceptron
* Processo de treinamento
* Ajuste de pesos
* Classificação binária

---

## 💡 Possível Aplicação

O modelo desenvolvido pode ser aplicado em sistemas de recomendação de eventos, auxiliando na previsão de comportamento de usuários.

---

## 👨‍💻 Autor

Lucas Miura

---

## 🧠 Observação

Este projeto tem caráter didático e foi desenvolvido para fins de aprendizado em Machine Learning.

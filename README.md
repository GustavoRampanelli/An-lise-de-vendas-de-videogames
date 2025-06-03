# 🎮 Análise de Vendas de Videogames

Este projeto realiza uma análise exploratória dos dados de vendas de jogos de videogame com foco na plataforma **PlayStation 4 (PS4)**, utilizando Python e bibliotecas como Pandas, Matplotlib e Seaborn.

## 📊 Objetivo

Explorar tendências e padrões de vendas de jogos por:
- Ano de lançamento
- Região (América do Norte, Europa, Japão, Resto do Mundo)
- Gênero
- Editora (Publisher)
- Título individual

## 🗂️ Dataset

O arquivo utilizado é `PS4_GamesSales.csv`, que contém as seguintes colunas:

| Coluna           | Descrição                              |
|------------------|----------------------------------------|
| Game             | Nome do jogo                           |
| Year             | Ano de lançamento                      |
| Genre            | Gênero do jogo                         |
| Publisher        | Empresa responsável pela publicação    |
| North America    | Vendas na América do Norte (milhões)   |
| Europe           | Vendas na Europa (milhões)             |
| Japan            | Vendas no Japão (milhões)              |
| Rest of World    | Vendas no restante do mundo (milhões)  |
| Global           | Vendas globais (milhões)               |

## 🛠️ Tecnologias Utilizadas

- Python 3
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (para modelagem básica)

## 📈 Análises Realizadas

- Top 10 jogos mais vendidos globalmente
- Evolução das vendas por ano
- Comparação de vendas entre regiões
- Vendas por gênero e publisher
- Correlação entre vendas regionais e globais
- Modelagem preditiva simples com Regressão Linear

## 📌 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/GustavoRampanelli/An-lise-de-vendas-de-videogames.git

2. Acesse o projeto:
   ```bash
   cd An-lise-de-vendas-de-videogames

3. Abra o notebook no Google Colab (recomendado) ou Jupyter Notebook.

4. Faça upload do arquivo PS4_GamesSales.csv quando solicitado.

📚 Referências
Dataset original no Kaggle
https://www.kaggle.com/datasets/sidtwr/videogames-sales-dataset?resource=download

Documentação das bibliotecas: Pandas, Matplotlib, Seaborn

✨ Autor
Desenvolvido por Gustavo Rampanelli

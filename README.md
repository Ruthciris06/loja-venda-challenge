# 📊 Análise Comparativa das Lojas – Recomendação de Venda

Este projeto tem como objetivo auxiliar na tomada de decisão sobre qual das quatro lojas de uma rede fictícia deve ser vendida, com base em dados reais de desempenho comercial. A análise foi realizada utilizando Python e bibliotecas de ciência de dados como *Pandas* e *Matplotlib*.

## 🧠 Objetivo

Ajudar o Sr. João, proprietário das lojas, a identificar a unidade com menor eficiência para viabilizar novos investimentos. Foram avaliados critérios como:

- Faturamento total  
- Vendas por categoria de produto  
- Média das avaliações dos clientes  
- Produtos mais e menos vendidos  
- Custo médio de frete  

## 📈 Resultados e Conclusões

Após a análise exploratória e visual dos dados, foi possível identificar que:

- A **Loja 4** apresentou o menor faturamento e desempenho inferior em categorias estratégicas.  
- Apesar do frete competitivo, sua performance geral foi a mais fraca entre as quatro unidades.  
- A recomendação final foi a venda da **Loja 4**.  

## 📊 Visualizações Utilizadas

Para melhor compreensão dos dados, foram geradas visualizações com diferentes tipos de gráficos:

- **Gráfico de barras**: Comparação do faturamento por loja  
- **Gráfico de pizza**: Distribuição de vendas por categoria  
- **Gráfico de dispersão**: Relação entre avaliação média e faturamento  

## 🛠️ Tecnologias Utilizadas

- Python 3.10+  
- Pandas  
- Matplotlib  
- Google Colab (ambiente de desenvolvimento)  

## 📁 Estrutura do Projeto

```

├── dados/
│   └── vendas\_lojas.csv
├── imagens/
│   ├── grafico\_faturamento.png
│   ├── grafico\_categorias.png
│   └── grafico\_avaliacoes.png
├── analise\_lojas.ipynb
└── README.md

````

## 🚀 Como Executar

1. Clone este repositório:
```bash
git clone https://github.com/ruthciris06/analise-lojas-alura.git
````

2. Acesse o projeto no [Google Colab](https://drive.google.com/file/d/1s4GM-OVNtqxS6tuIdex36q-U4Cl4lEj_/view?usp=sharing) ou execute localmente em Jupyter Notebook.

3. Instale as dependências, se necessário:

```bash
pip install pandas matplotlib
```

## 📌 Requisitos

* Realizar análise de dados com Pandas
* Criar gráficos com Matplotlib
* Interpretar métricas comerciais e propor recomendações baseadas em dados

## 📄 Licença

Licença MIT © 2025 Ruthciris06.  
Este projeto é de código aberto e está disponível sob os termos da licença MIT.

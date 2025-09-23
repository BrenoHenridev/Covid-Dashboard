Covid Dashboard Interativo
📊 Descrição

Este projeto apresenta um painel interativo de análise da COVID-19, desenvolvido em Jupyter Notebook. O objetivo é consolidar dados de casos confirmados, óbitos e recuperações, permitindo análise temporal, comparação entre regiões e storytelling com dados.

🚀 Funcionalidades

Tratamento e limpeza de dados públicos da COVID-19.

Visualizações interativas: séries temporais, gráficos comparativos e tabelas.

Comparação entre estados e regiões.

Uso de métricas como médias móveis (7 dias) para suavizar tendências.

Notebook pronto para execução no Google Colab ou Jupyter.

🛠️ Tecnologias Utilizadas

Python

Pandas

Matplotlib / Seaborn / Plotly

Jupyter Notebook

Git & GitHub

📂 Estrutura do Projeto
Covid-Dashboard/
├─ imgs/
│  └─ covid_dashboard_page1.png   # Imagem do dashboard
├─ Covid-Dashboard Interativo.ipynb   # Notebook principal
└─ README.md

📷 Resultado
Visão Geral do Dashboard

📈 Insights Obtidos

Identificação de picos e quedas em períodos críticos da pandemia.

Comparação de curvas regionais para avaliar o impacto de políticas públicas.

Uso de médias móveis para facilitar a interpretação.

📥 Como Executar
# 1) Clonar o repositório
git clone https://github.com/BrenoHenridev/Covid-Dashboard.git
cd Covid-Dashboard

# 2) Instalar dependências
pip install -r requirements.txt

# 3) Abrir o notebook
jupyter notebook "Covid-Dashboard Interativo.ipynb"

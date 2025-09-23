🦠 Covid Dashboard Interativo
🎯 Objetivo

Construir um painel interativo em Python para:

Analisar dados da COVID-19.

Explorar tendências de casos confirmados, óbitos e vacinação.

Facilitar a interpretação de séries temporais através de médias móveis.

🔎 Etapas Realizadas

Coleta e carregamento dos dados em Jupyter Notebook.

Limpeza e preparação dos dados (remoção de inconsistências e valores nulos).

Criação de métricas derivadas como média móvel de 7 dias.

Construção de visualizações interativas (gráficos de linha, tabelas e comparativos).

Consolidação em um dashboard final com indicadores principais.

🛠️ Tecnologias Utilizadas

Python

Pandas

Matplotlib

Seaborn

Plotly

Jupyter Notebook

Git & GitHub

📂 Estrutura do Projeto
Covid-Dashboard/
├─ imgs/
│  └─ covid_dashboard_page1.png     # Imagem do dashboard consolidado
├─ Covid-Dashboard Interativo.ipynb # Notebook principal
└─ README.md

📊 Resultado
Visão Geral do Dashboard

O painel apresenta:

Evolução de casos confirmados e óbitos.

Médias móveis (7 dias) para suavizar oscilações.

Taxas de vacinação (1ª dose, 2ª dose e reforço).

Ranking dos estados mais impactados.

📈 Principais Insights

A série temporal evidencia períodos críticos com picos de casos e mortes.

As médias móveis destacam tendências reais além do ruído diário.

O comparativo entre estados mostra diferenças regionais significativas.

A vacinação demonstra impacto direto na redução dos indicadores.

⚙️ Como Executar
# 1) Clonar o repositório
git clone https://github.com/BrenoHenridev/Covid-Dashboard.git
cd Covid-Dashboard

# 2) Instalar dependências
pip install -r requirements.txt

# 3) Abrir o notebook
jupyter notebook "Covid-Dashboard Interativo.ipynb"

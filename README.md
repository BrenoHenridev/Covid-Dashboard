🦠 Covid Dashboard Interativo
🎯 Objetivo

Construir um painel interativo em Python para analisar e visualizar dados da COVID-19, explorando tendências de casos confirmados, óbitos e vacinação ao longo do tempo.

🔎 Etapas Realizadas

📥 Coleta e carregamento dos dados em Jupyter Notebook.

🧹 Limpeza e preparação (remoção de inconsistências e tratamento de valores nulos).

📊 Criação de métricas derivadas como médias móveis (7 dias) para suavizar tendências.

📈 Desenvolvimento de gráficos interativos para análise temporal e comparativa.

📌 Construção de um dashboard consolidado com os indicadores principais.

🛠️ Tecnologias Utilizadas

Python

Pandas

Matplotlib / Seaborn / Plotly

Jupyter Notebook

Git & GitHub

📂 Estrutura do Projeto
Covid-Dashboard/
├─ imgs/
│  └─ covid_dashboard_page1.png     # Imagem do dashboard consolidado
├─ Covid-Dashboard Interativo.ipynb # Notebook principal
└─ README.md

📊 Resultado
📌 Visão Geral do Dashboard

O painel apresenta:

Evolução de casos confirmados e óbitos.

Médias móveis (7 dias) para suavizar oscilações diárias.

Taxas de vacinação (1ª dose, 2ª dose e reforço).

Tabela com ranking de estados mais impactados.

📈 Principais Insights

📉 A série temporal mostra períodos críticos com picos elevados de casos e óbitos.

📊 As médias móveis facilitam a identificação de tendências reais além do ruído diário.

🌍 O comparativo entre estados evidencia diferenças regionais significativas.

💉 Métricas de vacinação ajudam a correlacionar a cobertura vacinal com a queda nos indicadores.

⚙️ Como Executar
# 1) Clonar o repositório
git clone https://github.com/BrenoHenridev/Covid-Dashboard.git
cd Covid-Dashboard

# 2) Instalar dependências
pip install -r requirements.txt

# 3) Abrir o notebook
jupyter notebook "Covid-Dashboard Interativo.ipynb"

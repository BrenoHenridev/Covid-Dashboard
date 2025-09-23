Covid Dashboard Interativo
 Objetivo

Construir um painel interativo em Python para analisar e visualizar dados da COVID-19, explorando tendências de casos confirmados, óbitos e vacinação ao longo do tempo.

 Etapas Realizadas

Coleta e carregamento de dados em Jupyter Notebook.

Limpeza e preparação dos dados (remoção de inconsistências e tratamento de nulos).

Criação de métricas derivadas como médias móveis (7 dias) para suavizar tendências.

Desenvolvimento de gráficos interativos para análise temporal e comparativa.

Construção de um dashboard consolidado com indicadores principais.

 Tecnologias Utilizadas

Python

Pandas

Matplotlib / Seaborn / Plotly

Jupyter Notebook

Git & GitHub

Covid-Dashboard/
├─ imgs/
│  └─ covid_dashboard_page1.png     # Imagem do dashboard consolidado
├─ Covid-Dashboard Interativo.ipynb # Notebook principal
└─ README.md


 Resultado
Visão Geral do Dashboard

O painel apresenta:

Evolução de casos confirmados e óbitos.

Médias móveis (7 dias) para suavizar oscilações diárias.

Taxas de vacinação (1ª dose, 2ª dose, reforço).

Tabela com ranking de estados mais impactados.

 Principais Insights

A série temporal mostra períodos críticos da pandemia com picos elevados de casos e óbitos.

As médias móveis facilitam a identificação de tendências reais além do ruído diário.

O comparativo por estados evidencia diferenças regionais significativas no impacto da pandemia.

As métricas de vacinação ajudam a correlacionar cobertura vacinal com queda nos indicadores.

Como Executar
# 1) Clonar o repositório
git clone https://github.com/BrenoHenridev/Covid-Dashboard.git
cd Covid-Dashboard

# 2) Instalar dependências
pip install -r requirements.txt

# 3) Abrir o notebook
jupyter notebook "Covid-Dashboard Interativo.ipynb"

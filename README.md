📊 Dashboard de Salários na Área de Dados

Aplicação web interativa desenvolvida com Streamlit para análise exploratória de salários na área de dados ao redor do mundo, com filtros dinâmicos e visualizações interativas.

Nota: Projeto focado em análise de dados, visualização e construção de dashboards com Python.

🌍 Visão Geral

Este dashboard permite explorar dados salariais de profissionais da área de dados considerando diferentes fatores como:

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

Modelo de trabalho (remoto, híbrido, presencial)

O usuário pode filtrar as informações em tempo real e visualizar métricas e gráficos atualizados automaticamente.

🧠 O que este projeto demonstra

Manipulação de dados com Pandas

Criação de dashboards com Streamlit

Visualização interativa com Plotly

Uso de filtros dinâmicos

Estruturação de projeto Python

Leitura de dados externos via URL

🛠️ Tecnologias Utilizadas
Tecnologia	Função
Python	Linguagem principal
Streamlit	Interface web e dashboard
Pandas	Tratamento e análise dos dados
Plotly Express	Gráficos interativos
📂 Estrutura do Projeto
├── app.py              # Código principal do dashboard
├── requirements.txt    # Dependências do projeto
└── .venv               # Ambiente virtual (não versionar)

🚀 Como Executar o Projeto
1️⃣ Clonar o repositório
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_PROJETO>

2️⃣ Criar o ambiente virtual
python -m venv .venv

3️⃣ Ativar o ambiente

Windows (PowerShell):

.venv\Scripts\activate


Mac/Linux:

source .venv/bin/activate

4️⃣ Instalar as dependências
pip install -r requirements.txt

5️⃣ Rodar a aplicação
streamlit run app.py


A aplicação abrirá automaticamente no navegador em:
👉 http://localhost:8501

🎛️ Funcionalidades do Dashboard
🔍 Filtros Interativos

Localizados na barra lateral:

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

📈 Métricas Principais (KPIs)

💰 Salário médio anual

🚀 Salário máximo

📊 Total de registros

👔 Cargo mais frequente

📊 Visualizações

O dashboard apresenta gráficos interativos que reagem aos filtros:

Top 10 cargos por salário médio

Distribuição de salários (Histograma)

Proporção de modelos de trabalho (Gráfico de pizza)

Mapa mundial com salário médio de Data Scientists

📋 Tabela de Dados

Exibição completa dos dados filtrados para análise detalhada diretamente na interface.

🗂️ Fonte dos Dados

Dataset público hospedado no GitHub:
dados-imersao-final.csv

🎯 Objetivo do Projeto

Este projeto tem fins educacionais e de portfólio, com foco em demonstrar competências em:

Análise de dados reais

Visualização de informações

Boas práticas em projetos Python

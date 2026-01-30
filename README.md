# 📊 Dashboard de Salários na Área de Dados

Uma aplicação web interativa desenvolvida com **Streamlit** para análise exploratória de salários na área de dados ao redor do mundo. O projeto conta com filtros dinâmicos e visualizações interativas que permitem uma compreensão profunda das tendências do mercado.

> **Nota:** Projeto focado em análise de dados, visualização e construção de dashboards com Python.

## 🌍 Visão Geral

Este dashboard permite explorar dados salariais de profissionais da área de dados considerando diferentes fatores cruciais:

- **Ano:** Evolução temporal dos ganhos.
- **Senioridade:** Impacto da experiência no salário.
- **Tipo de contrato:** CLT, Freelance, Part-time, etc.
- **Tamanho da empresa:** Comparação entre Startups e Big Techs.
- **Modelo de trabalho:** Remoto, híbrido ou presencial.

O usuário pode filtrar as informações em tempo real e visualizar métricas e gráficos que são atualizados automaticamente conforme a seleção.

## 🧠 O que este projeto demonstra

- Manipulação de dados robusta com **Pandas**.
- Criação de dashboards modernos com **Streamlit**.
- Visualização interativa de alto nível com **Plotly**.
- Uso de filtros dinâmicos para exploração de dados.
- Estruturação de projeto Python profissional.
- Leitura de dados externos diretamente via URL.

## 🛠️ Tecnologias Utilizadas

| Tecnologia       | Função                                      |
|------------------|---------------------------------------------|
| Python           | Linguagem principal do projeto              |
| Streamlit        | Interface web e estrutura do dashboard      |
| Pandas           | Tratamento e análise profunda dos dados     |
| Plotly Express   | Criação de gráficos dinâmicos e interativos |

## 📂 Estrutura do Projeto
├── app.py              # Aplicação principal do dashboard Streamlit
├── requirements.txt    # Lista de dependências do projeto
└── .venv/              # Ambiente virtual (ignorado no versionamento)


## 🚀 Como Executar o Projeto

Siga os passos abaixo para rodar a aplicação localmente:

### 1️⃣ Clonar o repositório:
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_PROJETO>

2️⃣ Criar o ambiente virtual:
python -m venv .venv

3️⃣ Ativar o ambiente virtual:
Windows (PowerShell):
.venv\Scripts\activate

Mac/Linux:
source .venv/bin/activate

4️⃣ Instalar as dependências:
pip install -r requirements.txt

5️⃣ Rodar a aplicação:
streamlit run app.py
A aplicação abrirá automaticamente no navegador em: 👉 http://localhost:8501

🎛️ Funcionalidades do Dashboard
🔍 Filtros Interativos
Localizados na barra lateral, permitem segmentar por:

Ano

Senioridade

Tipo de contrato

Tamanho da empresa

📈 Métricas Principais (KPIs)
💰 Salário médio anual

🚀 Salário máximo

📊 Total de registros analisados

👔 Cargo mais frequente no dataset

📊 Visualizações
O dashboard apresenta gráficos interativos que reagem instantaneamente aos filtros:

Top 10 cargos por salário médio.

Distribuição de salários (Histograma para análise de desvio padrão).

Proporção de modelos de trabalho (Gráfico de pizza: Remoto vs Presencial).

Mapa mundial com a distribuição salarial de Data Scientists.

📋 Tabela de Dados
Exibição completa dos dados filtrados para análise detalhada diretamente na interface, permitindo auditoria dos números apresentados.

🗂️ Fonte dos Dados
O projeto consome um dataset público hospedado no GitHub: dados-imersao-final.csv.

🎯 Objetivo do Projeto
Este projeto tem fins educacionais e de portfólio, focado em demonstrar competências técnicas em análise de dados reais, visualização estratégica e boas práticas de desenvolvimento em Python.

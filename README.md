# ALURA-Imersao-Dados-Python-Dashboard-Analise-Salarios
Dashboard interativo desenvolvido em Python e Streamlit para análise de salários globais, baseado nos dados da Imersão de Dados da Alura. Inclui filtros dinâmicos, visualizações personalizadas e tema financeiro em tons de verde.
# 🌍 Salary Insights Dashboard — Streamlit

Dashboard interativo desenvolvido em Python e Streamlit para explorar dados salariais globais, baseado no dataset da **Imersão de Dados da Alura**.  
O projeto apresenta visualizações dinâmicas, filtros avançados e um tema personalizado em tons de verde, inspirado em análises financeiras.

---

## 📊 Funcionalidades

- Filtros por:
  - País de residência
  - Cargo
  - Tipo de contrato
  - Nível de experiência
  - Tamanho da empresa
- Gráficos interativos com Plotly:
  - Distribuição salarial
  - Média salarial por cargo
  - Comparação entre países (amostragem distribuída)
  - Tipos de contrato (gráfico de pizza)
- Tema visual customizado em verde (config.toml)
- Estrutura multipágina com Streamlit

---

## 🛠️ Tecnologias utilizadas

- **Python 3.10+**
- **Streamlit**
- **Pandas**
- **Plotly Express**
- **NumPy**

---

## 📁 Estrutura do projeto
ImersaoPython/
│
├── app.py
├── pages/
│   ├── 1_📈Visão_Geral.py
│ ├── 2🌍Países.py
│ ├── 3💼Cargos.py
│ └── 4📊_Contratos.py
│
├── data/
│   └── dados-imersao-final.csv
│
└── .streamlit/
└── config.toml

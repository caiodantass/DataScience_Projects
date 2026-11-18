# Data Science & Applied Statistics Portfolio

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626.svg?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Data%20Analysis-Pandas%20%7C%20NumPy-150458.svg?logo=pandas)](https://pandas.pydata.org/)
[![Visualization](https://img.shields.io/badge/Visualization-Plotly%20%7C%20Dash%20%7C%20Seaborn-4B8BBE.svg)](https://plotly.com/)
[![Focus](https://img.shields.io/badge/Domain-Applied%20Statistics%20%26%20EDA-success.svg)](#projetos-e-estudos-de-caso)

Coleção de projetos e estudos práticos de **Ciência de Dados**, **Estatística Aplicada** e **Análise Exploratória de Dados (EDA)** utilizando Python e bases de dados públicas reais.

Os estudos abordam pipelines completos de ETL, manipulação de grandes volumes de dados temporais, visualizações analíticas interativas e inferências estatísticas sobre problemas reais de trânsito, educação e segurança pública.

---

## 🔬 Projetos e Estudos de Caso

### 1. 🛣️ Análise Espaço-Temporal de Acidentes Rodoviários Federais
> **Notebook:** `PROJETO 1 - PRF.ipynb`  
> **Fonte de Dados:** Dados Abertos da Polícia Rodoviária Federal (PRF - 2018 a 2021)

* **Objetivo:** Investigar padrões de sinistralidade, sazonalidade e severidade de acidentes nas rodovias federais brasileiras ao longo de múltiplos anos.
* **Técnicas & Habilidades Aplicadas:**
  * **Data Wrangling em Larga Escala:** Ingestão remota de dados diretamente de endpoints públicos sem necessidade de download manual, unificando múltiplos anos via `pd.concat`.
  * **Análise Multivariada de Severidade:** Filtragem e agregação estatística de feridos graves e óbitos por estado (UF) e rodovia (BR).
  * **Séries Temporais:** Análise de sazonalidade mensal e anual identificando períodos de pico crítico.

---

### 2. 🎓 Evolução e Indicadores do Ensino Superior no Brasil
> **Notebook:** `Projeto 2 - Ens. Superior do BR.ipynb`  
> **Fonte de Dados:** Censo da Educação Superior / Microdados MEC/INEP

* **Objetivo:** Analisar a qualidade, expansão e acessibilidade da educação superior brasileira ao longo de diferentes períodos governamentais.
* **Técnicas & Habilidades Aplicadas:**
  * **Dashboards Interativos:** Desenvolvimento de componentes analíticos com **Plotly Express**, **Dash** e **JupyterDash**.
  * **Métricas Institucionais:** Análise comparativa entre instituições públicas e privadas, taxas de evasão e correlação entre investimentos e notas de avaliação.
  * **Visualização Reativa:** Gráficos interativos para exploração de hipóteses em tempo real.

---

### 3. 🚓 Análise Estatística de Abordagens Policiais (Stanford Policing Dataset)
> **Notebook:** `Projeto 3.ipynb`  
> **Fonte de Dados:** Rhode Island Traffic Stops Dataset (The Stanford Open Policing Project)

* **Objetivo:** Estudo probabilístico e inferência estatística sobre abordagens de trânsito, comportamento policial e desfechos de segurança pública.
* **Técnicas & Habilidades Aplicadas:**
  * **Análise de Frequências Absolutas e Relativas:** Distribuição condicional de tipos de infração (*violations*) por perfil demográfico e gênero.
  * **Taxas de Prisões e Buscas:** Cálculo de probabilidade condicional para buscas veiculares (*search rate*) e taxas horárias de prisões (*hourly arrest rate*).
  * **Análise Temporal e Dispersão:** Análise de risco horário com gráficos de barras múltiplos, séries temporais de apreensões e *boxplots* para detecção de assimetrias.

---

## 🛠️ Stack Tecnológica

| Categoria | Ferramentas |
| :--- | :--- |
| **Linguagem Principal** | Python (3.9+) |
| **Manipulação & Análise** | Pandas, NumPy |
| **Visualização de Dados** | Plotly Express, Dash, Seaborn, Matplotlib |
| **Ambiente Interativo** | Jupyter Notebook, JupyterLab |
| **Métodos Analíticos** | Estatística Descritiva, Séries Temporais, Análise Bivariada e Multivariada |

---

## 🚀 Como Executar Localmente

### Pré-requisitos
* Python 3.9 ou superior instalado.

### Passo a Passo

```bash
# 1. Clone o repositório
git clone https://github.com/caiodantass/DataScience_Projects.git
cd DataScience_Projects

# 2. Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# 3. Instale as bibliotecas necessárias
pip install pandas numpy matplotlib seaborn plotly dash jupyterlab

# 4. Inicie o JupyterLab para explorar os notebooks
jupyter lab
```

---

## 👨‍💻 Autor

**Caio Lívio Dantas**  
* Engenheiro de Software / Desenvolvedor  
* LinkedIn: [linkedin.com/in/caio-lívio](https://www.linkedin.com/in/caio-l%C3%ADvio/)  
* GitHub: [@caiodantass](https://github.com/caiodantass)

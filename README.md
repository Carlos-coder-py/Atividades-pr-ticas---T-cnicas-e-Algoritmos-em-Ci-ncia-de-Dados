# Atividades práticas - Técnicas e Algoritmos em Ciência de Dados
Atividades práticas - Python


# Técnicas e Algoritmos em Ciência de Dados

Repositório da disciplina **Técnicas e Algoritmos em Ciência de Dados**.

**Aluno:** Carlos Eduardo Borba Domingues  
**Professor:** Frederico Luiz Strey  

---

## 📁 Estrutura do Repositório

```
.
├── atividade_1_imdb.ipynb                    # Atividade 1 - EDA no Dataset IMDB
├── atividade_3_classificacao_clustering.ipynb # Atividade 3 - Classificação e Clustering
├── requirements.txt                           # Dependências do projeto
├── .gitignore                                 # Arquivos ignorados pelo Git
└── README.md                                  # Este arquivo
```

---

## 📌 Atividades

### Atividade 1 — Análise Exploratória de Dados (EDA) - Dataset IMDB
- Carregamento e limpeza do dataset
- Análise de valores nulos e duplicatas
- Visualizações: histogramas, boxplots, barplots, scatter plots
- Matriz de correlação
- Pré-processamento: LabelEncoder, MinMaxScaler
- Modelo preditivo: Regressão Linear

**Dataset:** [IMDB Dataset 2023 - Kaggle](https://www.kaggle.com/datasets/adriankiezun/imdb-dataset-2023)

---

### Atividade 2 — Versionamento com Git/GitHub
- Criação de repositório público no GitHub
- Configuração de README, requirements.txt e .gitignore
- Primeiro commit e push para o repositório remoto

---

### Atividade 3 — Algoritmos de Classificação e Agrupamento
- Dataset: Iris (sklearn)
- Modelos de classificação: KNN, Árvore de Decisão, Random Forest
- Redução de dimensionalidade: PCA
- Agrupamento: K-Means com Método Elbow e Silhouette Score

---

## 🚀 Como Rodar Localmente

### Pré-requisitos
- Python 3.8+
- pip

### Instalação

```bash
# 1. Clone o repositório
git clone https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
cd SEU_REPOSITORIO

# 2. (Opcional) Crie um ambiente virtual
python -m venv venv
source venv/bin/activate        # Linux/Mac
venv\Scripts\activate           # Windows

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Inicie o Jupyter Notebook
jupyter notebook
```

### Atividade 1 — Dataset IMDB
Baixe o dataset no [Kaggle](https://www.kaggle.com/datasets/adriankiezun/imdb-dataset-2023), salve o CSV na raiz do projeto e ajuste o caminho de leitura no notebook.

---

## 🛠️ Tecnologias Utilizadas

| Biblioteca | Versão | Uso |
|---|---|---|
| pandas | ≥1.5 | Manipulação de dados |
| numpy | ≥1.23 | Operações numéricas |
| matplotlib | ≥3.6 | Visualizações |
| seaborn | ≥0.12 | Visualizações estatísticas |
| scikit-learn | ≥1.2 | Machine Learning |
| jupyter | ≥1.0 | Notebooks interativos |

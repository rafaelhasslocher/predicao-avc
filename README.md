# MVP — Predição de Ocorrência de AVC

### 1. Informações Gerais

Este repositório contém o MVP desenvolvido para aprovação na Sprint "Análise de Dados e Boas Práticas", da Pós-Graduação Lato Sensu em Ciência de Dados e Analytics do CCE PUC-Rio.

**Autor:** Rafael Hasslocher de Oliveira Lima  
**Matrícula:** 4052024002344  
**Dataset Utilizado:** [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset). O autor disponibiliza o dataset para fins educacionais, condição devidamente atendida neste trabalho.

### 2. Tecnologias e Bibliotecas Utilizadas

- Python;
- `pandas`, `numpy`: manipulação e análise de dados;
- `matplotlib`, `seaborn`: visualização de dados;
- `scikit-learn`: pré-processamento e modelagem;
- `imbalanced-learn`: SMOTE - balanceamento de classes;
- `scipy`: testes estatísticos;
- `tabulate`: formatação de tabelas.

### 3. Como Executar

O notebook pode ser executado diretamente no Google Colab, sem necessidade de configuração local:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rafaelhasslocher/predicao-avc/blob/master/MVP_Predicao_AVC.ipynb)

Para execução local, recomenda-se o uso do `uv` (gerenciador de pacotes e ambientes Python), com as dependências definidas em `uv.lock` e a versão do Python especificada em `.python-version`.

## 4. Estrutura do Repositório

    📁 predicao-avc/
    ├── 📂 data/                        # Arquivos de dados utilizados no projeto
    ├── 📄 .gitignore                   # Arquivos e pastas ignorados pelo Git
    ├── 📄 MVP_Predicao_AVC.ipynb       # Notebook principal
    ├── 📄 README.md                    # Documentação do projeto
    ├── 📄 uv.lock                      # Dependências do projeto (uv)
    └── 📄 .python-version              # Versão do Python
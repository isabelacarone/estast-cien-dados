# EDA 
---

## Sobre o Projeto

O dataset contém **1.120.000 linhas** e **23 colunas**, incluindo dados demográficos dos clientes, características físico-químicas dos vinhos consumidos (médias por cliente) e o valor total gasto.

---

## Estrutura de Diretórios

```
estast-cien-dados/
├── apostilas/   
├── provas/              
├── atividades/              
│   ├── atividade1.ipynb
│   ├── atividade2.ipynb
│   ├── atividade3.ipynb
│   └── atividade4.ipynb
├── data/
│   └── table16.csv         
├── figures/                 
├── venv/                   
├── .gitignore
├── requirements.txt
└── readme.md
```

> **Nota:** O arquivo `data/table16.csv` não é versionado por exceder o limite de 100MB do GitHub

---

## Configuração do Ambiente

### Usando `venv` (recomendado)

```bash
# Criar o ambiente virtual
python -m venv venv

# Ativar o ambiente (Linux/macOS)
source venv/bin/activate

# Instalar dependências
pip install -r requirements.txt
```

### Usando Anaconda

```bash
conda create -n bigdata_env python=3.12
conda activate bigdata_env
pip install pandas numpy matplotlib seaborn scipy jupyter ipykernel
```

### Registrar o kernel no Jupyter

```bash
python -m ipykernel install --user --name=venv_estast --display-name "Python (estast)"
```



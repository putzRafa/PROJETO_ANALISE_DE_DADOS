# 📊 Projeto de Análise de Dados

Projeto desenvolvido com o objetivo de **praticar e desenvolver conhecimentos em Análise de Dados e Ciência de Dados**, utilizando Python para tratamento e exploração dos dados e Power BI para construção de visualizações e análises.

O projeto apresenta um fluxo básico de análise de dados, passando pelas etapas de **extração, tratamento, análise e visualização das informações**.

---

## 🎯 Objetivo

O principal objetivo deste projeto é colocar em prática conceitos fundamentais de análise de dados, desde a preparação de uma base de dados até a obtenção de informações que possam auxiliar na interpretação dos dados.

Durante o desenvolvimento, são exploradas técnicas como:

* Importação de dados;
* Limpeza e tratamento de dados;
* Padronização de informações;
* Conversão de tipos de dados;
* Remoção de dados desnecessários;
* Identificação e remoção de registros duplicados;
* Análise exploratória;
* Cálculos estatísticos;
* Criação de visualizações;
* Construção de dashboard no Power BI.

---

## 🗂️ Estrutura do projeto

```text
PROJETO_ANALISE_DE_DADOS/
│
├── EXTRACAO_MODELAGEM_DADOS.ipynb
├── POUWER_BI_ANALISE.pbix
├── base.xlsx
├── base_tratado.xlsx
└── README.md
```

### Arquivos

| Arquivo                          | Descrição                                                          |
| -------------------------------- | ------------------------------------------------------------------ |
| `EXTRACAO_MODELAGEM_DADOS.ipynb` | Notebook responsável pela extração, tratamento e análise dos dados |
| `base.xlsx`                      | Base de dados original utilizada no projeto                        |
| `base_tratado.xlsx`              | Base após as etapas de limpeza e tratamento                        |
| `POUWER_BI_ANALISE.pbix`         | Dashboard desenvolvido no Power BI                                 |
| `README.md`                      | Documentação do projeto                                            |

---

## 🔄 Fluxo da análise

O projeto segue, de forma geral, o seguinte fluxo:

```text
Base de dados
     ↓
Extração
     ↓
Tratamento e limpeza
     ↓
Base tratada
     ↓
Análise exploratória
     ↓
Visualização dos dados
     ↓
Dashboard no Power BI
```

---

## 🐍 Tratamento dos dados

O notebook `EXTRACAO_MODELAGEM_DADOS.ipynb` utiliza bibliotecas do ecossistema Python para realizar o processamento da base.

Entre as principais etapas estão:

### Importação dos dados

A base original é carregada a partir do arquivo `base.xlsx` utilizando o Pandas.

### Padronização das colunas

Os nomes das colunas são reorganizados para facilitar a identificação e utilização durante a análise.

Entre os campos trabalhados estão informações relacionadas a:

* Vendedor;
* Filial;
* Data da compra;
* Valor da compra;
* Valor do imposto;
* Informação sobre o imposto.

### Tratamento de valores

Os valores monetários são convertidos para formatos numéricos, permitindo a realização de operações matemáticas e estatísticas.

Também são realizadas operações de padronização dos nomes dos vendedores e tratamento das datas.

### Remoção de dados

Durante o processo de limpeza, são removidas informações consideradas desnecessárias para a análise, além de registros duplicados.

Ao final dessa etapa, uma nova base é gerada:

```text
base_tratado.xlsx
```

---

## 📈 Análise dos dados

Após o tratamento, a base é utilizada para realizar análises sobre os dados de vendas.

Entre os cálculos realizados no projeto estão:

* Valor total vendido;
* Média de vendas;
* Análise das vendas ao longo do tempo;
* Comparações entre vendedores;
* Análises relacionadas às filiais;
* Análise dos valores de impostos;
* Exploração de diferentes características da base.

Um dos cálculos realizados no notebook, por exemplo, obtém o valor total das vendas presentes na base tratada.

---

## 📊 Power BI

Após o tratamento e análise utilizando Python, os dados são utilizados na construção de um dashboard no **Power BI**.

O objetivo dessa etapa é transformar os resultados obtidos em informações visualmente mais fáceis de interpretar, permitindo explorar os dados por meio de gráficos e indicadores.

O arquivo do dashboard está disponível em:

```text
POUWER_BI_ANALISE.pbix
```

> **Observação:** é necessário possuir o Power BI Desktop para abrir o arquivo `.pbix`.

---

## 🛠️ Tecnologias utilizadas

### Python

Utilizado para:

* Extração dos dados;
* Limpeza e tratamento;
* Manipulação de DataFrames;
* Cálculos;
* Análise exploratória;
* Geração da base tratada.

Principais bibliotecas utilizadas no notebook:

```python
pandas
numpy
matplotlib
seaborn
```

### Excel

Utilizado como formato de armazenamento das bases de dados:

* `base.xlsx`
* `base_tratado.xlsx`

### Power BI

Utilizado para a criação das visualizações e do dashboard final.

---

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/putzRafa/PROJETO_ANALISE_DE_DADOS.git
```

### 2. Acesse a pasta

```bash
cd PROJETO_ANALISE_DE_DADOS
```

### 3. Instale as bibliotecas necessárias

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

### 4. Execute o notebook

Abra:

```text
EXTRACAO_MODELAGEM_DADOS.ipynb
```

O notebook pode ser executado utilizando:

* Jupyter Notebook;
* JupyterLab;
* Google Colab;
* Visual Studio Code com extensão para Jupyter.

### 5. Visualize o dashboard

Abra o arquivo:

```text
POUWER_BI_ANALISE.pbix
```

utilizando o Power BI Desktop.

---

## 📚 Objetivos de aprendizagem

Este projeto faz parte do processo de desenvolvimento de conhecimentos nas áreas de:

* Análise de Dados;
* Ciência de Dados;
* Python;
* Pandas;
* Visualização de Dados;
* Tratamento de bases de dados;
* Power BI;
* Business Intelligence.

A proposta é utilizar o projeto como um espaço de **experimentação e prática**, permitindo aplicar conceitos aprendidos em diferentes etapas do processo de análise de dados.

---

## 🔮 Possíveis melhorias

Como projeto de estudo, algumas melhorias que podem ser implementadas futuramente incluem:

* Automatizar a obtenção dos dados;
* Criar novas métricas de negócio;
* Expandir as análises estatísticas;
* Melhorar o tratamento de valores ausentes;
* Criar análises temporais mais detalhadas;
* Aprimorar o dashboard;
* Documentar as principais descobertas obtidas durante a análise;
* Estruturar o projeto em diferentes etapas de um pipeline de dados.

---

## 👨‍💻 Autor

**Rafael Farias de Lima**

Projeto desenvolvido para fins de estudo, prática e construção de portfólio na área de **Análise de Dados e Ciência de Dados**.

---

⭐ **Obrigado por visitar o projeto!**

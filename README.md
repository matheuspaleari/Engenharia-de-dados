# 🛠️ Sales ETL Pipeline

Projeto de Engenharia de Dados desenvolvido em Python com foco na construção de um pipeline ETL (Extract, Transform and Load) para processamento e análise de dados de vendas.

O objetivo é demonstrar conceitos fundamentais de ingestão, transformação, armazenamento e consulta de dados utilizando ferramentas amplamente empregadas em projetos de dados.

## 📁 Estrutura do Projeto

O projeto é composto pelas seguintes etapas:

### 📥 Extração (Extract)

Leitura de dados de vendas a partir de arquivos CSV.

### ⚙️ Transformação (Transform)

Tratamento e enriquecimento dos dados por meio de:

* Conversão de datas
* Limpeza de registros
* Criação de métricas de negócio
* Padronização de informações
* Geração de novas colunas analíticas

### 💾 Carga (Load)

Persistência dos dados processados em banco SQLite para consultas e análises posteriores.

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido para praticar conceitos essenciais de Engenharia de Dados, incluindo:

* Ingestão de dados
* Processos ETL
* Manipulação de dados com Python
* Armazenamento em banco relacional
* Consultas SQL
* Geração de insights a partir dos dados

---

## 🛠️ Tecnologias Utilizadas

### Linguagem

* Python

### Manipulação de Dados

* Pandas

### Banco de Dados

* SQLite

### Consultas

* SQL

### Ambiente

* Google Colab
* Jupyter Notebook

---

## 🔄 Pipeline de Dados

```text
CSV Files
    ↓
Data Extraction
    ↓
Data Cleaning
    ↓
Data Transformation
    ↓
SQLite Database
    ↓
SQL Analysis
    ↓
Business Insights
```

---

## ✨ Funcionalidades Implementadas

* Leitura de arquivos CSV
* Limpeza e tratamento de dados
* Conversão de tipos de dados
* Criação de métricas de vendas
* Armazenamento em banco SQLite
* Execução de consultas SQL
* Análise exploratória dos resultados

---

## 📊 Transformações Realizadas

Durante o processo ETL foram aplicadas as seguintes transformações:

* Conversão de colunas de data
* Criação da coluna `valor_total`
* Criação da coluna `mes`
* Padronização dos dados
* Remoção de inconsistências

---

## 🎯 Principais Aprendizados

* Construção de pipelines ETL utilizando Python
* Manipulação de grandes volumes de dados com Pandas
* Integração entre Python e bancos relacionais
* Escrita de consultas SQL para análise de dados
* Estruturação de projetos de Engenharia de Dados

---

## 👨‍💻 Autor

**Matheus Paleari**

GitHub: https://github.com/matheuspaleari

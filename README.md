# Atividade de Retomada - Estruturas de Dados e Pandas

Este diretório contém os exercícios práticos e anotações realizados para a retomada de conceitos fundamentais de Ciência de Dados, focando nas estruturas de dados nativas do Python e na manipulação de dados utilizando a biblioteca `pandas`.

## 📁 Estrutura do Diretório e Atividades

O projeto foi dividido em três frentes principais de estudo, cada uma em seu respectivo diretório:

### 1. Tipos de Dados (`/Tipos_Dados`)
Foco na compreensão e manipulação prática da diferença entre dados estruturados e semiestruturados.
- **`estudo_tipos_dados.ipynb`**: Notebook demonstrando a criação de DataFrames em Pandas a partir de dicionários.
- **Exportação e Importação**: Prática de como exportar e carregar dados em diferentes formatos:
  - Dados Estruturados: Planilhas Excel (`dadosEstruturados.xlsx` utilizando `openpyxl`).
  - Dados Semiestruturados: Arquivos JSON (`dadosSemi.json`).

### 2. Tipos de Estruturas Nativo do Python (`/Tipos_Estrutura`)
Foco nas estruturas de dados *built-in* do Python e suas principais operações.
- **`estudo_tipos_estrutura.ipynb`**: Notebook contendo exemplos práticos com:
  - **Listas**: Adição, remoção, ordenação e inserção (`append`, `pop`, `insert`, `remove`, `sort`, `reverse`).
  - **Tuplas**: Demonstração de sua característica principal: a imutabilidade.
  - **Conjuntos (Sets)**: Trabalhando com elementos únicos e operações de conjuntos (união, interseção, diferença simétrica, etc).
  - **Filas (Queues)**: Implementação básica do conceito **FIFO** (First In, First Out) simulado através de métodos de lista.

### 3. Manipulação de DataFrames (`/Dataframe`)
Aprofundamento no uso da biblioteca Pandas para tratamento e análise de dados tabulares.
- **`dataframe.ipynb`**: Notebook focado em extrair informações de um DataFrame simulando dados de pessoas, explorando:
  - Criação de DataFrames a partir de dicionários.
  - Seleção, filtragem com múltiplas condicionais e transposição de dados (`.T`).
  - Geração de estatísticas descritivas (`.describe()`).
  - Uso do método `.apply()` e funções `lambda` para criar/modificar colunas.
  - Funções de agrupamento e agregação (`.groupby()`, `.value_counts()`, `.sort_values()`).

## 🛠️ Tecnologias e Dependências

Para reproduzir os notebooks deste diretório, é necessário ter um ambiente Python configurado (recomenda-se o uso de um ambiente virtual - `.venv`) com as seguintes bibliotecas:

- Python 3.x
- `pandas`
- `openpyxl` (para a leitura e escrita de arquivos Excel)
- `jupyter` (para visualizar e executar os notebooks)

Para instalar as dependências, você pode rodar o comando:
```bash
pip install pandas openpyxl jupyter
```

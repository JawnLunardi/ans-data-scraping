# 📊 ANS - Extração e Transformação de Dados de Procedimentos

Este projeto automatiza o download, extração e transformação dos dados dos procedimentos da ANS (Agência Nacional de Saúde Suplementar) disponíveis em arquivos PDF no site oficial. Ao final, os dados são salvos em um arquivo `.csv` pronto para ser usado em análises e visualizações.

## 🚀 Funcionalidades

- Download automatizado dos arquivos PDF de procedimentos da ANS
- Extração e limpeza das tabelas dos PDFs
- Exportação dos dados tratados para `.csv` e `.zip`

## 🧰 Tecnologias utilizadas

- Python 3.10+
- [requests](https://pypi.org/project/requests/)
- [beautifulsoup4](https://pypi.org/project/beautifulsoup4/)
- [lxml](https://pypi.org/project/lxml/)
- [pdfplumber](https://pypi.org/project/pdfplumber/)
- [pandas](https://pypi.org/project/pandas/)

## 🛠️ Como usar

### 1. Clone este repositório

### 2. Instale as dependências

pip install -r requirements.txt

### 3. Execute o script de scraping

python scraping.py

Esse script baixa os arquivos PDF do site da ANS e salva na pasta pdf/.

### 4. Execute o script de tratamento de dados:

python data_transform.py

Esse script le lê os arquivos PDF baixados e cria um arquivo .csv com os dados tratados. O resultado será salvo na pasta dados/.

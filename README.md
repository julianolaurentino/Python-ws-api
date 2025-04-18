# 🕸️ Projeto de Web Scraping com Python

Este projeto tem como objetivo realizar a extração, transformação e visualização de dados da web utilizando ferramentas modernas do ecossistema Python.

## 🔧 Tecnologias Utilizadas

- **[Scrapy](https://scrapy.org/)**: Framework para extração de dados estruturados da web.
- **[Pandas](https://pandas.pydata.org/)**: Biblioteca para manipulação e análise de dados.
- **[Streamlit](https://streamlit.io/)**: Ferramenta para criação de dashboards interativos.


## ▶️ Como Executar

### 1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/python-ws-api.git
cd python-ws-api
```

### 2. Instalar as dependências
```
pip install -r requirements.txt
```
### 3. Rodar o spider do Scrapy
```
cd src/extraction
scrapy crawl notebook -o ../../base/data.jsonl
```
### 4. Executar a transformação dos dados com Pandas
```
cd ../transformLoad
python main.py
```
### 5. Iniciar o dashboard com Streamlit
```
cd ../../dashboard
streamlit run app.py
```

📝 Observações
É necessário ter Python 3.8 ou superior instalado.

Os dados extraídos são salvos em base/data.jsonl e tratados antes da visualização.

*Por motivos de segurança, alguns arquivos podem não estar dentro dos diretórios.

## Autor

- [@JulianoLaurentino](https://www.linkedin.com/in/julianolaurentinodasilva/)
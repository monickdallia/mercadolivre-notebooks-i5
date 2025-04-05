#Análise de Preços de Notebooks i5 no Mercado Livre

Este projeto realiza a coleta diária de preços de notebooks com processador Intel Core i5 anunciados no Mercado Livre, utilizando web scraping com Python e análise de dados com pandas e matplotlib.

---
#Objetivos
- Coletar informações atualizadas sobre preços de notebooks i5.
- Analisar a distribuição dos preços e identificar marcas mais comuns.
- Visualizar dados com gráficos para facilitar a tomada de decisões.
- Automatizar a coleta e manter um histórico.
---

#Tecnologias Utilizadas
- `Python 3.10+`
- `BeautifulSoup` (web scraping)
- `pandas` (tratamento de dados)
- `matplotlib` (visualizações)
- `requests` (requisições HTTP)
- `GitHub Actions` (automatização)
- `Streamlit` (dashboard)
---

#Estrutura dos Arquivos

```bash
.
├── notebooks_mel.csv             # Arquivo gerado com os dados coletados
├── mercadolivre_scraper.py      # Script principal de scraping e análise
├── grafico_precos.png           # Gráfico da distribuição de preços
├── preco_medio_marca.png        # Gráfico de preço médio por marca
├── faixa_preco.png              # Gráfico por faixa de preço
└── README.md                    # Este documento



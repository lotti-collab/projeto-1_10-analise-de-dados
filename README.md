# projeto-1_10-analise-de-dados
Este projeto tem como objetivo analisar o dataset de vendas de um supermercado, gerando insights de negócio através de KPIs e visualizações interativas. Ele simula um mini dashboard de BI dentro do Jupyter Notebook, permitindo filtrar vendas por cidade, tipo de produto e forma de pagamento.
# Projeto 1 - Análise de Vendas de Supermercado 🛒

## Descrição do Projeto
Este projeto tem como objetivo analisar o dataset de vendas de um supermercado, gerando insights de negócio através de KPIs e visualizações interativas. Ele simula um mini dashboard de BI dentro do Jupyter Notebook, permitindo filtrar vendas por cidade, tipo de produto e forma de pagamento.

O dashboard apresenta:

- KPIs de performance: Receita Total, Ticket Médio, Maior Venda e Nº de Transações  
- Evolução das vendas ao longo do tempo  
- Vendas por hora do dia  
- Top 5 produtos por receita  
- Heatmap de receita por cidade e linha de produto  

---

## Dataset
O dataset utilizado contém as seguintes colunas:

- `Invoice ID` – ID da nota fiscal  
- `Branch` – Filial  
- `City` – Cidade  
- `Customer type` – Tipo de cliente (Membro/Não Membro)  
- `Gender` – Gênero do cliente  
- `Product line` – Linha de produto  
- `Unit price` – Preço unitário  
- `Quantity` – Quantidade vendida  
- `Tax 5%` – Imposto  
- `Sales` – Total da venda  
- `Date` – Data da compra  
- `Time` – Hora da compra  
- `Payment` – Forma de pagamento  
- `cogs` – Custo do produto  
- `gross margin percentage` – Margem bruta em %  
- `gross income` – Lucro bruto  
- `Rating` – Avaliação do cliente  

**Fonte:** Dataset fictício de análise de vendas de supermercado.

---

## Ferramentas Utilizadas
- Python 3.x  
- Jupyter Notebook  
- Pandas (limpeza e manipulação de dados)  
- Plotly (visualizações interativas)  
- ipywidgets (filtros interativos no dashboard)  

---

## Como Rodar o Projeto

1. Clone o repositório:
```bash
git clone <URL_DO_REPOSITORIO>
Instale as dependências:

bash
Copiar código
pip install pandas plotly ipywidgets
Abra o notebook SuperMarket_Analysis.ipynb no Jupyter Notebook ou JupyterLab.

Execute todas as células para interagir com o dashboard.

Funcionalidades Interativas
Selecione uma cidade, linha de produto ou forma de pagamento nos filtros no topo do dashboard.

Os KPIs e gráficos serão atualizados automaticamente.

Explore insights de negócio como horários de maior venda, produtos mais rentáveis e desempenho por cidade.

Demonstração

Exemplo de layout interativo do dashboard.

Próximos Passos
Implementar análise preditiva de vendas usando modelos de Machine Learning.

Adicionar mais métricas financeiras, como margem líquida e lucro por produto.

Transformar o notebook em uma aplicação web interativa usando Dash ou Streamlit.

Autor
Alexandre Lotti
Cientista  de Dados | Especialista em Visualização e BI

# 📊 Análise de Dados - Delivery Rocketseat

Este projeto foi desenvolvido como parte de um desafio da **Rocketseat**, com o objetivo de realizar uma análise exploratória de dados de um delivery de refeições.  
A análise utiliza **Python, Pandas e NumPy** para explorar os pedidos e o cardápio, gerar insights de vendas e calcular indicadores estratégicos.

---

## 📂 Estrutura dos Dados

### pedidos.csv
- Data do pedido  
- Item pedido  
- Quantidade  
- Preço unitário cobrado  

### cardapio.csv
- Nome do item  
- Categoria (Salgados, Bebidas, Sobremesas, etc.)  
- Preço base  

---

## 🛠️ Etapas da Análise

1. **Importações** – bibliotecas essenciais (Pandas e NumPy).  
2. **Carregamento dos Dados** – leitura dos arquivos CSV.  
3. **EDA (Exploração)** – inspeção inicial dos dados.  
4. **Feature Engineering** – criação da coluna `Receita_Item`.  
5. **Tratamento de Dados** – correção de valores ausentes.  
6. **Agregações** – análise por item e identificação dos top 5.  
7. **Análise Temporal** – evolução das vendas por mês.  
8. **Merge** – integração com o cardápio para análise por categoria.  
9. **Filtros** – consultas específicas (ex.: salgados > 10 unidades).  
10. **KPIs** – cálculo de indicadores (Receita Total, Itens Vendidos, Ticket Médio).  
11. **Extra** – cálculo de percentis com NumPy.  

---

## 📈 KPIs Calculados

- **Receita Total**  
- **Total de Itens Vendidos**  
- **Ticket Médio**  
- **Percentis de Preço Unitário e Quantidade**  

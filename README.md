# Analise-Supermercado
# 🛒 Análise de Vendas de Supermercado

Este projeto realiza uma análise exploratória e estratégica de dados de vendas de um supermercado, utilizando o dataset `supermercado.csv`. O objetivo é extrair insights relevantes para tomada de decisão gerencial, como desempenho por filial, comportamento de clientes, produtos mais vendidos e impacto tributário.

---

## 📁 Dataset: `supermercado.csv`

O arquivo contém registros detalhados de transações realizadas em quatro filiais: São Luís, Imperatriz, Teresina e Belém.

### 📌 Estrutura das Colunas

| Coluna             | Descrição                                                                 |
|--------------------|---------------------------------------------------------------------------|
| `ID_Transacao`     | Identificador único da compra                                             |
| `Data`             | Data da transação                                                         |
| `Hora`             | Horário da transação                                                      |
| `Filial`           | Loja onde a compra ocorreu                                                |
| `Tipo_Cliente`     | Tipo de cliente (Membro ou Normal)                                        |
| `Forma_Pagamento`  | Método de pagamento                                                       |
| `Produto`          | Item comprado                                                             |
| `Categoria`        | Categoria do produto                                                      |
| `Preco_Unitario`   | Preço por unidade                                                         |
| `Quantidade`       | Número de unidades compradas                                              |
| `Custo`            | Preço total do item (Preco_Unitario × Quantidade)                         |
| `Imposto_ICMS`     | Imposto de 18% sobre o custo                                              |
| `Total`            | Valor final da compra, incluindo o imposto                                |
| `Avaliacao_Cliente`| Nota de 1 a 10 dada pelo cliente                                           |

---

## 🧪 Análises Realizadas

- Receita total por filial
- Avaliação média por loja e tipo de cliente
- Produtos mais vendidos e mais lucrativos
- Vendas por hora e dia da semana
- Impacto do imposto ICMS por produto e categoria
- Comparação entre clientes membros e normais
- Ticket médio por transação
- Tendência de vendas ao longo do tempo

---

## 📊 Ferramentas Utilizadas

- **Python**: pandas, matplotlib, seaborn
- **Jupyter Notebook**: para visualização e exploração interativa
- (Opcional) **Power BI / Excel**: para dashboards visuais

---


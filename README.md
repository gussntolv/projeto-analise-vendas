# 📊 Análise de Vendas - Tratamento de Dados com Python e Power BI

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Pandas](https://img.shields.io/badge/Pandas-DataFrame-green) ![PowerBI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)

## 📌 Descrição do Projeto

Projeto de análise de dados completo onde simulei um cenário real de e-commerce. Os dados estavam "sujos" (datas inconsistentes, preços mal formatados, emails inválidos) e passei por todo o processo de limpeza, transformação e visualização.

**Objetivo:** Demonstrar habilidades de tratamento de dados e criação de dashboard interativo.

---

## 🛠️ Tecnologias Utilizadas

- **Python** (Pandas, Matplotlib) - Limpeza e transformação
- **Power BI** - Dashboard interativo
- **CSV** - Fonte de dados
- **Jupyter Notebook** - Ambiente de desenvolvimento

- 
---

## 🔄 Etapas do Projeto

1. Carregamento do CSV com dados brutos
2. Exploração inicial dos dados
3. Tratamento de datas (múltiplos formatos)
4. Limpeza de preços (remoção de R$, conversão de vírgula)
5. Correção de quantidades negativas
6. Tratamento de emails inválidos
7. Criação da coluna de valor total
8. Exportação dos dados limpos
9. Criação do dashboard no Power BI

---

## ⚠️ Problemas Encontrados e Soluções

| Problema | Solução |
|----------|---------|
| Datas em formatos diferentes (2024-01-15, 15/02/2024, 2024-Mar-03) | Criei função com lista de formatos possíveis |
| Data inválida (31/02/2024) | Corrigi manualmente para 28/02/2024 |
| Preços com "R$ 1.299,90" | Removi R$, espaços, troquei ponto e vírgula |
| Quantidades negativas (-1, -2) | Converti para valor absoluto |
| Emails com caracteres estranhos | Substituí por NaN (mantendo a linha) |
| Valores textuais no lugar de números | Converti para float/int |

---

## 📈 Insights do Dashboard

- **Categoria mais vendida:** Eletrônicos 
- **Faturamento Total:** R$ 294,49 MIL
- **Ticket médio:** R$ 589,99
---

## 🚀 Como Reproduzir

1. Clone o repositório:
```bash
git clone https://github.com/gussntolv/projeto-analise-vendas.git

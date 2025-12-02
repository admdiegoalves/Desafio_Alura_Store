# 🛒 Desafio Alura Store: Análise de Desempenho e Recomendação de Venda

## 🎯 Objetivo do Projeto

Este projeto de Análise de Dados foi desenvolvido para atender à solicitação do Sr. João, proprietário da Alura Store, que planeja vender uma de suas quatro lojas para investir em um novo empreendimento.

O objetivo principal é responder à pergunta: **"Qual loja da Alura Store o João deve vender?"**

A recomendação final é baseada em uma análise quantitativa e visual de métricas de desempenho essenciais para o negócio.

---

## 📊 Metodologia e Análises Chave

Utilizamos a biblioteca Pandas para manipulação de dados e o Matplotlib/Seaborn para visualização. As seguintes métricas foram analisadas por loja:

1.  **Faturamento Total:** KPI primário para medir a contribuição de receita.
2.  **Média de Avaliação dos Clientes:** Indicador de Satisfação e Qualidade (notas de 1 a 5).
3.  **Custo Logístico (Frete Médio):** Para entender a eficiência da operação de envio.
4.  **Desempenho Geográfico (Extra):** Mapeamento de vendas por Latitude e Longitude para identificar a área de atuação e densidade de clientes de cada loja.

### 📈 Visualizações Geradas

Foram criados gráficos concisos para cada métrica principal:

* **Faturamento Total por Loja:** Gráfico de Barras
* **Média de Avaliação por Loja:** Gráfico de Barras Horizontais (Alternativa ao formato circular, por clareza analítica)
* **Distribuição de Produtos:** Gráfico de Barras (Top 10 Produtos Mais Vendidos)

---

## 💡 Conclusão e Recomendação

| Métrica | Loja com Pior Desempenho | Loja com Melhor Desempenho |
| :--- | :--- | :--- |
| **Faturamento Total** | **Loja 4** (Menor Receita) | Loja 1 (Maior Receita) |
| **Média de Avaliação** | **Loja 1** (3.98 - Pior Satisfação) | Loja 3 (4.05 - Melhor Satisfação) |
| **Frete Médio** | Loja 3 (Maior Custo) | Loja 1 (Menor Custo) |

### Recomendação: Vender a **Loja 4**

Embora a Loja 1 tenha a pior avaliação de clientes (o que exige atenção imediata para o serviço), a **Loja 4** é a loja com **menor faturamento total** e, portanto, o ativo com menor contribuição para a receita da rede.

**Justificativa:** A venda da Loja 4 permite ao Sr. João:
* Eliminar o ativo menos produtivo em termos de receita.
* Concentrar o capital de investimento nas outras lojas (especialmente na Loja 1 para resolver o problema de satisfação) e no novo empreendimento.

---

## 📁 Estrutura do Projeto

* `Alura_Store_Analise.ipynb`: Notebook Jupyter contendo todas as etapas da análise, limpeza de dados, cálculos e geração de gráficos.
* `README.md`: Este arquivo.
* `/dados`: Diretório com o dataset original de vendas (assumindo que o arquivo de dados está aqui).

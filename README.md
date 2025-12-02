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

### 💡 Recomendação Final: Vender a Loja 4

A Loja 4 apresenta o pior desempenho nas métricas mais críticas:
* Menor Receita: A Loja 4 gera o menor volume de faturamento total, indicando a menor contribuição para a receita consolidada da Alura Store.
* Satisfação: Possui uma das menores médias de avaliação, sugerindo problemas na experiência do cliente ou qualidade de entrega/produto.
Vender a Loja 4 permite ao Sr. João eliminar o ativo de menor performance em termos de receita e, provavelmente, o de maior risco em termos de satisfação. O capital obtido da venda pode ser investido no novo empreendimento ou nas outras três lojas mais eficientes.

---

## 📁 Estrutura do Projeto

* `Desafio_Alura_Store.ipynb`: Notebook Colab contendo todas as etapas da análise, limpeza de dados, cálculos e geração de gráficos.
* `README.md`: Este arquivo.
* `/dados`:
(https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
(https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
(https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
(https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

# 🛒 Alura Store - Análise de Desempenho Multilojas

## 📝 Propósito da Análise
Este projeto foi desenvolvido para analisar o desempenho de quatro unidades da **Alura Store**. O objetivo principal é extrair insights estratégicos a partir de dados reais de vendas para identificar qual loja apresenta os melhores indicadores e qual possui gargalos operacionais. 

A análise auxilia na tomada de decisão sobre:
* Faturamento e saúde financeira por unidade.
* Satisfação do cliente (NPS) através de avaliações.
* Eficiência logística e custo de frete.
* Comportamento de compra por categoria e localização geográfica.

---

## 📂 Estrutura do Projeto
O projeto está organizado em um único notebook interativo (`.ipynb`) que segue a seguinte ordem lógica:

1.  **Extração de Dados**: Carregamento automatizado de bases CSV via GitHub.
2.  **Exploração e Limpeza**: Verificação da estrutura (`head`, `columns`) e tratamento de nomes de colunas.
3.  **Análise Quantitativa**:
    * Cálculo de Faturamento Total.
    * Média de Avaliações por Loja.
    * Custo Médio de Frete.
4.  **Análise Qualitativa**:
    * Ranking de Categorias mais vendidas.
    * Produtos "Best-Sellers" vs. Menos vendidos.
5.  **Visualização de Dados**: Geração de múltiplos gráficos para síntese de resultados.
6.  **Análise Geográfica (Extra)**: Mapeamento de vendas por Latitude e Longitude.

---

## 📊 Gráficos e Insights Obtidos
Para esta análise, foram implementadas as seguintes visualizações:

* **Gráfico de Barras (Faturamento)**: Comparativo direto de receita entre as lojas.
    * *Insight*: Permite identificar rapidamente a loja líder em vendas.
* **Gráfico de Linhas (Avaliações)**: Mostra a variação da satisfação do cliente entre as unidades.
    * *Insight*: Crucial para entender onde o atendimento ou qualidade do produto precisa melhorar.
* **Gráfico de Pizza (Pagamentos)**: Distribuição dos métodos preferidos (Cartão, Pix, Boleto).
    * *Insight*: Ajuda na negociação de taxas com operadoras financeiras.
* **Gráfico de Dispersão (Preço x Frete)**: Analisa se o valor do produto impacta o custo de envio.
    * *Insight*: Identifica se o frete está sendo impeditivo para produtos de baixo ticket médio.
* **Mapa de Calor/Dispersão Geográfica**: Localização exata das vendas.
    * *Insight*: Revela em quais regiões a marca tem maior penetração de mercado.

---

## 🛠️ Tecnologias Utilizadas
* **Python 3.x**
* **Pandas**: Manipulação e análise de dados.
* **Matplotlib**: Criação de gráficos estáticos.
* **Folium**: Mapas interativos de geolocalização.

---

## 🚀 Instruções para Executar
1.  Abra o [Google Colab](https://colab.research.google.com/).
2.  Crie um novo Notebook.
3.  Certifique-se de que a biblioteca `pandas` e `matplotlib` estão disponíveis (padrão no Colab). Caso queira o mapa interativo, instale o Folium:
    ```bash
    !pip install folium
    ```
4.  Copie e cole as células do projeto na ordem apresentada.
5.  Execute as células (`Shift + Enter`) para processar os dados e gerar as visualizações em tempo real.

---
**Desenvolvido por:** Tanuris Pina

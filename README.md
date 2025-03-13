# 💡 Análise de Teste A/B de Eventos de Marketing

Bem-vindo ao repositório! Aqui você encontrará uma análise detalhada de um teste A/B aplicado a eventos de marketing, com o objetivo de avaliar o impacto de diferentes estratégias sobre as taxas de conversão, receita e comportamento dos usuários.

---

## 📌 Descrição do Projeto

O projeto busca responder perguntas-chave relacionadas ao desempenho de estratégias de marketing testadas por meio de um experimento controlado A/B:

- Qual o impacto das estratégias sobre as taxas de conversão?  
- Existe diferença estatisticamente significativa entre os grupos A e B?  
- Que insights podemos obter sobre receita e comportamento ao longo do funil de conversão?  

O objetivo é identificar estratégias mais eficazes e apoiar decisões com base em dados sólidos.

---

## 🛠️ Ferramentas e Tecnologias Utilizadas

- **Python**: Manipulação e análise de dados.
- **Bibliotecas**: Pandas, NumPy, SciPy, Matplotlib e Seaborn.
- **Testes Estatísticos**: Aplicação de Teste Z para comparação de proporções e avaliação de significância.

---

## 📂 Estrutura do Projeto

- **Coleta e Tratamento de Dados**:  
  - Carregamento de datasets, incluindo eventos, novos usuários e participantes do teste.
  - Filtragem do período do experimento e tratamento de valores ausentes.

- **Análises Exploratórias**:  
  - Cálculo da proporção de usuários duplicados entre os grupos.  
  - Identificação de padrões sazonais e distribuição de eventos ao longo do tempo.  

- **Taxas de Conversão e Testes Estatísticos**:  
  - Análise das taxas de conversão por etapa do funil (ex.: product_page → product_cart → purchase).  
  - Teste Z para verificar a significância estatística das diferenças entre os grupos A e B.  

- **Visualizações**:  
  - Gráficos para explorar taxas de conversão, sazonalidade e distribuição de receita.  

---

## 📊 Exemplos de Visualizações

1. **Distribuição de Eventos Diários**  
   Um gráfico de linha destacando a frequência de eventos ao longo do tempo, com ênfase no período do teste e datas sazonais.  

2. **Receita Cumulativa por Grupo**  
   Gráfico de linha mostrando a receita acumulada dos grupos A e B durante o experimento.

3. **Taxa de Conversão por Etapa do Funil**  
   Gráfico de barras comparando as taxas de conversão para os grupos A e B em cada etapa (ex.: product_page → product_cart → purchase).  

4. **Duplicação de Usuários entre os Grupos**  
   Análise detalhando a proporção de usuários duplicados presentes em ambos os grupos.  

5. **Resultados do Teste Estatístico (Teste Z)**  
   Para cada etapa do funil, calculamos os seguintes indicadores:
   - **Z-score**: Mede a diferença em desvios padrão.  
   - **P-value**: Determina a significância a um nível de 5% (0,05).  
   - **Significância**: Se a diferença é estatisticamente relevante.  



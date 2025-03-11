Análise de Teste A/B de Eventos de Marketing 💡
Este repositório contém uma análise detalhada de um teste A/B aplicado a eventos de marketing, com o objetivo de avaliar o impacto de diferentes estratégias sobre a conversão, a receita e o comportamento do usuário.

 Descrição do Projeto
O projeto analisa dados de um teste A/B para responder perguntas importantes, como:

Qual o impacto das estratégias testadas sobre as taxas de conversão?

Existe diferença estatisticamente significativa entre os grupos de teste?

Quais insights podemos obter sobre a receita e o comportamento dos usuários ao longo do funil?

 Ferramentas e Tecnologias Utilizadas
Python: Manipulação e análise de dados.

Bibliotecas: Pandas, NumPy, SciPy, Matplotlib, Seaborn.

Testes Estatísticos: Teste Z para comparação de proporções.

 Estrutura do Projeto
Coleta e Tratamento de Dados:

Carregamento de datasets com eventos, novos usuários e participantes do teste.

Filtragem do período do teste e tratamento de valores ausentes.

Análises Explorativas:

Identificação e cálculo da proporção de usuários duplicados entre os grupos de teste.

Distribuição de eventos ao longo do tempo e sazonalidade.

Taxas de Conversão e Testes Estatísticos:

Cálculo de taxas de conversão em cada etapa do funil para os grupos A e B.

Análise estatística (teste Z) para verificar a significância das diferenças entre os grupos.

Visualizações:

Gráficos que destacam taxas de conversão, distribuição de receita e sazonalidade.

 Exemplos de Visualizações
1. Distribuição de Eventos Diários
Um gráfico de linha exibindo a frequência de eventos por dia, com destaques para o período de teste e datas sazonais (ex.: Natal e Ano Novo).


2. Receita Cumulativa por Grupo
Gráfico de linha comparando a receita cumulativa dos grupos A e B durante o teste.


3. Taxa de Conversão por Etapa do Funil
Gráfico de barras apresentando as taxas de conversão em cada etapa do funil (product_page, product_cart, purchase) para os grupos A e B.


4. Duplicação de Usuários entre os Grupos
A análise identificou duplicatas no conjunto de participantes. Cerca de X% dos usuários estavam presentes em ambos os grupos, o que pode influenciar os resultados do teste.

5. Teste Estatístico (Teste Z)
Executamos um teste Z para verificar se as diferenças observadas nas taxas de conversão entre os grupos A e B são estatisticamente significativas. Para cada etapa do funil:

Z-score: Mede a diferença em desvios padrão.

P-value: Indica se a diferença é significativa a um nível de 5% (0,05).

Exemplos de Resultados:
Etapa do Funil: product_page → product_cart

Z-score: X

P-value: Y

Significância: Sim/Não

Etapa do Funil: product_cart → purchase

Z-score: X

P-value: Y

Significância: Sim/Não

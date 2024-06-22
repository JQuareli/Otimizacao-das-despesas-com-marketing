# Análise de Dados de Marketing para Y.Afisha

Este projeto foi desenvolvido para otimizar as despesas com marketing da Y.Afisha, analisando como os usuários interagem com o produto, suas tendências de compra e a efetividade das campanhas de marketing. Utilizando logs de servidor, dados de pedidos e estatísticas de despesas, realizamos uma análise detalhada para fornecer recomendações de investimento baseadas em dados.

## Índice

- [Metodologia](#metodologia)
- [Bibliotecas Utilizadas](#bibliotecas-utilizadas)
- [Conclusões](#conclusões)
- [Como Utilizar](#como-utilizar-este-repositório)
- [Possíveis Melhorias](#possíveis-melhorias)

## Metodologia

### Carregamento e Preparação dos Dados

1. **Carregamento dos Dados**:
    - Dados de acessos: `/datasets/visits_log_us.csv`
    - Dados de pedidos: `/datasets/orders_log_us.csv`
    - Dados de despesas: `/datasets/costs_us.csv`

2. **Preparação dos Dados**:
    - Neste ponto os dados foram limpos e organizados utilizando a biblioteca Pandas do Python para garantir a precisão das análises subsequentes.

### Relatórios e Cálculo de Métricas

1. **Acessos**:
    - Avaliamos detalhadamente as informações relacionadas às sessões dos usuários, como a quantidade de acessos durante os dias, semanas e ao longo dos meses e a duração de cada sessão.
    - Utilizamos gráficos de calor para visualizar os dados sobre a frequência de retorno dos usuários.

2. **Vendas**:
    - Também foi avaliado informações importantes a respeito das conversões, como o tempo para a primeira compra do usuário, a quantidade de pedidos por cliente, o volume médio (ticket médio) e o Lifetime Value (LTV).

3. **Marketing**:
    -Por fim, foram feitas análises a respeito das campanhas de marketing, como as despesas totais com as campanhas ao longo do tempo, e por origem, os custos de aquisição dos clientes (CAC) e o retorno sobre o investimento de marketing (ROMI).

Por fim, ainda foram tiradas conclusões a respeito das campanhas, avaliando os indicadores citados acima e seu desempenho ao longo do tempo.

## Bibliotecas Utilizadas

As seguintes bibliotecas Python foram utilizadas para a análise de dados e visualização:

- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

## Conclusões

A análise dos dados me permitiu obter insights valiosos a respeito do comportamento dos clientes, o desempenho das vendas e a eficácia das campanhas de marketing da Y.Afisha:

### Desempenho dos Anúncios e ROI
As origens de anúncios com maiores custos de aquisição de clientes (CAC) também apresentam os maiores retornos sobre o investimento (ROI), especialmente ao longo do tempo. Isso indica que os benefícios das campanhas de marketing se acumulam ao longo do tempo, reforçando a importância de um investimento contínuo e bem planejado.

### Eficiência das Origens de Anúncios
Com base nos dados das tabelas, verificou-se que as diferentes origens de anúncios possuem variações significativas em termos de custos e rentabilidades. Analisando o ROMI (Return on Marketing Investment), ficou evidente que as origens de anúncios com maiores custos (CAC) também são as que trazem maiores retornos financeiros.

### Estratégia de Investimento
A principal conclusão que pode ser retirada das análises é a necessidade de aumentar os investimentos nas origens de anúncios que trazem os maiores retornos. Especificamente, as origens 10 e 9 foram identificadas como as mais rentáveis, apesar dos altos custos iniciais. Assim, recomenda-se direcionar mais recursos para essas fontes de anúncios para maximizar o retorno sobre o investimento.

## Como utilizar este repositório

Para utilizar, basta clonar o repositório e instalar o arquivo requirements.txt em um ambiente Python. Os scripts são bem documentados e podem ser facilmente adaptados para outras análises de dados.

## Possíveis melhorias
O principal ponto em que o projeto pode ser melhorado é em relação a apresentação dos dados, criar gráficos e visualizações mais detalhadas que mostrem melhor a evolução ao longo do tempo, permitindo identificar padrões e tendencias de forma mais clara. Implementar gráficos interativos que permitam aos usuários explorar os dados em diferentes níveis de detalhe. Ferramentas como Plotly ou Tableau podem ser utilizadas para criar visualizações interativas que facilitem a análise e interpretação dos dados.

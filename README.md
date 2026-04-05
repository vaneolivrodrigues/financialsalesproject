📋 Visão Geral do Projeto
Este projeto consistiu na criação de um ecossistema de Business Intelligence para análise de performance financeira global. 
O objetivo foi consolidar dados de vendas, custos e unidades comercializadas entre 2013 e 2014, permitindo uma visão clara da rentabilidade por produto, segmento de mercado e localização geográfica.
Projeto foi estruturado durante o curso.

⚙️ Inteligência de ETL: Transformando Dados em Informação
A etapa de preparação de dados foi o pilar central para garantir que o dashboard não fosse apenas um conjunto de gráficos, mas uma ferramenta de decisão.

1. Modelagem e Estrutura de Dados

    Normalização de Séries Temporais: Os dados foram tratados para permitir a comparação direta entre os anos de 2013 e 2014, organizando a hierarquia de Ano e Mês para análises de tendência.

    Criação de KPIs de Valor: Através de transformações no ETL e DAX, o dado bruto foi convertido em indicadores estratégicos, como a Média de Sale Price por Produto e a Média de Profit Mensal.

2. Lógica de Negócio Aplicada

    Segmentação de Mercado: O pipeline de dados categorizou as transações em segmentos distintos (Government, Small Business, Enterprise, etc.), permitindo identificar que o setor governamental representa a maior fatia do lucro (65,04% do total).

    Geoprocessamento: Os dados de localização foram tratados para geração de mapas coropléticos, vinculando vendas e unidades vendidas a regiões da América do Norte e Europa.

📊 Visualização de Dados e Storytelling (Power BI)
O dashboard foi dividido em três visões principais para facilitar o consumo da informação por diferentes níveis hierárquicos:

Visão 01: Performance de Produto e Segmento

    Análise de Mix: Gráfico de rosca detalhando a Soma de Sales por Produto, destacando os produtos Velo e Paseo como líderes de faturamento.

    Sensibilidade de Preço: Gráfico de área cruzando a média de preço de venda por produto para identificar elasticidade e posicionamento de mercado.

Visão 02: Rentabilidade Regional e Temporal

    Ranking por País: Gráficos de barras comparando a Soma de Sales entre EUA, Canadá, França, Alemanha e México, revelando uma distribuição equilibrada de mercado (acima de 21 Mi por país líder).

    Sazonalidade: Gráfico de colunas analisando a Média de Profit por Ano e Mês, permitindo identificar picos de lucratividade (como os 33 mil em fevereiro de 2014).

Visão 03: Distribuição Geográfica e Volume

    Mapas de Calor: Visualização espacial da Soma de Units Sold, facilitando a identificação imediata de mercados com alto volume mas potencial margem a ser otimizada.


🚀 Impacto Gerado

Descoberta Estratégica: Identificação de que, apesar do alto volume de vendas, o lucro está concentrado no segmento Government, sugerindo uma revisão de estratégia para o segmento Enterprise (atualmente com a menor participação).

Eficiência Operacional: Centralização de métricas que antes estariam dispersas em planilhas, reduzindo o tempo de resposta para ajustes de preço e estoque.

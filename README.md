# Estudo de Caso: Análise de Vendas e Previsão em Loja Virtual  

## Introdução  
Neste projeto, utilizei o Superstore Dataset para explorar e prever o desempenho de vendas de uma loja virtual. A análise foi motivada pela necessidade de entender melhor os padrões de vendas e como eles podem influenciar as estratégias de marketing e operação da loja. O objetivo foi desenvolver um modelo preditivo que permita prever vendas futuras, além de gerar insights acionáveis a partir dos dados disponíveis.  

## Dados Utilizados  
A base de dados foi obtida do Kaggle e armazena informações detalhadas sobre vendas, clientes e produtos de uma loja online. As colunas incluem:  

| Coluna              | Descrição                                         | Tipo    |  
|---------------------|---------------------------------------------------|---------|  
| Order ID            | Código de identificação do pedido                  | String  |  
| Order Date          | Data do pedido                                    | Date    |  
| Ship Date           | Data de envio do pedido                           | Date    |  
| Customer ID         | Código de identificação do cliente                 | String  |  
| Customer Name       | Nome do cliente                                   | String  |  
| Segment             | Segmento do cliente (Consumer, Corporate, etc.)  | String  |  
| Country             | País do cliente                                   | String  |  
| State               | Estado do cliente                                 | String  |  
| Product ID          | Código do produto                                 | String  |  
| Category            | Categoria do produto                              | String  |  
| Sub-Category        | Subcategoria do produto                           | String  |  
| Sales               | Valor da venda                                   | Float   |  
| Quantity            | Quantidade vendida                               | Int     |  
| Discount            | Desconto aplicado                                | Float   |  
| Profit              | Lucro gerado pela venda                          | Float   |  

## Etapas de Desenvolvimento  

### Etapa 01: Análise Exploratória dos Dados (Data Understanding)  
Iniciei o projeto carregando a base de dados e realizando uma descrição estatística para entender as variáveis disponíveis. Utilize as funções `.info()` e `.isna().sum()` para verificar a quantidade de valores faltantes e a distribuição dos dados.  

### Etapa 02: Tratamento dos Dados (Data Preparation)  
Substituí valores “NaN” em colunas relevantes por 0 e removi linhas que apresentavam dados nulos em colunas críticas como Customer Name e Segment. Além disso, converti valores flutuantes em inteiros quando necessário, garantindo que os dados estivessem no formato apropriado para a análise.  

### Etapa 03: Análise Exploratória Aprofundada e Visualizações  
Realizei uma análise exploratória mais detalhada, utilizando bibliotecas como Matplotlib e Seaborn para criar visualizações informativas. Identifiquei e documentei 3-5 insights significativos, como tendências de vendas por região e a relação entre descontos e lucros.  

### Etapa 04: Modelagem dos Dados - Previsão de Vendas  
Desenvolvi um modelo preditivo para a previsão de vendas. Defini as variáveis X (fatores preditivos) e y (vendas) e realizei o ajuste do modelo. Separei os dados em conjuntos de treino e teste, e utilizei métricas como RMSE e R² para avaliar o desempenho do modelo.  

### Etapa 05: Integração com IA Generativa  
Integrei as análises a um modelo de IA generativa que me permitiu gerar insights em linguagem natural, facilitando a interpretação dos resultados. Documentei a abordagem e os resultados obtidos, ressaltando como essa tecnologia pode tornar a comunicação dos dados mais acessível.  

## Conclusão  
Ao final deste projeto, consegui desenvolver um modelo preditivo que oferece uma visão clara das vendas esperadas, além de gerar insights valiosos para otimização de estratégias de vendas e marketing. Esses resultados são fundamentais para a equipe de gestão da loja virtual, ajudando a informar decisões estratégicas para melhorar o desempenho e aumentar a rentabilidade. Estou animado para continuar explorando as possibilidades que a análise de dados proporciona! 

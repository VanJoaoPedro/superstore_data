# Mini Projeto 2 Aplicado: Análise de Vendas com o Power BI

## Objetivo:

Este projeto tem como objetivo implementar os conceitos de análise de dados de vendas apresentados no capítulo 05 do curso gratuito ["Microsoft Power BI Para Business Intelligence e Data Science"](https://www.datascienceacademy.com.br/course/microsoft-power-bi-para-business-intelligence-e-data-science), da Data Science Academy. Além de reproduzir os gráficos criados durante as aulas do capítulo, foi desenvolvida uma nova visualização para monitorar os indicadores de lucro.
## Os dados:

A base de dados selecionada para este projeto foi a [Sample Superstore Dataset](https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset) disponível na plataforma gratuita da Kaggle.

### Contexto:

### Dicionário dos dados:
   
| Coluna | Siginificado  |
| --- | --- |
| Ship Mode | Modalidade da entrega do produto |
| Segment | Segmento de clientes para o qual o produto foi envido |
| Country | País na qual a remessa foi entregue |
| City | Cidade na qual a remessa foi entregue |
| State | Estado na qual a remessa foi entregue |
| Postal Code | Codigo postal na qual a remessa foi entregue |
| Region | Região do país|
| Category | Categoria do produto |
| Sub-Category | Sub-categoria do produto |
| Sales | Vendas em Dolares |
| Quantity | Quantidade do produto |
| Discount | Disconto concedido no produto |
| Profit | Lucro/Perda obtido na venda |

## Iniciando o projeto: Narrativa inteligente.


### Qual é o segmento mais vendido?

> Para responder a essa pergunta, utiliza o gráfico de rosca.

![Grafico de rosca.png](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Grafico%20de%20rosca.png)

> Na base de dados, os segmentos estão divididos em Consumer (Consumidor), Corporate (Corporativo) e Home Office (Escritório em casa).

> O segmento de Consumidor apresentou o melhor desempenho nas vendas; em segundo lugar está o segmento Corporativo, seguido pelo segmento de Escritórios em Casa.
 
 ### Qual foi o produto que registrou as maiores vendas?
 
 > O gráfico selecionado foi o gráfico de barras, em razão da grande variedade de subcategorias presentes na coluna Sub-Category.

![Grafico de barras.png](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Grafico%20de%20barras.png)

 > Bookcases (Estantes de livros), Chairs (Cadeiras) e Phones (Telefones) são os produtos que tiveram mais vendas.
 
 ### Como se comportaram as vendas nas regiões?
 
 > O gráfico utilizado foi o funil, no qual as regiões estão ordenadas da maior para a menor quantidade de vendas.
 
![Grafico_funil.png](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Grafico_funil.png)

>  A região Oeste registrou o maior número de vendas, enquanto a região Sul apresentou o menor número de vendas.

### Narrativa Inteligente.

> A narrativa inteligente é uma ferramenta de visualização que gera um texto descritivo para contextualizar os insights presentes nos dados, auxiliando os usuários a compreenderem melhor as informações apresentadas no relatório.


![Narrativa Inteligente..png](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Narrativa%20Inteligente..png)


> Utilizando técnicas de linguagem natural e inteligência artificial para gerar automaticamente os textos de forma dinâmica, esses textos podem incluir análises estatísticas, tendências, padrões nos dados e outras informações relevantes.

### Primeiro Dashboard completo.


![Narrativa Inteligente.gif](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Narrativa%20Inteligente.gif)

> O objetivo deste primeiro painel de controle é observar o desempenho das vendas e utilizar a narrativa inteligente para facilitar a interpretação e a busca por alguns insights, tais como:

> * O segmento consumidor é o principal segmento da empresa.
> * Materiais de escritório como estantes e cadeiras são os produtos que mais venderam no período da amostra.
> * As regiões Oeste e Central são as regiões que registraram o maior volume de vendas.

## Parte 2: Principais Influenciadores.

### O que influencia o aumento e a diminuição das vendas?

> Para abordar essa questão, será empregado apenas um gráfico no Dashboard. Dada sua complexidade, a análise individual do gráfico facilita a interpretação.

![Principais influenciadores.gif](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Principais%20influenciadores.gif)

> O gráfico de principais influenciadores facilita a rápida identificação dos fatores mais relevantes que impulsionam ou afetam o resultado desejado, proporcionando insights como:
> * Tablets destacam-se como os principais produtos com potencial para aumentar as vendas da empresa, enquanto os Acessórios são os principais responsáveis pela redução nas vendas.

## Parte 3: Faixas de Vendas.

### Como as vendas de cada categoria se comportam em cada região?

> Para responder esse quetionamento, o Power Bi fornece a vizualzação "Grafico de Faixas", no qual gera faixas demonstrando o comportamento de vendas

![Faixa de vendas.gif](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Faixa%20de%20vendas.gif)

> Com base neste gráfico, é perceptível:
> * Na região Central, as vendas de móveis foram as mais expressivas em comparação com as de tecnologia e material de escritório.
> * Na região Oeste, por outro lado, as vendas de material de escritório apresentam uma queda em relação às vendas de tecnologia e móveis.
> * Na região Leste, as vendas de materiais de escritório superam as vendas das outras categorias.
> * Por último, a região Sul apresenta a maior estabilidade nas vendas.

## Parte 4: Mapa de Vendas.

### Como se comportam as vendas de cada categoria em cada estado?

> O gráfico de mapa é ideal para abordar essa questão, pois permite visualizar a distribuição das vendas em cada estado de forma clara e precisa.

![Mapa de Vendas.gif](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Mapa%20de%20Vendas.gif)

> Este mapa apresenta a distribuição das vendas em cada estado, fornecendo insights como:
> * California e Texas emergem como os estados com o maior volume de vendas.
> * Em comparação com California e Texas, os demais estados registram vendas significativamente mais baixas.

## Parte 5: Indicadores de Lucro

> Este último painel é um desafio pessoal para ir além do que foi proposto no curso.

### Como observar o Lucro / Prejuizo em cada Estado ?

> Para responder a esta pergunta, foi elaborado um painel completo, no qual cada visualização auxilia na agregação de informações.

#### Rank de Lucro. 
> Um ranking de lucro facilita a identificação imediata dos principais estados com maiores lucros e daqueles que apresentam prejuízo.

![Rank_de_lucro.png](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Rank_de_lucro.png)

#### Modo de Envio.
> O modo de envio pode influenciar significativamente no lucro de uma empresa. O custo de diferentes métodos de envio pode impactar diretamente o custo operacional. Além disso, a eficiência e a confiabilidade do método de envio refletem na satisfação do cliente. Portanto, é essencial observar como ele se comporta.


![Modo_de_envio.png](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Modo_de_envio.png)


#### Lucro por Segmento e Categoria:

> Aprimorar a compreensão dos setores de vendas que mais contribuem para o desempenho de uma empresa é crucial. Nesse sentido, é imprescindível analisar meticulosamente os segmentos e categorias que estão proporcionando os maiores retornos financeiros.



![Lucro_segmento_categoria.png](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Lucro_segmento_categoria.png)

#### Filtro dos Estados:
> Um filtro por estado é uma excelente maneira de analisar como esses indicadores se comportam de forma isolada em cada estado, seja ele o mais lucrativo ou aquele que gera prejuízos.
> 

![Filtro_estados.png](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Filtro_estados.png)


### Dashboard finalizado:



![Painel_de_lucro.gif](https://github.com/VanJoaoPedro/superstore_data/blob/main/Arquivos/Painel_de_lucro.gif)

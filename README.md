# Projeto Airplane Accidents

## Descrição Inicial

Durante o projeto, o meu objetivo foi passar pelas etapas de entendimento do problema, ideação da solução, análise dos fatores que poderiam influenciar. O objetivo era analisar alguns indicadores que comprovassem ou não a confiabilidade do avião como meio de transporte, considerado como meio mais seguro. Alguns questionamentos inicias importantes são:

- Qual a taxa de mortalidade em um acidente de avião e historicamente houve quantas mortes?

- Há um vislumbre de redução dessa taxa e de melhora nos dados?

- Quais companhias aéreas apresentam melhores taxas e quais, se puder, deveriam ser evitadas?

- Agrupando por continente de fundação das companhias aéreas, quais aqueles, que ao longo dos anos, ofereceram maior risco?

- Comparativamente, o nível, em números absolutos, de mortes é muito superior em acidentes de carro que avião? E em termos de taxa de mortalidade, há uma grande diferença?

Com o projeto é possível passar por comparações entre os acidentes de aviões e companhias, até o ponto de um comparativo com os acidentes de carro na Grã-Bretanha, para uma análise em termos de escala.

Para que a solução fosse entregue, foram utilizadas algumas tecnologias na Análise de Dados, tais como **Pandas, Plotly, SciPy**.

Para a realização das etapas de Análise de Dados, foi utilizado o **Pandas** para manipulação dos dados, o **Plotly** como feramenta de visualização de dados, de forma interativa e a biblioteca **SciPy** para realização de cálculos estatísticos.

## Etapas do Projeto

Foram utilizados três bases de dados:

- A primeira, **Airplane_Crashes_and_Fatalities_Since_1908** possui datas, informações sobre localização e do vôo que sofreu acidente, entre outras informações.

- A segunda, **airline-safety** possui informações sobre companhias aéreas e seus casos de acidente com quantidade de sobreviventes e de mortos.

- A terceira e última, **Accidents0515** contendo muitas informações sobre acidentes de carro na Grã-Bretanha.

#
**Durante a etapa de Análise de Dados foram descobertos diversos insights**

- Observa-se que a taxa de mortalidade de um acidente de avião é, em média, superior a 80%. Contudo, em termos absolutos, o número de mortes entre 1908 e 2009 teve seu pico em quase 3 mil mortes na década de 1970, e após 1999, não ultrapassou 1000 mortes ao ano.

- Kenya Airlines, China Airlines e Avianca apresentaram a maior taxa de mortalidade, enquanto Ethiopian Airlines, Aeroflot, Pakistan International apresentaram maior taxa de acidentes. Não menos importante, Ethiopian Airlines, Pakistan International e Aeroflot apresentaram maior taxa de acidentes fatais.

- Em termos de valores de mortes absolutos, a Europa, Ásia e América do Norte apresentam os piores índices (taxa de mortalidade, mortes). Em contrapartida, a taxa de mortalidade é maior na África, Ásia e América Central

- Mesmo com o baixo número de mortes em 2013, ainda eram contabilizadas 183 mil mortes por ano.
 
## Conclusão

Após a análise dos dados, é possível inferir que, em termos absolutos, acidentes de carro levam a um número maior de mortes por ano, por um fator de 60 vezes, porém possuem taxa de mortalidade,em média, 5 vezes menores.

Com o projeto existiu a análise de pontos críticos, como a taxa de mortalidade, quantidade de mortes e as principais linhas aéreas envolvidas em acidentes. 

Pensando-se em possíveis melhorias, seria interessante uma análise apenas dos dados de acidentes de avião da Grã-Bretanha, para ter melhor relação de escala com os acidentes de avião. Outro ponto, poderia ser criado um modelo preditivo, a partir dos dados de taxa de mortalidade, mortes e sobreviventes, para se ter uma melhor estimativa para os próximos anos e auxiliar nas metas de segurança do setor aeronáutico.

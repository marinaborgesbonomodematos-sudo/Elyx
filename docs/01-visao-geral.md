# Introdução
O Elyx é um projeto de análise de dados desenvolvido com o objetivo de explorar informações comerciais de uma empresa fictícia do setor varejista.

O setor varejista gera informações relacionadas às suas operações comerciais, incluindo registros de vendas, produtos, clientes e períodos de comercialização. A análise dessas informações permite investigar diferentes aspectos do desempenho das organizações e apoiar decisões relacionadas a estoque, promoções, planejamento de demanda e comportamento dos consumidores.

Segundo Rooderkerk, DeHoratius e Musalem (2022), a análise de dados no varejo contempla diferentes áreas de decisão e apresenta oportunidades de aprimoramento, incluindo desafios relacionados à qualidade e à integração das informações utilizadas pelas organizações.

Nesse contexto, o projeto Elyx propõe desenvolver uma análise de dados comerciais baseada em registros de uma empresa varejista fictícia utilizando um conjunto de dados público disponibilizado pelo UCI Machine Learning Repository.

A base selecionada, denominada Online Retail II, foi desenvolvida a partir de transações de uma empresa britânica de comércio eletrônico especializada na comercialização de artigos para presentes e diferentes ocasiões. O conjunto reúne registros referentes ao período de dezembro de 2009 a dezembro de 2011 e disponibiliza informações sobre produtos, quantidades, preços, datas de transação, identificadores de clientes e países (Chen, 2012).

A partir dessas informações, o Elyx pretende explorar o desempenho comercial, identificar padrões de vendas, investigar inconsistências nos registros e produzir indicadores que contribuam para a compreensão do comportamento das transações. O desenvolvimento será realizado de maneira incremental, iniciando com a exploração e organização dos dados no Microsoft Excel e avançando para consultas utilizando SQL, com possibilidade de incorporação de outras ferramentas em versões futuras.

## Cliente
 A Elyx é uma empresa fictícia do setor varejista, cuja atividade comercial envolve a comercialização de produtos para diferentes consumidores.

 A organização realiza transações comerciais que geram registros relacionados a produtos, quantidades comercializadas, valores e datas de venda. Essas informações representam uma fonte relevante para compreender o desempenho comercial da empresa. Entretanto, para que possam contribuir efetivamente com a tomada de decisões, precisam ser organizadas, exploradas e interpretadas.

*Observação:* a empresa é fictícia e não representa uma organização real. Seu contexto será delimitado de acordo com as características da base de dados selecionada.

## Problema
A empresa fictícia utilizada como contexto para o projeto possui dados históricos de vendas que ainda não foram explorados de forma estruturada para gerar informações gerenciais. Dessa forma, considera-se como problema central a ausência de uma análise consolidada que permita compreender o desempenho comercial ao longo do tempo, identificar os produtos com maior volume de vendas e acompanhar indicadores relevantes, como faturamento e quantidade de itens vendidos.

Diante desse cenário, o projeto propõe explorar e organizar os dados disponíveis, buscando identificar padrões, tendências e possíveis oportunidades de melhoria que possam contribuir para a tomada de decisões comerciais.

## Objetivos

### Objetivo geral
Desenvolver uma solução de análise de dados comerciais capaz de organizar, explorar e interpretar informações de vendas de uma empresa fictícia, permitindo identificar padrões, acompanhar indicadores de desempenho e gerar informações relevantes para apoiar a tomada de decisões.

### Objetivos específicos
- Compreender a estrutura e as características dos dados comerciais disponíveis.
- Identificar inconsistências e problemas de qualidade nos registros.
- Organizar e preparar os dados para análise.
- Desenvolver análises relacionadas ao volume de vendas e ao faturamento.
- Identificar padrões de desempenho por produto e período.
- Construir indicadores que facilitem a interpretação dos resultados.
- Aplicar ferramentas e técnicas de análise de dados de maneira incremental.
- Documentar os procedimentos, resultados e conclusões obtidos.

#### Objetivos da versão 1.0.0
A primeira versão do Elyx tem como finalidade realizar uma análise exploratória inicial dos dados comerciais, utilizando Microsoft Excel como ferramenta principal.

Seus objetivos em especial são:
- Identificar a origem, a estrutura e as características da base de dados. 
- Compreender o significado dos campos disponíveis.
- Identificar valores ausentes, duplicados e inconsistentes.
- Organizar os registros para possibilitar sua exploração.
- Calcular indicadores básicos de vendas e faturamento.
- Investigar o desempenho dos produtos comercializados.
- Observar variações no volume de vendas e no faturamento ao longo do tempo.
- Apresentar os resultados por meio de tabelas e gráficos.
- Documentar os procedimentos e as conclusões obtidas.

## Justificativa
A escolha do segmento varejista permite trabalhar com informações comerciais comuns em diferentes organizações, como produtos, quantidades vendidas, preços e datas de transações.
Além de proporcionar um cenário prático para o estudo de análise de dados, o projeto possibilita aplicar conhecimentos de organização de informações, tratamento de dados, consultas SQL e interpretação de resultados. O desenvolvimento incremental também permite demonstrar a evolução das habilidades técnicas ao longo das diferentes versões do projeto.


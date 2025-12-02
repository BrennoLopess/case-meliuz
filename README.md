
README – Case Técnico de Data Analytics | Méliuz

Visão Geral

Este repositório apresenta a solução completa desenvolvida para o processo seletivo de Estágio em Data Analytics da Méliuz. O objetivo deste projeto é demonstrar domínio técnico em análise de dados, capacidade de comunicação analítica e organização de insights orientados ao negócio. A entrega foi construída de forma estruturada, clara e profissional, refletindo boas práticas adotadas no dia a dia de equipes de dados.

O material inclui análise exploratória, construção de métricas, validação do teste A/B/C, visualizações e uma conclusão executiva com recomendações práticas. Todo o trabalho foi realizado em Python, utilizando Jupyter Notebook.

Objetivo do Estudo

O conjunto de dados fornecido possui quatro tabelas principais:

Clientes  
Pedidos  
Itens do pedido  
Produtos  

A partir desses dados, o desafio solicita:

Avaliação comparativa dos Grupos A, B e C (teste A/B/C)  
Análise geográfica de vendas (influência do estado e ranking por estados e cidades)  
Investigação do impacto da categoria de produto e da quantidade de itens no status dos pedidos  
Geração de métricas adicionais relevantes  
Criação de visualizações úteis  
Produção de conclusões claras e acionáveis  

Este repositório apresenta todo o processo, bem como os resultados alcançados.

Tecnologias Utilizadas

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
pandasql  
Jupyter Notebook  

Estrutura do Repositório

case-meliuz/  
    meliuz_abc_teste.ipynb  
    clientes.csv  
    pedidos.csv  
    produtos.csv  
    itens_pedido.csv  
    README.txt  

Principais Análises Realizadas

1. Desempenho dos Grupos A, B e C

Foram analisados:

Quantidade de clientes por grupo  
Quantidade de pedidos  
Taxa de conversão  
Ticket médio  
Receita total  
ARPU (receita média por cliente)  
Distribuição dos status  

Resultado: o Grupo B demonstrou desempenho superior em todas as métricas financeiras relevantes. Mesmo com volume de clientes semelhante aos demais, apresentou maior receita total, maior ticket médio e maior receita média por cliente. A recomendação para rollout é o Grupo B.

2. Influência do Estado no Valor das Vendas

As análises revelaram diferenças significativas entre estados. Estados do Norte e Nordeste, além de MG e GO, apresentaram receitas superiores. Estados como RS, RN e PB ficaram na parte inferior do ranking.

Conclusão: existe influência direta da localização geográfica no valor das vendas.

3. Ranking de Estados e Cidades

Os estados com maior receita foram RR, MG, MA, AL e GO.

As cidades com maior receita incluem São Paulo (considerando variações de grafia), Curitiba, Belo Horizonte, Goiânia e Rio de Janeiro.

Conclusão: o desempenho é fortemente concentrado em polos urbanos e regiões específicas do país.

4. Categoria do Produto e Quantidade de Itens x Status do Pedido

A taxa de cancelamento foi estável entre todas as categorias e faixas de quantidade de itens. As categorias apresentaram comportamento semelhante, assim como pedidos pequenos e grandes.

Conclusão: a categoria do produto e o volume de itens não influenciam o status dos pedidos.

5. Métricas Adicionais

Distribuição geral dos status  
Ticket médio mensal  
Top produtos mais vendidos  

As análises demonstraram estabilidade operacional, ausência de sazonalidade acentuada e portfólio diversificado com boa distribuição entre produtos.

Visualizações Incluídas

Distribuição dos status dos pedidos  
Evolução do ticket médio mensal  
Top estados por receita  
Top cidades por receita  
Top 10 produtos mais vendidos  

Conclusão Executiva

A partir da análise realizada, observamos:

O Grupo B apresentou melhor desempenho no teste A/B/C e deve ser priorizado em uma futura implementação.  
A geografia é um fator determinante no comportamento de compra.  
O pipeline operacional demonstra estabilidade, sem evidência de gargalos críticos.  
A categoria dos produtos e a quantidade de itens não influenciam o status final dos pedidos.  
A carteira de produtos se mostra diversificada e com distribuição saudável.  

O projeto atende integralmente ao escopo proposto e oferece insights claros, úteis e orientados ao negócio. A estrutura do notebook demonstra organização lógica, pensamento analítico e habilidade em transformar dados em decisões.

Autor

Brenno Lopes
Estudante de Engenharia de Software | Dados e Inteligência Artificial

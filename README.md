# Pipeline Faker

## [PoC] 

Este trabalho tem por objetivo criar dois artefatos: Batch e Streaming.

- Batch: Varias lojas registram vendas durante um periodo de tempo e carregam em um ambiente temporario. Os dados ficam nesse ambiente temporario por um periodo arbitrario de tempo. Nesse periodo um processo spark busca esses dados e os processa, para gerar um dashboard.

- Streaming: Varias lojas registram vendas e transmitem esse venda para o kafka, um processo spark conectado ao kafka consome esses dados e o processa para gerar um dashoard com informações sobre as vendas. 

Para cada artefato vai existir uma pasta neste repositório. Dentro de cada pasta vai se encontrar as informações de como executar o artefato.  

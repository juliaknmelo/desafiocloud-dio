# Desafio Cloud - DIO

Realizando análise de sentimentos com Language Studio no Azure AI.


## Input

- O texto de input realizado para o teste da ferramente se encontra na pasta "inputs" neste repósitorio. 


## Processo

Através da ferramenta Language Studio do Azure AI, foi realizado o input de um texto que se referia a avaliação de uma peça de roupa. Neste contexto o resumo geral de satisfação obtido pela AI foi:

* 74% positivo
* 1% neutro
* 25% negativo

<img src="/assets/sentimento-geral.png">


#### Referente a análise realizada por senteça, foram obtidos os seguintes resultados:

##### Sentença 1:

<img src="/assets/sentenca1.png">

* 95% positivo
* 4% neutro
* 1% negativo

##### Sentença 2:

<img src="/assets/sentenca2.png">

* 0% positivo
* 0% neutro
* 99% negativo

##### Sentença 3:

<img src="/assets/sentenca3.png">

* 99% positivo
* 0% neutro
* 0% negativo

##### Sentença 4:

<img src="/assets/sentenca4.png">

* 99% positivo
* 0% neutro
* 0% negativo


## Resultados

Os resultados obtidos pela ferramenta se mostraram bem parecidos com a realidade. Na primeira sentença por exemplo a porcentagem de positividade foi de 95% porém, a de negatividade foi de 4%, o que não reflete perfeitamente o texto, já que o cliente diz que a roupa serviu perfeitamente, ou seja, não há nada de negativo nisso. 

Na segunda sentença, o cliente relata insatisfação com ziper por ser dificil de subir e descer, e a ferramenta captou uma porcentagem de 99% de negatividade o que reflete a insatisfação do cliente. 

Na terceira e na quarta setença a positividade obtidade pela ferramenta foi de 99%, se mostrando identica à realidade, pois o cliente elogia a cor e o material, e por fim avalia o produto como muito confortável. 

Isso nos mostra quão eficiente a ferramenta pode ser para realizar analises em grande escala. Sua aplicabilidade agrega e muito na análise de opiniões de clientes, como a citada neste exemplo, trazendo resultados muito realistas às empresas que estão em busca de uma ferramenta onde possam realizar análises em escala muito maior e obter insights sobre seus produtos e serviços, e aplicar melhorias com o auxilio dos resultados que a ferramenta consegue obter.

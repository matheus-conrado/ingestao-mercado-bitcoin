# Ingestão de dados MercadoBitcoin

## Introdução

Este projeto tem como finalidade coletar os dados da API do [Mercado Bitcoin](https://www.mercadobitcoin.com.br/). **Este projeto ainda nao foi finalizado, onde ainda é necessario incluir as integrações com a AWS.**

## Desenho da Arquitetura 
![Ingestao-Mercado-Bitcoin](https://github.com/matheus-conrado/ingestao-mercado-bitcoin/blob/master/ingestao-mercado-bitcoin.jpg?raw=true)

## Tecnologias Utilizadas

Para este projeto foram utilizados as seguintes tecnologias:
- Python
- AWS:
 - Lambda
 - S3

## Fonte dos dados

Os dados foram coletados da [API do Mercado Bitcoin](https://www.mercadobitcoin.com.br/api-doc/) e para este projeto utilizamos os métodos [``/trades/``](https://www.mercadobitcoin.com.br/api-doc/#method_trade_api_trades) e [``/day-summary/``](https://www.mercadobitcoin.com.br/api-doc/#method_trade_api_daysummary) a fim de coletar os dados fornecidos.

## Considerações

Com este projeto agora temos informações precisas para decisões estratégicas. Este projeto continua em aperfeiçoamento, para se adaptar às mudanças estruturais e incorporar novos dados. Com este projeto conseguimos entender um pouco mais sobre a arquitetura de scripts escalaveis.

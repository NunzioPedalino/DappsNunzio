# DappsNunzio

## Requisiti

***
Installare plugin Metamask per Firefox/Chrome

Creare una cartella

*mkdir DappsNunzio*

*cd DappsNunzio*


Installare Angular Cli

*npm install -g @angular/cli*


Installare Truffle framework

*npm install -g truffle*


Scaricare Ganache come client Ethereum

https://www.trufflesuite.com/ganache


## Avvio

Avviare Ganache e impostarlo in modo tale che ascolti sulla porta *8545*

Compilare Solidity Contract

*truffle compile*

Deployare Solidity Contract nel client Ethereum

*truffle migrate*

Avviare con

*ng serve --open*

e connettersi alla porta localhost:4200
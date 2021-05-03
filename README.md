# DappsNunzio

***
Innanzitutto è stata creata una cartella DappsNunzio

*mkdir DappsNunzio*

*cd DappsNunzio*

al suo interno è stato installato Angular Cli

*npm install -g @angular/cli*

e poi è stato installato Truffle framework

*npm install -g truffle*

come client Ethereum è stato utilizzato ganache

https://www.trufflesuite.com/ganache


Innanzitutto avviare ganache e impostarlo in modo tale che ascolti sulla porta 8545

per compilare gli smart contract

*truffle compile*

per deployare gli smart contract nel client ethereum

*truffle migrate*

Avviare con

*ng serve --open*

e connettersi alla porta localhost:4200
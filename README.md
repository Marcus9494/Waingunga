# Waingunga
Il classico gioco dell'oca realizzato come pagina Web usando HTML5, CSS3 e Javascript vanilla.

Il gioco è stato realizzato per l'associazione [Lupetti FSE](https://scout.fse.it/lupetti/)

## Giocare
Per giocare basta visitare https://marco97pa.github.io/worldadventure/

Per accedere alle istruzioni di gioco e alla documentazione è possibile visitare questo 

## Sviluppo
Visti i tempi ristretti e la necessità di avere un prodotto funzionante su ogni computer, ho optato per la combinazione HTML5, CSS3 e Javascript vanilla.

Il file [index.html](https://github.com/marco97pa/worldadventure/blob/master/index.html) si occupa di indirizzare gli utenti verso la versione del gioco più adatta a loro, è responsive e si adatta anche su mobile.
Contiene inoltre i link alla documentazione e alle istruzioni specifiche per ogni branca.

Il file [main.html](https://github.com/marco97pa/worldadventure/blob/master/main.html) è la vera e propria piattaforma di gioco, **comune a ogni branca**.

Il gioco supporta massimo **12 giocatori** e **52 caselle** (comprese inizio e fine).

Il gioco funziona **solo su desktop**, non è responsive.
Sono supportati tutti i browser correnti ad eccezione di Internet Explorer.

Diverse parti dell'interfaccia sono state realizzate sfruttando i `<dialog>` di HTML5: su browser che non li supportano (Firefox e Safari) vengono renderizzati sfruttando i classici `alert()` di Javascript.

Ai fini della pubblicazione online è stato sfruttato **GitHub Pages**.

## Segnalare problemi
E' possibile segnalare eventuali problemi nella sezione Issues di Gihub oppure inviandomi una mail a 

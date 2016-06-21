# Linee guida visive siti web della Pubblica Amministrazione

[![Join the chat at https://gitter.im/italia-it/designer.italia.it](https://badges.gitter.im/italia-it/designer.italia.it.svg)](https://gitter.im/italia-it/designer.italia.it?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Stato del progetto
Attualmente il progetto redazionale delle Linee Guida è nella fase "alfa". I suggerimenti
e le proposte della community contribuiranno a raggiungere una versione più stabile e di riferimento.

## Adottare lo stile delle Linee Guida
Una volta recepiti i contribuiti dagli utenti, i CSS (o [Sass](http://sass-lang.com)) allegati alle linee guida
potranno essere utilizzati nella progettazione dei nuovi siti web della pubblica amministrazione.
Al momento è prevista l'implementazione come tema del framework CSS [Bootstrap](http://getbootstrap.com/).

È possibile scaricare la [versione corrente del CSS](https://github.com/italia-it/ita-bootstrap) e visualizzare gli [esempi dei componenti HTML](http://italia-it.github.io/ita-bootstrap/) illustrati nelle linee guida. Durante la fase alfa tali stili sono soggetti a cambiamenti.
Per contribuire fare riferimento alle [istruzioni per l'utilizzo e la compilazione dei sorgenti Sass](https://github.com/italia-it/ita-bootstrap/blob/master/README.md).

## Contribuire al progetto
Per inviare i commenti è necessario avere un account su [GitHub](https://github.com/), o [creare un account nuovo](https://github.com/join).

- [Accedere al repository del progetto delle linee guida](https://github.com/italia-it/designer.italia.it).
- [Inviare commenti/richieste o segnalare errori](https://github.com/italia-it/designer.italia.it/issues)
- Per proporre una modifica direttamente al codice e/o ai testi
  1. [effettuare una copia del repository (fork)](https://help.github.com/articles/fork-a-repo/)
  2. [sottoporre la modifica effettuata (pull request)](https://help.github.com/articles/using-pull-requests/).

Le richieste saranno esaminate dai *maintainer* del progetto che provvederanno a incorporare le proposte più valide.

## Visualizzare in locale il sito delle linee guida
È possibile visualizzare il sito delle linee guida su un webserver installato localmente.
Per farlo è necessario
- installare [Node.js](https://nodejs.org/)
- clonare il [repository Git](https://github.com/italia-it/designer.italia.it.git)
- installare i moduli richiesti

```
npm install
npm install -g bower
npm install -g gulp
bower install
```

- avviare il server di sviluppo tramite [Gulp](http://gulpjs.com/)

```
gulp serve
```

Utilizzando la configurazione di default il sito sarà accessibile all'indirizzo

```
 http://localhost:3000
```

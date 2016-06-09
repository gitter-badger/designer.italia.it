---
template: post.html
title: Uso di mappe nei siti della PA
published: true
---

È sempre più diffusa la necessità di produrre contesto geografico nella presentazione dei dati, anche solo nelle pagine di 'anagrafica' degli uffici.
Le mappe sono rappresentazioni del territorio e, i loro contenuti, potrebbero non essere neutrali, inoltre è importante
valorizzare anche il lavoro dei sistemi informativi territoriali delle varie PA a partire da quelle nazionali.

Questa sezione ha lo scopo di sensibilizzare sulla scelta della mappa da utilizzare come sfondo.

Sulle questioni relative alla neutralità dell'informazione geografica si rimanda a questo articolo
http://blog.spaziogis.it/2014/01/10/perche-abbiamo-bisogno-di-openstreetmap/

## La scelta della mappa di background

I moderni browser, grazie al miglioramento sempre crescente degli interpreti javascript e delle librerie che permettono la visualizzazione di geodati online,
sono in grado di gestire con una buona facilità elenchi di punti (o linee o geometrie) da rappresentare.
Questo implica pertanto che, il dato che si vuole mostrare (es. i luoghi degli uffici pubblici), sia facilmente rappresentabile in "overlay" su una mappa.
Le scelte tecniche spesso ricadono su strumenti come Google Maps senza porsi alcuna questione invece sul vero significato del riuso di queste mappe.
La proposta di queste linee guida è quella di selezionare mappe, prima di tutto, generate dai dati raccolti da una pubblica amministrazione. È indubbio che la toponomastica è stabilita dai Comuni e non da i produttori di mappe online.
Di contro però, non tutte le pubbliche amministrazioni sono in grado di ridistribuire i propri dati secondo questi sistemi informativi.
Si propone pertanto di seguire il seguente schema nella scelta della cartografia di sfondo:

1. fare uso di cartografia prodotta dalla PA di riferimento
qualora l'ente ne distribuisca una sua si consiglia vivamente di fare uso della propria mappa in background,
meglio se questa aggiornata anche tempestivamente con l'aggiornamento dei dati raccolti.
2. fare uso di cartografia prodotta da un ente centrale
tutte le regioni e province autonome dispongono di servizi SIT che offrono servizi di distribuzione della cartografia di base (carta tecnica o ortofotocarta) basati su protocolli standard (si veda la specifica INSPIRE).
Lo stesso portale cartografico nazionale offre diverse sorgenti in tal senso.
È importante che questa cartografia sia disponibile con licenze aperte al fine di evitare possibile confusione da parte dell'utente finale.
3. fare uso di OpenStreetMap
Il progetto OpenStreetMap offre una banca dati di dati georiferiti a cui chiunque può contribuire.
I dati raccolti, oltre ad essere messi a disposizione di tutti, sono da subito trasformati in mappe online attraverso diversi stili di rappresentazione.
Queste mappe spesso hanno al loro interno una ricchezza di dettagli superiori, garantiscono neutralità dei contenuti e possono essere facilmente aggiornate.

## Note tecniche su come le mappe devono essere distribuite

### Protocolli e sistemi di riferimento

Uso di TMS o WMS
Uso di WGS84 (EPSG:4326) o Google Mercator (EPSG:3857)

## Sorgenti disponibili

### Risorse nazionali

elencare anche l'uso foto aeree georiferite (ortofotocarta)

- come si usano
- esempi

### Risorse regionali o comunali

elencare anche l'uso foto aeree georiferite (ortofotocarta)

- come si usano
- esempi

### Openstreetmap

- come si usa
- esempi
- vari rendering disponibili

### Librerie javascript disponibili

Leaflet
OpenLayers

### Ordnance Survey

esempio del governo inglese:
https://www.ordnancesurvey.co.uk/business-and-government/products/opendata-products-grid.html

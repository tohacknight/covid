# Covid-19

In questo documento sono raccolti link che possono risultare utili: dove trovare i dati e riferimenti a dashboard già esistenti e infine ci sono idee su cosa fare.

Qua sotto trovi il link della chat e un paragrafo sulle modalità di lavoro da leggere.

## Chat per la serata

https://riot.im/app/#/room/!ZwMuALfJRUrfeXchci:matrix.org?via=matrix.org

## Modalità di lavoro

Torino Hacknight nasce per contribuire attivamente a progetti Open Source: lo spirito è quindi quello di fare qualcosa di utile :) Di solito, visto il poco tempo a disposizione, contribuire a progetti già esistenti ha più impatto che costruire qualcosa da zero.

In fondo alla pagina trovi una lista di possibili cose da fare ma non sentirti obbligato a doverne fare una di queste. Se vuoi aggiungerne qualcosa fai una Pull Request a questo repository.

Per evitare di duplicare il lavoro crea una issue in questo repository con quello che stai facendo: le risorse sono poche meglio non sprecarle!

All'inizio della serata faremo una call introduttiva alla serata e a questo repository, per comodità però lo strumento principale di comunicazione sarà la chat su matrix.

## Risorse

### Dati

- Collezione di dati definitiva https://docs.google.com/spreadsheets/d/1v99oT7y-PV9Sy7myZ2_XFmohiOuvAAtN11Onp7ZhTq0/edit
- Raccolta scrapers regionali https://github.com/opencovid-mr/scrapers
- Scraper dati su base comunale piemonte https://github.com/to-mg/covid-19-piemonte
- Dati in json su decessi su base provinciale https://github.com/tohacknight/covid2json
- Dati machine readable della Protezione Civile https://github.com/pcm-dpc/COVID-19
- API che esporta i dati della Protezione Civile ed altro https://covid19-it-api.herokuapp.com/doc/
- Aggiornamenti della regione Piemonte https://www.regione.piemonte.it/web/pinforma/notizie/coronavirus-gli-aggiornamenti-dalla-regione-piemonte
- ~~Scraper per avere i deceduti per provincia dalla pagina di aggiornamento della regione https://github.com/xrmx/piemontescrapecoronavirus~~
- ~~Dati e Dashboard su base regionale https://github.com/lucab/covid19-ita-regional~~
- Collezione di fonti di dati regionali https://www.infodata.ilsole24ore.com/2020/03/22/dati-coronavirus-regione-va-conto-suo-aiutateci-mappare-condivide-cosa-aggiornato/
- Challenge su Kaggle https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge/tasks

### Dashboard

- Dashboard che riusa i dati della Protezione Civile https://github.com/alessiodl/COVID19Dashboard
- Un'altra dashboard minimale a partire dai dati della Protezione Civile https://observablehq.com/@matjack1/covid-19-in-italia
- Modelli di traiettorie per il contagio e per il consumo di posti letto ospedalieri https://github.com/neherlab/covid19_scenarios
- Dashboard su andamenti mondiali, interessante perchè usa i casi su milione di abitanti al posto del numero assoluto https://covid19-dash.github.io/
- Dashboard del Financial Times https://www.ft.com/coronavirus-latest
- Dashboard di FBK per lo stato in Trentino (loro hanno i dati per comune) https://covid19trentino.fbk.eu/

### Varie ed eventuali

- Report servizio regionale epidemiologico Piemonte https://www.seremi.it/sites/default/files/2020%2004%2020%20Report%20COVID19%20Piemonte.pdf
- Web app open source per condividere informazioni sul coronavirus https://www.covid19italia.help/
- Collezione di link di progetti Open Source a tema Covid http://open-source-covid-19.weileizeng.com/
- Report sulla mobilità in Italia durante il Lockdown https://covid19mm.github.io/in-progress/2020/03/13/first-report-assessment.html
- Lista di hackathons in giro per il mondo https://www.bigdive.eu/covid19-hackathons/

## Idee per la serata

### Contribuire a progetti esistenti

- automazione scraping dati regione piemonte https://github.com/to-mg/covid-19-piemonte/issues/2
- Completare traduzione italiana jitsi https://github.com/jitsi/jitsi-meet/blob/master/lang/main-it.json
- Estendere covid2json per prendere altri dati https://github.com/tohacknight/covid2json
- Provare a sistemare qualche issue qua https://github.com/emergenzeHack/covid19italia
- Provare a sistemare qualche issue qua https://github.com/neherlab/covid19_scenarios/issues
- Traduzione italiana del'interfaccia di https://github.com/neherlab/covid19_scenarios
- ~~Migliorare interfaccia dashboard, ad esempio contrasto etichette grafico in basso a destra https://alessiodl.github.io/COVID19Dashboard/dist/index.html~~
- ~~Scrivere i test per lo scraper https://github.com/xrmx/piemontescrapecoronavirus/issues/1~~
- ~~Creare azione di github per fare lo scraping https://github.com/xrmx/piemontescrapecoronavirus/issues/4~~

### Fare una dashboard specifica per il Piemonte (riciclabile anche dalle altri regioni)

Le dashboard nazionali tendono ad avere meno strumenti di visualizzazione sui dati in base regionale o provinciale.

- Fare una dashboard usando i dati della Protezione civile e una volta disponibili quelli del punto sopra

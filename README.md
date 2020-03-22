# Covid

In questo documento sono raccolti link che possono risultare utili: ci sono risorse ed alcune idee su cosa fare. 

## Chat per la serata

<chat su riot>

## Risorse

- Dati machine readable della Protezione Civile https://github.com/pcm-dpc/COVID-19
- Aggiornamenti della regione Piemonte https://www.regione.piemonte.it/web/pinforma/notizie/coronavirus-gli-aggiornamenti-dalla-regione-piemonte
- Dashboard che riusa i dati della Protenzione Civile https://github.com/alessiodl/COVID19Dashboard
- Dashboard di FBK per lo stato in Trentino (loro hanno i dati per comune) https://covid19trentino.fbk.eu/
- Modelli di traiettorie per il contagio e per il consumo di posti letto ospedalieri https://github.com/neherlab/covid19_scenarios
- Collezione di link di progetti Open Source a tema Covid http://open-source-covid-19.weileizeng.com/

## Idee per la serata

### Contribuire a progetti esistenti

- Migliorare interfaccia dashboard, ad esempio contrasto etichette grafico in basso a destra https://alessiodl.github.io/COVID19Dashboard/dist/index.html
- Provare a sistemare qualche issue qua https://github.com/neherlab/covid19_scenarios
- *Se finiscono il sistema i18n* traduzione italiana del'interfaccia di https://github.com/neherlab/covid19_scenarios 

### Fare una dashboard specifica per il Piemonte (riciclabile anche dalle altri regioni)

Le dashboard nazionali tendono ad avere meno strumenti di visualizzazione sui dati in base regionale o provinciale.

- parsare la pagina di aggiornamento della regione Piemonte ed estrarre il numero dei deceduti su base provinciale e salvarli in un repository
- Fare una dashboard usando i dati della Protezione civile e una volta disponibili quelli del punto sopra

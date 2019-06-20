# Ricerca annunci online

Il progetto ha lo scopo di fornire una soluzione architetturale che consenta di analizzare gli annunci di compravendita tra privati presenti su uno o più siti online. 

La ricerca principalmente potrà essere effettuata tramite i seguenti campi: indirizzi email, numeri di telefono, nominativi e aree di azione.

### Prerequisites

* Python > 3.0

* Talend Open Studio

* MongoDB 3.0

### Ipython Notebook

Nel progetto sono presenti i file .ipynb relativi alla fase di scraping per il sito Subito.it e Kijiji.

I due notebook hanno come output due file .csv contenenti gli annunci trovati e le informazioni relative alle pagine di dettaglio.

### Talend

All'interno della directory Talend sono presenti:

* I file di configurazione relativi ai job Talend utilizzati per la fase di ETL dei dati

* I metadati relativi ai file csv utilizzati

* I metadati relativi alla connessione MongoDB


Il risultato finale si compone di due collection MongoDB contenenti ognuna i dati completi relativi a ciascun annuncio di Subito.it e di Kijiji, ed una collection relativa alle anagrafiche.




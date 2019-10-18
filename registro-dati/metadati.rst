4.1 Metadati
============

Di seguito è presentato l’elenco dei metadati necessari a descrivere
ciascun elemento del Registro Dati (Tabella 1). È prevedibile che questo
elenco possa essere integrato alla luce di esigenze istituzionali o
future indicazioni dell’Agenzia Digitale per l’Italia [1]_, tali
eventuali integrazioni verranno effettuate dall’UGD e verranno
opportunamente comunicate al personale e comunque rese disponibili sul
sito Web del Gruppo Gestione Registro Dati.

*Tabella 1. Metadati che descrivono ciascun elemento inserito nel
Registro Dati*

+-----------------------------------+-----------------------------------+
| Metadato                          | Descrizione del metadato          |
+-----------------------------------+-----------------------------------+
| ID                                | Identificativo del record.        |
+-----------------------------------+-----------------------------------+
| ID Gruppo                         | Identificativo del gruppo di      |
|                                   | elementi.                         |
+-----------------------------------+-----------------------------------+
| Gruppo                            | Nome per esteso del gruppo di     |
|                                   | elementi.                         |
+-----------------------------------+-----------------------------------+
| Acronimo Gruppo                   | Eventuale acronimo associato al   |
|                                   | gruppo.                           |
+-----------------------------------+-----------------------------------+
| Nome                              | Nome per esteso dell’elemento.    |
+-----------------------------------+-----------------------------------+
| Acronimo                          | Eventuale acronimo associato      |
|                                   | all’elemento.                     |
+-----------------------------------+-----------------------------------+
| Tipo di Elemento                  | Tipologia di elemento (es.:       |
|                                   | “Banca dati digitale”, “Dati      |
|                                   | digitali non strutturati in banca |
|                                   | dati”, “Campioni fisici”).        |
+-----------------------------------+-----------------------------------+
| Descrizione                       | Breve descrizione dell’elemento.  |
+-----------------------------------+-----------------------------------+
| Identificativi Persistenti        | Identificativi persistenti        |
|                                   | associati all’elemento.           |
+-----------------------------------+-----------------------------------+
| Classe                            | -  Dati Vulcanologici             |
|                                   |                                   |
|                                   | -  Dati Geochimici (analisi       |
|                                   |    geochimiche di rocce, acque e  |
|                                   |    gas)                           |
|                                   |                                   |
|                                   | -  Dati Geodetici                 |
|                                   |                                   |
|                                   | -  Dati Sismologici e Infrasonici |
|                                   |    (terrestri e marini)           |
|                                   |                                   |
|                                   | -  Dati di campioni fisici        |
|                                   |    (campioni e parametri fisici   |
|                                   |    di rocce, minerali e materiali |
|                                   |    vari)                          |
|                                   |                                   |
|                                   | -  Dati di Geofisica atmosferica  |
|                                   |    e Aeronomia                    |
|                                   |                                   |
|                                   | -  Dati Geologici (terrestri e    |
|                                   |    marini)                        |
|                                   |                                   |
|                                   | -  Dati Geofisici (geomagnetici,  |
|                                   |    geoelettrici, EM, etc.)        |
|                                   |    terrestri e marini             |
|                                   |                                   |
|                                   | -  Dati da Modelli Numerici       |
|                                   |                                   |
|                                   | -  Dati di Telerilevamento        |
+-----------------------------------+-----------------------------------+
| Livello                           | -  Livello 0: dati grezzi *(Level |
|                                   |    0 raw data)* o di base, che    |
|                                   |    non hanno subito alcun livello |
|                                   |    di elaborazione, esclusa, al   |
|                                   |    più, una validazione di tipo   |
|                                   |    automatico (esempi: forme      |
|                                   |    d’onda, dati GPS, immagini non |
|                                   |    calibrate, campioni di         |
|                                   |    roccia).                       |
|                                   |                                   |
|                                   | -  Livello 1: prodotti *(Level 1  |
|                                   |    data products)* ottenuti da    |
|                                   |    procedure automatiche o        |
|                                   |    semi-automatiche (esempi:      |
|                                   |    localizzazione, magnitudo,     |
|                                   |    meccanismi focali dei          |
|                                   |    terremoti, shakemaps, serie    |
|                                   |    storiche dell’ampiezza del     |
|                                   |    tremore vulcanico, dello       |
|                                   |    spostamento di stazioni GPS).  |
|                                   |                                   |
|                                   | -  Livello 2: prodotti *(Level 2  |
|                                   |    data products)* ottenuti       |
|                                   |    dall’attività di ricerca e     |
|                                   |    comunque sulla base di         |
|                                   |    procedure non automatiche      |
|                                   |    (esempi: modelli crostali,     |
|                                   |    mappe di strain, modelli di    |
|                                   |    sorgente dei terremoti o delle |
|                                   |    deformazioni, modelli di       |
|                                   |    simulazione numerica dei       |
|                                   |    processi vulcanici, risultati  |
|                                   |    di campagne geofisiche, misure |
|                                   |    di laboratorio su campioni     |
|                                   |    prelevati per finalità         |
|                                   |    scientifiche).                 |
|                                   |                                   |
|                                   | -  Livello 3: prodotti integrati  |
|                                   |    *(Level 3 integrated data      |
|                                   |    products)* ottenuti da analisi |
|                                   |    complesse che integrano più    |
|                                   |    prodotti di Livello 2 oppure   |
|                                   |    da analisi che integrano       |
|                                   |    prodotti di Livello 1 o 2 di   |
|                                   |    diverse tipologie e/o          |
|                                   |    provenienti da diverse         |
|                                   |    comunità (esempi: mappe di     |
|                                   |    pericolosità, cataloghi di     |
|                                   |    faglie attive, rapporti di     |
|                                   |    attività vulcanica).           |
+-----------------------------------+-----------------------------------+
| Copertura Geografica              | Si può indicare in modo testuale  |
|                                   | (esempi: Mondo; Europa; Italia;   |
|                                   | Etna; provincia di Catania)       |
|                                   | oppure con le coordinate dei      |
|                                   | vertici che rappresentano il      |
|                                   | poligono di copertura geografica  |
|                                   | codificate con lo standard        |
|                                   | WKT [6]_.                         |
+-----------------------------------+-----------------------------------+
| Formati di codifica dei dati      | Possibilmente indicando un        |
|                                   | riferimento allo standard per i   |
|                                   | formati meno diffusi.             |
+-----------------------------------+-----------------------------------+
| Metadati associati                | Se viene adottato un modello di   |
|                                   | metadati per la descrizione della |
|                                   | risorsa nel suo complesso e/o del |
|                                   | suo contenuto indicare quale      |
|                                   | (esempi: Dublin Core, DCAT,       |
|                                   | DataCite, RNDT, INSPIRE).         |
|                                   | Indicare "custom" se si tratta di |
|                                   | metadati codificati secondo uno   |
|                                   | standard interno non largamente   |
|                                   | diffuso.                          |
+-----------------------------------+-----------------------------------+
| Tipologia di dati                 | Dati dinamici o dati statici.     |
+-----------------------------------+-----------------------------------+
| Frequenza di aggiornamento        | Nel caso si tratti di dati        |
|                                   | dinamici, qui si specifica la     |
|                                   | frequenza con cui il contenuto    |
|                                   | viene modificato (es.: registrati |
|                                   | in continuo *“data streaming”*),  |
|                                   | indipendentemente dal motivo che  |
|                                   | porta alla modifica.              |
+-----------------------------------+-----------------------------------+
| Finalità di utilizzo              | Diverse casistiche e contesti di  |
|                                   | utilizzo dei dati (esempi:        |
|                                   | emergenza, comunicazione,         |
|                                   | formazione, usi commerciali).     |
+-----------------------------------+-----------------------------------+
| Responsabile dei Dati             | Dipendente INGV di riferimento    |
|                                   | che cura gli aspetti scientifici  |
|                                   | e amministrativi relativi ai      |
|                                   | dati. Oltre a nome, cognome e     |
|                                   | affiliazione, deve essere         |
|                                   | presente il codice ORCID.         |
+-----------------------------------+-----------------------------------+
| Responsabile Tecnico              | Dipendente INGV di riferimento    |
|                                   | che cura gli aspetti tecnologici  |
|                                   | relativi alla Banca Dati. Oltre a |
|                                   | nome, cognome e affiliazione,     |
|                                   | deve essere presente il codice    |
|                                   | ORCID.                            |
+-----------------------------------+-----------------------------------+
| Produttore dei Dati               | Singolo dipendente o gruppo di    |
|                                   | dipendenti INGV che produce i     |
|                                   | dati. Per ciascun dipendente deve |
|                                   | essere indicato nome, cognome,    |
|                                   | affiliazione, definito il ruolo,  |
|                                   | possibilmente espresso secondo le |
|                                   | specifiche OpenAire [7]_ e        |
|                                   | fornito il codice ORCID.          |
+-----------------------------------+-----------------------------------+
| Organizzazione della banca dati   | Tipologia di organizzazione       |
|                                   | dell’archiviazione dei dati       |
|                                   | (esempi: rete di monitoraggio,    |
|                                   | banca dati, dati grezzi su        |
|                                   | *filesystem* o *cloud*, archivio  |
|                                   | documentale, archivio di campioni |
|                                   | fisici, archivio fotografico).    |
+-----------------------------------+-----------------------------------+
| Sezioni INGV coinvolte            | Elenco delle Sezioni e sedi       |
|                                   | coinvolte nella creazione dei     |
|                                   | dati e nella loro gestione        |
|                                   | (esempi: ONT, RM1, RM2, OV, OE,   |
|                                   | PA, BO, PI, MI).                  |
+-----------------------------------+-----------------------------------+
| URLs                              | Indirizzo/i Web come              |
|                                   | l’\ *homepage* *(Landing page)*,  |
|                                   | o pagine relative ai servizi      |
|                                   | quali la ricerca di dati, la      |
|                                   | visualizzazione, il               |
|                                   | trasferimento, la trasformazione, |
|                                   | la modifica e/o aggiornamento dei |
|                                   | dati.                             |
+-----------------------------------+-----------------------------------+
| Web Service                       | Indicazione di eventuali modalità |
|                                   | di accesso ai dati tramite Web    |
|                                   | service o API *(Application       |
|                                   | Programming Interface)* o altre   |
|                                   | procedure automatizzabili con     |
|                                   | l’indicazione dello standard      |
|                                   | adottato (esempi: RESTful, SOAP,  |
|                                   | CGI). Se disponibile, indicare    |
|                                   | l’indirizzo Web da cui è          |
|                                   | possibile accedere.               |
+-----------------------------------+-----------------------------------+
| Documentazione                    | Link alla documentazione di       |
|                                   | riferimento, sia di natura        |
|                                   | scientifica, sia tecnologica. Se  |
|                                   | disponibile, compilare con il DOI |
|                                   | delle pubblicazioni, altrimenti   |
|                                   | con URL.                          |
+-----------------------------------+-----------------------------------+
| Citazione                         | Citazione bibliografica dei dati. |
+-----------------------------------+-----------------------------------+
| Parole chiave                     | Elenco di parole chiave che       |
|                                   | identificano i dati. Obbligatoria |
|                                   | la compilazione di un elenco in   |
|                                   | lingua inglese, facoltativa       |
|                                   | l’aggiunta di un elenco in lingua |
|                                   | italiana.                         |
+-----------------------------------+-----------------------------------+
| Stato                             | Valori ammessi: “in               |
|                                   | progettazione”, “in sviluppo”,    |
|                                   | “operativo”. Indicare *“legacy”*  |
|                                   | per dati o prodotti non più       |
|                                   | gestiti né aggiornati, ma         |
|                                   | comunque ancora accessibili.      |
+-----------------------------------+-----------------------------------+
| Titolarità                        | La titolarità è dell’INGV, salvo  |
|                                   | nei casi in cui siano coinvolte   |
|                                   | altre istituzioni.                |
+-----------------------------------+-----------------------------------+
| Licenza                           | Tipologia di licenza *Creative    |
|                                   | Commons* associata ai dati e/o    |
|                                   | alla banca dati, poiché           |
|                                   | potrebbero differire (licenza     |
|                                   | associata al contenitore diversa  |
|                                   | dalla licenza associata al/ai     |
|                                   | contenuto/i).                     |
+-----------------------------------+-----------------------------------+
| Accesso ai dati                   | I valori ammessi sono “anonimo”,  |
|                                   | “registrato”, “autorizzato”. Se   |
|                                   | non applicabile, descrivere       |
|                                   | brevemente eventuali termini di   |
|                                   | accesso alternativi.              |
+-----------------------------------+-----------------------------------+
| Classe Open Data                  | Classe secondo la classificazione |
|                                   | "5 stars" [8]_ che definisce la   |
|                                   | tipologia di *Open Data*.         |
+-----------------------------------+-----------------------------------+
| Classe metadati                   | Classe secondo la classificazione |
|                                   | dei metadati proposta             |
|                                   | dall'Agenzia per l'Italia         |
|                                   | Digitale ("Livelli del modello    |
|                                   | per i metadati" da "Linee Guida   |
|                                   | Nazionali per la Valorizzazione   |
|                                   | del Patrimonio Informativo        |
|                                   | Pubblico 2016").                  |
+-----------------------------------+-----------------------------------+
| RNDT                              | Indicazione della rilevanza dei   |
|                                   | dati ai fini del Repertorio       |
|                                   | Nazionale dei Dati Territoriali.  |
+-----------------------------------+-----------------------------------+
| Progetti/ iniziative di           | Progetto/i e/o iniziativa/e di    |
| riferimento                       | riferimento per il dato e/o       |
|                                   | prodotto indicato (esempi:        |
|                                   | Convenzione INGV-DPC, H2020       |
|                                   | –seguito dal nome del progetto-,  |
|                                   | EPOS, EMSO, MED-SUV).             |
+-----------------------------------+-----------------------------------+
| Altre istituzioni coinvolte       | Nel caso in cui altre istituzioni |
|                                   | oltre a INGV abbiano contribuito  |
|                                   | alla creazione dei dati, indicare |
|                                   | quali, specificando per ciascuna  |
|                                   | il livello di contributo (esempi: |
|                                   | trascurabile, marginale,          |
|                                   | sostanziale).                     |
+-----------------------------------+-----------------------------------+
| Collegamenti                      | E’ possibile indicare             |
|                                   | collegamenti e la tipologia di    |
|                                   | relazione secondo le linee guida  |
|                                   | *OpenAire*\  [9]_. E’ possibile   |
|                                   | stabilire collegamenti ad altri   |
|                                   | elementi di Registro oppure a     |
|                                   | elementi esterni al Registro come |
|                                   | ad esempio pubblicazioni, o altre |
|                                   | Banche Dati che rendono           |
|                                   | disponibili gli stessi dati.      |
+-----------------------------------+-----------------------------------+
| Data di creazione dei dati        | Data in cui i Dati sono stati     |
|                                   | creati.                           |
+-----------------------------------+-----------------------------------+
| Data di creazione del record      | Data in cui l’elemento è stato    |
|                                   | inserito nel Registro Dati.       |
+-----------------------------------+-----------------------------------+
| Data di ultimo aggiornamento del  | Data di ultimo aggiornamento      |
| record                            | delle informazioni relative       |
|                                   | all’elemento.                     |
+-----------------------------------+-----------------------------------+
| Note                              | Eventuali note aggiuntive utili   |
|                                   | ai fini del Registro Dati.        |
+-----------------------------------+-----------------------------------+

.. [1]
   Agenzia Digitale per l’Italia. Linee Guida per i cataloghi dati.

.. [2]
   Well-known text, ISO/IEC 13249-3:2016,
   https://en.wikipedia.org/wiki/Well-known_text

.. [3]
   OpenAire. OpenAIRE Guidelines for Data Archives.

.. [4]
   5 stars Open Data. http://5stardata.info

.. [5]
   OpenAire. Guidelines for Data Archives.

.. [6]
   Well-known text, ISO/IEC 13249-3:2016,
   https://en.wikipedia.org/wiki/Well-known_text

.. [7]
   OpenAire. OpenAIRE Guidelines for Data Archives.

.. [8]
   5 stars Open Data. http://5stardata.info

.. [9]
   OpenAire. Guidelines for Data Archives.

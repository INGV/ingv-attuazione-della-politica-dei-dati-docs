**DOCUMENTO DI **

**ATTUAZIONE DELLA POLITICA DEI DATI**

**DELL’INGV**

**A cura del Gruppo di Lavoro sulla Politica dei Dati INGV (PoliDat) **

Giuseppe Puglisi (Coordinatore)

Roberto Basili

Anna Grazia Chiodetti

Antonella Cianchi

Massimiliano Drudi

Carmela Freda

Mario Locati

Maurizio Pignone

Agata Sangianantoni

***Versione 16.1 – 24 luglio 2018***

**INDICE**

Premessa
========

Il documento che delinea i principi della Politica dei Dati dell’INGV è
stato approvato e formalizzato con il Decreto del Presidente n. 200
(DP200) del 26/4/2016.

La definizione di una politica dei dati per l’INGV risponde alla
necessità di governare la molteplicità dei dati di ricerca prodotti,
enunciare i principi ispiratori sui quali impostare una condivisa
gestione istituzionale di tali dati e gestire l’accesso, l’uso, il riuso
degli stessi. La politica dei dati dell’INGV si basa sul principio
fondamentale di “Accesso Aperto”. In tal senso, l’INGV adotta una
politica che consenta un accesso libero, aperto, pieno e tempestivo dei
propri dati di ricerca, rispettando i principi stabiliti nella normativa
comunitaria e nazionale e in accordo con le proprie finalità
istituzionali, struttura e organizzazione.

Sin dalle prime azioni intraprese (DP223 11/06/2015) per arrivare a una
piena attuazione dei principi ispiratori del documento, è stato evidente
che non si poteva parlare di politica dei dati senza avere un’adeguata
conoscenza del patrimonio immateriale dell’INGV rappresentato
dall’enorme mole di dati scientifici prodotti nell’ambito delle sue
attività di ricerca nelle diverse Sezioni. L’INGV ha, quindi,
individuato nel Registro Dati lo strumento chiave per una gestione
efficace ed efficiente dei dati di ricerca dell’INGV. Al fine di
elaborare tale Registro, nel secondo semestre del 2016 si è avviato il
censimento dei dati prodotti da tutte le Sezioni dell’INGV, conclusosi a
luglio 2017.

Questo primo censimento ha rilevato che l’INGV gestisce oltre 250 tipi
di dati di ricerca, diversi per provenienza, livello di elaborazione e
organizzazione. Questa diversità rappresenta uno degli aspetti della
ricchezza culturale dell’INGV, ma, allo stesso tempo, una sfida in
termini di gestione di un tale patrimonio. Ovviamente, la compilazione
del Registro con le informazioni relative a oltre 250 tipi di dati è
un’operazione né semplice, né breve, né tanto meno da effettuarsi in
un’unica soluzione, ma richiede un’adeguata programmazione che permetta
di procedere valutando eventuali incompletezze nelle informazioni o
difficoltà nelle procedure e di apportare le necessarie correzioni ed
implementazioni.

Il presente documento, in ottemperanza al DP200, fornisce il quadro
delle regole e procedure per la gestione dei dati, al fine di essere di
supporto all’attuazione della suddetta Politica dei Dati dell’INGV.

In particolare, questo documento definisce i termini chiave utili alla
gestione dei dati di ricerca dell’INGV (Capitolo 1), illustra obiettivi
e strategie per l’attuazione della Politica dei Dati dell’INGV e il
piano di attività per l’avvio, l’implementazione e la gestione ordinaria
del Registro Dati (Capitolo 2), definisce le procedure per la gestione
dei dati e il Registro Dati (Capitolo 3 e Capitolo 4, rispettivamente),
definisce le procedure per l’attribuzione dei DOI (*Digital Object
Identifier*) e per la gestione dei dati Territoriali (Capitolo 5) e
infine definisce l’Ufficio Gestione Dati la cui missione è promuovere il
paradigma *Open Science* e gestire il Registro Dati (Capitolo
5).\ |https://ssl.gstatic.com/ui/v1/icons/mail/images/cleardot.gif|

1. Definizioni
==============

Ai fini dell’applicazione della Politica dei Dati, si applicano le
seguenti definizioni, in ordine alfabetico:

**Accesso:** l’autorizzazione o diritto di un utente ad accedere ai dati
tramite un’infrastruttura associata a una banca dati. L’accesso può
essere distinto in relazioni alle modalità di identificazione e
registrazione dell’utente in:

    • Anonimo: in questo caso l’accesso al/ai servizi avviene senza
    alcuna identificazione o procedura di accredito;

    • Registrato: in questo caso l’accesso al/ai servizi richiede una
    identificazione mediante delle procedure di accredito che possono
    essere automatizzate;

    • Autorizzato: in questo caso l’accesso al/ai servizi richiede una
    specifica autorizzazione da parte del gestore della banca dati.

A seconda della complessità, l’infrastruttura di accesso ai dati può
svolgere una o più funzioni codificate con la sigla “AAAI”:
identificazione dell'utente *(Authentication)*, autorizzazione all’uso
dei servizi *(Authorisation)*, e tracciamento dell’utilizzo dei servizi
*(Accounting)*. Tale infrastruttura deve garantire il rispetto della
normativa per la protezione dei dati  [1]_.

**Banca Dati *(Collection of data)*:** raccolta di dati *(o “Set di
dati”)* indipendenti sistematicamente o metodicamente disposti e
individualmente accessibili mediante mezzi elettronici o in altro modo.
La tutela delle banche di dati non si estende al loro contenuto e lascia
impregiudicati diritti esistenti su tale contenuto [2]_\ :sup:`,`
 [3]_\ :sup:`,`  [4]_. Dalla definizione è esclusa l’infrastruttura
informatica che gestisce la banca data, ivi compresi eventuali Servizi
per l’interazione con i dati.

**Dati** (qui intesi nell’accezione di dati di ricerca [5]_): singoli
oggetti o registrazioni di qualunque natura (fisica o digitale), a
qualunque livello di elaborazione e comunque organizzati oltre ai
prodotti della ricerca ancorché non pubblicati, comunemente ritenuti e
accettati dalla comunità scientifica come necessari a validare le
scoperte scientifiche. In questa sede il termine “dato” si riferisce
indifferentemente al dato grezzo acquisito dal sensore, al campione
fisico di qualunque natura, ad un prodotto ottenuto da una qualunque
analisi sul dato a qualunque livello di elaborazione sia essa di tipo
automatico o manuale. Di seguito si riportano le definizioni di
tipologie di dati citati nel documento:

-  dati statici: non vengono più aggiornati una volta generati e/o
       pubblicati;

-  dati dinamici: possono essere modificati o estesi successivamente
       alla loro pubblicazione; possono essere ulteriormente suddivisi
       in base al tipo di variazione:

-  dati oggetto di revisione: modificabili al fine di migliorarne la
   qualità/affidabilità;

-  dati prodotti in continuo: prodotti da sensori che generano una serie
   temporale;

-  dati di monitoraggio: dati provenienti da sistemi osservativi
       istituzionali, acquisiti o prodotti con ricorrenza e
       sistematicità per la caratterizzazione e la comprensione dei
       processi fisici e/o chimici del sistema Terra;

-  dati di sorveglianza: dati elaborati per scopi di gestione dei rischi
       naturali, di protezione civile o di pubblica utilità forniti a
       enti e/o istituzioni pubbliche o private, nazionali e/o
       internazionali, a seguito di accordi formali;

-  dati territoriali [6]_: qualunque informazione geograficamente
       localizzata;

-  dati aperti: cioè “usabili, riutilizzabili e ridistribuibili
       liberamente da chiunque anche per finalità commerciali, soggetti
       al massimo alla richiesta di attribuzione e condivisione allo
       stesso modo” [7]_.

**Embargo:** periodo di tempo durante il quale è sospeso uno o più
Servizi di accesso ai Dati. Il periodo di embargo può variare da sei
mesi a un massimo di tre anni, in relazione della tipologia di dato. Nel
caso di dati ottenuti in ambito di iniziative nazionali o internazionali
a cui l’Istituto partecipa ufficialmente e che prevedono regole di
embargo diverse, l’Istituto adotta tali regole. L’embargo si applica
solo quando opportunamente motivato. I metadati relativi ai Dati
sottoposti a embargo sono comunque pubblicamente disponibili per
permetterne la ricerca *(Discoverability)*.

**Identificativo Persistente:** codice alfanumerico la cui struttura è
definita all’interno di sistemi di gestione degli oggetti (dati, libri,
persone, campioni fisici, etc.), alcuni dei quali seguono standard
aperti e condivisi a livello internazionale *(Open Standard)*.
L’aggettivo “Persistente” si riferisce alla caratteristica di garantire
che l’associazione tra il codice identificativo e la posizione sul Web
dell’oggetto associato sia mantenuta nel lungo periodo. Ciò implica che
il sistema di gestione dell’identificativo e l’accesso ai dati sia
mantenuto funzionante nel tempo.

**Istituto Nazionale di Geofisica e Vulcanologia** (di seguito
denominato INGV): ente pubblico di ricerca produttore e titolare dei
dati di ricerca oggetto della Politica dei Dati dell’INGV e di questo
documento di attuazione della suddetta politica.

**Licenza di Uso:** strumento negoziale nel quale sono definite in
dettaglio le regole e le condizioni da rispettare per utilizzare il
dato. La definizione del contenuto contrattuale è lasciata all'autonomia
delle parti contraenti, le quali possono definire i reciproci diritti e
doveri a loro discrezione. Tutti i dati pubblicati da INGV devono essere
accompagnati da una licenza di tipo *Creative Commons*\  [8]_, di cui va
sempre specificata, la tipologia e la versione e fornito il riferimento
al testo integrale della licenza. Ai dati classificati come “aperti” non
si possono apporre licenze *Creative Commons* che non consentano lavori
derivati, anche per finalità commerciali, i.e., licenze che riportano
chiaramente clausole *Non Commercial* (“NC”) e/o *Non Derivative* (“ND”)
e/o ogni altra clausola che limita la possibilità di riutilizzo e
ridistribuzione dei dati.

**Produttore di Dati**: stante che giuridicamente il Produttore dei Dati
è l’INGV, in questo specifico documento, applicando il principio
dell’immedesimazione organica, quando ci si riferisce a “Produttore dei
Dati” si intende il singolo addetto alla ricerca o gruppo di ricerca che
produce il dato con la propria attività lavorativa, con le risorse
interne (fondi ordinari) e esterne (fondi provenienti da progetti,
convenzioni, etc.) fornite dall’INGV, incluso il costo del personale.

**Registro Dati:** raccoglie i metadati che descrivono i Dati di Ricerca
che siano il frutto della produzione scientifica dell'INGV e/o gestiti
e/o pubblicati da INGV, indipendentemente se si tratti di dati statici o
dinamici e a prescindere dalle procedure seguite per la loro creazione.
Il Registro Dati è pubblicamente accessibile tramite il portale Web
istituzionale dell’INGV e il suo utilizzo mira a soddisfare le esigenze
interne all’INGV, ma anche le esigenze di utenti esterni.

**Responsabile dei Dati:** è responsabile scientifico e curatore dei
dati in rappresentanza del Produttore dei Dati; risponde della qualità
scientifica e dell’aggiornamento dei dati e svolge un ruolo di
coordinamento del gruppo di ricerca che produce il dato. Nel caso di
dati statici, il Responsabile dei Dati risponde della loro integrità.

**Responsabile Tecnico della Banca Dati:** responsabile della gestione e
funzionalità della Banca Dati, ha le adeguate conoscenze informatiche
per gestire l’infrastruttura tecnologica che sostiene la Banca Dati,
svolge un ruolo operativo sul sistema gestionale afferente al dato.
Inoltre, fornisce indicazioni circa il reperimento concreto dei dati
dalla base dati e cura il monitoraggio dei vari “connettori” (es.:
pagine web, servizi web) che interfacciano in modo sicuro e
standardizzato gli utenti esterni al contenuto della banca dati. Può
coincidere con il Responsabile dei Dati.

**Servizi:** una qualunque delle seguenti operazioni applicabili ad una
banca dati: ricerca di dati, visualizzazione, trasferimento,
trasformazione, modifica e/o aggiornamento. Il singolo servizio
disponibile per una banca dati, può essere:

-  Aperto: il servizio è liberamente disponibile e accessibile a
       chiunque, senza restrizioni;

-  Limitato: il servizio è disponibile, ma solo alle condizioni
       stabilite o concordate dal/col titolare del diritto di
       sfruttamento della proprietà intellettuale; un particolare caso è
       quello dei dati per i quali non è possibile accedere ad un certo
       tipo di servizio (tipicamente il trasferimento), per un periodo
       di tempo predefinito.

**Titolare dei Dati:** secondo la normativa vigente [9]_, il titolare
del dato è la Pubblica Amministrazione che ha originariamente formato
per uso proprio o commissionato ad altro soggetto il documento che
rappresenta il dato o che ne ha la disponibilità. L’INGV è dunque
titolare dei dati indipendentemente dal loro Livello, se creati con
proprie risorse umane e/o strumentali o comunque gestiti ovvero se
commissionati per fini istituzionali. In caso di situazioni complesse in
cui siano coinvolte altre istituzioni oltre a INGV, è necessaria la
stipula di un accordo che definisca chiaramente gli aspetti relativi
alla titolarità dei dati (es. accordi per le attività in convenzione con
il Dipartimento di Protezione Civile [10]_). Il trasferimento di un dato
da un sistema informativo a un altro non modifica la titolarità del
dato [11]_.

**Ufficio Gestione Dati (UGD):** agisce con la finalità di promuovere il
paradigma dell’\ *Open Science*, gestendo il Registro Dati, garantendo
la progressiva apertura dei dati di ricerca e il miglioramento della
loro gestione in conformità alla normativa vigente. L’Ufficio collabora
e supporta il Responsabile della Trasparenza [12]_.

2. Contesto Operativo
=====================

2.1 Obiettivi
-------------

In conformità con quanto definito nel DP200, la politica dei dati
dell’INGV ha lo scopo di:

-  organizzare e rendere accessibile il patrimonio immateriale
       dell’INGV, per contribuire alla crescita della conoscenza
       rispettando i principi dell’Accesso Aperto *(Open Access)* come
       base del paradigma dell’\ *Open Science*; contribuire al
       raggiungimento del paradigma dell’\ *Open Science* permetterà
       all’INGV non solo di rispettare i suoi obblighi statutari ma
       anche di raggiungere la piena valorizzazione del suo ruolo in
       ambito nazionale ed internazionale;

-  valorizzare il ruolo dell’INGV nell’ambito della ricerca nazionale e
       internazionale e del sistema di monitoraggio e sorveglianza
       nell’ambito dei compiti statutari;

-  valorizzare le competenze del personale dell’INGV addetto alla
       ricerca.

L’obiettivo di questo specifico documento è di fornire un quadro delle
regole e descrivere gli strumenti per la gestione dei dati al fine di
supportare l’attuazione della Politica dei Dati dell’INGV definita nel
DP200 e quindi al raggiungimento dei suoi obiettivi.

2.2 Strategia
-------------

La strategia di attuazione della politica dei dati dell’INGV descritta
in questo documento si basa sulla realizzazione del Registro dei Dati,
come strumento tecnico-organizzativo e sull’istituzione dell’Ufficio
Gestione Dati, con compiti strategici e tecnico-gestionali.

Il *Registro Dati*, secondo la sua definizione, raccoglie i metadati che
descrivono i Dati di ricerca che siano il frutto della produzione
scientifica e tecnologica dell'INGV e/o gestiti e/o pubblicati da INGV,
indipendentemente se si tratti di dati statici o dinamici e a
prescindere dalle procedure seguite per la loro creazione. La
realizzazione del Registro Dati non solo doterà l’INGV di un sistema per
l’identificazione istituzionale della propria produzione di dati
scientifici, ma permetterà anche di certificare la provenienza dei dati
immessi nel sistema della ricerca o, più in generale, nel mondo della
conoscenza condivisa attraverso le moderne tecnologie dell’informazione.
L'intero ciclo della ricerca scientifica si avvantaggerà della presenza
di un Registro Dati. Per esempio, si potrà migliorare la valutazione
della metrica concernente l’impatto dei risultati della ricerca, si
semplificherà la verificabilità di tesi di laurea e/o dottorato basate
su dati non originali (pubblicati in articoli scientifici), sarà
possibile citare in modo preciso ed aggiornato tutti i dati utilizzati,
valorizzando allo stesso tempo sia il lavoro di chi usa il dato sia
quello di chi lo produce. In fase di prima attuazione, la struttura del
Registro Dati dovrebbe ricalcare quella del Censimento dei Dati citato
in Premessa. Si prevede che tale struttura possa essere modificata in
funzione di come evolveranno le banche dati dell’INGV e la normativa,
ciò, sempre e comunque, al fine di ottimizzare il flusso d’informazioni
tra il Gruppo Gestione Registro Dati e i gestori dei dati.

\ *L’Ufficio Gestione Dati (UGD)* viene istituito per rispondere al
principio “Professionalità” del documento “Principi della Politica dei
dati dell’INGV” che sancisce l’impegno dell’INGV all’allocazione delle
risorse professionali necessarie all’attuazione della Politica dei
Dati\ *.* L’UGD, secondo la sua definizione, agendo con la finalità di
promuovere il paradigma *Open Science*, gestisce il Registro Dati sia
nella fase di “Avvio e Sperimentazione” sia nella fase di “Gestione
Ordinaria” (vedi successivo paragrafo 2.3).

Per le finalità della suddetta strategia è importante che l’istituzione
e successiva implementazione del Registro Dati siano il risultato di
azioni condivise tra le varie componenti dell’INGV rappresentate da
organi dirigenziali, organi di gestione (incluso l’Ufficio Gestione
Dati) e personale. Infatti, tutte queste componenti devono concorrere
verso l’obiettivo comune di riconoscere al contempo l’attività e
l’autorevolezza scientifica di chi produce i dati e i doveri e
responsabilità istituzionali verso la comunità scientifica e tutti i
potenziali utenti.

2.3 Piano di Attività
---------------------

La delicata fase di avvio e sperimentazione del Registro Dati nonché la
successiva gestione ordinaria sono affidate all’Ufficio Registro Dati.

2.3.1 Avvio e Sperimentazione
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Questa prima fase ha il duplice scopo di avviare il popolamento del
Registro Dati con gli elementi riportati nel Censimento secondo una
prioritizzazione di migrazione di seguito descritta e di testare e
validare le regole e procedure definite nel successivo Capitolo 3,
suggerendo eventuali correttivi. La programmazione dettagliata delle
attività di popolamento del Registro, la validazione delle procedure e
l’adozione di eventuali correttivi previste nella fase di Avvio e
Sperimentazione sono riportate nell’Allegato 1.

In considerazione dell’elevato numero di elementi censiti (oltre 250),
nella fase di avvio si procederà al popolamento del Registro seguendo
una scala di priorità che tenga conto della maturità degli elementi da
inserire e delle esigenze istituzionali.

Al fine di poter essere trasferito nel Registro, ogni dato dichiarato
nel Censimento deve essere associato a una tipologia di Servizio e
quindi indicare le relative regole di accesso. I\ **n mancanza di queste
informazioni il dato non può essere trasferito dal Censimento al
Registro.** Di conseguenza, il primo livello di prioritizzazione si
effettua sulla base della tipologia di servizi dichiarati e relative
regole di accesso e sulle caratteristiche che rendono un dato più o meno
facilmente accessibile come ad esempio la presenza di DOI e/o di
*Landing Page* operative. La definizione del tipo di servizio e relative
regole di accesso spettano al titolare del dato, ed attuate dal
Responsabile dei Dati.

Il secondo livello di prioritizzazione si basa sulla considerazione
degli obiettivi strategici ed operativi dell’INGV ed è quindi di
competenza dei Direttori di Dipartimento. Per stabilire la priorità
istituzionale del dato ci si potrà basare sulle caratteristiche del dato
in oggetto e sul suo eventuale impatto sugli aspetti strategici
dell’INGV, cioè sul contributo del dato al raggiungimento degli
obiettivi istituzionali stabiliti nel Piano Triennale di Attività. Per
stabilire la priorità istituzionale di un dato si può ad esempio
considerare se questo debba essere fornito a enti finanziatori esterni
sulla base di specifici accordi oppure stimare il valore economico
legato alla sua produzione, inteso come peso del contributo dell’INGV.
Questo valore può essere valutato in termini di risorse economiche
proprie (da FOE o da progetti istituzionali), di risorse di personale, o
di risorse strumentali per la sua produzione e preservazione nel lungo
termine (sostenibilità).

In sintesi, ai fini della prioritizzazione per la migrazione dal
Censimento al Registro, l’UGD prenderà in considerazione le seguenti
caratteristiche del dato censito:

-  tipologia di servizio associato al dato con le relative regole di
       accesso;

-  esistenza di un DOI, o altro identificatore permanente associato,
       oppure di una *Landing Page* operativa (anche in assenza di DOI)
       associata;

-  è prioritario nell’ambito dell’attività istituzionale.

In questa fase, contemporaneamente all’avvio del popolamento del
Registro, l’UGD sperimenterà le procedure definite al Capitolo 3, al
fine di verificarne la validità. Tale sperimentazione, della durata di
12 mesi, permetterà di evidenziare vantaggi, svantaggi e problematiche
relative alle procedure; al termine della sperimentazione l’UGD redigerà
un rapporto in cui verranno suggerite soluzioni alle criticità alle
procedure e/o alle regole di gestione e, qualora rilevate, i necessari
miglioramenti. Sulla base di questo rapporto, i Direttori di
Dipartimento valuteranno se applicare soluzioni e strategie proposte
dall’UGD, dichiarare quindi conclusa la fase di avvio e sperimentazione
e passare alla successiva fase di gestione ordinaria del Registro. Nel
caso in cui i Direttori di Dipartimento ritengano sia necessario
prolungare la fase di sperimentazione, ne definiranno modalità e durata
di concerto con l’UGD.

2.3.2 Gestione Ordinaria
~~~~~~~~~~~~~~~~~~~~~~~~

Al termine della fase di avvio e sperimentazione, l’UGD aggiornerà le
procedure, ed eventualmente le regole, per la gestione ordinaria del
Registro Dati sulla base del suo rapporto e delle indicazioni dei
Direttori di Dipartimento.

Il nuovo documento contenente regole e/o procedure aggiornate/modificate
sarà quindi sottoposto alla ratifica del Consiglio di Amministrazione
(CdA). Inoltre, l’UGD presenterà ai Direttori di Dipartimento e quindi
al CdA, un documento denominato Regole Interne all’Ufficio di Gestione
Dati che descriva, con un dettaglio che ne permetta l’effettiva
operatività, le procedure per la gestione ordinaria del Registro Dati.
Una volta avuta l’approvazione di tutti gli organi competenti si potrà
avviare la fase di gestione ordinaria del Registro Dati.

In linea di principio, in questa sede, si stabilisce che l’UGD:

-  aggiornerà periodicamente il Registro, con una tempistica concordata
       con il CdA;

-  stilerà, con periodicità annuale, un rapporto che contenga la
       statistica dei dati gestiti, un’analisi sull’efficacia
       dell’applicazione del paradigma dell’\ *Open Science* nelle
       strutture dell’INGV\ *,* l’impatto dell’evoluzione delle norme e
       delle pratiche comunitarie e nazionali sulla gestione dei dati,
       le eventuali criticità emerse nel corso dell’anno e le
       conseguenti azioni da adottare

Inoltre, sulla base dei rapporti annuali forniti dall’UGD, il CdA,
eventualmente sentiti i Direttori di Dipartimento, si esprimerà
sull’eventuale necessità di aggiornare il documento Principi della
Politica dei Dati dell’INGV e/o il documento di Gestione Ordinaria del
Registro dei Dati.

3. Gestione dei Dati 
=====================

Di seguito sono riportate le regole e le procedure adottate dall’INGV
per la gestione dei dati e vengono individuati gli organi istituzionali
che concorrono alla loro gestione.

3.1 Regole di Accesso ai Dati 
------------------------------

Secondo quanto stabilito nel DP200, principio fondamentale per l’INGV è
l’Accesso Aperto all’informazione scientifica, ovvero garantirne
l’accesso senza costi aggiuntivi per l’utente finale, oppure di renderla
disponibile ai costi marginali sostenuti per la riproduzione e
divulgazione [13]_.

Nel rispetto di questo principio valgono le seguenti regole.

Il ***Servizio***, laddove per servizio si intende una qualunque delle
operazioni applicabili ad una banca dati che permetta la ricerca,
visualizzazione, trasferimento, trasformazione, modifica e/o
aggiornamento dei dati, può essere **Aperto** (liberamente disponibile
ed accessibile a chiunque, senza restrizioni) oppure **Limitato**
(disponibile, ma alle condizioni stabilite o concordate dal/col titolare
del diritto di sfruttamento della proprietà intellettuale), in questo
caso la limitazione deve essere definita e motivata. In particolare:

-  il servizio di ricerca dei metadati sarà sempre aperto, ciò allo
       scopo di dare la maggior visibilità possibile ai dati;

-  il servizio di visualizzazione dei dati sarà aperto, laddove le
       infrastrutture informatiche lo rendano possibile;

-  il trasferimento dei dati può subire limitazioni per specifiche
       tipologie di utenti e/o per periodi di tempo definiti;

-  i servizi di analisi e trasformazione dei dati possono essere
       limitati ai soli produttori del dato o a gruppi ristretti di
       utenti adeguatamente definiti;

-  eventuali servizi di modifica e/o aggiornamento dei dati contenuti
       nelle banche dati dovranno essere necessariamente limitati a
       personale autorizzato e protetti con misure di sicurezza adeguate
       al fine di preservarne l’integrità e garantire il totale
       controllo delle modifiche.

Il tipo di accesso al singolo servizio può essere, se necessario,
modificato, previa adeguata e approvata motivazione.

Gli ***Utenti*** sono classificati secondo tre modalità di accesso:
**Anonimo**, **Registrato, Autorizzato**. Nel caso di utenti registrati
e autorizzati, i sistemi di accesso devono svolgere la funzione di
identificazione, autenticazione e autorizzazione all’utilizzo dei
servizi richiesti. In linea generale i dipendenti INGV non dovrebbero
mai avere limitazioni maggiori rispetto agli utenti esterni, ovviamente
nel rispetto di eventuali accordi nel caso in cui siano coinvolti più
istituzioni.

Il mancato rispetto delle regole di accesso da parte degli utenti o di
rispetto delle licenze di utilizzo dei dati, adeguatamente accertato,
sarà contestato agli interessati e, nel caso di autorizzazioni
istituzionali, anche all’ente di appartenenza. L’INGV si riserva di
adottare provvedimenti di limitazione di accesso ai dati nei confronti
di coloro (singoli o enti) che non rispettano le regole di accesso
stabilite nel Registro Dati. Nei casi più gravi, l’INGV si riserva di
adire le vie legali per tutelare la propria proprietà intellettuale o
eventuali danni patrimoniali o di immagine.

Nelle more della realizzazione del portale dati dell’INGV, i siti web
che pubblicano i dati contenuti nel Registro Dati, gestiti dai singoli
produttori o dalle Sezioni, dovranno esplicitare tutte le suddette
informazioni agli utenti. In particolare dovranno essere comunicate agli
utenti:

-  la licenza associata ai dati;

-  le regole di accesso ai dati in una sezione chiamata “Termini di
       utilizzo dei dati”;

-  le “Limitazioni di responsabilità” per informare gli utenti circa il
       livello di attendibilità dei dati così da scaricare eventuali
       responsabilità imputabili all’INGV e agli autori relativamente a
       potenziali danni derivanti da usi impropri dei dati causati da
       terze parti.

3.2 Procedure di Identificazione del Produttore dei Dati 
---------------------------------------------------------

Per quanto attiene al rispetto delle norme che regolamentano la gestione
dei dati della Pubblica Amministrazione e ai fini dell’inserimento dei
dati nel Registro Dati è necessario identificare il Produttore del Dato.
Nel fare ciò è opportuno considerare la tipologia, o classe, del dato.
Per questa prima fase di attuazione della politica dei dati, si adottano
due sole Classi di dati, denominate A e B, in funzione delle
caratteristiche e ruolo del dato in oggetto. In particolare, la Classe A
identifica i dati che hanno uno specifico ruolo rispetto agli impegni
istituzionali e agli obiettivi strategici dell'Ente per come stabiliti
nel PTA. La Classe B identifica tutti gli altri dati. La valutazione
della classe del dato è di competenza dei Direttori di Dipartimento in
quanto soggetti istituzionali con compiti di promozione, programmazione,
coordinamento e verifica, così come indicato nello Statuto
dell’ente [14]_. In particolare ai fini della migrazione dei dati nel
Registro, i dati di Classe A saranno considerati prioritari.

Per quanto concerne l’identificazione del Produttore dei Dati, la
procedura segue quindi percorsi diversi a seconda della classe
attribuita al dato.

Nel caso di dati attribuiti alla Classe A, l’identificazione del
Produttore dei Dati e del suo eventuale Responsabile, seguirà la
procedura "*top-down"* sotto definita.

-  Il/I Direttore/i di Dipartimento definisce il tipo di dato in base
       alla priorità istituzionale e contemporaneamente individua la
       Sezione, o le Sezioni nel caso di più Sezioni coinvolte nella
       produzione del dato, di riferimento.

-  Il/I Direttore/i della/e Sezione/i di riferimento individua il
       personale coinvolto nella raccolta e elaborazione del dato; in
       caso di più unità di personale il/i Direttore/i individua un
       Responsabile.

-  Il/I Direttore/i di Dipartimento/e valida la decisione del/i
       Direttore/i di Sezione/i.

-  Il Responsabile dei Dati avvia la procedura di inserimento dei dati
       nel Registro secondo le modalità indicate dall’Ufficio Gestione
       Dati.

Nel caso di dati attribuiti alla Classe B, l’identificazione del
Produttore dei Dati e del suo eventuale Responsabile, seguirà la
procedura *bottom-up* sotto definita.

-  Il personale coinvolto nella produzione del dato, propone il
       Produttore dei Dati al/i proprio/i Direttore/i di Sezione; in
       caso di più unità di personale, il Produttore dei Dati individua
       autonomamente un Responsabile; nel caso di Produttore dei Dati
       che coinvolgono più Sezioni, il personale coinvolto individua
       autonomamente una Sezione di riferimento, che dovrebbe coincidere
       con quella del Responsabile.

-  Il Direttore della Sezione di riferimento valida la proposta ricevuta
       considerando il contributo del personale proponente alla
       produzione del dato; nel caso di più Sezioni, la decisione è
       presa congiuntamente dai Direttori delle Sezioni coinvolte.

-  Il/i Direttore/i di Dipartimento valida la proposta del Direttore di
       Sezione considerando gli aspetti scientifici e gestionali del
       dato.

-  Nel caso in cui alcuni componenti del Produttore dei Dati afferiscano
       ad altre istituzioni deve esistere un documento formale che
       regoli la co-titolarità dei dati.

-  Il Responsabile dei Dati avvia la procedura di inserimento dei dati
       nel Registro secondo le modalità indicate dall’UGD.

3.3 Procedure di Verifica di Idoneità dei Dati
----------------------------------------------

Una volta definita la sua classe, prima che un dato possa essere
inserito nel Registro, è necessario verificarne l’idoneità. La procedura
per la verifica di tale idoneità è schematizzata in Figura 1. Le
informazioni necessarie alla verifica vengono fornite all’UGD dal
Referente del Produttore dei Dati (vedi Capitolo 4).

Nel caso di Set di Dati non strutturati per cui è richiesta una qualche
valutazione tecnico-scientifica, questa sarà a cura dei Direttori di
Dipartimento e dovrà essere acquisita prima dell’avvio della procedura
di inserimento dei dati nel Registro.

|Senza nome-1|

*Figura 1 – Procedura per la verifica di idoneità dei dati ai fini del
loro inserimento nel Registro Dati.*

4. Registro Dati
================

La realizzazione del Registro dei Dati è condizione determinante per
l’attuazione della politica dei dati dell’INGV.

Il Registro Dati, elencando l’insieme dei metadati riferiti ai dati
scientifici prodotti dall’INGV, di fatto dota l’INGV di un mezzo per
l’identificazione dei dati istituzionali e di quelli relativi a progetti
e convenzioni o prodotti da terzi. In linea di principio il Registro
Dati contiene dati relativi:

-  alle attività istituzionali, a prescindere se siano strutturati o
       meno in Banche Dati, qualunque tipo di accesso ai servizi
       prevedano;

-  a progetti e convenzioni, ammesso che prevedano un accesso aperto;

-  prodotti da terze parti la cui gestione e/o pubblicazione è stata
       demandata ad INGV grazie ad un accordo formale, ammesso che
       prevedano un accesso aperto.

Il Registro Dati intende migliorare e semplificare l’intero ciclo della
ricerca scientifica ed è pensato per soddisfare le esigenze del
personale INGV a tutti i livelli così come le esigenze di soggetti che
interagiscono o vorrebbero potenzialmente interagire con l’INGV e che
quindi richiedono strumenti semplificati e centralizzati per l’accesso
ai dati.

Il Registro Dati mira a semplificare i sistemi per la valutazione delle
metriche relative all'impatto dei risultati della Ricerca.

Il Registro Dati contribuisce alla semplificazione e verificabilità
delle ipotesi scientifiche in quanto permette di rintracciare
univocamente i dati utilizzati per elaborarle permettendone la
riproducibilità. Sarà inoltre possibile per i ricercatori aggiungere
nelle pubblicazioni dei riferimenti univoci ai dati utilizzati,
favorendo al contempo il riconoscimento del lavoro svolto dalle persone
che quei dati hanno contribuito a creare.

Il Registro Dati è aperto e reso accessibile tramite il Portale Web
dell’INGV. Ai fini della gestione e fruizione del Registro Dati, è
necessario raccogliere e mantenere aggiornati i metadati di ciascun
elemento. La gestione scientifica, tecnica e amministrativa del Registro
è affidata al Gruppo Gestione Registro Dati.

Le voci di Registro sono organizzate in gruppi di dati riconducibili a
una comune tipologia di oggetti, ad esempio versioni successive di un
prodotto scientifico oppure sottoprodotti o sottoinsiemi di dati
generati o semplicemente contenuti in una stessa Banca Dati. Ciascun
gruppo di elementi può essere a sua volta collegato ad altri gruppi,
adottando le tipologie di relazioni suggerite nelle linee guida
OpenAire [15]_.

4.1 Metadati
------------

Di seguito è presentato l’elenco dei metadati necessari a descrivere
ciascun elemento del Registro Dati (Tabella 1). È prevedibile che questo
elenco possa essere integrato alla luce di esigenze istituzionali o
future indicazioni dell’Agenzia Digitale per l’Italia [16]_, tali
eventuali integrazioni verranno effettuate dall’UGD e verranno
opportunamente comunicate al personale e comunque rese disponibili sul
sito Web del Gruppo Gestione Registro Dati.

*Tabella 1. Metadati che descrivono ciascun elemento inserito nel
Registro Dati*

+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Metadato                                  | Descrizione del metadato                                                                                                                                                                                                                                                                                                                                                                                      |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ID                                        | Identificativo del record.                                                                                                                                                                                                                                                                                                                                                                                    |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| ID Gruppo                                 | Identificativo del gruppo di elementi.                                                                                                                                                                                                                                                                                                                                                                        |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Gruppo                                    | Nome per esteso del gruppo di elementi.                                                                                                                                                                                                                                                                                                                                                                       |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Acronimo Gruppo                           | Eventuale acronimo associato al gruppo.                                                                                                                                                                                                                                                                                                                                                                       |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Nome                                      | Nome per esteso dell’elemento.                                                                                                                                                                                                                                                                                                                                                                                |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Acronimo                                  | Eventuale acronimo associato all’elemento.                                                                                                                                                                                                                                                                                                                                                                    |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Tipo di Elemento                          | Tipologia di elemento (es.: “Banca dati digitale”, “Dati digitali non strutturati in banca dati”, “Campioni fisici”).                                                                                                                                                                                                                                                                                         |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Descrizione                               | Breve descrizione dell’elemento.                                                                                                                                                                                                                                                                                                                                                                              |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Identificativi Persistenti                | Identificativi persistenti associati all’elemento.                                                                                                                                                                                                                                                                                                                                                            |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Classe                                    | -  Dati Vulcanologici                                                                                                                                                                                                                                                                                                                                                                                         |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati Geochimici (analisi geochimiche di rocce, acque e gas)                                                                                                                                                                                                                                                                                                                                                |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati Geodetici                                                                                                                                                                                                                                                                                                                                                                                             |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati Sismologici e Infrasonici (terrestri e marini)                                                                                                                                                                                                                                                                                                                                                        |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati di campioni fisici (campioni e parametri fisici di rocce, minerali e materiali vari)                                                                                                                                                                                                                                                                                                                  |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati di Geofisica atmosferica e Aeronomia                                                                                                                                                                                                                                                                                                                                                                  |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati Geologici (terrestri e marini)                                                                                                                                                                                                                                                                                                                                                                        |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati Geofisici (geomagnetici, geoelettrici, EM, etc.) terrestri e marini                                                                                                                                                                                                                                                                                                                                   |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati da Modelli Numerici                                                                                                                                                                                                                                                                                                                                                                                   |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Dati di Telerilevamento                                                                                                                                                                                                                                                                                                                                                                                    |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Livello                                   | -  Livello 0: dati grezzi *(Level 0 raw data)* o di base, che non hanno subito alcun livello di elaborazione, esclusa, al più, una validazione di tipo automatico (esempi: forme d’onda, dati GPS, immagini non calibrate, campioni di roccia).                                                                                                                                                               |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Livello 1: prodotti *(Level 1 data products)* ottenuti da procedure automatiche o semi-automatiche (esempi: localizzazione, magnitudo, meccanismi focali dei terremoti, shakemaps, serie storiche dell’ampiezza del tremore vulcanico, dello spostamento di stazioni GPS).                                                                                                                                 |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Livello 2: prodotti *(Level 2 data products)* ottenuti dall’attività di ricerca e comunque sulla base di procedure non automatiche (esempi: modelli crostali, mappe di strain, modelli di sorgente dei terremoti o delle deformazioni, modelli di simulazione numerica dei processi vulcanici, risultati di campagne geofisiche, misure di laboratorio su campioni prelevati per finalità scientifiche).   |
|                                           |                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                           | -  Livello 3: prodotti integrati *(Level 3 integrated data products)* ottenuti da analisi complesse che integrano più prodotti di Livello 2 oppure da analisi che integrano prodotti di Livello 1 o 2 di diverse tipologie e/o provenienti da diverse comunità (esempi: mappe di pericolosità, cataloghi di faglie attive, rapporti di attività vulcanica).                                                   |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Copertura Geografica                      | Si può indicare in modo testuale (esempi: Mondo; Europa; Italia; Etna; provincia di Catania) oppure con le coordinate dei vertici che rappresentano il poligono di copertura geografica codificate con lo standard WKT [17]_.                                                                                                                                                                                 |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Formati di codifica dei dati              | Possibilmente indicando un riferimento allo standard per i formati meno diffusi.                                                                                                                                                                                                                                                                                                                              |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Metadati associati                        | Se viene adottato un modello di metadati per la descrizione della risorsa nel suo complesso e/o del suo contenuto indicare quale (esempi: Dublin Core, DCAT, DataCite, RNDT, INSPIRE). Indicare "custom" se si tratta di metadati codificati secondo uno standard interno non largamente diffuso.                                                                                                             |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Tipologia di dati                         | Dati dinamici o dati statici.                                                                                                                                                                                                                                                                                                                                                                                 |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Frequenza di aggiornamento                | Nel caso si tratti di dati dinamici, qui si specifica la frequenza con cui il contenuto viene modificato (es.: registrati in continuo *“data streaming”*), indipendentemente dal motivo che porta alla modifica.                                                                                                                                                                                              |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Finalità di utilizzo                      | Diverse casistiche e contesti di utilizzo dei dati (esempi: emergenza, comunicazione, formazione, usi commerciali).                                                                                                                                                                                                                                                                                           |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Responsabile dei Dati                     | Dipendente INGV di riferimento che cura gli aspetti scientifici e amministrativi relativi ai dati. Oltre a nome, cognome e affiliazione, deve essere presente il codice ORCID.                                                                                                                                                                                                                                |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Responsabile Tecnico                      | Dipendente INGV di riferimento che cura gli aspetti tecnologici relativi alla Banca Dati. Oltre a nome, cognome e affiliazione, deve essere presente il codice ORCID.                                                                                                                                                                                                                                         |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Produttore dei Dati                       | Singolo dipendente o gruppo di dipendenti INGV che produce i dati. Per ciascun dipendente deve essere indicato nome, cognome, affiliazione, definito il ruolo, possibilmente espresso secondo le specifiche OpenAire [18]_ e fornito il codice ORCID.                                                                                                                                                         |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Organizzazione della banca dati           | Tipologia di organizzazione dell’archiviazione dei dati (esempi: rete di monitoraggio, banca dati, dati grezzi su *filesystem* o *cloud*, archivio documentale, archivio di campioni fisici, archivio fotografico).                                                                                                                                                                                           |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Sezioni INGV coinvolte                    | Elenco delle Sezioni e sedi coinvolte nella creazione dei dati e nella loro gestione (esempi: ONT, RM1, RM2, OV, OE, PA, BO, PI, MI).                                                                                                                                                                                                                                                                         |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| URLs                                      | Indirizzo/i Web come l’\ *homepage* *(Landing page)*, o pagine relative ai servizi quali la ricerca di dati, la visualizzazione, il trasferimento, la trasformazione, la modifica e/o aggiornamento dei dati.                                                                                                                                                                                                 |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Web Service                               | Indicazione di eventuali modalità di accesso ai dati tramite Web service o API *(Application Programming Interface)* o altre procedure automatizzabili con l’indicazione dello standard adottato (esempi: RESTful, SOAP, CGI). Se disponibile, indicare l’indirizzo Web da cui è possibile accedere.                                                                                                          |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Documentazione                            | Link alla documentazione di riferimento, sia di natura scientifica, sia tecnologica. Se disponibile, compilare con il DOI delle pubblicazioni, altrimenti con URL.                                                                                                                                                                                                                                            |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Citazione                                 | Citazione bibliografica dei dati.                                                                                                                                                                                                                                                                                                                                                                             |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Parole chiave                             | Elenco di parole chiave che identificano i dati. Obbligatoria la compilazione di un elenco in lingua inglese, facoltativa l’aggiunta di un elenco in lingua italiana.                                                                                                                                                                                                                                         |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Stato                                     | Valori ammessi: “in progettazione”, “in sviluppo”, “operativo”. Indicare *“legacy”* per dati o prodotti non più gestiti né aggiornati, ma comunque ancora accessibili.                                                                                                                                                                                                                                        |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Titolarità                                | La titolarità è dell’INGV, salvo nei casi in cui siano coinvolte altre istituzioni.                                                                                                                                                                                                                                                                                                                           |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Licenza                                   | Tipologia di licenza *Creative Commons* associata ai dati e/o alla banca dati, poiché potrebbero differire (licenza associata al contenitore diversa dalla licenza associata al/ai contenuto/i).                                                                                                                                                                                                              |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Accesso ai dati                           | I valori ammessi sono “anonimo”, “registrato”, “autorizzato”. Se non applicabile, descrivere brevemente eventuali termini di accesso alternativi.                                                                                                                                                                                                                                                             |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Classe Open Data                          | Classe secondo la classificazione "5 stars" [19]_ che definisce la tipologia di *Open Data*.                                                                                                                                                                                                                                                                                                                  |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Classe metadati                           | Classe secondo la classificazione dei metadati proposta dall'Agenzia per l'Italia Digitale ("Livelli del modello per i metadati" da "Linee Guida Nazionali per la Valorizzazione del Patrimonio Informativo Pubblico 2016").                                                                                                                                                                                  |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| RNDT                                      | Indicazione della rilevanza dei dati ai fini del Repertorio Nazionale dei Dati Territoriali.                                                                                                                                                                                                                                                                                                                  |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Progetti/ iniziative di riferimento       | Progetto/i e/o iniziativa/e di riferimento per il dato e/o prodotto indicato (esempi: Convenzione INGV-DPC, H2020 –seguito dal nome del progetto-, EPOS, EMSO, MED-SUV).                                                                                                                                                                                                                                      |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Altre istituzioni coinvolte               | Nel caso in cui altre istituzioni oltre a INGV abbiano contribuito alla creazione dei dati, indicare quali, specificando per ciascuna il livello di contributo (esempi: trascurabile, marginale, sostanziale).                                                                                                                                                                                                |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Collegamenti                              | E’ possibile indicare collegamenti e la tipologia di relazione secondo le linee guida *OpenAire*\  [20]_. E’ possibile stabilire collegamenti ad altri elementi di Registro oppure a elementi esterni al Registro come ad esempio pubblicazioni, o altre Banche Dati che rendono disponibili gli stessi dati.                                                                                                 |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Data di creazione dei dati                | Data in cui i Dati sono stati creati.                                                                                                                                                                                                                                                                                                                                                                         |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Data di creazione del record              | Data in cui l’elemento è stato inserito nel Registro Dati.                                                                                                                                                                                                                                                                                                                                                    |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Data di ultimo aggiornamento del record   | Data di ultimo aggiornamento delle informazioni relative all’elemento.                                                                                                                                                                                                                                                                                                                                        |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Note                                      | Eventuali note aggiuntive utili ai fini del Registro Dati.                                                                                                                                                                                                                                                                                                                                                    |
+-------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

4.2 Gestione Ordinaria del Registro Dati
----------------------------------------

La gestione ordinaria del Registro Dati coinvolge, a diverso livello, i
seguenti soggetti istituzionali:

-  Il Responsabile dei Dati e il Responsabile Tecnico della Banca Dati,
       che agisce per conto del Produttore di Dati;

-  Il Direttore di Sezione cui fa riferimento il Responsabile dei Dati;

-  Il Direttore di Dipartimento, responsabile della validazione
       istituzionale e della qualità scientifica; nel caso in cui il
       dato coinvolga più Dipartimenti, i Direttori di Dipartimento, ne
       identificano uno di riferimento;

-  L’Ufficio Gestione Dati (UGD), che coordina e gestisce l'intero iter
       procedurale.

4.2.1 Criteri di ammissibilità
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Ai fini del loro inserimento nel Registro Dati, i dati devono rispettare
alcuni criteri di ammissibilità.

In linea di principio, sono inseriti tutti i dati relativi ad attività
istituzionali, qualunque tipo di accesso ai servizi prevedano; i dati
relativi a progetti e convenzioni e quelli prodotti da terze parti la
cui gestione e/o pubblicazione è stata demandata ad INGV, sono inseriti
solo se prevedono un accesso aperto.

I dati devono essere frutto del lavoro di personale dell'INGV ovvero del
lavoro congiunto di personale INGV e di altro ente o istituzione, o
essere dati prodotti da altre istituzioni che demandino all’INGV il
ruolo di renderli accessibili; nel caso in cui siano coinvolte a vario
titolo altre istituzioni devono essere soddisfatte due condizioni:

-  il personale dipendente INGV deve avere contribuito non marginalmente
       alla creazione dei dati ovvero si occupa della gestione e/o
       pubblicazione dei dati;

-  l’INGV, al fine di prevenire possibili situazioni di contenzioso,
       deve dotarsi di accordi formali scritti, approvati dagli Organi
       competenti degli altri enti o istituzioni che disciplinino e
       riportino chiaramente i termini stabiliti tra le parti e,
       soprattutto, l'espressa accettazione dell'inserimento di questi
       dati nel Registro Dati dell’INGV; si precisa che tale
       documentazione deve essere sottoscritta dai soggetti legittimati,
       che dispongano cioè della titolarità dei dati oggetto
       dell’accordo.

I dati devono essere accessibili tramite Internet; nel caso di dati
fisici (ad esempio campioni di roccia), devono essere accessibili i
metadati e stabiliti i termini di accesso all’oggetto fisico.

Per ciascun dato deve essere specificata la tipologia di servizio e le
relative regole di accesso, secondo quanto stabilito nei Principi della
Politica dei Dati. Nel caso di Accesso Registrato o Autorizzato, devono
essere definiti e motivati i criteri. In caso di eventuali limitazioni
nei Servizi di Accesso, come nel caso di embargo, queste devono essere
specificate e adeguatamente motivate. In mancanza di queste specifiche e
motivazioni, il servizio di accesso sarà considerato aperto.

Devono essere disponibili i metadati previsti dal Registro Dati.

Deve essere inoltre disponibile una descrizione che illustri l'iter di
generazione dei dati, in cui sia segnalata l’eventuale provenienza di
dati di cui l’INGV non è l’unico titolare.

Per i dati classificati come statici, deve essere garantita l’integrità
e l’invariabilità nel tempo così come quando inseriti nel Registro,
anche attraverso l’utilizzo di strumenti informatici di validazione (es.
*hashing*, metodo per creare e confrontare chiavi crittografate).
Qualora si manifesti la necessità di variare un dato, si creerà un nuovo
elemento associato alla nuova versione del dato; a questo nuovo elemento
verrà assegnato un nuovo identificativo di Registro e, se presente nella
versione precedente, anche un nuovo DOI. E’ importante che una volta che
un elemento sia inserito nel Registro Dati, esso debba essere mantenuto
accessibile nel tempo, anche se versioni successive più evolute dello
stesso sono nel frattempo subentrate.

Devono essere rispettati gli standard d’interoperabilità sia per la
codifica dei dati, sia negli eventuali servizi di accesso ai dati,
indicando se coincidano con quelli suggeriti dall'Agenzia per l'Italia
Digitale [21]_, oppure se si tratta di standard di riferimento nel
settore scientifico di riferimento.

Deve essere data segnalazione se si tratti di dati territoriali che
possano essere iscritti nel Repertorio Nazionale dei Dati Territoriali
(RNDT) [22]_, con particolare riferimento ai dati territoriali definiti
da normativa di “interesse generale” [23]_.

Ogni richiesta di inserimento dati deve essere corredata da un piano di
sostenibilità concordato con i Direttori delle Sezioni coinvolte, che
chiarisca la natura e la durata della copertura finanziaria necessaria
all'infrastruttura che ospita i dati e che descriva se e come le
soluzioni adottate garantiscono sia la conservazione sia l'accessibilità
ai dati nel lungo periodo.

4.2.2 Procedura di inserimento di elementi 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

La procedura ordinaria di sottomissione si compone dei seguenti passaggi
(Figura 2):

1. Si formalizza l’identità del Produttore dei Dati (vedi Capitolo 3.2)
   indicando per ciascun componente l'afferenza, il ruolo, e il codice
   identificativo ORCID, come da indicazioni MIUR [24]_ e ANVUR [25]_.

2. Nel caso in cui alcune persone afferiscano ad altre istituzioni, è
   necessario assicurarsi che esista un documento formale che regoli i
   termini della collaborazione e dello scambio di dati che deve
   espressamente prevedere che l’INGV la facoltà di poter ripubblicare i
   dati e di inserirli nel proprio Registro Dati;

3. Il Produttore di Dati indica il Responsabile dei Dati e, nel caso di
   una Banca Dati, il Responsabile Tecnico della Banca Dati;

4. Il Responsabile dei Dati verifica i criteri di ammissibilità compila
   i metadati, nel caso in cui sia possibile, compila anche i metadati
   associati all’identificativo DOI (Capitolo 5.2) e per i dati di
   Livello 3 e 4 propone una delle licenze *Creative Commons* (paragrafo
   4.2.5);

5. Il Responsabile dei Dati sottomette la richiesta via e-mail all’UGD
   allegando il materiale preparato al punto precedente;

6. L’UGD verifica l'ammissibilità tecnica della richiesta e valida i
   metadati, interagendo se necessario con il Responsabile dei Dati per
   eventuali correzioni;

7. L’UGD identifica la tipologia di dati oggetto della richiesta e ne
   stabilisce il successivo iter che può essere di due tipi: completo,
   che si adotta per le Banche Dati nuove che non sono parte di gruppi
   di dati già presenti nel Registro, o semplificato, che si adotta per
   i singoli file o Banche Dati che sono parte di un gruppo di dati già
   presente nel Registro (es.: una nuova versione, o un sottoinsieme).
   Viene inviata notifica al Responsabile dei Dati dell'avvenuta
   accettazione preliminare; in caso di rigetto della richiesta, verrà
   inviata una e-mail al Responsabile dei Dati con le ragioni della
   inammissibilità;

8. Il Responsabile dei Dati sottomette al Direttore di Sezione una
   richiesta scritta per l’inserimento dei dati nel Registro, allegando
   il nulla osta dell’UGD, i metadati e l'eventuale documentazione
   necessaria (esempio: accordi formali per lo scambio dei dati con
   altre istituzioni).

9. Il Direttore di Sezione verifica l’attendibilità della richiesta
   sottomessa e la trasmette al Direttore di Dipartimento;

|Regolamento DOI|

*Fig.2 - Schema a blocchi della procedura per l’inserimento di nuovi
elementi nel Registro Dati.*

1. Il Direttore di Dipartimento valuta la richiesta, anche in relazione
   al Programma Triennale di Attività dell’INGV; nel caso di dati di
   Livello 0 o 1, assegna la licenza d’uso in qualità di delegato del
   legale rappresentante dell’INGV; invia l’autorizzazione a procedere
   all’UGD;

2. L’UGD procede all'assegnazione dell'identificativo di Registro e
   inserisce il nuovo elemento nel Registro Dati; nel caso in cui i dati
   non siano né strutturati né strutturabili in una Banca dati
   istituzionale esistente, essi vengono archiviati in Earth-Prints;

3. L’UGD inserisce i metadati dell’elemento in Registri di metadati
   esterni, in particolare nel Registro DOI di DataCite e, nel caso in
   cui sia data segnalazione dal Responsabile dei Dati che i dati siano
   di tipo territoriale e siano di interesse per il Repertorio Nazionale
   dei Dati Territoriali (RNDT), inserisce i dati nel Registro RNDT;

4. L’UGD procede ad aggiornare le informazioni del Registro Dati sul
   portale istituzionale dell’INGV.

4.2.3 Modifiche e integrazioni a elementi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Eventuali richieste di modifiche ai metadati associati agli elementi già
presenti nel Registro Dati vanno comunicate dal Responsabile dei Dati
all’UGD che ne valuterà l’ammissibilità, basandosi sulla consistenza
rispetto a quanto già presente nel Registro. Se l’entità delle
variazioni sarà giudicata rilevante, si valuterà la creazione di un
nuovo elemento nel Registro Dati, ripercorrendo in parte o tutta la
procedura di sottomissione. Sarà cura dell’UGD tenere traccia di tutte
le modifiche effettuate su ciascun elemento del Registro Dati.
Periodicamente, l’UGD verificherà l’accessibilità, integrità e coerenza
dei dati presenti nel Registro Dati; nel caso in cui vengano riscontrate
incongruenze, l’UGD interagirà con il Responsabile dei Dati per le
opportune azioni.

4.2.4 Rimozione di elementi
~~~~~~~~~~~~~~~~~~~~~~~~~~~

La rimozione di un elemento dal Registro Dati può avvenire dietro
presentazione di motivata richiesta da parte del Responsabile dei Dati
all’UGD che ne valuterà l’ammissibilità. Nel caso in cui venga approvata
la richiesta, l’elemento non scomparirà dal Registro Dati, ma verrà
indicato, insieme al motivo della rimozione, come elemento rimosso.
Eventuali identificativi persistenti (es.: DOI) non saranno rimossi, ma
si procederà a modificare opportunamente i relativi metadati per
segnalare che si tratta di elementi rimossi. Verrà inoltre richiesto al
Responsabile dei Dati la creazione di una *Landing Page* in cui sia
spiegata la motivazione della rimozione e che presenti, se esistente, un
collegamento all’elemento che sostituisce quello rimosso.

4.2.5 Licenze associate agli elementi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Poiché la normativa vigente adotta il principio *open by
default*\  [26]_ secondo cui *“I dati [...] che le amministrazioni
pubblicano, con qualsiasi modalità, senza l'espressa adozione di una
licenza [...] si intendono rilasciati come dati di tipo aperto”*, INGV,
in quanto titolare, apporrà una licenza [27]_ ad ogni elemento del
Registro Dati [28]_. In accordo con quanto stabilito nei Principi della
Politica dei Dati dell’INGV e con quanto suggerito dalle linee guida
della Commissione Europea [29]_, le licenze adottate saranno di tipo
*Creative Commons*\  [30]_.

Ai fini di supportare l’\ *Open Science* tramite la pubblicazione di
“Dati di tipo aperto” [31]_, si stabilisce che ai dati di Livello 0 e 1
sia attribuita la licenza *“Creative Commons Attribution (CC
BY)”*\  [32]_, in forza del principio sancito nei “Principi della
Politica dei Dati dell’INGV” secondo cui il titolare  [33]_ della
proprietà intellettuale di questi dati è l’INGV. Per quanto riguarda la
versione della licenza, al momento della redazione di questo documento
si fa riferimento alla v4.0 ma successivamente si dovranno tenere in
considerazione gli eventuali aggiornamenti [34]_.

Per i dati di Livello 2 e 3, il Responsabile dei Dati può suggerire,
tenendo conto della normativa vigente, una delle licenze *Creative
Commons* al momento della richiesta all’UGD che si occuperà di vagliarne
l’ammissibilità. Nel caso in cui il Responsabile dei Dati proponga una
licenza diversa dalla *CC BY*, dovrà fornire la motivazione della
proposta, al fine di indirizzare l’UGD nel processo di valutazione di
ammissibilità. Nel caso in cui nessuna licenza venga proposta dal
Responsabile dei Dati, verrà attribuita automaticamente la licenza *CC
BY*. La licenza assegnata dovrà essere riportata nella *Landing Page*
del sito dal quale vengono distribuiti i dati, le cui caratteristiche
sono dettagliate al punto 5.2.

4.2.6 Identificativi persistenti associati agli elementi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

I dati inseriti nel Registro avranno, oltre a un identificativo di
Registro, anche un identificativo persistente largamente adottato in
ambiente scientifico come il codice DOI. L’Agenzia di Registro DOI
utilizzata è DataCite, di cui si adotta il relativo schema di
metadati [35]_. Per dettagli sulla procedura di assegnazione di questo
identificativo, si fa riferimento al Capitolo 5 “Registri di metadati
non gestiti da INGV”.

4.2.7 Esclusione di responsabilità e termini di utilizzo dei dati
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

L’UGD di concerto con il settore Affari Legali e Contenzioso stabilirà
caso per caso le modalità ed azioni per la gestione dell’esclusione di
responsabilità dell’INGV e del personale circa l'eventuale incompletezza
ed incertezza dei dati presenti nel Registro Dati, utilizzo, anche
parziale, dei dati riportati nel Registro Dati da parte di terzi e
eventuali danni arrecati a terzi derivanti dal loro utilizzo.

5. Registri di Metadati non Gestiti da INGV
===========================================

I dati presenti nel Registro Dati INGV possono essere collegati a
livello istituzionale a registri di metadati non gestiti all’INGV. In
questa sede si prevede il collegamento a due registri in particolare:
DataCite, che permette l’assegnazione di un identificativo DOI agli
elementi e gestisce metadati adatti a descrivere i dati prodotti dalla
Ricerca scientifica, e il Repertorio Nazionale dei Dati Territoriali
(RNDT), gestito dall’Agenzia per l’Italia Digitale (AgID) e che si
colloca nell’ambito dell’infrastruttura europea per l'informazione
territoriale (INSPIRE) [36]_. L'eventuale adozione di nuovi registri
esterni, laddove se ne manifesti l’esigenza a livello istituzionale,
verrà valutata di concerto tra Ufficio Gestione Dati e Direttori di
Dipartimento.

Al fine di rispettare il principio di *“Data entry
minimisation"*\  [37]_, si prevede che i metadati necessari
all’inserimento di dati in registri esterni, siano prelevati
direttamente dal Registro Dati INGV in modo del tutto automatizzato,
senza quindi richiedere il reinserimento di informazioni già in
precedenza archiviate. L’aggiornamento dei metadati avviene dunque a
cascata, aggiornando i metadati nel Registro Dati INGV, vengono
aggiornati automaticamente i metadati associati ai dati collegati nei
registri esterni.

5.1 Requisiti della *Landing Page*
----------------------------------

La pagina Web di destinazione (Landing Page) è la pagina Web che viene
associata ai dati nei registri esterni, ovvero la pagina su cui gli
utenti arriveranno consultando questi registri. Al fine di armonizzare
le informazioni presentate in queste pagine e anche ai fini di
migliorare l’immagine coordinate dell’INGV verso l’esterno, le Landing
Page devono contenere i seguenti elementi.

-  Il logo dell’INGV, che chiarisca e identifichi la paternità dei dati
       all’utente esterno, e un collegamento diretto al portale
       istituzionale INGV. Se altre istituzioni sono coinvolte nella
       produzione del dato, anch’esse devono essere chiaramente
       identificabili e un collegamento ai rispettivi portali
       istituzionali deve essere presente.

-  Il nome e una breve descrizione dell’elemento del Registro Dati che
       si rende disponibile, riportando informazioni coerenti con quelle
       archiviate nel Registro.

-  Una descrizione esaustiva dei dati che permetta ai potenziali
       utilizzatori un uso consapevole, chiarendo le finalità e le
       modalità con cui i dati sono stati creati; se disponibili,
       fornire un elenco delle pubblicazioni scientifiche e tecniche di
       riferimento, sempre indicandone il codice DOI, se disponibile; si
       rammenta che il Registro Dati può contenere uno o più riferimenti
       a queste pubblicazioni, ed è quindi auspicabile che le
       pubblicazioni riportate sulla *Landing Page* siano le stesse
       riportate nel Registro Dati.

-  Un accesso diretto ai dati o, se trattasi di dati ad accesso non
       libero, una chiara spiegazione delle modalità di accesso ai dati.

-  Nel caso di dati associati ad elementi del Registro Dati che facciano
       parte di un gruppo di elementi, rendere disponibile un
       collegamento alle altre *Landing Page* che contengono gli altri
       elementi del gruppo, chiarendo la natura del collegamento
       esistente tra i diversi dati del gruppo. Soprattutto nel caso in
       cui si tratti di gruppi di elementi composti da diverse versioni
       dello stesso prodotto, è fondamentale presentare all’utente un
       collegamento alle altre versioni, chiarendo quali siano le
       differenze da una versione all’altra e, comunque, chiarendo quale
       sia la versione più aggiornata.

-  La citazione bibliografica dei dati, con l'elenco degli autori, il
       titolo, l'indicazione degli istituti o enti che detengono la
       titolarità dei dati. Per indicare l’INGV, utilizzare la dizione
       “Istituto Nazionale di Geofisica e Vulcanologia (INGV)”. Gli
       autori devono coincidere con quanto riportato nel Registro Dati;
       nel caso di un numero esteso di persone (ad esempio superiore a
       quattro), può comprendere, oltre ai principali responsabili
       scientifici, anche un generico riferimento al gruppo di lavoro.
       La citazione deve includere alla fine il codice DOI associato ai
       dati nella sua forma risolvibile sul Web, anteponendo la scritta
       “http://doi.org/”. Le citazioni bibliografiche devono essere
       redatte in lingua inglese; un’eventuale, aggiuntiva, citazione in
       italiano può anch’essa essere presentata.

-  L’elenco delle persone che hanno contribuito alla creazione dei dati,
       chiarendo quale sia tra questi il Responsabile Scientifico e, se
       presente, il responsabile Tecnologico, in coerenza con quanto
       riportato nel Registro Dati; gli utenti devono poter contattare
       il Responsabile dei Dati e/o il Responsabile Tecnico, per cui è
       necessario pubblicarne l’indirizzo di posta elettronica o, in
       alternativa, si deve poter raggiungere uno strumento interattivo
       per ricevere e fornire richieste.

-  L’indicazione della licenza *Creative Commons (CC)* così come
       riportata nel Registro Dati, che deve essere collegata alla
       pagina Web di descrizione sul sito *Creative Commons*; dovrà
       essere chiarito agli utenti quali siano le eventuali limitazioni
       di accesso al dato, le limitazioni d’uso e le limitazioni di
       responsabilità da parte di INGV e altre eventuali note legate
       alla sfera legale.

Sarà cura dell’UGD supportare i Responsabili dei Dati nel verificare la
presenza di tutti gli elementi necessari nella *Landing Page*, e in
particolar modo, verrà garantita la coerenza delle informazioni con
quanto riportato nel Registro Dati.

5.2 Identificativi DOI
----------------------

    L’UGD assocerà, laddove possibile, ogni elemento del Registro Dati a
    un identificativo persistente DOI inserendo i relativi metadati nel
    registro DataCite [38]_.

5.2.1 Linee Guida per l'Assegnazione
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

L’assegnazione è vincolata da una serie di condizioni inderogabili in
quanto deve essere:

-  disponibile una pagina Web da associare, detta *Landing Page*;

-  possibile recuperare i dati direttamente dalla L\ *anding Page*;

-  associata una licenza *Creative Commons* al dato identificato;

-  compilato l’elenco dei metadati secondo lo schema DataCite [39]_.

La convenzione stipulata nel 2013 tra INGV e CRUI rende disponibili due
prefissi DOI:

-  “10.6092/INGV.IT-” un sotto-codice del prefisso CRUI, condiviso con
       altre istituzioni, e con un esplicito riferimento a INGV;

-  “10.13127” un prefisso neutro ad uso esclusivo INGV.

L'identificativo DOI è strutturato con un prefisso e un suffisso, qui un
esempio basato sul codice con prefisso CRUI:

    |image3|

Di seguito le linee guida per l’assegnazione degli identificativi,
redatte prendendo in considerazione le indicazioni contenute nel *"DOI
Handbook"*\  [40]_.

Il codice “\ *10.6092/INGV.IT-*\ ” va utilizzato per i dati la cui
titolarità è dell’INGV in modo esclusivo e la cui copertura geografica
sia di interesse prettamente nazionale. I codici DOI basati su questo
prefisso devono rispettare questa struttura:

10.6092/INGV.IT/< gruppo-dati>/<identificativo specifico>

Il prefisso "*10.13127/*" va utilizzato quando è auspicabile l'uso di un
codice anonimo, ad esempio nel caso in cui si vogliano identificare
prodotti cui hanno contribuito più istituzioni o che siano di rilevanza
internazionale, oppure nel caso in cui viene richiesto l'uso di codici
identificativi "non parlanti", termine gergale con cui si intende che il
codice non presenta una forma intelligibile. I codici DOI basati su
questo prefisso devono rispettare questa struttura:

10.13127/< gruppo-dati >/<identificativo specifico>

Gruppi complessi di elementi del Registro possono adottare un codice
base comune, seguito da uno *slash* (“/”), seguito a sua volta da un
identificativo diverso per ciascun elemento del gruppo; è possibile
prevedere più di un sotto-livello, a seconda la complessità del gruppo.

Gruppi di elementi composti da versioni diverse dello stesso elemento,
devono adottare un prefisso costante, aggiungendo la versione dopo il
punto (“.”).

La lunghezza del suffisso non dovrebbe superare i 50 caratteri, e può
contenere i seguenti caratteri: numerici (0-9), lettere dell’alfabeto
inglese maiuscole (A-Z); il simbolo di “meno” (“-”) e il simbolo di
“sottolineato” (“\_”).

Al fine di diffondere l’uso dei codici, si suggerisce di aggiungere
sempre il riferimento al codice DOI in presentazioni, *abstract*,
poster, rapporti tecnici, social networks e soprattutto nelle
pubblicazioni. Per un uso più funzionale, si consiglia di presentare il
codice nella forma di indirizzo risolvibile (es.:
`*http://doi.org/10.13127/xxxx)* <http://doi.org/10.13127/xxxx)>`__.

5.2.2 Linee Guida per la Compilazione di Metadati DataCite
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

I metadati da associare all'identificativo DOI adottano lo schema
DataCite [41]_ nella sua più recente versione. Il presente documento fa
riferimento alla versione 4.1 dello schema (la più recente al momento
della stesura di questo documento); è prevedibile che in futuro questi
metadati possano variare con nuove versioni, per cui sarà cura dell’UGD
segnalare eventuali aggiornamenti sulla propria pagina Web.

Di seguito vengono elencati i metadati disponibili, per ognuno viene
specificata l’etichetta *(tag)* da utilizzare, il numero di occorrenze
possibili, la definizione secondo lo schema DataCite e un’indicazione
sul contenuto. I metadati vengono suddivisi tra quelli a compilazione
obbligatoria (Tabella 2), cioè la cui presenza è vincolante per
l’inserimento di Dati nel Registro, e metadati a compilazione
facoltativa (Tabella 3).

I metadati vanno redatti in formato XML; se possibile, l’UGD renderà
disponibili opportuni strumenti per semplificare il processo di
compilazione di tale file.

*Tabella 2 - Metadati a compilazione obbligatoria.*

+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Etichetta (tag)       | Occorr.   | Definizione secondo DataCite (v4.1)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Contenuto                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Identifier*          | 1         | *The Identifier is a unique string that identifies a resource. For software, determine whether the identifier is for a specific version of a piece of software, (per the Force11 Software Citation Principles*\  [42]_\ *), or for all versions.*                                                                                                                                                                                                                                                                               | Compilato con il codice DOI assegnato.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Title*               | 1         | *A name or title by which a resource is known. May be the title of a dataset or the name of a piece of software.*                                                                                                                                                                                                                                                                                                                                                                                                               | Titolo in lingua inglese; l'eventuale acronimo si aggiunge tra parentesi. E’ possibile specificare il titolo tradotto in altre lingue usando l’attributo “\ *TranslatedTitle*\ ”.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Publication Year*    | 1         | *The year when the data was or will be made publicly available. In the case of resources such as software or dynamic data where there may be multiple releases in one year, include the Date/dateType/dateInformation property and sub-properties to provide more information about the publication or release date details.*                                                                                                                                                                                                   | Anno di prima pubblicazione dei dati.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Resource Type*       | 1         | *A description of the resource.*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Ai fini del Registro Dati solitamente è compilato con “Dataset”. Lo schema DataCite lascia libera la compilazione del campo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Description*         | 1-n       | *All additional information that does not fit in any of the other categories. May be used for technical information.*                                                                                                                                                                                                                                                                                                                                                                                                           | Descrizione testuale dei dati concisa e chiara in lingua inglese. Aggiungere l’attributo “\ *DescriptionType*\ ” compilato con “\ *Abstract*\ ”. E’ possibile aggiungere altre tipologie di descrizioni: "*Methods*", "*SeriesInformation*", "*TableOfContents*", "*TechnicalInfo*".                                                                                                                                                                                                                                                                                                                                                                                   |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Subject*             | 1-n       | *Subject, keyword, classification code, or key phrase describing the resource.*                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Compilazione libera, con l’accortezza di specificare l’attributo “\ *SubjectScheme*\ ” in cui viene indicato lo schema di classificazione utilizzato.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *GeoLocation*         | 1-n       | *Spatial region or named place where the data was gathered or about which the data is focused.*                                                                                                                                                                                                                                                                                                                                                                                                                                 | E’ possibile specificare una serie di “\ *GeoLocationPlace*\ ”, e/o una serie di “\ *GeoLocationPolygon*\ ”, e/o una serie di “\ *GeoLocationPolygon*\ ”.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Publisher*           | 1         | *The name of the entity that holds, archives, publishes prints, distributes, releases, issues, or produces the resource. This property will be used to formulate the citation, so consider the prominence of the role. For software, use Publisher for the code repository. If there is an entity other than a code repository, that "holds, archives, publishes, prints, distributes, releases, issues, or produces" the code, use the property Contributor / contributorType / hostingInstitution for the code repository.*   | Inserire il nome dell’Istituto che rende disponibile i dati. Il campo viene compilato con “Istituto Nazionale di Geofisica e Vulcanologia (INGV)”.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Creator*             | 1-n       | *The main researchers involved in producing the data, or the authors of the publication, in priority order.*                                                                                                                                                                                                                                                                                                                                                                                                                    | Elencare i principali responsabili scientifici e/o tecnologici, indicando per ciascuno l’affiliazione e il codice identificativo ORCID. Oltre ai principali responsabili è anche possibile inserire un riferimento generico al gruppo di lavoro.                                                                                                                                                                                                                                                                                                                                                                                                                       |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Contributor*         | 1-n       | *The institution or person responsible for collecting, managing, distributing, or otherwise contributing to the development of the resource. To supply multiple contributors, repeat this property. For software, if there is an alternate entity that "holds, archives, publishes, prints, distributes, releases, issues, or produces" the code, use the contributorType "hostingInstitution" for the code repository.*                                                                                                        | Elencare le persone che hanno contribuito ai dati, identificando per ciascuno il ruolo svolto, l’affiliazione e il codice ORCID. E’ possibile aggiungere anche istituzioni. Settare l’attributo “\ *nameType*\ ” “personal” per le persone e “organizational” per le istituzioni. I ruoli previsti sono: *ContactPerson*, *DataCollector*, *DataCurator*, *DataManager*, *Distributor*, *Editor*, *HostingInstitution*, *Other*, *Producer*, *ProjectLeader*, *ProjectManager*, *ProjectMember*, *RegistrationAgency*, *RegistrationAuthority*, *RelatedPerson*, *ResearchGroup*, *RightsHolder*, Resea\ *r*\ cher, Spon\ *s*\ or, *Supervisor*, *WorkPackageLeader*   |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Rights*              | 1         | *Any rights information for this resource*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Tipologia di licenza *Creative* *Commons*.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Funding Reference*   | 1-n       | *Information about financial support (funding) for the resource being registered*                                                                                                                                                                                                                                                                                                                                                                                                                                               | Elenco delle istituzioni che hanno finanziato la creazione dei dati.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| *Date*                | 0-1       | *Different dates relevant to the work. The attribute 'dateType' may contains: Accepted, Available, Copyrighted, Collected, Created, Issued, Submitted, Updated, Valid.*                                                                                                                                                                                                                                                                                                                                                         | Se disponibili, compilare con le date relative.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
+-----------------------+-----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

*Tabella 3 – Metadati a compilazione facoltativa.*

+------------------------------+----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|     Etichetta (Tag)          | Occorr   | Descrizione fornita da DataCite                                                                                                                                                                                                                                                                                                             | Contenuto                                                                                                                                                                                                                            |
+------------------------------+----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|     *Language*               | 0-1      | *The primary language of the resource.*                                                                                                                                                                                                                                                                                                     | Compilare con la dizione inglese della lingua con cui i dati sono pubblicamente disponibili i dati.                                                                                                                                  |
+------------------------------+----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|     *Alternate Identifier*   | 0-n      | *An identifier or identifiers other than the primary Identifier applied to the resource being registered. This may be any alphanumeric string which is unique within its domain of issue. May be used for local identifiers. Alternate Identifier should be used for another identifier of the same instance (same location, same file).*   | Se i dati associati al DOI sono anche associati ad altri identificativi è possibile usare questo tag per stabilire un collegamento.                                                                                                  |
+------------------------------+----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|     *Related Identifier*     | 0-n      | *Identifiers of related resources. These must be globally unique identifiers.*                                                                                                                                                                                                                                                              | Se i dati hanno delle relazioni –di qualunque natura- con altri prodotti della ricerca associati ad identificativi è possibile usare questo tag per stabilire un collegamento. Si veda l’elenco delle relazioni ammesse a seguire.   |
+------------------------------+----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|     *Size*                   | 0-n      | *Size (e.g. bytes, pages, inches, etc.) or duration (extent), e.g. hours, minutes, days, etc., of a resource.*                                                                                                                                                                                                                              | Se è possibile quantificare i dati, compilare questo campo.                                                                                                                                                                          |
+------------------------------+----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|     *Format*                 | 0-n      | *Technical format of the resource. Use file extension or MIME type where possible.*                                                                                                                                                                                                                                                         | Se i dati sono disponibili in uno o più standard di codifica di dati, indicare qui i formati.                                                                                                                                        |
+------------------------------+----------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

5.2.3 Relazioni con altri prodotti della ricerca
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Lo schema di metadati DataCite permette di collegare l’identificativo
DOI ad altre risorse digitali. Nel tag “relatedIdentifier” demandato a
stabilire tali collegamenti è possibile specificare nell’attributo
“relatedIdentifierType” una delle seguenti tipologie di identificativi:
ARK, arXiv, bibcode, DOI, EAN13, EISSN, Handle, IGSN, ISBN, ISSN, ISTC,
LISSN, LSID, PMID, PURL, UPC, URL, URN. La tipologia di relazione tra il
DOI e un’altra risorsa digitale si specifica tramite l’attributo
“relationType”. In Tabella 4 si riportano le relazioni ammesse in cui
(A) rappresenta l’oggetto associato al DOI, e (B) l’elemento che si sta
collegando.

*Tabella 4 – Elenco delle tipologie di relazioni ammesse dallo schema di
metadati DataCite.*

+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| Tipo di relazione     | Descrizione fornita da DataCite                                                                                              |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsCitedBy             | *Indicates that B includes A in a citation*                                                                                  |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| Cites                 | *Indicates that A includes B in a citation*                                                                                  |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsSupplementTo        | *Indicates that A is a supplement to B*                                                                                      |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsSupplementedBy      | *Indicates that B is a supplement to A*                                                                                      |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsContinuedBy         | *Indicates A is continued by the work B*                                                                                     |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| Continues             | *Indicates A is a continuation of the work B*                                                                                |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| Describes             | *Indicates A describes B*                                                                                                    |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsDescribedBy         | *Indicates A is described by B*                                                                                              |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| HasMetadata           | *Indicates resource A has additional metadata B*                                                                             |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsMetadataFor         | *Indicates additional metadata A for a resource B*                                                                           |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| HasVersion            | *Indicates A has a version (B)*                                                                                              |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsVersionOf           | *Indicates A is a version of B*                                                                                              |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsNewVersionOf        | *Indicates A is a new edition of B, where the new edition has been modified or updated*                                      |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsPreviousVersionOf   | *Indicates A is a previous edition of B*                                                                                     |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsPartOf              | *Indicates A is a portion of B; may be used for elements of a series*                                                        |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| HasPart               | *Indicates A includes the part B*                                                                                            |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsReferencedBy        | *Indicates A is used as a source of information by B*                                                                        |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| References            | *Indicates B is used as a source of information for A*                                                                       |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsDocumentedBy        | *Indicates B is documentation about or explaining A*                                                                         |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| Documents             | *Indicates A is documentation about B*                                                                                       |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsCompiledBy          | *Indicates B is used to compile or create A*                                                                                 |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| Compiles              | *Indicates B is the result of a compile or creation event using A*                                                           |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsVariantFormOf       | *Indicates A is a variant or different form of B*                                                                            |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsOriginalFormOf      | *Indicates A is the original form of B*                                                                                      |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsIdenticalTo         | *Indicates that A is identical to B, for use when there is a need to register two separate instances of the same resource*   |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsReviewedBy          | *Indicates that A is reviewed by B*                                                                                          |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| Reviews               | *Indicates that A is a review of B*                                                                                          |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsDerivedFrom         | *Indicates B is a source upon which A is based*                                                                              |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsSourceOf            | *Indicates A is a source upon which B is based*                                                                              |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| IsRequiredBy          | *Indicates A is required by B*                                                                                               |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+
| Requires              | *Indicates A requires B*                                                                                                     |
+-----------------------+------------------------------------------------------------------------------------------------------------------------------+

5.2.4 Identificazione di Frammenti di Dati Complessi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Al fine di recuperare un sottoinsieme di un set di dati (frammento o
*subset)* che sia associato ad un identificativo DOI, è possibile usare
soluzioni per evitare l’inutile assegnazione di tanti identificativi
diversi per ogni possibile frammento del dato originale. A tal fine si
introduce il concetto di “frammento di identificativo” *(fragment
identifier)*.

Questa soluzione è supportata dal registro DataCite che ha implementato
i *“Media Fragment Identifier”* (MFIDs), uno standard sviluppato dal W3C
e basato su raccomandazioni IETF *(Internet Engineering Task Force)*
pensato per semplificare l’accesso a flussi di dati come video o audio.
La struttura della chiamata è la seguente:

<scheme name> : <hierarchical part> [ ? <query> ] [ # <fragment> ]

Gli identificativi DOI, essendo basati su *Handle System*\  [43]_,
possono usufruire dei *”Template handles”*, che permettono di aggiungere
un numero indefinito di parametri all’identificativo inseriti dopo il
simbolo di cancelletto (“#”). Questa soluzione è stato preso in
considerazione dal gruppo di lavoro *“Data Citation”*\  [44]_ dalla
*Research Data Alliance* (RDA) che ne ha fatto una raccomandazione in
ambito di dati dinamici. La tecnica di estrazione di sottoinsiemi di
dati con l'ausilio di parametri viene denominata *"data slicing"*. In
ambito sismologico sono in corso sperimentazioni [45]_\ :sup:`,`  [46]_
nell’ambito dei progetti europei COOPEUS, ENVRI ed EUDAT.

5.3 Il Repertorio Nazionale dei Dati Territoriali (RNDT)
--------------------------------------------------------

Il Repertorio Nazionale dei Dati Territoriali (RNDT) [47]_ è stato
individuato come “base di dati di interesse nazionale” [48]_ definito
come *"l'insieme delle informazioni raccolte e gestite digitalmente
dalle pubbliche amministrazioni, omogenee per tipologia e contenuto e la
cui conoscenza è utilizzabile dalle pubbliche amministrazioni, anche per
fini statistici, per l'esercizio delle proprie funzioni e nel rispetto
delle competenze e delle normative vigenti"*.

Il contenuto del RNDT e le relative modalità di costituzione e
aggiornamento sono state definite dal Comitato per le regole tecniche
sui dati territoriali delle pubbliche amministrazioni del Ministro per
la Pubblica Amministrazione e l’Innovazione, di concerto con il Ministro
dell’Ambiente e della Tutela del Territorio e del Mare [49]_. Sulla base
di tale contesto normativo, l’RNDT costituisce il catalogo nazionale dei
metadati riguardanti i dati territoriali e i servizi ad essi relativi
disponibili presso le Pubbliche Amministrazioni.

L’RNDT pubblica i metadati prodotti e conferiti da ciascuna
amministrazione accreditata che, come previsto dalla normativa vigente,
resta pienamente responsabile della correttezza e dell'aggiornamento
degli stessi, nonché della gestione e dell'aggiornamento dei dati cui
tali metadati si riferiscono.

5.3.1 Dati territoriali d’interesse generale 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Nel descrivere il contenuto del RNDT, il legislatore definisce
dettagliatamente 110 tipologie di “Dati d’interesse generale”, e l’INGV
è titolare di alcune di esse, tra cui:

-  *Reti geodetiche e monografie di elementi geodetici*: reti di punti
       con coordinate note relative a un sistema di riferimento
       geodetico comune, utilizzati per il corretto dimensionamento ed
       orientamento del rilevamento topo – cartografico di un'estesa
       area terrestre, e relative monografie.

-  *Modelli digitali di elevazione*: Rappresentazione della morfologia
       del suolo in formato digitale, comprendono rappresentazioni tipo
       DTM, DEM, DSM, DTED e simili.

-  *Rete sismica nazionale*: Stazioni e reti dove si misura e si
       registra l’attività sismica in corso (spostamenti del suolo).

-  *Carte della Pericolosità sismica di riferimento per il territorio
       nazionale*: rappresentazioni illustranti i valori di
       accelerazione di picco orizzontale del suolo (ag) e i valori
       spettrali per vari periodi di ritorno (approvati con l’Ordinanza
       PCM 3519 del 28 aprile 2006, All. 1b) da utilizzare nelle nuove
       norme tecniche per le costruzioni approvate con decreto
       ministeriale del 14.01.2008).

L’INGV, in qualità di Amministrazione Pubblica titolare di alcuni dei
dati di interesse generale, deve provvedere a incrementare e aggiornare
il Repertorio Nazionale Dati Territoriali così da rendere la
consultazione dei metadati accessibile a tutti tramite l’accesso al
Catalogo RNDT e, a cascata, soddisfare gli adempimenti della Direttiva
INSPIRE.

Il contributo al RNDT è anche previsto dalle “\ *Specifiche degli
standard per i formati dei dati e dei metadati, per il loro trattamento
ai fini della pubblicazione (trasparenza) e del riutilizzo (open data),
e per la consegna degli applicativi software”*, contenute nell’Allegato
1 della “\ *Convenzione tra il Dipartimento della Protezione Civile e
l’INGV per l’attività di sorveglianza sismica e vulcanica sul territorio
nazionale, di consulenza tecnico-scientifica e di studi sui rischi
sismico e vulcanico”*\  [50]_, riporta che *“per essere correttamente
utilizzati, tutti i servizi web erogati ed i dati consegnati dovranno
essere corredati dei relativi metadati che descrivano proprietà,
caratteristiche e storia del dato, nonché la descrizione dei singoli
campi associati alle tabelle dei dati. Tali metadati dovranno essere
redatti in maniera conforme agli standard previsti dal Repertorio
Nazionale dei Dati Territoriali, di cui al decreto del Presidente del
Consiglio dei Ministri del 10 novembre 2011”*.

Si rimanda al portale web RNDT per la “\ *Guida operativa per
l’accreditamento delle Pubbliche Amministrazioni”*\  [51]_ con la
procedura di accreditamento di Amministrazioni Pubbliche tenute ad
alimentare il Repertorio.

5.3.2 Linee Guida per la Compilazione di Metadati RNDT
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Il profilo di metadati “RNDT” è basato sugli Standard ISO 19115, 19119 e
TS 19139, prodotti dal *Technical Committe* ISO/TC211 [52]_ che si
occupa di standard per l'informazione geografica. Il rispetto delle
regole tecniche del RNDT, in aderenza agli standard ISO di riferimento,
assicura la contestuale conformità, senza ulteriori adempimenti, al
regolamento europeo per l’attuazione della direttiva europea
INSPIRE [53]_ per quanto riguarda i metadati. I metadati INSPIRE
rappresentano infatti un sottoinsieme di quelli previsti dal RNDT,
pertanto, la conformità di un set di metadati al profilo del RNDT se ne
garantisce la conformità ad INSPIRE.

Si rimanda al portale web del RNDT [54]_ per le regole tecniche di
compilazione dei metadati RNDT per i dati territoriali che descrivono
dettagliatamente i metadati da associare a dati vettoriali, immagini
raster e ai servizi di accesso ai dati. L’UGD si doterà degli opportuni
strumenti informatici per la compilazione di questi metadati in modo
automatizzato.

6. Ufficio Gestione Dati
========================

L’istituzione dell’Ufficio Gestione Dati (UGD) risponde al principio
“Professionalità” del DP200. Tale principio sancisce l’impegno dell’INGV
all’allocazione delle necessarie risorse professionali al fine di
attuare la Politica dei Dati\ *.*

L’UGD ha le seguenti finalità, strettamente interconnesse tra loro:

-  promozione del paradigma *Open Science*;

-  gestione del Registro Dati;

-  supporto tecnico-scientifico nella stesura di contratti o convenzioni
       che prevedono la gestione di dati INGV.

L’UGD promuove il paradigma *Open Science*, garantendo la progressiva
apertura dei dati e il miglioramento della loro gestione in conformità
alla normativa vigente. A tal fine l’UGD promuove iniziative di
formazione del personale e avanza proposte di modifiche della gestione
dei dati dell’INGV. I dati trattati dall’UGD sono, esclusivamente, Dati
di Ricerca come definiti al Capitolo 1 di questo documento.

L’UGD svolge la sua attività conformemente a quanto definito in questo
documento operando all’interno del “Centro Servizi per il coordinamento
delle attività a supporto della Ricerca”.

L’UGD è istituito con delibera del Consiglio di Amministrazione. I suoi
componenti sono nominati con decreto del Presidente e durano in carica
tre anni eventualmente rinnovabili una sola volta.

6.1 Compiti dell’Ufficio Gestione Dati 
---------------------------------------

L’UGD persegue le sue finalità secondo un Piano di Attività che
definisce gli obiettivi annuali e descrive dettagliatamente tempi, modi
e risorse umane e finanziarie necessarie allo svolgimento delle
attività. Il Piano di Attività viene sottoposto, per approvazione, al
Direttore Generale ed ai Direttori di Dipartimento, per le rispettive
competenze.

Nella fase di Avvio e Sperimentazione necessaria all’istituzione del
Registro Dati, l’UGD procederà a trasferire i Dati presenti nel
Censimento condotto nelle Sezioni dell’INGV nel periodo 2016-2017 nel
Registro Dati. Tale trasferimento avverrà secondo una lista di priorità
definita contestualmente all’approvazione del presente documento dai
Direttori di Dipartimento, sulla base dei criteri definiti nei capitoli
precedenti. Come indicato al punto 2.3, al termine del primo anno l’UGD
redigerà un rapporto da inviare ai Direttori di Dipartimento, suggerendo
soluzioni alle eventuali criticità e miglioramenti.

L’UGD dovrà dotarsi di strumenti per la gestione automatizzata del
Registro basati su principi di trasparenza, efficienza e
semplificazione, integrati con i sistemi gestionali dell’INGV. Tali
strumenti dovranno permettere l’allineamento automatico dei metadati del
Registro INGV con Registri di metadati esterni, sia quelli previsti nel
presente documento come il Registro DOI di DataCite o il Repertorio
Nazionale dei Dati Territoriali (RNDT), sia per altri registri che in
futuro potranno essere considerati. Al momento della sua istituzione,
l’UGD dovrà inserire nel suo Piano di Attività la costruzione dei
suddetti strumenti per la gestione ordinaria.

L’UGD dovrà dotarsi di una pagina Web opportunamente segnalata nel sito
istituzionale in cui raccolga e diffonda informazioni riguardanti la
propria attività.

L’UGD si occuperà del monitoraggio dei Dati elencati nel Registro Dati,
al fine di garantirne la coerenza e il rispetto di quanto dichiarato in
fase di inserimento nel Registro e a tal fine potrà interfacciarsi
direttamente con i Responsabili delle Banche Dati e con i Responsabili
Tecnici delle Banche Dati.

6.2 Composizione dell’Ufficio Gestione Dati
-------------------------------------------

La composizione dell’UGD tiene conto delle Linee Guida dell’Agenzia
dell’Italia Digitale (AgID) 2017 [55]_, adattandole allo specifico
contesto operativo dell’INGV e allo svolgimento dei compiti assegnati.
L’UGD è quindi composto da un Coordinatore, tre Referenti Scientifici e
un Referente Informatico i cui *curricula* devono essere coerenti con
quanto riportato nelle Linee Guida AgID.

Il **Coordinatore** svolge le seguenti funzioni:

-  Organizza le attività dell’UGD predisponendo il relativo Piano di
       Attività e coordinando le risorse umane e finanziarie assegnate
       all’UGD;

-  predispone le relazioni di attività e gli eventuali contributi
       richiesti all’UGD per la redazione dei documenti istituzionali di
       programmazione e rendicontazione;

-  svolge il ruolo di Responsabile Open Data (*Data Manager* previsto
       dalle Linee Guida AgID);

-  rappresenta l’UGD con gli organi di governo e di indirizzo dell’INGV
       e nei rapporti verso l’esterno;

-  collabora e si coordina con il Settore Affari Legali e Contenzioso
       per quanto concerne gli aspetti legali e normativi;

-  collabora e si coordina con la “Commissione per l’Accesso Aperto ai
       Contributi della Ricerca”;

-  collabora e supporta il Responsabile della Trasparenza [56]_,
       nell’ambito delle competenze a questo assegnate dalle norme, al
       fine di rafforzare gli obiettivi di trasparenza e di massimo
       utilizzo e riutilizzo dei dati pubblici di tipo aperto.

Il Coordinatore è selezionato tra il personale ricercatore e tecnologo
dell’INGV che possiede le caratteristiche del *Data Manager* come
previsto dalle Linee Guida AgID.

I tre **Referenti Scientifici** svolgono le seguenti funzioni:

-  coadiuvano il Coordinatore in tutte le materie relative alla gestione
       scientifica dei dati;

-  verificano l’idoneità dei dati in conformità a quanto definito al
       Capitolo 3;

-  seguono la procedura di inserimento dei dati nel Registro e nel RNDT
       in conformità a quanto definito ai Capitoli 4 e 5;

-  seguono l’assegnazione dei DOI, in conformità a quanto definito al
       Capitolo 5;

-  forniscono indicazioni sull’ottimizzazione e armonizzazione degli
       standard dei dati e dei metadati utilizzati dall’INGV, in
       conformità con le direttive nazionali ed internazionali e con le
       buone pratiche proposte dalla comunità scientifica.

I Referenti Scientifici, uno per ciascun Dipartimento, sono selezionati
tra il personale ricercatore e tecnologo dell’INGV afferente ai tre
dipartimenti.

Il **Referente Informatico** svolge le seguenti funzioni:

-  coadiuva il Coordinatore nella gestione tecnica ed informatica dei
       dati;

-  verifica la funzionalità delle banche dati ai fini della gestione del
       Registro Dati;

-  fornisce indicazioni per l’ottimizzazione e armonizzazione delle
       banche dati dell’INGV, in conformità con le direttive nazionali
       ed internazionali e con le buone pratiche proposte dalla comunità
       scientifica;

-  interagisce con Centro Servizi Informativi.

Il Referente Informatico è selezionato tra i Responsabili Tecnici
elencati nel Registro Dati. Nella fase di Avvio e Sperimentazione, il
Referente Informatico è selezionato tra i Responsabili Tecnici elencati
nel Censimento.

Allegato 1. 
============

Avvio e Sperimentazione del Registro dei Dati dell’INGV
=======================================================

Al fine di avviare la sperimentazione della realizzazione del Registro
dei Dati dell’INGV, e in conformità di quanto indicato nei Capitoli 2.3
e 6.1 del Documento di ATTUAZIONE DELLA POLITICA DEI DATI DELL’INGV (di
seguito “Documento Attuativo”), il presente Allegato definisce:

1) Piano di Attività

2) Lista dei Dati da implementare nel Registro dei Dati nel corso della
fase di Avvio e Sperimentazione

3) Verifica sui dati considerati nella fase di Avvio e Sperimentazione

A.1. Piano di Attività 
-----------------------

La costituzione dell’Ufficio Gestione Dati (UGD) avviene con la nomina
dei suoi componenti, con Decreto del Presidente dell’INGV.

Entro un mese dalla sua costituzione, l’UGD definisce e realizza lo
strumento per la gestione automatizzata del Registro, in conformità del
Capitolo 6.1 del “Documento Attuativo”.

Entro sei mesi dalla sua costituzione, l’UGD procede all’implementazione
di un primo gruppo di elementi individuati in Tabella 1 (30-40%) e
fornisce un rapporto preliminare ai Direttori di Dipartimento che
descriva lo stato di avanzamenti delle attività, definisca nel dettaglio
le attività di verifica (p.es., tipo e numero di test da effettuare) e
evidenzi le eventuali criticità riscontrate e le possibili soluzioni.

Entro dieci mesi, l’UGD completa l’implementazione degli elementi
individuati in Tabella 1 e avvia la fase di verifica.

Dodici mesi dopo la sua costituzione, l’UGD fornisce un rapporto finale
della fase di Avvio e Sperimentazione del Registro Dati che contiene:

a) Attività svolte (tempi, modi, personale / sezioni coinvolti, etc.)

b) Criticità riscontrate e soluzioni adottate

c) Proposte per il piano di gestione ordinaria del Registro dei Dati

A.2. Lista dei Dati 
--------------------

Gli elementi del Censimento dei dati dell’INGV ritenuti idonei per
essere utilizzati nella fase di Avvio e Sperimentazione del Registro dei
Dati sono riportati in Tabella 1. Ciò in applicazione dei criteri di
prioritizzazione definiti nel Capitolo 2.3.1 del “Documento Attuativo”.

A.3. Attività di verifica
-------------------------

Le attività di verifica del Registro dei Dati dovranno essere
finalizzate ad accertare l’effettiva operatività delle banche dati
implementate (nel rispetto delle regole di Accesso definite in Tabella
1) e la loro funzionalità nell’ambito del sistema di gestione dei dati
INGV (qualora già implementato). Nel caso in cui fosse previsto un
collegamento a banche dati esterne (come definite nel “Documento
Attuativo”), deve essere verificata anche la relativa interoperabilità.

TABELLA 1
---------

+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| **Rif. Censimento**   | **Nome**                                                                                              | **Responsabile dei Dati**                                                                                                                                  | **Responsabile Tecnico della Banca Dati**                                                                                                   | **Regole di Accesso**                                                                                                                                                                                                                   |
+=======================+=======================================================================================================+============================================================================================================================================================+=============================================================================================================================================+=========================================================================================================================================================================================================================================+
| DP.9                  | Bancadati registrazioni 30' GPS RING                                                                  | gianpaolo.cecere@ingv.it                                                                                                                                   | ciriaco.dambrosio@ingv.it                                                                                                                   | http://ring.gm.ingv.it/?page\_id=1223                                                                                                                                                                                                   |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.10                 | Bancadati soluzioni GPS                                                                               | analisigps@ingv.it                                                                                                                                         | luigi.falco@ingv.it                                                                                                                         | http://ring.gm.ingv.it/?page\_id=1223                                                                                                                                                                                                   |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.11                 | Serie temporali dello spostamento del suolo GPS                                                       | analisigps@ingv.it                                                                                                                                         | luigi.falco@ingv.it                                                                                                                         | http://ring.gm.ingv.it/?page\_id=1223                                                                                                                                                                                                   |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.12                 | Campi di velocità GPS                                                                                 | analisigps@ingv.it                                                                                                                                         | luigi.falco@ingv.it                                                                                                                         | http://ring.gm.ingv.it/?page\_id=1223                                                                                                                                                                                                   |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.13                 | Catalogo della Sismicità Italiana: fasi                                                               | barbara.castello@ingv.it                                                                                                                                   | patrizia.battelli@ingv.it                                                                                                                   | Open                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.14                 | Catalogo della Sismicità Italiana: localizzazioni                                                     | barbara.castello@ingv.it                                                                                                                                   | patrizia.battelli@ingv.it                                                                                                                   | Open                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.15                 | Catalogo della Sismicità strumentale Italiana:fasi                                                    | barbara.castello@ingv.it                                                                                                                                   | raffaele.distefano@ingv.it                                                                                                                  | Open/Authorized                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.16                 | Catalogo della Sismicità strumentale Italiana:localizzazioni                                          | barbara.castello@ingv.it                                                                                                                                   | raffaele.distefano@ingv.it                                                                                                                  | Open                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.17                 | Italian seismological instrumental and parametric data-base                                           | franco.mele@ingv.it                                                                                                                                        | andrea.bono@ingv.it; carlo.marcocci@ingv.it                                                                                                 | Open                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.18                 | Bollettino Sismico Italiano                                                                           | lucia.margheriti@ingv.it                                                                                                                                   | alessandro.marchetti@ingv.it; carlo.marcocci@ingv.it                                                                                        | Open                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.19                 | European Integrated Data Archive                                                                      | peter.danecek@ingv.it                                                                                                                                      | stefano.pintore@ingv.it; valentino.lauciani@ingv.it                                                                                         | Open                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.20                 | Time Domain Moment Tensor                                                                             | laura.scognamiglio@ingv.it                                                                                                                                 | matteo.quintiliani@ingv.it                                                                                                                  | Open                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.21                 | ShakeMaps                                                                                             | licia.faenza@ingv.it; alberto.michelini@ingv.it                                                                                                            | valentino.lauciani@ingv.it                                                                                                                  | Open                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.22                 | Rete Sismica Mobile                                                                                   | lucia.margheriti@ingv.it; milena.moretti@ingv.it; aladino.govoni@ingv.it; rmarco.massa@ingv.it; davide.piccinini@ingv.it; referenti dei singoli progetti   | aladino.govoni@ingv.it; simone.marzorati@ingv.it; luigi.falco@ingv.it; carlo.giunchi@ingv.it; ezio.dalema@ingv.it                           | n.d.                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.23                 | Stazioni accelerometriche/velocimetriche temporanee per emergenze gestite dal Coordinamento SISMIKO   | lucia.margheriti@ingv.it; milena.moretti@ingv.it;                                                                                                          | aladino.govoni@ingv.it (CNT-ROMA) ezio.d'alema@ingv.it (MI) simone.marzorati@ingv.it (CNT-ANCONA, luigi.falco@ingv.it (CNT-Grottaminarda)   | n.d.                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.27                 | Italian Accelerometric Archive                                                                        | lucia.luzi@ingv.it                                                                                                                                         | rodolfo.puglia@ingv.it                                                                                                                      | vedere licenza; download per utenti registrati                                                                                                                                                                                          |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.28                 | Italian Accelerometric Archive                                                                        | lucia.luzi@ingv.it                                                                                                                                         | rodolfo.puglia@ingv.it                                                                                                                      | vedere licenza; download per utenti registrati                                                                                                                                                                                          |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.29                 | Italian Accelerometric Archive                                                                        | lucia.luzi@ingv.it                                                                                                                                         | rodolfo.puglia@ingv.it                                                                                                                      | vedere licenza; download per utenti registrati                                                                                                                                                                                          |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.32                 | Database Macrosismico Italiano                                                                        | mario.locati@ingv.it                                                                                                                                       | mario.locati@ingv.it                                                                                                                        | http://emidius.mi.ingv.it/CPTI15-DBMI15/description\_DBMI15.htm                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.33                 | Catalogo Parametrico dei Terremoti Italiani                                                           | andrea.rovida@ingv.it                                                                                                                                      | mario.locati@ingv.it                                                                                                                        | http://emidius.mi.ingv.it/CPTI15-DBMI15/description\_CPTI15.htm                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.38                 | Engineering Strong-Motion database                                                                    | lucia.luzi@ingv.it                                                                                                                                         | rodolfo.puglia@ingv.it; maria.damico@ingv.it                                                                                                | vedere licenza; download per utenti registrati                                                                                                                                                                                          |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.39                 | Engineering Strong-Motion database                                                                    | lucia.luzi@ingv.it                                                                                                                                         | rodolfo.puglia@ingv.it; maria.damico@ingv.it                                                                                                | vedere licenza; download per utenti registrati                                                                                                                                                                                          |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.40                 | Engineering Strong-Motion database                                                                    | lucia.luzi@ingv.it                                                                                                                                         | rodolfo.puglia@ingv.it; maria.damico@ingv.it                                                                                                | vedere licenza; download per utenti registrati                                                                                                                                                                                          |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.41                 | European Archive of Historical Earthquake Data                                                        | andrea.rovida@ingv.it; mario.locati@ingv.it                                                                                                                | mario.locati@ingv.it                                                                                                                        | http://emidius.eu/AHEAD/introduction.php                                                                                                                                                                                                |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.42                 | SHARE European Earthquake Catalogue                                                                   | andrea.rovida@ingv.it                                                                                                                                      | mario.locati@ingv.it                                                                                                                        | http://www.emidius.eu/SHEEC/sheec\_1000\_1899.html                                                                                                                                                                                      |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.51                 | Campagne di monitoraggio per gli effetti di sito durante le emergenze sismiche                        | giovanna.cultrera@ingv.it; ezio.dalema@ingv.it                                                                                                             | ezio.dalema@ingv.it; gaetano.riccio@ingv.it; rocco.cogliano@ingv.it; fabrizio.cara@ingv.it; giuseppe.digiulio@ingv.it                       | Open Access con embargo della durata massima di 12 mesi dall'inserimento in EIDA                                                                                                                                                        |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.52                 | Campagne di monitoraggio per gli effetti di sito durante le emergenze sismiche                        | giovanna.cultrera@ingv.it; ezio.dalema@ingv.it                                                                                                             | ezio.dalema@ingv.it; gaetano.riccio@ingv.it; rocco.cogliano@ingv.it; fabrizio.cara@ingv.it; giuseppe.digiulio@ingv.it                       |                                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.53                 | Campagne di monitoraggio per gli effetti di sito durante le emergenze sismiche                        | giovanna.cultrera@ingv.it; ezio.dalema@ingv.it                                                                                                             | ezio.dalema@ingv.it; gaetano.riccio@ingv.it; rocco.cogliano@ingv.it; fabrizio.cara@ingv.it; giuseppe.digiulio@ingv.it                       |                                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.54                 | Quick Earthquake Survey Team                                                                          | andrea.tertulliani@ingv.it; raffaele.azzaro@ingv.it                                                                                                        | mario.locati@ingv.it; laura.graziani@ingv.it                                                                                                | dati sensibili, secretati a discrezione del DPC                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.60                 | Volcanic Observatory Reserved Access Database                                                         | placido.montalto@ingv.it                                                                                                                                   | placido.montalto@ingv.it; carmelo.cassisi@ingv.it                                                                                           | Autorizzato                                                                                                                                                                                                                             |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.73                 | Geoportale                                                                                            | emanuela.debeni@ingv.it; stefano.branca@ingv.it; mauro.coltelli@ingv.it                                                                                    | placido.montalto@ingv.it                                                                                                                    | Autorizzato                                                                                                                                                                                                                             |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.97                 | Catalogo Macrosismico dei Terremoti Etnei                                                             | raffaele.azzaro@ingv.it                                                                                                                                    | salvatore.damico@ingv.it                                                                                                                    | Public Web Site                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.101                | SICILY AND SOUTHERN CALABRIA FOCAL MECHANISMS CATALOG                                                 | luciano.scarfi@ingv.it                                                                                                                                     | carmelo.cassisi@ingv.it                                                                                                                     | Visibile sul web con due livelli: 1) utenti non registrati > visibilità mappa MF + parametri in una finestra pop-up per ciascun meccanismo; 2) utenti registrati> possibilità di download della tabella con i parametri di tutti i MF   |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.105                | FLAME-Rete UVScanner per misura flusso SO2-Etna                                                       | giuseppe.salerno@ingv.it                                                                                                                                   | carmelo.cassisi@ingv.it; tommaso.caltabiano@ingv.it                                                                                         | Interno alla Sezione e Sala Operativa                                                                                                                                                                                                   |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.115                | DB\_SUM\_EQ                                                                                           | patrizia.ricciolino@ingv.it                                                                                                                                | giovanni.scarpato@ingv.it; rosario.peluso@ingv.it                                                                                           | Autorizzato                                                                                                                                                                                                                             |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.116                | DBSeis\_GeoVes                                                                                        | patrizia.ricciolino@ingv.it                                                                                                                                | giovanni.scarpato@ingv.it; rosario.peluso@ingv.it                                                                                           | Autorizzato                                                                                                                                                                                                                             |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.125                | Rete Sismica Mobile OV                                                                                | paola.cusano@ingv.it                                                                                                                                       | danilo.galluzzo@ingv.it                                                                                                                     | n.d.                                                                                                                                                                                                                                    |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.166                | Mappe di scenari di invasione PDC al Vesuvio e Campi Flegrei                                          | augusto.neri@ingv.it                                                                                                                                       | tomaso.espostiongaro@ingv.it                                                                                                                | accessible (password-protected) to DPC and scientific team                                                                                                                                                                              |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.178                | Rrisultati di pericolosità probabilistica (vulcani, terremoti, tsunami) e di rischio                  | jacopo.selva@ingv.it                                                                                                                                       | paolo.perfetti@ingv.it                                                                                                                      | da definire                                                                                                                                                                                                                             |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.179                | Rete acque ETNA                                                                                       | francesco.italiano@ingv.it                                                                                                                                 | andrea.mastrolia@ingv.it                                                                                                                    |                                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.180                | Rete flusso CO2 ETNA                                                                                  | francesco.italiano@ingv.it                                                                                                                                 | andrea.mastrolia@ingv.it                                                                                                                    |                                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.181                | Rete CO2/SO2 Etna                                                                                     | francesco.italiano@ingv.it                                                                                                                                 | andrea.mastrolia@ingv.it                                                                                                                    |                                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.184                | Rete acque Vulcano                                                                                    | francesco.italiano@ingv.it                                                                                                                                 | andrea.mastrolia@ingv.it                                                                                                                    |                                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.185                | Rete CO2 Stromboli                                                                                    | francesco.italiano@ingv.it                                                                                                                                 | andrea.mastrolia@ingv.it                                                                                                                    |                                                                                                                                                                                                                                         |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.257                | Geochimica delle acque sotterranee in aree sismiche (Italia, Grecia, Turchia) e vulcaniche (Italia)   | luca.pizzino@ingv.it                                                                                                                                       |                                                                                                                                             | da definire (attualmente non pubblici, a parte i dati rivisti e/o acquisiti all'interno dei progetti Vigor e Atlante)                                                                                                                   |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.235                | Database of Individual Seismogenic Sources                                                            | gianluca.valensise@ingv.it                                                                                                                                 | roberto.basili@ingv.it                                                                                                                      | libero                                                                                                                                                                                                                                  |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.236                | European Database of Seismogenic Faults                                                               | roberto.basili@ingv.it                                                                                                                                     | roberto.basili@ingv.it                                                                                                                      | libero                                                                                                                                                                                                                                  |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.264                | Operational Earthquake Forecast                                                                       | warner.marzocchi@ingv.it                                                                                                                                   | giuseppe.falcone@ingv.it                                                                                                                    | autorizzato                                                                                                                                                                                                                             |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.275                | Italian Present-day Stress Indicators                                                                 | paola.montone@ingv.it; mariateresa.mariucci@ingv.it                                                                                                        | gabriele.tarabusi@ingv.it; mariateresa.mariucci@ingv.it                                                                                     | libero                                                                                                                                                                                                                                  |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| DP.222                | Multidisciplinary Oceanic Information SysTem                                                          | laura.beranzoli@ingv.it                                                                                                                                    | nicola.marcucci@ingv.it                                                                                                                     | anonymous per i metadati e i dati (a basso samplig rate). Su richiesta per i dati ad alto sampling rate                                                                                                                                 |
+-----------------------+-------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

.. [1]
       Regolamento (UE) 2016/679 del 27 aprile 2016, General Data
       Protection Regulation (GDPR).

.. [2]
       Direttiva 96/9/CE del Parlamento e del Consiglio europeo dell'11
       marzo 1996, sulla tutela giuridica delle banche di dati.

.. [3]
       D.Lgs. 6 maggio 1999, n. 169. Attuazione della direttiva 96/9/CE
       relativa alla tutela giuridica delle banche di dati.

.. [4]
       Legge del 22 aprile 1941, n. 633. Protezione del diritto d'autore
       e di altri diritti connessi al suo esercizio.

.. [5]
       Sono escluse dalla definizione di dati le informazioni relative a
       persone fisiche o giuridiche, enti o associazioni, identificati o
       identificabili, anche indirettamente, mediante riferimento a
       qualsiasi altra informazione, ivi compreso un numero di
       identificazione personale. Sono altresì esclusi i dati relativi
       al bilancio, al protocollo e alla gestione documentale.

.. [6]
       Direttiva 2007/2/CE del Parlamento europeo e del Consiglio, del
       14 marzo 2007, che istituisce un'Infrastruttura per
       l'informazione territoriale nella Comunità europea (INSPIRE).
       Definizione: “dati che attengono, direttamente o indirettamente,
       a una località o un'area geografica specifica”.

.. [7]
       D.Lgs 7 marzo 2005, n. 82. Codice dell'Amministrazione Digitale
       (CAD). Art. 68, comma 3, definisce dati digitali di tipo aperto
       quelli che: 1) sono disponibili secondo i termini di una licenza
       che ne permetta l'utilizzo da parte di chiunque, anche per
       finalità commerciali, in formato disaggregato; 2) sono
       accessibili attraverso le tecnologie dell'informazione e della
       comunicazione, ivi comprese le reti telematiche pubbliche e
       private, in formati aperti, sono adatti all'utilizzo automatico
       da parte di programmi per elaboratori e sono provvisti dei
       relativi metadati; 3) sono resi disponibili gratuitamente
       attraverso le tecnologie dell'informazione e della comunicazione,
       ivi comprese le reti telematiche pubbliche e private, oppure sono
       resi disponibili ai costi marginali sostenuti per la loro
       riproduzione e divulgazione.

.. [8]
       Licenze Creative Commons. https://creativecommons.org/licenses/

.. [9]
       D.Lgs. 7 marzo 2005, n. 82. Codice dell'Amministrazione Digitale
       (CAD) (con modificazioni introdotte dal D.Lgs. 26 agosto 2016 n.
       179, Art.1, comma g). Capo I, Art.1, comma bb.

.. [10]
       Allegato 1 alla convenzione "A" del 2017 tra il Dipartimento
       della Protezione Civile e l'Istituto Nazionale di Geofisica e
       Vulcanologia.

.. [11]
       D.Lgs. 7 marzo 2005, n. 82. Codice dell'Amministrazione Digitale
       (CAD). Capo V, Art.50, Comma 3-bis.

.. [12]
       D.Lgs. 14 marzo 2013 n. 33 e s.m.i, Riordino della disciplina
       riguardante il diritto di accesso civico e gli obblighi di
       pubblicità, trasparenza e diffusione di informazioni da parte
       delle pubbliche amministrazioni.

.. [13]
       D.Lgs. 7 marzo 2005, n. 82. Codice dell'Amministrazione Digitale
       (CAD). art.1, comma 1, lett. l-ter.

.. [14]
       Decreto n.424 del Consiglio di Amministrazione INGV del 15
       settembre 2017, come da Gazzetta Ufficiale n.27 del 2 settembre
       2018.

.. [15]
       OpenAire. Guidelines for Data Archives.

.. [16]
       Agenzia Digitale per l’Italia. Linee Guida per i cataloghi dati.

.. [17]
       Well-known text, ISO/IEC 13249-3:2016,
       https://en.wikipedia.org/wiki/Well-known\_text

.. [18]
       OpenAire. OpenAIRE Guidelines for Data Archives.

.. [19]
       5 stars Open Data. http://5stardata.info

.. [20]
       OpenAire. Guidelines for Data Archives.

.. [21]
       Agenzia Digitale per l'Italia (2017). Linee Guida Nazionali per
       la Valorizzazione del Patrimonio Informativo Pubblico.

.. [22]
       D.Lgs. 7 marzo 2005, n. 82. Codice dell'Amministrazione Digitale
       (CAD). Art. 59, Comma 5.

.. [23]
       Decreto della Presidenza del Consiglio dei Ministri 10 novembre
       2011. Art.3, Comma 1. Elenco in Allegato 1.

.. [24]
       Decreto del Ministero dell'Istruzione, dell'Università e della
       Ricerca del 7 giugno 2016, n. 120.

.. [25]
       ANVUR, Progetto IRIDE.

.. [26]
       D.Lgs. 7 marzo 2005 n. 82. Codice dell'amministrazione digitale
       (CAD). Art.52, comma 2.

.. [27]
       D.Lgs. 24 gennaio 2006, n.36. Art.5, Comma 1, *“[…] Il titolare
       del dato adotta prioritariamente licenze aperte standard […]”*.
       Art.2, Comma h, *"licenza standard per il riutilizzo: il
       contratto, o altro strumento negoziale, redatto ove possibile in
       forma elettronica, nel quale sono definite le modalità di
       riutilizzo dei documenti delle pubbliche amministrazioni o degli
       organismi di diritto pubblico"*.

.. [28]
       D.Lgs. 30 marzo 2001 n. 165, comma 2. I soggetti titolati
       all’apposizione di licenze ai dati sono le amministrazioni
       pubbliche, intese come *“tutte le amministrazioni dello Stato,
       ivi compresi gli istituti e scuole di ogni ordine e grado e le
       istituzioni educative, le aziende ed amministrazioni dello Stato
       ad ordinamento autonomo, le Regioni, le Province, i Comuni, le
       Comunità montane e loro consorzi e associazioni, le istituzioni
       universitarie, gli Istituti autonomi case popolari, le Camere di
       commercio, industria, artigianato e agricoltura e loro
       associazioni, tutti gli enti pubblici non economici nazionali,
       regionali e locali, le amministrazioni, le aziende e gli enti del
       Servizio sanitario nazionale l'Agenzia per la rappresentanza
       negoziale delle pubbliche amministrazioni (ARAN) e le Agenzie di
       cui al decreto legislativo 30 luglio 1999, n. 300. Fino alla
       revisione organica della disciplina di settore, le disposizioni
       di cui al presente decreto continuano ad applicarsi anche al
       CONI”*.

.. [29]
       European Commission notice (2014/C 240/01). Guidelines on
       recommended standard licences, datasets and charging for the
       reuse of documents.

.. [30]
       Creative Commons. https://creativecommons.org/

.. [31]
       D.Lgs. 7 marzo 2005 n. 8, Art.68, comma 3, lettera b

.. [32]
       Creative Commons Attribution 4.0 International (CC BY 4.0).
       https://creativecommons.org/licenses/by/4.0/

.. [33]
       D.Lgs. 7 marzo 2005 n. 82, Art. 1, comma cc, così come modificato
       dal D.Lgs. 26 agosto 2016 n. 179, Art.1, comma g

.. [34]
       Creative Commons Licenses.
       https://wiki.creativecommons.org/wiki/License\_Versions

.. [35]
       Datacite. Metadata Schema. https://schema.datacite.org/

.. [36]
       Directive 2007/2/EC of the European Parliament and of the Council
       of 14 March 2007 establishing an Infrastructure for Spatial
       Information in the European Community (INSPIRE),
       http://eur-lex.europa.eu/legal-content/EN/ALL/?uri=celex:32007L0002

.. [37]
       Position Statement on Research Information Systems, November
       2016,
       https://www.scienceeurope.org/wp-content/uploads/2016/11/SE\_PositionStatement\_RIS\_WEB.pdf

.. [38]
   DataCite. https://www.datacite.org/

.. [39]
   DataCite metadata schema. https://schema.datacite.org/

.. [40]
   International DOI Foundation. DOI Handbook.
   https://www.doi.org/hb.html

.. [41]
   DataCite. Metadata schema. https://schema.datacite.org/

.. [42]
   Smith AM, Katz DS, Niemeyer KE, FORCE11 Software Citation Working
   Group (2016). Software citation principles. PeerJ Computer Science.
   https://doi.org/10.7717/peerj-cs.86

.. [43]
   Handle Registry. https://www.handle.net/

.. [44]
   Rauber A., Asmi A., van Uytvanck D., Pröll S. (2015). Data Citation
   of Evolving Data.
   https://rd-alliance.org/system/files/documents/RDA-DC-Recommendations\_150924.pdf

.. [45]
   Klump J. and Huber R. (2016). DOI for geoscience data - how early
   practices shape present perceptions. Earth Science Informatics, 9(1):
   123-136. https://doi.org/10.1007/s12145-015-0231-5

.. [46]
   Huber R., Asmi A., Buck J., De Luca J.M., Diepenbroek D., Michelini
   A. (2015). Data citation and digital identifiers for time series data
   / environmental research infrastructures. Joint COOPEUS/ENVRI/EUDAT
   PID workshop, Bremen, 25-26 June 2013.
   https://doi.org/10.6084/m9.figshare.1285728.v1

.. [47]
   D.Lgs 7 marzo 2005, n. 82. Codice dell'Amministrazione Digitale
   (CAD). Art. 59 "Dati territoriali".

.. [48]
   D.Lgs 7 marzo 2005, n. 82. Codice dell'Amministrazione Digitale
   (CAD). Art. 60 "Base di dati di interesse nazionale".

.. [49]
   D.M. 10 novembre 2011, Regole tecniche per la definizione del
   contenuto del Repertorio nazionale dei dati territoriali, nonché
   delle modalità di prima costituzione e di aggiornamento dello stesso.
   http://www.gazzettaufficiale.it/eli/id/2012/02/27/12A01801/sg

.. [50]
   http://istituto.ingv.it/images/Convenzioni\_DPC/convenzione\_dpc\_Allegato\_A\_2018.pdf

.. [51]
   Guida operativa per l’accreditamento delle Pubbliche Amministrazioni,
   versione 2.0 del 2014,
   http://www.rndt.gov.it/RNDT/home/images/RNDT_guida_operativa_accreditamento_v2.0_20140725.pdf

.. [52]
   ISO Technical Committee on digital geographic information,
   https://committee.iso.org/home/tc211

.. [53]
   | Commission Regulation (EC) No 1205/2008 of 3 December 2008
     implementing Directive 2007/2/EC of the European Parliament and of
     the Council as regards metadata.
   | http://eur-lex.europa.eu/legal-content/EN/ALL/?uri=CELEX:32008R1205

.. [54]
   Repertorio Nazionale dei Dati Territoriali, http://www.rndt.gov.it

.. [55]
   Le Linee Guida Nazionali per la Valorizzazione del Patrimonio
   Informativo Pubblico
   (`*http://lg-patrimonio-pubblico.readthedocs.io/* <http://lg-patrimonio-pubblico.readthedocs.io/>`__)
   raccomandano l’individuazione di “\ *una chiara data governance
   interna con professionalità strategiche e specifiche*\ ” e auspicano
   l’istituzione di un “\ *Gruppo di Lavoro Open Data (Team Open
   Data)”*. Nel caso INGV, l’Ufficio Gestione Dati svolge anche il ruolo
   del *Gruppo di Lavoro Open Data.* Le Linee Guida AgID precisano
   inoltre che “\ *affinché il lavoro del Team Open Data possa essere
   incisivo all’interno dell’Amministrazione, è importante che tale team
   si confronti con il livello più politico, sia per ottenere da questo
   le necessarie “spinte”, sia per offrire al decisore politico proposte
   e stimoli*\ ”

.. [56]
   ai sensi del D.lgs. n. 33/2013 e s.m.i.

.. |https://ssl.gstatic.com/ui/v1/icons/mail/images/cleardot.gif| image:: media/image1.gif
.. |Senza nome-1| image:: media/image2.png
   :width: 6.21298in
   :height: 4.15526in
.. |Regolamento DOI| image:: media/image3.png
   :width: 5.78542in
   :height: 7.82222in
.. |image3| image:: media/image4.png
   :width: 3.26958in
   :height: 1.24653in

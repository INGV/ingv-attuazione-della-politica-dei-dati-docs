Registri di Metadati non Gestiti da INGV
========================================

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

Requisiti della *Landing Page*
------------------------------

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

Identificativi DOI
------------------

    L’UGD assocerà, laddove possibile, ogni elemento del Registro Dati a
    un identificativo persistente DOI inserendo i relativi metadati nel
    registro DataCite [38]_.

Linee Guida per l'Assegnazione
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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

.. image:: ../images/esempioDOI.jpg
   :name: esempioDOI
   :alt: Esempio di DOI basato sul codice con prefisso CRUI.
   :align:  center 
   :width: 480 px

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

Linee Guida per la Compilazione di Metadati DataCite
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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
obbligatoria (:ref:`Tabella 2 <Tabella-2>`), cioè la cui presenza è vincolante per
l’inserimento di Dati nel Registro, e metadati a compilazione
facoltativa (:ref:`Tabella 3 <Tabella-3>`).

I metadati vanno redatti in formato XML; se possibile, l’UGD renderà
disponibili opportuni strumenti per semplificare il processo di
compilazione di tale file.

.. table:: Tabella 2 - Metadati a compilazione obbligatoria.
   :name: Tabella-2

+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Etichetta (tag)    | Occorr.     | Definizione secondo DataCite (v4.1)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Contenuto                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
+====================+=============+==============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================+==================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================+
| Identifier         | 1           | The Identifier is a unique string that identifies a resource. For software, determine whether the identifier is for a specific version of a piece of software, (per the Force11 Software Citation Principles), or for all versions.                                                                                                                                                                                                                                                                                         	| Compilato con il codice DOI assegnato.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Title              | 1           | A name or title by which a resource is known. May be the title of a dataset or the name of a piece of software.                                                                                                                                                                                                                                                                                                                                                                                                             	| Titolo in lingua inglese; l'eventuale acronimo si aggiunge tra parentesi. E’ possibile specificare il titolo tradotto in altre lingue usando l’attributo “TranslatedTitle”.                                                                                                                                                                                                                                                                                                                                                                                                                                  	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Publication Year   | 1           | The year when the data was or will be made publicly available. In the case of resources such as software or dynamic data where there may be multiple releases in one year, include the Date/dateType/dateInformation property and sub-properties to provide more information about the publication or release date details.                                                                                                                                                                                                 	| Anno di prima pubblicazione dei dati.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Resource Type     	| 1       	| A description of the resource.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              	| Ai fini del Registro Dati solitamente è compilato con “Dataset”. Lo schema DataCite lascia libera la compilazione del campo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Description       	| 1-n     	| All additional information that does not fit in any of the other categories. May be used for technical information.                                                                                                                                                                                                                                                                                                                                                                                                         	| Descrizione testuale dei dati concisa e chiara in lingua inglese. Aggiungere l’attributo “DescriptionType” compilato con “Abstract”. E’ possibile aggiungere altre tipologie di descrizioni: "Methods", "SeriesInformation", "TableOfContents", "TechnicalInfo".                                                                                                                                                                                                                                                                                                                                             	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Subject           	| 1-n     	| Subject, keyword, classification code, or key phrase describing the resource.                                                                                                                                                                                                                                                                                                                                                                                                                                               	| Compilazione libera, con l’accortezza di specificare l’attributo “SubjectScheme” in cui viene indicato lo schema di classificazione utilizzato.                                                                                                                                                                                                                                                                                                                                                                                                                                                              	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| GeoLocation       	| 1-n     	| Spatial region or named place where the data was gathered or about which the data is focused.                                                                                                                                                                                                                                                                                                                                                                                                                               	| E’ possibile specificare una serie di “GeoLocationPlace”, e/o una serie di “GeoLocationPolygon”, e/o una serie di “GeoLocationPolygon”.                                                                                                                                                                                                                                                                                                                                                                                                                                                                      	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Publisher         	| 1       	| The name of the entity that holds, archives, publishes prints, distributes, releases, issues, or produces the resource. This property will be used to formulate the citation, so consider the prominence of the role. For software, use Publisher for the code repository. If there is an entity other than a code repository, that "holds, archives, publishes, prints, distributes, releases, issues, or produces" the code, use the property Contributor / contributorType / hostingInstitution for the code repository. 	| Inserire il nome dell’Istituto che rende disponibile i dati. Il campo viene compilato con “Istituto Nazionale di Geofisica e Vulcanologia (INGV)”.                                                                                                                                                                                                                                                                                                                                                                                                                                                           	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Creator           	| 1-n     	| The main researchers involved in producing the data, or the authors of the publication, in priority order.                                                                                                                                                                                                                                                                                                                                                                                                                  	| Elencare i principali responsabili scientifici e/o tecnologici, indicando per ciascuno l’affiliazione e il codice identificativo ORCID. Oltre ai principali responsabili è anche possibile inserire un riferimento generico al gruppo di lavoro.                                                                                                                                                                                                                                                                                                                                                             	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Contributor       	| 1-n     	| The institution or person responsible for collecting, managing, distributing, or otherwise contributing to the development of the resource. To supply multiple contributors, repeat this property. For software, if there is an alternate entity that "holds, archives, publishes, prints, distributes, releases, issues, or produces" the code, use the contributorType "hostingInstitution" for the code repository.                                                                                                      	| Elencare le persone che hanno contribuito ai dati, identificando per ciascuno il ruolo svolto, l’affiliazione e il codice ORCID. E’ possibile aggiungere anche istituzioni. Settare l’attributo “nameType” “personal” per le persone e “organizational” per le istituzioni. I ruoli previsti sono: ContactPerson, DataCollector, DataCurator, DataManager, Distributor, Editor, HostingInstitution, Other, Producer, ProjectLeader, ProjectManager, ProjectMember, RegistrationAgency, RegistrationAuthority, RelatedPerson, ResearchGroup, RightsHolder, Researcher, Sponsor, Supervisor, WorkPackageLeader     |
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Rights            	| 1       	| Any rights information for this resource                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    	| Tipologia di licenza Creative Commons.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Funding Reference 	| 1-n     	| Information about financial support (funding) for the resource being registered                                                                                                                                                                                                                                                                                                                                                                                                                                             	| Elenco delle istituzioni che hanno finanziato la creazione dei dati.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Date              	| 0-1     	| Different dates relevant to the work. The attribute 'dateType' may contains: Accepted, Available, Copyrighted, Collected, Created, Issued, Submitted, Updated, Valid.                                                                                                                                                                                                                                                                                                                                                       	| Se disponibili, compilare con le date relative.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              	|
+--------------------+-------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

.. table:: Tabella 3 - Metadati a compilazione facoltativa.
   :name: Tabella-3

| Etichetta (Tag)      | Occorr | Descrizione fornita da DataCite                                                                                                                                                                                                                                                                                                         | Contenuto                                                                                                                                                                                                                          |
|----------------------|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Language             | 0-1    | The primary language of the resource.                                                                                                                                                                                                                                                                                                   | Compilare con la dizione inglese della lingua con cui i dati sono pubblicamente disponibili i dati.                                                                                                                                |
| Alternate Identifier | 0-n    | An identifier or identifiers other than the primary Identifier applied to the resource being registered. This may be any alphanumeric string which is unique within its domain of issue. May be used for local identifiers. Alternate Identifier should be used for another identifier of the same instance (same location, same file). | Se i dati associati al DOI sono anche associati ad altri identificativi è possibile usare questo tag per stabilire un collegamento.                                                                                                |
| Related Identifier   | 0-n    | Identifiers of related resources. These must be globally unique identifiers.                                                                                                                                                                                                                                                            | Se i dati hanno delle relazioni –di qualunque natura- con altri prodotti della ricerca associati ad identificativi è possibile usare questo tag per stabilire un collegamento. Si veda l’elenco delle relazioni ammesse a seguire. |
| Size                 | 0-n    | Size (e.g. bytes, pages, inches, etc.) or duration (extent), e.g. hours, minutes, days, etc., of a resource.                                                                                                                                                                                                                            | Se è possibile quantificare i dati, compilare questo campo.                                                                                                                                                                        |
| Format               | 0-n    | Technical format of the resource. Use file extension or MIME type where possible.                                                                                                                                                                                                                                                       | Se i dati sono disponibili in uno o più standard di codifica di dati, indicare qui i formati.                                                                                                                                      |

Relazioni con altri prodotti della ricerca
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Lo schema di metadati DataCite permette di collegare l’identificativo
DOI ad altre risorse digitali. Nel tag “relatedIdentifier” demandato a
stabilire tali collegamenti è possibile specificare nell’attributo
“relatedIdentifierType” una delle seguenti tipologie di identificativi:
ARK, arXiv, bibcode, DOI, EAN13, EISSN, Handle, IGSN, ISBN, ISSN, ISTC,
LISSN, LSID, PMID, PURL, UPC, URL, URN. La tipologia di relazione tra il
DOI e un’altra risorsa digitale si specifica tramite l’attributo
“relationType”. In :ref:`Tabella 4<Tabella-4>` si riportano le relazioni ammesse in cui
(A) rappresenta l’oggetto associato al DOI, e (B) l’elemento che si sta
collegando.

.. table:: Tabella 4 – Elenco delle tipologie di relazioni ammesse dallo schema di metadati DataCite.
   :name: Tabella-4

| Tipo di relazione   | Descrizione fornita da DataCite                                                                                          |
|---------------------|--------------------------------------------------------------------------------------------------------------------------|
| IsCitedBy           | Indicates that B includes A in a citation                                                                                |
| Cites               | Indicates that A includes B in a citation                                                                                |
| IsSupplementTo      | Indicates that A is a supplement to B                                                                                    |
| IsSupplementedBy    | Indicates that B is a supplement to A                                                                                    |
| IsContinuedBy       | Indicates A is continued by the work B                                                                                   |
| Continues           | Indicates A is a continuation of the work B                                                                              |
| Describes           | Indicates A describes B                                                                                                  |
| IsDescribedBy       | Indicates A is described by B                                                                                            |
| HasMetadata         | Indicates resource A has additional metadata B                                                                           |
| IsMetadataFor       | Indicates additional metadata A for a resource B                                                                         |
| HasVersion          | Indicates A has a version (B)                                                                                            |
| IsVersionOf         | Indicates A is a version of B                                                                                            |
| IsNewVersionOf      | Indicates A is a new edition of B, where the new edition has been modified or updated                                    |
| IsPreviousVersionOf | Indicates A is a previous edition of B                                                                                   |
| IsPartOf            | Indicates A is a portion of B; may be used for elements of a series                                                      |
| HasPart             | Indicates A includes the part B                                                                                          |
| IsReferencedBy      | Indicates A is used as a source of information by B                                                                      |
| References          | Indicates B is used as a source of information for A                                                                     |
| IsDocumentedBy      | Indicates B is documentation about or explaining A                                                                       |
| Documents           | Indicates A is documentation about B                                                                                     |
| IsCompiledBy        | Indicates B is used to compile or create A                                                                               |
| Compiles            | Indicates B is the result of a compile or creation event using A                                                         |
| IsVariantFormOf     | Indicates A is a variant or different form of B                                                                          |
| IsOriginalFormOf    | Indicates A is the original form of B                                                                                    |
| IsIdenticalTo       | Indicates that A is identical to B, for use when there is a need to register two separate instances of the same resource |
| IsReviewedBy        | Indicates that A is reviewed by B                                                                                        |
| Reviews             | Indicates that A is a review of B                                                                                        |
| IsDerivedFrom       | Indicates B is a source upon which A is based                                                                            |
| IsSourceOf          | Indicates A is a source upon which B is based                                                                            |
| IsRequiredBy        | Indicates A is required by B                                                                                             |
| Requires            | Indicates A requires B                                                                                                   |

Identificazione di Frammenti di Dati Complessi
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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

Il Repertorio Nazionale dei Dati Territoriali (RNDT)
----------------------------------------------------

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

Dati territoriali d’interesse generale 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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

Linee Guida per la Compilazione di Metadati RNDT
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

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
   Repertorio Nazionale dei Dati Territoriali, http://www.rndt.gov.it.gov.it

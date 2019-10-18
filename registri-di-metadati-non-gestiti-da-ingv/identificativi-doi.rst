5.2 Identificativi DOI
======================

L’UGD assocerà, laddove possibile, ogni elemento del Registro Dati a un
identificativo persistente DOI inserendo i relativi metadati nel
registro DataCite [1]_.

5.2.1 Linee Guida per l'Assegnazione
------------------------------------

L’assegnazione è vincolata da una serie di condizioni inderogabili in
quanto deve essere:

-  disponibile una pagina Web da associare, detta *Landing Page*;

-  possibile recuperare i dati direttamente dalla L\ *anding Page*;

-  associata una licenza *Creative Commons* al dato identificato;

-  compilato l’elenco dei metadati secondo lo schema DataCite [2]_.

La convenzione stipulata nel 2013 tra INGV e CRUI rende disponibili due
prefissi DOI:

-  “10.6092/INGV.IT-” un sotto-codice del prefisso CRUI, condiviso con
   altre istituzioni, e con un esplicito riferimento a INGV;

-  “10.13127” un prefisso neutro ad uso esclusivo INGV.

L'identificativo DOI è strutturato con un prefisso e un suffisso, qui un
esempio basato sul codice con prefisso CRUI:

|image0|

Di seguito le linee guida per l’assegnazione degli identificativi,
redatte prendendo in considerazione le indicazioni contenute nel *"DOI
Handbook"*\  [3]_.

Il codice “10.6092/INGV.IT-” va utilizzato per i dati la cui titolarità
è dell’INGV in modo esclusivo e la cui copertura geografica sia di
interesse prettamente nazionale. I codici DOI basati su questo prefisso
devono rispettare questa struttura:

10.6092/INGV.IT/< gruppo-dati>/<identificativo specifico>

Il prefisso "10.13127/" va utilizzato quando è auspicabile l'uso di un
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
“sottolineato” (“_”).

Al fine di diffondere l’uso dei codici, si suggerisce di aggiungere
sempre il riferimento al codice DOI in presentazioni, *abstract*,
poster, rapporti tecnici, social networks e soprattutto nelle
pubblicazioni. Per un uso più funzionale, si consiglia di presentare il
codice nella forma di indirizzo risolvibile (es.:
http://doi.org/10.13127/xxxx).

5.2.2 Linee Guida per la Compilazione di Metadati DataCite
----------------------------------------------------------

I metadati da associare all'identificativo DOI adottano lo schema
DataCite [4]_ nella sua più recente versione. Il presente documento fa
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

+-----------------+-----------------+-----------------+-----------------+
| Etichetta (tag) | Occorr.         | Definizione     | Contenuto       |
|                 |                 | secondo         |                 |
|                 |                 | DataCite (v4.1) |                 |
+-----------------+-----------------+-----------------+-----------------+
| *Identifier*    | 1               | *The Identifier | Compilato con   |
|                 |                 | is a unique     | il codice DOI   |
|                 |                 | string that     | assegnato.      |
|                 |                 | identifies a    |                 |
|                 |                 | resource. For   |                 |
|                 |                 | software,       |                 |
|                 |                 | determine       |                 |
|                 |                 | whether the     |                 |
|                 |                 | identifier is   |                 |
|                 |                 | for a specific  |                 |
|                 |                 | version of a    |                 |
|                 |                 | piece of        |                 |
|                 |                 | software, (per  |                 |
|                 |                 | the Force11     |                 |
|                 |                 | Software        |                 |
|                 |                 | Citation        |                 |
|                 |                 | Principles*\  [ |                 |
|                 |                 | 6]_\ *),        |                 |
|                 |                 | or for all      |                 |
|                 |                 | versions.*      |                 |
+-----------------+-----------------+-----------------+-----------------+
| *Title*         | 1               | *A name or      | Titolo in       |
|                 |                 | title by which  | lingua inglese; |
|                 |                 | a resource is   | l'eventuale     |
|                 |                 | known. May be   | acronimo si     |
|                 |                 | the title of a  | aggiunge tra    |
|                 |                 | dataset or the  | parentesi. E’   |
|                 |                 | name of a piece | possibile       |
|                 |                 | of software.*   | specificare il  |
|                 |                 |                 | titolo tradotto |
|                 |                 |                 | in altre lingue |
|                 |                 |                 | usando          |
|                 |                 |                 | l’attributo     |
|                 |                 |                 | “\ *TranslatedT |
|                 |                 |                 | itle*\ ”.       |
+-----------------+-----------------+-----------------+-----------------+
| *Publication    | 1               | *The year when  | Anno di prima   |
| Year*           |                 | the data was or | pubblicazione   |
|                 |                 | will be made    | dei dati.       |
|                 |                 | publicly        |                 |
|                 |                 | available. In   |                 |
|                 |                 | the case of     |                 |
|                 |                 | resources such  |                 |
|                 |                 | as software or  |                 |
|                 |                 | dynamic data    |                 |
|                 |                 | where there may |                 |
|                 |                 | be multiple     |                 |
|                 |                 | releases in one |                 |
|                 |                 | year, include   |                 |
|                 |                 | the             |                 |
|                 |                 | Date/dateType/d |                 |
|                 |                 | ateInformation  |                 |
|                 |                 | property and    |                 |
|                 |                 | sub-properties  |                 |
|                 |                 | to provide more |                 |
|                 |                 | information     |                 |
|                 |                 | about the       |                 |
|                 |                 | publication or  |                 |
|                 |                 | release date    |                 |
|                 |                 | details.*       |                 |
+-----------------+-----------------+-----------------+-----------------+
| *Resource Type* | 1               | *A description  | Ai fini del     |
|                 |                 | of the          | Registro Dati   |
|                 |                 | resource.*      | solitamente è   |
|                 |                 |                 | compilato con   |
|                 |                 |                 | “Dataset”. Lo   |
|                 |                 |                 | schema DataCite |
|                 |                 |                 | lascia libera   |
|                 |                 |                 | la compilazione |
|                 |                 |                 | del campo.      |
+-----------------+-----------------+-----------------+-----------------+
| *Description*   | 1-n             | *All additional | Descrizione     |
|                 |                 | information     | testuale dei    |
|                 |                 | that does not   | dati concisa e  |
|                 |                 | fit in any of   | chiara in       |
|                 |                 | the other       | lingua inglese. |
|                 |                 | categories. May | Aggiungere      |
|                 |                 | be used for     | l’attributo     |
|                 |                 | technical       | “\ *Description |
|                 |                 | information.*   | Type*\ ”        |
|                 |                 |                 | compilato con   |
|                 |                 |                 | “\ *Abstract*\  |
|                 |                 |                 | ”.              |
|                 |                 |                 | E’ possibile    |
|                 |                 |                 | aggiungere      |
|                 |                 |                 | altre tipologie |
|                 |                 |                 | di descrizioni: |
|                 |                 |                 | "*Methods*",    |
|                 |                 |                 | "*SeriesInforma |
|                 |                 |                 | tion*",         |
|                 |                 |                 | "*TableOfConten |
|                 |                 |                 | ts*",           |
|                 |                 |                 | "*TechnicalInfo |
|                 |                 |                 | *".             |
+-----------------+-----------------+-----------------+-----------------+
| *Subject*       | 1-n             | *Subject,       | Compilazione    |
|                 |                 | keyword,        | libera, con     |
|                 |                 | classification  | l’accortezza di |
|                 |                 | code, or key    | specificare     |
|                 |                 | phrase          | l’attributo     |
|                 |                 | describing the  | “\ *SubjectSche |
|                 |                 | resource.*      | me*\ ”          |
|                 |                 |                 | in cui viene    |
|                 |                 |                 | indicato lo     |
|                 |                 |                 | schema di       |
|                 |                 |                 | classificazione |
|                 |                 |                 | utilizzato.     |
+-----------------+-----------------+-----------------+-----------------+
| *GeoLocation*   | 1-n             | *Spatial region | E’ possibile    |
|                 |                 | or named place  | specificare una |
|                 |                 | where the data  | serie di        |
|                 |                 | was gathered or | “\ *GeoLocation |
|                 |                 | about which the | Place*\ ”,      |
|                 |                 | data is         | e/o una serie   |
|                 |                 | focused.*       | di              |
|                 |                 |                 | “\ *GeoLocation |
|                 |                 |                 | Polygon*\ ”,    |
|                 |                 |                 | e/o una serie   |
|                 |                 |                 | di              |
|                 |                 |                 | “\ *GeoLocation |
|                 |                 |                 | Polygon*\ ”.    |
+-----------------+-----------------+-----------------+-----------------+
| *Publisher*     | 1               | *The name of    | Inserire il     |
|                 |                 | the entity that | nome            |
|                 |                 | holds,          | dell’Istituto   |
|                 |                 | archives,       | che rende       |
|                 |                 | publishes       | disponibile i   |
|                 |                 | prints,         | dati. Il campo  |
|                 |                 | distributes,    | viene compilato |
|                 |                 | releases,       | con “Istituto   |
|                 |                 | issues, or      | Nazionale di    |
|                 |                 | produces the    | Geofisica e     |
|                 |                 | resource. This  | Vulcanologia    |
|                 |                 | property will   | (INGV)”.        |
|                 |                 | be used to      |                 |
|                 |                 | formulate the   |                 |
|                 |                 | citation, so    |                 |
|                 |                 | consider the    |                 |
|                 |                 | prominence of   |                 |
|                 |                 | the role. For   |                 |
|                 |                 | software, use   |                 |
|                 |                 | Publisher for   |                 |
|                 |                 | the code        |                 |
|                 |                 | repository. If  |                 |
|                 |                 | there is an     |                 |
|                 |                 | entity other    |                 |
|                 |                 | than a code     |                 |
|                 |                 | repository,     |                 |
|                 |                 | that "holds,    |                 |
|                 |                 | archives,       |                 |
|                 |                 | publishes,      |                 |
|                 |                 | prints,         |                 |
|                 |                 | distributes,    |                 |
|                 |                 | releases,       |                 |
|                 |                 | issues, or      |                 |
|                 |                 | produces" the   |                 |
|                 |                 | code, use the   |                 |
|                 |                 | property        |                 |
|                 |                 | Contributor /   |                 |
|                 |                 | contributorType |                 |
|                 |                 | /               |                 |
|                 |                 | hostingInstitut |                 |
|                 |                 | ion             |                 |
|                 |                 | for the code    |                 |
|                 |                 | repository.*    |                 |
+-----------------+-----------------+-----------------+-----------------+
| *Creator*       | 1-n             | *The main       | Elencare i      |
|                 |                 | researchers     | principali      |
|                 |                 | involved in     | responsabili    |
|                 |                 | producing the   | scientifici e/o |
|                 |                 | data, or the    | tecnologici,    |
|                 |                 | authors of the  | indicando per   |
|                 |                 | publication, in | ciascuno        |
|                 |                 | priority        | l’affiliazione  |
|                 |                 | order.*         | e il codice     |
|                 |                 |                 | identificativo  |
|                 |                 |                 | ORCID. Oltre ai |
|                 |                 |                 | principali      |
|                 |                 |                 | responsabili è  |
|                 |                 |                 | anche possibile |
|                 |                 |                 | inserire un     |
|                 |                 |                 | riferimento     |
|                 |                 |                 | generico al     |
|                 |                 |                 | gruppo di       |
|                 |                 |                 | lavoro.         |
+-----------------+-----------------+-----------------+-----------------+
| *Contributor*   | 1-n             | *The            | Elencare le     |
|                 |                 | institution or  | persone che     |
|                 |                 | person          | hanno           |
|                 |                 | responsible for | contribuito ai  |
|                 |                 | collecting,     | dati,           |
|                 |                 | managing,       | identificando   |
|                 |                 | distributing,   | per ciascuno il |
|                 |                 | or otherwise    | ruolo svolto,   |
|                 |                 | contributing to | l’affiliazione  |
|                 |                 | the development | e il codice     |
|                 |                 | of the          | ORCID. E’       |
|                 |                 | resource. To    | possibile       |
|                 |                 | supply multiple | aggiungere      |
|                 |                 | contributors,   | anche           |
|                 |                 | repeat this     | istituzioni.    |
|                 |                 | property. For   | Settare         |
|                 |                 | software, if    | l’attributo     |
|                 |                 | there is an     | “\ *nameType*\  |
|                 |                 | alternate       | ”               |
|                 |                 | entity that     | “personal” per  |
|                 |                 | "holds,         | le persone e    |
|                 |                 | archives,       | “organizational |
|                 |                 | publishes,      | ”               |
|                 |                 | prints,         | per le          |
|                 |                 | distributes,    | istituzioni. I  |
|                 |                 | releases,       | ruoli previsti  |
|                 |                 | issues, or      | sono:           |
|                 |                 | produces" the   | *ContactPerson* |
|                 |                 | code, use the   | ,               |
|                 |                 | contributorType | *DataCollector* |
|                 |                 | "hostingInstitu | ,               |
|                 |                 | tion"           | *DataCurator*,  |
|                 |                 | for the code    | *DataManager*,  |
|                 |                 | repository.*    | *Distributor*,  |
|                 |                 |                 | *Editor*,       |
|                 |                 |                 | *HostingInstitu |
|                 |                 |                 | tion*,          |
|                 |                 |                 | *Other*,        |
|                 |                 |                 | *Producer*,     |
|                 |                 |                 | *ProjectLeader* |
|                 |                 |                 | ,               |
|                 |                 |                 | *ProjectManager |
|                 |                 |                 | *,              |
|                 |                 |                 | *ProjectMember* |
|                 |                 |                 | ,               |
|                 |                 |                 | *RegistrationAg |
|                 |                 |                 | ency*,          |
|                 |                 |                 | *RegistrationAu |
|                 |                 |                 | thority*,       |
|                 |                 |                 | *RelatedPerson* |
|                 |                 |                 | ,               |
|                 |                 |                 | *ResearchGroup* |
|                 |                 |                 | ,               |
|                 |                 |                 | *RightsHolder*, |
|                 |                 |                 | Resea\ *r*\ che |
|                 |                 |                 | r,              |
|                 |                 |                 | Spon\ *s*\ or,  |
|                 |                 |                 | *Supervisor*,   |
|                 |                 |                 | *WorkPackageLea |
|                 |                 |                 | der*            |
+-----------------+-----------------+-----------------+-----------------+
| *Rights*        | 1               | *Any rights     | Tipologia di    |
|                 |                 | information for | licenza         |
|                 |                 | this resource*  | *Creative*      |
|                 |                 |                 | *Commons*.      |
+-----------------+-----------------+-----------------+-----------------+
| *Funding        | 1-n             | *Information    | Elenco delle    |
| Reference*      |                 | about financial | istituzioni che |
|                 |                 | support         | hanno           |
|                 |                 | (funding) for   | finanziato la   |
|                 |                 | the resource    | creazione dei   |
|                 |                 | being           | dati.           |
|                 |                 | registered*     |                 |
+-----------------+-----------------+-----------------+-----------------+
| *Date*          | 0-1             | *Different      | Se disponibili, |
|                 |                 | dates relevant  | compilare con   |
|                 |                 | to the work.    | le date         |
|                 |                 | The attribute   | relative.       |
|                 |                 | 'dateType' may  |                 |
|                 |                 | contains:       |                 |
|                 |                 | Accepted,       |                 |
|                 |                 | Available,      |                 |
|                 |                 | Copyrighted,    |                 |
|                 |                 | Collected,      |                 |
|                 |                 | Created,        |                 |
|                 |                 | Issued,         |                 |
|                 |                 | Submitted,      |                 |
|                 |                 | Updated,        |                 |
|                 |                 | Valid.*         |                 |
+-----------------+-----------------+-----------------+-----------------+

*Tabella 3 – Metadati a compilazione facoltativa.*

+-----------------+-----------------+-----------------+-----------------+
| Etichetta (Tag) | Occorr          | Descrizione     | Contenuto       |
|                 |                 | fornita da      |                 |
|                 |                 | DataCite        |                 |
+-----------------+-----------------+-----------------+-----------------+
| *Language*      | 0-1             | *The primary    | Compilare con   |
|                 |                 | language of the | la dizione      |
|                 |                 | resource.*      | inglese della   |
|                 |                 |                 | lingua con cui  |
|                 |                 |                 | i dati sono     |
|                 |                 |                 | pubblicamente   |
|                 |                 |                 | disponibili i   |
|                 |                 |                 | dati.           |
+-----------------+-----------------+-----------------+-----------------+
| *Alternate      | 0-n             | *An identifier  | Se i dati       |
| Identifier*     |                 | or identifiers  | associati al    |
|                 |                 | other than the  | DOI sono anche  |
|                 |                 | primary         | associati ad    |
|                 |                 | Identifier      | altri           |
|                 |                 | applied to the  | identificativi  |
|                 |                 | resource being  | è possibile     |
|                 |                 | registered.     | usare questo    |
|                 |                 | This may be any | tag per         |
|                 |                 | alphanumeric    | stabilire un    |
|                 |                 | string which is | collegamento.   |
|                 |                 | unique within   |                 |
|                 |                 | its domain of   |                 |
|                 |                 | issue. May be   |                 |
|                 |                 | used for local  |                 |
|                 |                 | identifiers.    |                 |
|                 |                 | Alternate       |                 |
|                 |                 | Identifier      |                 |
|                 |                 | should be used  |                 |
|                 |                 | for another     |                 |
|                 |                 | identifier of   |                 |
|                 |                 | the same        |                 |
|                 |                 | instance (same  |                 |
|                 |                 | location, same  |                 |
|                 |                 | file).*         |                 |
+-----------------+-----------------+-----------------+-----------------+
| *Related        | 0-n             | *Identifiers of | Se i dati hanno |
| Identifier*     |                 | related         | delle relazioni |
|                 |                 | resources.      | –di qualunque   |
|                 |                 | These must be   | natura- con     |
|                 |                 | globally unique | altri prodotti  |
|                 |                 | identifiers.*   | della ricerca   |
|                 |                 |                 | associati ad    |
|                 |                 |                 | identificativi  |
|                 |                 |                 | è possibile     |
|                 |                 |                 | usare questo    |
|                 |                 |                 | tag per         |
|                 |                 |                 | stabilire un    |
|                 |                 |                 | collegamento.   |
|                 |                 |                 | Si veda         |
|                 |                 |                 | l’elenco delle  |
|                 |                 |                 | relazioni       |
|                 |                 |                 | ammesse a       |
|                 |                 |                 | seguire.        |
+-----------------+-----------------+-----------------+-----------------+
| *Size*          | 0-n             | *Size (e.g.     | Se è possibile  |
|                 |                 | bytes, pages,   | quantificare i  |
|                 |                 | inches, etc.)   | dati, compilare |
|                 |                 | or duration     | questo campo.   |
|                 |                 | (extent), e.g.  |                 |
|                 |                 | hours, minutes, |                 |
|                 |                 | days, etc., of  |                 |
|                 |                 | a resource.*    |                 |
+-----------------+-----------------+-----------------+-----------------+
| *Format*        | 0-n             | *Technical      | Se i dati sono  |
|                 |                 | format of the   | disponibili in  |
|                 |                 | resource. Use   | uno o più       |
|                 |                 | file extension  | standard di     |
|                 |                 | or MIME type    | codifica di     |
|                 |                 | where           | dati, indicare  |
|                 |                 | possible.*      | qui i formati.  |
+-----------------+-----------------+-----------------+-----------------+

5.2.3 Relazioni con altri prodotti della ricerca
------------------------------------------------

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

+-----------------------------------+-----------------------------------+
| Tipo di relazione                 | Descrizione fornita da DataCite   |
+-----------------------------------+-----------------------------------+
| IsCitedBy                         | *Indicates that B includes A in a |
|                                   | citation*                         |
+-----------------------------------+-----------------------------------+
| Cites                             | *Indicates that A includes B in a |
|                                   | citation*                         |
+-----------------------------------+-----------------------------------+
| IsSupplementTo                    | *Indicates that A is a supplement |
|                                   | to B*                             |
+-----------------------------------+-----------------------------------+
| IsSupplementedBy                  | *Indicates that B is a supplement |
|                                   | to A*                             |
+-----------------------------------+-----------------------------------+
| IsContinuedBy                     | *Indicates A is continued by the  |
|                                   | work B*                           |
+-----------------------------------+-----------------------------------+
| Continues                         | *Indicates A is a continuation of |
|                                   | the work B*                       |
+-----------------------------------+-----------------------------------+
| Describes                         | *Indicates A describes B*         |
+-----------------------------------+-----------------------------------+
| IsDescribedBy                     | *Indicates A is described by B*   |
+-----------------------------------+-----------------------------------+
| HasMetadata                       | *Indicates resource A has         |
|                                   | additional metadata B*            |
+-----------------------------------+-----------------------------------+
| IsMetadataFor                     | *Indicates additional metadata A  |
|                                   | for a resource B*                 |
+-----------------------------------+-----------------------------------+
| HasVersion                        | *Indicates A has a version (B)*   |
+-----------------------------------+-----------------------------------+
| IsVersionOf                       | *Indicates A is a version of B*   |
+-----------------------------------+-----------------------------------+
| IsNewVersionOf                    | *Indicates A is a new edition of  |
|                                   | B, where the new edition has been |
|                                   | modified or updated*              |
+-----------------------------------+-----------------------------------+
| IsPreviousVersionOf               | *Indicates A is a previous        |
|                                   | edition of B*                     |
+-----------------------------------+-----------------------------------+
| IsPartOf                          | *Indicates A is a portion of B;   |
|                                   | may be used for elements of a     |
|                                   | series*                           |
+-----------------------------------+-----------------------------------+
| HasPart                           | *Indicates A includes the part B* |
+-----------------------------------+-----------------------------------+
| IsReferencedBy                    | *Indicates A is used as a source  |
|                                   | of information by B*              |
+-----------------------------------+-----------------------------------+
| References                        | *Indicates B is used as a source  |
|                                   | of information for A*             |
+-----------------------------------+-----------------------------------+
| IsDocumentedBy                    | *Indicates B is documentation     |
|                                   | about or explaining A*            |
+-----------------------------------+-----------------------------------+
| Documents                         | *Indicates A is documentation     |
|                                   | about B*                          |
+-----------------------------------+-----------------------------------+
| IsCompiledBy                      | *Indicates B is used to compile   |
|                                   | or create A*                      |
+-----------------------------------+-----------------------------------+
| Compiles                          | *Indicates B is the result of a   |
|                                   | compile or creation event using   |
|                                   | A*                                |
+-----------------------------------+-----------------------------------+
| IsVariantFormOf                   | *Indicates A is a variant or      |
|                                   | different form of B*              |
+-----------------------------------+-----------------------------------+
| IsOriginalFormOf                  | *Indicates A is the original form |
|                                   | of B*                             |
+-----------------------------------+-----------------------------------+
| IsIdenticalTo                     | *Indicates that A is identical to |
|                                   | B, for use when there is a need   |
|                                   | to register two separate          |
|                                   | instances of the same resource*   |
+-----------------------------------+-----------------------------------+
| IsReviewedBy                      | *Indicates that A is reviewed by  |
|                                   | B*                                |
+-----------------------------------+-----------------------------------+
| Reviews                           | *Indicates that A is a review of  |
|                                   | B*                                |
+-----------------------------------+-----------------------------------+
| IsDerivedFrom                     | *Indicates B is a source upon     |
|                                   | which A is based*                 |
+-----------------------------------+-----------------------------------+
| IsSourceOf                        | *Indicates A is a source upon     |
|                                   | which B is based*                 |
+-----------------------------------+-----------------------------------+
| IsRequiredBy                      | *Indicates A is required by B*    |
+-----------------------------------+-----------------------------------+
| Requires                          | *Indicates A requires B*          |
+-----------------------------------+-----------------------------------+

5.2.4 Identificazione di Frammenti di Dati Complessi
----------------------------------------------------

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

Gli identificativi DOI, essendo basati su *Handle System*\  [7]_,
possono usufruire dei *”Template handles”*, che permettono di aggiungere
un numero indefinito di parametri all’identificativo inseriti dopo il
simbolo di cancelletto (“#”). Questa soluzione è stato preso in
considerazione dal gruppo di lavoro *“Data Citation”*\  [8]_ dalla
*Research Data Alliance* (RDA) che ne ha fatto una raccomandazione in
ambito di dati dinamici. La tecnica di estrazione di sottoinsiemi di
dati con l'ausilio di parametri viene denominata *"data slicing"*. In
ambito sismologico sono in corso sperimentazioni [9]_\ :sup:`,`  [10]_
nell’ambito dei progetti europei COOPEUS, ENVRI ed EUDAT.

.. [1]
   DataCite. https://www.datacite.org/

.. [2]
   DataCite metadata schema. https://schema.datacite.org/

.. [3]
   International DOI Foundation. DOI Handbook.
   https://www.doi.org/hb.html

.. [4]
   DataCite. Metadata schema. https://schema.datacite.org/

.. [5]
   Smith AM, Katz DS, Niemeyer KE, FORCE11 Software Citation Working
   Group (2016). Software citation principles. PeerJ Computer Science.
   https://doi.org/10.7717/peerj-cs.86

.. [6]
   Smith AM, Katz DS, Niemeyer KE, FORCE11 Software Citation Working
   Group (2016). Software citation principles. PeerJ Computer Science.
   https://doi.org/10.7717/peerj-cs.86

.. [7]
   Handle Registry. https://www.handle.net/

.. [8]
   Rauber A., Asmi A., van Uytvanck D., Pröll S. (2015). Data Citation
   of Evolving Data.
   https://rd-alliance.org/system/files/documents/RDA-DC-Recommendations_150924.pdf

.. [9]
   Klump J. and Huber R. (2016). DOI for geoscience data - how early
   practices shape present perceptions. Earth Science Informatics, 9(1):
   123-136. https://doi.org/10.1007/s12145-015-0231-5

.. [10]
   Huber R., Asmi A., Buck J., De Luca J.M., Diepenbroek D., Michelini
   A. (2015). Data citation and digital identifiers for time series data
   / environmental research infrastructures. Joint COOPEUS/ENVRI/EUDAT
   PID workshop, Bremen, 25-26 June 2013.
   https://doi.org/10.6084/m9.figshare.1285728.v1

.. |image0| image:: ./media/image4.png
   :width: 3.26958in
   :height: 1.24653in

4.2 Gestione Ordinaria del Registro Dati
========================================

La gestione ordinaria del Registro Dati coinvolge, a diverso livello, i
seguenti soggetti istituzionali:

-  Il Responsabile dei Dati e il Responsabile Tecnico della Banca Dati,
   che agisce per conto del Produttore di Dati;

-  Il Direttore di Sezione cui fa riferimento il Responsabile dei Dati;

-  Il Direttore di Dipartimento, responsabile della validazione
   istituzionale e della qualità scientifica; nel caso in cui il dato
   coinvolga più Dipartimenti, i Direttori di Dipartimento, ne
   identificano uno di riferimento;

-  L’Ufficio Gestione Dati (UGD), che coordina e gestisce l'intero iter
   procedurale.

4.2.1 Criteri di ammissibilità
------------------------------

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
   soprattutto, l'espressa accettazione dell'inserimento di questi dati
   nel Registro Dati dell’INGV; si precisa che tale documentazione deve
   essere sottoscritta dai soggetti legittimati, che dispongano cioè
   della titolarità dei dati oggetto dell’accordo.

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
Digitale [1]_, oppure se si tratta di standard di riferimento nel
settore scientifico di riferimento.

Deve essere data segnalazione se si tratti di dati territoriali che
possano essere iscritti nel Repertorio Nazionale dei Dati Territoriali
(RNDT) [2]_, con particolare riferimento ai dati territoriali definiti
da normativa di “interesse generale” [3]_.

Ogni richiesta di inserimento dati deve essere corredata da un piano di
sostenibilità concordato con i Direttori delle Sezioni coinvolte, che
chiarisca la natura e la durata della copertura finanziaria necessaria
all'infrastruttura che ospita i dati e che descriva se e come le
soluzioni adottate garantiscono sia la conservazione sia l'accessibilità
ai dati nel lungo periodo.

4.2.2 Procedura di inserimento di elementi 
-------------------------------------------

La procedura ordinaria di sottomissione si compone dei seguenti passaggi
(Figura 2):

1. Si formalizza l’identità del Produttore dei Dati (vedi Capitolo 3.2)
   indicando per ciascun componente l'afferenza, il ruolo, e il codice
   identificativo ORCID, come da indicazioni MIUR [4]_ e ANVUR [5]_.

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

10. Il Direttore di Dipartimento valuta la richiesta, anche in relazione
    al Programma Triennale di Attività dell’INGV; nel caso di dati di
    Livello 0 o 1, assegna la licenza d’uso in qualità di delegato del
    legale rappresentante dell’INGV; invia l’autorizzazione a procedere
    all’UGD;

11. L’UGD procede all'assegnazione dell'identificativo di Registro e
    inserisce il nuovo elemento nel Registro Dati; nel caso in cui i
    dati non siano né strutturati né strutturabili in una Banca dati
    istituzionale esistente, essi vengono archiviati in Earth-Prints;

12. L’UGD inserisce i metadati dell’elemento in Registri di metadati
    esterni, in particolare nel Registro DOI di DataCite e, nel caso in
    cui sia data segnalazione dal Responsabile dei Dati che i dati siano
    di tipo territoriale e siano di interesse per il Repertorio
    Nazionale dei Dati Territoriali (RNDT), inserisce i dati nel
    Registro RNDT;

13. L’UGD procede ad aggiornare le informazioni del Registro Dati sul
    portale istituzionale dell’INGV.

4.2.3 Modifiche e integrazioni a elementi
-----------------------------------------

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
---------------------------

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
-------------------------------------

Poiché la normativa vigente adotta il principio *open by default*\  [6]_
secondo cui *“I dati [...] che le amministrazioni pubblicano, con
qualsiasi modalità, senza l'espressa adozione di una licenza [...] si
intendono rilasciati come dati di tipo aperto”*, INGV, in quanto
titolare, apporrà una licenza [7]_ ad ogni elemento del Registro
Dati [8]_. In accordo con quanto stabilito nei Principi della Politica
dei Dati dell’INGV e con quanto suggerito dalle linee guida della
Commissione Europea [9]_, le licenze adottate saranno di tipo *Creative
Commons*\  [10]_.

Ai fini di supportare l’\ *Open Science* tramite la pubblicazione di
“Dati di tipo aperto” [11]_, si stabilisce che ai dati di Livello 0 e 1
sia attribuita la licenza *“Creative Commons Attribution (CC
BY)”*\  [12]_, in forza del principio sancito nei “Principi della
Politica dei Dati dell’INGV” secondo cui il titolare  [13]_ della
proprietà intellettuale di questi dati è l’INGV. Per quanto riguarda la
versione della licenza, al momento della redazione di questo documento
si fa riferimento alla v4.0 ma successivamente si dovranno tenere in
considerazione gli eventuali aggiornamenti [14]_.

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
--------------------------------------------------------

I dati inseriti nel Registro avranno, oltre a un identificativo di
Registro, anche un identificativo persistente largamente adottato in
ambiente scientifico come il codice DOI. L’Agenzia di Registro DOI
utilizzata è DataCite, di cui si adotta il relativo schema di
metadati [15]_. Per dettagli sulla procedura di assegnazione di questo
identificativo, si fa riferimento al Capitolo 5 “Registri di metadati
non gestiti da INGV”.

4.2.7 Esclusione di responsabilità e termini di utilizzo dei dati
-----------------------------------------------------------------

L’UGD di concerto con il settore Affari Legali e Contenzioso stabilirà
caso per caso le modalità ed azioni per la gestione dell’esclusione di
responsabilità dell’INGV e del personale circa l'eventuale incompletezza
ed incertezza dei dati presenti nel Registro Dati, utilizzo, anche
parziale, dei dati riportati nel Registro Dati da parte di terzi e
eventuali danni arrecati a terzi derivanti dal loro utilizzo.

.. [1]
   Agenzia Digitale per l'Italia (2017). Linee Guida Nazionali per la
   Valorizzazione del Patrimonio Informativo Pubblico.

.. [2]
   D.Lgs. 7 marzo 2005, n. 82. Codice dell'Amministrazione Digitale
   (CAD). Art. 59, Comma 5.

.. [3]
   Decreto della Presidenza del Consiglio dei Ministri 10 novembre 2011.
   Art.3, Comma 1. Elenco in Allegato 1.

.. [4]
   Decreto del Ministero dell'Istruzione, dell'Università e della
   Ricerca del 7 giugno 2016, n. 120.

.. [5]
   ANVUR, Progetto IRIDE.

.. [6]
   D.Lgs. 7 marzo 2005 n. 82. Codice dell'amministrazione digitale
   (CAD). Art.52, comma 2.

.. [7]
   D.Lgs. 24 gennaio 2006, n.36. Art.5, Comma 1, *“[…] Il titolare del
   dato adotta prioritariamente licenze aperte standard […]”*. Art.2,
   Comma h, *"licenza standard per il riutilizzo: il contratto, o altro
   strumento negoziale, redatto ove possibile in forma elettronica, nel
   quale sono definite le modalità di riutilizzo dei documenti delle
   pubbliche amministrazioni o degli organismi di diritto pubblico"*.

.. [8]
   D.Lgs. 30 marzo 2001 n. 165, comma 2. I soggetti titolati
   all’apposizione di licenze ai dati sono le amministrazioni pubbliche,
   intese come *“tutte le amministrazioni dello Stato, ivi compresi gli
   istituti e scuole di ogni ordine e grado e le istituzioni educative,
   le aziende ed amministrazioni dello Stato ad ordinamento autonomo, le
   Regioni, le Province, i Comuni, le Comunità montane e loro consorzi e
   associazioni, le istituzioni universitarie, gli Istituti autonomi
   case popolari, le Camere di commercio, industria, artigianato e
   agricoltura e loro associazioni, tutti gli enti pubblici non
   economici nazionali, regionali e locali, le amministrazioni, le
   aziende e gli enti del Servizio sanitario nazionale l'Agenzia per la
   rappresentanza negoziale delle pubbliche amministrazioni (ARAN) e le
   Agenzie di cui al decreto legislativo 30 luglio 1999, n. 300. Fino
   alla revisione organica della disciplina di settore, le disposizioni
   di cui al presente decreto continuano ad applicarsi anche al CONI”*.

.. [9]
   European Commission notice (2014/C 240/01). Guidelines on recommended
   standard licences, datasets and charging for the reuse of documents.

.. [10]
   Creative Commons. https://creativecommons.org/

.. [11]
   D.Lgs. 7 marzo 2005 n. 8, Art.68, comma 3, lettera b

.. [12]
   Creative Commons Attribution 4.0 International (CC BY 4.0).
   https://creativecommons.org/licenses/by/4.0/

.. [13]
   D.Lgs. 7 marzo 2005 n. 82, Art. 1, comma cc, così come modificato dal
   D.Lgs. 26 agosto 2016 n. 179, Art.1, comma g

.. [14]
   Creative Commons Licenses.
   https://wiki.creativecommons.org/wiki/License_Versions

.. [15]
   Datacite. Metadata Schema. https://schema.datacite.org/

.. |Regolamento DOI| image:: ./media/image3.png
   :width: 5.78542in
   :height: 7.82222in

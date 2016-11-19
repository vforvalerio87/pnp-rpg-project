#Sistema gioco di ruolo
*di Valerio Versace*

##Obiettivi
Lo scopo di questo documento è quello di delineare le basi per un sistema di gioco di ruolo essenziale. Il motivo della stesura di questo documento è il seguente: 
* Fornire un sistema di regole semplice, adattabile a diverse ambientazioni con modifiche minime
* Consentire ai master di scrivere velocemente avventure giocabili
* Consentire ai master di convertire rapidamente a questo sistema di gioco meccaniche di altri sistemi utilizzando pochi semplici prinicipi
* Consentire ai master di convertire rapidamente a questo sistema di gioco avventure di altri sistemi
* Consentire ai giocatori di imparare rapidamente le regole di questo sistema per facilitarne la memorizzazione e iniziare a giocare velocemente 
* Consentire ai giocatori di creare velocemente personaggi giocabili
* Consentire di simulare combattimenti senza mappe, miniature o righelli: il combattimento deve potersi svolgere solo coi dadi e la narrazione

Questo documento non è una bozza di manuale del giocatore: è per me ed altri eventuali addetti ai lavori che dovessero trovarsi a collaborare al progetto. È una versione del sistema di gioco spiegata e commentata, nei suoi principi e nei suoi obiettivi, in modo da poterla espandere, definire e formalizzare.

Per il momento l'idea è quella di rilasciare il sistema di gioco **open source** con licenza **GPLv3**. Allo stato attuale si può considerare non coperto da alcuna licenza, né un sistema vero e proprio; sono solo appunti.

###Guida di stile
Queste sono indicazioni che utilizzerò per la progettazione di questo sistema di gioco:
* Usare termini precisi senza abbreviazioni da memorizzare
* Tenere gli elementi generici, veramente utili a qualsiasi avventura o campagna, all'interno delle regole base; tutto il resto deve essere in documenti di ambientazione o di avventura. Per un principio di specificità, eventuali regole indicate in un manuale dell'ambientazione hanno la precedenza su quelle generiche; sopra a tutto vale la decisione del master.
* Se una meccanica è troppo articolata, semplificarla o rimuoverla e concentrarsi sulla sua componente narrativa. Esempio: non è importante definire secondo quali fattispecie e in quanto tempo da una declinazione dello stato di *gravemente ferito* un personaggio passi allo stato di *morto* se nessuno interviene; è una decisione che è meglio lasciare al master
* Evitare pagine di armi qualitativamente simili, diverse solo per valori numerici: poche armi generiche con caratteristiche differenti prima di tutto sul piano qualitativo. Sono spesso elementi fortemente distintivi di una ambientazione e di un personaggio
* Tutti i tiri sono scoperti, sia quelli dei giocatori che quelli del master
* Per la maggior parte dei tiri il master può decidere arbitrariamente invece di ricorrere ai dadi; è suggerito all'interno del manuale quando questo potrebbe essere particolarmente opportuno. Fanno eccezione i confronti tra due giocatori nei quali il master dovrebbe cercare di non intromettersi per avvantaggiare uno o l'altro

##Appunti
Questi sono alcuni appunti sulle meccaniche, scritti man mano che mi vengono in mente, da ordinare

###Elementi minimi
Cosa deve esserci nel sistema:
* Abilità - generiche. Esigenze di caratterizzazione non devono essere penalizzate e produrre personaggi monodimensionali
* Evitare statistiche. Possono essere ricondotte ad abilità nei casi generali; a bonus o malus a determinati tiri in casi più specifici
* Valutare se tenere vantaggi o svantaggi - separare elementi legati a meccaniche da elementi legati a caratterizzazione
* Niente successi e fallimenti critici

###Test
* Tiri contro livelli di difficoltà
* Confronti diretti (tiro contro tiro)
* Dadi? Ipotesi: dadi da 10; i tiri sono d10 + punteggio nell'abilità rilevante
* Il master può applicare bonus e malus a tiri o confronti; esempio, può decidere di dare ad un nano un malus in un confronto diretto per stabilire chi vinca una corsa a piedi, o un bonus in una gara di bevute. È consigliabile appuntarsi quando si decide in questo senso per mantenere una coerenza interna durante l'avventura

###Fato
Una volta per sessione ciascun giocatore può appellarsi al fato per ottenere uno dei due seguenti effetti:
* Decidere il risultato di un tiro di dado prima che questo venga tirato
* Prendere una decisione al posto del master o rettificare una sua decisione appena presa

Esempio: per determinare se una ferita porti o meno all'incapacitamento di un soggetto è possibile tirare un dado, oppure il master può decidere in maniera arbitraria. Appellandosi al fato un giocatore può decidere che un personaggio sia per forza di cose incapacitato, oppure che non lo sia, anche se il master ha appena deciso in senso contrario. Qualsiasi giocatore può appellarsi al fato anche se il suo personaggio è ferito, privo di sensi o morto.

Un giocatore non può invocare il fato contro un altro giocatore.

###Abilità
Le abilità vanno da 0 a 10?
A seconda dell'ambientazione, ogni abilità può richiedere delle specializzazioni. Per esempio, in una ambientazione in cui siano presenti e fortemente utilizzati da gruppi differenti sia archi che fucili, l'abilità *combattimento a distanza* potrebbe riferirsi solo ad una di queste tipologie di armi. Per comodità diverse specializzazioni della stessa abilità hanno un livello pari al livello di abilità -1 fino a livello 6, -2 da livello 6 in su, a meno che il materiale specifico dell'ambientazione non specifichi altro o il master non decida diversamente.

####Sotterfugio
Esempio: borseggiare, scassinare, hackerare sistemi di sicurezza o falsificare documenti.

####Combattimento a distanza
Esempio: tirare con l'arco o sparare con la pistola.

####Combattimento corpo a corpo
Esempio: combattimento a mani nude o con arma bianca.

###Tratti?
Caratteristiche del personaggio. Per esempio il mestiere che svolge o i tipi di ambiente che frequenta o le cose che lo spaventano. Li vogliamo? Come si gestiscono? Costo in punti (tipo vantaggi/svantaggi di GURPS) o ne prendi un determinato numero alla creazione e stop? Li scelgono i giocatori liberamente (contro: sindrome da colloquio. Esempio: "il mio difetto è che sono preciso nelle cose") o c'è una lista base da cui attingere? O li sceglie il master?
>IPOTESI: facciamo una roba tipo la selezione delle squadre di calcetto. All'inizio di ogni campagna il master determina casualmente una serie di tratti (li pesca dal ciclindro, tira dei dadi... come preferite); a quel punto i giocatori a turno se li spartiscono finché non terminano. 

##Combattimento

###Turni
Quanto dura un turno? Non importa. Il turno è un'unità di misura propria del combattimento; l'unica cosa che conta in combattimento è l'ordine di iniziativa. Possiamo distinguere azioni normali e azioni lunghe: un'azione normale si contende l'iniziativa con altre azioni normali; le azioni lunghe sortiscono i loro effetti dopo quelle normali, se non vengono interrotte. Ad esempio, un tiro lungo richiede sempre almeno un minimo di tempo per mirare, per cui è un'azione lunga. Allo stesso modo, sparare da dietro una copertura pesante costringe a sporgersi dalla copertura, per cui è un'azione lunga.
Qualsiasi azione più lunga, salvo discrezione del master, non può essere svolta in combattimento, per cui non si misura in turni.

###Salute
La salute si basa su due assi: quanto il personaggio è ferito e quanto è incapacitato.

####Incapacitamento
Lo stato di incapacitamento determina quello che un personaggio è in grado o non è in grado di fare. Di seguito gli stati:
* **In salute**
* **Incapacitato** - il personaggio non è in grado di svolgere determinate funzioni: può essere incapace di parlare, o paralizzato, ma il giocatore è ancora in grado di esercitare controllo sul suo personaggio e interagire con il gruppo. Il master può decretare che il personaggio non sia in grado di effettuare specifici compiti o assegnargli penalità a sua discrezione
* **Privo di sensi** - il personaggio non è in grado di svolgere praticamente alcuna funzione; rappresenta qualsiasi stato che vada dalla perdita di conoscenza al coma profondo. Il giocatore non ha il controllo del suo personaggio. È tendenzialmente un processo reversibile; qualora non lo fosse per qualsiasi motivo, è assimilabile alla morte

####Ferite
Ogni volta che un personaggio subisce una ferita, il suo stato complessivo di ferite può rimanere uguale o peggiorare. In entrambi i casi, il personaggio fa un tiro per vedere se il suo stato di incapacitamento rimane uguale o peggiora.
* **Non ferito**
* **Lievemente ferito** - il personaggio ha subito delle ferite ma le sue capacità non sono compromesse in maniera sensibile
* **Gravemente ferito** - nel momento in cui un personaggio diventa gravemente ferito, tira normalmente per l'incapacitamento. Qualsiasi sia il risultato del tiro, se il personaggio non è già almeno incapacitato, allora è automaticamente incapacitato
* **Morto**

La sequenza degli stati deve essere la seguente:
* Qualsiasi colpo a segno può ferire
* Qualsiasi ferita subita può lasciare il personaggio al suo livello complessivo di ferite corrente (non ferito, lievemente ferito o gravemente ferito) oppure peggiorarlo
* Ogni volta che un personaggio subisce una ferita, sia che il suo livello complessivo di ferite corrente peggiori sia che resti uguale, può restare incapacitato o perdere i sensi

In ciascuno di questi tre casi, sia per i giocatori che per i personaggi non giocanti, il master può decidere aribtrariamente oppure può far tirare un dado al giocatore.

###Combattimento a distanza

####Distanza
* Corto raggio
* Medio raggio
* Lungo raggio - attaccare è un'azione lunga: serve tempo per mirare

####Coperture
* Nessuna copertura
* Copertura leggera
* Copertura pesante - attaccare è un'azione lunga: serve tempo per uscire dalla copertura

Le indicazioni sulla durata delle azioni sono generiche e indicative; possono cambiare da tipologia di arma a tipologia di arma. Per esempio con un arco ogni tipo di attacco può essere un'azione lunga; con una balestra può esserlo ricaricare.

##Provvisori

Abilità da 0 a 3. Si tira il dado da 6. Prima di ogni test il master decide la difficoltà; nei confronti la difficoltà è data dall'altro. Con 1-2 il personaggio sottrae 1 alla sua abilità; con 5 o 6 somma 1.

Ferite: una volta colpito si viene feriti con 4, 5 o 6

Armatura: si viene feriti con 5 o 6

Scudo: +1 al tiro di dado in difesa

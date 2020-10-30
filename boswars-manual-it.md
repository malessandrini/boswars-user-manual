(Avvertenza: questo è un progetto indipendente, l'autore non fa parte del team di sviluppo del gioco ([Bos Wars](https://www.boswars.org/) è &copy; 2004-2013 by Tina Petersen Jensen, Francois Beerten et al., rilasciato come free software sotto licenza GPL v.2). Come tale 1) Questo lavoro potrebbe non essere accurato al 100% e 2) Gli autori del gioco non devono essere contattati per problemi relativi a questo manuale.)










# Indice

- [Introduzione](#introduzione)
- [Menù iniziale](#menù-iniziale)
- [Mappa](#mappa)
  - [Mini-mappa](#mini-mappa)
  - [Menù di gioco](#menù-di-gioco)
  - [Unità](#unità)
  - [Oggetti naturali](#oggetti-naturali)
- [Azioni basilari: selezione e movimento](#azioni-basilari-selezione-e-movimento)
  - [Selezione](#selezione)
  - [Movimento](#movimento)
- [Risorse](#risorse)
  - [Energia](#energia)
  - [Magma](#magma)
- [Costruire strutture](#costruire-strutture)
  - [L'ingegnere](#lingegnere)
  - [Strutture di base](#strutture-di-base)
    - [Vault](#vault-v)
    - [Magma pump](#magma-pump-m)
    - [Radar](#radar-r)
    - [Camera](#camera-c)
    - [Power plant](#power-plant-p)
    - [Nuclear power plant](#nuclear-power-plant-n)
  - [Strutture unità](#strutture-unità)
    - [Training camp](#training-camp-c)
    - [Hospital](#hospital-h)
    - [Vehicle factory](#vehicle-factory-v)
    - [Shipyard](#shipyard-s)
    - [Aircraft factory](#aircraft-factory-a)
  - [Strutture difensive](#strutture-difensive)
    - [Gun turret](#gun-turret-g)
    - [Big gun turret](#big-gun-turret-b)
    - [Cannon](#cannon-c)
    - [Missile silo](#missile-silo-m)
- [Costruire unità](#costruire-unità)
  - [Unità da training camp](#unità-da-training-camp)
  - [Unità da hospital](#unità-da-hospital)
  - [Unità da vehicle factory](#unità-da-vehicle-factory)
  - [Unità da shipyard](#unità-da-shipyard)
  - [Unità da aircraft factory](#unità-da-aircraft-factory)
- [Combattimento](#combattimento)
- [Consigli di strategia](#consigli-di-strategia)








# Introduzione

[Bos Wars](https://www.boswars.org/) è un gioco di strategia in tempo reale (RTS in inglese) rilasciato come software libero (free software). In un gioco RTS in genere si deve conquistare l'intero "mondo" in un determinato livello, distruggendo nel contempo tutti i nemici. Solitamente si inizia in un piccolo angolo con poche risorse e bisogna costruire il proprio esercito (incluse le difese per la propria base) per poter esplorare e conquistare aree sempre più vaste e sconfiggere i nemici che si incontrano. Per far ciò occorre anche gestire le risorse necessarie (energia, materiali) e trovarne sempre di nuove. Ma attenzione, nel buio intanto i nemici si danno da fare con lo stesso scopo, incluso distruggerci, quindi bisogna adottare una strategia efficace e bilanciare le proprie risorse.










# Menù iniziale

All'avvio del programma viene visualizzato il menù iniziale, le cui voci sono abbastanza intuitive, perciò saranno descritte solo sommariamente.

Nota: l'interfaccia del menù è disponibile in varie lingue, tra cui l'italiano, selezionabili nella sezione "Opzioni" ("Options"). Tuttavia all'interno del gioco i vari oggetti sono denominati con il loro nome originale inglese, per cui nel seguito si utilizzeranno i nomi inglesi.

Alcune funzionalità sono al di là dello scopo di questo manuale, come per esempio l'editor delle mappe che permette di creare nuovi livelli partendo da zero o modificando un livello esistente.

Il pulsante "Opzioni" ("Options") permette di settare alcune impostazioni del gioco come la risoluzione video, l'audio, la velocità e così via.

"Carica" ("Load game") serve a riprendere un gioco precedentemente salvato.

Infine "Inizia partita" ("Start game") permette di iniziare un nuovo gioco. Una volta premuto si può scegliere una delle mappe dalla lista a destra (inizialmente si possono ignorare le campagne). Selezionando una mappa se ne possono vedere i dettagli nella parte sinistra, in particolare le sue dimensioni, ad esempio 64x64 per le più piccole, fino a 256x256. Si consiglia vivamente di iniziare con le mappe più piccole se non si è ancora pratici con il gioco, e di lasciare tutte le opzioni al valore predefinito, almeno finché non si è più esperti. Premendo "Inizio" ("Start") si inizia il gioco vero e proprio.










# Mappa

![Mappa del gioco](pics/map/map.png "Esempio di mappa del gioco")

La mappa è dove si svolge il gioco. Si possono distinguere tre tipi di aree:

- Aree pienamente illuminate: aree nel campo visivo delle nostre unità, dove cioè è presente almeno una nostra unità. Grazie alla presenza fisica è possibile vedere cosa sta succedendo in tempo reale. Ogni unità ha una propria distanza visiva, in genere alquanto limitata.
- Aree nere: inizialmente la maggior parte, sono aree dove il giocatore non è mai stato e che saranno scoperte una volta raggiunte. Questa caratteristica può essere disabilitata, in modo da vedere tutta la mappa dall'inizio, ma questo verosimilmente può compromettere le dinamiche del gioco.
- Aree offuscate (parzialmente illuminate): aree dove il giocatore è stato in precedenza, ma che adesso non hanno più nostre unità nelle vicinanze, ad esempio se tutte le unità sono state distrutte. Si può ancora vedere l'area, ma non quello che sta avvenendo attualmente; si può vedere solo una "fotografia" dell'ultima volta che una nostra unità era in zona, così che l'area potrebbe essere piena di nemici ma non è possibile vederli finché delle nostre unità non vi ritornano. Questa caratteristica è chiamata "nebbia di guerra" ("fog of war") e anch'essa può essere disabilitata, ma anche in questo caso ciò potrebbe togliere interesse al gioco.

Si può far scorrere la mappa nelle quattro direzioni muovendo il mouse vicino ai quattro bordi.

## Mini-mappa

![Mini-mappa](pics/map/minimap.png "Esempio di mini-mappa")

La mini-mappa, nell'angolo in alto a destra, fornisce una visione di insieme dell'intera mappa. Ci si può muovere rapidamente nella mappa cliccando e trascinando il mouse nella mini-mappa. Punti di diversi colori indicano differenti tipi di oggetti, ad esempio verde per le nostre unità, blu per quelle nemiche, magenta per sorgenti di magma libere. Costruendo un radar (si veda [Costruire strutture](#costruire-strutture)) si possono vedere tutti gli oggetti importanti nella mini-mappa, anche nelle zone inesplorate.

## Menù di gioco

Premendo F10 durante il gioco si può mettere in pausa la partita ed accedere al menù con le opzioni proprie del gioco, come salvare, abbandonare o cambiare la velocità. I tasti funzione associati ai vari sotto-menù (F5, F9, ecc.) possono essere premuti per accedere direttamente alle relative sezioni. Il sotto-menù "Aiuto" (F1) merita attenzione in quanto elenca una serie di scorciatoie da tastiera e consigli generali che forniscono funzionalità avanzate, non sempre elencate in questo manuale.

## Unità

Le unità (umani, veicoli, fabbriche, strutture, ecc.) risiedono sulla mappa, a meno che non sono attaccate e private di tutto il loro livello di salute, in tal caso sono distrutte e scompaiono. Per esempio il seguente è un ingegnere:

![Ingegnere](pics/units/engineer.png "Ingegnere")

Questo tipetto giallo è molto importante nel gioco. Non può combattere o difendersi, ma può [costruire strutture](#costruire-strutture) e [raccogliere risorse](#risorse), per cui ne parleremo in diversi punti del manuale. Come si può vedere, ogni unità indica il proprio livello di salute con una barra (quando non è al massimo). Quando la barra è vuota l'unità muore.

## Oggetti naturali

Il paesaggio include alberi e rocce che possono essere usati per raccogliere [risorse](#risorse). Gli alberi possono essere distrutti dalle nostre unità armate se sono di ostacolo.










# Azioni basilari: selezione e movimento

## Selezione

Una singola unità può essere selezionata cliccando su di essa con il tasto sinistro, come in questo esempio:

![Selezione singola](pics/map/select1.png "Selezione singola")

Più unità possono essere selezionate tenendo premuto il tasto shift (maiuscole) mentre si clicca.

Si possono selezionare tutte le unità di uno stesso tipo facendo doppio clic su una di esse:

![Selezione per tipo](pics/map/select2.png "Selezione per tipo")

Si può selezionare un gruppo di unità tracciando un rettangolo attorno ad esse con il tasto sinistro del mouse:

![Selezione rettangolare](pics/map/select3.png "Selezione tracciando un rettangolo")

(Nota: sembra esserci un limite al numero massimo di unità selezionabili contemporaneamente).

Quando un'unità è selezionata, a destra della mappa si possono vedere due riquadri: il suo stato attuale (livello di salute e caratteristiche) e un menù di azioni con diversi pulsanti, corrispondenti alle azioni che è possibile far compiere all'unità. Per esempio selezionando un ingegnere:

![Stato unità](pics/map/status-menu.png "Stato e menù azioni di un'unità")

Si può cliccare su ogni azione, o premere il tasto corrispondente sulla tastiera. Un'azione può mostrare un altro menù con maggiori dettagli. Si può muovere il puntatore del mouse sopra un pulsante per avere una descrizione di un dato elemento. Per ogni unità nel seguito saranno descritte le possibili azioni.

## Movimento

Quando una o più unità sono selezionate, queste possono essere spostate cliccando col tasto destro su una zona vuota (e raggiungibile) della mappa. Le unità cercheranno di trovare il percorso migliore, ognuna alla propria velocità. A volte cliccando con il tasto destro su un oggetto, invece che su un'area vuota, si può far compiere all'unità l'azione giusta per quell'oggetto, a seconda del tipo di unità. Quest'ultima modalità sarà spiegata quando necessario.










# Risorse

Per costruire il proprio crescente esercito, insieme alle strutture, alle difese, ecc., occorrono due tipi di risorse: **energia** e **magma** (minerali). Nella parte alta della mappa è presente un indicatore delle loro quantità e tasso di produzione:

![Indicatore energia e magma](pics/map/energy-magma.png "Indicatore di energia e magma")

Per ogni tipo di risorsa si può vedere la quantità che si sta producendo (segno +), la quantità che si sta consumando (segno -) e quella accumulata (accumulare riserve è possibile solo se si ha almeno un [vault](#vault-v)).

Le risorse vengono consumate quando gli ingegneri costruiscono oggetti o quando le fabbriche producono unità. Se la quantità prodotta è minore della richiesta, la produzione di unità e strutture rallenta o si ferma completamente.

Vediamo in maggiore dettaglio come raccogliere i due tipi di risorse.

## Energia

A un basso livello l'energia può essere raccolta dagli alberi. A questo scopo si può selezionare un ingegnere e scegliere l'azione "Harvest" (o premere H) nel menù azioni, quindi cliccare su un albero. Un modo più veloce è selezionare un ingegnere e cliccare con il tasto destro su un albero (attenzione: un albero va selezionato cliccando sulla sua base). Quando l'albero è esaurito, l'ingegnere si sposta ad un altro albero, e così via. Ecco un ingegnere intento a raccogliere energia da un albero:

![Raccogliere energia da alberi](pics/map/tree-harvest.png "Un ingegnere che raccoglie energia da un albero")

Il modo standard e più efficiente per generare energia, tuttavia, è costruire una centrale elettrica ("power plant" o "nuclear power plant", si veda [costruire strutture](#costruire-strutture)). Non appena si ha un'entrata minima di energia e magma si possono costruire una o più centrali elettriche ed avere una quantità illimitata di energia. Per questo motivo l'energia non è un grosso problema nell'economia del gioco.

## Magma

A un basso livello il magma può essere raccolto dalle rocce. Si può selezionare un ingegnere e usare gli stessi comandi visti per gli alberi per fargli raccogliere magma dalle rocce o dalle distese rocciose:

![Rocce](pics/map/rocks.png "Rocce e distese rocciose")

Le rocce durano per un tempo limitato, fino a che tutte quelle di un'area sono esaurite.

Il modo più efficiente è trovare delle sorgenti di magma e costruire delle pompe per magma su di esse. Una pompa fornisce un flusso continuo di magma. A questo scopo si può selezionare un ingegnere e scegliere l'azione "Build" (o premere B) nel menù azioni, quindi "Magma pump" (M) nel sotto-menù, infine cliccare sulla sorgente di magma per iniziare la costruzione. Un modo più veloce è selezionare un ingegnere e cliccare con il tasto destro sulla sorgente di magma. Di seguito sono raffigurate una sorgente di magma libera e una su cui è stata costruita una pompa:

![Sorgenti di magma](pics/map/magma.png "Sorgenti e pompe di magma")

(esiste anche una sorgente di magma più debole, non raffigurata qui).

Le sorgenti di magma sono spesso rare, e le rocce hanno una durata limitata, per cui il magma è spesso il problema maggiore nella gestione delle risorse. Assicuratevi di cercare nuove sorgenti non appena si espande il proprio dominio. Un buon flusso di magma è la chiave per costruire un esercito corposo velocemente.

(È anche possibile ottenere magma riciclando strutture esistenti, incluse le proprie, ma è un metodo molto inefficiente).

Se si vuole continuare a raccogliere risorse da alberi e rocce anche più avanti nel gioco, si può usare un harvester (si veda [costruire unità](#costruire-unità)), un veicolo specializzato nel raccogliere risorse in maniera più efficace. Si possono impartire ordini a tale veicolo come si fa con gli ingegneri.










# Costruire strutture

Le strutture fisse sono costruite dagli ingegneri. Tali strutture includono impianti di utilità generale, armi difensive e fabbriche che a loro volta possono produrre le unità da combattimento.

Per la sua importanza descriveremo di seguito in dettaglio l'ingegnere.

## L'ingegnere

![Ingegnere](pics/units/engineer.png "Ingegnere")

Un ingegnere può costruire le varie strutture fisse, come accennato, può raccogliere le [risorse](#risorse) in caso di necessità (come descritto in precedenza) e riparare oggetti.

Per costruire una struttura, selezionare un ingegnere e cliccare su uno dei seguenti pulsanti azione (o premere il tasto corrispondente):

- B (Build basic structures) per costruire strutture generiche.
- U (Build unit structures) per costruire fabbriche di unità da combattimento.
- D (Build defensive structures) per costruire armi di difesa.

Ogni sotto-menù elenca le possibili strutture da costruire, descritte nel seguito. Muovendo il puntatore del mouse sopra ognuna si può vedere una lista delle sue caratteristiche, oltre al costo in energia e magma per la sua costruzione (si vedano le immagini nella prossima sezione). In genere gli elementi in un sotto-menù sono ordinati per importanza, dalle unità più economiche ma più deboli fino alle più potenti (ma più dispendiose).

Una volta selezionata la struttura desiderata (cliccandovi o premendo il tasto corrispondente sulla tastiera), si deve cliccare su un'area vuota della mappa con spazio sufficiente per la struttura, la cui forma è indicata in corrispondenza del puntatore del mouse. Infine l'ingegnere inizierà la sua costruzione, come in questo esempio in cui un ingegnere sta costruendo una fabbrica di veicoli (vehicle factory):

![Ingegnere che costruisce una struttura](pics/structs/engineer-building.png "Un ingegnere che costruisce una struttura")

La costruzione impiega un certo tempo, con una barra che ne indica l'avanzamento. La barra scompare a costruzione ultimata, ma riappare se viene danneggiata, ad indicare il livello di salute.

Un ingegnere può anche riparare un oggetto danneggiato, o continuare la sua costruzione se non era stata ultimata. A questo scopo il modo più veloce è selezionare un ingegnere e cliccare col tasto destro sull'oggetto.

Si possono assegnare più ingegneri a costruire o riparare un oggetto se si vuole accelerare il processo (ma aumentando l'uso delle risorse); per far ciò si possono selezionare gli altri ingegneri e cliccare col tasto destro sull'oggetto su cui il primo ingegnere sta lavorando.

Se un ingegnere sta costruendo qualcosa e gli viene impartito un nuovo ordine, esso interromperà il lavoro attuale. Si possono però accodare più lavori per uno stesso ingegnere premendo il tasto shift (maiuscole) mentre si clicca: in tal modo i vari lavori verranno eseguiti in successione. Un'altra scorciatoia utile è premere ALT-I per trovare e selezionare automaticamente un ingegnere libero.

Infine gli ingegneri possono essere prodotti come tutte le altre unità se ne servono di più. Nello specifico sono prodotti dal [vault](#vault-v) o dal [training camp](#training-camp-c) (si veda nel seguito).

Suggerimento: assicuratevi di avere almeno un ingegnere vivo, o di avere fabbriche che possono produrli, o non sarete in grado di costruire nuovi oggetti o sostituire quelli distrutti.


## Strutture di base

![Sotto-menù basic structures](pics/structs/menu-basic.png "Sotto-menù basic structures")

### Vault ("V")

![Vault](pics/structs/vault.png "Vault")

Il vault può immagazzinare energia e magma, in modo da stoccarne delle riserve per un uso futuro, e può produrre nuovi ingegneri. Di solito un livello possiede un vault in partenza (ma non sempre).

### Magma pump ("M")

![Magma pump](pics/structs/magma-pump.png "Magma pump")

Una pompa di magma, costruita su una sorgente di magma, produce un flusso costante di magma. Si veda [risorse](#risorse) per una spiegazione approfondita.

### Radar ("R")

![Radar](pics/structs/radar.png "Radar")

Il radar può rivelare la posizione di oggetti importanti nella [mini-mappa](#mini-mappa), anche in aree inesplorate. Questo permette anche di puntare strutture lontane con armi a lungo raggio. Per queste ragioni è consigliabile averne uno.

### Camera ("C")

![Camera](pics/structs/camera.png "Camera")

La camera può fornire una visuale dell'area in cui è costruita, così da avere un'immagine aggiornata di quell'area.

### Power plant ("P")

![Power plant](pics/structs/power.png "Power plant")

Produce una quantità costante di energia. Si veda [risorse](#risorse).

### Nuclear power plant ("N")

![Nuclear power plant](pics/structs/nuclear.png "Nuclear")

Come il power plant, ma produce più energia. Si veda [risorse](#risorse).


## Strutture unità

Nota: i dettagli della costruzione di unità dalle varie strutture unità (fabbriche) sono forniti nel prossimo capitolo.

![Sotto-menù unit structures](pics/structs/menu-unit.png "Sotto-menù unit structures")

### Training camp ("C")

![Training camp](pics/structs/training-camp.png "Training camp")

Il campo di addestramento (training camp) "produce" combattenti di forma umana, di potenza variabile, più gli ingegneri.

### Hospital ("H")

![Hospital](pics/structs/hospital.png "Hospital")

L'ospedale (hospital) produce solo l'unità "medic".

### Vehicle factory ("V")

![Vehicle factory](pics/structs/vehicle-factory.png "Vehicle factory")

La fabbrica di veicoli (vehicle factory) produce veicoli da combattimento, come ad esempio i carri armati.

### Shipyard ("S")

![Shipyard](pics/structs/shipyard.png "Shipyard")

Il cantiere navale (shipyard) produce veicoli acquatici che possono muoversi e combattere in acqua. Lo shipyard deve essere costruito vicino all'acqua.

### Aircraft factory ("A")

![Aircraft factory](pics/structs/aircraft-factory.png "Aircraft factory")

La fabbrica di velivoli (aircraft factory) produce veicoli aerei che possono raggiungere ogni punto della mappa per esplorare o combattere.

## Strutture difensive

![Sotto-menù defensive structures](pics/structs/menu-defensive.png "Sotto-menù defensive structures")

### Gun turret ("G")

![Gun turret](pics/structs/gun-turret.png "Gun turret")

La torretta (gun turret) spara ai nemici non appena sono alla sua portata. Utile per creare una linea di difesa attorno alla propria base.

### Big gun turret ("B")

![Bin gun turret](pics/structs/big-gun-turret.png "Big gun turret")

La torretta grande (big gun turret) è simile alla torretta, ma più potente.

### Cannon ("C")

![Cannon](pics/structs/cannon.png "Cannon")

Il cannone (cannon) spara ad una grande distanza ed è abbastanza potente, tanto che in genere si è colpiti prima ancora di poterlo vedere (il suo colpo appare come una palla di fuoco azzurra). D'altra parte impiega molto tempo a ricaricarsi e non è molto preciso, specialmente con bersagli mobili. Per queste ragioni può essere visto più come un'arma offensiva che difensiva. Insieme al radar permette di colpire unità nemiche anche in aree inesplorate.

### Missile silo ("M")

![Missile silo](pics/structs/missile-silo.png "Missile silo")

Il silo missili (missile silo) può lanciare missili nucleari molto potenti su ogni bersaglio nella mappa, ma la sua costruzione è molto costosa e impiega molto tempo a ricaricarsi. Anche i missili possono puntare ai bersagli rivelati dal radar.










# Costruire unità

Una volta costruita una fabbrica per una determinata unità, come visto nelle sezioni precedenti, si può ordinare alla fabbrica di costruire delle unità, scelte tra quelle fornite dalla fabbrica.

Il meccanismo di produzione delle unità è lo stesso per tutte le fabbriche, per cui sarà spiegato solo nel primo caso.


## Unità da training camp

![Menù training camp](pics/units/menu-training.png "Menù training camp")

Il training camp può produrre le seguenti unità:

- Ingegnere.
- Assault unit, Grenadier, Bazoo: combattenti di forma umana di potenza (e costo) crescente. Sono più vulnerabili e meno letali dei veicoli, ma possono essere prodotti velocemente e possono quindi rappresentare una forza da stanziare rapidamente, specialmente in grandi quantità.

Per produrre unità da una fabbrica, selezionare la fabbrica e cliccare sull'unità che si desidera per iniziarne la produzione. Cliccando più unità è possibile accodarle in modo che la fabbrica le produca in serie. Per esempio nella figura seguente una serie di assault unit sono accodate per la produzione, come si può vedere dal riquadro di stato della fabbrica:

![Unità accodate per la produzione](pics/units/queued.png "Unità accodate per la produzione")

Una barra vicino alla fabbrica indica l'avanzamento della produzione di ogni unità. Nell'immagine seguente si può vedere la stessa fabbrica che sta producendo delle unità, assieme ad altre già terminate:

![Fabbrica che produce unità](pics/units/producing.png "Fabbrica che produce unità")

Il training camp (a differenza di tutte le altre fabbriche) include lo speciale comando "Set new units target" ("N"), che permette di cliccare su un punto della mappa per indicare dove le nuove unità prodotte devono raggrupparsi.

## Unità da hospital

![Menù hospital](pics/units/menu-hospital.png "Menù hospital")

L'hospital può produrre soltanto il Medico (Medic), che può curare le unità danneggiate, ma ha bisogno di tempo per ricaricarsi dopo ogni intervento.

## Unità da vehicle factory

![Menù vehicle factory](pics/units/menu-vehicle.png "Menù vehicle factory")

Le unità disponibili sono:

- APC smolder: veicolo da trasporto per altre unità. Si possono caricare e scaricare delle unità dal veicolo. Le unità possono combattere mentre sono nel veicolo.
- Harvester: il suo scopo è raccogliere [risorse](#risorse) in maniera più efficiente degli ingegneri, ma può essere facilmente distrutto dai nemici.
- Buggy: veicolo armato leggero ed economico, ma non molto forte.
- Tank, Rocket Tank, Artil: carri armati di varia potenza (e costo), più potenti in battaglia, hanno anche una portata di attacco maggiore in modo da poter colpire certi tipi di nemici senza esserne colpiti a loro volta.

## Unità da shipyard

![Menù shipyard](pics/units/menu-shipyard.png "Menù shipyard")

Le unità disponibili sono:

- Water Scout: veicolo non armato con funzione esplorativa.
- Destroyer: veicolo acquatico armato.

## Unità da aircraft factory

![Menù aircraft factory](pics/units/menu-aircraft.png "Menù aircraft factory")

Le unità disponibili sono:

- Heli: il veicolo aereo più debole.
- Jet Fighter, Bomber, Chopper: veicoli aerei con diversi gradi di portata, potenza di fuoco ed armatura.










# Combattimento

Quando le proprie unità sono a portata di elementi nemici, esse inizieranno ad attaccarle senza necessità di un intervento specifico dell'utente. Si muoveranno anche parzialmente avanti e indietro per meglio rispondere al fuoco, a seconda della loro portata di attacco. Se si vuole prima attaccare un bersaglio specifico, si possono selezionare le unità e cliccare espressamente con il tasto sinistro sul bersaglio (questo evita di dover richiamare l'azione "Attack" esplicitamente). È anche possibile distruggere oggetti che non sono nemici, come ad esempio gli alberi se sono di ostacolo, ma in questo caso occorre richiamare l'azione "Attack" (o premere semplicemente il tasto "A") e cliccare sull'oggetto. È anche possibile distruggere le proprie unità!

Suggerimento: se le unità si stanno muovendo verso una destinazione specifica e sono avvicinate da unità nemiche durante il percorso, esse non risponderanno al fuoco fintanto che si stanno muovendo. In tal caso si può farle fermare premendo il tasto "S" come scorciatoia (mentre sono selezionate) così che possano iniziare a combattere.










# Consigli di strategia

I seguenti sono una serie di suggerimenti generici da non intendere come regole, ma più come un aiuto per chi si avvicina a Bos Wars per la prima volta. Nel lungo periodo si tenderà a giocare secondo le proprie preferenze e la propria esperienza. Ricordatevi di iniziare con le mappe più piccole.

Prima di tutto assicuratevi di avere un flusso minimo di energia e magma. In alcuni livelli si inizia con alcune strutture già esistenti, in caso contrario assegnate degli ingegneri a raccogliere risorse da rocce e/o alberi. Se ci sono delle sorgenti di magma, costruite subito delle pompe di magma. Durante queste operazioni, ovviamente, esplorate le immediate vicinanze della base. Si hanno a disposizione degli ingegneri all'inizio del livello, ma ne potete produrre altri se avete un vault o un training camp (o li costruite). Tre ingegneri è un buon numero.

Con le prime quantità di energia e magma costruite delle centrali elettriche, in modo da avere una buona quantità di energia per il futuro.

Costruite un radar (non importa dove), è molto economico e rivelerà importanti dettagli nella [mini-mappa](#mini-mappa).

Quando avrete una buona quantità di energia e magma, pianificate quali unità produrre. I nemici non dormono, perciò non bisogna perdere tempo. Costruite quindi un paio di fabbriche, anche dello stesso tipo se volete produrre le unità più rapidamente. Nel frattempo costruite delle armi di difesa (torrette) lungo i bordi della base che ritenete più esposti, presto potreste ricevere visite indesiderate. Le unità prodotte dalle fabbriche possono fungere da linee di difesa dal proprio lato.

Se volete esplorare aree maggiori intorno a voi, inviate alcune unità ma non troppo lontano, inizialmente con poche unità rischiate che vengano distrutte in pochi secondi se incontrano gruppi di nemici.

Se state raccogliendo magma dalle rocce, costruite più che potete in questa fase, approfittando dell'afflusso maggiore di magma prima che le rocce si esauriscano.

Ad un certo punto vi sentirete abbastanza forti da compiere delle uscite con le vostre armate. Assicuratevi di avere un buon numero di unità prima di esplorare l'ignoto. Un esercito numeroso può distruggere un gruppo di nemici velocemente e senza grosse perdite, mentre con poche unità potreste facilmente vederle distrutte e dover ricominciare da capo, o peggio permettere al nemico di penetrare nella vostra base indisturbato.

Quando conquistate nuove aree, cercate di fortificarle difendendo gli accessi chiave. Idealmente potete trattarle come estensioni della vostra base mentre procedete, costruendovi nuove pompe di magma e fabbriche dopo che le vostre armate hanno distrutto tutte le strutture nemiche.

Quindi in poche parole: costruite, espandetevi, distruggete, ricominciate. Alla fine è abbastanza liberatorio!

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

All'avvio del programma c'è il menù iniziale, le cui voci sono abbastanza intuitive, perciò saranno descritte solo sommariamente.

Nota: l'interfaccia del menù è disponibile in varie lingue, tra cui l'italiano, selezionabili nella sezione "Opzioni" ("Options"). Tuttavia all'interno del gioco i vari oggetti sono denominati con il loro nome originale inglese, per cui nel seguito si utilizzeranno i nomi inglesi.

Alcune funzionalità sono al di là dello scopo di questo manuale, come per esempio l'editor delle mappe che permette di creare nuovi livelli partendo da zero o modificando un livello esistente.

Il pulsante "Opzioni" ("Options") permette di settare alcune impostazioni del gioco come la risoluzione video, l'audio, la velocità del gioco e così via.

"Carica" ("Load game") è per riprendere un gioco precedentemente salvato.

Infine "Inizia partita" ("Start game") permette di iniziare un nuovo gioco. Una volta premuto si può scegliere una delle mappe dalla lista a destra (inzialmente si possono ignorare le campagne ("campaigns"). Selezionando una mapppa si possono vederne i dettagli nella parte sinistra, in particolare le sue dimensioni, ad esempio 64x64 per le più piccole, fino a 256x256. Si consiglia vivamente di iniziare con le mappe più piccole se non si è ancora pratici con il gioco, e di lasciare tutte le opzioni al valore predefinito, almeno finché non si è un giocatore esperto. Premendo "Inizio" ("Start") si inizia il gioco vero e proprio.










# Mappa

![Mappa del gioco](pics/map/map.png "Esempio di mappa del gioco")

La mappa è dove si svolge il gioco. Si possono distinguere tre tipi di aree:

- Aree pienamente illuminate: aree nel campo visivo delle nostre unità, cioè dove è presente almeno una nostra unità. Grazie alla presenza fisica è possibile vedere cosa sta succedendo in tempo reale. Ogni unità ha una propria distanza visiva, in genere non molto vasta.
- Aree nere: inizialmente la maggior parte, sono aree dove il giocatore non è mai stato e che saranno scoperte una volta raggiunte. Questa caratteristica può essere disabilitata, in modo da vedere tutta la mappa dall'inizio, ma questo verosimilmente può compromettere le dinamiche del gioco.
- Aree offuscate (parzialmente illuminate): aree dove il giocatore è stato in precedenza, ma che adesso non hanno più nostre unità nelle vicinanze, ad esempio se tutte le unità sono state distrutte. Si può ancora vedere l'area, ma non quello che sta avvenendo attualmente; si può vedere solo una "fotografia" dell'ultima volta che una nostra unità era lì, così che l'area potrebbe ora essere piena di nemici, ma possiamo vederlo solo se delle nostre unità vi ritornano. Questa caratteristica è chiamata "nebbia di guerra" ("fog of war") e anch'essa può essere disabilitata, ma anche in questo caso ciò potrebbe togliere interesse al gioco.

Si può far scorrere la mappa nelle quattro direzioni muovendo il mouse vicino ai quattro bordi.

## Mini-mappa

![Mini-mappa](pics/map/minimap.png "Esempio di mini-mappa")

La mini-mappa, nell'angolo in alto a destra, dà una visione di insieme dell'intera mappa. Ci si può muovere rapidamente nella mappa cliccando e trascinando il mouse nella mini-mappa. Punti di diversi colori indicano differenti tipi di oggetti, ad esempio verde per le nostre unità, blu per quelle nemiche, magenta per sorgenti di magma libere. Costruendo un radar (si veda [Costruire strutture](#costruire-strutture)) si possono vedere tutti gli oggetti importanti nella mini-mappa, anche nelle zone inesplorate.

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

## Movimento










# Risorse

## Energia

## Magma










# Costruire strutture

## L'ingegnere

## Strutture di base

### Vault ("V")

### Magma pump ("M")

### Radar ("R")

### Camera ("C")

### Power plant ("P")

### Nuclear power plant ("N")


## Strutture unità

### Training camp ("C")

### Hospital ("H")

### Vehicle factory ("V")

### Shipyard ("S")

### Aircraft factory ("A")


## Strutture difensive

### Gun turret ("G")

### Big gun turret ("B")

### Cannon ("C")

### Missile silo ("M")










# Costruire unità
## Unità da training camp
## Unità da hospital
## Unità da vehicle factory
## Unità da shipyard
## Unità da aircraft factory










# Combattimento










# Consigli di strategia


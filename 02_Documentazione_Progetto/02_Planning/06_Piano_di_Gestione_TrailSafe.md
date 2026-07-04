# Piano di gestione - TrailSafe

## 1. Obiettivo del documento

Questo documento descrive come verrà gestito il progetto TrailSafe durante le fasi di analisi, progettazione, sviluppo, test e rilascio della versione pilota.

Il piano serve a definire alcune regole comuni per comunicazione, qualità, monitoraggio dell'avanzamento, gestione dei problemi, modifiche allo scope e controllo della documentazione. L'obiettivo non è appesantire il lavoro con procedure inutili, ma mantenere il progetto tracciabile e ridurre il rischio di decisioni prese in modo poco chiaro.

In caso di dubbi, il Project Manager sarà il primo riferimento operativo e avrà il compito di coinvolgere committente, sponsor o team tecnico quando la decisione supera la gestione ordinaria.

---

## 2. Comunicazione

La comunicazione del progetto sarà organizzata con incontri brevi ma regolari. Le riunioni serviranno soprattutto a verificare l'avanzamento, chiarire dubbi sui requisiti e intercettare in anticipo eventuali blocchi.

| Comunicazione | Partecipanti | Frequenza | Modalità |
|---|---|---|---|
| Riunione operativa | Project Manager e team | Settimanale | Online o in presenza |
| Riunione di avanzamento | Project Manager e committente | Ogni due settimane | Online o in presenza |
| Revisione dei requisiti | Committente, Business Analyst e Project Manager | Al termine dell'analisi | Riunione di validazione |
| Revisione del prototipo | Committente, UX/UI Designer e referente amministratori | Prima dello sviluppo completo | Presentazione e raccolta feedback |
| Revisione dei rischi | Project Manager e responsabili coinvolti | Mensile, o prima se necessario | Riunione breve |
| Riunione finale | Sponsor, committente e team | A fine progetto | In presenza o online |

Per ogni riunione rilevante dovrà rimanere una traccia sintetica, con:

- ordine del giorno;
- partecipanti;
- decisioni prese;
- attività assegnate e relativo responsabile;
- eventuali punti aperti;
- breve sintesi dello svolgimento.

Le decisioni che incidono su scope, tempi, costi o priorità dovranno essere riportate anche nei documenti di progetto interessati.

---

## 3. Gestione della qualità

La qualità verrà controllata lungo tutto il progetto, non solo alla fine. In questo modo eventuali problemi potranno essere corretti prima che diventino costosi o difficili da gestire.

I controlli principali saranno:

- revisione dei requisiti con il committente;
- controllo del prototipo prima dello sviluppo completo;
- verifica delle funzionalità durante lo sviluppo;
- test di integrazione tra i moduli;
- test con utenti pilota e amministratori;
- verifica finale con il committente prima dell'accettazione.

### Criteri principali

La piattaforma dovrà:

- funzionare correttamente da browser desktop e mobile;
- consentire l'accesso solo agli utenti autorizzati;
- mostrare in modo chiaro sentieri, schede percorso e informazioni ambientali;
- gestire gli errori dei servizi esterni, come mappe e meteo;
- permettere agli amministratori di verificare e gestire le segnalazioni;
- proteggere i dati personali degli utenti;
- rispettare i requisiti ad alta priorità definiti nello scope.

I problemi trovati durante i test saranno registrati, classificati per priorità e assegnati a un responsabile. La chiusura di un problema dovrà essere verificata prima di considerarlo risolto.

---

## 4. Monitoraggio del progetto

Il Project Manager controllerà l'avanzamento confrontando il lavoro completato con il piano previsto. Il monitoraggio servirà anche a capire se è necessario rivedere priorità, risorse o scadenze.

Saranno controllati in particolare:

- attività completate;
- attività in ritardo;
- scadenze principali;
- costi sostenuti rispetto al budget;
- rischi aperti o in aumento;
- problemi tecnici non risolti;
- modifiche richieste dal committente o dal team.

### Indicatori utilizzati

| Indicatore | Frequenza di controllo |
|---|---|
| Percentuale di attività completate | Settimanale |
| Ritardo rispetto al Gantt | Settimanale |
| Costi sostenuti rispetto al budget | Mensile |
| Numero di rischi aperti | Ogni due settimane |
| Numero di problemi non risolti | Settimanale |
| Requisiti completati | A ogni revisione significativa |
| Modifiche allo scope richieste o approvate | Quando emergono |

In caso di ritardo o scostamento rilevante, il Project Manager valuterà con il team una o più azioni correttive:

- modifica delle priorità;
- redistribuzione delle attività;
- spostamento di risorse sulle funzioni più critiche;
- riduzione o rinvio di funzioni non essenziali per l'MVP;
- aggiornamento del piano e comunicazione al committente.

---

## 5. Gestione dei problemi

Ogni problema rilevante emerso durante sviluppo, test o rilascio dovrà essere registrato. Questo permette di evitare perdite di informazioni e di seguire lo stato delle correzioni.

Il registro dei problemi includerà:

- descrizione del problema;
- data di apertura;
- area o funzionalità interessata;
- priorità;
- responsabile assegnato;
- soluzione prevista o azione proposta;
- stato aggiornato.

Gli stati utilizzati saranno:

- **aperto**, quando il problema è stato registrato ma non ancora preso in carico;
- **in lavorazione**, quando è in corso un'attività di analisi o correzione;
- **risolto**, quando è stata applicata una soluzione;
- **chiuso**, quando la soluzione è stata verificata.

I problemi urgenti, soprattutto se possono bloccare il rilascio o compromettere requisiti ad alta priorità, dovranno essere comunicati subito al Project Manager.

---

## 6. Gestione delle modifiche

Le modifiche potranno riguardare requisiti, funzionalità, tempi, costi, risorse o servizi esterni. Non tutte le richieste avranno lo stesso peso: alcune potranno essere gestite all'interno del lavoro ordinario, mentre altre richiederanno una valutazione formale.

### Procedura

1. La richiesta viene registrata con una breve descrizione.
2. Il Project Manager valuta se la modifica incide su scope, tempi, costi o rischi.
3. Il team fornisce, se necessario, una stima di impatto tecnico e operativo.
4. Il committente approva o rifiuta la richiesta quando l'impatto è rilevante.
5. I documenti interessati vengono aggiornati.
6. La decisione viene comunicata al team e inserita nel piano di lavoro.

Le modifiche minori, che non incidono su budget, durata o requisiti ad alta priorità, possono essere gestite dal Project Manager.

Le modifiche che cambiano lo scope dell'MVP, aumentano il budget o spostano la data di rilascio devono essere approvate dallo Sponsor / Committente prima di essere applicate.

---

## 7. Gestione dei documenti

I documenti di progetto saranno salvati nella cartella condivisa del progetto e mantenuti aggiornati durante le fasi principali. Ogni documento dovrà essere identificabile in modo chiaro, così da evitare l'uso di versioni superate.

Per ogni documento saranno indicati, quando necessario:

- nome del documento;
- versione;
- data di aggiornamento;
- autore o responsabile;
- stato del documento.

Gli stati previsti sono:

- **bozza**, quando il documento è in preparazione;
- **in revisione**, quando è in attesa di controllo o commenti;
- **approvato**, quando è stato validato e può essere usato come riferimento;
- **archiviato**, quando non è più la versione corrente ma deve essere conservato.

Solo le versioni approvate saranno considerate ufficiali per decisioni, verifiche e accettazione del progetto.

---

## 8. Approvazioni principali

Le approvazioni servono a confermare i passaggi più importanti del progetto e a mantenere allineati team e committente.

Saranno richieste approvazioni nei seguenti momenti:

1. avvio del progetto;
2. approvazione dei requisiti e dello scope dell'MVP;
3. approvazione del prototipo;
4. autorizzazione al rilascio della versione pilota;
5. accettazione finale da parte del committente;
6. chiusura del progetto.

Ogni approvazione dovrà essere tracciata con una breve nota, un verbale o un aggiornamento del documento interessato. Eventuali condizioni o riserve espresse dal committente dovranno essere riportate insieme alla decisione.

---

<nav class="next-page">
  <a href="../03_Execution/01_Backlog_e_Piano_Iterazioni_TrailSafe.md">Pagina successiva: Backlog e piano iterazioni &rarr;</a>
</nav>

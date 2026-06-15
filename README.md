# TrailSafe - Elaborato di Project Management

## Descrizione

Questo repository contiene l'elaborato di Project Management relativo a **TrailSafe**, una piattaforma web pensata per migliorare la consultazione dei sentieri escursionistici e rendere piu accessibili informazioni su condizioni ambientali, chiusure e situazioni di rischio.

L'obiettivo dell'elaborato non e sviluppare il software, ma simulare e documentare la gestione completa del progetto: avvio, pianificazione, esecuzione, monitoraggio, controllo e chiusura.

TrailSafe viene trattato come un progetto commissionato da un ente parco territoriale. La prima versione prevista e un **MVP** per un'area geografica pilota, con circa 20-30 sentieri iniziali.

---

## Obiettivo del progetto

La piattaforma TrailSafe consente agli escursionisti di:

- consultare l'elenco dei sentieri;
- visualizzare i percorsi su una mappa interattiva;
- leggere informazioni su difficolta, durata, lunghezza e stato dei percorsi;
- ricevere informazioni meteorologiche e avvisi;
- inviare segnalazioni relative a ostacoli o situazioni di pericolo;
- salvare i percorsi preferiti.

La piattaforma comprende anche un'area amministrativa per:

- gestire i sentieri;
- aggiornare lo stato dei percorsi;
- verificare e moderare le segnalazioni;
- pubblicare avvisi e chiusure.

Non fanno parte dell'MVP applicazioni mobili native, localizzazione continua, gestione diretta delle emergenze, copertura nazionale e manutenzione pluriennale successiva al progetto.

---

## Scenario di progetto

| Voce | Valore |
|---|---|
| Titolo | TrailSafe - Piattaforma web per la sicurezza sui sentieri escursionistici |
| Committente ipotetico | Ente Parco territoriale |
| Tipologia | Progetto di sviluppo di una piattaforma web |
| Risultato atteso | MVP funzionante per un'area pilota |
| Utenti principali | Escursionisti e amministratori |
| Durata prevista | Circa 5 mesi |
| Budget massimo indicativo | 75.000 euro |
| Area pilota | Circa 20-30 sentieri |
| Approccio | Ibrido: tradizionale e iterativo/Agile |

---

## Approccio di Project Management

Per TrailSafe e stato scelto un approccio **ibrido**.

La parte iniziale del progetto e stata gestita con una pianificazione tradizionale, utile per definire in modo chiaro:

- obiettivi;
- scope;
- deliverable;
- tempi;
- costi;
- responsabilita;
- rischi;
- criteri di accettazione.

La parte di realizzazione delle funzionalita e stata invece organizzata in iterazioni, cosi da poter gestire priorita, verifiche periodiche e possibili modifiche senza perdere il controllo generale del progetto.

Questa scelta permette di mantenere equilibrio tra controllo e flessibilita: budget, tempi e milestone restano monitorati, mentre le funzionalita dell'MVP possono essere sviluppate e validate in modo incrementale.

---

## Struttura del repository

```text
TrailSafePM/
|
|-- README.md
|
|-- 01_Descrizione_Approccio/
|   |-- Descrizione_Approccio_TrailSafe.md
|
|-- 02_Documentazione_Progetto/
    |-- 01_Initiating/
    |   |-- Business_Case_TrailSafe.md
    |   |-- Project_Charter_TrailSafe.md
    |   |-- Stakeholder_Register_TrailSafe.md
    |   |-- Obiettivi_Vincoli_Criteri_Successo.md
    |
    |-- 02_Planning/
    |   |-- 01_Scope_e_Requisiti_TrailSafe.md
    |   |-- 02_PBS_e_WBS_TrailSafe.md
    |   |-- 03_Organizzazione_e_RACI_TrailSafe.md
    |   |-- 04_Tempi_Costi_e_Gantt_TrailSafe.xlsx
    |   |-- 05_Analisi_dei_Rischi_TrailSafe.md
    |   |-- 06_Piano_di_Gestione_TrailSafe.md
    |
    |-- 03_Execution/
    |   |-- 01_Backlog_e_Piano_Iterazioni_TrailSafe.md
    |   |-- 02_Kickoff_e_Riunioni_TrailSafe.md
    |   |-- 03_Registro_Decisioni_e_Attivita_TrailSafe.md
    |
    |-- 04_Monitoring_controlling/
    |   |-- 01_Report_Avanzamento_e_KPI_TrailSafe.md
    |   |-- 02_Registro_Problemi_Modifiche_e_Rischi_TrailSafe.md
    |
    |-- 05_Closing/
        |-- 01_Accettazione_e_Chiusura_TrailSafe.md
        |-- 02_Lessons_Learned_e_Riunione_Finale_TrailSafe.md
```

---

## Contenuto dell'elaborato

### 1. Descrizione dell'approccio

La cartella `01_Descrizione_Approccio` contiene la relazione principale dell'elaborato.

La relazione spiega:

- scenario e obiettivi del progetto;
- motivazioni della scelta dell'approccio ibrido;
- gestione delle fasi di initiating, planning, execution, monitoring & controlling e closing;
- collegamento tra l'approccio scelto e i documenti prodotti;
- considerazioni finali su risultati, criticita e miglioramenti possibili.

### 2. Initiating

La sezione di avvio contiene:

- Business Case;
- Project Charter;
- Stakeholder Register;
- obiettivi, vincoli e criteri di successo.

Questi documenti definiscono il problema da risolvere, la soluzione proposta, gli stakeholder principali, le assunzioni iniziali e l'autorizzazione formale all'avvio del progetto.

### 3. Planning

La sezione di pianificazione contiene:

- Scope e requisiti;
- PBS e WBS;
- organizzazione del team e matrice RACI;
- piano tempi, costi e diagramma di Gantt in formato Excel;
- analisi dei rischi;
- piano di gestione.

Questi documenti definiscono cio che rientra nell'MVP, le attivita necessarie, le responsabilita, il budget, le milestone, i rischi e le regole di gestione del progetto.

### 4. Execution

La sezione di esecuzione contiene:

- Product Backlog e piano delle iterazioni;
- verbale di kick-off e riunioni di avanzamento;
- registro delle decisioni e delle attivita.

Il lavoro e simulato in cinque iterazioni: utenti e accesso, mappa e sentieri, meteo e segnalazioni, area amministrativa, test e rilascio.

### 5. Monitoring e Controlling

La sezione di monitoraggio e controllo contiene:

- report di avanzamento e KPI;
- registro di problemi, modifiche e rischi.

Il monitoraggio simula uno stato intermedio del progetto, con un lieve ritardo tecnico sull'integrazione del servizio meteo e relative azioni correttive.

### 6. Closing

La sezione di chiusura contiene:

- verifica dei deliverable e accettazione finale;
- confronto tra pianificato e risultato;
- attivita residue non bloccanti;
- lessons learned;
- verbale della riunione finale.

La simulazione si conclude con l'accettazione dell'MVP e la chiusura formale del progetto.

---

## Stato di avanzamento

| Area | Stato |
|---|---|
| Descrizione dell'approccio | Completata |
| Initiating | Completato |
| Planning | Completato |
| Execution | Completato |
| Monitoring e Controlling | Completato |
| Closing | Completato |
| File Gantt, tempi e costi | Presente in formato Excel |

---

## Nota

Tutti i dati relativi a durata, budget, team, committente, area geografica e stato di avanzamento sono definiti a scopo didattico e fanno parte della simulazione di Project Management.

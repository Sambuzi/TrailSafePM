# PBS e WBS - TrailSafe

## 1. Obiettivo del documento

Questo documento scompone il progetto TrailSafe in due viste complementari: da una parte il prodotto da realizzare, dall'altra il lavoro necessario per arrivare al rilascio della versione pilota.

La PBS descrive i componenti principali della piattaforma. La WBS, invece, organizza le attività operative che il team dovrà seguire durante il progetto.

Questa distinzione aiuta a evitare ambiguità: prima si chiarisce cosa deve esistere nel prodotto finale, poi si definisce come costruirlo, verificarlo e consegnarlo.

---

## 2. PBS - Product Breakdown Structure

La PBS di TrailSafe parte dalla piattaforma nel suo insieme e la divide nei blocchi che compongono l'MVP. Ogni blocco rappresenta una parte riconoscibile del prodotto e sarà poi collegato alle attività di analisi, sviluppo, test e rilascio.

### 1. Piattaforma TrailSafe

#### 1.1 Area utenti

L'area utenti raccoglie le funzioni legate all'accesso personale alla piattaforma e alla gestione minima del profilo.

- registrazione dell'utente;
- accesso alla piattaforma;
- gestione base del profilo;
- salvataggio dei sentieri preferiti.

#### 1.2 Mappa e sentieri

Questa è la parte centrale del servizio, perché permette agli utenti di esplorare i percorsi disponibili nell'area pilota.

- mappa interattiva;
- visualizzazione dei percorsi;
- scheda informativa del sentiero;
- punti di interesse;
- stato aggiornato del percorso.

#### 1.3 Informazioni ambientali

Le informazioni ambientali servono a dare contesto alla consultazione del sentiero e a supportare una scelta più consapevole prima dell'escursione.

- dati meteorologici;
- condizioni del sentiero;
- avvisi di chiusura, pericolo o manutenzione.

#### 1.4 Segnalazioni

Il modulo segnalazioni consente agli utenti di comunicare problemi o situazioni rilevanti riscontrate sui percorsi. Le segnalazioni non diventano automaticamente informazioni ufficiali: dovranno essere verificate dagli amministratori.

- invio di una segnalazione;
- inserimento di descrizione e posizione;
- gestione dello stato della segnalazione;
- verifica prima dell'eventuale pubblicazione o aggiornamento del sentiero.

#### 1.5 Area amministrativa

L'area amministrativa permette al personale autorizzato di mantenere aggiornati i contenuti principali della piattaforma.

- gestione dei sentieri;
- gestione degli utenti;
- controllo e lavorazione delle segnalazioni;
- pubblicazione di avvisi e chiusure.

#### 1.6 Documentazione

La documentazione accompagna il rilascio e serve sia per la consegna del progetto sia per l'uso ordinario della piattaforma da parte degli amministratori.

- manuale sintetico per gli amministratori;
- documentazione tecnica essenziale;
- documentazione finale del progetto.

---

## 3. WBS - Work Breakdown Structure

La WBS traduce i componenti della PBS in attività di progetto. Le fasi non vanno lette come blocchi completamente isolati: alcune attività, come il confronto con il committente o la verifica dei requisiti, potranno ripetersi più volte durante lo sviluppo.

### 1. Gestione del progetto

- avvio del progetto;
- pianificazione iniziale;
- riunioni di avanzamento;
- controllo di tempi, costi e rischi;
- gestione delle modifiche allo scope;
- chiusura del progetto.

### 2. Analisi

- raccolta dei requisiti;
- confronto con il committente e con i referenti dell'ente;
- definizione dello scope dell'MVP;
- verifica dei dati disponibili sui sentieri;
- validazione dei requisiti principali.

### 3. Progettazione

- progettazione dell'interfaccia utente;
- definizione della struttura della piattaforma;
- progettazione del database;
- scelta dei servizi esterni per mappe e meteo;
- definizione dei flussi principali per utenti e amministratori.

### 4. Sviluppo

- sviluppo dell'area utenti;
- sviluppo della mappa e della visualizzazione dei sentieri;
- sviluppo delle schede dei percorsi;
- integrazione del servizio meteo;
- sviluppo del modulo segnalazioni;
- sviluppo dell'area amministrativa;
- gestione degli avvisi e dello stato dei percorsi.

### 5. Test

- test delle singole funzioni;
- test di integrazione tra moduli;
- verifica dei dati mostrati su mappa e schede sentiero;
- test con utenti pilota e amministratori;
- correzione dei problemi emersi.

### 6. Rilascio

- preparazione dell'ambiente di rilascio;
- caricamento dei dati iniziali dei sentieri;
- verifica finale della versione pilota;
- formazione breve degli amministratori;
- pubblicazione dell'MVP.

### 7. Chiusura

- verifica dei deliverable consegnati;
- accettazione da parte del committente;
- raccolta delle lesson learned;
- archiviazione dei documenti di progetto;
- chiusura amministrativa del progetto.

---

## 4. Collegamento tra PBS e WBS

Il collegamento tra PBS e WBS permette di controllare che ogni parte del prodotto abbia attività coerenti di progettazione, sviluppo e verifica. In questo modo si riduce il rischio di avere componenti descritti nei requisiti ma non coperti dal piano di lavoro.

| Componente PBS | Attività WBS principali |
|---|---|
| Area utenti | Analisi dei requisiti, progettazione dei flussi, sviluppo e test |
| Mappa e sentieri | Progettazione, integrazione mappe, sviluppo delle schede e verifica dei dati |
| Informazioni ambientali | Scelta dei servizi esterni, integrazione, gestione errori e test |
| Segnalazioni | Analisi del flusso, sviluppo del modulo, verifica amministrativa e test |
| Area amministrativa | Progettazione, sviluppo, controllo accessi e test con amministratori |
| Documentazione | Preparazione manuali, raccolta materiali di progetto, consegna e chiusura |

---

## 5. Work package principali

I work package principali del progetto sono:

1. analisi dei requisiti e conferma dello scope;
2. progettazione dell'interfaccia e dei flussi principali;
3. sviluppo dell'area utenti;
4. sviluppo della mappa e delle schede sentiero;
5. integrazione di meteo e informazioni ambientali;
6. sviluppo del modulo segnalazioni;
7. sviluppo dell'area amministrativa;
8. test della piattaforma con dati pilota;
9. rilascio della versione MVP;
10. formazione, documentazione e chiusura del progetto.

Questi work package saranno usati come base per assegnare responsabilità, stimare tempi e costi, individuare le dipendenze e seguire l'avanzamento del progetto. Eventuali variazioni rilevanti dovranno essere valutate insieme allo scope, perché potrebbero incidere su tempi, budget o priorità di rilascio.

---

<nav class="next-page">
  <a href="03_Organizzazione_e_RACI_TrailSafe.md">Pagina successiva: Organizzazione e RACI &rarr;</a>
</nav>

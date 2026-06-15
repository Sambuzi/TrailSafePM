# Descrizione dell’Approccio Utilizzato – TrailSafe

## 1. Introduzione

L’elaborato riguarda la gestione del progetto TrailSafe, una piattaforma web pensata per migliorare la consultazione dei sentieri escursionistici e rendere più accessibili le informazioni relative a condizioni ambientali, chiusure e situazioni di rischio.

L’idea nasce da un progetto software già sviluppato in precedenza, ma in questo elaborato l’attenzione non è posta sull’implementazione tecnica. L’obiettivo è simulare la gestione completa del progetto, dall’avvio fino alla chiusura.

Per rendere il lavoro realistico, TrailSafe è stato impostato come un progetto commissionato da un ente parco territoriale. La prima versione della piattaforma viene trattata come un MVP (minimum viable product) per chiarezza userò nel corso del mio elaborato solo l'acronimo, limitato a un’area pilota e a un numero iniziale di circa 20–30 sentieri.

---

## 2. Scelta dell’approccio

Per il progetto è stato scelto un approccio ibrido.

La parte iniziale è stata gestita con una pianificazione tradizionale. Sono stati definiti in anticipo:

- obiettivi;
- scope;
- deliverable;
- tempi;
- costi;
- ruoli;
- rischi;
- criteri di accettazione.

Per la realizzazione delle funzionalità è stato invece adottato un approccio iterativo. Il lavoro è stato diviso in più iterazioni, ognuna dedicata a un gruppo di funzioni.

La scelta è stata fatta perché alcune parti del progetto possono essere definite fin dall’inizio, mentre altre possono richiedere modifiche durante lo sviluppo. Ad esempio, obiettivi, budget e durata devono essere controllati fin dall’avvio. L’interfaccia, le integrazioni con mappe e meteo e alcune funzioni utente possono invece essere migliorate attraverso varie verifiche periodiche.

Un approccio completamente tradizionale sarebbe risultato meno flessibile. Un approccio completamente Agile avrebbe invece reso meno chiaro il controllo iniziale di budget, milestone e responsabilità.

---

## 3. Scoping e Initiating

La prima fase è stata dedicata alla definizione del progetto.

Il **Business Case** spiega il problema da risolvere, le alternative considerate e i benefici attesi. La soluzione scelta è la realizzazione di un MVP, perché permette di verificare l’utilità della piattaforma senza avviare subito un progetto troppo ampio.

Il **Project Charter** autorizza formalmente l’avvio e riassume obiettivi, scope iniziale, stakeholder, vincoli, assunzioni e rischi principali.

Lo **Stakeholder Register** identifica le persone e i gruppi coinvolti. Per ogni stakeholder sono stati valutati interesse, influenza e modalità di coinvolgimento.

In questa fase è stato deciso di mantenere uno scenario semplice:

- committente rappresentato da un ente parco;
- area geografica pilota;
- durata di circa cinque mesi;
- budget massimo indicativo di 75.000 euro;
- team di progetto di dimensioni contenute.

Queste ipotesi servono a rendere la simulazione coerente e permettono di sviluppare i documenti successivi.

---

## 4. Planning

La fase di pianificazione è stata divisa in sei documenti principali.

### Scope e requisiti

Il documento **Scope e Requisiti** definisce ciò che deve essere realizzato e ciò che resta escluso.

Tra le funzioni principali sono comprese:

- gestione degli utenti;
- consultazione dei sentieri;
- mappa interattiva;
- informazioni meteorologiche;
- segnalazioni;
- area amministrativa.

Sono invece escluse funzioni come l’app mobile nativa, la localizzazione continua e la gestione diretta delle emergenze.

La distinzione tra attività incluse ed escluse serve a limitare lo scope e a ridurre il rischio di aggiungere nuove funzionalità durante il progetto.

### PBS e WBS

La **PBS** suddivide il prodotto nei suoi componenti principali.

La **WBS** suddivide invece il lavoro nelle attività necessarie per realizzare il prodotto.

I principali work package riguardano:

- analisi;
- progettazione;
- sviluppo;
- integrazioni;
- test;
- rilascio;
- chiusura.

Questa suddivisione è stata utilizzata come base per assegnare responsabilità, tempi e costi.

### Organizzazione e RACI

Il documento **Organizzazione e RACI** definisce i ruoli del team e chiarisce chi svolge, approva, viene consultato o informato per ogni attività.

La matrice è stata mantenuta semplice, utilizzando pochi ruoli prevesti per il prgetto:

- Sponsor;
- Project Manager;
- Business Analyst;
- UX/UI Designer;
- sviluppatori;
- tester;
- referente del committente.

In un progetto di dimensioni contenute alcuni ruoli possono essere ricoperti dalla stessa persona.

### Tempi, costi e Gantt

La pianificazione temporale è stata realizzata in un file Excel.

Il file contiene:

- attività;
- durate;
- dipendenze;
- milestone;
- diagramma di Gantt;
- stima dei costi;
- budget complessivo.

La durata prevista è di circa cinque mesi. Le attività tecniche sono in parte sovrapposte per ridurre il tempo totale.

Il piano dei costi comprende personale, servizi esterni, infrastruttura, test, documentazione e una riserva per gli imprevisti.

### Analisi dei rischi

L’analisi dei rischi considera rischi tecnici, organizzativi, operativi e di progetto.

Per ogni rischio sono stati indicati:

- probabilità;
- impatto;
- priorità;
- responsabile;
- azione prevista.

I rischi più importanti riguardano la qualità dei dati sui sentieri, i servizi meteo e cartografici, i ritardi e l’aumento dei requisiti.

### Piano di gestione

Il **Piano di Gestione** raccoglie in un solo documento:

- comunicazione;
- qualità;
- monitoraggio;
- gestione dei problemi;
- gestione delle modifiche;
- gestione dei documenti.

Questa scelta evita di creare molti file separati e mantiene la documentazione più semplice da consultare.

---

## 5. Launching ed Execution

La fase di esecuzione è stata organizzata in iterazioni.

Il **Backlog e Piano delle Iterazioni** raccoglie le principali funzionalità sotto forma di user story e le divide in cinque iterazioni:

1. utenti e accesso;
2. mappa e sentieri;
3. meteo e segnalazioni;
4. area amministrativa;
5. test e rilascio.

Le funzioni ad alta priorità devono essere completate prima della consegna. Le funzioni a priorità media possono essere rinviate se causano ritardi o aumento dei costi.

Le riunioni principali sono raccolte nel documento **Kick-off e Riunioni di Progetto**.

Per ogni incontro sono stati riportati:

- partecipanti;
- ordine del giorno;
- sintesi;
- decisioni;
- attività assegnate.

Sono stati simulati il kick-off, la revisione dei requisiti, una riunione di avanzamento e la preparazione al rilascio.

Il **Registro Decisioni e Attività** collega le decisioni prese durante gli incontri alle attività operative. I codici che iniziano con D identificano le decisioni, mentre quelli che iniziano con A identificano le attività.

---

## 6. Monitoring e Controlling

Il controllo del progetto è stato simulato attraverso due documenti.

Il **Report di Avanzamento e KPI** mostra la situazione del progetto in un momento intermedio.

Il report considera:

- attività completate;
- attività in corso;
- ritardi;
- costi;
- requisiti completati;
- problemi aperti;
- azioni correttive.

Durante il progetto è stato simulato un ritardo legato all’integrazione del servizio meteo. Il ritardo viene gestito dando priorità alle funzionalità essenziali e rinviando alcune funzioni secondarie.

Il **Registro Problemi, Modifiche e Rischi** raccoglie:

- problemi emersi;
- richieste di modifica;
- aggiornamento dei rischi.

Le modifiche che incidono su scope, budget o durata devono essere valutate dal Project Manager e approvate dal committente o dallo Sponsor.

Questo permette di mantenere il controllo sul progetto e di evitare modifiche non concordate.

---

## 7. Closing

La fase di chiusura serve a verificare che il progetto possa essere formalmente concluso.

Il documento **Accettazione e Chiusura** controlla:

- deliverable consegnati;
- requisiti completati;
- tempi;
- costi;
- attività ancora aperte;
- accettazione del committente.

Le attività residue sono considerate non bloccanti e possono essere valutate in una fase successiva.

Il documento **Lessons Learned e Riunione Finale** raccoglie invece ciò che ha funzionato, i problemi incontrati e i possibili miglioramenti.

Tra gli aspetti positivi sono stati individuati:

- uso dell’MVP;
- controllo dello scope;
- incontri periodici;
- sviluppo per iterazioni;
- test con utenti pilota.

Tra gli aspetti da migliorare:

- verifica anticipata dei servizi esterni;
- maggiore controllo iniziale dei dati;
- più tempo per i test su dispositivi mobili.

La riunione finale formalizza l’accettazione e la chiusura del progetto.

---

## 8. Documentazione allegata

La documentazione del progetto è organizzata nelle seguenti cartelle:

### Initiating

- Business Case;
- Project Charter;
- Stakeholder Register.

### Planning

- Scope e Requisiti;
- PBS e WBS;
- Organizzazione e RACI;
- Tempi, Costi e Gantt;
- Analisi dei Rischi;
- Piano di Gestione.

### Execution

- Backlog e Piano delle Iterazioni;
- Kick-off e Riunioni di Progetto;
- Registro Decisioni e Attività.

### Monitoring & Controlling

- Report di Avanzamento e KPI;
- Registro Problemi, Modifiche e Rischi.

### Closing

- Accettazione e Chiusura;
- Lessons Learned e Riunione Finale.

---

## 9. Considerazioni finali

Con questo elaborato ho cercato di rappresentare la gestione di TrailSafe in modo semplice ma completo, seguendo tutte le fasi principali di un progetto.

La scelta dell'approccio ibrido mi è sembrata la più adatta, perché permette di avere una pianificazione iniziale chiara, ma lascia anche un po' di flessibilità durante lo sviluppo delle funzionalità. In un progetto come questo, infatti, alcune cose devono essere definite fin dall'inizio, come tempi, costi, responsabilità e obiettivi, mentre altre possono cambiare dopo i primi confronti con utenti e committente.

Un aspetto importante emerso durante la simulazione è il controllo dello scope. Aggiungere nuove funzioni può sembrare utile, ma rischia facilmente di aumentare tempi, costi e complessità. Per questo TrailSafe è stato impostato come MVP, concentrandosi prima sulle funzioni davvero necessarie per avere una versione iniziale utilizzabile.

Nel complesso, il lavoro mi ha permesso di capire meglio quanto sia importante organizzare un progetto prima di passare alla parte operativa. Anche se TrailSafe è una simulazione, la documentazione prodotta aiuta a vedere in modo più concreto come un'idea iniziale possa essere trasformata in un progetto pianificato, controllato e concluso.

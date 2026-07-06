# Project Charter – TrailSafe

## 1. Informazioni generali

| Voce | Contenuto |
|---|---|
| **Nome del progetto** | TrailSafe |
| **Titolo completo** | TrailSafe – Piattaforma web per la sicurezza sui sentieri escursionistici |
| **Tipologia** | Progetto di sviluppo software |
| **Committente** | Ente territoriale / Ente Parco (scenario simulato) |
| **Project Manager** | Sajmir Buzi |
| **Data di avvio prevista** | 07/09/2026 |
| **Durata prevista** | Circa 5 mesi |
| **Versione del documento** | 1.0 |

---

## 2. Contesto

Chi organizza un'escursione ha spesso bisogno di raccogliere informazioni da fonti diverse: sito dell'ente parco, pagine turistiche, previsioni meteo, comunicazioni locali o segnalazioni informali di altri utenti. Il problema non è solo trovare le informazioni, ma capire se siano aggiornate e affidabili.

Nel caso dei sentieri, questo aspetto è particolarmente importante. Un percorso può essere temporaneamente chiuso, danneggiato, poco praticabile dopo il maltempo o interessato da ostacoli non ancora riportati nei canali ufficiali. Per un escursionista, non conoscere queste condizioni in anticipo può rendere più difficile pianificare l'uscita in modo consapevole.

TrailSafe nasce quindi come progetto per raccogliere in un unico punto le informazioni essenziali sui sentieri di un'area pilota. L'idea non è sostituire tutti gli strumenti già esistenti, ma offrire una piattaforma semplice, consultabile da browser, che aiuti sia gli utenti finali sia chi gestisce i percorsi.

---

## 3. Obiettivo del progetto

L'obiettivo del progetto è realizzare e validare una prima versione funzionante di TrailSafe, limitata inizialmente a un'area geografica pilota. La versione prevista è un MVP, quindi una piattaforma con le funzioni principali necessarie per dimostrare il valore del servizio senza estendere troppo l'ambito iniziale.

La piattaforma dovrà permettere agli escursionisti di consultare l'elenco dei sentieri, visualizzarli su mappa, leggere le informazioni principali del percorso e controllare eventuali avvisi o condizioni ambientali. Gli utenti registrati potranno anche salvare percorsi e inviare segnalazioni su ostacoli, problemi o situazioni di rischio.

Accanto alla parte pubblica sarà prevista un'area amministrativa, utile al personale incaricato per aggiornare i contenuti, gestire le segnalazioni ricevute e pubblicare avvisi o chiusure.

---

## 4. Motivazione del progetto

Il progetto risponde alla necessità di rendere più ordinata e accessibile la comunicazione sui sentieri. In uno scenario reale, un ente parco deve spesso gestire dati tecnici, aggiornamenti operativi e richieste degli utenti con strumenti non sempre integrati tra loro.

Una piattaforma come TrailSafe può portare benefici concreti: gli escursionisti avrebbero un punto di riferimento più chiaro prima di partire, mentre l'ente gestore potrebbe centralizzare aggiornamenti, segnalazioni e avvisi. Anche la collaborazione con associazioni o referenti locali diventerebbe più semplice, perché le informazioni potrebbero essere raccolte e verificate in modo più strutturato.

Dal punto di vista del progetto, la scelta di partire con un MVP consente di contenere tempi e costi e di verificare prima l'utilità della soluzione su un numero limitato di sentieri.

---

## 5. Obiettivi specifici

Gli obiettivi operativi della prima versione sono i seguenti:

1. realizzare una piattaforma web accessibile da browser desktop e mobile;
2. mostrare l'elenco dei sentieri disponibili nell'area pilota;
3. visualizzare i percorsi su una mappa interattiva;
4. fornire per ogni sentiero informazioni come difficoltà, lunghezza, durata stimata e stato del percorso;
5. integrare informazioni meteorologiche o ambientali utili alla pianificazione;
6. permettere agli utenti registrati di salvare i percorsi preferiti;
7. consentire l'invio di segnalazioni relative a ostacoli o situazioni di pericolo;
8. mettere a disposizione degli amministratori strumenti per gestire sentieri, segnalazioni, avvisi e chiusure;
9. consegnare una versione MVP entro i limiti di tempo e budget definiti.

---

## 6. Ambito del progetto

### 6.1 Attività comprese

Il progetto comprende tutte le attività necessarie per arrivare alla consegna della versione pilota: raccolta e analisi dei requisiti, progettazione dell'esperienza utente, realizzazione dell'interfaccia, sviluppo frontend e backend, integrazione con servizi esterni, test, rilascio e documentazione finale.

Rientrano inoltre nel progetto la formazione iniziale degli amministratori e la predisposizione di un manuale sintetico, in modo che l'ente committente possa utilizzare la piattaforma dopo la consegna.

In termini funzionali, l'MVP comprende la gestione utenti, la consultazione dei sentieri, la mappa, le schede dei percorsi, le informazioni meteo, il sistema di segnalazione e l'area amministrativa.

### 6.2 Attività escluse

Per mantenere il progetto realistico e compatibile con la durata prevista, alcune funzionalità restano fuori dall'MVP. Non sono quindi previste applicazioni mobili native, copertura nazionale, localizzazione continua degli utenti, gestione diretta delle emergenze o integrazione con centrali operative di soccorso.

Sono esclusi anche dispositivi fisici installati sui sentieri, servizi di pagamento, funzionalità commerciali e manutenzione pluriennale successiva alla chiusura del progetto. Questi aspetti potranno essere valutati in una fase successiva, ma non fanno parte dell'obiettivo iniziale.

---

## 7. Deliverable principali

Alla fine del progetto sono attesi i seguenti deliverable:

1. documento dei requisiti;
2. prototipo dell'interfaccia;
3. piattaforma web MVP;
4. modulo di gestione utenti;
5. mappa interattiva dei sentieri;
6. modulo meteo e stato dei percorsi;
7. sistema di segnalazione;
8. area amministrativa;
9. piano e risultati dei test;
10. manuale sintetico per gli amministratori;
11. documentazione finale di progetto;
12. report di chiusura.

---

## 8. Stakeholder principali

| Stakeholder | Interesse principale |
|---|---|
| Ente committente | Avere uno strumento più efficace per comunicare informazioni sui sentieri |
| Project Manager | Coordinare il progetto e mantenere sotto controllo tempi, costi, qualità e rischi |
| Team di sviluppo | Realizzare la soluzione tecnica prevista dall'MVP |
| Amministratori della piattaforma | Aggiornare contenuti, segnalazioni, avvisi e chiusure |
| Escursionisti | Consultare informazioni chiare, aggiornate e facili da raggiungere |
| Gestori dei sentieri | Comunicare variazioni, problemi o limitazioni sui percorsi |
| Servizi meteo e cartografici | Fornire dati esterni utilizzati dalla piattaforma |
| Associazioni escursionistiche | Supportare la raccolta e la verifica delle informazioni sul territorio |

---

## 9. Approccio di gestione

Per TrailSafe viene adottato un approccio ibrido. La parte iniziale del progetto richiede una pianificazione abbastanza chiara, perché devono essere definiti ambito, budget, responsabilità, milestone, rischi e criteri di accettazione. Questi elementi servono a mantenere il progetto controllabile e a evitare che l'MVP diventi troppo ampio.

La realizzazione delle funzionalità sarà invece organizzata in iterazioni. Questo permette di procedere per blocchi di lavoro, verificare periodicamente l'avanzamento e adattare alcune priorità in base ai riscontri del committente. L'approccio scelto cerca quindi di bilanciare controllo e flessibilità: il progetto mantiene una direzione precisa, ma lascia spazio a piccoli aggiustamenti durante l'esecuzione.

---

## 10. Milestone preliminari

| Milestone | Risultato atteso |
|---|---|
| Approvazione del progetto | Autorizzazione all'avvio |
| Approvazione dei requisiti | Requisiti condivisi con il committente |
| Approvazione del prototipo | Interfaccia validata |
| Prima versione interna | Funzionalità principali integrate |
| Fine dei test | Requisiti principali verificati |
| Rilascio pilota | MVP disponibile |
| Accettazione finale | Approvazione del committente |
| Chiusura | Consegna finale e raccolta delle lesson learned |

Le date di dettaglio sono riportate nella pianificazione temporale e nel diagramma di Gantt. In questo documento le milestone hanno lo scopo di indicare i principali passaggi decisionali del progetto.

---

## 11. Vincoli

Il progetto deve rimanere entro una durata indicativa di circa cinque mesi e un budget massimo di 75.000 euro. Questi due vincoli rendono necessario limitare l'ambito alla sola versione MVP e rimandare eventuali evoluzioni a una fase successiva.

Un altro vincolo importante riguarda la disponibilità dei dati sui sentieri. La qualità della piattaforma dipende anche dalla completezza e dall'aggiornamento delle informazioni fornite dal committente o dai referenti territoriali.

Il progetto dipende inoltre da servizi esterni per mappe e meteo. Eventuali problemi tecnici o limitazioni di questi servizi dovranno essere gestiti durante lo sviluppo. Resta infine necessario rispettare la normativa sulla protezione dei dati, soprattutto per quanto riguarda utenti registrati e segnalazioni.

---

## 12. Assunzioni

La pianificazione si basa su alcune assunzioni iniziali. Si considera che il committente possa fornire un primo insieme di dati sui sentieri e che sia disponibile almeno un referente per chiarire dubbi, validare requisiti e verificare i contenuti.

Si assume inoltre che esistano servizi utilizzabili per mappe e informazioni meteorologiche, e che il team disponga delle competenze tecniche necessarie per integrarli nella piattaforma. La fase pilota viene considerata limitata a circa 20-30 sentieri, così da mantenere gestibile sia il caricamento iniziale dei dati sia la validazione finale.

Infine, si dà per scontato che gli utenti utilizzino TrailSafe tramite connessione Internet e browser, senza richiedere per questa prima versione funzionalità offline o applicazioni native.

---

## 13. Rischi iniziali

| Rischio | Possibile effetto |
|---|---|
| Dati sui sentieri incompleti o non aggiornati | Informazioni poco affidabili per gli utenti |
| Problemi con servizi meteo o cartografici | Ritardi o malfunzionamenti di alcune funzionalità |
| Aumento non controllato dei requisiti | Allungamento dei tempi e incremento dei costi |
| Bassa partecipazione degli stakeholder | Requisiti meno precisi o validazioni più lente |
| Segnalazioni degli utenti non attendibili | Pubblicazione di informazioni errate se non verificate |
| Problemi di privacy o sicurezza | Rischi legali e reputazionali |
| Sottostima delle attività tecniche | Ritardo nel rilascio dell'MVP |

Questi rischi saranno ripresi e approfonditi nel registro dei rischi, dove verranno indicati priorità, responsabilità e azioni di mitigazione.

---

## 14. Criteri di successo

Il progetto potrà essere considerato concluso positivamente se, al termine delle attività, la versione MVP sarà disponibile e utilizzabile nell'area pilota. In particolare, gli utenti dovranno riuscire a consultare i sentieri, visualizzare le informazioni principali, accedere alla mappa e inviare segnalazioni.

Dal lato amministrativo, la piattaforma dovrà consentire la gestione dei sentieri, degli avvisi e delle segnalazioni ricevute. I requisiti ad alta priorità dovranno essere completati e i test principali dovranno avere esito positivo.

Saranno considerati elementi di successo anche il rispetto del budget massimo, il mantenimento della durata prevista e l'approvazione finale da parte del committente. La documentazione di progetto dovrà essere completata e archiviata insieme al report di chiusura.

---

## 15. Autorità del Project Manager

Il Project Manager ha il compito di coordinare le attività, aggiornare la pianificazione, assegnare il lavoro al team e monitorare l'andamento complessivo del progetto. Rientrano nelle sue responsabilità anche la gestione delle riunioni, la comunicazione con il committente, il controllo di tempi, costi, qualità e rischi, e la predisposizione della documentazione di chiusura.

Il Project Manager può proporre azioni correttive e valutare le richieste di modifica. Le modifiche minori potranno essere gestite operativamente, mentre quelle che incidono in modo significativo su budget, durata o ambito dovranno essere approvate dal committente o dallo sponsor.

---

## 16. Approvazione

L'approvazione del presente Project Charter autorizza l'avvio formale del progetto TrailSafe e il passaggio alla pianificazione dettagliata. Con questa approvazione vengono confermati l'obiettivo generale, il perimetro iniziale dell'MVP, i principali vincoli e il ruolo del Project Manager.

| Ruolo | Nome | Firma | Data |
|---|---|---|---|
| Sponsor | Dott.ssa Laura Monti | Laura Monti | 07/09/2026 |
| Committente | Ing. Marco Rinaldi | Marco Rinaldi | 07/09/2026 |
| Project Manager | Sajmir Buzi | Sajmir Buzi | 07/09/2026 |

---

<nav class="next-page">
  <a href="02_Business_Case_TrailSafe.html">Pagina successiva: Business Case &rarr;</a>
</nav>

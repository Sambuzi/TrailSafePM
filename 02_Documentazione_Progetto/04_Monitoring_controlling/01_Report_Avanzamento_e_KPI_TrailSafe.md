# Report di avanzamento e KPI - TrailSafe

## 1. Informazioni generali

Questo report fotografa lo stato del progetto TrailSafe alla data del 20/11/2026. Il periodo considerato va dal kick-off fino alla riunione di avanzamento di novembre.

Il documento serve a verificare se il progetto sta procedendo secondo il piano, quali scostamenti sono emersi e quali azioni devono essere seguite prima del prossimo controllo. I KPI non vengono letti solo come numeri, ma come segnali utili per capire dove intervenire.

| Voce | Valore |
|---|---|
| Progetto | TrailSafe |
| Data del report | 20/11/2026 |
| Periodo considerato | 07/09/2026 - 20/11/2026 |
| Responsabile | Project Manager |
| Stato generale | In linea, con lieve ritardo tecnico |

---

## 2. Sintesi dello stato attuale

Nel complesso il progetto sta procedendo in modo regolare. Le attività di avvio, analisi e progettazione sono state completate, mentre lo sviluppo delle funzionalità principali è in corso.

Il punto da monitorare con più attenzione riguarda l'integrazione del servizio meteo, che ha richiesto più tempo del previsto a causa di alcune difficoltà con l'API esterna. Il ritardo è ancora contenuto e, al momento, non modifica la data finale prevista per il rilascio pilota.

Lo scope dell'MVP rimane invariato. Alcune funzionalità a priorità media potranno però essere rinviate se il ritardo tecnico dovesse aumentare.

---

## 3. Stato delle attività

| Area | Stato | Nota |
|---|---|---|
| Avvio del progetto | Completato | Kick-off svolto e modalità di lavoro confermate |
| Raccolta requisiti | Completata | Requisiti principali approvati dal committente |
| Progettazione UX/UI | Completata | Prototipo validato prima dello sviluppo completo |
| Progettazione tecnica | Completata | Struttura applicativa e integrazioni principali definite |
| Area utenti | Quasi completata | Restano correzioni minori su profilo e accesso |
| Mappa e sentieri | In corso | Avanzamento regolare, con alcuni dati ancora da verificare |
| Integrazione meteo | In ritardo | Problemi tecnici con API esterna e gestione errori |
| Segnalazioni | In corso | Sviluppo avviato, test previsti dopo integrazione dei moduli |
| Area amministrativa | Da avviare | Prevista nella fase successiva del piano iterativo |
| Test | Da avviare | Test completi previsti dopo l'integrazione delle funzioni principali |

---

## 4. KPI principali

I KPI mostrano uno stato complessivamente controllato. Lo scostamento più evidente riguarda l'avanzamento delle attività e il numero di problemi aperti, entrambi collegati soprattutto all'integrazione meteo.

| Indicatore | Valore previsto | Valore attuale | Stato |
|---|---:|---:|---|
| Attività completate | 45% | 42% | Leggermente sotto |
| Ritardo complessivo | 0 giorni | 4 giorni | Da monitorare |
| Budget utilizzato | 50% | 48% | In linea |
| Requisiti ad alta priorità completati | 40% | 38% | In linea |
| Rischi aperti | 5 | 5 | In linea |
| Problemi aperti | 2 | 3 | Sopra la previsione |

Il budget risulta leggermente inferiore al previsto, ma questo dato non va interpretato come margine disponibile automatico. Prima di usare eventuali risorse residue sarà necessario verificare l'impatto su tempi, qualità e priorità dell'MVP.

---

## 5. Scostamenti rilevati

Il principale scostamento riguarda l'integrazione del servizio meteo. Il ritardo stimato è di circa 4 giorni ed è dovuto a difficoltà tecniche nell'uso dell'API scelta, in particolare nella gestione delle risposte lente o non disponibili.

Al momento il ritardo non compromette la data finale del progetto, ma richiede un controllo ravvicinato nella prossima riunione di avanzamento. Se il problema dovesse proseguire, sarà necessario valutare un servizio alternativo o ridurre temporaneamente alcune funzioni a priorità media.

Un secondo punto riguarda la qualità dei dati dei sentieri. Alcune informazioni risultano incomplete e dovranno essere confermate dal referente del committente prima dei test di integrazione.

I costi sono sotto controllo e non emergono, alla data del report, superamenti del budget pianificato.

---

## 6. Problemi aperti

| ID | Problema | Impatto | Responsabile | Stato |
|---|---|---|---|---|
| P01 | Risposta lenta o non stabile del servizio meteo | Medio | Backend Developer | In lavorazione |
| P02 | Alcuni dati dei sentieri sono incompleti | Medio | Referente committente | In lavorazione |
| P03 | Visualizzazione della mappa non ottimale su mobile | Basso | Frontend Developer | Aperto |

I problemi P01 e P02 hanno priorità maggiore perché possono incidere sui test di integrazione e sulla qualità della versione pilota. Il problema P03 è da correggere, ma al momento non blocca l'avanzamento delle attività principali.

---

## 7. Azioni correttive

Sono state definite le seguenti azioni correttive:

- dare priorità al completamento dell'integrazione meteo;
- verificare la possibilità di usare un servizio alternativo se l'API attuale continua a creare problemi;
- completare la verifica dei dati dei sentieri con il referente del committente;
- rimandare alcune funzionalità a priorità media se necessario;
- aggiornare il Gantt con il ritardo tecnico rilevato;
- preparare i test di integrazione sulle parti già stabili;
- ricontrollare KPI, rischi e problemi aperti nella prossima riunione di avanzamento.

Le azioni saranno seguite dal Project Manager e aggiornate nel registro decisioni e attività, quando producono nuove assegnazioni o modifiche al piano.

---

## 8. Valutazione generale

Il progetto rimane sotto controllo. Il ritardo tecnico è contenuto e può essere recuperato senza modificare la data finale, a condizione che l'integrazione meteo venga stabilizzata entro la prossima finestra di lavoro.

La priorità per le prossime settimane sarà completare le funzionalità essenziali dell'MVP, evitare l'espansione dello scope e preparare i test di integrazione. Budget e requisiti ad alta priorità risultano ancora in linea con il piano.

La valutazione complessiva è quindi positiva, con una raccomandazione: monitorare da vicino i servizi esterni e la qualità dei dati dei sentieri, perché sono i due elementi che potrebbero avere l'impatto maggiore sul rilascio pilota.

---

<nav class="next-page">
  <a class="previous-page" href="../03_Execution/03_Registro_Decisioni_e_Attivita_TrailSafe.html">&larr; Pagina precedente: Registro decisioni e attivita</a>
  <a href="02_Registro_Problemi_Modifiche_e_Rischi_TrailSafe.html">Pagina successiva: Registro problemi, modifiche e rischi &rarr;</a>
</nav>

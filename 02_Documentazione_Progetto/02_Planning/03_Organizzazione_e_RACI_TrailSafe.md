# Organizzazione e matrice RACI - TrailSafe

## 1. Obiettivo del documento

Questo documento descrive come viene organizzato il team di progetto TrailSafe e chiarisce chi partecipa alle principali decisioni operative.

La matrice RACI serve a evitare sovrapposizioni o responsabilità poco chiare: per ogni attività viene indicato chi esegue il lavoro, chi approva il risultato, chi deve essere consultato e chi deve solo essere tenuto informato.

---

## 2. Struttura del team

TrailSafe sarà gestito da un team contenuto, adatto alla dimensione dell'MVP. Alcuni ruoli potranno essere coperti dalla stessa persona, soprattutto nelle fasi meno cariche o per attività molto vicine tra loro.

| Ruolo | Responsabilità principali |
|---|---|
| Sponsor / Committente | Approva obiettivi, budget, requisiti principali e modifiche rilevanti |
| Project Manager | Coordina il progetto, segue tempi, costi, rischi e comunicazione con il committente |
| Business Analyst | Raccoglie i requisiti, li organizza e supporta la validazione con gli stakeholder |
| UX/UI Designer | Progetta interfaccia, flussi utente e usabilità della piattaforma |
| Sviluppatore Frontend | Realizza le schermate e le interazioni visibili agli utenti |
| Sviluppatore Backend | Realizza API, database, logica applicativa e integrazioni esterne |
| Tester | Verifica che le funzionalità rispettino i requisiti e segnala eventuali problemi |
| Referente amministratori | Porta il punto di vista di chi userà l'area amministrativa e gestirà i contenuti |

---

## 3. Organizzazione del progetto

Lo Sponsor interviene sulle decisioni principali, in particolare quando una scelta incide su budget, tempi, priorità o perimetro del progetto.

Il Project Manager mantiene il coordinamento quotidiano: organizza le attività, monitora l'avanzamento e fa da collegamento tra team tecnico e committente.

Il Business Analyst lavora soprattutto nelle fasi di raccolta e verifica dei requisiti, ma rimane coinvolto anche durante progettazione e test per controllare che le funzionalità sviluppate siano coerenti con quanto concordato.

Il team tecnico si occupa della progettazione tecnica e dello sviluppo della piattaforma. Il referente degli amministratori supporta la definizione dei flussi di gestione, soprattutto per sentieri, avvisi e segnalazioni.

Il Tester entra nella verifica delle funzionalità e nella validazione della versione pilota, con attenzione particolare ai requisiti ad alta priorità.

---

## 4. Matrice RACI

Legenda:

- **R** - Responsible: svolge direttamente l'attività;
- **A** - Accountable: approva il risultato ed è responsabile finale dell'attività;
- **C** - Consulted: viene consultato prima o durante l'attività;
- **I** - Informed: viene informato sull'avanzamento o sull'esito.

| Attività | Sponsor | PM | Analyst | UX/UI | Frontend | Backend | Tester | Referente admin |
|---|---|---|---|---|---|---|---|---|
| Approvazione del progetto | A | R | I | I | I | I | I | I |
| Raccolta dei requisiti | C | A | R | C | I | I | I | C |
| Approvazione dei requisiti | A | R | C | I | I | I | I | C |
| Progettazione dell'interfaccia | I | A | C | R | C | I | I | C |
| Progettazione tecnica | I | A | C | C | R | R | C | I |
| Sviluppo frontend | I | A | I | C | R | C | C | I |
| Sviluppo backend | I | A | I | I | C | R | C | I |
| Integrazione mappe e meteo | I | A | I | I | C | R | C | I |
| Test della piattaforma | I | A | C | I | C | C | R | C |
| Validazione con gli utenti | I | A | C | C | I | I | R | C |
| Rilascio della versione pilota | A | R | I | I | C | C | C | I |
| Chiusura del progetto | A | R | I | I | I | I | C | I |

---

## 5. Regole decisionali

Le decisioni operative vengono gestite dal Project Manager insieme al team coinvolto. Per scelte tecniche ordinarie è sufficiente il confronto tra Project Manager e sviluppatori, con il coinvolgimento del Tester quando la decisione ha impatto sulla verifica.

Le modifiche che incidono su tempi, costi, requisiti ad alta priorità o scope dell'MVP devono essere portate allo Sponsor / Committente prima di essere inserite nel piano di lavoro.

I requisiti e i flussi dell'area amministrativa devono essere verificati con il referente del committente, così da evitare differenze tra quanto progettato e il modo in cui la piattaforma verrà usata dopo il rilascio.

Il rilascio della versione pilota richiede una verifica interna del team e l'approvazione finale del committente.

---

## 6. Comunicazione interna

Per mantenere il progetto sotto controllo senza appesantire troppo il lavoro, sono previste poche occasioni di confronto ma regolari.

- breve riunione operativa del team ogni settimana;
- riunione di avanzamento con il committente ogni due settimane;
- aggiornamento del Project Manager in caso di rischi, ritardi o decisioni bloccanti;
- riunioni aggiuntive solo quando emergono problemi, modifiche allo scope o dubbi sui requisiti.

Le decisioni rilevanti e le modifiche approvate dovranno essere riportate nei documenti di progetto o nei verbali di avanzamento, in modo da mantenere una traccia condivisa.

---

<nav class="next-page">
  <a class="previous-page" href="02_PBS_e_WBS_TrailSafe.html">&larr; Pagina precedente: PBS e WBS</a>
  <a href="04_Tempi_Costi_e_Gantt_TrailSafe.html">Pagina successiva: Tempi, costi e Gantt &rarr;</a>
</nav>

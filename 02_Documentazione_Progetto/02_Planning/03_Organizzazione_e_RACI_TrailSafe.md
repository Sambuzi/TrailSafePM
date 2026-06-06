# Organizzazione e Matrice RACI – TrailSafe

## 1. Struttura del team

Il progetto TrailSafe sarà gestito da un piccolo team.

| Ruolo | Responsabilità principali |
|---|---|
| Sponsor / Committente | Approva obiettivi, budget e modifiche importanti |
| Project Manager | Coordina il progetto e controlla tempi, costi e rischi |
| Business Analyst | Raccoglie e organizza i requisiti |
| UX/UI Designer | Progetta l’interfaccia e l’esperienza utente |
| Sviluppatore Frontend | Realizza la parte visibile della piattaforma |
| Sviluppatore Backend | Realizza API, database e logica applicativa |
| Tester | Verifica il funzionamento della piattaforma |
| Referente amministratori | Porta le esigenze di chi gestirà i contenuti |

In un team ridotto, alcuni ruoli potranno essere svolti dalla stessa persona.

---

## 2. Organizzazione del progetto

Lo Sponsor approva le decisioni principali.

Il Project Manager coordina il lavoro e mantiene i contatti con il committente.

Il team tecnico realizza le funzionalità previste, mentre il Business Analyst e il referente degli amministratori supportano la definizione e la verifica dei requisiti.

Il Tester controlla che le funzionalità rispettino quanto concordato.

---

## 3. Matrice RACI

Legenda:

- **R** – Responsible: svolge l’attività;
- **A** – Accountable: approva ed è responsabile del risultato;
- **C** – Consulted: viene consultato;
- **I** – Informed: viene informato.

| Attività | Sponsor | PM | Analyst | UX/UI | Frontend | Backend | Tester | Referente admin |
|---|---|---|---|---|---|---|---|---|
| Approvazione del progetto | A | R | I | I | I | I | I | I |
| Raccolta dei requisiti | C | A | R | C | I | I | I | C |
| Approvazione dei requisiti | A | R | C | I | I | I | I | C |
| Progettazione dell’interfaccia | I | A | C | R | C | I | I | C |
| Progettazione tecnica | I | A | C | C | R | R | C | I |
| Sviluppo frontend | I | A | I | C | R | C | C | I |
| Sviluppo backend | I | A | I | I | C | R | C | I |
| Integrazione mappe e meteo | I | A | I | I | C | R | C | I |
| Test della piattaforma | I | A | C | I | C | C | R | C |
| Validazione con gli utenti | I | A | C | C | I | I | R | C |
| Rilascio della versione pilota | A | R | I | I | C | C | C | I |
| Chiusura del progetto | A | R | I | I | I | I | C | I |

---

## 4. Regole decisionali

- Le decisioni operative vengono prese dal Project Manager insieme al team.
- Le modifiche che incidono su tempi, costi o scope devono essere approvate dallo Sponsor.
- I requisiti devono essere verificati con il referente del committente.
- I problemi tecnici vengono discussi tra Project Manager e sviluppatori.
- Il rilascio finale richiede l’approvazione del committente.

---

## 5. Comunicazione interna

Il team svolgerà:

- una breve riunione operativa ogni settimana;
- una riunione di avanzamento con il committente ogni due settimane;
- riunioni aggiuntive in caso di problemi o richieste di modifica.

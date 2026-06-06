# Project Charter

## Informazioni generali

| Campo | Dettaglio |
| - | - |
| Titolo del progetto | TrailSafe - Piattaforma web per la sicurezza sui sentieri escursionistici |
| Committente | Ente Parco Regionale, scenario simulato |
| Project Manager | Da assegnare |
| Sponsor di progetto | Direzione dell'Ente Parco |
| Tipologia di progetto | Sviluppo MVP di piattaforma web |
| Area pilota | Area escursionistica regionale con rete di sentieri gestiti dall'ente |
| Data di avvio prevista | 01/03/2026 |
| Data di chiusura prevista | 31/08/2026 |
| Durata stimata | 6 mesi |
| Versione documento | 1.0 |

## Scopo del documento

Il Project Charter autorizza formalmente l'avvio del progetto TrailSafe e definisce le informazioni essenziali necessarie per procedere con la pianificazione. Il documento descrive obiettivi, motivazioni, ambito preliminare, stakeholder principali, vincoli, assunzioni, rischi iniziali e criteri di successo.

## Contesto

L'Ente Parco Regionale gestisce un'area con diversi sentieri escursionistici frequentati da turisti, residenti e gruppi organizzati. La comunicazione sullo stato dei percorsi, sugli avvisi e sulle situazioni di pericolo avviene attualmente tramite canali non sempre aggiornati o centralizzati, come sito istituzionale, cartelli fisici, comunicazioni telefoniche e social media.

Questa frammentazione rende difficile per gli escursionisti ottenere informazioni affidabili prima e durante l'escursione. Inoltre, le segnalazioni da parte degli utenti non seguono un processo strutturato, rallentando la presa in carico da parte degli amministratori dell'ente.

TrailSafe nasce come MVP per centralizzare le informazioni essenziali sui sentieri e migliorare la gestione delle segnalazioni in un'area pilota.

## Business need

Il progetto risponde alla necessita di:

- aumentare la sicurezza degli escursionisti;
- rendere piu accessibili le informazioni sui sentieri;
- ridurre la dispersione delle comunicazioni operative;
- migliorare la raccolta e la moderazione delle segnalazioni;
- fornire all'ente uno strumento amministrativo semplice per aggiornare dati, avvisi e stato dei percorsi.

## Obiettivi del progetto

| ID | Obiettivo | Indicatore di successo |
| - | - | - |
| O1 | Realizzare un MVP web consultabile da utenti escursionisti | MVP rilasciato e accessibile online entro la data prevista |
| O2 | Rendere disponibili informazioni base sui sentieri dell'area pilota | Almeno 20 sentieri caricati con difficolta, durata, lunghezza e stato |
| O3 | Consentire l'invio di segnalazioni da parte degli utenti | Funzione di segnalazione attiva e collegata all'area amministrativa |
| O4 | Fornire agli amministratori strumenti per gestire sentieri, stati e avvisi | Area amministrativa funzionante con accesso riservato |
| O5 | Integrare informazioni meteorologiche o avvisi rilevanti | Visualizzazione di dati meteo o messaggi di allerta nella scheda sentiero |

## Ambito preliminare

### Incluso nel progetto

- mappa interattiva dei sentieri dell'area pilota;
- schede informative dei sentieri;
- stato dei percorsi, come aperto, chiuso, attenzione o manutenzione;
- visualizzazione di avvisi e informazioni meteo;
- invio di segnalazioni da parte degli escursionisti;
- gestione e moderazione delle segnalazioni da parte degli amministratori;
- area amministrativa per aggiornare sentieri, stati e avvisi;
- definizione del Product Backlog e pianificazione incrementale dell'MVP;
- test funzionali e accettazione finale con il committente simulato.

### Escluso dal progetto

- sviluppo di app mobile native per iOS e Android;
- tracciamento GPS in tempo reale degli utenti;
- chiamata automatica ai servizi di emergenza;
- gestione dei pagamenti o prenotazioni;
- copertura di tutte le aree escursionistiche regionali;
- integrazione avanzata con sistemi GIS proprietari;
- manutenzione evolutiva successiva al rilascio dell'MVP.

## Deliverable principali

| Deliverable | Descrizione |
| - | - |
| Analisi iniziale | Scenario, stakeholder, obiettivi, vincoli e criteri di successo |
| Documentazione di pianificazione | Scope, requisiti, PBS/PDS, WBS, RACI, Gantt, costi, rischi, comunicazione e qualita |
| MVP TrailSafe | Prima versione web funzionante della piattaforma |
| Area amministrativa | Funzioni riservate per gestione sentieri, avvisi e segnalazioni |
| Documentazione di execution e controllo | Roadmap, backlog, verbali, report, issue log, change log e KPI |
| Documentazione di chiusura | Accettazione, closure report e lessons learned |

## Milestone preliminari

| Milestone | Data stimata |
| - | - |
| Approvazione Project Charter | 07/03/2026 |
| Completamento analisi stakeholder e requisiti | 21/03/2026 |
| Approvazione scope e piano di progetto | 05/04/2026 |
| Completamento prototipo funzionale | 15/05/2026 |
| Completamento MVP | 20/07/2026 |
| Test e validazione con committente | 10/08/2026 |
| Chiusura progetto | 31/08/2026 |

## Budget preliminare

Il budget simulato per la realizzazione dell'MVP e pari a 75.000 euro.

| Voce | Stima |
| - | -: |
| Analisi e project management | 12.000 euro |
| UX/UI design | 8.000 euro |
| Sviluppo frontend | 16.000 euro |
| Sviluppo backend e database | 18.000 euro |
| Integrazioni mappa/meteo | 7.000 euro |
| Test e qualita | 6.000 euro |
| Formazione e rilascio | 3.000 euro |
| Riserva rischi | 5.000 euro |
| Totale | 75.000 euro |

## Stakeholder principali

| Stakeholder | Ruolo/interesse |
| - | - |
| Ente Parco Regionale | Committente e proprietario del servizio |
| Direzione Ente Parco | Sponsor e decisore principale |
| Ufficio tecnico/manutenzione sentieri | Fornisce dati e aggiorna lo stato operativo dei percorsi |
| Escursionisti | Utenti finali della piattaforma |
| Amministratori TrailSafe | Gestiscono contenuti, avvisi e segnalazioni |
| Team di progetto | Analisi, progettazione, sviluppo, test e gestione |
| Servizi di emergenza locali | Stakeholder informativi per scenari di sicurezza |
| Docente/valutatore | Valuta la completezza dell'elaborato |

## Assunzioni

- L'ente fornisce dati iniziali sui sentieri dell'area pilota.
- Il numero di sentieri gestiti nell'MVP resta limitato e coerente con il budget.
- Gli utenti dispongono di connessione internet sufficiente per consultare la piattaforma.
- Le integrazioni con mappe e meteo sono realizzate tramite servizi esterni disponibili.
- Il progetto ha finalita didattica e i dati economici, temporali e organizzativi sono simulati.

## Vincoli

- Il progetto deve essere completato entro 6 mesi.
- Il budget massimo simulato e pari a 75.000 euro.
- Il prodotto rilasciato deve essere un MVP, non una piattaforma completa definitiva.
- La soluzione deve essere utilizzabile da browser web.
- La documentazione deve coprire le principali fasi di Project Management richieste dall'elaborato.

## Rischi iniziali

| Rischio | Impatto | Probabilita | Risposta preliminare |
| - | - | - | - |
| Dati sui sentieri incompleti o non aggiornati | Alto | Media | Prevedere validazione iniziale con l'ente |
| Requisiti troppo ampi per un MVP | Alto | Media | Definire chiaramente ambito incluso ed escluso |
| Dipendenza da servizi esterni per mappe/meteo | Medio | Media | Valutare alternative e limiti dei servizi scelti |
| Bassa adozione da parte degli utenti | Medio | Bassa | Curare usabilita e comunicazione del servizio |
| Ritardi nello sviluppo | Alto | Media | Usare milestone intermedie e backlog prioritizzato |

## Criteri di successo

Il progetto sara considerato concluso con successo se:

- l'MVP viene rilasciato entro il 31/08/2026;
- il costo complessivo resta entro il budget simulato di 75.000 euro;
- almeno 20 sentieri dell'area pilota sono consultabili nella piattaforma;
- gli utenti possono consultare mappa, dettagli sentiero, stato percorso e avvisi;
- gli utenti possono inviare segnalazioni;
- gli amministratori possono gestire sentieri, stati, avvisi e segnalazioni;
- il committente simulato approva il rilascio finale;
- la documentazione di progetto risulta completa rispetto alle fasi richieste.

## Approccio di gestione

Il progetto adotta un approccio ibrido:

- impostazione tradizionale per definire scope, tempi, costi, responsabilita, rischi e milestone;
- gestione Agile delle funzionalita tramite backlog, priorita e iterazioni incrementali;
- monitoraggio periodico tramite report di avanzamento, KPI, issue log e change log.

Questa scelta consente di mantenere controllo sulla pianificazione generale e, allo stesso tempo, flessibilita nella realizzazione progressiva dell'MVP.

## Autorizzazione

Con l'approvazione del presente Project Charter, lo sponsor autorizza l'avvio della fase di pianificazione del progetto TrailSafe.

| Ruolo | Nome | Firma | Data |
| - | - | - | - |
| Sponsor di progetto | Da definire |  |  |
| Project Manager | Da definire |  |  |

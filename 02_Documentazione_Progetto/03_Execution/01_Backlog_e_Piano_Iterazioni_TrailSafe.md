# Backlog e piano delle iterazioni - TrailSafe

## 1. Obiettivo del documento

Questo documento raccoglie le funzionalità principali previste per TrailSafe e le organizza in un piano di lavoro a iterazioni.

Il backlog parte dai requisiti dell'MVP e li traduce in elementi più operativi, utili per pianificare sviluppo, test e rilascio. Le priorità sono state assegnate considerando ciò che serve per avere una prima versione realmente utilizzabile: consultazione dei sentieri, mappa, informazioni essenziali, segnalazioni e gestione amministrativa.

Le funzionalità a priorità media restano importanti, ma potranno essere ridotte o rinviate se dovessero mettere a rischio tempi, budget o rilascio della versione pilota.

---

## 2. Product backlog

Il backlog è espresso in forma di user story sintetiche. Ogni voce rappresenta una funzionalità che dovrà essere analizzata, sviluppata e verificata prima di essere considerata completata.

| ID | Funzionalità | Priorità |
|---|---|---|
| US01 | Come utente voglio registrarmi e accedere alla piattaforma | Alta |
| US02 | Come utente voglio consultare l'elenco dei sentieri disponibili | Alta |
| US03 | Come utente voglio visualizzare i sentieri su una mappa interattiva | Alta |
| US04 | Come utente voglio aprire la scheda di un sentiero e leggerne i dettagli | Alta |
| US05 | Come utente voglio vedere meteo e condizioni del percorso | Alta |
| US06 | Come utente registrato voglio salvare i sentieri preferiti | Media |
| US07 | Come utente voglio inviare una segnalazione su un sentiero | Alta |
| US08 | Come amministratore voglio creare, modificare e rimuovere sentieri | Alta |
| US09 | Come amministratore voglio controllare e gestire le segnalazioni ricevute | Alta |
| US10 | Come amministratore voglio pubblicare avvisi, chiusure o aggiornamenti | Alta |
| US11 | Come utente voglio vedere punti di interesse collegati ai sentieri | Media |
| US12 | Come utente voglio ricevere aggiornamenti importanti sui sentieri salvati | Media |

---

## 3. Piano delle iterazioni

Le iterazioni sono ordinate in modo da costruire prima le basi della piattaforma e poi aggiungere progressivamente le funzioni più specifiche. Ogni iterazione dovrà produrre un risultato verificabile, anche se non ancora completo dal punto di vista del prodotto finale.

### Iterazione 1 - Utenti e accesso

**Obiettivo:** predisporre la base applicativa e permettere agli utenti di accedere alla piattaforma.

Attività principali:

- registrazione degli utenti;
- accesso alla piattaforma;
- gestione base del profilo;
- impostazione iniziale del database;
- prime regole di autorizzazione.

**Risultato atteso:** gli utenti possono creare un account, accedere e usare una struttura applicativa pronta per le iterazioni successive.

---

### Iterazione 2 - Mappa e sentieri

**Obiettivo:** rendere consultabili i percorsi dell'area pilota.

Attività principali:

- elenco dei sentieri;
- visualizzazione dei percorsi su mappa;
- scheda informativa del sentiero;
- inserimento dei dati iniziali dei percorsi;
- visualizzazione dei punti di interesse, se disponibili.

**Risultato atteso:** gli utenti possono cercare i sentieri, aprire le schede di dettaglio e visualizzare i percorsi sulla mappa.

---

### Iterazione 3 - Meteo, stato percorsi e segnalazioni

**Obiettivo:** aggiungere le informazioni utili alla valutazione del percorso prima dell'escursione.

Attività principali:

- integrazione del servizio meteo;
- visualizzazione dello stato dei percorsi;
- invio delle segnalazioni da parte degli utenti;
- salvataggio dei sentieri preferiti;
- gestione degli errori dei servizi esterni.

**Risultato atteso:** gli utenti possono consultare condizioni ambientali, salvare percorsi e comunicare eventuali problemi riscontrati sui sentieri.

---

### Iterazione 4 - Area amministrativa

**Obiettivo:** permettere agli amministratori di mantenere aggiornati contenuti e informazioni operative.

Attività principali:

- gestione dei sentieri;
- verifica e lavorazione delle segnalazioni;
- pubblicazione di avvisi;
- gestione di chiusure o aggiornamenti sullo stato dei percorsi;
- controllo degli accessi all'area amministrativa.

**Risultato atteso:** gli amministratori possono aggiornare le informazioni presenti nella piattaforma e gestire le segnalazioni prima che diventino comunicazioni ufficiali.

---

### Iterazione 5 - Test, dati pilota e rilascio

**Obiettivo:** stabilizzare l'MVP e prepararlo alla consegna al committente.

Attività principali:

- test funzionali delle aree principali;
- test di integrazione tra mappa, sentieri, meteo e segnalazioni;
- test con utenti pilota e amministratori;
- correzione dei problemi rilevati;
- caricamento e verifica dei dati iniziali;
- breve formazione degli amministratori;
- rilascio della versione pilota.

**Risultato atteso:** l'MVP è pronto per la verifica finale e per la consegna al committente.

---

## 4. Regole di gestione del backlog

Il backlog sarà aggiornato durante il progetto, ma le modifiche dovranno essere valutate con attenzione. TrailSafe è una versione MVP: questo significa che il piano deve proteggere prima di tutto le funzionalità essenziali per la consultazione dei sentieri e la gestione amministrativa.

Ogni nuova richiesta o modifica sarà valutata in base a:

- utilità per l'MVP;
- coerenza con lo scope approvato;
- tempo necessario per realizzarla;
- costo stimato;
- rischio tecnico o operativo;
- impatto sulle altre attività già pianificate.

Le funzioni ad alta priorità dovranno essere completate prima del rilascio della versione pilota, salvo approvazione esplicita del committente.

Le funzioni a priorità media potranno essere rinviate se causano ritardi, aumentano il budget o riducono la qualità delle funzioni principali.

---

## 5. Criteri di completamento

Una funzionalità del backlog sarà considerata completata quando:

- è stata sviluppata secondo il requisito approvato;
- è stata verificata dal team;
- non presenta problemi bloccanti noti;
- è coerente con l'interfaccia e i flussi previsti;
- se riguarda l'area amministrativa, è stata controllata anche con il referente degli amministratori.

Il completamento delle singole funzionalità sarà monitorato dal Project Manager durante le riunioni operative e usato per aggiornare l'avanzamento complessivo del progetto.
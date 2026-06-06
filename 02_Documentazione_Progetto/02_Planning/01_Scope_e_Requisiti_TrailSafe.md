# Scope e Requisiti – TrailSafe

## 1. Scopo del documento

Questo documento definisce l’ambito del progetto TrailSafe e raccoglie i requisiti principali della versione MVP.

L’obiettivo è chiarire cosa deve essere realizzato, cosa resta escluso e quali condizioni dovranno essere rispettate per considerare il progetto completato.

---

## 2. Obiettivo del progetto

Realizzare una piattaforma web per la consultazione dei sentieri escursionistici, inizialmente limitata a un’area geografica pilota.

La piattaforma dovrà permettere agli utenti di consultare i percorsi, visualizzare informazioni ambientali, ricevere avvisi e inviare segnalazioni. Gli amministratori dovranno poter gestire sentieri, avvisi e segnalazioni.

---

## 3. Ambito incluso

Il progetto comprende:

- raccolta e definizione dei requisiti;
- progettazione dell’interfaccia;
- sviluppo della piattaforma web;
- registrazione e accesso degli utenti;
- mappa interattiva dei sentieri;
- schede informative dei percorsi;
- visualizzazione di meteo e condizioni del sentiero;
- salvataggio dei percorsi preferiti;
- invio di segnalazioni;
- area amministrativa;
- gestione di sentieri, segnalazioni e avvisi;
- test e rilascio della versione pilota;
- documentazione e breve formazione per gli amministratori.

---

## 4. Ambito escluso

Non fanno parte dell’MVP:

- applicazioni mobili native;
- localizzazione continua degli utenti;
- gestione diretta delle emergenze;
- collegamento con centrali di soccorso;
- copertura dell’intero territorio nazionale;
- funzioni di pagamento;
- dispositivi fisici installati sui sentieri;
- manutenzione pluriennale successiva al progetto.

---

## 5. Deliverable principali

1. Documento dei requisiti.
2. Prototipo dell’interfaccia.
3. Piattaforma web MVP.
4. Mappa interattiva.
5. Modulo di gestione utenti.
6. Modulo di gestione sentieri.
7. Modulo meteo e stato dei percorsi.
8. Sistema di segnalazione.
9. Area amministrativa.
10. Piano e risultati dei test.
11. Manuale sintetico per gli amministratori.
12. Documentazione finale di progetto.

---

## 6. Requisiti funzionali

| ID | Requisito | Priorità |
|---|---|---|
| RF01 | L’utente deve poter consultare l’elenco dei sentieri | Alta |
| RF02 | L’utente deve poter visualizzare i sentieri su una mappa | Alta |
| RF03 | Ogni sentiero deve avere una scheda con difficoltà, durata, lunghezza e stato | Alta |
| RF04 | La piattaforma deve mostrare informazioni meteorologiche | Alta |
| RF05 | L’utente deve potersi registrare e accedere | Alta |
| RF06 | L’utente registrato deve poter salvare i sentieri preferiti | Media |
| RF07 | L’utente deve poter inviare una segnalazione | Alta |
| RF08 | L’amministratore deve poter creare, modificare e rimuovere un sentiero | Alta |
| RF09 | L’amministratore deve poter verificare e gestire le segnalazioni | Alta |
| RF10 | L’amministratore deve poter pubblicare avvisi e chiusure | Alta |
| RF11 | La piattaforma deve mostrare punti di interesse | Media |
| RF12 | Il sistema deve notificare aggiornamenti importanti sui sentieri salvati | Media |

---

## 7. Requisiti non funzionali

| ID | Requisito | Priorità |
|---|---|---|
| RNF01 | La piattaforma deve essere utilizzabile da browser desktop e mobile | Alta |
| RNF02 | L’interfaccia deve essere semplice e comprensibile | Alta |
| RNF03 | Le pagine principali devono caricarsi in tempi accettabili | Alta |
| RNF04 | I dati degli utenti devono essere protetti | Alta |
| RNF05 | Solo gli amministratori autorizzati devono accedere all’area di gestione | Alta |
| RNF06 | Le segnalazioni devono essere verificate prima della pubblicazione | Alta |
| RNF07 | Il sistema deve gestire eventuali errori dei servizi esterni | Media |
| RNF08 | La soluzione deve poter essere estesa ad altre aree geografiche | Media |

---

## 8. Vincoli e assunzioni

### Vincoli

- durata prevista di circa 5 mesi;
- budget massimo indicativo di 75.000 euro;
- utilizzo di servizi esterni per mappe e meteo;
- realizzazione limitata a una versione MVP;
- rispetto della normativa sulla protezione dei dati.

### Assunzioni

- il committente fornirà i dati iniziali dei sentieri;
- sarà disponibile un referente dell’ente;
- il team avrà le competenze necessarie;
- la fase pilota comprenderà circa 20–30 sentieri;
- gli amministratori parteciperanno alla verifica delle funzionalità.

---

## 9. Criteri di accettazione

Il progetto sarà considerato accettato quando:

- gli utenti potranno consultare i sentieri e le relative informazioni;
- la mappa mostrerà correttamente i percorsi pilota;
- i dati meteorologici saranno visualizzati;
- gli utenti registrati potranno salvare percorsi e inviare segnalazioni;
- gli amministratori potranno gestire sentieri, avvisi e segnalazioni;
- i requisiti ad alta priorità saranno completati;
- i test principali saranno superati;
- il committente approverà la versione pilota.

---

## 10. Gestione delle modifiche allo scope

Qualsiasi richiesta che modifichi funzionalità, tempi o costi dovrà essere:

1. registrata;
2. valutata dal Project Manager;
3. analizzata per impatto su tempi, costi e rischi;
4. approvata o rifiutata dal committente;
5. riportata nei documenti di progetto.

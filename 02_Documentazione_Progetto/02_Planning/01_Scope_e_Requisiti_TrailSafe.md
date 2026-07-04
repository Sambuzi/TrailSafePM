# Scope e requisiti - TrailSafe

## 1. Scopo del documento

Questo documento raccoglie lo scope del progetto TrailSafe e i requisiti previsti per la prima versione operativa, cioè l'MVP.

Serve a fissare in modo chiaro cosa verrà realizzato, cosa resta fuori da questa fase e quali condizioni dovranno essere soddisfatte per considerare concluso il lavoro.

---

## 2. Obiettivo del progetto

TrailSafe nasce come piattaforma web per consultare sentieri escursionistici in un'area pilota. La prima versione non punta quindi a coprire tutto il territorio, ma a validare il servizio su un numero limitato di percorsi.

Gli utenti dovranno poter cercare e consultare i sentieri, vedere le informazioni principali, controllare meteo e condizioni del percorso, ricevere eventuali avvisi e inviare segnalazioni. Gli amministratori, invece, avranno a disposizione un'area dedicata per aggiornare sentieri, avvisi e segnalazioni ricevute.

---

## 3. Ambito incluso

Rientrano nello scope dell'MVP:

- raccolta, revisione e conferma dei requisiti;
- progettazione dell'interfaccia utente;
- sviluppo della piattaforma web;
- registrazione, accesso e gestione base degli utenti;
- mappa interattiva con i sentieri dell'area pilota;
- schede dei percorsi con le informazioni essenziali;
- visualizzazione di meteo e stato del sentiero;
- salvataggio dei percorsi preferiti;
- invio di segnalazioni da parte degli utenti;
- area amministrativa;
- gestione di sentieri, segnalazioni e avvisi;
- test della piattaforma e rilascio della versione pilota;
- documentazione finale e breve formazione per gli amministratori.

---

## 4. Ambito escluso

Non sono previsti in questa fase:

- applicazioni mobili native;
- tracciamento continuo della posizione degli utenti;
- gestione diretta di emergenze o richieste di soccorso;
- integrazione con centrali operative o servizi di pronto intervento;
- copertura dell'intero territorio nazionale;
- pagamenti o servizi a pagamento;
- sensori, beacon o altri dispositivi fisici installati sui sentieri;
- manutenzione pluriennale dopo la chiusura del progetto.

---

## 5. Deliverable principali

I deliverable attesi sono:

1. documento dei requisiti;
2. prototipo dell'interfaccia;
3. piattaforma web MVP;
4. mappa interattiva dei sentieri;
5. modulo di gestione utenti;
6. modulo di gestione sentieri;
7. modulo meteo e stato dei percorsi;
8. sistema di segnalazione;
9. area amministrativa;
10. piano di test e risultati;
11. manuale sintetico per gli amministratori;
12. documentazione finale di progetto.

---

## 6. Requisiti funzionali

| ID | Requisito | Priorità |
|---|---|---|
| RF01 | L'utente può consultare l'elenco dei sentieri disponibili | Alta |
| RF02 | L'utente può visualizzare i sentieri su una mappa interattiva | Alta |
| RF03 | Ogni sentiero ha una scheda con difficoltà, durata, lunghezza e stato aggiornato | Alta |
| RF04 | La piattaforma mostra le informazioni meteorologiche relative all'area del percorso | Alta |
| RF05 | L'utente può registrarsi ed effettuare l'accesso | Alta |
| RF06 | L'utente registrato può salvare i sentieri preferiti | Media |
| RF07 | L'utente può inviare una segnalazione su un sentiero | Alta |
| RF08 | L'amministratore può creare, modificare e rimuovere un sentiero | Alta |
| RF09 | L'amministratore può verificare e gestire le segnalazioni ricevute | Alta |
| RF10 | L'amministratore può pubblicare avvisi, chiusure o aggiornamenti sullo stato dei percorsi | Alta |
| RF11 | La piattaforma può mostrare punti di interesse collegati ai sentieri | Media |
| RF12 | Il sistema può avvisare l'utente in caso di aggiornamenti importanti sui sentieri salvati | Media |

---

## 7. Requisiti non funzionali

| ID | Requisito | Priorità |
|---|---|---|
| RNF01 | La piattaforma deve funzionare correttamente da browser desktop e mobile | Alta |
| RNF02 | L'interfaccia deve essere semplice da usare anche per utenti non tecnici | Alta |
| RNF03 | Le pagine principali devono caricarsi in tempi accettabili | Alta |
| RNF04 | I dati degli utenti devono essere gestiti in modo sicuro | Alta |
| RNF05 | L'area di gestione deve essere accessibile solo agli amministratori autorizzati | Alta |
| RNF06 | Le segnalazioni devono essere controllate prima di essere rese visibili o utilizzate come aggiornamento ufficiale | Alta |
| RNF07 | Il sistema deve gestire eventuali errori dei servizi esterni, come mappe o meteo | Media |
| RNF08 | La soluzione deve poter essere estesa in futuro ad altre aree geografiche | Media |

---

## 8. Vincoli e assunzioni

### Vincoli

- durata prevista di circa 5 mesi;
- budget massimo indicativo di 75.000 euro;
- utilizzo di servizi esterni per mappe e dati meteo;
- rilascio limitato a una versione MVP;
- rispetto della normativa sulla protezione dei dati personali.

### Assunzioni

- il committente fornirà i dati iniziali dei sentieri;
- sarà disponibile un referente dell'ente per verifiche e chiarimenti;
- il team avrà accesso alle competenze tecniche necessarie;
- la fase pilota comprenderà circa 20-30 sentieri;
- gli amministratori parteciperanno alla verifica delle funzionalità prima del rilascio.

---

## 9. Criteri di accettazione

Il progetto potrà essere considerato accettato quando:

- gli utenti riusciranno a consultare i sentieri e le relative informazioni;
- la mappa mostrerà correttamente i percorsi inclusi nella fase pilota;
- i dati meteorologici saranno visibili nelle sezioni previste;
- gli utenti registrati potranno salvare percorsi e inviare segnalazioni;
- gli amministratori potranno gestire sentieri, avvisi e segnalazioni;
- i requisiti ad alta priorità saranno completati;
- i test principali saranno stati eseguiti con esito positivo;
- il committente approverà la versione pilota.

---

## 10. Gestione delle modifiche allo scope

Eventuali richieste che modificano funzionalità, tempi o costi non verranno inserite automaticamente nel progetto. Prima dovranno essere:

1. registrate;
2. valutate dal Project Manager;
3. analizzate rispetto a tempi, costi e rischi;
4. approvate o rifiutate dal committente;
5. riportate nei documenti di progetto, se approvate.

---

<nav class="next-page">
  <a href="02_PBS_e_WBS_TrailSafe.md">Pagina successiva: PBS e WBS &rarr;</a>
</nav>

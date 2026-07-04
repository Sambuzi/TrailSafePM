# Registro problemi, modifiche e rischi - TrailSafe

## 1. Obiettivo del documento

Questo documento raccoglie gli elementi da monitorare durante l'esecuzione del progetto TrailSafe: problemi emersi, richieste di modifica e aggiornamenti sui rischi principali.

Il registro serve a mantenere una vista unica sugli elementi che possono incidere su tempi, qualità, scope o rilascio della versione pilota. Non sostituisce il piano di gestione o l'analisi dei rischi, ma li aggiorna con ciò che emerge durante l'avanzamento reale del progetto.

Viene aggiornato dal Project Manager durante le riunioni di avanzamento o quando un evento richiede una decisione prima della riunione successiva.

---

## 2. Issue log

L'issue log contiene i problemi operativi o tecnici rilevati durante sviluppo, test e preparazione al rilascio. Ogni problema deve avere un responsabile, un'azione prevista e uno stato aggiornato.

| ID | Data | Problema | Impatto | Responsabile | Azione prevista | Stato |
|---|---|---|---|---|---|---|
| P01 | 16/11/2026 | Risposta lenta o non stabile del servizio meteo | Medio | Backend Developer | Verificare API alternativa, introdurre gestione degli errori e messaggi chiari per l'utente | In lavorazione |
| P02 | 18/11/2026 | Alcuni dati dei sentieri sono incompleti | Medio | Referente committente | Completare i dati mancanti e confermarli prima dei test di integrazione | In lavorazione |
| P03 | 20/11/2026 | Visualizzazione della mappa non ottimale su mobile | Basso | Frontend Developer | Correggere il layout responsive e verificarlo sui principali breakpoint | Aperto |
| P04 | 12/01/2027 | Alcune notifiche arrivano in ritardo | Basso | Backend Developer | Controllare il processo di invio e verificare i tempi di aggiornamento | Risolto |

I problemi P01 e P02 richiedono attenzione prioritaria perché possono incidere direttamente sui test di integrazione. P03 è meno critico, ma dovrà essere corretto prima della consegna se la visualizzazione mobile compromette l'uso della mappa.

---

## 3. Change log

Il change log registra le richieste di modifica emerse durante il progetto. Ogni richiesta viene valutata in base all'impatto su tempi, costi, scope, rischi e priorità dell'MVP.

| ID | Data | Richiesta | Motivo | Impatto | Decisione | Responsabile |
|---|---|---|---|---|---|---|
| C01 | 02/10/2026 | Inserire un'app mobile nativa | Migliorare l'accesso da smartphone | Alto su tempi, costi e complessità tecnica | Rifiutata | Sponsor |
| C02 | 20/11/2026 | Rinviare i punti di interesse avanzati | Evitare ritardi sul rilascio delle funzioni essenziali | Riduzione controllata dello scope dell'MVP | Approvata | Project Manager |
| C03 | 20/11/2026 | Valutare un secondo servizio meteo | Ridurre la dipendenza da una sola API esterna | Medio su costi e attività tecniche | Approvata | Project Manager |
| C04 | 22/01/2027 | Correggere alcuni difetti minori dopo il rilascio | I difetti non bloccano l'uso della piattaforma pilota | Basso, con attività successive tracciate | Approvata | Committente |

Le modifiche approvate dovranno essere riportate, se necessario, anche nel backlog, nel Gantt o nel registro decisioni e attività. Le modifiche rifiutate restano nel registro per mantenere traccia della valutazione svolta.

---

## 4. Aggiornamento dei rischi

Questa sezione aggiorna i rischi principali già individuati nella fase di pianificazione. Lo stato riportato tiene conto di ciò che è emerso durante le attività operative e nei report di avanzamento.

| ID | Rischio | Situazione iniziale | Situazione aggiornata | Stato |
|---|---|---|---|---|
| R1 | Dati dei sentieri incompleti | Alto | Il rischio resta presente fino alla verifica finale dei dati pilota | In monitoraggio |
| R2 | Ritardi nello sviluppo | Medio | Aumentato temporaneamente a causa dell'integrazione meteo | In monitoraggio |
| R3 | Aumento dei requisiti | Medio | Ridotto grazie alla procedura di approvazione delle modifiche | Sotto controllo |
| R4 | Problemi con API meteo o mappe | Medio | Rischio confermato; avviata valutazione di un servizio alternativo | In trattamento |
| R5 | Basso coinvolgimento del committente | Medio | Ridotto grazie a riunioni periodiche e approvazioni intermedie | Sotto controllo |
| R6 | Segnalazioni non attendibili | Medio | Ridotto con verifica amministrativa prima della pubblicazione | Sotto controllo |
| R7 | Problemi di sicurezza e privacy | Medio | Nessun problema rilevato, ma il rischio resta aperto fino ai test finali | In monitoraggio |

I rischi R1, R2 e R4 sono quelli da seguire con maggiore attenzione nel breve periodo. Sono collegati tra loro perché dati incompleti, servizi esterni instabili e ritardi tecnici possono incidere sulla qualità della versione pilota.

---

## 5. Regole di aggiornamento

Il Project Manager aggiorna il registro quando:

- emerge un nuovo problema;
- cambia lo stato di un problema già registrato;
- viene richiesta, approvata o rifiutata una modifica;
- cambia la probabilità o l'impatto di un rischio;
- viene applicata un'azione correttiva;
- una decisione modifica scope, tempi, costi o priorità dell'MVP.

Gli stati usati per i problemi sono:

- **Aperto**, quando il problema è stato registrato ma non ancora preso in carico;
- **In lavorazione**, quando il responsabile sta analizzando o correggendo il problema;
- **Risolto**, quando è stata applicata una soluzione;
- **Chiuso**, quando la soluzione è stata verificata.

Gli stati usati per i rischi sono:

- **In monitoraggio**, quando il rischio è presente ma non richiede ancora un'azione correttiva immediata;
- **In trattamento**, quando è già stata avviata un'azione per ridurre probabilità o impatto;
- **Sotto controllo**, quando il rischio resta noto ma le misure adottate sono considerate sufficienti.

Le modifiche approvate o i problemi con impatto medio/alto dovranno essere ripresi nella riunione di avanzamento successiva, così da verificare se l'azione prevista ha prodotto l'effetto atteso.

---

<nav class="next-page">
  <a class="previous-page" href="01_Report_Avanzamento_e_KPI_TrailSafe.html">&larr; Pagina precedente: Report avanzamento e KPI</a>
  <a href="../05_Closing/01_Accettazione_e_Chiusura_TrailSafe.html">Pagina successiva: Accettazione e chiusura &rarr;</a>
</nav>

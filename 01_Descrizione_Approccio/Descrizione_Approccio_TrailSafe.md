<table width="100%" style="border-collapse: collapse; border: none; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;">
  <tr>
    <!-- Dati Accademici e Studente -->
    <td align="left" valign="middle" style="border: none; padding: 0; width: 65%;">
      <div style="border-left: 4px solid #990000; padding-left: 15px; margin: 10px 0;">
        <span style="font-size: 18px; font-weight: 800; letter-spacing: 0.5px; color: #111111; text-transform: uppercase;">Alma Mater Studiorum • Università di Bologna</span><br>
        <span style="font-size: 14px; font-weight: 600; color: #555555;">Corso di Laurea Magistrale in Ingegneria e Scienze Informatiche</span>
      </div>
      <div style="margin-top: 25px; font-size: 13px; color: #444444; line-height: 1.6;">
        <span style="color: #777777;">Insegnamento:</span> <strong>Project Management</strong><br>
        <span style="color: #777777;">Anno Accademico:</span> 2025/2026<br>
        <span style="color: #777777;">Studente:</span> <strong>Sajmir Buzi</strong>
      </div>
    </td>
    <!-- Logo di Ateneo -->
    <td align="right" valign="middle" style="border: none; padding: 0; width: 35%;">
      <img src="../02_Documentazione_Progetto/00_Assets/Immagini/logo_unibo.svg" alt="Logo Università di Bologna" width="240" style="display: block; max-width: 100%; height: auto;">
    </td>
  </tr>
</table>

<br>
<hr style="border: 0; height: 1px; background: linear-gradient(to right, #990000, rgba(0,0,0,0.1)); margin-bottom: 30px;">

# Descrizione dell'approccio utilizzato - TrailSafe

## 1. Introduzione

Questo elaborato presenta il lavoro svolto per il progetto TrailSafe nell'ambito dell'insegnamento di Project Management. L'obiettivo non è descrivere soltanto un'idea software, ma mostrare come quella idea sia stata trasformata in un progetto strutturato, con una logica di gestione, una pianificazione, un controllo dell'avanzamento e una chiusura formale.

TrailSafe è stato pensato come una piattaforma web dedicata alla consultazione dei sentieri escursionistici. Il problema di partenza è abbastanza concreto: chi organizza un'escursione spesso deve cercare informazioni in fonti diverse, come siti istituzionali, mappe online, previsioni meteo, comunicazioni locali o segnalazioni informali. Questo rende più difficile capire se un percorso sia aperto, aggiornato, sicuro o interessato da criticità temporanee.

La piattaforma proposta prova a rispondere a questa esigenza raccogliendo in un unico ambiente le informazioni essenziali sui sentieri. Per gli escursionisti significa poter consultare percorsi, schede informative, condizioni meteo, avvisi e segnalazioni. Per l'ente gestore significa avere uno strumento più ordinato per aggiornare i contenuti, controllare le segnalazioni ricevute e pubblicare eventuali chiusure o comunicazioni operative.

Il progetto è stato costruito come scenario simulato per un ente parco territoriale. Per mantenerlo realistico, TrailSafe non è stato trattato come una piattaforma completa e definitiva, ma come MVP, cioè una prima versione funzionante e limitata. L'MVP riguarda un'area geografica pilota e un numero iniziale di circa 20-30 sentieri. Questa scelta permette di verificare il valore della soluzione senza aumentare subito complessità, tempi e costi.

Il contenuto del file descrive quindi l'intero percorso di gestione del progetto: avvio, pianificazione, esecuzione, monitoraggio e chiusura. Leggendolo, si dovrebbe capire non solo che cosa fa TrailSafe, ma anche quali documenti sono stati prodotti, perché sono stati prodotti e come le varie parti del progetto sono collegate tra loro.

---

## 2. Scelta dell'approccio di gestione

Per TrailSafe è stato scelto un approccio ibrido, perché il progetto contiene sia elementi che devono essere definiti in modo stabile fin dall'inizio, sia parti che beneficiano di verifiche progressive.

La parte iniziale è stata gestita con un'impostazione più tradizionale. Prima di simulare lo sviluppo della piattaforma sono stati chiariti obiettivi, scope, deliverable, ruoli, tempi, costi, rischi e criteri di accettazione. Questi aspetti servono a dare una cornice chiara al progetto e a evitare che l'MVP diventi troppo ampio o poco controllabile.

La parte realizzativa, invece, è stata organizzata per iterazioni. Le funzionalità sono state divise in blocchi di lavoro: prima utenti e accesso, poi mappa e sentieri, quindi meteo e segnalazioni, area amministrativa, test e rilascio. Questa suddivisione rende più naturale controllare l'avanzamento e permette di intervenire sulle priorità se emergono problemi.

La scelta dell'approccio ibrido è coerente con la natura del progetto. TrailSafe ha vincoli abbastanza precisi, come durata, budget e perimetro dell'MVP, ma contiene anche componenti che possono richiedere aggiustamenti, ad esempio l'interfaccia, l'integrazione con i servizi meteo e cartografici, la gestione delle segnalazioni e la qualità dei dati sui sentieri.

Un approccio completamente tradizionale avrebbe dato molto controllo, ma poca flessibilità durante lo sviluppo. Un approccio completamente Agile, invece, avrebbe reso meno evidente la gestione iniziale di budget, milestone, responsabilità e accettazione formale. L'approccio ibrido è stato quindi scelto come compromesso: pianificazione chiara all'inizio, ma lavoro organizzato in modo progressivo durante l'esecuzione.

---

## 3. Avvio del progetto

La prima fase del progetto è stata dedicata a capire perché TrailSafe dovesse essere realizzato, quale problema volesse risolvere e quali limiti dovesse rispettare.

Il Business Case presenta il problema principale: le informazioni sui sentieri sono spesso frammentate. Un escursionista può dover consultare più fonti per sapere se un percorso è aperto, se ci sono criticità, se il meteo è favorevole o se altri utenti hanno segnalato problemi. Anche per l'ente gestore la situazione può diventare complessa, perché le segnalazioni arrivano da canali diversi e non sempre vengono trasformate rapidamente in comunicazioni ufficiali.

Nel Business Case sono state valutate diverse alternative. Mantenere la situazione attuale non avrebbe richiesto investimenti, ma non avrebbe risolto il problema. Ampliare un sito istituzionale già esistente sarebbe stato possibile, ma meno adatto a gestire mappe interattive, segnalazioni, preferiti e aggiornamenti frequenti. La soluzione scelta è stata quindi realizzare TrailSafe come piattaforma dedicata, limitata inizialmente a un MVP.

Il Project Charter formalizza l'avvio del progetto. In questo documento sono stati definiti obiettivo generale, contesto, ambito iniziale, stakeholder, deliverable, milestone, vincoli, assunzioni, rischi iniziali e criteri di successo. Il Charter chiarisce anche il ruolo del Project Manager, che ha il compito di coordinare il lavoro, controllare tempi e costi, gestire la comunicazione con il committente e proporre eventuali azioni correttive.

Lo Stakeholder Register completa la fase iniziale identificando le persone e i gruppi coinvolti. Gli stakeholder principali sono il committente, il Project Manager, il team di sviluppo, gli amministratori della piattaforma, gli escursionisti, i gestori dei sentieri e i fornitori di servizi esterni come mappe e meteo. Per ciascuno viene considerato il tipo di interesse, il livello di influenza e il modo in cui deve essere coinvolto.

In questa fase sono state fissate alcune ipotesi fondamentali: progetto commissionato da un ente parco, area pilota, durata di circa cinque mesi, budget massimo di 75.000 euro e team di dimensioni contenute. Queste scelte servono a rendere la simulazione concreta e coerente per i documenti successivi.

---

## 4. Pianificazione del progetto

La fase di pianificazione è quella più ampia dell'elaborato, perché trasforma l'idea iniziale in un progetto gestibile. Qui vengono definiti il perimetro, il lavoro da svolgere, l'organizzazione del team, i tempi, i costi, i rischi e le regole di gestione.

### Scope e requisiti

Il documento di Scope e Requisiti stabilisce cosa rientra nell'MVP e cosa invece viene lasciato fuori. Questa distinzione è importante perché TrailSafe potrebbe facilmente crescere: app mobile, copertura nazionale, funzioni di emergenza, localizzazione continua e dispositivi fisici sui sentieri sarebbero tutte idee possibili, ma non compatibili con una prima versione limitata.

Le funzionalità incluse nell'MVP sono quelle considerate essenziali: registrazione e accesso degli utenti, elenco dei sentieri, mappa interattiva, schede dei percorsi, informazioni meteo, salvataggio dei preferiti, invio di segnalazioni e area amministrativa. Dal lato amministrativo sono previste funzioni per gestire sentieri, segnalazioni, avvisi e chiusure.

Il documento distingue anche requisiti funzionali e non funzionali. I requisiti funzionali descrivono cosa deve fare la piattaforma. I requisiti non funzionali riguardano invece aspetti come usabilità, accesso da browser desktop e mobile, protezione dei dati, controllo degli accessi amministrativi e gestione degli errori dei servizi esterni.

### PBS e WBS

La PBS e la WBS aiutano a leggere il progetto da due punti di vista diversi. La PBS scompone il prodotto finale, quindi mostra le parti che compongono TrailSafe: area utenti, mappa e sentieri, informazioni ambientali, segnalazioni, area amministrativa e documentazione.

La WBS scompone invece il lavoro necessario per arrivare alla consegna. Le fasi individuate sono gestione del progetto, analisi, progettazione, sviluppo, test, rilascio e chiusura. In questo modo diventa più chiaro quali attività devono essere svolte e come collegarle ai componenti del prodotto.

Questa distinzione è utile perché evita confusione tra prodotto e lavoro. La PBS mostra cosa deve essere realizzato, mentre la WBS mostra come il team deve organizzarsi per arrivare a quel risultato specifico.

### Organizzazione e RACI

Il documento Organizzazione e RACI definisce i ruoli coinvolti e chiarisce le responsabilità. I ruoli principali sono Sponsor o Committente, Project Manager, Business Analyst, UX/UI Designer, sviluppatori, Tester e referente degli amministratori.

La matrice RACI assegna per ogni attività chi è responsabile dell'esecuzione, chi approva, chi viene consultato e chi deve essere informato. Questo è particolarmente utile in un team piccolo, dove alcune persone possono coprire più ruoli, ma le responsabilità devono comunque rimanere chiare.

Nel progetto TrailSafe il Project Manager coordina il lavoro e mantiene il contatto con il committente. Il Business Analyst lavora sui requisiti. Il Designer si occupa di interfaccia e flussi utente. Gli sviluppatori realizzano frontend, backend e integrazioni. Il Tester verifica il rispetto dei requisiti. Il referente amministratori aiuta a controllare che l'area di gestione sia adatta all'uso reale.

### Tempi, costi e Gantt

La pianificazione temporale e dei costi è stata raccolta in un file Excel. Il Gantt organizza le attività lungo i circa cinque mesi previsti, mostrando durate, dipendenze e milestone. Le attività tecniche sono in parte sovrapposte, perché in un progetto software alcune fasi possono procedere in parallelo dopo la definizione iniziale dei requisiti.

Il budget massimo è stato fissato a 75.000 euro. La stima considera personale, servizi esterni, infrastruttura, test, documentazione, formazione e una riserva per imprevisti. Il budget non viene trattato solo come numero finale, ma come vincolo da controllare durante il progetto, soprattutto se emergono richieste di modifica o problemi tecnici.

### Analisi dei rischi

L'analisi dei rischi individua gli eventi che potrebbero influire negativamente sul progetto. I rischi sono stati divisi in tecnici, organizzativi, operativi e di progetto.

I rischi più rilevanti riguardano la qualità dei dati sui sentieri, la dipendenza da servizi esterni per mappe e meteo, possibili ritardi nello sviluppo, aumento dei requisiti e problemi di sicurezza o privacy. Per ogni rischio sono stati indicati probabilità, impatto, priorità, responsabile e azione prevista.

Questa parte è importante perché TrailSafe dipende da elementi non completamente controllabili dal team. Se i dati forniti dal committente sono incompleti, la piattaforma può funzionare tecnicamente ma risultare poco affidabile. Se il servizio meteo ha problemi, alcune funzionalità possono subire ritardi. Per questo il rischio viene monitorato lungo tutto il progetto.

### Piano di gestione

Il Piano di Gestione raccoglie le regole operative del progetto. Include comunicazione, qualità, monitoraggio, gestione dei problemi, gestione delle modifiche e gestione dei documenti.

La scelta è stata di non creare troppi piani separati, ma di mantenere un documento unico e leggibile. In questo modo si capisce come vengono organizzate le riunioni, come vengono tracciate le decisioni, come si controlla la qualità, come si registrano i problemi e come vengono approvate eventuali modifiche allo scope.

---

## 5. Esecuzione del progetto

La fase di esecuzione simula il passaggio dalla pianificazione al lavoro operativo. Non viene sviluppato codice reale, ma viene descritta la gestione del lavoro come se il progetto fosse in corso.

Il Backlog e Piano delle Iterazioni traduce i requisiti in user story e organizza il lavoro in cinque iterazioni. La prima riguarda utenti e accesso, perché la piattaforma deve avere una base applicativa. La seconda riguarda mappa e sentieri, cioè il cuore del servizio. La terza aggiunge meteo, stato dei percorsi e segnalazioni. La quarta introduce l'area amministrativa. La quinta è dedicata a test, caricamento dati, formazione e rilascio.

Le funzionalità ad alta priorità devono essere completate prima della consegna. Le funzionalità a priorità media, come alcuni punti di interesse avanzati o aggiornamenti più evoluti, possono essere rinviate se rischiano di compromettere tempi, budget o qualità dell'MVP.

Il documento Kick-off e Riunioni di Progetto raccoglie le principali riunioni simulate. Sono presenti il kick-off, la revisione dei requisiti, una riunione di avanzamento e la preparazione al rilascio. Per ogni incontro sono indicati partecipanti, ordine del giorno, sintesi, decisioni e attività assegnate.

Il Registro Decisioni e Attività serve invece a collegare ciò che viene deciso alle attività operative. Le decisioni sono identificate con codici che iniziano con D, mentre le attività iniziano con A. Questo permette di ricostruire perché una certa attività è stata assegnata, chi ne è responsabile e se è stata completata.

Durante l'esecuzione viene simulata anche una scelta tipica di progetto: rinviare alcune funzioni a priorità media per proteggere il rilascio dell'MVP. Questa decisione mostra concretamente il valore dell'approccio scelto: il progetto rimane controllato, ma può adattarsi quando emergono problemi durante la sua esecuzione.

---

## 6. Monitoraggio e controllo

La fase di Monitoring & Controlling serve a verificare se il progetto sta procedendo secondo il piano. In TrailSafe questa fase è stata rappresentata con un report di avanzamento e un registro dedicato a problemi, modifiche e rischi.

Il Report di Avanzamento e KPI fotografa lo stato del progetto al 20/11/2026. Vengono controllati attività completate, ritardo complessivo, budget utilizzato, requisiti ad alta priorità completati, rischi aperti e problemi aperti.

Nel report è stato simulato un lieve ritardo tecnico, pari a circa quattro giorni, legato all'integrazione del servizio meteo. Il ritardo non blocca la consegna finale, ma richiede di fare abbastanza attenzione. Le azioni correttive previste sono dare priorità all'integrazione meteo, valutare un servizio alternativo, completare la verifica dei dati dei sentieri, aggiornare il Gantt e rinviare funzioni secondarie se necessario.

Il Registro Problemi, Modifiche e Rischi raccoglie gli elementi da seguire durante l'avanzamento. L'issue log registra problemi come risposta lenta del servizio meteo, dati incompleti e visualizzazione mobile da correggere. Il change log registra richieste di modifica, tra cui l'idea di un'app mobile nativa, rifiutata perché avrebbe aumentato troppo tempi e costi. La sezione rischi aggiorna la situazione rispetto all'analisi iniziale.


---

## 7. Chiusura del progetto

La fase di chiusura serve a verificare che il progetto possa essere formalmente concluso e che il committente possa accettare il risultato.

Il documento Accettazione e Chiusura controlla i deliverable consegnati: gestione utenti, mappa dei sentieri, schede dei percorsi, informazioni meteo, sistema di segnalazione, area amministrativa, test, manuale amministratori e documentazione finale. Viene inoltre confrontato il risultato finale con il piano iniziale: durata rispettata, budget rispettato, area pilota confermata, 25 sentieri caricati e requisiti ad alta priorità completati.

Alcune attività restano aperte, ma non sono considerate bloccanti. Tra queste ci sono miglioramenti alla visualizzazione mobile, controllo delle notifiche in caso di connessione lenta, eventuali punti di interesse avanzati e valutazione futura di un'applicazione mobile nativa. Queste attività possono essere riprese in una fase successiva, ma non impediscono l'accettazione dell'MVP.

La Relazione Finale raccoglie le considerazioni conclusive. Vengono analizzati ciò che ha funzionato, le difficoltà incontrate, le decisioni risultate utili e i possibili miglioramenti futuri. Tra gli aspetti positivi ci sono il controllo dello scope, l'uso dell'MVP, le riunioni periodiche, la divisione in iterazioni e i test con utenti pilota. Tra gli aspetti da migliorare emergono la verifica anticipata dei servizi esterni, il controllo iniziale dei dati e più tempo per i test su dispositivi mobili.

La riunione finale formalizza l'accettazione della versione pilota e la chiusura del progetto nel perimetro concordato.

---

## 8. Documentazione prodotta

La documentazione è stata organizzata seguendo le fasi del ciclo di vita del progetto.

### Initiating

- Project Charter;
- Business Case;
- Stakeholder Register;
- Obiettivi, vincoli e criteri di successo.

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
- Chiusura Finale.

Questa organizzazione permette di seguire il progetto dall'idea iniziale fino alla consegna. Ogni documento ha una funzione precisa e contribuisce a rendere tracciabile il lavoro svolto.

## 9. Considerazioni finali

Con questo elaborato ho rappresentato TrailSafe come un progetto software gestito in modo completo, dalla nascita dell'idea fino alla chiusura. Il lavoro non si limita a dire cosa dovrebbe fare la piattaforma, ma mostra come il progetto viene impostato, pianificato, seguito e concluso.

L'aspetto più importante è stato mantenere il controllo dello scope. TrailSafe potrebbe facilmente diventare un progetto molto più grande, ma l'obiettivo dell'MVP è diverso: realizzare una prima versione concreta, utile e verificabile. Per questo alcune funzionalità sono state escluse o rinviate.

L'approccio ibrido si è rivelato adatto alla simulazione. La parte iniziale ha dato struttura al progetto, mentre la divisione in iterazioni ha reso più semplice rappresentare l'avanzamento e la gestione delle priorità. Anche il monitoraggio dei rischi e delle modifiche ha avuto un ruolo importante, soprattutto nel caso del ritardo legato al servizio meteo e della qualità dei dati sui sentieri.

Nel complesso, il progetto mostra come un'idea software possa essere trasformata in un percorso di gestione ordinato. Partendo da un problema concreto, cioè la frammentazione delle informazioni sui sentieri, sono stati definiti obiettivi, vincoli, deliverable, ruoli, tempi, costi, rischi, attività e criteri di accettazione. La chiusura finale conferma che l'MVP è stato consegnato nel perimetro previsto e che le attività residue possono essere valutate in una fase successiva.
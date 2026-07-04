# Analisi dei rischi - TrailSafe

## 1. Obiettivo del documento

Questo documento raccoglie i principali rischi individuati per il progetto TrailSafe e le azioni previste per ridurne probabilità o impatto.

L'analisi non va considerata come un elenco chiuso: durante il progetto potranno emergere nuovi rischi, oppure alcuni rischi già presenti potranno cambiare peso. Per questo motivo il registro sarà rivisto nelle riunioni di avanzamento e aggiornato quando cambiano condizioni, priorità o informazioni disponibili.

L'obiettivo pratico è evitare che problemi prevedibili, come dati incompleti, ritardi o dipendenze da servizi esterni, vengano affrontati solo quando sono già diventati bloccanti.

---

## 2. Categorie di rischio

I rischi sono stati organizzati in quattro gruppi, così da facilitarne la lettura e assegnare più chiaramente le responsabilità di controllo.

- **tecnici**, legati allo sviluppo della piattaforma, alle integrazioni e alla sicurezza;
- **organizzativi**, legati al team, alla disponibilità delle persone e al coinvolgimento degli stakeholder;
- **di progetto**, legati a tempi, costi, priorità e modifiche allo scope;
- **operativi**, legati alla qualità dei dati, all'uso della piattaforma e alla gestione delle segnalazioni.

Questa classificazione non è rigida: alcuni rischi possono avere effetti su più aree. Ad esempio, dati dei sentieri incompleti sono un problema operativo, ma possono generare anche ritardi di progetto.

---

## 3. Scala di valutazione

Per mantenere la valutazione semplice e leggibile, probabilità e impatto sono misurati su una scala da 1 a 3.

### Probabilità

| Valore | Significato | Descrizione sintetica |
|---|---|---|
| 1 | Bassa | Il rischio è possibile, ma poco probabile nelle condizioni attuali |
| 2 | Media | Il rischio potrebbe verificarsi e va monitorato |
| 3 | Alta | Il rischio è realistico o già parzialmente presente |

### Impatto

| Valore | Significato | Descrizione sintetica |
|---|---|---|
| 1 | Basso | Effetto limitato, gestibile senza modifiche rilevanti al piano |
| 2 | Medio | Effetto significativo su attività, qualità o tempi di alcune parti del progetto |
| 3 | Alto | Effetto potenzialmente critico su rilascio, budget, scope o accettazione |

La priorità è calcolata moltiplicando probabilità e impatto. I rischi con valore più alto saranno controllati con maggiore attenzione durante l'avanzamento del progetto.

---

## 4. Registro dei rischi

Il registro seguente riporta i rischi principali noti nella fase di pianificazione. Le azioni previste sono pensate come misure preventive o correttive iniziali; potranno essere aggiornate se il rischio cambia o se l'azione non è sufficiente.

| ID | Rischio | Categoria | Prob. | Impatto | Priorità | Azione prevista | Responsabile |
|---|---|---|---:|---:|---:|---|---|
| R1 | Dati sui sentieri incompleti, incoerenti o non aggiornati | Operativo | 3 | 3 | 9 | Verifica dei dati con il committente prima del caricamento e controllo a campione durante i test | Referente committente |
| R2 | Ritardi nello sviluppo delle funzionalità principali | Progetto | 2 | 3 | 6 | Controllo settimanale delle attività, revisione delle priorità e anticipo dei blocchi al committente | Project Manager |
| R3 | Aumento dei requisiti durante il progetto | Progetto | 2 | 3 | 6 | Applicare una procedura formale di change request e valutare l'impatto su tempi, costi e scope | Project Manager |
| R4 | Problemi con API meteo o servizi di mappe | Tecnico | 2 | 3 | 6 | Valutare servizi alternativi, gestire gli errori applicativi e prevedere messaggi chiari per l'utente | Backend Developer |
| R5 | Basso coinvolgimento del committente nelle verifiche | Organizzativo | 2 | 3 | 6 | Pianificare incontri regolari, fissare momenti di approvazione e segnalare subito eventuali mancate risposte | Project Manager |
| R6 | Segnalazioni degli utenti non attendibili o incomplete | Operativo | 3 | 2 | 6 | Rendere obbligatori i campi essenziali e pubblicare gli aggiornamenti solo dopo verifica amministrativa | Referente amministratori |
| R7 | Problemi di sicurezza o privacy | Tecnico | 2 | 3 | 6 | Limitare gli accessi, proteggere i dati personali e svolgere test specifici sulle funzioni sensibili | Backend Developer |
| R8 | Interfaccia poco chiara per utenti o amministratori | Tecnico | 2 | 2 | 4 | Testare il prototipo con un piccolo gruppo di utenti e raccogliere feedback prima dello sviluppo completo | UX/UI Designer |
| R9 | Superamento del budget disponibile | Progetto | 1 | 3 | 3 | Controllo periodico dei costi e utilizzo della riserva solo dopo valutazione del Project Manager | Project Manager |
| R10 | Assenza temporanea di una risorsa del team | Organizzativo | 1 | 2 | 2 | Condivisione della documentazione, allineamenti interni e redistribuzione delle attività più urgenti | Project Manager |

---

## 5. Rischi prioritari

Il rischio più rilevante è legato alla qualità dei dati sui sentieri. Se le informazioni iniziali non sono complete o affidabili, la piattaforma può risultare formalmente funzionante ma poco utile nella fase pilota.

Richiedono attenzione anche i rischi collegati a tempi e scope. TrailSafe è un MVP, quindi l'aggiunta di nuove funzionalità durante il progetto potrebbe spostare il focus dalle funzioni essenziali e rendere più difficile rispettare tempi e budget.

I rischi prioritari da monitorare con maggiore frequenza sono:

1. dati dei sentieri non corretti, incompleti o non aggiornati;
2. ritardi nello sviluppo delle funzionalità principali;
3. aumento non controllato dei requisiti;
4. dipendenza da servizi esterni per mappe e meteo;
5. problemi di sicurezza e privacy;
6. basso coinvolgimento del committente nelle verifiche intermedie.

Questi rischi saranno discussi nelle riunioni di avanzamento e, se necessario, collegati ad azioni correttive specifiche.

---

## 6. Controllo dei rischi

Il Project Manager mantiene aggiornato il registro dei rischi e verifica che le azioni previste vengano effettivamente seguite. Il controllo avverrà soprattutto nei momenti di avanzamento, ma potrà essere anticipato se emerge un problema urgente.

Il registro sarà aggiornato quando:

- emerge un nuovo rischio;
- cambia la probabilità o l'impatto di un rischio già noto;
- viene applicata un'azione correttiva;
- una decisione di progetto modifica tempi, costi o scope;
- un rischio può essere considerato chiuso.

Per ogni rischio verrà indicato uno stato di avanzamento:

- **aperto**, quando il rischio è presente e richiede attenzione;
- **in monitoraggio**, quando non è bloccante ma va controllato periodicamente;
- **chiuso**, quando il rischio non è più rilevante o l'azione prevista è stata completata.

Le situazioni critiche dovranno essere comunicate al committente senza attendere la riunione successiva, soprattutto se possono incidere sul rilascio della versione pilota.

---

<nav class="next-page">
  <a href="06_Piano_di_Gestione_TrailSafe.md">Pagina successiva: Piano di gestione &rarr;</a>
</nav>

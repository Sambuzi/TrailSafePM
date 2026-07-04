# Kick-off e riunioni di progetto - TrailSafe

## 1. Obiettivo del documento

Questo documento raccoglie le principali riunioni previste durante il progetto TrailSafe e ne sintetizza contenuti, decisioni e attività assegnate.

Non si tratta di verbali estesi, ma di una traccia operativa utile per mantenere allineati team e committente. Ogni incontro dovrà lasciare evidenza di ciò che è stato deciso, dei punti ancora aperti e delle attività da completare prima della riunione successiva.

Per ogni riunione vengono indicati:

- partecipanti;
- ordine del giorno;
- sintesi dell'incontro;
- decisioni prese;
- attività assegnate, con responsabile e scadenza.

---

## 2. Kick-off meeting

**Data:** 07/09/2026  
**Durata:** 1 ora  
**Partecipanti:** Sponsor, Project Manager, Business Analyst, UX/UI Designer, sviluppatori, Tester, referente del committente.

### Ordine del giorno

1. Presentazione del progetto.
2. Obiettivi della versione MVP.
3. Ruoli e responsabilità.
4. Tempi, milestone e principali vincoli.
5. Modalità di comunicazione.
6. Rischi iniziali e punti da chiarire.

### Sintesi

Il Project Manager presenta gli obiettivi di TrailSafe e chiarisce il perimetro della prima versione. Viene confermato che l'MVP sarà limitato a un'area pilota e a un numero iniziale di circa 20-30 sentieri.

Il gruppo concorda sull'importanza di partire dai dati disponibili sui percorsi, perché la qualità delle informazioni iniziali avrà un impatto diretto sulla mappa, sulle schede sentiero e sui test finali.

Viene inoltre confermato un approccio ibrido: pianificazione iniziale, controllo periodico dell'avanzamento e sviluppo organizzato in iterazioni.

### Decisioni

- confermato lo scope dell'MVP;
- confermata la durata indicativa di 5 mesi;
- approvata la riunione operativa settimanale del team;
- approvata la riunione di avanzamento con il committente ogni due settimane;
- confermata la necessità di validare i dati dei sentieri prima del caricamento definitivo.

### Attività assegnate

| Attività | Responsabile | Scadenza |
|---|---|---|
| Avviare la raccolta dei requisiti | Business Analyst | 14/09/2026 |
| Preparare l'elenco iniziale dei sentieri | Referente committente | 18/09/2026 |
| Predisporre l'ambiente di lavoro | Team tecnico | 18/09/2026 |
| Aprire il primo registro dei rischi | Project Manager | 18/09/2026 |

---

## 3. Revisione dei requisiti

**Data:** 02/10/2026  
**Durata:** 1 ora  
**Partecipanti:** Project Manager, Business Analyst, referente del committente, referente amministratori.

### Ordine del giorno

1. Presentazione dei requisiti raccolti.
2. Verifica delle funzionalità principali.
3. Controllo delle funzioni escluse dall'MVP.
4. Conferma delle priorità.
5. Approvazione dei requisiti.

### Sintesi

Vengono esaminati i requisiti relativi ad area utenti, mappa, sentieri, meteo, segnalazioni e area amministrativa. Il referente degli amministratori evidenzia la necessità di rendere semplice la gestione di avvisi e chiusure, perché saranno tra le funzioni più usate dopo il rilascio.

Il committente conferma le funzionalità ad alta priorità. Le notifiche avanzate e alcuni elementi accessori, come punti di interesse più dettagliati, restano a priorità media e potranno essere ridotti se il piano dovesse subire ritardi.

### Decisioni

- approvati i requisiti principali;
- confermato il limite dell'MVP alla sola area pilota;
- esclusa l'applicazione mobile nativa dalla prima versione;
- confermata la priorità alta per mappa, schede sentiero, segnalazioni e area amministrativa.

### Attività assegnate

| Attività | Responsabile | Scadenza |
|---|---|---|
| Aggiornare il documento dei requisiti | Business Analyst | 05/10/2026 |
| Avviare il prototipo dell'interfaccia | UX/UI Designer | 05/10/2026 |
| Verificare completezza dei dati sentiero disponibili | Referente committente | 09/10/2026 |

---

## 4. Riunione di avanzamento

**Data:** 20/11/2026  
**Durata:** 45 minuti  
**Partecipanti:** Project Manager, team di sviluppo, Tester, referente del committente.

### Ordine del giorno

1. Stato delle attività.
2. Verifica del Gantt.
3. Problemi tecnici aperti.
4. Aggiornamento dei rischi.
5. Attività successive.

### Sintesi

L'area utenti e la mappa risultano quasi completate. Le schede sentiero sono già consultabili, anche se alcuni dati devono ancora essere verificati con il committente.

L'integrazione del servizio meteo ha richiesto più tempo del previsto, soprattutto per la gestione degli errori e dei casi in cui il servizio esterno non risponde. Al momento il ritardo non compromette la data finale, ma il Project Manager segnala la necessità di proteggere le funzionalità essenziali dell'MVP.

Il team concorda di rinviare alcune funzioni a priorità media, così da concentrare il lavoro su meteo, segnalazioni, area amministrativa e test di integrazione.

### Decisioni

- confermata la priorità alle funzioni necessarie per l'MVP;
- rinviata la gestione avanzata dei punti di interesse;
- richiesto un nuovo controllo tecnico sull'integrazione meteo;
- confermata la preparazione anticipata dei test di integrazione.

### Attività assegnate

| Attività | Responsabile | Scadenza |
|---|---|---|
| Completare l'integrazione meteo | Backend Developer | 27/11/2026 |
| Aggiornare il Gantt | Project Manager | 23/11/2026 |
| Preparare i test di integrazione | Tester | 30/11/2026 |
| Confermare i dati mancanti dei sentieri | Referente committente | 27/11/2026 |

---

## 5. Preparazione al rilascio

**Data:** 22/01/2027  
**Durata:** 1 ora  
**Partecipanti:** Sponsor, Project Manager, team di sviluppo, Tester, referente amministratori.

### Ordine del giorno

1. Risultati dei test.
2. Problemi ancora aperti.
3. Preparazione della versione pilota.
4. Formazione degli amministratori.
5. Criteri di accettazione.
6. Passaggi per la consegna finale.

### Sintesi

I requisiti ad alta priorità risultano completati e verificati. Restano alcuni problemi minori, principalmente legati a rifiniture dell'interfaccia e a messaggi informativi, che non impediscono il rilascio della versione pilota.

Il committente accetta di registrarli come attività successive, purché siano tracciati nel registro dei problemi e non incidano sulla consultazione dei sentieri o sulla gestione amministrativa.

Viene confermata la formazione degli amministratori prima della pubblicazione, con attenzione particolare alla gestione di segnalazioni, avvisi e chiusure.

### Decisioni

- autorizzato il rilascio pilota;
- i problemi minori saranno registrati e corretti dopo la consegna;
- confermata la verifica finale con il committente;
- confermata la formazione degli amministratori prima della pubblicazione.

### Attività assegnate

| Attività | Responsabile | Scadenza |
|---|---|---|
| Preparare l'ambiente di rilascio | Team tecnico | 25/01/2027 |
| Completare il manuale amministratori | Business Analyst | 25/01/2027 |
| Svolgere la formazione | Project Manager | 27/01/2027 |
| Preparare il verbale di accettazione | Project Manager | 28/01/2027 |
| Aggiornare il registro dei problemi residui | Tester | 28/01/2027 |

---

## 6. Archiviazione e tracciamento

I verbali e le sintesi delle riunioni saranno salvati nella cartella del progetto insieme agli altri documenti di gestione.

Le decisioni rilevanti dovranno essere riportate anche nel Registro Decisioni e Attività, soprattutto quando incidono su scope, priorità, tempi, rischi o rilascio.

Le attività assegnate durante le riunioni saranno considerate aperte fino a conferma del responsabile o verifica del Project Manager. In caso di attività non completate entro la scadenza, il punto verrà ripreso nella riunione successiva.

---

<nav class="next-page">
  <a href="03_Registro_Decisioni_e_Attivita_TrailSafe.html">Pagina successiva: Registro decisioni e attivita &rarr;</a>
</nav>

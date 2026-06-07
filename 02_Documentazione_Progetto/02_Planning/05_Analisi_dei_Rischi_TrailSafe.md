# Analisi dei Rischi – TrailSafe

## 1. Obiettivo

Questo documento raccoglie i principali rischi del progetto TrailSafe e le azioni previste per ridurne probabilità e impatto.

I rischi saranno controllati durante le riunioni di avanzamento e aggiornati quando necessario.

---

## 2. Categorie di rischio

I rischi sono stati divisi in quattro gruppi:

- **tecnici**, legati allo sviluppo e ai servizi esterni;
- **organizzativi**, legati al team e agli stakeholder;
- **di progetto**, legati a tempi, costi e requisiti;
- **operativi**, legati ai dati, agli utenti e all’uso della piattaforma.

---

## 3. Scala di valutazione

### Probabilità

| Valore | Significato |
|---|---|
| 1 | Bassa |
| 2 | Media |
| 3 | Alta |

### Impatto

| Valore | Significato |
|---|---|
| 1 | Basso |
| 2 | Medio |
| 3 | Alto |

La priorità è calcolata moltiplicando probabilità e impatto.

---

## 4. Registro dei rischi

| ID | Rischio | Categoria | Prob. | Impatto | Priorità | Azione prevista | Responsabile |
|---|---|---|---:|---:|---:|---|---|
| R1 | Dati sui sentieri incompleti o non aggiornati | Operativo | 3 | 3 | 9 | Verifica dei dati con il committente prima del caricamento | Referente committente |
| R2 | Ritardi nello sviluppo | Progetto | 2 | 3 | 6 | Controllo settimanale delle attività e revisione delle priorità | Project Manager |
| R3 | Aumento dei requisiti durante il progetto | Progetto | 2 | 3 | 6 | Uso di una procedura formale per le richieste di modifica | Project Manager |
| R4 | Problemi con API meteo o mappe | Tecnico | 2 | 3 | 6 | Valutare servizi alternativi e gestire gli errori applicativi | Backend Developer |
| R5 | Basso coinvolgimento del committente | Organizzativo | 2 | 3 | 6 | Pianificare incontri regolari e approvazioni intermedie | Project Manager |
| R6 | Segnalazioni degli utenti non attendibili | Operativo | 3 | 2 | 6 | Pubblicare le segnalazioni solo dopo verifica amministrativa | Referente amministratori |
| R7 | Problemi di sicurezza o privacy | Tecnico | 2 | 3 | 6 | Limitare gli accessi, proteggere i dati e svolgere test specifici | Backend Developer |
| R8 | Interfaccia poco chiara per gli utenti | Tecnico | 2 | 2 | 4 | Testare il prototipo con un piccolo gruppo di utenti | UX/UI Designer |
| R9 | Superamento del budget | Progetto | 1 | 3 | 3 | Controllo mensile dei costi e utilizzo della riserva solo se necessario | Project Manager |
| R10 | Assenza temporanea di una risorsa del team | Organizzativo | 1 | 2 | 2 | Condivisione della documentazione e redistribuzione delle attività | Project Manager |

---

## 5. Rischi prioritari

I rischi che richiedono maggiore attenzione sono:

1. dati dei sentieri non corretti o incompleti;
2. ritardi nello sviluppo;
3. aumento non controllato dei requisiti;
4. dipendenza dai servizi esterni;
5. problemi di sicurezza e privacy.

Questi rischi saranno verificati con maggiore frequenza durante il progetto.

---

## 6. Controllo dei rischi

Il Project Manager aggiornerà il registro:

- durante le riunioni di avanzamento;
- quando emerge un nuovo rischio;
- quando cambia la probabilità o l’impatto;
- quando viene applicata un’azione correttiva.

Per ogni rischio sarà controllato anche lo stato:

- aperto;
- in monitoraggio;
- chiuso.

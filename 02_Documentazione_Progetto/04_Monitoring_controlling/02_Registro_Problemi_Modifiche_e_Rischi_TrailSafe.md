# Registro Problemi, Modifiche e Rischi – TrailSafe

## 1. Obiettivo

Questo documento raccoglie:

- i problemi emersi durante il progetto;
- le richieste di modifica;
- l’aggiornamento dei rischi principali.

Il registro viene aggiornato durante le varie riunioni di avanzamento.

---

## 2. Issue Log

| ID | Data | Problema | Impatto | Responsabile | Azione prevista | Stato |
|---|---|---|---|---|---|---|
| P01 | 16/11/2026 | Risposta lenta del servizio meteo | Medio | Backend Developer | Verificare API alternativa e introdurre gestione degli errori | In lavorazione |
| P02 | 18/11/2026 | Alcuni dati dei sentieri sono incompleti | Medio | Referente committente | Completare e verificare i dati mancanti | In lavorazione |
| P03 | 20/11/2026 | Visualizzazione mappa non ottimale su mobile | Basso | Frontend Developer | Correggere il layout responsive | Aperto |
| P04 | 12/01/2027 | Alcune notifiche arrivano in ritardo | Basso | Backend Developer | Controllare il processo di invio | Risolto |

---

## 3. Change Log

| ID | Data | Richiesta | Motivo | Impatto | Decisione | Responsabile |
|---|---|---|---|---|---|---|
| C01 | 02/10/2026 | Inserire un’app mobile nativa | Migliorare l’accesso da smartphone | Alto su tempi e costi | Rifiutata | Sponsor |
| C02 | 20/11/2026 | Rinviare i punti di interesse avanzati | Evitare ritardi sul rilascio | Riduzione dello scope | Approvata | Project Manager |
| C03 | 20/11/2026 | Valutare un secondo servizio meteo | Ridurre il rischio di dipendenza da una sola API | Medio sui costi | Approvata | Project Manager |
| C04 | 22/01/2027 | Correggere alcuni difetti minori dopo il rilascio | Non bloccano l’uso della piattaforma | Basso | Approvata | Committente |

---

## 4. Aggiornamento dei rischi

| ID | Rischio | Situazione iniziale | Situazione aggiornata | Stato |
|---|---|---|---|---|
| R1 | Dati dei sentieri incompleti | Alto | Il rischio resta presente fino alla verifica finale | In monitoraggio |
| R2 | Ritardi nello sviluppo | Medio | Aumentato a causa dell’integrazione meteo | In monitoraggio |
| R3 | Aumento dei requisiti | Medio | Ridotto grazie alla procedura di approvazione | Sotto controllo |
| R4 | Problemi con API meteo o mappe | Medio | Rischio confermato; valutata una soluzione alternativa | In trattamento |
| R5 | Basso coinvolgimento del committente | Medio | Ridotto grazie alle riunioni periodiche | Sotto controllo |
| R6 | Segnalazioni non attendibili | Medio | Ridotto con la verifica da parte degli amministratori | Sotto controllo |
| R7 | Problemi di sicurezza e privacy | Medio | Nessun problema rilevato, ma il rischio resta aperto | In monitoraggio |

---

## 5. Regole di aggiornamento

Il Project Manager aggiorna il registro quando:

- emerge un nuovo problema;
- cambia lo stato di un problema;
- viene richiesta una modifica;
- cambia la probabilità o l’impatto di un rischio;
- viene applicata un’azione correttiva.

Gli stati usati sono:

- **Aperto**
- **In lavorazione**
- **Risolto**
- **Chiuso**
- **In monitoraggio**
- **Sotto controllo**

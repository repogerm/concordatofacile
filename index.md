# ConcordatoFacile: Guida introduttiva

Benvenuto alla guida di ConcordatoFacile, un sistema che semplifica la gestione dei contratti di locazione a canone concordato per le associazioni di categoria.

Questa soluzione innovativa si basa su un insieme di componenti IT all'avanguardia che lavorano in sinergia per garantire un'esperienza utente efficiente, sicura e automatizzata. Queste componenti comprendono Google Workspace, JotForm, DocVariables, e Yet Another Mail Merge (YAMM), ciascuna delle quali svolge un ruolo fondamentale all'interno di ConcordatoFacile.

Prima di iniziare, è importante sottolineare che questa guida è di natura generica e serve come un punto di partenza per la tua esperienza con ConcordatoFacile. Poiché uno dei punti di forza di ConcordatoFacile è la sua capacità di essere personalizzato su misura per le tue esigenze specifiche, potrebbe esserci qualche passaggio unico per il tuo caso che non è indicato qui.

Nel caso in cui ci siano processi non menzionati o se hai domande specifiche relative alla tua configurazione di ConcordatoFacile, non esitare a contattarmi all'indirizzo email [germ.riccio@gmail.com](mailto:germ.riccio@gmail.com). Sarà un piacere assisterti affinché che tu possa sfruttare al meglio tutte le funzionalità di ConcordatoFacile.

Questa guida ti condurrà attraverso il processo di gestione dei contratti di locazione, assicurandoti una navigazione fluida attraverso ogni sezione dell'applicazione. Se non sei un esperto di tecnologia, non preoccuparti! Questa guida è stata progettata per essere chiara e intuitiva, anche per gli utenti con meno familiarità con la tecnologia.

> 💡 Il successo nella gestione dei contratti di locazione a canone concordato per la tua associazione risiede nella precisione. Assicurati di inserire accuratamente le informazioni richieste in ciascun foglio elettronico e di seguire attentamente le istruzioni presenti in questa guida per garantire il corretto funzionamento del sistema.

## Indice

1. [Ricezione Della Richiesta](#ricezione-della-richiesta)
2. [Elaborazione Della Richiesta](#elaborazione-della-richiesta)
3. [Registrazione di un Nuovo Membro](#registrazione-di-un-nuovo-membro)
4. [Generazione del Contratto](#generazione-del-contratto)
5. [Salvataggio e Registrazione del Contratto](#salvataggio-e-registrazione-del-contratto)
6. [Monitoraggio dei Contratti](#monitoraggio-dei-contratti)
7. [FAQs e Risoluzione dei Problemi](#faqs-e-risoluzione-dei-problemi)

## Ricezione della Richiesta

Il modulo JotForm è uno strumento versatile e potente per la raccolta di richieste di assistenza da vari utenti. Può essere inviato a proprietari di immobili, inquilini o agenzie immobiliari. Questo permette di gestire efficacemente un'ampia gamma di richieste, mantenendo tutte le informazioni ordinate e accessibili in un unico luogo: il foglio "Archivio richieste".

Seguendo i passaggi descritti in questa sezione, potrai apprendere come gestire le richieste inviate attraverso JotForm.

Prima di esaminare i dettagli tecnici, diamo un'occhiata al modulo che gli utenti utilizzano per inviare le loro richieste.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_1-57-44%20PM.gif) |
|:--:|
| **Panoramica del modulo JotForm** |

Una volta che un utente sottomette una richiesta tramite JotForm, le informazioni fornite vengono automaticamente trasferite e registrate nel foglio "Archivio richieste". Ogni invio di un modulo JotForm rappresenta una singola riga in questo foglio, con i dati forniti dagli utenti ordinatamente organizzati in colonne distinte.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_2-05-47%20PM.gif) | 
|:--:|
| **Panoramica del foglio "Archivio richieste"** |

Nel foglio "Archivio richieste", ci sono due colonne di primaria importanza a cui devi prestare attenzione:

- "Completata?" (Colonna A): Se immetti "sì" in questa cella, il modulo JotForm associato viene ritenuto gestito e quindi rimosso dalla lista delle attività in sospeso.
- "Note" (Colonna B): Questa colonna è designata per contenere eventuali osservazioni o commenti pertinenti al modulo JotForm. È il posto perfetto per registrare dettagli aggiuntivi o lasciare dei promemoria.

Gestire attentamente la colonna "Completata?" è fondamentale per mantenere un flusso di lavoro efficiente e ben organizzato. Quando hai finito di gestire un modulo e non sono necessarie ulteriori azioni, scrivi "sì" in questa cella. Questo indica che la richiesta è stata completamente trattata e la rimuove dalla lista delle attività pendenti. Se, invece, un modulo richiede ancora attenzione, lascia questa cella vuota.

> 💡 Ricorda: L'aggiornamento dello stato di "Completata?" dovrebbe avvenire solo quando sei assolutamente sicuro che una richiesta sia stata completamente gestita.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_2-17-28%20PM.gif) |
|:--:|
| **Impostando "sì" sotto la colonna "Completata?" nel foglio 'Archivio richieste', il conteggio di "Richieste da Elaborare" nel foglio "Pannello di Controllo" si aggiorna automaticamente** |

Ricorda, sebbene i dati nel foglio "Archivio richieste" vengano inseriti automaticamente, hai sempre la possibilità di correggerli o modificarli se l'utente ha commesso errori o ha cambiato idea.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_1-15-08%20PM.gif) |
|:--:|
| **Esempio di modifica dei dati inseriti tramite JotForm** |

### Pronto a Procedere?

Fino a questo punto, abbiamo esaminato come viene ricevuta una richiesta e come gestire le informazioni iniziali nel foglio "Archivio richieste". Tuttavia, ci sono ancora diversi passaggi da completare prima che una richiesta possa essere considerata effettivamente "Completata". Non è quindi il momento di inserire "sì" in "Completata?". Continua a leggere per scoprire quali sono i passaggi successivi da seguire per gestire una richiesta in modo veloce e accurato.

## Elaborazione della Richiesta

Il foglio "Richiesta in Elaborazione" presenta la richiesta meno recente inviata tramite JotForm e ancora in sospeso - essenzialmente, la più datata nella coda di lavoro. In questo quadro, avrai l'opportunità di esaminare i dati inseriti dagli utenti e verificare la presenza di eventuali errori, che verranno resi visibili nelle colonne evidenziate in giallo. Qualora riscontrassi imprecisioni, potrai tornare al foglio "Archivio richieste" per correggere i dati. Questo foglio non è destinato unicamente al monitoraggio dei dati, ma anche per effettuare i calcoli indispensabili per la generazione dell'asseverazione e dell'allegato H.

[panoramica foglio elaborazione]

Per quanto riguarda i calcoli: se l'immobile in questione si trova in un comune presente nel database di ConcordatoFacile, i valori minimi e massimi dell'area omogenea cui appartiene saranno identificati automaticamente dal sistema. Nel caso in cui il comune non fosse incluso nel database, riceverai una notifica. 

[screenshot notifica]

In tale circostanza, dovrai verificare, consultando gli accordi territoriali pertinenti, la correttezza dei dati forniti dagli utenti. All'occorrenza, potrai apportare modifiche nel foglio "Archivio richieste" come precedentemente indicato. Per individuare rapidamente la richiesta in lavorazione, copia il "Submission ID" dal foglio "Richiesta in Elaborazione" e cercalo nel foglio "Archivio richieste", come illustrato nel seguente video.

[link al video che dimostra come correggere dati valori minimi e massimi errati]

Se una richiesta di assistenza perviene da un utente non registrato all'associazione, un messaggio di errore apparirà nel foglio "Richiesta in Elaborazione". 

[screenshot errore]

In tale evenienza, vai al foglio "Gestione Anagrafiche" per registrare il nuovo membro o rinnovare la sua iscrizione. Da qui potrai anche monitorare lo stato di iscrizione di tutti i membri.

[link al video che dimostra come registrare nuovo membro]

Una volta completata la registrazione del nuovo membro, torna al foglio "Richiesta in Elaborazione" e accertati che il valore di "Totale Errori" sia 0, quindi attiva i calcoli iterativi come illustrato nel video sottostante e attendi che "Sì" compaia nella cella sotto "Procedere con DocMerge?".

[link al video che dimostra come funzionano i calcoli iterativi]

Al comparire del "Sì", procedi cliccando su "Link a DocMerge", come mostrato nel video sottostante.

[link al video che dimostra come aprire docmerge]

Ottimo lavoro finora! Nei passaggi successivi, ti guiderò attraverso il processo di generazione automatica dei documenti necessari per finalizzare la richiesta. Imparerai come archiviarli correttamente nella cartella desiderata e come documentare quest'operazione e i file appena generati nel foglio "Archivio Contratti - YAMM". Questo ti permetterà di spedire la documentazione in maniera rapida alle parti interessate.

Ora che hai compiuto tutti questi passaggi, potresti chiederti se sia il momento di segnare "Sì" nella colonna "Completata?" del foglio "Archivio richieste". Non proprio! Ci sono ancora alcuni passaggi cruciali da completare prima di poter considerare conclusa l'intera procedura.

[documentazione ancora da scrivere qui]

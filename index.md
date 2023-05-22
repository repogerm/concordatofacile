# ConcordatoFacile: Guida introduttiva

Benvenuto alla guida di ConcordatoFacile, un sistema che semplifica la gestione dei contratti di locazione a canone concordato per le associazioni di categoria. Questa soluzione innovativa si basa su un insieme di componenti IT all'avanguardia che lavorano in sinergia per garantire un'esperienza utente efficiente, sicura e automatizzata.

È fondamentale notare che questa guida serve come un punto di riferimento generale per avviare la tua esperienza con ConcordatoFacile. La versatilità di questa soluzione risiede nella sua capacità di adattarsi alle tue esigenze specifiche, il che significa che potrebbero esserci aspetti unici al tuo caso che non sono espressamente delineati qui.

Se dovessero emergere processi non coperti da questa guida o se avessi domande specifiche riguardanti la tua configurazione di ConcordatoFacile, non esitare a contattarmi all'indirizzo email [germ.riccio@gmail.com](mailto:germ.riccio@gmail.com). Sarà un piacere assisterti affinché tu possa sfruttare al meglio tutte le funzionalità di questo strumento.

Prima di iniziare, è utile familiarizzare con alcune delle componenti chiave utilizzate in ConcordatoFacile. Di seguito è presentato un glossario che fornisce una descrizione dettagliata di ciascuna di queste componenti.

## Glossario

### Google Drive

Google Drive è un servizio di archiviazione cloud fornito da Google. Questo servizio offre un ambiente sicuro e affidabile per l'archiviazione di dati e documenti. In ConcordatoFacile, Google Drive funge da deposito centrale per tutti i file e i documenti relativi ai contratti di locazione. Questo include i moduli compilati, i contratti generati e qualsiasi altro documento correlato. L'uso di Google Drive garantisce che i documenti siano sempre disponibili, accessibili da qualsiasi dispositivo connesso a Internet e protetti da perdite di dati.

### Google Sheets

Google Sheets è un'applicazione per fogli di calcolo basata su cloud, anch'essa fornita da Google. Questa applicazione offre funzionalità simili a quelle di Microsoft Excel, ma si differenzia da quest'ultima per la possibilità di accedere e modificare i dati da qualsiasi dispositivo con una connessione Internet e per il suo efficiente sistema di collaborazione in tempo reale. In ConcordatoFacile, Google Sheets è utilizzato per gestire, analizzare ed elaborare i dati raccolti tramite JotForm. Inoltre, Google Sheets funge da interfaccia per l'interazione con altre componenti del sistema, come DocVariables e YAMM.

### JotForm

JotForm è uno strumento online che permette di creare moduli personalizzati. Questo strumento offre un'ampia gamma di opzioni di personalizzazione, rendendolo adatto a una varietà di applicazioni. In ConcordatoFacile, JotForm è utilizzato per raccogliere le informazioni necessarie per la creazione del contratto di locazione. Queste informazioni vengono raccolte tramite un modulo online che può essere compilato dai proprietari di immobili, dagli inquilini o dalle agenzie immobiliari. Una volta compilato, il modulo viene inviato a Google Sheets per l'elaborazione.

### DocVariables

DocVariables è uno strumento per la generazione automatica di documenti. Questo strumento è progettato per semplificare il processo di creazione di documenti personalizzati, eliminando la necessità di copiare e incollare manualmente le informazioni da una fonte all'altra. In ConcordatoFacile, DocVariables utilizza i dati raccolti tramite JotForm e gestiti in Google Sheets per generare automaticamente un documento contenente il contratto di locazione completo. Questo documento è poi pronto per essere condiviso con le parti coinvolte nel contratto di locazione.

### Yet Another Mail Merge (YAMM)

Yet Another Mail Merge, o YAMM, è uno strumento per l'invio di email personalizzate in modo automatizzato. Questo strumento è particolarmente utile quando si devono inviare email a molte persone contemporaneamente, ma si desidera personalizzare il contenuto per ciascun destinatario. In ConcordatoFacile, YAMM utilizza i dati gestiti in Google Sheets per inviare i contratti di locazione via email. Questo garantisce una comunicazione tempestiva e professionale con le parti coinvolte.

Ora che hai una comprensione di base delle componenti chiave di ConcordatoFacile, possiamo procedere con la guida.

> 💡 Ricorda: Il successo nella gestione dei contratti di locazione a canone concordato per la tua associazione risiede nella precisione. Assicurati di inserire accuratamente le informazioni richieste in ciascun foglio Google Sheets e di seguire attentamente le istruzioni presenti in questa guida per garantire il corretto funzionamento del sistema.

## Indice

1. [Ricezione Della Richiesta](#ricezione-della-richiesta)
2. [Elaborazione Della Richiesta](#elaborazione-della-richiesta)
3. [Registrazione di un Nuovo Membro](#registrazione-di-un-nuovo-membro)
4. [Generazione del Contratto](#generazione-del-contratto)
5. [Salvataggio e Registrazione del Contratto](#salvataggio-e-registrazione-del-contratto)
6. [Monitoraggio dei Contratti](#monitoraggio-dei-contratti)
7. [FAQs e Risoluzione dei Problemi](#faqs-e-risoluzione-dei-problemi)

## Ricezione della Richiesta

ConcordatoFacile utilizza un modulo JotForm per raccogliere tutte le informazioni necessarie dagli utenti che richiedono assistenza per i contratti di locazione a canone concordato. Tale modulo può essere trasmesso via e-mail oppure integrato direttamente sul sito web della tua associazione. Questo ti permetterà di gestire efficacemente un'ampia gamma di richieste, mantenendo tutte le informazioni ordinate e accessibili in un unico luogo: il foglio elettronico "Archivio richieste".

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_1-57-44%20PM.gif) |
|:--:|
| **Panoramica del modulo JotForm** |

Quando un utente invia una richiesta tramite JotForm, le informazioni fornite vengono automaticamente trasferite e registrate in "Archivio richieste". Ogni invio di un modulo JotForm rappresenta una singola riga in questo foglio, con i dati forniti dagli utenti ordinatamente organizzati in colonne distinte.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_2-05-47%20PM.gif) | 
|:--:|
| **Panoramica del foglio "Archivio richieste"** |

Nel foglio "Archivio richieste", ci sono due colonne di primaria importanza a cui prestare attenzione:

- "Completata?" (Colonna A): Se immetti "sì" in questa cella, il modulo JotForm associato viene ritenuto gestito e quindi rimosso dalla lista delle attività in sospeso.
- "Note" (Colonna B): Questa colonna è designata per contenere eventuali osservazioni o commenti pertinenti al modulo JotForm. È il posto perfetto per registrare dettagli aggiuntivi o lasciare dei promemoria.

Gestire attentamente la colonna "Completata?" è fondamentale per mantenere un flusso di lavoro efficiente e ben organizzato. Quando hai finito di gestire un modulo e non sono necessarie ulteriori azioni, scrivi "sì" in questa cella. Questo indica che la richiesta è stata completamente trattata e la rimuove dalla lista delle attività pendenti. Se, invece, un modulo richiede ancora attenzione, lascia questa cella vuota.

> 💡 Ricorda: L'aggiornamento dello stato di "Completata?" dovrebbe avvenire solo quando sei assolutamente sicuro che una richiesta sia stata completamente gestita.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_2-17-28%20PM.gif) |
|:--:|
| **Impostando "sì" sotto la colonna "Completata?" nel foglio 'Archivio richieste', il conteggio di "Richieste da Elaborare" nel foglio "Pannello di Controllo" si aggiorna automaticamente** |

Sebbene i dati nel foglio "Archivio richieste" vengano inseriti automaticamente, hai sempre la possibilità di correggerli o modificarli se l'utente ha commesso errori o ha cambiato idea.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_1-15-08%20PM.gif) |
|:--:|
| **Esempio di modifica dei dati inseriti tramite JotForm** |

### Pronto a Procedere?

Fino a questo punto, abbiamo esaminato come ricevere una richiesta e come gestire le informazioni iniziali nel foglio "Archivio richieste". Tuttavia, ci sono ancora diversi passaggi da completare prima che una richiesta possa essere considerata effettivamente "Completata". Non è quindi il momento di inserire "sì" nella colonna "A". Continua a leggere per scoprire quali sono i passaggi successivi da seguire per gestire una richiesta in modo veloce e accurato.

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

Ottimo lavoro finora! Nei passaggi successivi, ti guiderò attraverso il processo di generazione automatica dei documenti necessari per finalizzare la richiesta. Imparerai come archiviarli correttamente nella cartella desiderata e come documentare quest'operazione e i file appena generati nel foglio "Archivio Contratti - YAMM". Questo passaggio ti permetterà di spedire la documentazione in maniera rapida alle parti interessate.

Ora che hai compiuto tutti questi passaggi, potresti chiederti se sia il momento di segnare "Sì" nella colonna "Completata?" del foglio "Archivio richieste". Non proprio! Ci sono ancora alcuni passaggi cruciali da completare prima di poter considerare conclusa l'intera procedura.

[documentazione ancora da scrivere qui]

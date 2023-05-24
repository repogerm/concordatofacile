# ConcordatoFacile: Guida introduttiva

Benvenuto alla guida di ConcordatoFacile, un sistema che semplifica la gestione dei contratti di locazione a canone concordato per le associazioni di categoria. Questa soluzione innovativa si basa su un insieme di componenti IT all'avanguardia che lavorano in sinergia per garantire un'esperienza utente efficiente, sicura e automatizzata. Attraverso una simulazione completa del processo di gestione di una richiesta di assistenza per un contratto di locazione a canone concordato, questa guida ti mostrerà come funziona ConcordatoFacile e come può rendere il tuo lavoro notevolmente più semplice.

È fondamentale notare che questa guida ha lo scopo di fornire un punto di partenza generale per la tua esperienza con ConcordatoFacile. La flessibilità di questa soluzione nell'adattarsi alle tue specifiche esigenze potrebbe comportare aspetti unici nel tuo caso che non sono esplicitamente descritti qui.

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

> 💡 Il successo nella gestione dei contratti di locazione a canone concordato per la tua associazione risiede nella precisione. Assicurati di inserire accuratamente le informazioni richieste in ciascun foglio Google Sheets e di seguire attentamente le istruzioni presenti in questa guida per garantire il corretto funzionamento del sistema.

## Indice

1. [Ricezione della richiesta](#ricezione-della-richiesta)
2. [Elaborazione della richiesta](#elaborazione-della-richiesta)
3. [Registrazione di un nuovo membro](#registrazione-di-un-nuovo-membro)
4. [Generazione dei documenti](#generazione-dei-documenti)
5. [Archiviazione ed invio dei documenti](#archiviazione-ed-invio-dei-documenti)
6. [Pannello di controllo](#pannello-di-controllo)

## Ricezione della richiesta

ConcordatoFacile utilizza un modulo JotForm per raccogliere tutte le informazioni necessarie dagli utenti che richiedono assistenza per i contratti di locazione a canone concordato. Puoi inviare il modulo tramite e-mail o integrarlo direttamente sul sito web della tua associazione. Questo metodo ti permetterà di gestire in modo efficiente una vasta gamma di richieste, mantenendo tutte le informazioni ordinate e accessibili in un unico luogo: il foglio elettronico "Archivio richieste".

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_1-57-44%20PM.gif) |
|:--:|
| **Panoramica del modulo JotForm** |

Quando un utente invia una richiesta tramite JotForm, il sistema trasferisce automaticamente le informazioni fornite e le registra in "Archivio richieste". Ogni invio di un modulo JotForm costituisce una singola riga all'interno di questo foglio, con i dati forniti dagli utenti accuratamente organizzati in colonne distinte.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_2-05-47%20PM.gif) | 
|:--:|
| **Panoramica del foglio "Archivio richieste"** |

Nel foglio "Archivio richieste", ci sono due colonne di primaria importanza a cui è fondamentale prestare attenzione:

- "Completata?" (Colonna A): Se inserisci "sì" in questa cella, il modulo JotForm associato viene considerato come gestito e, di conseguenza, rimosso dalla lista delle attività in sospeso.
- "Note" (Colonna B): Questa colonna è destinata a contenere eventuali osservazioni o commenti pertinenti al modulo JotForm. È il luogo ideale per registrare dettagli aggiuntivi o annotare promemoria.

È fondamentale gestire attentamente la colonna "Completata?" al fine di mantenere un flusso di lavoro efficiente e ben organizzato. Quando hai concluso la gestione di un modulo e non sono necessarie ulteriori azioni, scrivi "sì" in questa cella. Tale azione indicherà che la richiesta è stata completamente trattata e verrà rimossa dalla lista delle attività pendenti. Al contrario, se un modulo richiede ancora attenzione, lascia questa cella vuota.

> 💡 Si consiglia di aggiornare lo stato di "Completata?" solo quando si è assolutamente sicuri che una richiesta sia stata completamente gestita.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_2-17-28%20PM.gif) |
|:--:|
| **Impostando "sì" sotto la colonna "Completata?" nel foglio 'Archivio richieste', il conteggio di "Richieste da Elaborare" nel foglio "Pannello di Controllo" si aggiorna automaticamente** |

Sebbene i dati nel foglio "Archivio richieste" vengano inseriti automaticamente, hai sempre la possibilità di correggerli o modificarli nel caso l'utente abbia commesso degli errori o abbia cambiato idea.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_20_2023_1-15-08%20PM.gif) |
|:--:|
| **Esempio di modifica dei dati inseriti tramite JotForm** |

### Pronto a procedere?

Fino a questo punto, abbiamo esaminato come ricevere una richiesta e come gestire le informazioni iniziali nel foglio "Archivio richieste". Tuttavia, ci sono ancora diversi passaggi da completare prima che una richiesta possa essere considerata effettivamente "Completata". Continua a leggere per scoprire quali sono i passaggi successivi da seguire per gestire una richiesta in modo veloce e accurato.

## Elaborazione della richiesta

Il foglio "Richiesta in Elaborazione" presenta la richiesta meno recente inviata tramite JotForm e ancora in sospeso - essenzialmente, la più datata nella coda di lavoro. In questo quadro, avrai l'opportunità di esaminare i dati inseriti dagli utenti e verificare la presenza di eventuali errori, che verranno resi visibili nelle colonne evidenziate in giallo. Qualora riscontrassi imprecisioni, potrai tornare al foglio "Archivio richieste" per correggere i dati. Questo foglio non è destinato unicamente al monitoraggio dei dati, ma anche per effettuare i calcoli indispensabili per la generazione dell'asseverazione e dell'allegato H.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_23_2023_12-54-22%20PM.gif) |
|:--:|
| **Panoramica del foglio "Richiesta in elaborazione"** |

Per quanto riguarda i calcoli: se l'immobile in questione si trova in un comune presente nel database di ConcordatoFacile, i valori minimi e massimi dell'area omogenea cui appartiene saranno identificati automaticamente dal sistema. Nel caso in cui il comune non fosse incluso nel database, riceverai una notifica.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_23_2023_1-10-44%20PM.png) |
|:--:|
| **Screenshot notifica** |

In tale circostanza, dovrai verificare, consultando gli accordi territoriali pertinenti, la correttezza dei dati forniti dagli utenti. All'occorrenza, potrai apportare modifiche nel foglio "Archivio richieste" come precedentemente indicato. Per individuare rapidamente la richiesta in lavorazione, copia il "Submission ID" dal foglio "Richiesta in Elaborazione" e cercalo nel foglio "Archivio richieste", come illustrato nel seguente video.

> 💡 Per cercare una stringa specifica in Google Sheets, utilizza la combinazione di tasti "Ctrl + F" (o "Cmd + F" su Mac). Inserisci la stringa nella casella di ricerca che appare e Sheets evidenzierà automaticamente le corrispondenze trovate nel foglio di lavoro corrente.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_23_2023_1-19-08%20PM.gif) |
|:--:|
| **Esempio di modifica dei dati inseriti tramite JotForm** |

### Registrazione di un nuovo membro

Se una richiesta di assistenza perviene da un utente non registrato all'associazione, un messaggio di errore apparirà nel foglio "Richiesta in Elaborazione".

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_23_2023_1-29-28%20PM.png) |
|:--:|
| **Screenshot errore** |

In tale evenienza, vai al foglio "Gestione Anagrafiche" per registrare il nuovo membro o rinnovare la sua iscrizione. Da qui potrai anche monitorare lo stato di iscrizione di tutti i membri.

> ⚠️ Segui questi passaggi per inserire un nuovo membro nel database degli iscritti:
>
> 1. Clicca su "Estensioni" nella barra del menu.
> 2. Seleziona "Macro" dal menu a discesa che appare.
> 3. Nella finestra delle macro, scegli l'opzione "Nuova iscrizione" per avviare la creazione di una nuova iscrizione nel database.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_23_2023_1-38-18%20PM.gif) |
|:--:|
| **Processo di registrazione di un nuovo membro** |

Come puoi notare, nelle colonne colorate in giallo, utilizzate per evidenziare possibili problematiche, è presente un errore evidenziato sulla riga relativa al nuovo iscritto: non esistono contratti collegati a questo membro. Tuttavia, non c'è motivo di preoccuparsi, poiché procederemo a breve con la generazione e l'archiviazione del contratto di locazione a canone concordato per questo utente. Una volta completata questa operazione, l'avviso di errore scomparirà.

Una volta completata la registrazione del nuovo membro, torna al foglio "Richiesta in Elaborazione" e accertati che il valore di "Totale Errori" sia 0, quindi attiva i calcoli iterativi come illustrato nel video sottostante e attendi che "Sì" compaia nella cella sotto "Procedere con DocMerge?". Al comparire del "Sì", procedi cliccando su "DocMerge".

> ⚠️ Segui questi passaggi per gestire i calcoli iterativi e evitare rallentamenti al foglio elettronico:
>
> - Per attivare i calcoli iterativi:
>   1. Fai clic sull'icona "File" nella barra del menu.
>   2. Seleziona "Impostazioni" dal menu a discesa.
>   3. Nella finestra delle impostazioni, fai clic su "Calcolo".
>   4. Imposta l'opzione "Calcolo iterativo" su "on".
>   5. Fai clic su "Salva impostazioni".
> - Per disattivare i calcoli iterativi:
>   1. Segui gli stessi primi tre passaggi sopra menzionati.
>   2. Trova l'opzione "Calcolo iterativo" e impostala su "off".
>   3. Fai clic su "Salva impostazioni".
>
> ⚠️ È necessario disattivare i calcoli iterativi **dopo** aver generato i documenti contenenti l'asseverazione e l'allegato H per evitare rallentamenti indesiderati al foglio elettronico.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/scrnli_5_23_2023_3-20-31%20PM.gif) |
|:--:|
| **Correzione degli errori individuati ed esecuzione dei calcoli necessari per compilare l'asseverazione e l'allegato H** |

Ottimo lavoro finora! Ora che abbiamo compiuto tutti questi passaggi, potresti chiederti se sia il momento di segnare "Sì" nella colonna "Completata?" del foglio "Archivio richieste". Non proprio! Ci sono ancora alcuni passaggi cruciali da completare prima di poter considerare conclusa l'intera procedura.

Nei passaggi successivi, ti guiderò attraverso il processo di generazione automatica dei documenti necessari per finalizzare la richiesta. Imparerai come archiviarli correttamente e come documentare quest'operazione e i file appena generati nel foglio "Archivio Contratti - YAMM". Questo ti permetterà inoltre di spedire la documentazione in maniera rapida alle parti interessate.

## Generazione dei documenti

Una volta che avrai cliccato su "DocMerge", ti troverai di fronte a un documento simile a questo:

[screenshot che mostra il documento che si trova di fronte all'utente]

Per procedere con la generazione dei documenti, segui i passaggi mostrati nel video sottostante. DocVariables utilizzerà i dati contenuti in Google Sheets per generare i documenti, basandosi sui dati elaborati dal sistema e da te revisionati.

> ⚠️ Segui attentamente questi passaggi per generare i documenti utilizzando DocVariables.
>
> 1. Clicca su "Estensioni".
> 2. Seleziona "DocVariables" per avviare DocVariables.
> 3. Clicca su "DocMerge" per avviare la funzione DocMerge.
> 4. Fai clic su "Run Now" per avviare il processo di trasferimento dei dati da Google Sheets.
> 5. Clicca sul link blu a destra di "Export Folder" per accedere alla cartella in cui è stata archiviata la documentazione generata automaticamente.

[video]

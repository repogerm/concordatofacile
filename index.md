# ConcordatoFacile: Guida introduttiva

Benvenuto alla guida di ConcordatoFacile, un sistema che semplifica la gestione dei contratti di locazione a canone concordato per le associazioni di categoria. Questa soluzione innovativa si basa su un insieme di componenti IT all'avanguardia che lavorano in sinergia per garantire un'esperienza utente efficiente, sicura e automatizzata. Attraverso una simulazione completa del processo di gestione di una richiesta di assistenza per un contratto di locazione a canone concordato, questa guida ti mostrerà come funziona ConcordatoFacile e come può rendere il tuo lavoro notevolmente più semplice.

È fondamentale notare che questa guida ha lo scopo di fornire un punto di partenza generale per la tua esperienza con ConcordatoFacile. La flessibilità di questa soluzione nell'adattarsi alle tue specifiche esigenze potrebbe comportare aspetti unici nel tuo caso che non sono esplicitamente descritti qui.

Se dovessero emergere processi non coperti da questa guida o se avessi domande specifiche riguardanti la tua configurazione di ConcordatoFacile, non esitare a contattarmi all'indirizzo email [germ.riccio@gmail.com](mailto:germ.riccio@gmail.com). Sarà un piacere assisterti affinché tu possa sfruttare al meglio tutte le funzionalità di questo strumento.

Prima di iniziare, è utile familiarizzare con alcune delle componenti chiave utilizzate in ConcordatoFacile. Di seguito è presentato un glossario che fornisce una descrizione dettagliata di ciascuna di queste componenti.

## Glossario

### Google Drive

Google Drive fornisce un servizio di archiviazione cloud offerto da Google. Questo servizio ti permette di conservare i tuoi dati e documenti in un ambiente sicuro e affidabile. In ConcordatoFacile, Google Drive funge da deposito centrale per tutti i file e i documenti relativi ai contratti di locazione. Questo comprende i moduli compilati, i contratti generati e qualsiasi altro documento pertinente. L'utilizzo di Google Drive assicura che i documenti siano sempre disponibili, accessibili da qualsiasi dispositivo connesso a Internet e protetti da eventuali perdite di dati.

### Google Sheets

Google Sheets è un'applicazione basata su cloud per fogli di calcolo fornita da Google. A differenza di Microsoft Excel, questa applicazione consente di accedere e modificare i dati da qualsiasi dispositivo con una connessione Internet. In ConcordatoFacile, Google Sheets viene utilizzato per gestire, analizzare ed elaborare i dati raccolti tramite JotForm. Inoltre, Google Sheets funge da interfaccia per interagire con altre componenti del sistema, come DocVariables e YAMM.

### JotForm

JotForm è uno strumento online che consente di creare moduli personalizzati. Questo strumento offre una vasta gamma di opzioni di personalizzazione, rendendolo adatto a diverse applicazioni. Nel contesto di ConcordatoFacile, JotForm viene utilizzato per raccogliere le informazioni necessarie alla creazione del contratto di locazione. Queste informazioni vengono raccolte attraverso un modulo online, che può essere compilato dai proprietari di immobili, dagli inquilini o dalle agenzie immobiliari. Una volta compilato, il modulo viene inviato a Google Sheets per essere elaborato.

### DocVariables

DocVariables è uno strumento che consente la generazione automatica di documenti. È stato progettato per semplificare il processo di creazione di documenti personalizzati, eliminando la necessità di copiare e incollare manualmente le informazioni da una fonte all'altra. Nel contesto di ConcordatoFacile, DocVariables utilizza i dati raccolti tramite JotForm e gestiti in Google Sheets per generare automaticamente un documento completo che include il contratto di locazione. Questo documento è pronto per essere condiviso con tutte le parti coinvolte nel contratto di locazione.

### Yet Another Mail Merge (YAMM)

Yet Another Mail Merge, o YAMM, è uno strumento che consente di inviare email personalizzate in modo automatizzato. Questo strumento risulta particolarmente utile quando si ha la necessità di inviare email a un gran numero di destinatari contemporaneamente, ma si desidera comunque personalizzare il contenuto per ciascun ricevente. Nel contesto di ConcordatoFacile, YAMM viene impiegato per utilizzare i dati gestiti in Google Sheets al fine di inviare i contratti di locazione tramite email. Questo approccio garantisce una comunicazione rapida e professionale con tutte le parti coinvolte.

Ora che hai una comprensione di base delle componenti chiave di ConcordatoFacile, possiamo procedere con la guida.

> 💡 Il successo nella gestione dei contratti di locazione a canone concordato per la tua associazione risiede nella precisione. Assicurati di inserire accuratamente le informazioni richieste in ciascun foglio Google Sheets e di seguire attentamente le istruzioni presenti in questa guida per garantire il corretto funzionamento del sistema.

## Indice

1. [Ricezione della richiesta](#ricezione-della-richiesta)
2. [Elaborazione della richiesta](#elaborazione-della-richiesta)
3. [Registrazione di un nuovo membro](#registrazione-di-un-nuovo-membro)
4. [Generazione e archiviazione dei documenti](#generazione-e-archiviazione-dei-documenti)
5. [Invio dei documenti](#invio-dei-documenti)
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

## Registrazione di un nuovo membro

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

Nelle colonne gialle, che evidenziano possibili problematiche, noterai un errore sulla riga del nuovo iscritto che indica l'assenza di un contratto collegato a questo membro. Non c'è bisogno di preoccuparsi: nei passaggi successivi, completeremo la richiesta di questo utente generando e archiviando il contratto di locazione a canone concordato. Una volta completate queste operazioni, l'avviso di errore scomparirà.

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

Nelle prossime fasi, esplorerai il processo di generazione automatica dei documenti necessari per completare la richiesta. Scoprirai come archiviarli correttamente e come registrare l'operazione e i file appena generati nel foglio "Archivio Contratti - YAMM". Questi passaggi non solo semplificano e accelerano l'invio della documentazione alle parti coinvolte, ma implementano anche un efficiente sistema di monitoraggio per tutte le scadenze dei contratti di locazione, consentendoti di notificare i membri della tua associazione in modo tempestivo.

## Generazione e archiviazione dei documenti

Dopo aver cliccato su "DocMerge", vedrai un documento analogo a quello mostrato nello screenshot sottostante.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/screenshot-docs.google.com-2023.05.24-12_51_11.png) |
|:--:|
| **Screenshot del template** |

Per generare i documenti, segui i passaggi mostrati nel video sottostante. DocVariables utilizzerà i dati contenuti in Google Sheets per generare i documenti, basandosi sui dati elaborati dal sistema e da te revisionati.

> ⚠️ Segui attentamente questi passaggi per generare i documenti utilizzando DocVariables.
>
> 1. Clicca su "Estensioni".
> 2. Seleziona "DocVariables" per avviare DocVariables.
> 3. Clicca su "DocMerge" per avviare la funzione DocMerge.
> 4. Fai clic su "Run Now" per avviare il processo di trasferimento dei dati da Google Sheets.
> 5. Clicca sul link blu a destra di "Export Folder" per accedere alla cartella in cui è stata archiviata la documentazione generata automaticamente.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/screencast-docs.google.com-2023.05.24-14_51_08.gif) |
|:--:|
| **Panoramica del template ed esecuzione di DocMerge** |

Apri la cartella dove è archiviata la documentazione generata automaticamente e ordina i file dal più recente al più vecchio per posizionare in cima alla lista i documenti appena generati. Identifica e apri questi nuovi documenti, poi revisiona il loro contenuto. Se necessario, puoi ancora effettuare modifiche: il file è in un formato editabile.

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/screencast-docs.google.com-2023.05.24-16_07_36.gif) |
|:--:|
| **Nell'esempio specifico, la documentazione è archiviata in una cartella denominata 'output' e tra i documenti generati da DocVariables, oltre al contratto di locazione, all'asseverazione e all'allegato H, noterai anche la presenza di una ricevuta e del modulo di iscrizione all'associazione** |

Bene, i documenti sono stati generati correttamente. È il momento di tornare a Google Sheets per registrare l'operazione appena effettuata. Prima di procedere, come già indicato, disattivare i calcoli iterativi se sono ancora attivi è un passaggio obbligatorio. Conclusa questa operazione, accedere al foglio di calcolo "Archivio contratti - YAMM" e avviare il processo di registrazione di un nuovo contratto, seguendo le istruzioni presenti nel video seguente.

> ⚠️ Ecco come registrare l'ultimo contratto generato nel database dei contratti:
>
> 1. Clicca su "Estensioni" nella barra del menu.
> 2. Seleziona "Macro" dal menu a discesa che appare.
> 3. Quando si apre la finestra delle macro, scegli l'opzione "Nuovo contratto".

| ![Alt Text](https://filedn.eu/llmlYMMbHsXVkfJvhTGDV50/concordatofacile/demo_assets/screencast-docs.google.com-2023.05.24-16_14_24.gif) |
|:--:|
| **Registrazione ultimo contratto in "Archivio contratti - YAMM** |

## Invio dei documenti

spiegare colonne in questo foglio, spiegare yamm

spiegare foglio contratti in scadenza

Bene! Abbiamo gestito con successo la richiesta in tutti i suoi aspetti: abbiamo esaminato il contenuto inviato tramite JotForm, eseguito i calcoli necessari su Google Sheets, creato i documenti con DocVariables, e inviato tramite email la documentazione completa all'utente che ha richiesto assistenza per il contratto di locazione a canone concordato. 

Prima di contrassegnare la richiesta come completata, controlliamo le note indicate nella colonna B del foglio "Archivio Richieste". Se, ad esempio, le note indicano che l'utente non ha ancora effettuato il pagamento o ci sono altri motivi che impediscono di considerare la richiesta come completata, eviteremo di scrivere "sì" nella colonna A. Se tutto va per il verso giusto e le note non evidenziano alcun problema, procederemo a contrassegnare la richiesta come completata scrivendo "sì" nella colonna A.

## Pannello di controllo

Il foglio "Pannello di Controllo" fornisce una visione d'insieme costantemente aggiornata dei dati relativi alla tua associazione.

[panoramica del "pannello di controllo"]

1. **Generatore ID membri**: Questo campo è responsabile della generazione automatica di un ID univoco per ogni nuovo membro che si iscrive alla tua associazione. L'ID è composto dal prefisso "MEM" seguito da un numero di sei cifre. Questo sistema di ID univoci semplifica il tracciamento e la gestione dei membri, garantendo che ognuno abbia un'identificazione unica nel sistema. Puoi utilizzare questi ID per individuare i membri specifici, seguire il loro coinvolgimento nell'associazione e monitorare le loro attività.

2. **Generatore ID contratti**: Allo stesso modo, il generatore di ID dei contratti fornisce un identificatore univoco per ogni nuovo contratto creato. Ogni contratto viene automaticamente assegnato a un ID che inizia con il prefisso "CON" seguito da un numero di sei cifre. Questo sistema di ID univoci consente di organizzare e archiviare i contratti in modo strutturato nel database dell'associazione. Ogni volta che è necessario fare riferimento a un contratto specifico o effettuare modifiche, l'ID univoco semplifica l'individuazione del contratto desiderato, migliorando l'efficienza delle operazioni interne.

3. **Richieste da elaborare**: Questo campo tiene traccia del numero di richieste provenienti da JotForm che devono essere elaborate. Tenere il conteggio delle richieste pendenti è di fondamentale importanza per garantire che nessuna richiesta venga trascurata o dimenticata. Monitorare il carico di lavoro in arrivo ti aiuta inoltre a organizzare le risorse necessarie per gestire le richieste in modo tempestivo ed efficiente.

4. **Iscrizioni attive**: Questo campo conta il numero di membri attualmente iscritti all'associazione. Mantenere un monitoraggio costante delle iscrizioni attive è fondamentale per valutare la crescita dell'associazione nel tempo e per valutare l'efficacia delle strategie di marketing e fidelizzazione implementate.

5. **Iscrizioni scadute**: Questo campo tiene conto del numero di membri la cui iscrizione è scaduta. Monitorare il numero di iscrizioni scadute può essere utile per identificare i membri che potrebbero aver bisogno di un promemoria o di strategie mirate per rinnovare la loro iscrizione. L'identificazione tempestiva dei membri con iscrizioni scadute consente di ridurre la perdita potenziale di adesioni e di mantenere un rapporto attivo con gli ex membri, al fine di favorire il loro coinvolgimento futuro.

6. **Iscrizioni con errori**: Questo campo tiene traccia del numero di iscrizioni che presentano errori. La presenza di iscrizioni errate può causare problemi operativi e compromettere l'efficienza dell'associazione. Monitorare attentamente le iscrizioni con errori consente di identificare rapidamente eventuali problemi e di risolverli tempestivamente. Ciò contribuisce a mantenere l'integrità dei dati dei membri e a garantire una gestione senza intoppi delle informazioni associate.

7. **Totale iscrizioni**: Questo campo rappresenta il numero complessivo di iscrizioni, includendo sia quelle attive che quelle scadute. Fornisce una panoramica completa del numero totale di membri che si sono iscritti all'associazione nel corso del tempo. Rappresenta un indicatore fondamentale per valutare l'andamento complessivo e la crescita dell'associazione nel corso del tempo.

8. **Errori nel database dei contratti:** Questo campo indica il numero di errori presenti nel database dei contratti. Monitorare gli errori nel database dei contratti ti consente di individuare potenziali problematiche o incongruenze nel sistema. Risolvere tempestivamente questi errori garantisce l'integrità e l'accuratezza delle informazioni contrattuali, facilitando così la gestione e la consultazione dei dati in futuro.

9. **Totale contratti in scadenza**: Questo campo tiene conto del numero totale di contratti di locazione che stanno per scadere. Questa informazione ti consente di avere una visione chiara dei contratti che richiedono attenzione imminente. Con questo conteggio, puoi pianificare in anticipo le comunicazioni con i membri interessati al rinnovo dei contratti e assicurarti che le procedure di rinnovo siano gestite in modo tempestivo ed efficace. Tenere sotto controllo i contratti in scadenza ti aiuta a mantenere una gestione efficiente e organizzata degli affari dell'associazione.

## Grazie!

Grazie per aver scelto ConcordatoFacile per semplificare la gestione dei contratti di locazione a canone concordato. Spero che questa guida ti abbia fornito una panoramica completa e che tu abbia acquisito una migliore comprensione di come utilizzare efficacemente questa soluzione. Non esitare a contattarmi all'indirizzo email [germ.riccio@gmail.com](mailto:germ.riccio@gmail.com) per qualsiasi dubbio o problema che potresti incontrare lungo il percorso.

Buon lavoro!
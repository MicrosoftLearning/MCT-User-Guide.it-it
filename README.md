# Guida dell'utente di GitHub per MCT

I servizi cloud, ad esempio Microsoft Azure, vengono aggiornati frequentemente, causando sfide per i Microsoft Certified Trainers (MCT) mentre insegnano corsi e passaggi dei lab che non corrispondono più ai servizi cloud. . A causa della frequenza delle modifiche e del fatto che non c’è alcuna notifica quando si verificano modifiche, può essere difficile per il team di sviluppo del corso identificare e regolare rapidamente le modifiche del lab.

Per risolvere questi problemi, si usa GitHub per pubblicare i passaggi del lab e gli script del lab per corsi che coprono servizi cloud come Azure. L'uso di GitHub consente agli autori e ai MCT del corso di mantenere aggiornato il contenuto del lab con le modifiche apportate al servizio cloud. L'uso di GitHub consente ai MCT di fornire commenti e suggerimenti per le modifiche al lab e quindi gli autori del corso possono aggiornare tempestivamente i passaggi e gli script del lab.

Quando ci si prepara a insegnare questi corsi, è necessario assicurarsi di usare i passaggi e gli script più recenti del lab scaricando i file appropriati da GitHub.

Questa guida utente è destinata a MCT che non hanno esperienza con GitHub. Fornisce i passaggi per la connessione a GitHub, il download e la stampa dei materiali dei corsi, l'aggiornamento degli script usati dagli studenti nei lab e la spiegazione di come è possibile garantire che il contenuto di un corso rimanga aggiornato.

> **Nota**: Il supporto di Microsoft Learning per l'accesso ai file in GitHub e il supporto per l'esplorazione del sito GitHub è riservato esclusivamente ai MCT che insegnano questo corso.

GitHub non deve essere usato per discutere il contenuto tecnico del corso o come prepararsi per il corso o i suoi lab. È specifico per risolvere le modifiche nei lab.

 
> **Nota**: Per fare riferimento a commenti generali sul corso e sulle demo o su come prepararsi per il corso, usare i forum MCT.

## Sezioni

- [Terminologia di GitHub](https://microsoftlearning.github.io/MCT-User-Guide/terminology/)

- [Ricezione di notifiche di aggiornamento e collaborazione su progetti](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/)

- Suggerire modifiche o inviare un problema alle istruzioni del lab

## Terminologia di GitHub

GitHub introduce la terminologia che potrebbe essere nuova per l'utente. L'elenco seguente include termini e concetti usati in questo documento. Per un elenco completo dei termini di GitHub, vedere tuttavia il [glossario di GitHub](https://docs.github.com/en/get-started/quickstart/github-glossary).

| Termine| Spiegazione |
| - | - |
| Git e GitHub| Git è un programma open source, change-tracking e GitHub è un sito/soluzione basato su Git. Esistono altri siti Web e soluzioni che usano Git come back-end. È consigliabile usare GitHub principalmente per i progetti di sviluppo open source (pubblico) ed è gratuito per tali progetti. Tuttavia, se si vuole usare GitHub per i progetti privati e non open source, è necessario iscriversi per ottenere una versione a pagamento. |
| Archivio o repository| Ogni progetto in GitHub si trova in un repository o archivio. Un repository contiene tutti i file per un progetto, inclusa la documentazione e supporta la cronologia delle revisioni. Una repository può essere pubblico o privato. È possibile avere una copia locale di esso sul disco rigido del computer oppure è possibile usarlo all'interno di GitHub. |
| Markdown| Si tratta di un formato di file di testo che è possibile usare per la creazione della documentazione. È basato su testo e molto semplice da aggiornare, caratteristiche che semplificano l'uso durante la collaborazione. GitHub lo esegue quindi come HTML. |
| GitHub flavored markdown (GFM)| Esistono molte varianti, o versioni, del formato di file Markdown. La versione di GitHub, comunemente nota come GFM, è una delle varianti più comuni di Markdown. Per altre informazioni su GFM e su come usare il formato di markup per i documenti GFM, vedere "Introduzione alla scrittura e alla formattazione in GitHub" all'indirizzo https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/. |
| Fork| Si tratta di una copia di un altro repository che risiede nell'account GitHub, rispetto a un ramo che risiede nel repository originale. Vedere "Branch" direttamente di seguito. |
| Filiale| Si tratta di una copia di un repository che si trova nello stesso repository dell'originale. È possibile unire un ramo con l'originale. |
| Recupera| Si tratta del processo di recupero di una copia delle modifiche più recenti da un repository online. Tuttavia, un recupero non unisce le modifiche. |
| Pull| Questo è il processo di recupero delle modifiche più recenti da un repository online e della loro unione con le modifiche locali. |
| Unire| Questo è il processo di recupero delle modifiche da un ramo e dell'applicazione a un altro. Ciò include il recupero delle modifiche da un repository online e l'applicazione di tali modifiche alla versione locale del repository. |
| Richiesta pull| Si tratta di un set di modifiche proposte a un repository inviato da un utente e i proprietari o i collaboratori di un repository possono quindi accettare o rifiutare la richiesta pull. |
| Push| Questo è il processo di invio o sottomissione delle modifiche locali al repository online. |
| Collaboratore| Si tratta di un utente GitHub che dispone delle autorizzazioni per aggiungere, eliminare o modificare il contenuto di un repository. |

## Ricezione di notifiche di aggiornamento, suggerimento di modifiche e collaborazione su progetti

È possibile configurare l'esperienza GitHub in modo da ricevere notifiche quando vengono effettuati aggiornamenti a un repository GitHub. Esistono diversi modi in cui è possibile iscriversi per le notifiche e molti di essi sono correlati ai molti modi in cui è possibile collaborare a un progetto. Per ricevere notifiche, è possibile eseguire le azioni seguenti.

| Azione| Descrizione |
| - | - |
| [Controllare i repository](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/watching/)| Quando si osserva un repository, GitHub sottoscrive automaticamente le notifiche per eventuali nuove richieste pull o problemi creati per tale repository specifico. È possibile controllare automaticamente qualsiasi repository creato o per il quale si è collaboratori. |
| [Richiesta pull](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Quando si crea una richiesta pull e si propone che i proprietari di un repository accettino una modifica apportata, si sottoscrive automaticamente per ricevere notifiche per la discussione correlata sulla richiesta pull. Per creare una richiesta pull, è prima necessario creare un ramo. |
| [Commenti](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Quando si apportano commenti sulla richiesta pull di un'altra persona, GitHub sottoscrive automaticamente il forum relativo a tale commento oppure è possibile iscriversi manualmente al forum. |
| [Problemi](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Un problema è un suggerimento, una domanda o una richiesta relativa a un repository. Ogni problema ha una propria discussione ed è possibile sottoscrivere i problemi oppure GitHub sottoscrive automaticamente i problemi creati. |
| [Menzioni](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/mention/)| Quando un altro utente menziona l'utente in una conversazione, usando il nome utente di GitHub ([@username](https://github.com/username)), GitHub sottoscrive automaticamente la discussione. |

> **Nota**: È possibile modificare come e quando si ricevono le notifiche ed è anche possibile annullare la sottoscrizione a una qualsiasi o a tutte le discussioni.

## Inviare problemi o suggerire modifiche alle istruzioni del lab

Se si ha un suggerimento o si verifica un errore in un lab, è possibile inviare una richiesta pull e registrare un problema. Se si conosce già la correzione per l'errore, è consigliabile inviare una richiesta pull; in caso contrario, inviare un problema.

| Azione| Descrizione |
| - | - |
| [Richiesta pull](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Quando si crea una richiesta pull e si propone che i proprietari di un repository accettino una modifica apportata, si sottoscrive automaticamente per ricevere notifiche per la discussione correlata sulla richiesta pull. Per creare una richiesta pull, è prima necessario creare un ramo. |
| [Commenti](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Quando si apportano commenti sulla richiesta pull di un'altra persona, GitHub sottoscrive automaticamente il forum relativo a tale commento oppure è possibile iscriversi manualmente al forum. |
| [Problemi](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Un problema è un suggerimento, una domanda o una richiesta relativa a un repository. Ogni questione ha una propria discussione. È possibile sottoscrivere i problemi oppure GitHub sottoscrive automaticamente i problemi creati. |

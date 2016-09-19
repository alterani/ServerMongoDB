# ServerMongoDB
Creazione installazione e configurazione di un server mongoDB.
Esempi Pratici di creazione database nosql.

#Installazione mongodb su MAC OS
## Installazione usando package manager brew

<p> Per lanciare l'installazione: </p>
<CODE> brew install mongodb </CODE>

<p>Dopo aver installato Mongo bisogna creare la cartella /data/db per i dati (se si vuole creare la cartella dati in un percorso diverso bisogna impostare la proprietà dbpath quando si lancia Mongo)</p>
<CODE>mkdir -p /data/db</CODE>

Dopo aver creato la cartella settare i permessi per l'utente che utilizzerà il servizio mongod.

<p>per lanciare il servizio mongodb digitare</p>

<CODE>mongod</CODE>

<p>per lanciare il servizio in un path differente da quello di default</p>

<CODE>mongod --dbpath "percorso" </CODE>

<p>Dopo aver lanciato il servizio mondod possiamo utilizzare la shell. Digitare:</p>

<CODE>mongo</CODE>

<p> A questo link è possibile trovare le istruzioni https://docs.mongodb.com/manual/reference/mongo-shell/</p>

#Comandi SHELL

Per posizionarsi sul database:
<CODE>Use nomedatabase</CODE>

Per visualizzare i database presenti digitare:
<CODE>show databases</CODE>

Per visualizzare tutte le collections digitare:
<CODE>show collections</CODE>


Per visualizzare tutti i documenti(record) di una collection(tabella) digitare:
<CODE>db.nomecollection.find()</CODE>

Per conoscere tutte le opzioni delle query cercare esempi su google.








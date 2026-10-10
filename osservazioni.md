# Osservazioni — Esercitazione 0

Gruppo:

Componenti (Giacomo Marino, The-Voode; Christian Goxhaj, ):

URL del repository condiviso: https://github.com/The-Voode/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2: 

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: printf("\n");

Comando di esecuzione e risultato osservato: ./hello
Viene stampato Hello, computational physics sul terminale.

Che cosa ho capito su sorgente ed eseguibile: la sorgente è il file su cui scrivo il codice, mentre l'eseguibile è il file che ho dopo aver compilato e che viene eseguito.

Output richiesto e comportamento del programma prima della modifica: l'output era una stampa da eseguire su terminale; prima della modifica non poteva stampare nulla.

Esito dopo la modifica e spiegazione della correzione: è stato aggiunto il comando printf che ha permesso la stampa del testo richiesto.

La differenza tra hello.c ed hello è che hello.c è il codice scritto in c che va eseguito dal programma.
Ricompilando considero solo l'ultima versione del file.
Riconosco quello che stampa dai messaggi del terminale perché è quello che mi aspetto dal printf.
Se aggiungo > output.txt stampo in un altro file di testo anziché sul terminale.

## Step 1 — Git

Quali file ho incluso nel commit e perché: hello.c e osservazioni.md, avendoli modificati.

Come ho verificato che la versione provata sia presente su GitHub: perché ci sto scrivendo ora ed è modificata.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: perché resto nella stessa repository.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: ciao 12 3.5, mi ha restituito ciao 12 3.500000

Che cosa posso concludere: vegono presi in imput delle stringhe di caratteri e inserite nell'array, poi convertite in un intero e un reale.
Scrivendo 1.25e5 mi calcola il numero reale come elevato alla 5.
Se l'input non è quello previsto, il programma dà 0, poiché non riesce a convertire nulla.
Il risultato mi restituisce ciò che scrivo, usando 6 cirfre decimali per il numero reale.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: i risultati di echo $? erano entrambi 0.
Nel file txt viene rediretto l'output riuscito del programma.

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: 0 12 3.500000

Come un controllo automatico può riconoscere un errore: con un if seguito da un return diverso da 0, che mi dà errore se ci sono problemi nel codice o nell'input. 

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: serve ricompilare quando modifico il codice, mentre gli argomenti li posso decidere prima dell'esecuzione.

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step: controllo la cronologia di git per vedere le modifiche.

Come ho verificato che la versione finale sia presente su GitHub: controllo dal web se il codice è aggiornato all'ultima versione.

Questa estensione rimpiazza il grafema Schwa (ə) con il plurale maschile generico, quando trovato in una pagina web.

## PERCHÈ?
La schwa è una soluzione scomoda ad un problema di cui si parla da decenni ma che non ha mai ricevuto una vera e propria soluzione, forse perché non ce n’è bisogno.
L'adottare un nuovo simbolo crea più problemi di quanti se ne riescano a risolvere. Alcuni dei motivi sono:
1. COMODITÀ
    - Non è facile da trovare sulla tastiera (esistono dei TUTORIAL su come si possa impostare una scorciatoia da tastiera per scrivere lo schwa su Word, https://www.paroleinlinea.com/strumenti/applicazioni/4-modi-per-scrivere-lo-schwa-su-word/);
    - Non tutti sono in grado di impostare scorciatoie da tastiera a causa delle poche competenze informatiche
    - Non tutti i PC sono in possesso di un NUMPAD, necessario per effettuare la scorciatoia numerica predefinita (ALT + 601)
    - La scorciatoia numerica con NUMPAD è disponibile solo su Windows. Sistemi come MacOS o Linux devono attrezzarsi diversamente
    - Scrivere a mano uno schwa può risultare in una involontaria "a" minuscola a causa della sua composizione
2. LEGGIBILITÀ
    - Da lontano, lo schwa sembra una "a" minuscola
    - Ad una rapida lettura può sembrare una "e" minuscola
    - Chi non si è mai imbattuto in un testo con al suo interno lo schwa potrebbe pensare in un errore di battitura
3. PRATICITÀ
    - Lo schwa è un fonema a metà strada tra una "a" e una "e". I sintetizzatori vocali, come ad esempio quelli utilizzati da persone ipovedenti o adolescenti con disturbo dell'apprendimento (DSA), potrebbero rendere incomprensibili parole con al suo interno la lettera schwa o, nei casi più particolari, la parola con all'interno un carattere non riconosciuto potrebbe non essere letta, rendendo insensata l'intera frase
    - I traduttori automatici meno evoluti come Deepl o Google Translate potrebbero fraintendere l'ambiguità linguistica della schwa e tradurre in modo errato le frasi riportate nel testo originale
    - Le persone che studiano la lingua italiana che vengono a conoscenza della caratteristica grammaticale del genere potrebbero trovare difficoltà durante lo studio della lingua, poiché verrebbe prima insegnata una componente pilastro della lingua e poi tutte le eccezioni dovute all'uso della schwa sui social/articoli
4. SCELTA
    - L'idea di essere contrario all'uso di un simbolo grammaticale che sconvolge le parole scritte e lette su un testo, in relazione a quanto studiato e appreso fin dall'infanzia, è totalmente soggettiva e mi riservo il diritto di poter scegliere se adottarle o meno, almeno per quanto concerne ciò che IO leggo. Se qualcun altro o qualcun'altra riterrà opportuno adottare queste regole, sarà liberissimo/a di farlo senza alcuna critica o impedimento.
5. GLI ESPERTI DICONO ALTRIMENTI
    - Gli esperti della lingua italiana dell'Accademia della Crusca si sono già espressi in merito all'uso di questo simbolo all'interno della costruzione delle frasi, anche se alcuni individui ancora tendono a non seguire le regole ma il loro cervello. Potete liberamente approfondire la questione qui:
        - [Repubblica](https://www.repubblica.it/cultura/2021/09/24/news/l_accademia_della_crusca_interviene_su_schwa_e_asterisco-319271624/)
        - [Accademia della Crusca](https://accademiadellacrusca.it/it/consulenza/un-asterisco-sul-genere/4018#:~:text=...-,allo%20schwa,-In%20alternativa%20all%E2%80%99asterisco)

## INSTALLAZIONE
1. Scaricare la repository come ZIP sul proprio PC
2. Estrarre la cartella dovunque desiderato
3. Aprire Chrome o Edge
4. Aprire l'indirizzo
    - Chrome: `chrome://extensions`
    - Edge: `edge://extensions`
5. Attivare la modalità sviluppatore (in basso a sinistra c'è un flag da attivare)
6. Cliccare su "carica decompressa"
7. Selezionare l'interno della cartella dove sono presenti i file dell'estensione

## BUGS E LIMITAZIONI
- [x] ~~Se la schwa è scritta da sola, quindi solo come indicazione della lettera, verrà sostituita dalla lettera "i"~~
- [ ] Al momento l'estensione funziona solo con le forme plurali. Non trattandosi di un algoritmo di *machine learning* ma di un banale trova-e-sostituisci, devo trovare un modo per distinguere la forma singolare da quella plurale
- [ ] L'estensione non può distinguere quando i soggetti della frase sono esplicitamente di sesso femminile. Come sopra, trattandosi di un trova-e-sostituisci e non di un algoritmo di *machine learning*, non è possibile intuire quale scenario si stia riscontrando.

Potete aprire una [issue](https://github.com/frankie-mceyes/NoSchwa/issues) per segnalare bug.

## AGGIORNAMENTI
- FIX: Ora la regex permette di sostituire la parola contenente la lettera schwa **senza** sostituire unicamente la lettera

## TEST
Questa sezione serve per testare l'effettiva installazione dell'estensione.
Di seguito sono riportate alcune frasi. Se notate che tutte le parole **tranne la singola schwa** terminano con il maschile generico, allora l'installazione dell'estensione è andata a buon fine. In caso contrario, dovrete rivedere i passaggi ed eventualmente ripeterli.
<br>
**TEST:**
- Ciao a tutti
- Siamo stati a casa di Lucio
- Io faccio uso della schwa per indicare il generico: ə

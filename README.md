# Arcode

🇮🇹 [Italiano](#italiano) · 🇬🇧 [English](#english)

---

## Italiano

Un arcade per imparare a programmare: ogni **mondo** è un linguaggio di programmazione, ogni mondo ha le sue **cartelle** di livelli e ogni livello è un **file** da superare. Si gioca nel browser con un terminale vero. Interfaccia e lezioni in **italiano e inglese**.

### I mondi

In ordine di difficoltà: **Python** (pronto), HTML e CSS, JavaScript, SQL, TypeScript, Go, Java, C, C++ e Rust (in arrivo).

### Cosa c'è dentro

- **Python vero** (Pyodide, Python 3.13) che gira sul tuo dispositivo: stessi errori e stessa libreria standard del Python installato. `numpy`, `pandas` e `matplotlib` si scaricano da sole quando le importi, con i grafici mostrati nel terminale; per altre librerie scrivi `pip install nome`. Se Pyodide non si carica, l'app usa una versione base (Skulpt).
- **Lab**: lo spazio libero, con editor e terminale insieme. Nella barra laterale: i tuoi file, gli esempi da aprire (indovina il numero, tabelline, calcolatrice, sasso carta forbici), la **Guida** (quando usare l'editor e quando il terminale, più il tutorial guidato di 11 passi), il promemoria della sintassi e le librerie. Con "Solo terminale" il terminale va a tutta altezza.
- **Banco di lavoro**: editor grande e terminale come striscia in basso, con una maniglia da trascinare per cambiare le altezze; su computer restano sempre visibili mentre leggi la spiegazione.
- **Editor con colori della sintassi**, numeri di riga, rientro automatico dopo i due punti, Tab e Maiusc+Tab per spostare blocchi di righe.
- **Terminale interattivo**: scrivi Python dopo `>>>` e premi Invio, come nel vero interprete. Dopo aver eseguito un programma, le sue variabili restano disponibili nel terminale. Frecce su/giù per i comandi precedenti, Ctrl+C per fermare, Ctrl+L per pulire.
- **Lezioni** su: `print`, commenti, leggere gli errori, variabili, numeri, `//` e `%`, f-string, tipi, `input`, booleani, `if/elif/else`, `and/or/not`, `for` e `range`, contatori, liste e indici, `while` e `break`, stringhe e metodi, funzioni, parametri, `return`, dizionari, `try/except`, moduli `math` e `random`, list comprehension, classi e oggetti, più due bonus su `numpy` e `matplotlib`. Ogni lezione spiega una o due idee e le fa usare subito; niente viene usato prima di essere spiegato.
- **Esempi eseguibili** in ogni lezione con il pulsante ▶ Prova.
- **Correzione automatica** degli esercizi, con verifiche nascoste su altri valori e altre risposte a `input()`, così le risposte scritte "a mano" non passano; nei giochi con numeri casuali le verifiche truccano i dadi. Quando manca qualcosa, il livello lo dice a parole.
- **Errori in stile Python** (traceback con riga e codice) con una spiegazione in italiano, e la riga sbagliata evidenziata nell'editor.
- **Barra dei simboli** sul telefono per scrivere `( ) : " [ ] { } =` senza cercarli sulla tastiera.
- Tema chiaro/scuro, dimensione del testo regolabile.

### Il percorso a livelli

- **Schermata d'apertura**: all'avvio le mascotte inseguono un bug, se lo litigano in una nuvola di polvere e lo risolvono, poi si mettono in posa. Si salta con un tocco, e dalle impostazioni si può spegnere. Chi non ha fatto l'accesso trova subito **Accedi**, e sotto **Crea account** o **Entra come ospite**; chi è già dentro riceve un saluto ed entra da solo.
- **Esplora file** del mondo Python: 8 cartelle numerate (`00_inizio`, `01_basi`, …) con 79 file `.py` da aprire in ordine. Ogni cartella ha il suo `README.md` con la mascotte, e l'icona di ogni file dice che tipo di livello è.
- **Lo stesso ritmo in ogni cartella**: lezioni brevi, poi un livello **Prevedi** (leggi il codice e indovina cosa stampa: arriva sempre dopo che le cose nuove sono state spiegate e provate), un **Ripasso** con più domande che mescola il nuovo e il vecchio, un livello **Costruisci** e il **boss**. Nei livelli Costruisci fai crescere "Indovina il numero", sempre lo stesso gioco: ogni parte riparte dal codice che hai scritto tu nella parte prima e aggiunge una cosa sola (gli indizi, i tentativi in un ciclo, le funzioni, i livelli con il numero casuale, il record con le classi).
- **Tipi di esercizio**: scrivi il programma, completa i `___` (un tocco seleziona lo spazio vuoto), rimetti in ordine le righe e scegli i rientri con le frecce, prevedi l'output, tocca la riga che ferma Python. Riordinare e toccare funzionano bene anche sul telefono.
- **la cartella 00_inizio**: il primo programma con `print`, prevedere cosa fa Python, le regole di scrittura, i commenti, leggere un errore, un ripasso e il biglietto da visita.
- **Un boss per cartella**: un programma pieno di bug da correggere, guidato da Papera, la paperella del debug, che risponde con domande invece che con soluzioni.
- **Mascotte in pixel art** che guidano le cartelle e reagiscono al tuo codice: Cursy, Bit, Graffa, Pip, Floppy e Papera.
- **La quest** di ogni livello sta in un riquadro sopra l'editor, separata dalla spiegazione.
- **Aiuti a gradini**: il primo suggerimento è una domanda che ti indirizza, il secondo è il piano a parole; la soluzione si sblocca solo dopo.
- **Stelle**: ★★★ senza aiuti, ★★ con i suggerimenti, ★ con la soluzione; nei quiz contano gli errori. Puoi rigiocare un livello per prenderle tutte.
- **Byte e gradi**: ogni livello vale dei byte; con i byte sali di grado, da Principiante a Maestro del codice: un grado a metà della prima cartella, poi uno per cartella, quando ne batti il boss.
- **Suoni morbidi** quando superi un livello, disattivabili.
- **Account**: scegli un nome utente e una password; i progressi di ogni account sono separati e restano sul dispositivo. Puoi usare l'app anche come ospite, avere più account sullo stesso dispositivo, cambiare la password ed eliminare l'account. Alla creazione ricevi un **codice di recupero** (mostrato una sola volta) per rientrare se dimentichi la password. Password e codice non vengono mai salvati in chiaro (PBKDF2).
- **Salvataggio**: dalle impostazioni puoi salvare i progressi in un file o in un codice da copiare, e ripristinarli anche su un altro dispositivo; il ripristino unisce i progressi invece di sovrascriverli.
- **Pronta per la sincronizzazione**: il codice ha già il punto di aggancio per un server gratuito (oggetto `REMOTE` e unione dei progressi `mergeStates`), da collegare in seguito.
- **App installabile**: aggiungila alla schermata Home; dopo la prima apertura funziona anche offline.
- **Aggiornamenti**: nelle impostazioni vedi la data della versione che stai usando e puoi cercare gli aggiornamenti. Quando ne esce una nuova compare anche un avviso in basso; con **Aggiorna ora** l'app si ricarica già aggiornata e i progressi restano.

### Come usarla

È un solo file: apri `index.html` nel browser. Serve la connessione a internet, perché l'interprete Python viene scaricato all'apertura.

Per metterla online gratis: su GitHub vai in **Settings → Pages**, scegli il branch `main` e la cartella `/ (root)`.

---

## English

An arcade for learning to code: every **world** is a programming language, every world has its own **folders** of levels and every level is a **file** to beat. It runs in the browser with a real terminal. Interface and lessons in **English and Italian**.

### The worlds

Sorted by difficulty: **Python** (ready), HTML and CSS, JavaScript, SQL, TypeScript, Go, Java, C, C++ and Rust (coming soon).

### What's inside

- **Real Python** (Pyodide, Python 3.13) running on your device: same errors and standard library as installed Python. `numpy`, `pandas` and `matplotlib` download by themselves when you import them, with charts shown in the terminal; for other libraries type `pip install name`. If Pyodide can't load, the app falls back to a basic version (Skulpt).
- **Lab**: the free space, with editor and terminal together. In the side bar: your files, examples to open (guess the number, times tables, calculator, rock paper scissors), the **Guide** (when to use the editor and when the terminal, plus the 11-step guided tutorial), the syntax cheat sheet and the libraries. "Terminal only" makes the terminal full height.
- **Workbench**: a big editor and the terminal as a strip at the bottom, with a handle to drag to change their heights; on computers they stay in view while you read the explanation.
- **Editor with syntax colors**, line numbers, auto-indent after a colon, Tab and Shift+Tab to move blocks of lines.
- **Interactive terminal**: type Python after `>>>` and press Enter, like the real interpreter. After you run a program, its variables stay available in the terminal. Up/down arrows for previous commands, Ctrl+C to stop, Ctrl+L to clear.
- **Lessons** on: `print`, comments, reading errors, variables, numbers, `//` and `%`, f-strings, types, `input`, booleans, `if/elif/else`, `and/or/not`, `for` and `range`, counters, lists and indexes, `while` and `break`, strings and methods, functions, parameters, `return`, dictionaries, `try/except`, the `math` and `random` modules, list comprehensions, classes and objects, plus two bonus levels on `numpy` and `matplotlib`. Every lesson explains one or two ideas and puts them to use right away; nothing is used before it's explained.
- **Runnable examples** in every lesson with the ▶ Try it button.
- **Automatic checking** of exercises, with hidden checks on other values and other answers to `input()`, so hard-coded answers don't pass; in games with random numbers the checks load the dice. When something is missing, the level says so in words.
- **Python-style errors** (traceback with line and code) with a plain-language explanation, and the wrong line highlighted in the editor.
- **Symbol bar** on phones to type `( ) : " [ ] { } =` without hunting for them on the keyboard.
- Light/dark theme, adjustable text size.

### The level path

- **Opening screen**: when the app starts, the mascots chase a bug, scuffle over it in a dust cloud and fix it, then pose for a group photo. Tap to skip, or turn it off in Settings. If you're not logged in you get **Log in**, with **Create account** and **Continue as guest** below; if you are, you get a hello and go straight in.
- **File explorer** of the Python world: 8 numbered folders (`00_start`, `01_basics`, …) with 79 `.py` files opened in order. Each folder has its own `README.md` with the mascot, and each file's icon tells what kind of level it is.
- **The same rhythm in every folder**: short lessons, then a **Predict** level (read the code and guess what it prints: it always comes after the new things have been explained and tried), a **Review** with several questions mixing new and old, a **Build** level and the **boss**. In the Build levels you grow "Guess the number", always the same game: each part starts again from the code you wrote in the part before and adds one thing (the hints, the attempts in a loop, functions, levels with a random secret, the record with classes).
- **Kinds of exercise**: write the program, fill in the `___` (one tap selects the blank), put the lines back in order and set the indentation with the arrows, predict the output, tap the line that stops Python. Reordering and tapping work well on phones too.
- **the 00_start folder**: the first program with `print`, predicting what Python does, the writing rules, comments, reading an error, a review and the business card.
- **One boss per folder**: a buggy program to fix, guided by Papera, the debugging duck, who answers with questions instead of solutions.
- **Pixel-art mascots** that guide each folder and react to your code: Cursy, Bit, Graffa, Pip, Floppy and Papera.
- **The quest** of each level sits in its own box above the editor, apart from the explanation.
- **Help in steps**: the first hint is a question that points the way, the second is the plan in words; the solution unlocks only after them.
- **Stars**: ★★★ with no help, ★★ with the hints, ★ with the solution; in quizzes, mistakes count. Replay a level to collect them all.
- **Bytes and ranks**: every level is worth bytes; bytes raise your rank, from Beginner to Code master: one halfway through the first folder, then one per folder, when you beat its boss.
- **Soft sounds** when you pass a level, and you can turn them off.
- **Accounts**: pick a username and a password; each account's progress is kept separate and stays on the device. You can also play as a guest, keep several accounts on one device, change the password and delete the account. When you sign up you get a **recovery code** (shown only once) to get back in if you forget the password. Passwords and codes are never stored in clear text (PBKDF2).
- **Saving**: from Settings you can save progress to a file or a copyable code, and restore it, even on another device; restoring merges progress instead of overwriting it.
- **Ready for sync**: the code already has the hook for a free server (the `REMOTE` object and the `mergeStates` progress merge), to be connected later.
- **Installable app**: add it to your home screen; after the first visit it also works offline.
- **Updates**: Settings show the date of the version you're using and let you check for updates. When a new one is out, a strip at the bottom says so too; **Update now** reloads the app already updated, and your progress stays.

### How to use it

It's a single file: open `index.html` in a browser. You need an internet connection, because the Python interpreter is downloaded when the page opens.

To put it online for free: on GitHub go to **Settings → Pages**, pick the `main` branch and the `/ (root)` folder.

---

Python runs in the browser through [Pyodide](https://pyodide.org) (CPython compiled to WebAssembly), inside a Web Worker so the page stays responsive. When Pyodide can't load, [Skulpt](https://skulpt.org) is used as a fallback: it covers the language basics but not external libraries.

**Online:** https://blfrlrnz.github.io/Coding_gym/

---

Font dei titoli e di tutte le scritte in grassetto (pulsanti, etichette, schede): [Pixelify Sans](https://github.com/eifetx/Pixelify-Sans), SIL Open Font License 1.1 (`fonts/OFL-PixelifySans.txt`). La lettera C è servita da un piccolo font derivato, "Arcode C", con l'apertura più larga per non confonderla con O e 0.
Font for headings and every bold text (buttons, labels, tabs): Pixelify Sans, SIL Open Font License 1.1. The letter C comes from a tiny derived font, "Arcode C", with a wider opening so it isn't mistaken for O and 0.

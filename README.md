# Arcode

🇮🇹 [Italiano](#italiano) · 🇬🇧 [English](#english)

---

## Italiano

Un arcade per imparare a programmare: ogni **mondo** è un linguaggio di programmazione, ogni mondo ha le sue **cartelle** di livelli e ogni livello è un **file** da superare. Si gioca nel browser con un terminale vero. Interfaccia e lezioni in **italiano e inglese**.

### I mondi

In ordine di difficoltà: **Python** (pronto), HTML e CSS, JavaScript, SQL, TypeScript, Go, Java, C, C++ e Rust (in arrivo).

### Cosa c'è dentro

- **Python vero** (Pyodide, Python 3.13) che gira sul tuo dispositivo: stessi errori e stessa libreria standard del Python installato. `numpy`, `pandas` e `matplotlib` si scaricano da sole quando le importi, con i grafici mostrati nel terminale; per altre librerie scrivi `pip install nome`. Se Pyodide non si carica, l'app usa una versione base (Skulpt).
- **Lab**: lo spazio libero, con editor e terminale insieme. Nella barra laterale: i tuoi file, gli esempi da aprire (indovina il numero, tabelline, calcolatrice, sasso carta forbici), il **tutorial guidato** del terminale (11 passi), il promemoria della sintassi e le librerie. Con "Solo terminale" il terminale va a tutta altezza.
- **Editor con colori della sintassi**, numeri di riga, rientro automatico dopo i due punti, Tab e Maiusc+Tab per spostare blocchi di righe.
- **Terminale interattivo**: scrivi Python dopo `>>>` e premi Invio, come nel vero interprete. Dopo aver eseguito un programma, le sue variabili restano disponibili nel terminale. Frecce su/giù per i comandi precedenti, Ctrl+C per fermare, Ctrl+L per pulire.
- **Lezioni** su: `print`, variabili, numeri, f-string, `input`, booleani, `if/elif/else`, `for`, liste, cicli sulle liste, `while`, stringhe, funzioni, parametri, dizionari, `try/except`, moduli `math` e `random`, list comprehension, classi e una sfida finale.
- **Esempi eseguibili** in ogni lezione con il pulsante ▶ Prova.
- **Correzione automatica** degli esercizi, con verifiche extra su altri valori per evitare risposte "a memoria", più suggerimento e soluzione.
- **Errori in stile Python** (traceback con riga e codice) con una spiegazione in italiano, e la riga sbagliata evidenziata nell'editor.
- **Barra dei simboli** sul telefono per scrivere `( ) : " [ ] { } =` senza cercarli sulla tastiera.
- Tema chiaro/scuro, dimensione del testo regolabile, progressi salvati nel browser.

### Il percorso a livelli

- **Esplora file** del mondo Python: 8 cartelle numerate (`00_inizio`, `01_basi`, …) con 34 file `.py` da aprire in ordine. Ogni cartella ha il suo `README.md` con la mascotte.
- **la cartella 00_inizio**: come ragiona Python, regole di scrittura, commenti, leggere un errore, blocchi e rientro.
- **Un boss per cartella**: un programma pieno di bug da correggere, guidato da Papera, la paperella del debug, che risponde con domande invece che con soluzioni.
- **Mascotte in pixel art** che guidano le cartelle e reagiscono al tuo codice: Cursy, Bit, Graffa, Pip, Floppy e Papera.
- **La quest** di ogni livello sta in un riquadro sopra l'editor, separata dalla spiegazione.
- **Stelle**: ★★★ senza aiuti, ★★ con il suggerimento, ★ con la soluzione. Puoi rigiocare un livello per prenderle tutte.
- **Byte e gradi**: ogni livello vale dei byte; con i byte sali di grado, da Principiante a Maestro del codice.
- **Suoni morbidi** quando superi un livello, disattivabili.
- **Salvataggio**: i progressi restano sul dispositivo; dalle impostazioni puoi salvarli in un file o in un codice da copiare, e ripristinarli anche su un altro dispositivo.
- **App installabile**: aggiungila alla schermata Home; dopo la prima apertura funziona anche offline.

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
- **Lab**: the free space, with editor and terminal together. In the side bar: your files, examples to open (guess the number, times tables, calculator, rock paper scissors), the **guided tutorial** of the terminal (11 steps), the syntax cheat sheet and the libraries. "Terminal only" makes the terminal full height.
- **Editor with syntax colors**, line numbers, auto-indent after a colon, Tab and Shift+Tab to move blocks of lines.
- **Interactive terminal**: type Python after `>>>` and press Enter, like the real interpreter. After you run a program, its variables stay available in the terminal. Up/down arrows for previous commands, Ctrl+C to stop, Ctrl+L to clear.
- **Lessons** on: `print`, variables, numbers, f-strings, `input`, booleans, `if/elif/else`, `for`, lists, looping over lists, `while`, strings, functions, parameters, dictionaries, `try/except`, the `math` and `random` modules, list comprehensions, classes and a final challenge.
- **Runnable examples** in every lesson with the ▶ Try it button.
- **Automatic checking** of exercises, with extra checks on other values so answers can't be hard-coded, plus a hint and a solution.
- **Python-style errors** (traceback with line and code) with a plain-language explanation, and the wrong line highlighted in the editor.
- **Symbol bar** on phones to type `( ) : " [ ] { } =` without hunting for them on the keyboard.
- Light/dark theme, adjustable text size, progress saved in the browser.

### The level path

- **File explorer** of the Python world: 8 numbered folders (`00_start`, `01_basics`, …) with 34 `.py` files opened in order. Each folder has its own `README.md` with the mascot.
- **the 00_start folder**: how Python thinks, writing rules, comments, reading an error, blocks and indentation.
- **One boss per folder**: a buggy program to fix, guided by Papera, the debugging duck, who answers with questions instead of solutions.
- **Pixel-art mascots** that guide each folder and react to your code: Cursy, Bit, Graffa, Pip, Floppy and Papera.
- **The quest** of each level sits in its own box above the editor, apart from the explanation.
- **Stars**: ★★★ with no help, ★★ with the hint, ★ with the solution. Replay a level to collect them all.
- **Bytes and ranks**: every level is worth bytes; bytes raise your rank, from Beginner to Code master.
- **Soft sounds** when you pass a level, and you can turn them off.
- **Saving**: progress stays on the device; from Settings you can save it to a file or a copyable code, and restore it, even on another device.
- **Installable app**: add it to your home screen; after the first visit it also works offline.

### How to use it

It's a single file: open `index.html` in a browser. You need an internet connection, because the Python interpreter is downloaded when the page opens.

To put it online for free: on GitHub go to **Settings → Pages**, pick the `main` branch and the `/ (root)` folder.

---

Python runs in the browser through [Pyodide](https://pyodide.org) (CPython compiled to WebAssembly), inside a Web Worker so the page stays responsive. When Pyodide can't load, [Skulpt](https://skulpt.org) is used as a fallback: it covers the language basics but not external libraries.

**Online:** https://blfrlrnz.github.io/Coding_gym/

---

Font dei titoli: [Pixelify Sans](https://github.com/eifetx/Pixelify-Sans), SIL Open Font License 1.1 (`fonts/OFL-PixelifySans.txt`). La lettera C è servita da un piccolo font derivato, "Arcode C", con l'apertura più larga per non confonderla con O e 0.
Headings font: Pixelify Sans, SIL Open Font License 1.1. The letter C comes from a tiny derived font, "Arcode C", with a wider opening so it isn't mistaken for O and 0.

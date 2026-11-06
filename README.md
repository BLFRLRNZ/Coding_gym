# Palestra Python · Python Gym

🇮🇹 [Italiano](#italiano) · 🇬🇧 [English](#english)

---

## Italiano

Un terminale Python che gira direttamente nel browser, con lezioni guidate per imparare a programmare da zero. Interfaccia e lezioni in **italiano e inglese**.

### Cosa c'è dentro

- **Python vero** (Pyodide, Python 3.13) che gira sul tuo dispositivo: stessi errori e stessa libreria standard del Python installato. `numpy`, `pandas` e `matplotlib` si scaricano da sole quando le importi, con i grafici mostrati nel terminale; per altre librerie scrivi `pip install nome`. Se Pyodide non si carica, l'app usa una versione base (Skulpt).
- **Pagina Terminale** a tutta pagina, con un **tutorial guidato** di 11 passi (scrivi `tutorial` o premi ▶ Tutorial).
- **Editor con colori della sintassi**, numeri di riga, rientro automatico dopo i due punti, Tab e Maiusc+Tab per spostare blocchi di righe.
- **Terminale interattivo**: scrivi Python dopo `>>>` e premi Invio, come nel vero interprete. Dopo aver eseguito un programma, le sue variabili restano disponibili nel terminale. Frecce su/giù per i comandi precedenti, Ctrl+C per fermare, Ctrl+L per pulire.
- **22 lezioni** (20 base + 2 bonus su `numpy` e grafici): `print`, variabili, numeri, f-string, `input`, booleani, `if/elif/else`, `for`, liste, cicli sulle liste, `while`, stringhe, funzioni, parametri, dizionari, `try/except`, moduli `math` e `random`, list comprehension, classi e una sfida finale.
- **Esempi eseguibili** in ogni lezione con il pulsante ▶ Prova.
- **Correzione automatica** degli esercizi, con verifiche extra su altri valori per evitare risposte "a memoria", più suggerimento e soluzione.
- **Errori in stile Python** (traceback con riga e codice) con una spiegazione in italiano, e la riga sbagliata evidenziata nell'editor.
- **Modalità Libero** con più programmi salvati, esempi da aprire (indovina il numero, tabelline, calcolatrice, sasso carta forbici) e un promemoria della sintassi.
- **Barra dei simboli** sul telefono per scrivere `( ) : " [ ] { } =` senza cercarli sulla tastiera.
- Tema chiaro/scuro, dimensione del testo regolabile, progressi salvati nel browser.

### Come usarla

È un solo file: apri `index.html` nel browser. Serve la connessione a internet, perché l'interprete Python viene scaricato all'apertura.

Per metterla online gratis: su GitHub vai in **Settings → Pages**, scegli il branch `main` e la cartella `/ (root)`.

---

## English

A Python terminal that runs right in the browser, with guided lessons to learn programming from scratch. Interface and lessons in **English and Italian**.

### What's inside

- **Real Python** (Pyodide, Python 3.13) running on your device: same errors and standard library as installed Python. `numpy`, `pandas` and `matplotlib` download by themselves when you import them, with charts shown in the terminal; for other libraries type `pip install name`. If Pyodide can't load, the app falls back to a basic version (Skulpt).
- **Terminal page** at full size, with an 11-step **guided tutorial** (type `tutorial` or press ▶ Tutorial).
- **Editor with syntax colors**, line numbers, auto-indent after a colon, Tab and Shift+Tab to move blocks of lines.
- **Interactive terminal**: type Python after `>>>` and press Enter, like the real interpreter. After you run a program, its variables stay available in the terminal. Up/down arrows for previous commands, Ctrl+C to stop, Ctrl+L to clear.
- **22 lessons** (20 core + 2 bonus on `numpy` and charts): `print`, variables, numbers, f-strings, `input`, booleans, `if/elif/else`, `for`, lists, looping over lists, `while`, strings, functions, parameters, dictionaries, `try/except`, the `math` and `random` modules, list comprehensions, classes and a final challenge.
- **Runnable examples** in every lesson with the ▶ Try it button.
- **Automatic checking** of exercises, with extra checks on other values so answers can't be hard-coded, plus a hint and a solution.
- **Python-style errors** (traceback with line and code) with a plain-language explanation, and the wrong line highlighted in the editor.
- **Playground** with several saved programs, examples to open (guess the number, times tables, calculator, rock paper scissors) and a syntax cheat sheet.
- **Symbol bar** on phones to type `( ) : " [ ] { } =` without hunting for them on the keyboard.
- Light/dark theme, adjustable text size, progress saved in the browser.

### How to use it

It's a single file: open `index.html` in a browser. You need an internet connection, because the Python interpreter is downloaded when the page opens.

To put it online for free: on GitHub go to **Settings → Pages**, pick the `main` branch and the `/ (root)` folder.

---

Python runs in the browser through [Pyodide](https://pyodide.org) (CPython compiled to WebAssembly), inside a Web Worker so the page stays responsive. When Pyodide can't load, [Skulpt](https://skulpt.org) is used as a fallback: it covers the language basics but not external libraries.

**Online:** https://blfrlrnz.github.io/Coding_gym/

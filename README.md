# Palestra Python

Un terminale Python che gira direttamente nel browser, con lezioni guidate per imparare a programmare da zero.

## Cosa c'è dentro

- **Editor + terminale**: scrivi codice Python, premi **Esegui** (o Ctrl/⌘ + Invio) e vedi l'output vero. Anche `input()` funziona: rispondi direttamente nel terminale.
- **12 lezioni**: `print`, variabili, numeri, f-string, `input`, `if/elif/else`, `for`, liste, `while`, funzioni, dizionari, `try/except`.
- **Correzione automatica** degli esercizi, con suggerimento e soluzione.
- **Errori spiegati in italiano** sotto il messaggio originale di Python.
- **Modalità libera** con un gioco "indovina il numero" da modificare e un promemoria della sintassi.
- **Progressi salvati** nel browser (localStorage).

## Come usarla

È un solo file: apri `index.html` nel browser. Serve la connessione a internet, perché l'interprete Python viene scaricato all'apertura.

Per metterla online gratis: su GitHub vai in **Settings → Pages**, scegli il branch `main` e la cartella `/ (root)`.

## Come funziona

Il codice Python viene tradotto in JavaScript ed eseguito nel browser da [Skulpt](https://skulpt.org). Le basi del linguaggio ci sono tutte; le librerie esterne come `numpy` o `pandas` non sono disponibili.

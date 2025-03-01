# Linee guida per contribuire

Grazie per il tuo interesse nel contribuire a questo progetto! Questo documento fornisce le linee guida per contribuire agli appunti in LaTeX.

## Processo di contribuzione

1. **Fork della repository**
   - Clicca sul pulsante "Fork" in alto a destra della pagina GitHub
   - Questo creerà una copia della repository nel tuo account GitHub

2. **Clone locale**
   ```bash
   git clone git@github.com:giuppycode/unibo-sistemi-operativi-2024.git
   ```

3. **Crea un branch per le tue modifiche**
   ```bash
   git checkout -b nome-modifica
   ```
   Usa un nome descrittivo, ad esempio: `aggiungi-capitolo-3`, `correggi-sezione-2`

4. **Fai le tue modifiche**
   - Modifica i file .tex necessari
   - Assicurati che il documento compili correttamente

5. **Commit delle modifiche**
   ```bash
   git add .
   git commit -m "Descrizione delle modifiche"
   ```

6. **Push e Pull Request**
   ```bash
   git push origin nome-modifica
   ```
   - Vai sulla pagina GitHub della tua fork
   - Clicca su "Pull Request"
   - Seleziona il tuo branch e compila il template della PR

## Linee guida per il LaTeX

### Struttura del documento
- Usa una struttura chiara con sezioni e sottosezioni
- Inserisci le immagini nella cartella `images/`

### Stile del codice
- Cerca di attenerti allo stile usato

## Cosa contribuire

- Correzioni di errori matematici o tipografici
- Miglioramenti alle spiegazioni
- Nuovi esempi o esercizi
- Miglioramenti alla formattazione
- Aggiunta di figure


## Licenza

Ricorda che contribuendo a questo progetto, accetti che il tuo lavoro sia distribuito sotto la stessa licenza MIT del progetto principale.

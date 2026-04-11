# Portfolio personale - Andrea Malo

## Descrizione del progetto
Questo progetto consiste nella realizzazione di un sito portfolio personale sviluppato per presentare in modo chiaro, ordinato e responsive il mio profilo, il mio percorso formativo e le mie competenze.

Il sito è composto da tre pagine principali:
- **Home**: introduzione personale, sezione "Il mio percorso" e panoramica delle skills
- **Curriculum**: profilo, formazione, esperienza, competenze e progetti
- **Contatti**: form di contatto e riferimenti esterni

L’obiettivo del progetto è mostrare le mie competenze di base nello sviluppo front-end, nella strutturazione dei contenuti e nella creazione di un’interfaccia moderna, leggibile e adattabile anche ai dispositivi mobili.

## Tecnologie usate
Per lo sviluppo del progetto sono state utilizzate le seguenti tecnologie:

- **HTML5** per la struttura delle pagine
- **CSS3** per la definizione dello stile
- **SCSS** per organizzare meglio il codice CSS tramite variabili, nesting e struttura più ordinata
- **JavaScript** per la gestione del menu hamburger nella versione mobile
- **Google Fonts** per la tipografia
- **Font Awesome** per l’inserimento di icone nelle sezioni del sito

## Funzionalità principali
Il sito include:
- layout responsive
- menu di navigazione con evidenziazione della pagina attiva tramite `aria-current`
- menu hamburger su mobile
- sezione introduttiva personale
- timeline/sezione descrittiva del percorso
- sezione skills nella home page
- pagina curriculum con informazioni su formazione, esperienza e competenze
- pagina contatti con form
- meta tag descrittivi e Open Graph per una migliore presentazione del sito

## Come eseguire il progetto in locale
Per eseguire il progetto in locale:

1. Scaricare o clonare il repository sul proprio computer
2. Aprire la cartella del progetto in **Visual Studio Code**
3. Verificare che la struttura dei file sia corretta
4. Avviare il progetto in uno di questi modi:
   - aprendo direttamente il file `index.html` nel browser
   - oppure usando l’estensione **Live Server** di Visual Studio Code

Se si vuole modificare il file SCSS e rigenerare il CSS, è possibile compilare `style.scss` in `style.css` tramite Sass.

Esempio comando:

```bash
sass assets/scss/style.scss assets/css/style.css


Struttura del progetto

La struttura principale del progetto è la seguente:

portfolio-html/
│── index.html
│── cv.html
│── contatti.html
│── README.md
│── script.js
│
└── assets/
    ├── css/
    │   └── style.css
    ├── scss/
    │   └── style.scss
    └── img/
        ├── profilo.jpg
        └── favicon.png

Possibili sviluppi futuri

Tra i possibili miglioramenti futuri:

aggiunta di progetti reali più dettagliati
integrazione del form con servizi come EmailJS
miglioramento ulteriore dell’accessibilità
aggiunta di animazioni e microinterazioni
pubblicazione online del portfolio
Autore

Andrea Malo
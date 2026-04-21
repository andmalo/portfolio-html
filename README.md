# Portfolio — Andrea Malo

Portfolio personale realizzato in HTML, CSS e JavaScript vanilla, senza framework esterni.

## Pagine

- **Home** (`index.html`) — presentazione, percorso formativo e skills
- **Curriculum** (`cv.html`) — profilo, formazione, esperienza e progetti
- **Contatti** (`contatti.html`) — form di contatto con validazione e invio email

## Funzionalità

- Dark / Light mode con persistenza via `localStorage`
- Form di contatto con validazione client-side (lunghezza, caratteri non consentiti) e invio tramite [EmailJS](https://www.emailjs.com/)
- Layout responsive mobile-first
- Menu hamburger con chiusura su click esterno o su link

## Tecnologie

- HTML5, CSS3 (custom properties, grid, flexbox, backdrop-filter)
- JavaScript ES6+ vanilla
- [EmailJS](https://www.emailjs.com/) per l'invio email lato client
- [Font Awesome](https://fontawesome.com/) per le icone
- [Google Fonts](https://fonts.google.com/) — Inter

## Struttura

```
portfolio-html/
├── index.html
├── cv.html
├── contatti.html
└── assets/
    ├── css/
    │   └── style.css
    └── img/
        ├── profilo.jpg
        └── favicon.png
```

## Esecuzione in locale

1. Clonare il repository
2. Aprire `index.html` direttamente nel browser oppure tramite l'estensione **Live Server** di VS Code

---

Sviluppato da [Andrea Malo](https://github.com/andmalo)

# Medium Clone

Questo progetto è una **riproduzione fedele della homepage desktop di Medium.com**, realizzata interamente con **HTML**, **CSS**, e **JavaScript**. È stato sviluppato come esercizio pratico per consolidare competenze su **layout responsivo**, **animazioni CSS**, e **manipolazione del DOM**.

## 🎯 Obiettivi del progetto

- Riprodurre la homepage desktop di Medium.com il più fedelmente possibile
- Creare una **navbar dinamica** che cambia colore durante lo scroll (da gialla a bianca)
- Implementare animazioni CSS (fade-in)
- Utilizzare **flexbox**, **positioning**, e **media query** per la gestione responsive
- Aggiungere **effetti DOM avanzati** come l’animazione delle "M" nella sezione hero

## ✅ Funzionalità implementate

- ✅ Layout desktop fedele al sito originale
- ✅ Navbar che cambia colore e stile al superamento della sezione hero
- ✅ Effetto fade-in all’apparizione degli elementi nella pagina
- ✅ Comportamento responsive completo (desktop, tablet, mobile)
- ✅ Animazione delle "M" tramite JavaScript e DOM Manipulation
- ✅ Utilizzo dei font originali di Medium (Spectral, Roboto)
- ✅ Integrazione di SVG, icone, immagini avatar e thumbnail

## 🛠️ Tecnologie utilizzate

- HTML5
- CSS3 (Flexbox, Positioning, Animazioni, Media Queries)
- JavaScript (DOM Manipulation, Eventi, setAttribute)
- Google Fonts
- SVG Assets

## 📁 Struttura del progetto

├── assets/ # Immagini, icone SVG, avatar e style
├── index.html
└── README.md # Documentazione del progetto

## 📜 Note aggiuntive

> 📂 La cartella `temp/` include bozze e versioni vecchie realizzate in fase di sviluppo.  
> ❗ Questa cartella **non è rilevante per il funzionamento finale** del progetto e viene ignorata tramite `.gitignore`.

## 📱 Responsività

Sono stati rispettati i mockup forniti per:

- ✅ Desktop
- ✅ Tablet
- ✅ Mobile

## 🔄 Animazioni ed Eventi

- La navbar cambia aspetto **prima** di uscire dalla sezione gialla (`hero`) sfruttando l'**event scroll** e il controllo dinamico della posizione della sezione
- Le **"M" animate** nella sezione hero sono gestite con JavaScript utilizzando `setAttribute()` e loop su elementi del DOM

## 🔧 Come eseguire il progetto

1. Clona il repository:

   ```bash
   git clone https://github.com/tuo-utente/epicode-benchmark-clone.git
   ```

2. Apri index.html in un browser moderno oppure col Live Server di Visual Studio Code per visualizzare la pagina web.

## 👨‍💻 Autori

- Aniello Casolla - 06/03/2023
  > Progetto realizzato durante esercitazione/clonazione front-end con focus su layout avanzato e animazioni.

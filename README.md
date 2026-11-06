# Atletica Castello: Generatore Post Full Time

Web app single-page per creare in pochi secondi la grafica **post-partita** dell'Atletica Castello, pronta per Instagram, Facebook e WhatsApp.

Niente installazioni, niente backend: basta aprire `index.html` nel browser.

## ✨ Funzionalità

- **Formato quadrato 1:1** a 1080×1080 px, con export in alta qualità 2160×2160 px
- **Categorie preimpostate**, da Prima Squadra a Primi Calci, con tipo di gara associato
- **Risultato e marcatori** modificabili al volo (squadra di casa/ospite, gol, marcatori)
- **Foto di sfondo** caricabile da telefono o PC, con zoom, posizione (X/Y) e sfumatura regolabili
- **Stili del punteggio** selezionabili e **font personalizzabili** (preset o file `.ttf` / `.otf` / `.woff`)
- **Logo societario** sostituibile; se `logo_castello.png` non viene trovato, usa un SVG di fallback integrato
- **Download PNG** oppure **salvataggio/condivisione diretta** dal telefono

## 📁 Struttura

```
.
├── index.html          # L'applicazione (HTML + CSS + JS in un unico file)
└── logo_castello.png   # Logo della società, caricato di default
```

## 🚀 Utilizzo

1. Apri `index.html` nel browser, oppure usa la versione online (vedi sotto).
2. Scegli la categoria e inserisci squadre, risultato e marcatori.
3. Carica la foto della partita e regola inquadratura e sfumatura.
4. Scarica la grafica o condividila direttamente.

### Pubblicazione con GitHub Pages

1. Vai su **Settings → Pages**
2. Come sorgente scegli il branch `main` e la cartella `/ (root)`
3. Dopo qualche istante l'app sarà online su `https://<tuo-utente>.github.io/<nome-repo>/`

> 💡 Servire l'app via GitHub Pages (o un piccolo server locale) è preferibile rispetto all'apertura diretta del file: il logo viene caricato correttamente e l'export PNG funziona senza restrizioni del browser.

## 🛠️ Tecnologie

- HTML5 Canvas per il rendering della grafica
- [Tailwind CSS](https://tailwindcss.com/) (via CDN) per l'interfaccia
- Google Fonts (Inter, Barlow Condensed, Roboto Condensed e altri)
- JavaScript vanilla, nessuna dipendenza da installare

## 📝 Note

- Le foto caricate vengono elaborate **solo nel browser**: nessun file viene inviato a server esterni.
- Serve connessione internet per caricare Tailwind e i font da CDN.

## 📄 Licenza

Progetto ad uso interno dell'Atletica Castello. Il logo e il marchio societario restano di proprietà della società.

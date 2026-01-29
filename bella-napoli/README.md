# Bella Napoli - Landing Page Ristorante

Un sito web moderno e professionale per un ristorante italiano, con design responsive e animazioni fluide.

## 🎨 Features

- **Design Moderno e Accattivante**: Layout professionale con gradiente colori caldi
- **Completamente Responsive**: Funziona perfettamente su desktop, tablet e mobile
- **Animazioni Smooth**: Transizioni fluide e effetti hover
- **SEO-Ready**: Struttura HTML ottimizzata per i motori di ricerca
- **Performance Ottimizzate**: Codice pulito e leggero
- **Form di Prenotazione**: Sistema di prenotazione tavoli funzionale

## 📋 Sezioni

1. **Navigation Bar**: Menu di navigazione fisso con logo
2. **Hero Section**: Sezione principale con call-to-action
3. **Features**: Caratteristiche principali del ristorante
4. **Menu**: Showcase dei piatti principali con prezzi
5. **About**: Storia e valori del ristorante
6. **Gallery**: Galleria fotografica
7. **Contact**: Form di prenotazione e informazioni contatto
8. **Footer**: Link e informazioni aggiuntive

## 🚀 Come mettere online su GitHub Pages

### 1. Crea un nuovo repository su GitHub
- Vai su github.com
- Clicca su "New repository"
- Nome: `bella-napoli` (o qualsiasi nome tu preferisca)
- Lascia pubblico
- NON aggiungere README, .gitignore o licenza
- Clicca "Create repository"

### 2. Carica i file
Hai due opzioni:

#### Opzione A - Drag & Drop (più semplice)
1. Apri il repository appena creato
2. Clicca su "uploading an existing file"
3. Trascina tutti i file (index.html, style.css, script.js)
4. Scrivi un messaggio (es: "Initial commit")
5. Clicca "Commit changes"

#### Opzione B - Da terminale
```bash
# Naviga nella cartella dove hai salvato i file
cd bella-napoli

# Inizializza git
git init

# Aggiungi i file
git add .

# Commit
git commit -m "Initial commit"

# Collega al tuo repository (sostituisci USERNAME con il tuo username GitHub)
git remote add origin https://github.com/NexoWebDeveloper/bella-napoli.git

# Push
git branch -M main
git push -u origin main
```

### 3. Attiva GitHub Pages
1. Nel repository, vai su "Settings"
2. Nella sidebar sinistra, clicca "Pages"
3. Sotto "Source", seleziona "main" branch
4. Clicca "Save"
5. Aspetta 1-2 minuti

Il tuo sito sarà disponibile a:
`https://nexowebdeveloper.github.io/bella-napoli/`

## 🛠️ Personalizzazione

### Colori
Nel file `style.css`, modifica le variabili CSS all'inizio:
```css
:root {
    --primary-color: #d4145a;  /* Colore principale */
    --secondary-color: #fbb03b; /* Colore secondario */
    /* ... altre variabili */
}
```

### Contenuti
Modifica il file `index.html` per cambiare:
- Testi
- Nomi dei piatti
- Prezzi
- Informazioni di contatto

### Immagini
Sostituisci i placeholder colorati con immagini reali:
1. Aggiungi le tue immagini nella cartella
2. Nel file `index.html` o `style.css`, sostituisci i background gradient con:
```css
background: url('nome-immagine.jpg');
background-size: cover;
```

## 📱 Compatibilità

- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 📝 Licenza

Progetto creato da **Nexowebs** per uso portfolio.

---

**Nexowebs** - Web Development Professionale

# Valentin Nau - Mathematik Portfolio

Willkommen zu meinem Portfolio für interaktive mathematische Visualisierungen!

## 🚀 Live Demo

Die Seite ist live auf GitHub Pages: `https://valentinnau.github.io/math-visualizations/`

## 📁 Projektstruktur

```
.
├── index.html                          # Landing Page (Hauptseite)
├── lineare_abbildung_optimized.html   # Lineare Abbildungen Tool
└── README.md                           # Diese Datei
```

## ⚙️ Konfiguration

Die Landing Page (`index.html`) ist vollständig konfigurierbar! Alle Einstellungen findest du im **CONFIG-Objekt** am Ende der Datei.

### 1. Persönliche Informationen ändern

```javascript
personal: {
  name: "Valentin Nau",           // Dein Name
  initials: "VN",                 // Initialen für Logo
  tagline: "Mathematik · ...",    // Untertitel
  description: "...",             // Beschreibung
  email: "deine@email.com",       // E-Mail Adresse
  github: "https://github.com/dein-username",
  linkedin: "https://linkedin.com/in/dein-profil"
}
```

### 2. Projekte hinzufügen/bearbeiten

```javascript
projects: [
  {
    title: "Projekt Name",
    description: "Beschreibung des Projekts...",
    icon: "📐",                    // Emoji als Icon
    tags: ["Tag1", "Tag2"],        // Tags für das Projekt
    link: "./datei.html",          // Link zur Datei
    status: "active"               // active, coming-soon, archived
  },
  // Füge weitere Projekte hinzu...
]
```

**Status-Optionen:**
- `active` - Projekt ist fertig und verlinkt
- `coming-soon` - Projekt in Entwicklung (klick-geschützt)
- `archived` - Archiviertes Projekt

### 3. Features anpassen

```javascript
features: [
  {
    icon: "🎨",
    title: "Feature Name",
    description: "Beschreibung..."
  },
  // Füge weitere Features hinzu...
]
```

### 4. Theme einstellen

```javascript
theme: {
  defaultDark: false  // true für Dark Mode als Standard
}
```

## 🌐 GitHub Pages Deployment

### Schritt 1: Repository erstellen

```bash
# Erstelle ein neues Repository auf GitHub
# z.B. "math-visualizations"

# Klone es lokal
git clone https://github.com/valentinnau/math-visualizations.git
cd math-visualizations
```

### Schritt 2: Dateien hinzufügen

```bash
# Kopiere alle HTML-Dateien ins Repository
# - index.html
# - lineare_abbildung_optimized.html

git add .
git commit -m "Initial commit: Portfolio mit Lineare Abbildungen Tool"
git push origin main
```

### Schritt 3: GitHub Pages aktivieren

1. Gehe zu deinem Repository auf GitHub
2. Klicke auf **Settings** (Einstellungen)
3. Scrolle zu **Pages** (unter "Code and automation")
4. Bei **Source** wähle: **Deploy from a branch**
5. Bei **Branch** wähle: **main** und Ordner **/ (root)**
6. Klicke auf **Save**

**Fertig!** Deine Seite ist jetzt live unter:
```
https://valentinnau.github.io/math-visualizations/
```

### Schritt 4: Eigene Domain (optional)

Wenn du eine eigene Domain hast:
1. Erstelle eine Datei `CNAME` im Repository root
2. Füge deine Domain ein: `math.valentin-nau.de`
3. Konfiguriere DNS-Einträge bei deinem Domain-Provider

## 📱 Auf dem iPad öffnen

### Methode 1: Direkt via GitHub Pages URL
Nach dem Deployment einfach die URL im Safari öffnen:
```
https://valentinnau.github.io/math-visualizations/
```

### Methode 2: Als Web-App zum Home Screen hinzufügen
1. Öffne die Seite in Safari
2. Tippe auf das "Teilen"-Icon
3. Wähle "Zum Home-Bildschirm"
4. Die Seite funktioniert jetzt wie eine native App!

### Methode 3: Lokal testen (vor Deployment)
1. Lade die HTML-Dateien herunter
2. Sende sie per E-Mail oder iCloud Drive an dein iPad
3. Öffne sie in Safari

## 🎨 Weitere Ideen für die Landing Page

Hier sind einige Features, die du später hinzufügen kannst:

### 1. Animiertes Header-Banner
- Canvas-Animation mit mathematischen Mustern
- Particle-System mit Formeln
- Interaktive Geometrie im Hintergrund

### 2. Blog/Artikel-Sektion
- Tutorial-Artikel zu den Visualisierungen
- Mathematische Erklärungen
- Behind-the-scenes

### 3. Filter & Suche
- Projekte nach Tags filtern
- Suchfunktion für Inhalte
- Kategorien (Analysis, Algebra, Geometrie, etc.)

### 4. Statistiken & Badges
- "X Visualisierungen erstellt"
- GitHub-Contributions
- Projekt-Downloads

### 5. Timeline
- Chronologische Übersicht aller Projekte
- Meilensteine in der Entwicklung

### 6. Interaktive Demos
- Mini-Vorschauen der Tools direkt auf der Hauptseite
- Hover-Effekte mit Live-Previews

### 7. Kommentare & Feedback
- Integration von Giscus (GitHub Discussions)
- Feedback-Formular

### 8. Newsletter-Anmeldung
- Für Updates bei neuen Visualisierungen

### 9. Mehrsprachigkeit
- Deutsch/Englisch Toggle
- Automatische Spracherkennung

### 10. Analytics Dashboard
- Besucher-Statistiken
- Beliebte Projekte
- Interaktions-Metriken

## 🔧 Technische Details

- **Keine Build-Tools nötig** - Reine HTML/CSS/JS
- **Keine Abhängigkeiten** - Alles läuft im Browser
- **Responsives Design** - Funktioniert auf allen Geräten
- **Performance-optimiert** - Schnelle Ladezeiten
- **Barrierearm** - Semantisches HTML

## 📝 Lizenz

Dieses Projekt steht unter der MIT-Lizenz. Du kannst es frei verwenden und anpassen!

## 🤝 Beitragen

Hast du Ideen für neue Visualisierungen oder Verbesserungen? 
- Öffne ein Issue auf GitHub
- Erstelle einen Pull Request
- Schreibe mir eine E-Mail

---

Viel Erfolg mit deinem Portfolio! 🚀✨

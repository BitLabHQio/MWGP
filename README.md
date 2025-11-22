# WG-Putzplan 🧹

Eine Progressive Web App (PWA) zur Verwaltung des Putzplans in einer Wohngemeinschaft.

## 📋 Beschreibung

WG-Putzplan ist eine einfache, übersichtliche Webanwendung, die den Putzplan einer WG in einer Kalenderansicht darstellt. Die App zeigt vergangene, aktuelle und zukünftige Putzdienste an und bietet eine Checkliste mit allen notwendigen Reinigungsaufgaben.

## ✨ Features

- **Kalenderübersicht**: Zeigt vergangene, aktuelle und zukünftige Putztermine
- **Farbcodierung**: 
  - Grau: Vergangene Termine
  - Türkis: Nächster anstehender Termin
  - Hellblau: Zukünftige Termine
- **Aufgaben-Checkliste**: Übersicht aller Reinigungsaufgaben nach Räumen gegliedert
  - Küche
  - Bad
  - Flur
- **Progressive Web App**: Kann auf dem Homescreen installiert werden (iOS & Android)
- **Responsive Design**: Optimiert für Mobile, Tablet und Desktop

## 🚀 Installation

### Als Webanwendung nutzen

Besuche einfach: [https://bitlabhqio.github.io/MWGP/](https://bitlabhqio.github.io/MWGP/)

### Als App installieren

**iOS:**
1. Öffne die Website in Safari
2. Tippe auf das Teilen-Symbol
3. Wähle "Zum Home-Bildschirm"
4. Bestätige mit "Hinzufügen"

**Android:**
1. Öffne die Website in Chrome
2. Tippe auf die drei Punkte (Menü)
3. Wähle "Zum Startbildschirm hinzufügen"
4. Bestätige mit "Hinzufügen"

## 🛠️ Technologien

- HTML5
- CSS3 (mit CSS-Variablen)
- JavaScript
- PWA (Manifest, Service Worker bereit)
- Font Awesome Icons

## 📱 PWA Features

- **Offline-Fähigkeit**: Die App kann auch ohne Internetverbindung genutzt werden
- **Installierbar**: Kann wie eine native App installiert werden
- **App-Icon**: Eigenes Icon auf dem Homescreen
- **Standalone-Modus**: Läuft im Vollbildmodus ohne Browser-UI

## 🎨 Farbschema

- **Hintergrund**: `#F2EFE7` (Beige)
- **Primary**: `#9ACBD0` (Hellblau)
- **Secondary**: `#48A6A7` (Türkis)
- **Accent**: `#2973B2` (Dunkelblau)
- **Text**: `#333` (Dunkelgrau)

## 📂 Projektstruktur

```
MWGP/
├── index.html          # Hauptdatei
├── manifest.json       # PWA Manifest
├── favicon.ico         # Browser-Icon
├── AppIcon.png         # App-Icon (192x192 & 512x512)
├── css/
│   └── styles.css      # Stylesheet
└── js/
    └── script.js       # JavaScript-Logik
```

## 👥 WG-Mitglieder

- tbd

## 📅 Putzplan-Rotation

Die Putzverantwortung rotiert wöchentlich am Sonntag zwischen den WG-Mitgliedern.

## 🔮 Geplante Features

- [ ] Automatische Rotation durch Django-Backend
- [ ] Hosting auf PythonAnywhere
- [ ] Admin-Interface zur Verwaltung der Mitglieder
- [ ] Benachrichtigungen für anstehende Putzdienste
- [ ] Datenbank zur Speicherung erledigter Aufgaben

## 📄 Lizenz

© 2025 MWGP by Iosif Gogolos

## 🤝 Beitragen

Da dies ein privates WG-Projekt ist, sind externe Beiträge aktuell nicht vorgesehen.

## 📧 Kontakt

Bei Fragen oder Anregungen wende dich an die WG-Mitglieder.

---

Made with ❤️ on GitHub
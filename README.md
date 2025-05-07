# 🌱 Spargelanbau Gaussmann – Website-Projekt

Willkommen zur Projektübersicht für die neue Website des Hofs **Spargelanbau Gaussmann**. Dieses Dokument enthält die wichtigsten Punkte zum geplanten Webauftritt.

---

## 🎯 Projektziele

* 🖌️ Individuelles, modernes Design – weg von WordPress
* ❌ Kein CMS nötig – statische, wartungsarme Seite
* 📱 Responsive für Mobilgeräte und Tablets
* 📅 Integration eines einfachen Saisonkalenders
* 📬 Kontaktformular mit sicherem Mailversand
* 🗘️ Anfahrtskarte via externer Dienste (Google Maps o. ä.)

---

## 🛠️ Technologiestack

* 🧹 **HTML5 + Tailwind CSS** für Struktur & Design
* ⚡ **Vanilla JS oder Alpine.js** für einfache Interaktionen
* 🧪 **Vite** oder **Astro** als optionales Build-Tool
* 📄 Formularversand via **Formspree**, **PHP-Mailer** oder Plesk-Mail
* 🔀 Deployment über **Plesk Git-Repos** oder **FTP**

---

## 🧭 Seitenstruktur

1. 🏡 **Startseite** – Begrüßung, Hofbild, Saisonhinweis
2. 🧑‍🌾 **Über uns** – Hofgeschichte, Philosophie, Team
3. 🌾 **Saisonkalender** – visuell oder tabellarisch, leicht aktualisierbar
4. 📞 **Kontakt** – Formular, Telefonnummer, E-Mail, Karte
5. ⚖️ **Impressum & Datenschutz** – rechtssicherer Footerbereich

---

## 💶 Preis & Leistungsrahmen

**Pauschalpreis:** `800 €`

**Enthalten:**

* Konzeption & Design
* Entwicklung von 4–5 Seiten
* Responsives Layout
* Einbindung des Kontaktformulars & Anfahrtskarte
* Hosting-Setup via Plesk
* Kleine Anpassungen nach Abnahme

**Nicht enthalten:**

* CMS oder E-Commerce-Funktionalität
* Fortlaufender Content-Service oder SEO
* Logo-Entwicklung (optional zubuchbar)

---

## 🚀 Nächste Schritte

1. 🎨 Farb- & Designkonzept abstimmen
2. 🧱 HTML-Grundgerüst mit Tailwind aufsetzen
3. 🧭 Seiteninhalt strukturieren & Inhalte einpflegen
4. ✅ Kontaktformular & Karte einbinden
5. 📦 Bereitstellung via Plesk

---

## 🗂️ Projektstruktur

```text
spargelhof-gaussmann/
├── public/                    # Statische Assets
│   ├── images/                # Bilder (Hof, Spargel, Team, etc.)
│   └── favicon.ico
│
├── src/                       # Entwicklungsquellen
│   ├── assets/                # Fonts, Icons, ggf. JS-Module
│   │   ├── js/
│   │   └── styles/
│   │       └── main.css       # Tailwind-Einstiegspunkt
│   ├── pages/                 # HTML-Seiten
│   │   ├── index.html         # Startseite
│   │   ├── about.html         # Über uns
│   │   ├── kalender.html      # Saisonkalender
│   │   ├── kontakt.html       # Kontaktseite
│   │   └── rechtliches.html   # Impressum & Datenschutz
│   └── components/            # Wiederverwendbare HTML-Fragmente
│       ├── header.html
│       ├── footer.html
│       └── kalender-card.html
│
├── tailwind.config.js         # Tailwind-Konfiguration
├── postcss.config.js          # Für Tailwind/PostCSS
├── vite.config.js             # Optional: wenn Vite verwendet wird
├── package.json               # NPM-Projektdatei
├── .gitignore
└── README.md                  # Projektbeschreibung
```

---

> ✉️ Optional: Logo-Entwurf oder Druckdateien für Flyer/Plakate können zusätzlich angeboten werden.

---

> Erstellt mit ❤️ für individuelle, wartungsarme Weblösungen.

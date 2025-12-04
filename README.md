# 🎤 Sprechbattle Arena

Digitale Sprechtraining-Arena für Integrationskurse (A2-B1)

## ⚡ Schnellstart

1. **Öffne `index.html`** im Browser (oder nutze GitHub Pages)
2. **Namen eingeben** + Level wählen (🔴 Rubin / 🟢 Smaragd / 🟣 Amethyst)
   - ODER: **📥 JSON importieren** aus deinem Punkteverwaltungssystem
3. **Spielmodus wählen** (🎭 Klassisch / 🎁 Mystery Box / ⚡ Schnellfeuer / 🔥 Eskalation)
4. **Level klicken** → System wählt 2 Spieler + Situation
5. **Dialog starten** → Timer läuft → Punkte vergeben

**Tipp:** F11 für Vollbild auf Beamer!

## 🎮 Die 4 Spielmodi

- **🎭 Klassischer Dialog** - Gemeinsam planen, Prüfungsvorbereitung
- **🎁 Mystery Box** - 3 geheime Wörter natürlich einbauen
- **⚡ Schnellfeuer** - Schnelle Reaktionen, hohe Geschwindigkeit
- **🔥 Eskalation** - Probleme lösen, Schwierigkeit steigt

## 🎯 3 Schwierigkeitsstufen

- 🔴 **Rubin** - Einfach (A2): Grundlegende Dialoge
- 🟢 **Smaragd** - Mittel (A2-B1): Komplexere Situationen
- 🟣 **Amethyst** - Schwer (B1): Problemlösung, Kompromisse

## 📁 Dateien

- `index.html` - Hauptanwendung (Arena)
- `ANLEITUNG.html` - Ausführliche Nutzungsanleitung
- `bewertung-redemittel.html` - Bewertungsbögen & Redemittel-Listen
- `situationskarten.html` - Optionale Karten zum Ausdrucken
- `zertifikate.html` - Zertifikat-Vorlagen

## 💡 Empfohlener Einsatz

**Woche 1-2:** 🔴 Rubin + 🎭 Klassisch (Vertrautheit)  
**Woche 3-4:** 🔴🟢 + 🎭🎁 (Abwechslung)  
**Woche 5-6:** Alle Modi + 🟣 Amethyst (Prüfungsvorbereitung)

## 🎓 Features

✅ Roulette-System - wählt zufällig Spieler  
✅ Live-Timer auf Leinwand  
✅ Punktesystem mit Scoreboard  
✅ 4 Teams (Mond, Sonne, Stern, Ozean)  
✅ 3 Levels pro Spieler  
✅ **JSON Import/Export** - Integration mit Punkteverwaltungssystemen  
✅ Komplett offline nutzbar  

## 📥 JSON Import/Export

**Daten importieren:**
1. Button "📥 JSON importieren" im Setup-Screen
2. JSON-Datei auswählen (Format siehe `beispiel-teilnehmer.json`)
3. Namen + Levels werden automatisch geladen

**Daten exportieren:**
1. Button "💾 JSON exportieren"
2. Datei wird heruntergeladen
3. Kann später wieder importiert werden

**JSON-Format:**
```json
{
  "teams": {
    "mond": {
      "participants": [
        {"name": "Ahmed", "level": "rubin", "points": 0}
      ]
    }
  }
}
```

Unterstützte Levels: `rubin`, `smaragd`, `amethyst`  

## 📝 Für Entwickler

Komplett in einer HTML-Datei - kein Build, keine Dependencies!

```bash
# GitHub Pages aktivieren
# Settings → Pages → Source: main branch
# Deine Arena läuft unter: username.github.io/repository
```

## 📄 Lizenz

Erstellt für JIK-AWO 25/26 Integration Course, Kiel

---

**Made with 💜 für Deutschlerner**

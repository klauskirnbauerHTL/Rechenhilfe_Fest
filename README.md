# Rechenhilfe_Fest

Eine einfache lokale Rechenhilfe-Webanwendung für das Festprojekt. Diese Seite enthält eine übersichtliche Benutzeroberfläche zur Anzeige von Getränken und Speisen und dient als Rechenhilfe mit automatischer Berechnung.

## Inhalt

- `index.html`: Die Hauptseite der Anwendung mit dem Rechenhilfe-Interface
- `config.js`: Konfigurationsdatei mit allen Getränken und Speisen (einfach bearbeitbar)


## Nutzung

### Schnellstart - Keine Installation nötig! ⚡

Öffne einfach die `index.html` direkt im Browser - das war's!

```
Doppelklick auf index.html → fertig!
```

## Konfiguration

Die `config.js` enthält alle Artikel und kann einfach bearbeitet werden:

```javascript
const configData = {
  "kategorien": [
    {
      "name": "Getränke",
      "id": "getränke",
      "label": "Getränke",
      "artikel": [
        {"name": "0,25l Almdudler", "preis": 2.00},
        {"name": "0,50l Bier", "preis": 3.50}
      ]
    }
  ]
};
```

**So bearbeitest du Artikel:**
1. Öffne `config.js` in einem Texteditor (Notepad, VS Code, etc.)
2. Füge Artikel hinzu/bearbeite sie
3. Speichern
4. Seite im Browser neuladen (F5)

## Features

- ✅ **Responsive Design**: Funktioniert auf Handy, Tablet und Desktop
- ✅ **Getränke & Speisen**: Zwei nebeneinander Spalten auf breiten Bildschirmen
- ✅ **Automatische Berechnung**: Summen und Gesamtbetrag werden live berechnet
- ✅ **Verlauf**: Alle Bestellungen werden lokal gespeichert
- ✅ **Druckfunktion**: Verlauf als Tabelle drucken
- ✅ **Bearbeitung**: Bestellungen können nachträglich bearbeitet werden
- ✅ **Keine Abhängigkeiten**: Funktioniert ohne Server oder Zusatz-Software

## Tipps

- Die Daten werden im Browser gespeichert (LocalStorage) - funktioniert auch offline
- Zum Drucken: Einfach auf "🖨️ Drucken" im Verlauf klicken
- Auf einen Verlauf-Eintrag klicken zum Bearbeiten
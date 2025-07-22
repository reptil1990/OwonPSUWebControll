# OWON PSU Web Controller

Ein modernes Webinterface zur Steuerung und Überwachung von OWON (und kompatiblen) Labornetzteilen über die Web Serial API (z.B. Chrome/Edge).

## Features
- Verbindung zu OWON Netzteilen via Web Serial API (USB)
- Live-Anzeige von Spannung und Strom
- Setzen von Sollwerten und Limits
- Ausgang ein-/ausschalten
- Not-Aus Funktion
- Logbuch für alle Kommandos und Antworten
- Responsive, modernes UI (auch mobil nutzbar)

## Voraussetzungen
- OWON Netzteil (z.B. SPM, SPE, P4 Serie) oder kompatibles Gerät
- Aktueller Chromium-basierter Browser (Chrome, Edge, Opera, ...)
- Aktivierte Web Serial API (Standard in Chrome/Edge)

## Nutzung
1. **Projekt klonen oder entpacken**
2. `index.html` im Browser öffnen
3. Auf "Mit OWON PSU verbinden" klicken und das Netzteil auswählen
4. Einstellungen und Messwerte wie gewünscht nutzen

## Hinweise
- Die Web Serial API funktioniert **nicht** in Firefox oder Safari.
- Bei Problemen mit Timeouts: USB-Kabel prüfen, Netzteil neu starten, Browser neu laden.
- Die Firmware des Netzteils muss SCPI-kompatibel sein.

## Sicherheit
- Die Not-Aus-Funktion schaltet den Ausgang sofort ab.
- Es werden keine Daten ins Internet übertragen – alles läuft lokal im Browser.

## Lizenz
MIT License

---

**Entwickelt für den schulischen/privaten Gebrauch. Keine Garantie auf Funktion oder Geräteschutz!**

---

Developed with love from reptil1990

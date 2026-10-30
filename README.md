# NetPython 🐍

Ein schneller, moderner Python Online-Compiler und Interpreter direkt im Browser – ganz ohne Backend-Server!

Online erreichbar unter ![https://mickyroth.github.io/NetPython/](https://mickyroth.github.io/NetPython/) 

![Python](https://img.shields.io/badge/Python-3.12%20(Pyodide)-3776AB?logo=python&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-Wasm-654FF0?logo=webassembly&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

NetPython bringt eine vollwertige Python-Umgebung direkt in Ihren Webbrowser. Es läuft vollständig clientseitig über WebAssembly (CPython via Pyodide) und unterstützt standardmäßig auch mathematische und statistische Bibliotheken wie `math`, `random` und `statistics`.

---

## 🚀 Features

- **Vollständiges Python 3 im Browser**: Basiert auf Pyodide (WebAssembly-Portierung des offiziellen CPython).
- **Zwei-Spalten-Layout**:
  - **Links**: Moderner Code-Editor mit Syntax-Highlighting (Dracula-Theme), Zeilennummern und automatischem Klammerabgleich.
  - **Rechts**: Konsole (Terminal) für Standardausgabe (`stdout`), Fehlermeldungen (`stderr`) und Ausführungszeitmessung.
  - **Mitte**: Stufenlos verschiebbarer Splitter / Trennbalken.
- **Wichtige Module sofort einsatzbereit**:
  - `math` (Geometrie, Trigonometrie, Logarithmen etc.)
  - `random` (Zufallszahlen, Ziehungen, Listenmischen etc.)
  - `statistics` (Mittelwert, Median, Modalwert, Standardabweichung, Varianz etc.)
- **Dateiverwaltung**:
  - 📄 **Neu**: Neues Skript erstellen.
  - 📂 **Öffnen**: Lokale `.py`- oder Textdateien vom Computer laden.
  - 💾 **Speichern**: Dateidialog („Speichern unter...“) zum Abspeichern auf der Festplatte.
  - ▶️ **Run**: Sofortige Ausführung des Codes (Kürzel: `Strg` + `Enter` oder `F5`).
- **Interaktives `input()`**: Benutzereingaben werden abgefragt und wie in einem echten Terminal ausgegeben.
- **Beispiele-Menü**: Integrierte Vorlagen für schnelle Tests und Demonstrationen.

---

## 💻 Verwendung

Einfach die Datei `index.html` in einem modernen Webbrowser (Chrome, Edge, Firefox, Brave, Safari) öffnen – keine Installation von Python oder Abhängigkeiten auf dem Rechner erforderlich!

---

## 📝 Lizenz

MIT License

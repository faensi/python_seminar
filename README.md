# Python Seminar Workspace

Dieses Repository enthält Materialien, Notebooks und Ressourcen für ein Python-Seminar. Die Inhalte sind in verschiedene Kapitel und Themenbereiche gegliedert.

---

## Setup environment

Um die Notebooks und Skripte auszuführen, solltest du eine eigene Python-Umgebung mit Miniconda/Conda einrichten. Das sorgt für saubere Abhängigkeiten und vermeidet Versionskonflikte. Am einfachsten geht das mit der bereitgestellten `environment.yml`:

```bash
# Neue Umgebung aus environment.yml erstellen (empfohlen)
conda env create -f environment.yml

# Umgebung aktivieren
conda activate pyseminar
```

**Bestehende Umgebung aktualisieren:**
Falls du bereits eine Umgebung (z.B. `pyseminar`) hast und die Pakete aus der `environment.yml` nachinstallieren möchtest:

```bash
conda env update -n pyseminar -f environment.yml --prune
```

- Mit `--prune` werden nicht mehr benötigte Pakete entfernt.
- Das `-f environment.yml` gibt die Datei an, aus der installiert wird.
- Nach Aktivierung der Umgebung kannst du direkt mit den Notebooks und Skripten arbeiten.

---


## Verzeichnisstruktur

- **1/**: Grundlagen der Python-Programmierung
  - Datentypen, Operatoren, Schleifen, Funktionen, OOP (Klassen & Vererbung)
- **2/**: Numerische Berechnungen und Datenanalyse
  - Einführung und Vertiefung in NumPy und Pandas
- **3/**: Datenvisualisierung mit Matplotlib
  - Von den Grundlagen bis zu fortgeschrittenen Visualisierungstechniken
- **4/**: Wissenschaftliches Rechnen mit SciPy
  - Einführung und fortgeschrittene Methoden
- **5/**: Interaktive Visualisierung mit Plotly
  - Verschiedene Plotly-Notebooks (Alternative zu Matplotlib)
- **data/**: Datensätze und Beispielbilder für Übungen und Analysen
- **EinführungsNotebooks/**: Einführende Notebooks zu Python, Jupyter, NumPy, Pandas, Matplotlib und SciPy
- **extras/**: Zusätzliche Materialien, Debugging-Tipps, Beispielnotebooks, OS-spezifische Notebooks
- **imgs/**: Bilder und Grafiken für Präsentationen und Notebooks

## Wichtige Dateien

- `CheatSheetConda.png`, `CheatSheetPython.pdf`: Spickzettel für Conda und Python
- Diverse CSV- und Bilddateien in `data/` und `imgs/` für Übungen

## Hinweise

- Die Notebooks sind nummeriert und bauen thematisch aufeinander auf.
- Für die Ausführung wird eine Python-Umgebung mit den Paketen NumPy, Pandas, Matplotlib, SciPy und Plotly empfohlen.
- Die Materialien eignen sich für Selbststudium, Unterricht und Workshops.

Viel Erfolg beim Lernen und Anwenden von Python!
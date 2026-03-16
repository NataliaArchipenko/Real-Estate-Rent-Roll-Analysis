# Real Estate Rent Roll Analyse

## Projektübersicht

Dieses Projekt analysiert einen sogenannten **Rent-Roll-Datensatz** aus dem Immobilienbereich.  
Ein Rent Roll enthält detaillierte Informationen über Mietverträge innerhalb eines Immobilienportfolios, einschließlich Flächengrößen, Mietpreisen, Vertragslaufzeiten und Leerständen.

Ziel der Analyse ist es, wichtige Einblicke in die Struktur des Portfolios zu gewinnen und potenzielle Risiken oder Chancen zu identifizieren.

Die Analyse wurde mit **Python und pandas** durchgeführt und umfasst sowohl Datenbereinigung als auch explorative Datenanalyse und Visualisierung.

---

## Analysierte Fragestellungen

Im Rahmen dieses Projekts wurden folgende Fragen untersucht:

- Wie hoch ist die **Auslastung der einzelnen Immobilien**?
- Wie verteilen sich die **Vertragslaufzeiten der Mietverträge**?
- Wie hoch ist die **Miete pro Quadratmeter** innerhalb des Portfolios?
- Gibt es **Unterschiede zwischen verschiedenen Nutzungstypen** (Office, Warehouse, Production, Storage)?
- In welchen Jahren laufen **besonders viele Mietverträge aus**?

---

## Datensatz

Der verwendete Datensatz enthält über **500 Einträge** zu einzelnen Mieteinheiten und umfasst unter anderem folgende Informationen:

- Immobilienobjekt
- Nutzungstyp der Einheit
- Fläche in Quadratmetern
- Mietstatus (vermietet oder leerstehend)
- Mietpreis
- Vertragsbeginn und Vertragsende
- Betriebskosten
- Nettomietertrag (NOI)

---

## Verwendete Technologien

Die Analyse wurde mit folgenden Technologien durchgeführt:

- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Wichtige Analysen

### Vertragslaufzeiten

Die Verteilung der Vertragslaufzeiten zeigt, dass sich die meisten Mietverträge im Bereich von **2 bis 4 Jahren** bewegen.

---

### Auslastungsquote der Immobilien

Die Analyse der belegten und leerstehenden Flächen zeigt, dass die meisten Immobilien eine **Auslastung von über 80 %** aufweisen.

Dennoch existieren in einzelnen Objekten größere Leerstandsflächen, die potenzielles Vermietungspotenzial darstellen.

---

### Mietpreise pro Quadratmeter

Die Mietpreise bewegen sich überwiegend im Bereich zwischen **100 EUR und 180 EUR pro Quadratmeter**.

Zwischen den verschiedenen Nutzungstypen bestehen nur moderate Unterschiede im durchschnittlichen Mietpreisniveau.

---

### Risiko durch auslaufende Mietverträge

Die Analyse der Vertragsenddaten zeigt eine erhöhte Anzahl von Mietvertragsenden zwischen **2023 und 2026**, mit einem Höhepunkt im Jahr **2025**.

Eine solche Konzentration kann ein Risiko darstellen, da mehrere Mietverträge gleichzeitig auslaufen und neu verhandelt werden müssen.

---

## Zentrale Erkenntnisse

- Das Portfolio weist insgesamt eine **relativ hohe Auslastung** auf.
- Die meisten Mietverträge haben eine **mittelfristige Laufzeit**.
- Die Mietpreise im Portfolio sind **relativ homogen verteilt**.
- Zwischen **2023 und 2026** besteht ein erhöhtes Risiko durch auslaufende Mietverträge.

---



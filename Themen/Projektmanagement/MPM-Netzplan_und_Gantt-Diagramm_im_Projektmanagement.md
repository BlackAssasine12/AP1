# MPM-Netzplan und Gantt-Diagramm im Projektmanagement

## Einführung

Das Metra-Potential-Method (MPM) Netzplan und das Gantt-Diagramm sind zwei wichtige Werkzeuge im Projektmanagement, die zur Planung, Überwachung und Steuerung von Projekten verwendet werden. Beide Methoden helfen dabei, die zeitliche Abfolge von Aufgaben zu visualisieren und zu kontrollieren.

## MPM-Netzplan

### Beschreibung
- **Netzplantechnik**: Grafische Darstellung der Aufgaben und ihrer Abhängigkeiten in einem Projekt.
- **Knoten und Kanten**: Aufgaben werden als Knoten dargestellt, Abhängigkeiten als Kanten.
- **Zeitplanung**: Berechnung der frühesten und spätesten Start- und Endzeiten für jede Aufgabe.

### Vorteile
- **Übersichtlichkeit**: Klare Darstellung der Abhängigkeiten und des kritischen Pfades.
- **Flexibilität**: Anpassungsfähig bei Änderungen im Projektplan.
- **Präzision**: Genauere Berechnung der Zeitpläne und Ressourcen.

### Nachteile
- **Komplexität**: Kann bei großen Projekten unübersichtlich werden.
- **Erlernen**: Erfordert Schulung und Erfahrung im Umgang mit der Methode.
- **Aktualisierung**: Regelmäßige Aktualisierung erforderlich, um den aktuellen Stand des Projekts widerzuspiegeln.

## Zentrale Begriffe

- **Vorgang**: Ein Arbeitsschritt im Projekt (z. B. „Wände mauern“).
- **Dauer (d)**: Benötigte Zeitspanne für einen Vorgang (in Tagen, Wochen etc.).

### Zeitliche Kenngrößen
- **FAZ (Frühester Anfangszeitpunkt)**: Früheste mögliche Startzeit eines Vorgangs, ohne Vorgänger zu verletzen.
- **FEZ (Frühester Endzeitpunkt)**: Frühestes mögliches Ende eines Vorgangs.  
  **Formel:** `FEZ = FAZ + Dauer`

- **SAZ (Spätester Anfangszeitpunkt)**: Spätest möglicher Start, ohne das Projektende zu verzögern.  
  **Formel:** `SAZ = SEZ - Dauer`

- **SEZ (Spätester Endzeitpunkt)**: Spätest mögliches Ende, ohne das Projektende zu verzögern.

### Pufferzeiten
- **GP (Gesamtpuffer)**: Zeitspanne, um die ein Vorgang maximal verschoben werden kann, **ohne das Projektende zu verschieben**.  
  **Formel:** `GP = SEZ - FEZ` oder `GP = SAZ - FAZ`

- **FP (Freier Puffer)**: Zeitspanne, um die ein Vorgang verschoben werden kann, **ohne den frühesten Anfang eines Nachfolgers zu verschieben**.  
  **Formel:** `FP = min(FAZ der Nachfolger) - FEZ`

---

## Vorgehensweise zur Berechnung

1. **Vorwärtsrechnung (Bestimmung von FAZ & FEZ)**
   - Startvorgänge beginnen mit `FAZ = 0`.
   - Berechne: `FEZ = FAZ + Dauer`
   - Für Nachfolger: `FAZ = max(FEZ der Vorgänger)`

2. **Rückwärtsrechnung (Bestimmung von SEZ & SAZ)**
   - Endvorgänge: `SEZ = FEZ (des letzten Vorgangs auf kritischem Pfad)`
   - Berechne: `SAZ = SEZ - Dauer`
   - Für Vorgänger: `SEZ = min(SAZ der Nachfolger)`

3. **Pufferzeiten**
   - **Gesamtpuffer**: `GP = SAZ - FAZ`
   - **Freier Puffer**: `FP = min(FAZ Nachfolger) - FEZ`

---

## Kritischer Pfad
- Alle Vorgänge mit **GP = 0** liegen auf dem **kritischen Pfad**.  
- Diese Vorgänge bestimmen die **Mindestprojektdauer**.  
- Verzögerungen dort verzögern das gesamte Projekt.


## Gantt-Diagramm

### Beschreibung
- **Balkendiagramm**: Grafische Darstellung der Aufgaben und ihrer Dauer im Zeitverlauf.
- **Zeitachse**: Horizontale Achse, die die Zeit darstellt.
- **Balken**: Vertikale Balken, die die Dauer der Aufgaben anzeigen.

### Vorteile
- **Einfachheit**: Leicht verständlich und einfach zu erstellen.
- **Visualisierung**: Klare Darstellung der Aufgaben und ihrer Dauer.
- **Kommunikation**: Gut geeignet zur Kommunikation des Projektplans an Stakeholder.

### Nachteile
- **Detailtiefe**: Weniger detailliert als der MPM-Netzplan, insbesondere bei der Darstellung von Abhängigkeiten.
- **Aktualisierung**: Regelmäßige Aktualisierung erforderlich, um den aktuellen Stand des Projekts widerzuspiegeln.
- **Flexibilität**: Weniger flexibel bei Änderungen im Projektplan.

### Berechnung der Schritte
1. **Aufgaben identifizieren**: Alle Aufgaben des Projekts auflisten.
2. **Zeitschätzungen vornehmen**: Die Dauer jeder Aufgabe schätzen.
3. **Start- und Endzeiten festlegen**: Die Start- und Endzeiten für jede Aufgabe festlegen.
4. **Gantt-Diagramm erstellen**: Die Aufgaben und ihre Dauer in einem Balkendiagramm darstellen.
5. **Abhängigkeiten darstellen**: Die Abhängigkeiten zwischen den Aufgaben durch Pfeile oder Verknüpfungen darstellen.
6. **Fortschritt überwachen**: Den Fortschritt der Aufgaben im Diagramm aktualisieren und überwachen.

## Zusammenfassung

Der MPM-Netzplan und das Gantt-Diagramm sind wertvolle Werkzeuge im Projektmanagement, die jeweils ihre eigenen Vorteile und Nachteile haben. Der MPM-Netzplan bietet eine detaillierte und präzise Darstellung der Abhängigkeiten und des kritischen Pfades, während das Gantt-Diagramm eine einfache und verständliche Visualisierung der Aufgaben und ihrer Dauer bietet. Durch die Kombination beider Methoden können Projektmanager ihre Projekte effektiv planen, überwachen und steuern.

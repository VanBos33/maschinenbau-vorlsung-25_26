Hallo, ich bin eine Gabel

# Informatik Grundlagen - Bachelor (Maschinenbau)

Dieses Repository enthält strukturierte Vorlesungsinhalte für das Modul **Informatik Grundlagen** im Maschinenbaustudium (1. und 2. Semester Bachelor).

## Überblick

Dieses Projekt ist als **Dozentenressource** konzipiert und dient der Verwaltung und Bereitstellung von Vorlesungsmaterialien zu Informatik Grundlagen.

### Inhalte

- **Theorie**: Grundkonzepte der Informatik
- **Praxis**: Python Programmierung

Die Vorlesung kombiniert theoretisches Verständnis mit praktischen Programmierübungen.

## Lernziele & Kompetenzen

### Theorie
Studierende verstehen:
- Grundlagen der Informatik und wie Software funktioniert
- Wie Informationen gespeichert und kommuniziert werden
- Systemische Zusammenhänge in der IT

### Praxis (Python Programmierung)
Studierende können:
- Grundsätzlich mittel-komplexe Python-Dateien eigenständig schreiben
- Schnittstellen zu Excel, CSV und Datenbanken anbinden
- Datenbestände auswerten und mathematische Funktionen anwenden
- Ergebnisse grafisch darstellen

### Übergreifende Fähigkeiten
- **Logisches Denken**: Strukturiertes Problem-Solving
- **Komplexitätsmanagement**: "Teile und Herrsche"-Prinzip, Single Responsibility Principle (SRP)
- **Softwaredesign-Grundlagen**: Best Practices verstehen und anwenden

## Projektstruktur

```
newVorlesung/
├── lessons/                      # Alle Vorlesungsinhalte (22 Lektionen)
│   ├── V01-Binaeres-Zahlensystem/
│   │   ├── V01-Binaeres-Zahlensystem_skript.md      # Theorie + Python kombiniert
│   │   ├── V01-Binaeres-Zahlensystem_aufgaben.md    # 3 Theorie + 5 Python Aufgaben
│   │   └── V01-Binaeres-Zahlensystem_loesungen.md   # Ausführliche Lösungen
│   ├── V02-... (in Planung)
│   ├── ...
│   ├── V21-... (Prüfungsvorbereitung Teil 1)
│   └── V22-... (Prüfungsvorbereitung Teil 2)
├── src/                         # Tools und Ressourcen zur Erstellung
├── .github/                     # GitHub-Workflows und Prompts
├── lesson.md                    # Vollständiger Vorlesungsplan (22 Termine)
├── python_topics.md             # Python-Tracking: Welche Konzepte wann eingeführt
└── readme.md                    # Diese Datei
```

## Namenkonvention für Lektionen

Alle Lektionen folgen dem Namensmuster: **`VXX-Thema`**

- **VXX**: Vorlesungsnummer von V01 bis V22
- **Thema**: Beschreibender Titel des Theorie-Hauptthemas
- **Semesterverteilung**:
  - **V01-V11**: Semester 1 (Grundlagen und Kernkonzepte)
  - **V12-V20**: Semester 2 (Vertiefung)
  - **V21-V22**: Semester 2 (Prüfungsvorbereitung und Wiederholung)

**Struktur jeder Lektion:**
- `VXX-Thema_skript.md`: Vollständiges Lernskript (Theorie + Python-Praxis kombiniert)
- `VXX-Thema_aufgaben.md`: Übungsaufgaben (3 Theorie-Aufgaben ⭐→⭐⭐→⭐⭐⭐ + 5 Python-Aufgaben ⭐→⭐⭐⭐⭐)
- `VXX-Thema_loesungen.md`: Ausführliche Lösungen mit Schritt-für-Schritt-Erklärungen

**Beispiele:**
- `V01-Binaeres-Zahlensystem/` → Lektion 1: Binäres Zahlensystem + Python Get Started ✅
- `V11-...` → Lektion 11: Letzte Lektion Semester 1
- `V21-...` → Lektion 21: Prüfungsvorbereitung Teil 1
- `V22-...` → Lektion 22: Prüfungsvorbereitung Teil 2 (Final)

**Umfang & Semesterplan:**
- **22 Lektionen** insgesamt
- **Semester 1**: 11 Lektionen (01-11)
- **Semester 2**: 11 Lektionen (12-22)
  - **Lektionen 12-20**: Neuer Stoff
  - **Lektionen 21-22**: Prüfungsvorbereitung (integrierte Wiederholung und Praxis)
- **Pro Lektion**: 135 Minuten Unterrichtszeit

## Voraussetzungen

### Theoretische Vorkenntnisse
- **Keine speziellen Voraussetzungen** - Der Kurs startet bei den absoluten Grundlagen

### Praktische Voraussetzungen (Python)
- Heterogene Vorkenntnisse: Von Totalanfängern bis zu fortgeschrittenen Anfängern
- Der Kurs ist so ausgestaltet, dass alle Niveaus berücksichtigt werden
- Computer mit installierten Tools erforderlich (siehe Installationsanleitung)

## Struktur einer Lektion

Jede Lektion im `lessons`-Ordner enthält drei Markdown-Dateien:

### 1. Skript (`VXX-Thema_skript.md`)
Das vollständige Lernskript für den Vorlesungstag mit zwei kombinierten Teilen:
- **Teil 1: Theorie** - Informatik-Grundlagen mit fachlichen Konzepten
- **Teil 2: Python-Praxis** - Praktische Programmierung mit Bezug zur Theorie
- Lernziele, NOTE/TIP/WARNING-Blöcke, Code-Beispiele
- Zusammenfassungen und weiterführende Ressourcen

### 2. Aufgaben (`VXX-Thema_aufgaben.md`)
Übungsaufgaben in progressiver Schwierigkeit:
- **Teil A: Theorie-Aufgaben** (3 Aufgaben: ⭐ leicht → ⭐⭐ mittel → ⭐⭐⭐ schwer)
- **Teil B: Python-Aufgaben** (5 Aufgaben: ⭐ leicht → ⭐⭐⭐⭐ schwer/komplex)
- Jede Aufgabe mit Schwierigkeitsgrad, Zeitaufwand, Hinweisen

### 3. Lösungen (`VXX-Thema_loesungen.md`)
Ausführliche Musterlösungen:
- Schritt-für-Schritt-Erklärungen
- Häufige Fehler und deren Vermeidung
- Alternative Lösungsansätze
- Bei Python: Vollständiger, kommentierter Code

**Zielgruppe**: Materialen für 1. und 2. Semester Bachelor Maschinenbau

## Verfügbare Lektionen

### ✅ Semester 1
- **[V01: Binäres Zahlensystem](lessons/V01-Binaeres-Zahlensystem/)** - Stellenwertsysteme, Umrechnung, Zweierkomplement, Bit-Manipulation | Python: Installation, Variablen, print(), input()
- **[V02: Fließkommazahlen](lessons/V02-Fliesskommazahlen/)** - IEEE 754, Rundungsfehler, Genauigkeit | Python: String-Formatierung, f-Strings, Datei-I/O
- **[V03: Boolsche Algebra Teil 1](lessons/V03-Boolsche-Algebra-Teil1/)** - Logische Operatoren, Wahrheitstabellen | Python: Datentypen, Type Casting, Scope
- **[V04: Boolsche Algebra Teil 2](lessons/V04-Boolsche-Algebra-Teil2/)** - De Morgan, XOR, Logikschaltungen | Python: Vergleichsoperatoren, and/or/not, Truthy/Falsy
- **[V05: Programm-Ablauf-Pläne Teil 1](lessons/V05-Programm-Ablauf-Plaene-Teil1/)** - PAP-Symbole, Grundstrukturen, DIN 66001/ISO 5807 | Python: if, if-else, if-elif-else, Verzweigungen
- **[V06: Programm-Ablauf-Pläne Teil 2](lessons/V06-Programm-Ablauf-Plaene-Teil2/)** - PAP zu Pseudocode, verschachtelte Schleifen, Algorithmen visualisieren | Python: for, while, range(), enumerate()
- **[V07: Software Engineering (KISS, DRY, SRP)](lessons/V07-Software-Engineering-KISS-DRY-SRP/)** - Software-Design-Prinzipien, Code-Qualität, Refactoring | Python: break, continue, loop else, List Comprehensions, string/random Module
- **[V08: Listen und Datenstrukturen Teil 1](lessons/V08-Listen-und-Datenstrukturen-Teil1/)** - Arrays, Verkettete Listen, Stacks (LIFO), Queues (FIFO), Zeitkomplexität | Python: Listen, Tupel, 11 List-Methoden, sorted(), sum(), all(), any(), zip(), Slicing, Aliasing vs. Copying
- **[V09: Listen und Datenstrukturen Teil 2](lessons/V09-Listen-und-Datenstrukturen-Teil2/)** - Binärbäume, BST-Operationen, Tree Traversals (Inorder/Preorder/Postorder/Level-Order), Hash-Tabellen, Kollisionsbehandlung (Chaining, Open Addressing) | Python: try-except-else-finally, raise, Benutzerdefinierte Exceptions, json-Modul
- **[V10: Laufzeitanalyse & Algorithmik](lessons/V10-Laufzeitanalyse-und-Algorithmik/)** - O-Notation (Big-O, Omega, Theta), Best/Average/Worst-Case Analyse, Sortieralgorithmen (Bubble Sort, Quick Sort, Merge Sort), Rekursion, Fibonacci-Komplexität | Python: def-Statement, return, Parameter/Argumente, Default-Parameter, Keyword Arguments, Multiple Return Values, Funktionen als First-Class Objects, Scope & LEGB-Regel, Docstrings
- **[V11: GPTs, LLMs & Künstliche Intelligenz](lessons/V11-GPTs-LLMs-KI/)** - KI-Geschichte (Symbolische KI → ML → DL), Neuronale Netze, Transformer-Architektur, Self-Attention & Multi-Head Attention, GPT/BERT/LLaMA, Training/Fine-Tuning, Halluzinationen, Bias, Risikobewertung | Python: Keyword-Only Arguments (*), *args, **kwargs, Unpacking-Operatoren, Lambda-Funktionen, map(), filter(), Type Hints (typing-Modul), Docstring-Stile (Google/NumPy), fehlertolerante Batch-Verarb
eitung

### ✅ Semester 2
- **[V12: Prompt Engineering & Best Practices](lessons/V12-Prompt-Engineering-Best-Practices/)** - Prompt-Anatomie (Kontext, Aufgabe, Format, Constraints), Zero/One/Few-Shot Learning, Chain-of-Thought Prompting, Role-Based Prompting, Fortgeschrittene Patterns (ReAct, Tree-of-Thoughts, Self-Consistency), Iteratives Prompt-Design, Temperatur-Parameter, Häufige Fehler, Ethik & Bias-Vermeidung | Python: import, from...import, as-Aliase, Eigene Module erstellen, Packages (__init__.py, __all__), if __name__ == "__main__" Pattern, Relative vs. Absolute Imports, Virtuelle Umgebungen (venv, pip freeze, requirements.txt), CLI-Tools mit argparse
- **[V13: Betriebssysteme & Rechnerarchitektur – Teil 1](lessons/V13-Betriebssysteme-Rechnerarchitektur-Teil1/)** - Von-Neumann-Architektur (4 Komponenten, gemeinsamer Bus, Flaschenhals), CPU-Struktur (ALU, Control Unit, Register, Taktgeber), Fetch-Decode-Execute-Zyklus, Cache-Hierarchie (L1/L2/L3, Zugriffszeiten, Locality-Prinzipien: Temporal & Spatial) | Python: Matplotlib (matplotlib.pyplot), Linienplots (plt.plot()), Scatter-Plots (plt.scatter()), Achsenbeschriftungen (xlabel, ylabel, title), Legenden & Gitter (legend, grid), Fehlerbalken (errorbar), Flächen-Schattierung (fill_between), Subplots (subplots), Logarithmische Skalierung (xscale, yscale), Referenzlinien (axhline, axvline, axhspan, axvspan), Plot-Export (savefig), NumPy-Integration (polyfit, polyval, linspace)
- **[V14: Betriebssysteme & Rechnerarchitektur – Teil 2](lessons/V14-Betriebssysteme-Rechnerarchitektur-Teil2/)** - Betriebssystem-Aufgaben (Prozessverwaltung, Speicherverwaltung, Dateisysteme, I/O, Sicherheit), Prozesse & Threads (Unterschiede, Vorteile), Scheduling-Algorithmen (FCFS, SJF, Round Robin, Priority), Virtueller Speicher & Paging (MMU, Page Tables, TLB, Page Faults), Dateisysteme & Journaling (ext4-Modi, moderne Alternativen: ZFS/Btrfs/APFS/XFS) | Python: Bar Charts (bar, barh, gruppiert, gestapelt), Histogramme (hist mit bins/density/cumulative), Erweiterte Subplots (subplot, subplots, subplot2grid, GridSpec), Logarithmische Achsen (xscale, yscale, loglog), Annotationen (annotate mit arrowprops/bbox), NumPy-Funktionen (logspace, argmax, argmin, cumsum), transparente Plot-Exporte

### ✅ Semester 2 (fortgesetzt)
- **[V15: Netzwerktechnik Grundlagen & Protokolle – Teil 1](lessons/V15-Netzwerktechnik-Grundlagen-Protokolle-Teil1/)** - OSI-Modell (7 Schichten: Physical, Data Link, Network, Transport, Session, Presentation, Application), TCP/IP-Modell (4 Schichten), Protokoll-Zuordnung, Encapsulation, IPv4 (32-bit, private/public Ranges, spezielle Adressen), IPv6 (128-bit, Shortening-Regeln, Adresstypen), Subnetting mit CIDR-Notation (Netzwerk-/Host-Bits, praktische Berechnungen) | Python: Generator-Konzept (yield-Keyword, Lazy Evaluation, Memory-Effizienz O(1)), Generator-Funktionen & -Pipelines (Verkettung für ETL), Iterator-Protokoll (__iter__, __next__), Iterator vs. Iterable (Exhaustion, mehrfache Iteration), CSV-Modul (csv.reader, csv.writer, csv.DictReader, csv.DictWriter, newline=''-Parameter), Built-in-Funktionen (iter, next), itertools.tee (Generator klonen), Anwendungen: Log-Analyse mit Generator-Pipeline, E-Commerce ETL mit decimal.Decimal
- **[V17: Kryptografie – Teil 1](lessons/V17-Kryptografie-Teil1/)** - Kryptografie-Grundlagen (Caesar, Kerckhoffs' Prinzip), Symmetrische Verschlüsselung (DES, AES), Asymmetrische Verschlüsselung (RSA mit mathematischen Details), RSA-Workflow (Schlüsselerzeugung, Ver-/Entschlüsselung), Hybrid-Verschlüsselung (Kombination symmetrisch + asymmetrisch), Schlüsselaustausch-Problem, Anwendungen (HTTPS, E-Mail, VPN) | Python: Socket-Programmierung (socket-Modul), Server-/Client-Socket-Methoden (bind, listen, accept, connect), Datenübertragung (send, sendall, recv), Byte-Encoding/Decoding, Socket-Verwaltung (close, setsockopt, settimeout), TCP/IP Client-Server-Architektur, Multi-Client-Server (sequenziell, Threading-Vorschau), HMAC-ähnliche Authentifizierung (hashlib.sha256, hexdigest), Praxis: Echo-Server, CNC-Temp-Monitor (JSON), Multi-Client Sensor-Server, Roboter-Steuerung, Sichere Maschinen-Kommunikation
- **[V18: Kryptografie – Teil 2](lessons/V18-Kryptografie-Teil2/)** - Hash-Funktionen (SHA-256, SHA-3, MD5), Hash-Eigenschaften (Eindeutigkeit, Deterministisch, Einweg, Lawineneffekt, Kollisionsresistenz), Public-Key-Infrastruktur (PKI), Certificate Authorities, X.509-Zertifikate, Digitale Signaturen (Workflow, Verifikation), TLS/SSL Handshake, Passwort-Hashing (bcrypt, scrypt, Argon2, Salt & Pepper, Rainbow Tables) | Python: HTTP-Protokoll (Request-Response, Methoden, URL-Anatomie), requests-Bibliothek (get, post, Response-Objekte), Query-Parameter & Headers (User-Agent, Authorization, Content-Type), Status Codes (200, 201, 400, 401, 404, 500), Error Handling (raise_for_status, Timeout, ConnectionError, HTTPError, JSONDecodeError), Pagination (Loop über Seiten), bcrypt-Modul (hashpw, gensalt, checkpw, Salt-Generierung), hashlib (SHA-256, update, hexdigest, blockweises Lesen), Praxis: Material-API, Produktionsdaten-Pagination, CNC-Zugriffskontrolle, Firmware-Update-Verifikation
- **[V19: Datenbanken – Teil 1](lessons/V19-Datenbanken-Teil1/)** - Relationale Datenbanken (DBMS-Vorteile: Redundanz, Integrität, Konkurrenz, Sicherheit), Relational Model (Tabellen, Schlüssel, Beziehungen, Constraints), SQL DDL (CREATE TABLE mit PRIMARY KEY, FOREIGN KEY, NOT NULL, UNIQUE, CHECK, DEFAULT, AUTOINCREMENT), SQL DML (INSERT, UPDATE, DELETE mit executemany), SQL DQL (SELECT mit WHERE/ORDER BY/LIMIT, Aggregationen: COUNT/SUM/AVG/MIN/MAX), Erweiterte SQL (JOINs: INNER/LEFT, GROUP BY + HAVING, Subqueries, Indexes), Transaktionen (BEGIN/COMMIT/ROLLBACK, ACID-Eigenschaften), Normalisierung (1NF/2NF/3NF mit Beispielen), ER-Modellierung (Entitäten, Attribute, Kardinalitäten 1:1/1:n/n:m) | Python: sqlite3-Modul (connect, cursor, execute, executemany, fetchall/fetchone/fetchmany, commit, rollback, close), Prepared Statements (? Platzhalter, SQL-Injection-Schutz), Error Handling (IntegrityError, OperationalError, Error), Context Managers (with-Statement für auto-cleanup), row_factory (sqlite3.Row für dict-ähnlichen Zugriff), Transaktionsmuster (commit bei Erfolg, rollback bei Fehler), pandas-Integration (read_sql_query), matplotlib-Visualisierung (Zeitreihen, Anomalieerkennung), Multi-Format I/O (CSV/JSON/XML Import/Export), OOP Datenbank-Wrapper, Praxis: Kühlschrank-Monitoring, Werkstoff-Prüfdatenbank (3-Tabellen-JOINs), Fertigungsauftragsverwaltung (Transaktionen), IoT Sensor-Analyse (pandas/matplotlib), Produktionsplanung (komplexe JOINs, CSV-Export)

### 🔄 In Planung
- V16, V20-V22 folgen schrittweise

## Prüfungsformat & Bewertung

### Format
- **Schriftliche Prüfung**
- **Anforderung**: Mindestens **50% Praktische Aufgaben** (Python-Programmierung)
- Kombination aus Theorie- und Praxisfragen

### Bewertungskriterien
- Verständnis informatischer Grundlagen
- Korrektheit und Funktionalität des geschriebenen Python-Codes
- Problemlösungsansätze und Komplexitätsmanagement
- Dokumentation und Code-Qualität

## Für Dozenten

Diese Dokumentation richtet sich primär an Lehrende und unterstützt bei:
- Der Verwaltung von Vorlesungsinhalten
- Der Standardisierung von Lehrmaterialien
- Der Versionskontrolle von Vorlesungsskripten
- Der Durchführung konsistenter Vorlesungen über mehrere Semester
- Der Prüfungsvorbereitung und -durchführung

## Ressourcen

### Im src-Ordner verfügbar
- Tools und Skripte zur Lesson-Erstellung
- Templates für Aufgaben und Prüfungen
- Beispielcode und Lösungsvorschläge

### Technische Setup
- Installationsanleitungen für Python und erforderliche Bibliotheken
- IDE- und Umgebungs-Empfehlungen
- Troubleshooting-Guides

## Nächste Schritte

Weitere Informationen zur Nutzung und Erstellung von Lessons folgen in den kommenden Updates.

---

*Letzte Aktualisierung: Januar 2026*

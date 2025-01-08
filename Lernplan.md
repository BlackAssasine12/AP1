# Lernzettel AP1 2024

## Inhalt
- [Vorwort](#vorwort)
- [Projektmanagement](#projektmanagement)
  - [Agile Modelle](#agile-modelle)
  - [Wasserfallmodell](#wasserfallmodell)
  - [Netzplan](#netzplan)
  - [Projektmanagement Generell](#projektmanagement-generell)
  - [Qualitätsmanagement](#qualitätsmanagement)
- [IT-Sicherheit und Datenschutz](#it-sicherheit-und-datenschutz)
  - [Datenschutz (DSGVO)](#datenschutz-dsgvo)
  - [Gefährdungen der IT-Sicherheit](#gefährdungen-der-it-sicherheit)
  - [Maßnahmen gegen Gefährdungen](#maßnahmen-gegen-gefährdungen)
  - [IT-Grundschutz und IT-Sicherheitsgesetz](#it-grundschutz-und-it-sicherheitsgesetz)
- [IT-Systeme und Netzwerke](#it-systeme-und-netzwerke)
  - [Verschlüsselungsverfahren](#verschlüsselungsverfahren)
  - [IT-Systeme](#it-systeme)
  - [Konzeption einer IT-Ausstattung](#konzeption-einer-it-ausstattung)
  - [Installation von Hardware](#installation-von-hardware)
  - [Einsatz von Cloud Computing](#einsatz-von-cloud-computing)
  - [Server-Virtualisierung](#server-virtualisierung)
  - [Betriebssysteme](#betriebssysteme)
- [Software und Programmierung](#software-und-programmierung)
  - [Software](#software)
  - [Netzwerk](#netzwerk)
- [Arbeits- und Geschäftsprozesse](#arbeits--und-geschäftsprozesse)
  - [Marktformen](#marktformen)
  - [Leitungssysteme](#leitungssysteme)
  - [Führungsstile](#führungsstile)
  - [Rechtsformen und Wirtschaftlichkeitsüberlegungen](#rechtsformen-und-wirtschaftlichkeitsüberlegungen)
- [Weitere Themen](#weitere-themen)
  - [4-Ohren-Modell](#4-ohren-modell)
  - [Fragen aus den AO2020 Prüfungen/Misc Stuff](#fragen-aus-den-ao2020-prüfungenmisc-stuff)
  - [USV](#usv)
  - [DSL Arten](#dsl-arten)
  - [Netzwerk Komponenten/Vererbung](#netzwerk-komponentenvererbung)
  - [Einführung Software/Hardware](#einführung-softwarehardware)
  - [SWOT-Analyse](#swot-analyse)
  - [Projektabschluss](#projektabschluss)
  - [Nachhaltigkeit (Green IT)](#nachhaltigkeit-green-it)
  - [Service-Level-Agreement / SLA](#service-level-agreement--sla)

## Vorwort
Dieser Lernzettel wurde zur Vorbereitung der AP1 Prüfung erstellt, basierend auf alten Prüfungen und dem Prüfungsvorbereitungsbuch. Später wurde er mit der Community im Fachinformatiker Discord erweitert.

## Projektmanagement

### Agile Modelle
Agile Methoden richten sich nach den Prinzipien einer eingeübten oder formalisierten Abläufe, die sich als sinnvoll und erfolgreich erwiesen haben. Agile Prozesse helfen, die Entwurfsphase kurz und so schnell wie möglich das Ergebnis mit dem Kunden abzustimmen.

#### Scrum
- Beginnt mit Sprintplanung und endet mit einem Sprint-Review.
- Ein Sprint darf nicht unterbrochen werden.
- Ein Sprint dauert in der Regel ein bis vier Wochen.
- Der Scrum Master führt die Scrum-Regeln ein und sorgt für einen ungestörten Ablauf in der Entwicklung.
- Der Scrum Master entwickelt nicht und ist kein Teil des Entwicklerteams.
- Ein Entwicklerteam besteht aus 3 bis 9 Personen.
- Ein Entwicklerteam soll aus mehreren Experten (Entwickler, Tester, Architekten) bestehen.
- Der Product Owner ist für das Product Backlog verantwortlich.
- Das Daily Scrum ist ein tägliches 15-minütiges Meeting des Entwicklerteams.
- Stakeholder können sich jederzeit zu den Prozessen informieren und diese begleiten.

### Wasserfallmodell
#### Dokumentgetrieben
Für alle Phasen des Wasserfallmodells müssen Dokumentationen verfasst werden. Am Ende der Phase ist die abgeschlossene Dokumentation gleichzeitig ein Meilenstein im Projekt.

- **Lastenheft**: Beschreibt die Funktionalitäten, die die Software erfüllen soll. Wird vom Auftraggeber erstellt.
- **Pflichtenheft**: Beschreibt, wie die Anforderungen des Lastenhefts umgesetzt werden können. Wird vom Auftragnehmer erstellt.

#### Top-Down-Methode
Diese Methode beschreibt eine Vorgehensweise, die vom Allgemeinen zum Speziellen führt. Für die Softwareentwicklung entsteht beispielsweise zuerst der Entwurf oder das Design und anschließend werden die einzelnen Module implementiert. Das Wasserfallmodell arbeitet genau nach dieser Vorgehensweise.

##### Vorteile
- Einfache verständliche Struktur
- Wenig Managementaufwand
- Kalkulierbare Kosten
- Konsequente Dokumentation

##### Nachteile
- Geringe (keine) Flexibilität
- Keine Rückkopplungsmöglichkeiten in früheren Phasen
- Systemerfahrung meist sehr spät nach Projektbeginn
- Kunde ist nur zu Beginn und am Ende beteiligt (Fehlentwicklungen)

### Netzplan
#### Vorwärtsrechnung und Rückwärtsrechnung
- **Vorwärtsrechnung**: Dient dazu, den frühestmöglichen Endzeitpunkt zu ermitteln.
- **Rückwärtsrechnung**: Dient dazu, zu ermitteln, wann mit einem Vorgang spätestens begonnen werden muss, damit das Projektende gehalten werden kann.

#### Gantt-Diagramm
- **Parallelvorgänge**: Direkt ersichtlich (visuell)
- **Abhängigkeiten**: Im Netzplan besser ersichtlich (Wer ist der Nachfolger bzw. Vorgänger von wem)

### Projektmanagement Generell
Ein Projekt ist ein einmaliges Vorhaben mit klarem Ziel sowie einem Anfangs- und Endtermin.

#### Projektmanagementmethode PRINCE2
Eine temporäre Organisation, die mit dem Ziel gegründet wurde, ein oder mehrere Produkte gemäß einer vereinbarten Business Case (Geschäftsszenario) zu liefern.

##### Stakeholder in einem Projekt
- Projektleiter
- Projektmitarbeiter
- Lieferanten
- Kunden
- Benutzer
- Auftraggeber
- Sponsoren

##### Projektphasen
1. Projektauftrag/Projektdefinition: Machbarkeitsstudie
2. Projektplanung: Meilensteine, Gantt-Diagramm
3. Projektdurchführung: Gantt-Diagramm
4. Projektabschluss: Abschlussbericht

##### Stakeholder-Analyse
Die Stakeholder-Analyse ermittelt die wesentlichen Ziele, die Motivation und die Einstellungen der Stakeholder im Zusammenhang mit den geplanten Projekten. Damit werden frühzeitig Probleme erkannt (Projektgegner, gegenläufige Ziele etc.).

##### Risikoanalyse
Die Risikoanalyse hilft bei der Identifizierung potenzieller Probleme, die während eines Projekts oder Prozesses auftreten könnten.

##### Machbarkeitsanalyse
Die Machbarkeitsanalyse ist eine umfassende Studie, in der die Machbarkeit des Projekts aus verschiedenen Perspektiven überprüft wird. Das sind sowohl technische als auch wirtschaftliche Überprüfungen. Die Stakeholder-Analyse ist ein Teil dieser umfassenden Studie, ebenso wie die Risikoanalyse.

### Qualitätsmanagement
#### Total Quality Management (TQM)
Das Total Quality Management (TQM) besteht aus organisationsweiten Bemühungen zur Installation und Herstellung eines dauerhaften Klimas, in dem die Mitarbeiter ihre Fähigkeiten kontinuierlich verbessern, um gewünschte Produkte und Dienstleistungen anzubieten, die von Kunden besonders wertgeschätzt werden.

#### Grundlagen Qualität
##### Qualitätsaspekte
- Qualitätsbegriffe
- Prozessqualität
- Qualität der Prozesse, die zum Produkt führen
- Produktqualität
- Qualität des Endproduktes

##### Ablauf Qualitätsmanagement
Ist-Analyse → Sollkonzept → Schulung der Mitarbeiter → QM-Handbuch verfassen → Interne Audits → Zertifizierung

##### Qualität
Qualität (lat. qualitas: Beschaffenheit, Merkmal, Eigenschaft, Zustand) bezeichnet die Güte aller Eigenschaften eines Objektes, Systems oder Prozesses sowie die den Handlungen und deren Ergebnissen vorgelagerten individuellen Werthaltungen.

##### Softwarequalität
- Zuverlässigkeit: Reife, Fehlertoleranz, Wiederherstellbarkeit
- Funktionalität: Angemessenheit, Interoperabilität, Sicherheit
- Benutzbarkeit: Verständlichkeit, Erlernbarkeit, Bedienbarkeit
- Effizienz: Zeitverhalten, Verbrauchsverhalten
- Wartbarkeit: Analysierbarkeit, Änderbarkeit/Updatebarkeit
- Portabilität: Anpassbarkeit, Austauschbarkeit, Installierbarkeit

##### Modultest
Modultests dienen dazu, einzelne Module der Komponenten zu testen. Das geschieht in der Regel in Form eines White-Box-Tests. Durch den Entwickler Frameworks wie JUnit helfen dabei solche Tests zu automatisieren.

##### Integrationstest
Der Integrationstest prüft die einzelnen Komponenten im Zusammenspiel. In der Regel werden Komponenten nach dem Modultest direkt mit einem Integrationstest auf Fehler in der Interaktion mit bestehenden Komponenten geprüft. Auch hier ist eine Automatisierung möglich.

##### Systemtest
Der Systemtest prüft die komplette Software gegen die definierten Anforderungen. In der Regel findet dieser Test auch in einem Testsystem statt, das die Produktivumgebung nachbildet.

##### Abnahmetest
Der Abnahmetest wird durch den Auftraggeber durchgeführt. Er prüft das Produkt auf die geforderten Funktionalitäten. Der Test findet in der Regel als Black-Box-Test statt.

## IT-Sicherheit und Datenschutz

### Datenschutz (DSGVO)
Seit Mai 2018 gilt die DSGVO. Das BDSG (Bundesdatenschutzgesetz) regelt die Bereiche, in denen die DSGVO den Mitgliedstaaten Gestaltungsmöglichkeiten einräumt.

#### Recht auf Auskunft
Die betroffene Person hat das Recht, ob personenbezogene Daten von ihr verarbeitet werden. Falls ja, hat sie das Recht auf Auskunft über den Verarbeitungszweck, über die Kategorie der Datenerhebung, über die Empfänger der Daten, über die Dauer der Speicherung und über die Herkunft der Daten.

#### Recht auf Berichtigung/Richtigkeit
Sofortige Berichtigung oder Ergänzung nicht korrekter personenbezogener Daten.

#### Recht auf Löschung
Daten müssen gelöscht werden, wenn:
- Daten nicht mehr notwendig sind
- Betroffene Person widerruft
- Daten unrechtmäßig erhoben worden sind

#### Recht auf Widerspruch
Die betroffene Person kann der Verarbeitung ihrer personenbezogenen Daten widersprechen.

### Grundlagen
#### Vertraulichkeit
Unter Vertraulichkeit versteht man, dass Daten nur von Personen eingesehen oder offengelegt werden dürfen, die dazu berechtigt sind.

#### Integrität
Bedeutet, dass es nicht möglich sein darf, Daten unbemerkt/unerkannt zu ändern. Die Korrektheit der Systeme und Informationen muss gegeben sein.

#### Verfügbarkeit
Eines Systems beschreibt die Zeit, in der das System funktioniert. Autorisierte Benutzer oder Administratoren müssen Zugang zu den Informationen/Systemen haben.

### DSGVO und BDSG
Der Datenschutz in Unternehmen und Organisationen wird seit Mai 2018 grundsätzlich durch die EU-Datenschutz-Grundverordnung (DSGVO) geregelt. Das neue Bundesdatenschutzgesetz (BDSG) regelt die Bereiche, in denen die DSGVO den Mitgliedstaaten Gestaltungsmöglichkeiten einräumt. Neben der DSGVO und dem BDSG regeln Datenschutzgesetze der Bundesländer und bereichsspezifische Gesetze den Umgang mit personenbezogenen Daten, die in IT- und Kommunikationssystemen oder manuell verarbeitet werden. Man hat das Recht auf Auskunft, Berichtigung und Löschung seiner Daten.

Ein Datenschutzbeauftragter muss benannt werden, wenn:
- Mehr als 10 Personen an der automatisierten Verarbeitung personenbezogener Daten arbeiten
- Die Verarbeitung personenbezogener Daten ein hohes Risiko für Rechte und Freiheiten der betroffenen Personen birgt
- Personenbezogene Daten geschäftsmäßig verarbeitet und übermittelt oder für Meinungsforschung genutzt werden
- Die Kernfähigkeit eine umfangreiche und systematische Überwachung der betroffenen Personen fordert
- Die Kernfähigkeit bei der Erfassung von Daten zur Herkunft, Religion, politischer Anschauung oder Gesundheit liegt

### Standard-Datenschutzmodell
- Zweckbindung Art 5 - Nichtverhaftung
- Datenminimierung Art 5 - Datenminimierung WICHTIG
- Richtigkeit Art 5 - Integrität
- Speicherbegrenzung Art 5 - Datenminimierung
- Vertraulichkeit Art 5 - Vertraulichkeit
- Identifizierung und Authentifizierung Art 12 - Integrität
- Belastbarkeit Art 32 - Verfügbarkeit/Integrität/Vertraulichkeit
- Berichtigungsmöglichkeiten von Daten Art 5 - Intervenierbarkeit
- Datenschutzfreundliche Voreinstellungen Art 25 - Datenminimierung/Intervenierbarkeit
- Verfügbarkeit Art 32: Verfügbarkeit
- Löschbarkeit von Daten Art 17 - Intervenierbarkeit
- Wiederherstellbarkeit Art 32 - Verfügbarkeit
- Einwilligung Art 4 - Transparenz, Intervenierbarkeit
- Unterstützung bei der Wahrnehmung von Betroffenenrechten Art 12 - Intervenierbarkeit

### Gefährdung der IT-Sicherheit
#### Angriffsmethoden und Angriffsszenarien auf die IT-Sicherheit
- **Identitätsdiebstahl**:
  - **Phishing**: Mithilfe gefälschter Websites oder E-Mails sollen vertrauliche Daten eines Nutzers ermittelt werden. Mit diesen Daten werden dann beispielsweise Onlinekonten des Nutzers manipuliert und Geldbeträge überwiesen.
  - **Vishing**: Stands for Voice Phishing und ist eine Variante des Phishings. Dabei werden Nutzer durch Telefonanrufe manipuliert und zur Herausgabe von persönlichen Daten animiert.
  - **Phorming**: Basiert auf der Manipulation der DNS-Abfragen von Webbrowsern. Damit werden die Benutzer auf gefälschte Websites umgeleitet, obwohl sie die korrekte Adresse eingegeben haben.
  - **Spoofing**: Beschreibt die allgemeine Methode, mit der ein Angreifer eine Identität verschleiern will. Das Phishing ist eine Variante des Spoofings.
  - **Nickmapping**: Setzt sich aus Nickname und Kidnapping zusammen. Bei dieser Methode wird versucht, die Internet-Identität einer Person zu „stehlen“, um damit in verschiedenen Bereichen illegal zu arbeiten.

#### Schadprogramme (Malware)
- **Spam**: Das unaufgeforderte Senden von Nachrichten/Informationen (meist per E-Mail)
- **Spyware**: Setzt sich aus Spy und Software zusammen. Spyware soll den Benutzer ausspähen, also Daten über den Benutzer sammeln und auch versenden. Diese Software wird sowohl zu Werbezwecken als auch zur Überwachung genutzt.
- **Adware**: Setzt sich aus Advertisement und Software zusammen. Oftmals ohne Rückfrage installiert sich diese Software zusätzlich auf dem PC des Benutzers und dient vor allem zu Werbezwecken.
- **Virus**: Ist ein Programm, das sich selbst weiterverbreitet. Dazu schleust es sich in andere Computerprogramme oder beispielsweise den Bootsektoren ein und sorgt dann für seine Reproduktion. Viren können großen Schaden anrichten, beispielsweise Datenverlust oder auch das System verlangsamen.
- **Trojaner**: Ist ein Programm, welches sich in oder hinter einem anderen nützlichen Programm versteckt und im Hintergrund schädliche Aktivitäten durchführt.
- **Wurm**: Ist ein Programm, welches sich selbst reproduziert. Die Intention ist wie bei einem Virus, Schaden anzurichten.
- **Ransomware**: Setzt sich aus Ransom (Lösegeld) und Software zusammen. Diese Software verschlüsselt die Daten auf fremden Systemen oder blockiert den Zugang zu den Daten. Damit soll eine Lösegeldzahlung erzwungen werden.

### DDOS
Mit Hilfe einer „distributed-denial-of-service attack“ soll ein Internetdienst so ausgelastet werden, dass er nicht mehr ansprechbar ist. Das wird mit einer hohen Anzahl von Anfragen aus verschiedenen Quellen erreicht. Die verschiedenen Quellen sorgen dafür, dass der Dienst nicht durch Blockieren einer Quelle den Angriff stoppen kann. DDOS-Angriffe werden oft durch Botnetze durchgeführt.

#### Botnetze
Ein Botnetz entsteht durch die Installation eines Schadprogramms auf viele Rechner und Vernetzung dieser Rechner im Hintergrund. Dadurch kann zentral der Befehl eines Angriffs gegeben werden und von unzähligen Rechnern parallel ausgeführt werden.

#### APT-Angriffe (Advanced Persistent Threats)
Diese Art des Angriffs unterscheidet sich von den herkömmlichen Schadprogrammen, da es eine geplante und intensiv vorbereitete Aktion mit verschiedenen Methoden ist und die IT-Infrastruktur einer Firma oder Behörde zu kompromittieren. Bei dieser Aktion können alle oben genannten Formen und Methoden eingesetzt werden, um das Ziel zu erreichen.

### Maßnahmen gegen Gefährdungen
#### Vermeidung von Phishing
- Aktuellen Virenscanner mit Phishing-Warnung installieren und aktuell halten (updaten)
- Niemals TANs oder Kennwörter aufgrund einer E-Mail/Link eingeben
- Mangelnde Rechtschreibung und allgemeine Ansprachen (wie sehr geehrte Damen und Herren) können auf einen Phishing-Versuch hinauslaufen

#### Verhalten bei einer Ransomware-Gefährdung
- Sofort alle Netzwerkverbindungen lösen
- Keine Anmeldung mehr an System mit Administrator- oder erweiterten Rechten
- Backups auf Infizierung prüfen und falls nicht infiziert das System komplett neu aufsetzen und Backups einspielen

#### Vermeidung von DDOS
- Alle Netzwerkkomponenten und Geräte (IoT) sollten mit sicheren Passwörtern versehen werden, unbenutzte Ports sollten geschlossen werden
- Deaktivieren einer alternativen statischen Website, auf die während des Angriffs umgeleitet wird. Damit können Kunden trotz des Angriffs über Kontaktmöglichkeiten informiert werden.

### IT-Grundschutz (Bild ersetzen)
#### BSI
Das BSI (Bundesamt für Sicherheit in der Informationstechnik) ist eine Bundesbehörde, die die IT-Sicherheit in Staat, Wirtschaft und Gesellschaft fördern und gewährleisten will.

#### IT-Grundschutz
Eine Methodik, die die Informationssicherheit in Behörden und Unternehmen erhöhen soll. Der IT-Grundschutz gilt als Maßstab für Absicherungen von Informationen und den Aufbau eines Managementsystems für Informationssicherheit (ISMS), kompatibel zu ISO 22001.

#### Sicherheitslinie und Sicherheitskonzept
Die Sicherheitslinie ist ein wichtiges Grundschutzdokument der Leitung zu den Stellen verbindlichen Prinzipien und das anzuhebende Niveau der Informationssicherheit in einer Institution. Das Sicherheitskonzept hingegen beschreibt die konkreten Maßnahmen, mit denen die Leitlinie umgesetzt werden kann.

Ein Informationssicherheitsbeauftragter muss:
- Die Entwicklung eines Sicherheitskonzeptes koordinieren
- Der Geschäftsleitung über den aktuellen Stand der Informationssicherheit berichten

### IT-Sicherheitsgesetz (Bild ersetzen)
Das IT-Sicherheitsgesetz soll einen Beitrag dazu leisten, die IT-Systeme und digitalen Infrastrukturen Deutschlands zu den sichersten weltweit zu machen. Dabei hat es vor allem die IT-Systeme der kritischen Infrastrukturen im Blick. Zu den kritischen Infrastrukturen gehören die Sektoren, deren Dienstleistung zur Versorgung der Allgemeinheit dient und deren Ausfall oder Beeinträchtigung zu erheblichen Versorgungsengpässen oder zu Gefährdung der öffentlichen Sicherheit führen könnte.

#### Sektoren der kritischen Infrastruktur
- Transport und Verkehr
- Finanz- und Versicherungswesen
- Gesundheit
- Informationstechnik und Telekommunikation
- Ernährung
- Wasser
- Energie

## IT-Systeme und Netzwerke

### Verschlüsselungsverfahren
#### Symmetrische Verschlüsselung
Für die symmetrische Ver- und Entschlüsselung ist es wichtig, dass sowohl Sender als auch Empfänger denselben Schlüssel benutzen. Die Daten werden mit dem Schlüssel verschlüsselt und ebenfalls entschlüsselt. Das Verfahren ist sehr sicher, solange die Schlüssel wirklich nur von beiden Parteien bekannt sind.
- Beispiele: WPA2, SSH, WLAN, OpenVPN, WPA3
- Verfahren: AES, Triple DES, Blowfish, SHA2 (MD5)

#### Asymmetrische Verschlüsselung
Die asymmetrische Ver- und Entschlüsselung benutzt nicht nur einen Schlüssel, sondern einen öffentlichen und einen privaten Schlüssel. Der öffentliche Schlüssel ist frei verfügbar, der private Schlüssel muss hingegen geheim bleiben. Die Verschlüsselung erfolgt dann mit dem öffentlichen Schlüssel, kann aber nur mit dem privaten Schlüssel entschlüsselt werden.
- Beispiele: RSA, Multifaktor TAN/Einmalpasswörter
- Kryptographische Hashfunktionen: Beispiele, Integritätsprüfungen, Prüfsummen, Einmalpasswörter, Sitzungsschlüssel, Speichern von Passwörtern, Digitale Signaturen

### IT-Systeme
#### UEFI/BIOS
- **UEFI**: Neu, grafisch mit Maus und Tastatur, schneller, direkt updatebar
- **BIOS**: Alt, tastaturbedienbar, 2,2 TB

#### Datensicherungskonzept
- **12 Großvater (jeden Monat) - 4 Väter (jede Woche) - 4 Söhne (jeden Tag außer dem Vater)**
- **Vollsicherung**: Komplettes Abbild der Daten, z.B. die Sicherung einer kompletten Festplatte oder eines kompletten Ordners
- **Differenzielle Sicherung**: Hier wird der aktuelle Datenbestand mit der letzten Vollsicherung verglichen und es werden alle Daten gesichert, die sich nach der letzten Vollsicherung geändert haben. Für die Rekonstruktion braucht man die letzte Vollsicherung und die letzte differenzielle Sicherung.
- **Inkrementelle Sicherung**: Hier wird immer nur das gesichert, was sich nach der letzten Vollsicherung und den anschließenden Sicherungen verändert hat. Für eine Rekonstruktion braucht man die letzte Vollsicherung und alle weiteren inkrementellen Sicherungen danach.

### Konzeption einer IT-Ausstattung
#### Open Source
Bietet öffentlichen Zugang zum Quelltext der Software. Je nach Lizenz kann der Quelltext genutzt, verändert oder weiterverarbeitet werden.

#### Public Domain
Der Begriff Public Domain bedeutet frei von Urheberrechten. Allerdings ist dieser Rechtsbegriff nur in einigen englischsprachigen Ländern gültig. In Deutschland kommt der Rechtsbegriff Gemeinfreiheit dem Public Domain recht nahe.

#### GNU/GPL
Ist eine Software-Lizenz, die den Benutzern die Möglichkeit gibt, die Software zu nutzen, zu ändern und zu verarbeiten. Wenn die Software verändert und vertrieben wird, dann muss es auf den gleichen Lizenzbedingungen geschehen.

#### OEM
Steht für Original Equipment Manufacturer. OEM-Softwareversionen werden oft nicht direkt verkauft, sondern nur in Kombination mit Hardware. Die Versionen sind dann preiswerter als im direkten Verkauf, können in manchen Fällen nicht einfach von der Hardware entkoppelt werden, um auf ein anderes System installiert zu werden.

#### EULA
Steht für End User License Agreement und soll die Benutzung von Software regeln.

### Installation von Hardware
#### Parallele Datenübertragung
Hier werden gebündelte Leitungen einzelne Bits gleichzeitig übertragen. Oftmals sind es 8 Leitungen, damit ein ganzes Byte übertragen werden kann. Ein Problem bei der parallelen Übertragung ist die Fehleranfälligkeit, je länger die Leitung ist.

#### Serielle Datenübertragung
Hier wird ein Bit nach dem anderen auf einer Leitung gesendet. Die Fehleranfälligkeit ist geringer als bei der parallelen Übertragung, deshalb können auch die Leitungen länger sein. Bei heutigen Schnittstellen wie USB 3.0 ist die Übertragungsgeschwindigkeit trotzdem enorm schnell.

### Einsatz von Cloud Computing
#### Infrastructure as a Service (IaaS)
Mit diesem Service werden den Nutzern virtuelle Rechner oder andere virtualisierte Hardware angeboten. Der Nutzer kann diese Ressourcen frei konfigurieren. Ein Beispiel für einen solchen Service sind virtuelle Server, mit denen der Nutzer seine Website verwaltet oder einen Onlineshop anbietet.

#### Platform as a Service (PaaS)
Dieser Service bietet die Möglichkeit, eine Plattform zu mieten, auf der eigene Programme entwickelt oder auch ausgeführt werden können. Beispielsweise muss eine Softwareentwicklungsfirma nicht alle Plattformen selbst installieren, um die Software zu testen, sondern mietet sich je nach Bedarf eine entsprechende Plattform.

#### Software as a Service (SaaS)
Dieser Service bietet verschiedene Software (z.B. Office), an die der Anwender ohne eigene Installation über die Cloud benutzen kann. Es kann beispielsweise über den Browser auf diese Software zugegriffen werden.

#### Vorteile
- Kosteneinsparung durch weniger oder geringe Lizenzgebühren für Software oder auch virtualisierte Hardware
- Zugriff auf Daten von überall
- Zeitnahes Backup aller Daten

#### Nachteile
- Abhängig von Internetzugang
- Datenschutz wird schwieriger, da der Server oft im Ausland steht
- Abhängigkeit von einem Unternehmen

#### Public Cloud
Cloud gemietet von einem Unternehmen (Dropbox, OneDrive)

#### Private Cloud
Cloud im eigenen Unternehmen (Intranet)

#### Hybrid Cloud
Kombination aus beidem

#### Community Cloud
Teilen sich mehrere Unternehmen

### Server-Virtualisierung
Zur Virtualisierung von Servern wird durch Einsatz einer Software eine virtuelle Schicht zwischen der eigentlichen Hardware und dem Betriebssystem erzeugt. Durch diese virtuelle Schicht können mehrere virtuelle Server mit unterschiedlichen Betriebssystemen auf einer gemeinsamen Hardwareplattform gleichzeitig betrieben werden. Die Virtualisierungsschicht regelt den vereinheitlichten Zugriff auf die zur Verfügung stehenden Ressourcen, wie Speicher oder Netzwerkanbindung. Die virtuellen Maschinen sind voneinander unabhängig und beeinflussen sich nicht gegenseitig.

#### Vorteile
- Bessere Auslastung von Systemressourcen
- Weniger physische Server notwendig
- Geringe Bereitstellungszeit für neue Server
- Einfache Wartung

#### Nachteile
- Fällt der physische Server aus, sind alle VMs down
- Geteilte Ressourcen wie RAM können überlastet werden

#### Hypervisor
Auch Virtual Machine Monitor genannt, ist ein Prozess, mit dem virtuelle Maschinen (VMs) erstellt und ausgeführt werden. Mit einem Hypervisor kann ein Host-Computer mehrere Gast-VMs unterstützen, indem er deren Ressourcen (z.B. Arbeitsspeicher und Rechenleistung) virtuell verteilt.

#### Bare Metal
- Setzt direkt auf der Hardware auf
- Verwaltet die Ressourcen besonders effizient
- Unterstützt gleichzeitig mehrere virtuelle Maschinen

#### Hosted
- Läuft als Anwendung in einem Host-Betriebssystem
- Ist im privaten Einsatz gebräuchlich
- Unterstützt gleichzeitig mehrere virtuelle Maschinen

#### Snapshot
Ist ein Abbild einer virtuellen Maschine. Bei der Erstellung eines Snapshots werden der Status, die Konfiguration und die Datenträgerinhalte eines virtuellen Computers gesichert. Ein Snapshot kann auch im laufenden Betrieb erstellt werden. Eine Rückkehr auf einen in einem Snapshot gesicherten Zustand ist problemlos möglich. Vor Veränderung einer Konfiguration ist daher die Erstellung eines Snapshots zu empfehlen.

### Betriebssysteme
#### Marktanteile der aktuellen Betriebssysteme
Die folgenden Betriebssysteme sind in den Grafiken eintragen: Android, weitere Betriebssysteme (mobil), Windows, iOS, Linux, MacOS X, weitere Betriebssysteme (PC)

#### Zusammenhang Betriebssystem, Hardware und Anwendungen
#### Technische organisatorische Maßnahmen (Datenschutz)
- **Härtung des Betriebssystems**: Keine lokalen Adminrechte, nur das was nötig ist installieren
- **Nutzerrechte**: Nur die Berechtigung, die der Nutzer braucht (GPO / AD Berechtigungen, Lizenzverwaltung, Assetverwaltung)
- **Asset-Tag**: Eindeutige Nummerierung der Hardware für die interne Hardwareverwaltung

## Software und Programmierung

### Software
#### Primitäre Datentypen
- **Int**: Ganzzahl
- **String**: Zeichenfolge aus Zahlen, Buchstaben und Sonderzeichen
- **Double**: Dezimalzahl/Fließkommazahl
- **Char**: 1 Zeichen
- **Bool**: True/False, 1/0
- **Byte**: 8 Bit
- **Short, Long**

### Normalisierung
#### Erste Normalform (1NF)
| RNr | RDatum | RBetrag | ArtikelNr | ArtikelBez | KNr | KName | KPLZ | KOrt |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 04.02.2021 | 500,00 € | A1 | Board | 201 | Beck | 50441 | Köln |
| 1 | 04.02.2021 | 500,00 € | A3 | Prozessor | 201 | Beck | 50441 | Köln |
| 1 | 04.02.2021 | 500,00 € | B6 | Monitor | 201 | Beck | 50441 | Köln |
| 2 | 20.01.2021 | 900,00 € | B9 | Drucker | 5 | Ritter | 40210 | Düsseldorf |
| 3 | 16.01.2021 | 400,00 € | A1 | Board | 68 | Krause | 50441 | Köln |
| 3 | 17.01.2021 | 400,00 € | A3 | Prozessor | 68 | Krause | 50441 | Köln |

#### Zweite Normalform (2NF)
Man bringt eine Tabelle in die zweite Normalform (2NF), indem man die Daten der Tabelle (aus der ersten Normalform) in einzelne Tabellen (Entitäten) aufteilt.

Im ersten Schritt muss man ermitteln, welche Entitäten in der Tabelle vorhanden sind (evtl. unterstützt durch farbige Markierungen).

| RNr | RDatum | RBetrag | Artikelnr | ArtikelBez | KNr | KName | KPLZ | KOrt |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 04.02.2021 | 500,00 € | A1 | Board | 201 | Beck | 50441 | Köln |
| 1 | 04.02.2021 | 500,00 € | A3 | Prozessor | 201 | Beck | 50441 | Köln |
| 1 | 04.02.2021 | 500,00 € | B6 | Monitor | 201 | Beck | 50441 | Köln |
| 2 | 20.01.2021 | 900,00 € | B9 | Drucker | 5 | Ritter | 40210 | Düsseldorf |
| 3 | 16.01.2021 | 400,00 € | A1 | Board | 68 | Krause | 50441 | Köln |
| 3 | 17.01.2021 | 400,00 € | A3 | Prozessor | 68 | Krause | 50441 | Köln |

In diesem Beispiel erkennt man drei Haupttabellen: Rechnung, Kunde und Artikel
Im zweiten Schritt zerlegt man die Tabelle und entfernt die Redundanzen aus den Einzeltabellen.

| RNr | RDatum | RBetrag |
| :--: | :--: | :--: |
| 1 | 04.02.2021 | 500,00 € |
| 2 | 20.01.2021 | 900,00 € |
| 3 | 16.01.2021 | 400,00 € |

| Artikelnr | ArtikelBez |
| :--: | :--: |
| A1 | Board |
| A3 | Prozessor |
| B6 | Monitor |
| B9 | Drucker |

| KNr | KName | KPLZ | KOrt |
| :--: | :--: | :--: | :--: |
| 201 | Beck | 50441 | Köln |
| 5 | Ritter | 40210 | Düsseldorf |
| 68 | Krause | 50441 | Köln |

Im dritten Schritt müssen die Beziehungen zwischen den Tabellen wieder hergestellt werden. Dazu muss man zunächst ermitteln, um welche Art von Beziehungen es sich handelt (1:1, 1:n oder m:n). Als Hilfsmittel kann man z.B. ein kleines ERM zeichnen.

Anschließend werden wie beim ERM Fremdschlüssel und Hilfstabellen ergänzt.

| RNr | RDatum | RBetrag | KNr |
| :--: | :--: | :--: | :--: |
| 1 | 04.02.2021 | 500,00 € | 201 |
| 2 | 20.01.2021 | 900,00 € | 5 |
| 3 | 16.01.2021 | 400,00 € | 68 |

| KNr | KName | KPLZ | KOrt |
| :--: | :--: | :--: | :--: |
| 201 | Beck | 50441 | Köln |
| 5 | Ritter | 40210 | Düsseldorf |
| 68 | Krause | 50441 | Köln |

| Artikelnr | ArtikelBez |
| :--: | :--: |
| A1 | Board |
| A3 | Prozessor |
| B6 | Monitor |
| B9 | Drucker |

| RNr | ArtNr |
| :--: | :--: |
| 1 | A1 |
| 1 | A3 |
| 1 | B6 |
| 2 | B9 |
| 3 | A1 |
| 3 | A3 |

### Datenbankaspekte (NoSQL, SQL)
#### Normalisierung
Ist ein Verfahren zur Verringerung von Datenredundanz in relationalen Datenbankmodellen verbunden mit dem Ziel, die Datenkonsistenz zu erhöhen.

#### Anforderungen an Datenbanksysteme
- Hard- und Software an einem Dateiserver
- Redundante Netzteile/Netzzugriff/Plattensystem (Raid)
- Granulares Datenberechtigungssystem
- Zusammenarbeit auf Dateiebene
- Latenz gering
- Backups
- Möglicher Fernzugriff
- Dynamische Speicherplatzanpassung
- Normalisierung der Datenbank (Normalisierung)

#### Allgemeine Anforderungen
- Datenunabhängigkeit
- Paralleler Datenzugriff (mehrere Accounts)
- Gemeinsame Datenbasis
- Integrität/Sicherheit
- Wiederherstellungsverfahren (Raid)

#### Relationales Datenbanksystem
- Weite Verbreitung
- Gute Unterstützung
- Geprüfte Qualität

##### Nachteile
- Bruch zwischen objektorientierter Programmierung und Dateihaltung
- Zwischenlösung durch ORM

#### Objektorientiertes Datenbanksystem
- Sinnvolle Ergänzung zur objektorientierten Programmierung

##### Nachteile
- Kaum verbreitet
- Wenig Know-how in Firmen

### Netzwerk
#### VPN
- **End-to-End**: (PC zu PC) Einzelne Geräte eine sichere Verbindung direkt miteinander über ein öffentliches Netzwerk
- **End-to-Site**: (PC zu Netzwerk, Homeoffice) Verbindet einzelnes Gerät mit einem Netzwerk
- **Site-to-Site**: (Netzwerk zu Netzwerk) Verbindet Netzwerk mit einem Netzwerk

##### Tunnel
Der Tunnel-Modus kommt stets dann zum Einsatz, wenn zumindest einer der beteiligten Rechner nicht direkt angesprochen, sondern als Security Gateway genutzt wird. → verschlüsselt

##### Transport
Im Transport-Modus kommunizieren zwei Hosts direkt via Internet miteinander. → nicht verschlüsselt, veraltet

#### OSI-Schichtenmodell und TCP/IP-Modell
| Von | Bis | Suffix | Netzklasse (typisch) | Anzahl Netze | Hosts pro Netz |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 10.0.0.0 | 10.255.255.255 | /8 | A (255.0.0.0) | 1 | 16.777.214 |
| 172.16.0.0 | 172.31.255.255 | /12 | B (255.255.0.0) | 16 | 65.534 |
| 192.168.0.0 | 192.168.255.255 | /16 | C (255.255.255.0) | 256 | 254 |

127.0.0.1 localhost

#### OSI
Das OSI-Referenzmodell ist ein Modell in der Netzwerktechnik, das auf 7 Schichten basiert. Die einzelnen Schichten haben klare Schnittstellen und bauen aufeinander auf. Das bedeutet, dass die oberen Schichten die Funktionalitäten und Dienste der anderen Schichten nutzen. Damit erhöht sich die Transparenz und die Austauschbarkeit einzelner Schichtmodule.

#### TCP/IP
Das TCP/IP-Modell ist ebenfalls ein Referenzmodell, das sämtliche Aspekte der Kommunikation im Netzwerk abbilden soll. Das Modell besteht aus vier Schichten:
- Anwendungsschicht
- Transportschicht
- Internetschicht
- Netzzugangsschicht

Das TCP/IP-Modell ähnelt in seiner Struktur dem DoD-Schichtenmodell (Department of Defense), das in den 1960er Jahren – deutlich früher als das OSI-Modell – entwickelt wurde.

##### Merksatz
Alle Deutschen Studierenden trinken verschiedene Sorten Bier

| OSI-Schicht | TCP-Schicht | Protokoll | Verwendete Adressen | Möglicher Fehler |
| :--: | :--: | :--: | :--: | :--: |
| Anwendung/Application | Anwendung/Application | DNS, DHCP |  | Serverkonfiguration fehlerhaft |
| Darstellung/Presentation | Anwendung/Application | IMAP/HTTPS |  |  |
| Sitzung/Session | Anwendung/Application | IMAP/HTTPS |  |  |
| Transport | Transport | TCP/UDP | Ports | Verlust eines Segments |
| Vermittlung/Network | Internet | IPv4/IPv6, ICMP | IP-Adressen | Falsche IP-Adresse vergeben |
| Sicherung/Data link | Netzzugang/Network Access | Ethernet | MAC-Adressen | Netzwerkkarte defekt |
| Bitübertragung/Physical | Netzzugang/Network Access |  |  | Medium getrennt |

#### DNS (Domain Name System)
DNS ist ein wichtiger Dienst in IP-Netzwerken. Durch DNS wird die Namensauflösung realisiert. So kann beispielsweise der Name "google.de" in eine IP (z.B. 91.250.85.179) aufgelöst werden. Port 53 (TCP/UDP)

#### SMTP (Simple Mail Transfer Protocol)
SMTP wird schwerpunktmäßig zum Einliefern und Weiterleiten von E-Mails verwendet.
- Häufig wird der TCP-Port 25 verwendet
- 465 (TCP mit TLS/SSL)

#### IMAPS (Internet Message Access Protocol over TLS/SSL)
IMAPS ist die abgesicherte Variante von IMAP und wird zum Abruf von E-Mails verwendet.
- Port: 993 TCP

#### TCP (Transmission Control Protocol)
TCP wird verwendet, um eine bidirektionale Verbindung zwischen zwei Netzwerkgeräten aufzubauen. Durch TCP wird eine zuverlässige Übertragung gewährleistet, da alle Segmente mit entsprechenden Nummern versehen werden. Verlorene Pakete können somit erneut angefordert werden. Kein Port

#### UDP (User Datagram Protocol)
Bei UDP wird keine Verbindung zwischen Sender und Empfänger aufgebaut. Stattdessen werden die Datagramme ungesichert versendet. Dies ist bei Anwendungen empfehlenswert, die eine geringe Latenz benötigen (z.B. VoIP oder Onlinespiele). Kein Port.

#### Telnet (Teletype Network)
Mit Hilfe von Telnet kann ein Fernzugriff auf diverse Systeme realisiert werden. Allerdings wird bei Telnet keine Verschlüsselung genutzt und somit das Passwort im Klartext übertragen. Meist wird deshalb SSH genutzt. Port 23 (TCP)

#### SSH (Secure Shell)
SSH wird häufig verwendet, um einen abgesicherten Zugriff auf die Kommandozeile eines entfernten Systems herzustellen. Port 22 (TCP/UDP)

#### HTTPS (Hypertext Transfer Protocol Secure)
HTTPS ist die abgesicherte Version von HTTP und wird genutzt, um Daten zwischen Webserver und Webbrowser zu übertragen. Port 443 (TCP)

#### DHCP (Dynamic Host Configuration Protocol)
Dieses Protokoll ermöglicht die Zuweisung der Netzwerkkonfiguration an einen Client (Host) durch einen Server. Port 67, 68 (UDP)

#### NFS (Network File System)
Mit Hilfe von NFS kann über eine Netzwerkverbindung auf Dateien zugegriffen werden. Das Protokoll kam ursprünglich nur im UNIX-Bereich zum Einsatz. Port 2049 (TCP)

#### SMB (Server Message Block)
Das SMB-Protokoll ermöglicht es, Netzwerkfreigaben bereitzustellen. Port 445 (TCP)

#### ICMP (Internet Control Message Protocol)
ICMP dient dem Austausch von Kontroll- und Fehlermeldungen in IP-Netzwerken. Der häufig genutzte "ping"-Befehl setzt auf die ICMP-Paket-Typen "Echo-Request" und "Echo Reply".

### Wireless Local Area Network (WLAN)

#### Access Point (AP)
Für WLANs im sogenannten "Infrastructure Mode" agiert der Access Point als zentrale Sendestation, die mit den einzelnen Teilnehmern kommuniziert.

#### IEEE 802.11n (Institute of Electrical and Electronics Engineers)
Der 802.11n Standard des IEEE ist eine Erweiterung des 802.11 Standards. Die n-Erweiterung ermöglicht beispielsweise größere Kanalbandbreiten (40 MHz) und MIMO (Multiple Input/Multiple Output).

#### SSID
Steht für "Service Set Identifier". Die SSID entspricht dem Namen des ausgestrahlten Netzwerks.

#### WLAN-Struktur mit WLAN Controller
WPA2 nutzt das Verschlüsselungsverfahren AES (Advanced Encryption Standard).

#### Multi-SSID
WLAN und Gast-WLAN, mehrere WLANs in einem Netzwerk.

#### WPA2 Personal
Pre-Shared Key/vorkonfiguriertes Passwort, das auf dem Client eingetragen muss (WPA2-PSK).

#### WPA2 Enterprise
Unternehmenseinsatz, hierbei wird vom Client eine Verbindung zu einem AAA-Server (meist RADIUS-Server) hergestellt. Der generiert Verschlüsselungscodes, die von dem jeweiligen Nutzer verwendet werden.

### Gebäudeverkabelung
 | Bereich | Beschreibung | Typische Übergangsmedium |
 | :--: | :--: | :--: |
 | Primärverkabelung (Campusverkabelung) | In diesem Bereich wird die Verkabelung zwischen Gebäuden realisiert. Es sind häufig Distanzen von mehreren hundert Metern zu überbrücken. | Lichtwellenleiter |
 | Sekundärverkabelung (Stockwerkverkabelung) | In diesem Bereich wird die Verkabelung zwischen dem Hauptverteiler des Gebäudes und den Etagenverteilern realisiert. Häufig treten auch hier Kabellängen von über 100 Metern auf. | Lichtwellenleiter |
 | Tertiärverkabelung (Etagenverkabelung) | In diesem Bereich wird die Verkabelung vom Stockwerkverteiler zu den Anschlussdosen realisiert. Häufig wird hier eine sternenförmige Struktur ausgehend vom Verteiler umgesetzt. Die Streckenlängen liegen typischerweise unter 100 Metern. | Kupferkabel |

#### LWL
- **Single-Mode-Fasern**: Bieten die höchste Übertragungsrate. Kleines Glas, braucht stärkeren Laser, 5-fache Reichweite.
- **Multi-Mode-Fasern**: Günstiger herzustellen, kleinere Übertragungsrate, Glas nicht so rein, großes Glas.
- **Kunststofffasern**: Für kurze Strecken gut geeignet.
- **Aufgrund hoher Kosten für Verlegung über lange Strecken werden meist sehr hochwertige Fasern vergraben.**

Lichtwellenleiter haben immer einen Kern aus Glas.

Multi-Mode-Gradientenindex-Faser

Single-Mode-Faser

##### Multi-Mode-Fasern
Erlauben höhere Übertragungsraten, da mehrere Modi gleichzeitig ausbreitungsfähig sind.

### Konfiguration von IP-Adressen

#### Aufgabe 1
Der Kunde bittet um Hilfe, da er trotz Konfiguration der IP-Adresse seines Desktop-PCs keine Netzwerkverbindung aufbauen kann. Auf Ihre Bitte stellt der Kunde einen Screenshot seiner IP-Konfiguration zur Verfügung. Erklären Sie, wo das Problem vermutlich liegt und machen Sie einen Vorschlag, um das Problem zu beheben.

Der eingetragene Standardgateway befindet sich in einem anderen Netz, da der Client im "192.168.99.12/24" Netz ist. Der Standardgateway muss im selben Netz wie der Client sein, z.B. 192.168.99.1.

#### Vorteile von DHCP
- Die Verwaltung und Vergabe von IP-Adressen wird automatisiert.
- IP-Adresskonflikte werden vermieden.
- Verringerter Konfigurationsaufwand bei den Endgeräten.

#### DHCP Discover
Der DHCP-Client schickt eine Anfrage an alle erreichbaren Geräte. Als Quell-Adresse wird 0.0.0.0 und als Ziel 255.255.255.255 verwendet. Jedes Gerät nimmt die Anfrage an und alle erreichbaren DHCP-Server verarbeiten die Nachricht weiter.

#### DHCP Offer
Jeder angesprochene DHCP-Server mit freien Adressen sendet ein Angebot (Offer) als Antwort auf ein DHCP Discover. Dieses Angebot ist an die MAC-Adresse des angefragten Geräts adressiert. Enthalten ist ein Vorschlag für eine IP-Adresse inkl. Subnetzmaske und Gültigkeitsdauer (Leasetime).

#### DHCP Request
Der DHCP-Client akzeptiert eines der erhaltenen Angebote und informiert den zugehörigen DHCP-Server. Nach Hälfte der Lease-Time sendet der Client erneut einen Request, um die Zeit zu verlängern.

#### DHCP Acknowledge
Der DHCP-Server bestätigt dem Client die Zuweisung der IP-Adresse an den Client. Gegebenenfalls können noch weitere Informationen wie IP-Adresse des DNS-Servers übermittelt werden.

Man kann eine MAC-Adressen-Liste auf dem DHCP-Server hinterlegen und nur Geräte auf der Liste erhalten eine IP.

#### IPv6
- IPv4 und IPv6 können mithilfe geeigneter Mechanismen (z.B. Tunnelmechanismen) parallel betrieben werden.
- IPv6 hat 2^128 Möglichkeiten zur Bildung von Adressen.
- Ein Hauptgrund für die Entwicklung von IPv6 ist der erweiterte Adressraum (128 Bit statt 32 Bit).
- Windows 10 unterstützt IPv6.

#### AF00:0000:0000:E255:0000:0000:0001:332D:81EA
Folgende Regeln sind zu beachten, um die verkürzte Darstellung von IPv6-Adressen zu ermitteln:
- Führende Nullen in einem Block von 4 Hexadezimal-Ziffern können weggelassen werden. Beispiel: 002B → 2B.
- Benachbarte Blöcke von Nullen können durch "::" ersetzt werden. Allerdings kann dies nur an einer Stelle der IPv6-Adresse angewandt werden, da ansonsten die IP-Adresse nicht eindeutig wäre. Bei mehreren Blockfolgen bestehend aus Nullen wird die erste Blockfolge ersetzt.
- Beispiel: A21B:C756:0000:0000:1234:0000:0000:0000 → A21B:C756::1234:0:0:0.

Bei Subnetzen wird standardmäßig ein /64 Netz gegeben.

#### Bedeutung hinter /64
Die ersten 64 Bits (128 Bit lang) IPv6-Adresse den Netzanteil der Adresse definieren. Dieser Netzanteil wird meist als Network Prefix bezeichnet und kann auch Bits für die Subnetzbildung beinhalten. Die verbleibenden 64 Bit sind die Interface ID, die mit dem Hostanteil bei IPv4 vergleichbar ist.

#### Wie viele IP-Adressen bei /64?
2^64

#### Warum ist /64 die Regel bei IPv6?
Ist für Autoconfiguration angedacht, hierbei entspricht die Interface ID einem zufälligen Wert oder der EUI-64 (Extended Unique Identifier 64 Bit) der Netzwerkkarte fast, ist die Vergabe eines /64 Subnetzes normal.

#### Was machen Privacy Extensions?
Sind Erweiterungen zu IPv6, die zum Schutz der Privatsphäre keinen direkten Rückschluss auf die Hardwareadresse des Nutzers aus der IPv6-Adresse zulassen. Für öffentlich zugängliche Dienste werden die Privacy Extensions teilweise deaktiviert.

#### Was ist DS-Lite?
Dual Stack Lite → keine öffentliche IPv4-Adresse, sondern eine private IPv4-Adresse und ein globales IPv6-Präfix zugewiesen. Soll IPv4-Datenverkehr transportiert werden, werden am Endkunden-Router Pakete mit einer privaten IPv4-Adresse in IPv6-Pakete verpackt. Man spricht hier von einer 4-in-6-Tunnel-Technologie. Am Endpunkt des 4-in-6-Tunnels wird der IPv5-Header entfernt. Um das Paket mit der privaten IPv4-Adresse in das öffentliche IPv4-Netz einschleusen zu können, nimmt der Internet Service Provider eine Adressumsetzung von der privaten IPv4-Adresse auf öffentliche IPv4-Adressen vor. Man spricht hier von Carrier Grade NAT (CG-NAT).

#### RFC4291 IPv6 Erklärung - Hexa (16^x)
2019:abcd:0123:1200:0000:0000:0000:0001 → 2019:abcd:123:1200::1

2019:abcd:0123:1200 → Network Prefix → 64 Bit gesamt → 16 Bit pro "::" Teil
0000:0000:0000:0001 → Interface Identifier → 64 Bit

Gesamt 128 Bit - 1 Zahl = 4 Bit (Hexadezimal)

Network Prefix | Subnetze | Interface Identifier
2019:abcd:0123:12 | 00: | 0000:0000:0000:0001 → /56
1200 → 000100100000000 (binär)

### Kupferkabel
- **POE**: Power over Ethernet, 20 W ungefähr.
- **Cat 5**: 100 MHz bis zu 1 Gbit/s möglich (veraltet).
- **Cat 6 (a)**: 250-500 MHz bis zu 10 Gbit/s für normale Anwendungen ausreichend.
- **Cat 7**: 600-1000 MHz bis zu 10 Gbit/s, wird für die meisten Installationen genutzt.
- **Cat 8**: 1600-2000 MHz bis zu 25 Gbit/s oder auch 40 Gbit/s auf 30 m. Meist Einsatz in Rechenzentren.
- **Kupferkabel**: Einfache Handhabung, wird für Etagenverkabelung benutzt, da Endnutzer keinen Glasfaseranschluss haben.

### Fernwartung

#### VNC
VNC steht für Virtual Network Computing. VNC-basierte Software nutzt das plattformunabhängige Remote Framebuffer Protocol. VNC zeigt den Bildschirminhalt eines entfernten Geräts (Server) auf dem lokalen Rechner (Client) an. Tastatur- und Maus-Eingaben können an den Client gesendet werden. Implementierungen sind beispielsweise RealVNC oder TightVNC.

#### RDP
Steht für Remote Desktop Protocol. RDP ist ein von Microsoft entwickeltes Netzwerkprotokoll zur Übertragung von Bildschirminhalten und Peripheriefunktionen wie Maus, Tastatur oder Audio. Bei RDP-Sitzungen kommt eine TLS-Verschlüsselung zum Einsatz. Inzwischen sind RDP-Clients für die meisten Betriebssysteme verfügbar.

#### Clientless
Eine aktuelle Entwicklung ist der Einsatz von Clientless Remote Access. Ein Vorteil ist, dass hierbei auf dem entfernten Gerät keine zusätzliche Software installiert werden muss. Je nach Implementierung können beispielsweise die genannten Protokolle VNC, RDP oder SSH genutzt werden.

## Arbeits- und Geschäftsprozesse

### Marktformen

#### Monopol
Von einem Monopol spricht man, wenn der gesamte Markt für ein ökonomisches Gut nur von einem einzigen Anbieter, dem Monopolisten, bedient wird. Dieser kann den Monopolpreis für das Gut bestimmen.

#### Oligopol
Beherrschen dagegen einige wenige Marktteilnehmer auf Angebots- oder Nachfrageseite den Markt, handelt es sich um ein Oligopol. Es wird unterschieden zwischen Angebotsoligopol (wenig Anbieter, viele Nachfrager) und Nachfrageoligopol (geringe Anzahl Nachfrager, viele Anbieter).

#### Polypol
Viele Anbieter und viele Nachfrager.

#### Käufermarkt
Mehr Angebot als Nachfrage.

#### Marktgleichgewicht
50/50 Gleichgewichtspreis.

#### Verkäufermarkt
Mehr Nachfrage als Angebot.

### Leitungssysteme

#### Einliniensystem
Jede Stelle bezieht Weisungen von nur einer übergeordneten Stelle (Instanz).

##### Vorteile
- Eindeutige Anordnungsbefugnisse.
- Keine Kompetenzschwierigkeiten.
- Leichte Kontrollen.

##### Nachteile
- Lange Befehlswege.
- Überlastung der Geschäftsleitung.
- Schwerfällig.
- Lange Dienstwege.

#### Stabliniensystem
Zuordnung von Stabstellen: beraten und informieren, keine Anordnungsbefugnis.

##### Vorteile
- Siehe Vorteile Einliniensystem.
- Entlastung der Geschäftsleitung.
- Entscheidungsverbesserung.

##### Nachteile
- Reibereien zwischen Stab und Linie.
- Hohe Kosten.
- Trennung von Verantwortung (Linie) und Entscheidungsvorbereitung (Stab).

#### Mehrliniensystem
Eine Stelle erhält Anweisungen von mehreren übergeordneten Stellen.

##### Vorteile
- Weisung nur durch Spezialisten.
- Kurze Weisungswege.
- Entlastung der Geschäftsleitung.

##### Nachteile
- Gefahr der Kompetenzüberschreitung → Konflikte.
- Konfliktgefahr, weil mehrere Vorgesetzte.
- Hoher Koordinationsbedarf.

#### Matrissystem
Mehrdimensionale Organisationshilfe, Aufteilung der Leitungsfunktionen.

##### Vorteile
- Bereichsaufteilung.
- Kurze Kommunikationswege.
- Abdeckung von Aufgaben.
- Flexible Berücksichtigung von wettbewerbsrelevanten Aspekten.

##### Nachteile
- Hierarchie unklar.
- Dezentral – Jeder arbeitet in seinem Bereich für sich.
- Ggf. Aufgabenüberschneidung.

### Führungsstile

#### Autoritärer Führungsstil
Führungskraft schafft alle Entscheidungen. Die Mitarbeiter werden nicht in den Entscheidungsprozess mit einbezogen und sie werden nicht nach ihrer Meinung oder ihren Ideen gefragt.

#### Kooperativer Führungsstil
Der kooperative Führungsstil bzw. der demokratische Führungsstil ist einer der klassischen Führungsstile. Er zeichnet sich dadurch aus, dass die Führungskräfte und ihre Mitarbeiter als Team zusammenarbeiten. Die Entscheidungen trifft das Team also gemeinsam und jeder hat ein Mitspracherecht. Jeder soll seine Ideen, Kritik und seine Meinung äußern. Die Führungskräfte delegieren Aufgaben und Verantwortungsbereiche an ihre Angestellten, damit diese sie eigenverantwortlich erledigen.

### Rechtsformen und Wirtschaftlichkeitsüberlegungen

#### Eingetragener Kaufmann
Einfachste aller Rechtsformen, haftet mit allem.

#### GbR (Gesellschaft bürgerlichen Rechts)
Fahrgemeinschaft (Personen, die sich zusammenfinden, Wohngemeinschaft WG), Gesellschaftsvertrag, haftet mit allem.

#### OHG (Offene Handelsgesellschaft)
Gruppe von Leuten, die sich zusammengeschlossen haben (Personengesellschaft für eine Firma), alle dürfen vertreten, aber alle haften auch, Gewinn wird aufgeteilt.

#### KG (Kommanditgesellschaft)
- **Komplementär**: Darf alleine über alles entscheiden außer Verkauf der Firma, haftet privat.
- **Kommandist**: Nur Geldgeber, haftet auch nur damit.

#### GmbH (Gesellschaft mit beschränkter Haftung)
Juristische Person (Form Recht eine Person, darf Verträge machen), haftet nur mit dem Kapital, Startkapital 25.000 €.

#### AG (Aktiengesellschaft)
Börse, gibt's Aktien raus, haftet nur mit dem Geld, was du reinsteckst, Startkapital 50.000 €.

#### GmbH & Co. KG
Kombination aus beidem.

#### Unternehmensleitbild
Das Unternehmensleitbild beschreibt die Grundsätze, das Selbstverständnis eines Unternehmens. Es gibt eine Antwort auf die Frage: Was (wer) wollen wir sein? Was ist unsere Aufgabe? Was ist uns wichtig? Das könnte bei der ConSystem GmbH beispielsweise der Anspruch sein, das beste IT-Haus zu sein. Dieser Anspruch sollte sich dann im täglichen Handeln widerspiegeln. Kunden sollen innovative, flexible und offizielle Lösungen geboten werden, die einen Mehrwert für sie schaffen und zukunftsfähig sind.

#### Ökonomische Ziele
- Erhöhung des Marktanteils.
- Kostenreduktion.
- Gewinnmaximierung.
- Expansion.
- Marktführerschaft.

#### Fixkosten
Sind ein Teil des Gesamtkosten eines Unternehmens. Sie bleiben innerhalb einer bestimmten Zeit konstant und fallen unabhängig von der Beschäftigung an, z.B. Wartungs- oder Garantiekosten.

#### Variable Kosten
Bilden den zweiten Teil der Gesamtkosten und verändern sich je nach Bezugsgröße, z.B. der Beschaffung.

#### Vorteile Leasing
- Geringerer Kapitalbedarf zum Zeitpunkt der Anschaffung.
- Kreditrahmen des Unternehmens wird nicht beansprucht.
- Gleichbleibende Leasingraten ermöglichen klare Kalkulationsgrundlagen je nach Vertragsgestaltung.
- Möglichkeit von Service und Betreuung.
- Möglichkeit des Geräteaustausches bei technischen Neuerungen.
- Möglichkeit der Kaufoption nach Ablauf der Nutzungszeit.

#### Vorteile Kreditfinanzierung
Als Eigentümer komplette Verfügungsgewalt über das Gerät.
Gesamtkosten meist geringer als bei Leasing.
Keine Bindung an Grundmietzeiten oder Nutzungsfristen des Gerätes.
Eigentum = Eigentümer ist der Leasinggeber.
Besitzer = Besitzer ist der Leasingnehmer.

#### Eigenkapitalrentabilität
Gewinn * 100 / eingesetztes Kapital.

#### Wirtschaftlichkeit
Ertrag / Aufwand.

#### Produktivität
Ausbringungsmenge / Einsatzmenge.

#### Vertragsbestandteile
2 übereinstimmende Willenserklärungen (Unterschrift/Kopie, volljährig/berechtigt sein), die Übergabe, Annahme.

#### Annahme verweigern wenn
- Paket falsch adressiert.
- Paket äußerlich beschädigt.
- Anzahl der Paketstücke stimmt nicht überein.

### Weitere Themen

#### 4-Ohren-Modell
- **Sachaspekt**: Wertfrei.
- **Selbstäußerung**: Was möchtest du ausdrücken?
- **Beziehung**: Ich gebe was über die Beziehung preis.
- **Appell**: Ich rufe zu einer Handlung auf.

##### Sachebene
Ampel ist grün.

##### Selbstäußerung
Ich habe es eilig.

##### Beziehung
Du brauchst meine Hilfsstellung.

##### Appell
Gib Gas.

#### Fragen aus den AO2020 Prüfungen/Misc Stuff

##### KPI Key-Performance-Indikator
Als Key-Performance-Indikator (KPI) bezeichnet man eine Messgröße oder Kennzahl, die eine Zielgröße oder Leistungsstärke (z.B. Effizienz, Effektivität und Wirtschaftlichkeit) eines Prozesses, IT-Services oder allgemein einer Aktivität anzeigen soll. Kennzahlen werden absolut miteinander und im Zeitablauf verglichen und auch in Beziehung zu anderen Messgrößen gesetzt.

#### USV

##### 3 Arten
- **Klasse 1 VFI Online Doppelwandler**: Voltage Frequency Independent (unabhängig), schützt vor Stromausfall, Unterspannung, Überspannung, Frequenzschwankung, Oberschwingung → läuft durchgehend über Batterie und gibt gleichmäßig Strom aus.
- **Klasse 2 VI: Line Interaktive/Netz Interaktive**: Voltage Independent (unabhängig), Stromausfall, Unterspannung, Überspannung → schaltet sich bei Stromausfall und Spannungsschwankung ein.
- **Klasse 3 VFD: Offline Voltage & Frequency Dependent** (abhängig), Stromausfall mit Verzögerung 10 ms → schaltet sich nur bei Stromausfall ein.

#### DSL Arten
- **DSL**: Digital Subscriber Line.
- **VDSL**: Very High DSL.
- **SDSL**: Synchron DSL → Upload/Download gleich.
- **ADSL**: Asynchronell DSL → Download höher/Upload niedriger.
- **Modem**: Übersetzer von Analog/Digital.

#### Netzwerk Komponenten/Vererbung
- **DMZ**: Demilitarized Zone → extra Zone, die nochmal extra durch die Firewall müssen, z.B. E-Mail-Verkehr, da dort Viren etc. kommen könnten.
- **VLAN**: Virtual Local Area Network → unterschiedliche Netzwerke einrichten in einem lokalen Netzwerk, Kollisionsvermeidung, Priorisierung, mehrere Switches möglich, ohne Sicherheitsbedenken untereinander kommunizierbar.
- **Trunk**: Kommunikation zwischen VLANs über mehrere Router, siehe Bild (4 und 8 Port in dem Bild), wird beim Durchgehen getagged - wenn's rausgeht, wird's entfernt.
- **Unterschied Subnet/VLAN**: Subnet Hardware, VLAN virtuell/Software.
- **Firewall**: Besteht aus Hardware/Software, alles kann raus, nichts kann rein ohne Kontrolle, Paketfilter.
- **Proxy**: Geht über einen Stellvertreter übers Netz (VPN-Anbieter als Beispiel), Proxyregeln, Ports verbieten, Websites verbieten.

#### Einführung Software/Hardware
- **Rollout Software**:
  - Kompatibilität.
  - Neuinstallation oder Update.
  - Wie soll sie verteilt werden?
  - Zeitpunkt (Downtime / Maintenance).
- **Rollout Hardware**:
  - Datenmigration.
  - Dokumentation von Asset-Tags.
  - Kompatibilität.
  - Backups.
  - Terminabstimmung.
  - Einsatz eines Rolloutmanagers (Überwachung).

#### 6 Phasen Softwareentwicklung
- Anforderungsphase.
- Konzeptionsphase.
- Entwicklungsphase.
- Qualitätssicherungsphase.
- Releasephase.
- Wartung & Optimierungsphase.

#### Marketingkonzept
Das die Schritte beschreibt, die ein Kunde durchläuft, bevor er eine Kaufentscheidung trifft.

#### AIDA-Formel
- **Attention**: Aufmerksamkeit des Kunden generieren.
- **Interest**: Kunden am Produkt interessieren.
- **Desire**: Kunden davon überzeugen, dass er es haben will.
- **Action**: Kunde kauft sich das Produkt.

#### Eisbergmodell
Sichtbare und unsichtbare Aspekte.

#### SWOT-Analyse
- **Strengths**: Stärken.
- **Weaknesses**: Schwächen.
- **Opportunities**: Möglichkeiten.
- **Threats**: Gefahren bei einem Projekt.

#### Kickoff-Meeting
Initialmeeting, alle Mitglieder des Projekts nehmen teil.

#### Forming
Alle lernen sich kennen.

#### Storming
Konfliktphase.

#### Norming
Strukturierungsphase.

#### Performing
Hochleistungsphase.

#### Projektabschluss
- **Gegenstand der Abnahme**: Genaue Bezeichnung des abgenommenen Objekts (z.B. Bauwerk, Maschine, Software).
- **Beteiligte Personen**: Name und Funktion des Auftraggebers und Auftragnehmers sowie ggf. weiterer anwesender Personen.
- **Ort, Datum und Uhrzeit**: Ort, Datum und Uhrzeit der Abnahme.
- **Feststellungen**: Ergebnis der Abnahme (z.B. mängelfrei, mit Mängeln), Beschreibung der festgestellten Mängel.
- **Vereinbarungen**: Vereinbarte Fristen zur Behebung der Mängel, ggf. weitere Vereinbarungen.
- **Unterschriften**: Unterschriften des Auftraggebers und Auftragnehmers sowie ggf. weiterer anwesender Personen.

#### ITSupport
- **1st Level**: Erstanalyse, Weiterleitung an 2nd Level.
- **2nd Level**: Vertiefte Analyse, Weiterleitung an 3rd Level.
- **3rd Level**: Spezialisten, Hersteller.

#### Nachhaltigkeit (Green IT)
- **IMAC/R/D Zyklus**: Alle Maßnahmen, die im Lebenszyklus von Hardware-Komponenten anstehen, lassen sich unter dem Begriff IMAC/R/D (Install, Move, Add, Change, Remove and Dispose) zusammenfassen. Von den IT-Teams erfordern sie meist kurze Reaktions- und Durchführungszeiten mit hohem Ressourceneinsatz.
- **Korrektes Recyclen von IT-Produkten/Remarketing**.
- **Speicher ausbauen/löschen/schreddern**.
- **Energiesparmodus**.
- **PC runterfahren**.
- **Smartsteckdosen/Mehrfachstecker**.
- **Stromabschaltung in den Büros**.
- **Energiesparlampen**.
- **Virtualisierung**.
- **Performante Netzteile/hoher Effizienzgrad**.

#### Service-Level-Agreement / SLA
- **Angabe vom Wartungsgegenstand**: Anzahl der Systeme/Standorte.
- **Information der Dienstleistung & Einsatzzeiten**: Mo-Fr 8-16 Uhr.
- **Ansprechpartner**.
- **Angabe Mängel und Gewährleistung**.
- **Datenschutz/Sicherheit**.
- **Regelung und Haftung bei Datenverlust**.
- **Höhe der Vergütung**.
- **Laufzeit des Vertrages**.
- **Informationen zu Nebenabreden**.
- **Zusatzleistungen**: Notrufhotline, kostet extra, außerhalb der Geschäftszeiten.

#### Eventuelle Themen
- **Korrektes Recyclen von IT-Produkten/Remarketing**.
- **Speicher ausbauen/löschen/schreddern**.
- **Energiesparmodus**.
- **PC runterfahren**.
- **Smartsteckdosen/Mehrfachstecker**.
- **Stromabschaltung in den Büros**.
- **Energiesparlampen**.
- **Virtualisierung**.
- **Performante Netzteile/hoher Effizienzgrad**.

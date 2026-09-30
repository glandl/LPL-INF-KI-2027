+++
title = "Kompetenzmatrix"
weight = 1
+++

Diese Seite zeigt, wie die Projekte des Kursbuchs alle Kompetenzen des Lehrplans für das Pflichtfach „Informatik und Künstliche Intelligenz“ (9.–11. Schulstufe) abdecken. Für jede Schulstufe gibt es eine kurze Beschreibung der Projekte und eine Matrix mit dem Wortlaut des Lehrplans, der Semesterzuordnung und dem Projekt, das die Kompetenz sichert.

## Rahmen

- **Zeit:** 1 Wochenstunde, geblockt als Doppelstunde (100 min) jede zweite Woche, also **15 Blöcke pro Schulstufe**. Ferien und Ausfälle sind bereits herausgerechnet.
- **Projekte:** 3–4 Projekte pro Schulstufe mit je 3–4 Blöcken. Jedes Projekt führt zu einem sichtbaren Ergebnis.
- **Kern und Erweiterungen:** Den **Kern** bearbeiten alle Schüler:innen, er allein sichert die Kompetenzen ab. 2–3 **Erweiterungen** pro Projekt sind für schnellere oder besonders interessierte Schüler:innen gedacht und nicht kompetenzrelevant.
- **Spiralcurriculum:** Jede Schulstufe baut direkt auf der vorigen auf (10 setzt 9 voraus, 11 setzt 10 voraus).
- **Semesterzuordnung:** Das Semester im Lehrplan gilt als Default: Dort liegt der Schwerpunkt, im anderen Semester darf vorbereitet oder wieder aufgegriffen werden.
- **Hardware:** Jedes Hardware-Projekt lässt sich vollständig auch mit einem **Simulator** durchführen.
- **Werkzeuge:** Eine textbasierte Programmiersprache durchgehend über alle drei Schulstufen, dazu Markdown (9), SQL mit dateibasierter Datenbank (10) sowie HTML/CSS/JavaScript und ein kleines Webserver-Framework (11).

**Legende:** ● Kompetenz wird im Kern dieses Projekts erarbeitet · ○ Kompetenz wird aufgegriffen und vertieft

## 9. Schulstufe

**Roter Faden:** Die Messdaten aus P9.2 speisen das KI-Modell in P9.3, und P9.4 verwertet Material aus P9.1–P9.3.

### Projekte

**P9.1 Reaktionsspiel** (Blöcke 1–4)
: Die Schüler:innen bauen mit einem Mikrocontroller oder Simulator ein Reaktionsspiel oder ein Mini-Gadget mit Taster, LED und Summer. Zuerst modellieren sie das Verhalten als Zustandsdiagramm, erst danach programmieren sie es in einer textbasierten Programmiersprache.

**P9.2 Klassenklima-Station** (Blöcke 5–8)
: Ein Sensor misst Temperatur, Lautstärke oder Licht im Klassenraum und sendet die Werte über das lokale Netz an einen Klassenrechner. Die Klasse verfolgt den Weg der Daten und die beteiligten Akteur:innen, klärt, wann Messdaten personenbezogen werden, und wägt das Messintervall gegen den Energieverbrauch ab.

**P9.3 Lüften ja/nein? – Entscheidungsbaum** (Blöcke 9–12)
: Aus den eigenen Messdaten entsteht ein Entscheidungsbaum, zuerst händisch und dann per Algorithmus. Mit Trainings- und Testdaten bestimmen die Schüler:innen die Fehlerquote. Abschließend beurteilen sie ein reales KI-System nach Eignung sowie nach ethischen und inklusiven Aspekten.

**P9.4 Tech-Messe** (Blöcke 13–15)
: Jede Gruppe gestaltet eine Projektseite oder ein Poster in Markdown mit getrenntem Layout und nutzt dabei offen lizenzierte Medien korrekt. Die Aufgaben aus den eigenen Projekten werden IT-Berufsfeldern zugeordnet.

### Matrix

| ZTB | Kompetenz (Lehrplan-Wortlaut) | Sem. | P9.1 | P9.2 | P9.3 | P9.4 |
| --- | --- | --- | :---: | :---: | :---: | :---: |
| 01 | den Weg von Daten von der Erfassung bis zur Analyse untersuchen und benennen, von welchen Akteurinnen und Akteuren sie zu welchen Zwecken genutzt und erfasst werden. | WS+SS | | ● | ○ | |
| 02 | Algorithmen in einer textbasierten Programmiersprache anhand einfacher Anwendungen umsetzen. | WS+SS | ● | | | |
| 03 | einfache KI-Modelle mit Hilfe eines Algorithmus erstellen, anwenden sowie bewerten und KI-Systeme hinsichtlich ihrer Eignung sowie ethischer und inklusiver Aspekte beurteilen. | WS+SS | | | ● | |
| 05 | die Grundidee lokaler Netzwerke sowie einfache Protokolle erklären und ein Gerät eigenständig in ein lokales Netzwerk einbinden. | WS+SS | | ● | | |
| 08 | digitale Artefakte unter Berücksichtigung der Trennung zwischen Form und Inhalt erstellen, anpassen und unter Berücksichtigung von geistigem Eigentum verantwortungsvoll weiterverwenden. | WS+SS | | | | ● |
| 09 | reale Objekte oder Situationen zustandsbasiert und ablauforientiert abstrahieren und modellieren. | WS+SS | ● | | | |
| 10 | die Sphären der Privatheit nach DSGVO beschreiben und im Kontext der eigenen Lebenswelt ihr Verhalten begründen. | WS+SS | | ● | | |
| 11 | erklären, welche technischen Faktoren (zB Rechenleistung, Datenübertragung, Speicherung) den Energie- und Ressourcenverbrauch digitaler Systeme beeinflussen und Systeme nachhaltig gestalten. | WS+SS | | ● | | |
| 11 | zentrale Berufsfelder der Informatik und der Informationstechnik beschreiben, typische Aufgaben zuordnen und erklären, wo Informatik und KI im (Berufs-)Alltag und in der Gesellschaft eine Rolle spielt. | WS+SS | | | | ● |

## 10. Schulstufe

**Roter Faden:** Das Gerät aus P10.1 liefert die Daten für P10.2. WS = Blöcke 1–7, SS = Blöcke 8–15.

### Projekte

**P10.1 Smart Home im Schuhkarton** (Blöcke 1–3, WS)
: Die Schüler:innen konfigurieren einen Mikrocontroller oder Simulator mit Sensoren und Aktoren und machen ihn übers Netzwerk steuerbar. Sie untersuchen das Systemverhalten, indem sie Schwellwerte, Rückmeldungen und Reaktionszeiten variieren.

**P10.2 Das Gerät lernt** (Blöcke 4–7, WS)
: Sensor- oder Gestendaten werden in geeigneten Datenstrukturen abgelegt (Liste, Dictionary, Tabelle). Ein Perzeptron wird schrittweise erarbeitet, zuerst auf Papier und dann im Code, und steuert anschließend das Gerät. Ein kurzer, handlungsorientierter Durchlauf zum Clustering (z. B. k-Means mit 2D-Punkten) zeigt den Umgang mit unbeschrifteten Daten.
: *Zeitkritisch:* 2–3 Blöcke für das Perzeptron, Clustering nur kurz.

**P10.3 Unsere eigene Plattform** (Blöcke 8–11, SS)
: Für ein Mini-Soziales-Netzwerk sind die Anforderungen als User Stories sowie als Use-Case- und Klassendiagramm vorgegeben und werden nachvollzogen. Die Klasse leitet daraus ein Datenmodell ab, formuliert SQL-Abfragen und führt Tabellen zusammen. Parallel geht es um den Aufbau von Plattformen und Identitätssystemen, um gesellschaftliche Teilhabe und um die EU-Richtlinien zu KI.

**P10.4 Geheimbotschaften & Erklärvideo** (Blöcke 12–15, SS)
: Die Schüler:innen verschlüsseln Nachrichten händisch mit einer einfachen symmetrischen Chiffre (z. B. XOR oder Vigenère) und erarbeiten anhand kleiner Zahlenbeispiele asymmetrischen Schlüsseltausch (z. B. Diffie-Hellman) oder Verschlüsselung und Signaturen (z. B. RSA). Sie vergleichen Authentifizierungsverfahren (Passwort, zweiter Faktor, E-Government-ID) und wägen dabei Sicherheit gegen Nutzbarkeit ab. Das Ergebnis ist ein barrierearmes multimediales Artefakt für eine selbst gewählte Zielgruppe.

### Matrix

| ZTB | Kompetenz (Lehrplan-Wortlaut) | Sem. | P10.1 | P10.2 | P10.3 | P10.4 |
| --- | --- | --- | :---: | :---: | :---: | :---: |
| 01 | einfache Datenmodellierung sowie Abfragen durchführen und Daten aus Datenbeständen zusammenführen. | SS | | | ● | |
| 02 | Algorithmen unter Verwendung geeigneter Datenstrukturen implementieren. | WS | | ● | | |
| 03 | grundlegende Verfahren des maschinellen Lernens anhand geeigneter Algorithmen schrittweise durchführen und deren Funktionsweisen erklären. | WS | | ● | | |
| 04 | Rechnersysteme mit Peripherie, Sensoren oder Aktoren sowie grundlegender Netzwerkfunktionalität konfigurieren und für lebensweltliche Aufgaben einsetzen. | WS | ● | | | |
| 06 | einfache interaktive Systeme bauen sowie deren Systemverhalten durch Variation von Eingaben und Rückmeldungen untersuchen und erklären. | WS | ● | | | |
| 07 | Anforderungen an Software- oder technische Systeme in natürlicher Sprache sowie einfachen grafischen Notationen nachvollziehen. | SS | | | ● | |
| 08 | multimediale Artefakte mit unterschiedlichen Zugängen bzgl. Gruppen von Benutzerinnen und Benutzern (auch unter Berücksichtigung von Inklusion) erzeugen und die verwendeten Prinzipien begründen. | SS | | | | ● |
| 10 | unterschiedliche symmetrische und asymmetrische Verschlüsselungs- und Authentifizierungsverfahren anwenden und erklären, sowie Vor- und Nachteile in Bezug auf Sicherheit, Nutzbarkeit und Privatsphäre in unterschiedlichen gesellschaftlichen und rechtlichen Kontexten begründet abwägen. | SS | | | | ● |
| 11 | erklären, wie digitale Infrastrukturen (zB Identitätssysteme, Plattformen, eGovernment-Dienste, Soziale Medien) technisch aufgebaut sind und gesellschaftliche Teilhabe ermöglichen oder begrenzen, sowie die Chancen und Risiken digitaler Infrastrukturen begründet bewerten. | SS | | | ● | |

## 11. Schulstufe

**Roter Faden:** Der Assistent wird in P11.2 entworfen und in P11.3 gebaut. WS = Blöcke 1–8, SS = Blöcke 9–15.

### Projekte

**P11.1 Blick in die KI** (Blöcke 1–4, WS)
: Die Forwardpropagation eines Mini-Netzes wird zuerst händisch oder in einer Tabellenkalkulation durchgerechnet und dann im Code umgesetzt. Die Schüler:innen testen generative KI systematisch und dokumentieren Fehler und Verzerrungen. Eine Übersicht „Welches Verfahren für welches Problem?“ greift auf die Verfahren aus der 9. und 10. Schulstufe zurück. Zum Abschluss reflektiert die Klasse die Auswirkungen von KI auf die Arbeitswelt.

**P11.2 Ein Assistent für alle** (Blöcke 5–8, WS)
: Die Klasse skizziert ein Informationssystem für die Schule, das die Interessen verschiedener Gruppen unter ethischen und inklusiven Gesichtspunkten berücksichtigt. Sie vergleicht Interaktionsformen und baut in schnellen Runden Papierprototypen. In einem fokussierten Beobachtungsauftrag (≈ 1 Block) vergleichen die Schüler:innen zwei vorgegebene Demo-Anwendungen – einen einzelnen Datenabruf (z. B. eine Seite, die bei jedem Klick neu lädt) und einen Videoanruf mit dauerhafter Verbindung – indem sie die Netzwerkverbindung kurz unterbrechen und beobachten, was jeweils passiert. Daraus leiten sie ab, welche technischen Voraussetzungen (Wiederholung, Zeitüberschreitung, Wiederverbindung) für eine zuverlässige Nutzung nötig sind.

**P11.3 Der Assistent geht online** (Blöcke 9–12, SS)
: Ein Teil des Entwurfs aus P11.2 entsteht als kleine Web-App. Ausgangspunkt ist eine vorgegebene, fehlerhafte Startversion, deren Code korrigiert und verbessert wird. Dabei trennen die Schüler:innen Client- und Serveranteile und passen das bestehende Layout an. Beim Debuggen hängender Codeabschnitte stellt sich die Frage, ob ein Programm jemals fertig wird oder nur lange braucht; daran lernen sie das Halteproblem als Beispiel für ein nicht berechenbares Problem kennen.

**P11.4 Datendetektive** (Blöcke 13–15, SS)
: Die Schüler:innen lernen die Prinzipien von OSINT kennen und leiten aus dem eigenen (oder einem fiktiven) Datenfußabdruck neue Informationen ab. In einem Ratespiel suchen sie zu zweit einen Namen in einer sortierten Liste (z. B. Klassenliste oder Telefonbuch): Eine Person antwortet nur mit „früher“ oder „später“ im Alphabet. Einmal wird der Reihe nach geraten (linear), einmal immer in der Mitte des verbleibenden Bereichs (binär); die Anzahl der nötigen Fragen wird verglichen. Mit vorgegebenem Code für lineare sowie rekursive und iterative binäre Suche testen sie dieselbe Idee an einer größeren Datenmenge und messen die Laufzeit.

### Matrix

| ZTB | Kompetenz (Lehrplan-Wortlaut) | Sem. | P11.1 | P11.2 | P11.3 | P11.4 |
| --- | --- | --- | :---: | :---: | :---: | :---: |
| 02 | gegebene Programmcodes bei Bedarf verbessern/korrigieren. | SS | | | ● | |
| 02 | Algorithmen anhand einfacher Laufzeitabschätzungen vergleichen (rekursive und nicht rekursive) sowie ein Beispiel für ein nicht berechenbares Problem benennen. | SS | | | ● | ● |
| 03 | grundlegende Funktionsweisen neuronaler Netze und generativer KI erklären, deren Ergebnisse (wie auch Fehler und Verzerrungen) analysieren sowie Auswirkungen von KI auf die Arbeitswelt reflektieren. | WS | ● | | | |
| 03 | KI-Anwendungsbereiche vergleichen und begründen, welches Verfahren für einen gegebenen Problemtyp geeignet ist. | WS | ● | | | |
| 05 | unterschiedliche Modelle für Netzwerk-Kommunikation erklären (zB zustandslos/verbindungsorientiert) sowie netzbasierte Dienste analysieren und begründet beurteilen, welche technischen Voraussetzungen für eine zuverlässige Nutzung erforderlich sind. | WS | | ● | | |
| 06 | Interaktionsformen mit Computersystemen beschreiben und vergleichen sowie deren Nutzung für diverse Benutzergruppen begründet einordnen. | WS | | ● | | |
| 08 | einfache webbasierte Anwendungen gestalten, client- und serverseitige Anteile unterscheiden und bestehende Webartefakte gezielt anpassen. | SS | | | ● | |
| 10 | Prinzipien der Open Source Intelligence (OSINT) erläutern, sowie aus dem eigenen Datenfußabdruck neue Informationen ableiten. | SS | | | | ● |
| 11 | skizzenhaft Informatiksysteme unter Berücksichtigung unterschiedlicher vorgegebener Interessen und menschlicher Bedürfnisse gestalten, unter anderem unter ethischen und inklusiven Gesichtspunkten. | WS | | ● | | |

## Überblick

| Schulstufe | Projekte | Blöcke | Kompetenzen abgedeckt |
| --- | --- | --- | --- |
| 9 | P9.1–P9.4 | 15 | 9 / 9 |
| 10 | P10.1–P10.4 | 15 | 9 / 9 |
| 11 | P11.1–P11.4 | 15 | 9 / 9 |
| **Summe** | **12** | **45** | **27 / 27** |

# PLAN – Projektplanung Informatik und KI (9.–11. Schulstufe)

Ziel: Für jede Schulstufe 3–4 Projekte, die gemeinsam alle 9 Kompetenzen der Schulstufe abdecken, plus eine Kompetenzmatrix (`planning/KOMPETENZMATRIX.md`).

## Rahmenbedingungen (festgelegt)

- **Zielgruppe:** Handreichung für alle Schulen, daher **produktneutral**: keine Produkt-, Marken- oder Dienstnamen, nur allgemeine Gerätebezeichnungen (z. B. „WLAN-fähiger Mikrocontroller“, „Simulator“).
- **Umfang des Ergebnisses:** kurze Projektbeschreibungen + Kompetenzmatrix. Keine Detail- oder Stundenplanung.
- **Zeit:** 1 Wochenstunde, geblockt als **Block** (Doppelstunde, 100 min) jede zweite Woche → **15 Blöcke pro Schulstufe**, netto (Ferien/Ausfälle bereits abgezogen), kein Puffer eingeplant.
- **Projekte:** 3–4 pro Schulstufe (≈ 4–5 Blöcke je Projekt). Projekte müssen im Zeitrahmen realistisch bleiben.
- **Semesterzuordnung:** gilt als Default. Schwerpunkt im angegebenen Semester, Vorbereitung/Wiederaufgreifen im anderen Semester erlaubt. Matrix zeigt Semester und tatsächliche Blöcke.
- **Hardware:** jedes Hardware-Projekt muss vollständig auch mit einem **Simulator** durchführbar sein (Fallback für Schulen ohne Geräte).
- **Vorgehen:** erst `planning/` fertigstellen (PLAN, Matrix), danach die Website (`content/`) umbauen und `selbstlernen/` auflösen.

- **Differenzierung:** jedes Projekt hat einen **Kern** (alle; sichert die Kompetenz) und 2–3 **Erweiterungen** (für schnellere/interessierte Schüler:innen). Keine vorgeschriebenen Rollen oder Themenvarianten.

- **Kein Selbstlernen:** jede Kompetenz wird im Kern eines Projekts innerhalb der Blöcke erarbeitet. Kleine Vorbereitungen zwischen den Blöcken sind erlaubt, dürfen aber nicht kompetenzrelevant sein; das wird in der Handreichung nicht eigens erwähnt. Auch „theorielastige“ Kompetenzen (Laufzeit/Berechenbarkeit, Netzwerkmodelle, Berufsfelder, Interaktionsformen) brauchen eine praktische Phase im Projekt.

- **Spiralcurriculum (strikt):** jede Schulstufe baut direkt auf der vorigen auf (10 setzt 9 voraus, 11 setzt 10 voraus). Keine eingeplante Wiederholung; Einstiegsjahr/Quereinsteiger:innen sind nicht Teil der Planung.

- **Sprachen/Werkzeuge:** Kategorien statt Produkte; offene Standards (HTML, CSS, JavaScript, SQL, Markdown) dürfen genannt werden. Empfehlung: eine textbasierte Programmiersprache durchgehend über alle drei Schulstufen.
  - 9: textbasierte Programmiersprache (Mikrocontroller oder Simulator), Markdown/Textformate für Artefakte
  - 10: + SQL mit dateibasierter Datenbank
  - 11: + HTML/CSS/JavaScript + kleines Webserver-Framework der Programmiersprache

- **Sprache:** PLAN und Kompetenzmatrix auf Deutsch (englische Fassung erst beim Website-Umbau). Kompetenz-Wortlaut ohne die Fußnoten-Ziffern aus dem Lehrplan; keine Spalte dafür.

## Projekte 9. Schulstufe (festgelegt)

Roter Faden: Daten aus P9.2 speisen die KI in P9.3; P9.4 verwertet Material aus P9.1–P9.3.

| # | Projekt (Arbeitstitel) | Blöcke | Kern | Kompetenzen |
| --- | --- | --- | --- | --- |
| P9.1 | Reaktionsspiel | 1–4 | Mikrocontroller/Simulator als Reaktionsspiel oder Mini-Gadget (Taster, LED, Summer); erst Zustandsdiagramm, dann Programm | 02, 09 |
| P9.2 | Klassenklima-Station | 5–8 | Sensor misst Temperatur/Lautstärke/Licht, sendet über das lokale Netz an einen Klassenrechner; Datenweg und Akteure, personenbezogene Daten, Messintervall vs. Energie | 05, 01, 10, 11a |
| P9.3 | Lüften ja/nein? – Entscheidungsbaum | 9–12 | Entscheidungsbaum aus eigenen Messdaten, händisch und per Algorithmus; Trainings-/Testdaten, Fehlerquote; Beurteilung eines realen KI-Systems (Eignung, Ethik, Inklusion) | 03, (01) |
| P9.4 | Tech-Messe | 13–15 | Projektseite/Poster in Markdown mit getrenntem Layout, offen lizenzierte Medien korrekt genutzt; Projektaufgaben IT-Berufsfeldern zuordnen | 08, 11b |

Erweiterungen (Beispiele): Highscore (P9.1), zweiter Sensor/Dashboard (P9.2), Baumtiefe vs. Überanpassung (P9.3), barrierearme Variante (P9.4).

## Projekte 10. Schulstufe (festgelegt)

WS = Blöcke 1–7, SS = Blöcke 8–15. Roter Faden: das Gerät aus P10.1 liefert die Daten für P10.2.

| # | Projekt (Arbeitstitel) | Blöcke | Kern | Kompetenzen |
| --- | --- | --- | --- | --- |
| P10.1 | Smart Home im Schuhkarton | 1–3 | Mikrocontroller/Simulator mit Sensoren und Aktoren konfigurieren, übers Netzwerk steuerbar machen; Systemverhalten durch Variation von Schwellwerten, Rückmeldungen und Reaktionszeit untersuchen | 04, 06 |
| P10.2 | Das Gerät lernt | 4–7 | Sensor-/Gestendaten in geeigneten Datenstrukturen (Liste/Ringpuffer, Wörterbuch, Tabelle); Perzeptron schrittweise (Papier, dann Code) steuert das Gerät; Clustering (z. B. k-Means mit 2D-Punkten) für unbeschriftete Daten | 03, 02 |
| P10.3 | Unsere eigene Plattform | 8–11 | Vorgegebene Anforderungen (User Stories + Use-Case-/Klassendiagramm) für ein Mini-Soziales-Netzwerk nachvollziehen, Datenmodell, SQL-Abfragen, Tabellen zusammenführen; Aufbau von Plattformen/Identitätssystemen, Teilhabe, EU-Regeln zu KI | 07, 01, 11 |
| P10.4 | Geheimbotschaften & Erklärvideo | 12–15 | Symmetrische/asymmetrische Verschlüsselung und Signatur selbst anwenden, Authentifizierungsverfahren vergleichen (Passwort, zweiter Faktor, E-Government-ID); Sicherheit vs. Nutzbarkeit; Ergebnis als barrierearmes multimediales Erklärstück für eine gewählte Zielgruppe | 10, 08 |

Zeitkritisch: P10.2 – Perzeptron 2–3 Blöcke, Clustering nur als kurzer, handlungsorientierter Durchlauf.

## Projekte 11. Schulstufe (festgelegt)

WS = Blöcke 1–8, SS = Blöcke 9–15. Roter Faden: P11.2 entwirft den Assistenten, P11.3 baut ihn.

| # | Projekt (Arbeitstitel) | Blöcke | Kern | Kompetenzen |
| --- | --- | --- | --- | --- |
| P11.1 | Blick in die KI | 1–4 | Forwardpropagation eines Mini-Netzes händisch/Tabellenkalkulation, dann Code; generative KI systematisch testen, Fehler/Verzerrungen dokumentieren; Übersicht „welches Verfahren für welches Problem“ (Rückgriff auf 9 und 10); KI und Arbeitswelt reflektieren | 03a, 03b |
| P11.2 | Ein Assistent für alle | 5–8 | Informationssystem für die Schule für verschiedene Interessengruppen skizzieren (ethisch, inklusiv); Interaktionsformen vergleichen, Papierprototypen; Datenverkehr eines zustandslosen und eines verbindungsorientierten Dienstes mitschneiden und vergleichen, Voraussetzungen für zuverlässige Nutzung ableiten | 11, 06, 05 |
| P11.3 | Der Assistent geht online | 9–12 | Ausschnitt des Entwurfs als kleine Web-App auf Basis einer vorgegebenen, fehlerhaften Startversion; Code korrigieren/verbessern; Client-/Serveranteile trennen, bestehendes Layout anpassen | 08, 02a |
| P11.4 | Datendetektive | 13–15 | OSINT-Prinzipien, Ableitungen aus dem eigenen (oder fiktiven) Datenfußabdruck; lineare vs. binäre Suche, rekursiv vs. iterativ, Laufzeiten messen; Halteproblem als nicht berechenbares Problem | 10, 02b |

Zeitkritisch: P11.2 – Netzwerkteil als fokussierter Messauftrag (≈ 1 Block), Papierprototypen in schnellen Runden.

## Offene Entscheidungen

- Projektideen je Schulstufe

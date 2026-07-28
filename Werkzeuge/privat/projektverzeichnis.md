# 2Rat – Büro für Radverkehrsplanung
*Armin Jung · Radverkehrsplaner EIPOS · www.2rat.org*

---

# 2Rat – Gesamt-Projektverzeichnis

**Stand:** 27.07.2026
**Anzahl Vorhaben (konsolidiert):** 36
**Quellen:** Fassung 05.05.2026 · Tool-Updates 12.07.2026 (RadPlan v3.2, Zuständigkeiten v16) · Förderung-Projekt · 📮 Meldung Tool-Portal 19.07.2026 (Accessibility-Deployment) · **Live-Repo-Analyse 19.07.2026** (Portal-index, LICENSES, projekt-check, karte-prototyp) · 📮 Meldungen Tool-Portal 27.07.2026 (RAD-Lab-Rückmeldungen, Zuständigkeiten v17, Vergabe-Assistent v3, Projekt-Check)

> **Lebendiges Arbeitsdokument – EINZIGE gültige Fassung.** Diese Datei lebt im Repo **`2Rat/2Rat.github.io`** unter `Werkzeuge/privat/projektverzeichnis.md`. Claude holt sich zu Sitzungsbeginn die Live-Version von GitHub (raw-URL) – das Projektwissen enthält keine Kopie mehr. Update-Workflow: Claude liefert die komplette Datei neu → Armin committet. Fertig.

---

# 🔥 AKUT – Das zählt jetzt

| Wann | Was | Wo |
|---|---|---|
| ~~15.07.2026~~ **abgelaufen** | JGF FL1 – Skizzen-Frist verstrichen, Ausgang nachtragen (Skizze eingereicht?) | Förderung-Projekt |
| **31.07.2026 (4 Tage!)** | JGF FL2 – Antrags-Frist | Förderung-Projekt |
| **30.09.2026** | FRL-NMOB Jahres-Stichtag **+ AGFK-Kennenlern-Tools laufen ab (Upsell-Chance!)** **+ RAD-Lab-Testrunde endet** | Förderung / Tool-Portal |
| prüfen | RadPlan Pro: 19.07.-Deployment (JSON-Pipeline) erfolgt – ist die Login-bereinigte Version mit drin? | RadPlan-Projekt |
| prüfen | Rotierte Codes (Kommandozentrale + RadPlan): Werte stehen vermutlich in den Chats der jeweiligen Claude-Projekte (Tool-Portal / RadPlan Pro) → dort raussuchen und in den **Passwortmanager** übertragen, bevor die 30-Tage-Session abläuft | Tool-Portal / RadPlan |
| offen | Projekt-Check: fachliche Letztabnahme durch AGFK-Prüfer (§ 12 StVZustG) → danach Übergabe + Rechnung | Tool-Portal |
| **jetzt** | Projekt-Check: Freigabe für **Referenznennung + Zitate** aus der Testrunde bei der AGFK-SL einholen – solange die Testphase läuft, ist es eine Formsache | Tool-Portal |
| **offen** | Upload: Vergabe-Assistent v3 nach `Werkzeuge/kunden/` (Projekt-Check und Zuständigkeiten sind live und gegengeprüft) | Tool-Portal |
| **erledigt 27.07.** | `quoteAGFK` geprüft – Feld ist sachlich falsch, muss vor jeder Auslieferung raus (→ 2.3) | Tool-Portal |
| nach Urlaub | Gespräch AGFK-SL: Nutzungsrechte Projekt-Check, Pflegevereinbarung, Lizenzmodell übrige Tools → Eckpunktepapier liegt vor | Tool-Portal / BÜRO 2Rat |
| wartet | AGFK-Logo → dann `agfk-sl/`-Tool-Varianten erstellen (Routing steht bereits) | Tool-Portal |

**Geklärt 19.07.:** Demo läuft als Freemium OHNE Code unter `2rat.org/demo/` (alter Code bleibt deaktiviert) ✓ · Wadgassen-Pilot → abgeschlossen mit Abschlussbericht ✓ · Wadern → keine Rückmeldung, ruht ✓ · AGFK-Code → neue Lizenz bis 15.05.2027 aktiv ✓ · Admin-Code → **aktiv** als „2Rat intern"-Lizenz (Hash identisch, im Array bis 2099 verlängert) ✓ – veralteten Kommentar im Array bei Gelegenheit löschen

---

## Inhalt

1. Kundenprojekte & Akquise
2. Tools & Werkzeuge-Portal
3. QGIS-Plugins & Planungs-Werkzeuge
4. Apps & Digitale Produkte
5. Marketing & Website
6. Infrastruktur
7. Büro-intern & Behörden
8. Archiv / Verworfen
9. Claude-Projekt-Landkarte
10. URL-Verzeichnis
11. Fristen
12. Statusverteilung
13. Zugänge & Codes

---

# 1️⃣ Kundenprojekte & Akquise

### 1.1 Radverkehrsplanung Hostenbach
- **Kunde / Partner:** Gemeinde Wadgassen
- **Zweck:** Gesamtprojekt – LP1 (Konzept Hauptachse Schulstraße → Weberstraße → Turnerstraße, 13 Maßnahmenblätter) ✓ · Klimabeirat-Präsentation ✓ · LP2-Angebot liegt vor.
- **Status:** LP1 **abgeschlossen & bezahlt** ✓ (19.07.2026) · LP2 ungewiss (Haushaltslage der Kommune)
- **Nächster Schritt:** LP2 ruhen lassen; zum Haushalt 2027 gezielt nachfassen
- **Details (Beträge, Ansprechpartner):** → Projekt „Hostenbach" / Rechnungsablage

### 1.2 Radwegemelder-Pilot Wadgassen
- **Kunde / Partner:** Gemeinde Wadgassen
- **Zweck:** Erste Saarland-Pilotkommune mit echter Bürgerbeteiligung – Referenzprojekt für die Kommunen-Kampagne (1.4).
- **Status:** **abgeschlossen** ✓ – Abschlussbericht erstellt und an die Gemeinde versendet, positives Feedback; Rechnung bezahlt. Umsetzungsphase in Aussicht (haushaltsabhängig).
- **Nächster Schritt:** Konzept-Check-Auswertung starten (→ 2.4); Wadgassen ist zum RAD-Lab eingeladen (→ 2.13); als Referenz in der Radherbst-Kampagne nutzen

### 1.3 Radverkehrskonzept Stadt Wadern
- **Kunde / Partner:** Stadt Wadern
- **Zweck:** Umsetzungsbegleitung zum bestehenden RVK plus Radwegemelder als niederschwelliger Vorlauf.
- **Status:** ruht (nach Mai-Rats-Sitzung keine Rückmeldung erhalten)
- **Nächster Schritt:** Aktiv nachhaken – ggf. gekoppelt an die Radherbst-Kampagne (1.4) als Wiedereinstieg

### 1.4 Kommunen-Kampagne „Radherbst 2026"
- **Kunde / Partner:** intern (Vertriebskampagne)
- **Zweck:** Systematische Ansprache der saarländischen Kommunen mit dem Radwegemelder. Frühjahrsaktion verschoben → Neuauflage als „Radherbst 2026" (Aktionszeitraum 01.09.–15.10.2026, inkl. Europäische Mobilitätswoche).
- **Status:** vorbereitet (Material fertig, wartet auf Versand)
- **Nächster Schritt:** Versand Anfang August 2026 (vorher Flyer-Datum aktualisieren, Test-Versand)
- **Details (Preise, Strategie, Material, Rechtliches):** → Claude-Projekt **„BÜRO 2Rat"** (Session-Notizen)

### 1.5 AGFK-SL Kunde (Tool-Lizenzierung) 🎉
- **Kunde / Partner:** AGFK-SL (geschaeftstelle@agfk-sl.de)
- **Zweck:** Erste kommerzielle Tool-Lizenzierung. **Beauftragt ist ausschließlich der Projekt-Check** – Abrechnung: Pauschale bei Übergabe, **Zahlung noch nicht erfolgt** (fällig bei Übergabe). Die fachliche Letztabnahme erfolgt durch einen externen Prüfer, **den die AGFK bezahlt** (→ Lizenz „AGFK Honorarkraft"). Die übrigen 4 Tools (Fördermittel-Finder, Zuständigkeiten, VwV-StVO 2025, Vergabe-Assistent) sind **kein Auftrag**, sondern Kennenlern-Zugang befristet bis 30.09.2026.
- **Lizenzen im Portal:** „AGFK Saarland" bis 15.05.2027 · „AGFK Honorarkraft" (externer Prüfer) bis 27.05.2027 (5-Tool-Suite)
- **Status:** läuft (Auftrag Projekt-Check; Übergabe + Zahlung ausstehend)
- **Offen (27.07.2026):** Nutzungsrechte am Projekt-Check ungeklärt (gemeinsame Leistung – Fachinhalt AGFK-SL, Umsetzung 2Rat) · Freigabe für Referenznennung und Zitate aus der Testrunde steht aus · Abgrenzung Mängelbeseitigung / Weiterentwicklung noch nicht schriftlich · Entscheidung Beistellung oder Lizenzierung der übrigen Werkzeuge
- **Achtung Vertriebsargument:** Der erhöhte Fördersatz von 90 % taugt **nicht** als Argument für eine AGFK-Mitgliedschaft – er hängt an der Finanzschwäche der Kommune, nicht an der Mitgliedschaft (→ 2.3). Falls das gegenüber Geschäftsstelle oder Mitgliedern schon so angeklungen ist, beiläufig geraderücken, bevor es in eine Präsentation oder ein Rundschreiben wandert.
- **Grundlage:** Eckpunktepapier „Eckpunkte zur vertraglichen Regelung" (27.07.2026) erstellt – Leistungsarten, Rechte, Referenz, Pflege · Inhalte → Projekt „BÜRO 2Rat"
- **Nächster Schritt:** Referenzfreigabe kurzfristig einholen; Gespräch nach der Urlaubszeit; vor 30.09.2026 Upsell-Gespräch zu den Kennenlern-Tools; nach AGFK-Logo: `agfk-sl/`-Varianten erstellen

---

# 2️⃣ Tools & Werkzeuge-Portal
*Alle unter: www.2rat.org/Werkzeuge · aktuell 5 Tools im Portal*

### 2.1 Werkzeuge-Portal (Login & Lizenzverwaltung)
- **Kunde / Partner:** eigen (Infrastruktur)
- **Zweck:** Passwortgeschütztes Portal auf GitHub Pages (`Werkzeuge/index.html`). **Architektur seit 06–07/2026:** zentrales `TOOLS`-Array (6 Tools) + `PATHS`-Routing in Varianten-Ordner (`kunden/` = Vollversionen · `agfk-sl/` = AGFK-Fassungen, noch leer · `demo/` = Trial) + `LICENSES` mit `target` (Ordner-Variante), `tools`-Filter (Sichtbarkeit pro Kunde) und `toolExpires` (Ablauf pro Einzeltool). Neue Kundenlizenz = eine Zeile im Array.
- **Repo:** github.com/2Rat/2Rat.github.io *(Ordner `Werkzeuge/`, Tools in `Werkzeuge/kunden/`)*
- **Status:** läuft / produktiv · **Accessibility-Politur (7 Dateien) am 19.07.2026 deployed & verifiziert – Live-Stand = gepatchter Stand** · **Sichtbarkeitsschutz seit 11.07.2026:** `noindex` in allen `kunden/`-Tools + `robots.txt` im Repo-Root (sperrt `Werkzeuge/`, Cockpit, `cmd` für Suchmaschinen) · Wartungskalender-Dokument vorhanden (→ Tool-Portal-Projekt)
- **Nächster Schritt:** veralteten Array-Kommentar zur intern-Lizenz löschen; nach AGFK-Logo: `agfk-sl/`-Varianten befüllen

### 2.2 Zuständigkeiten Radverkehr Saarland
- **Kunde / Partner:** eigen (Tool, lizenzpflichtig)
- **Zweck:** Interaktive Entscheidungshilfe zur Bestimmung der zuständigen Behörde (Gemeinde / Landkreis / Regionalverband / Land-LfS) nach StVO/SaarlStrG.
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/zustaendigkeiten.html`)*
- **Status:** live · **v16 (12.07.2026)** – Fahrradstraße auf ERA-Werte korrigiert (4,00 m Fahrgasse statt alter MuLöS-2016-Wert 4,10 m), MuLöS BW als „ergänzend, im Saarland nicht verbindlich" gekennzeichnet · v15 (11.07.): Saarbrücken-Baulast-Fix § 47 Abs. 1 SaarlStrG, StVB-Kontakte, Ergebnis-Vermerke, Cross-Links · **Update 19.07.2026 deployed:** Fahrradzonen-Sonderfall, ODR-Ergänzungen · **v17 (27.07.2026) deployed & live verifiziert:** Fachjargon entschärft (Vzul/DTV ausgeschrieben), Abstellanlagen-Logik nach drei Fallgruppen differenziert, Aufsichtsbehörde und Mitteilungspflicht bei reinen Baumaßnahmen ausgeblendet, LfS-Kontaktbox bei Bundes-/Landesstraßen ergänzt, Kontaktdaten aller Kreise geprüft (Neunkirchen war die Zulassungsstelle statt der Straßenverkehrsbehörde), Direktlinks zu den Kontaktseiten
- **Nächster Schritt:** Pflege bei VwV-Änderungen; Update als Pflege-Nachweis an AGFK-SL; Kontaktdaten Saarpfalz-Kreis noch unbestätigt

### 2.3 Fördermittel-Finder (FRL-NMOB-Rad-Fuß)
- **Kunde / Partner:** eigen (Tool, lizenzpflichtig)
- **Zweck:** Entscheidungshilfe zur Förderkulisse für Rad- und Fußverkehrsmaßnahmen mit Praxis-Hinweisen pro Fördergegenstand. Mit Hinweis-Block: Abdeckung nur Landesförderung NMOB (inkl. Stadt-und-Land), Verweis auf Bundestöpfe (Kommunalrichtlinie, Bike+Ride, Junge Generation Fahrrad).
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/foerdermittel-finder.html`)*
- **Status:** live · **v2 (11.07.2026)** – Ergebnis-Vermerke, Cross-Links, einheitlicher Disclaimer · **Update 19.07.2026 deployed:** Förderquoten nach FRL-NMOB korrigiert (Schule/Kita 90/95 %, Landesinteresse bis 100 %, neue Quoten-Datenfelder) · **Freemium-Demo live** unter `2rat.org/demo/` (frei ohne Code, 3 von 13 Fördergegenständen, Export gesperrt)
- **Zwei Live-Fassungen (geprüft 27.07.2026):** `Werkzeuge/kunden/foerdermittel-finder.html` und `demo/foerdermittel-finder.html` – getrennte Dateien mit eigenem Datenblock, **Fördersätze derzeit deckungsgleich**. Jede inhaltliche Änderung muss in beiden gepflegt werden. Die 1-Byte-Leiche `demo/foerdermittelfinder.html` (ohne Bindestrich) liegt weiterhin im Repo.
- **AGFK-Entwürfe:** liegen nur lokal, `Werkzeuge/agfk-sl/` im Repo weiterhin nicht vorhanden. Die beiden Entwurfsfassungen weichen voneinander ab – **eine davon ohne 2Rat-Urhebervermerk in der Fußzeile** („© AGFK-SL" statt „Entwickelt und gepflegt von 2Rat"). Verbindliche Fassung vor dem Portal-Umbau festlegen; Stand-Angaben (03/2026 bzw. 2026) veraltet.
- ⚠️ **`quoteAGFK` geprüft (27.07.2026) – Ergebnis: sachlich falsch.** Der erhöhte Satz von bis zu 90 % gilt für **finanzschwache** Gemeinden, Städte und Landkreise; die Finanzschwäche stellt das Landesverwaltungsamt als Kommunalaufsichtsbehörde fest und muss bei Antragstellung nachgewiesen werden. Die Systematik lautet bis zu 75 % / 90 % bei Finanzschwäche / bis zu 100 % bei besonderem Landesinteresse. **Eine AGFK-Mitgliedschaft ist in keiner Fundstelle Fördervoraussetzung.** Das Feld enthält in jeder Zeile exakt den höchsten alternativen Satz der Kundenfassung (mal Finanzschwäche, mal Schule/Kita, bei den Abstellanlagen beide zusammengefasst) – also eine Umetikettierung, keinen eigenen Fördertatbestand.
- **Folge:** `quoteAGFK` ersatzlos streichen. Die AGFK-Fassung darf keinen eigenen Datenstand führen, sondern nur eine Co-Branding-Hülle über demselben Datenblock sein – sonst wiederholt sich das Auseinanderlaufen wie bei den Kontaktdaten in Projekt-Check und Zuständigkeiten. **Risiko entschärft:** Die Entwürfe waren nie live, Kunden- und Demofassung sind korrekt.
- **Änderungsvorschläge v3 (noch nicht beauftragt):** Antragsfrist dynamisch statt statisch („30.09.2026 – noch X Tage", nach dem Stichtag automatisch aufs Folgejahr) – dabei die Ausnahme **31.05.2030** berücksichtigen, sonst zeigt das Werkzeug 2030 ein falsches Datum · Hinweis „Zuwendungsantrag vor Vorhabenbeginn" als rotes Warnfeld nach oben ziehen. Beides in `kunden/` **und** `demo/`.
- **Nächster Schritt:** `quoteAGFK` aus den AGFK-Entwürfen entfernen; Aktualisierung bei neuer FRL-Fassung

### 2.4 Konzept-Check
- **Kunde / Partner:** eigen (Service-Erweiterung)
- **Zweck:** Bürgermeldungen werden gegen kommunale RVK-Maßnahmen abgeglichen und liefern eine priorisierte Handlungsempfehlung.
- **Status:** läuft (Tool live) · Wadgassen-Pilot ist beendet → Auswertung kann starten
- **Nächster Schritt:** JETZT: PDF-Maßnahmentabellen importieren, Abgleich rechnen, Bericht für den Gemeinderat Wadgassen

### 2.5 Mängelmelder
- **Kunde / Partner:** eigen (Tool-Portal)
- **Zweck:** Niederschwelliges Meldetool für Mängel an Radinfrastruktur, wird in Tool-Portal integriert.
- **Status:** in Entwicklung
- **Nächster Schritt:** Funktionsumfang & Datenablage finalisieren

### 2.6 Demo- und Trial-Versionen (Freemium)
- **Kunde / Partner:** eigen (Vertrieb)
- **Zweck:** Freemium-Demos als Kaufanreiz, verlinkt über Startseiten-Sektion „Testen".
- **Status:** **Fördermittel-Finder-Demo live** unter **`2rat.org/demo/`** (Repo-Root, NICHT `Werkzeuge/demo/`) seit 11.07.2026 – **frei zugänglich ohne Code** (3 von 13 Fördergegenständen offen, Export gesperrt, „Vollversion anfragen"-CTA). Alter Demo-Vollzugangs-Code am 24.06.2026 deaktiviert – für die Freemium-Demo irrelevant. *(Geklärt 19.07. per Repo-Analyse.)*
- **Nächster Schritt:** 3 weitere Demos erstellen (geplant); 1-Byte-Datei-Leiche `demo/foerdermittelfinder.html` (ohne Bindestrich) löschen

### 2.7 Hash-Generator (Admin-Tool)
- **Kunde / Partner:** intern
- **Zweck:** Lokales HTML-Werkzeug zur Erzeugung von SHA-256-Hashes für neue Kundenzugänge; nicht veröffentlicht. Kunden-/Cockpit-Codes werden hierüber erzeugt und extern abgelegt.
- **Status:** läuft · 19.07.: neues `hash-generator-lokal.html` mit zwei Modi (Portal-normalisiert / RadPlan-exakt) – **bleibt offline, nie ins Repo**
- **Nächster Schritt:** —

### 2.8 Lizenzkonzept-Dokument
- **Kunde / Partner:** intern
- **Zweck:** DOCX mit 2Rat-Briefkopf, dokumentiert Lizenzbedingungen und Konditionen für die Tool-Nutzung.
- **Status:** abgeschlossen
- **Nächster Schritt:** —

### 2.9 Vergabe-Assistent Saarland
- **Kunde / Partner:** eigen (Tool, Portal)
- **Zweck:** Entscheidungshilfe zu Vergabeverfahren für Kommunen nach Vergabeerlass Saarland 2025.
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/vergabe-assistent.html`)*
- **Status:** live (Portal-Tool) · **v2 (11.07.2026)** – § 3-VgV-Hinweis, Ergebnis-Vermerke, Cross-Links · **v3 (27.07.2026) gepatcht, Deployment offen:** Einleitungs- und Vergabebeschluss als Pflichtschritte (Hauptsatzung / Zuständigkeitsordnung), EU-Schwellenwert wird im Ergebnistext ausdrücklich benannt, damit erkennbar ist, warum bei 250.000 € Bau kein EU-Verfahren greift · Schwellenwerte 2026/27 waren bereits aktuell hinterlegt
- **Nächster Schritt:** v3 hochladen; Pflege bei Erlass-Änderungen; **Anfang 2028: neue EU-Schwellenwerte einpflegen** (aktuelle Werte gelten bis 31.12.2027)

### 2.10 Förderrichtlinien & Förder-Matcher
- **Kunde / Partner:** eigen (Tool, Portal)
- **Zweck:** Übersicht der Förderrichtlinien (FRL-NMOB-Rad-Fuß, Bundesaufruf JGF u. a.) mit Matcher zur Zuordnung Maßnahme → Fördertopf.
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/foerderrichtlinien.html`)*
- **Status:** live (Portal-Tool)
- **Nächster Schritt:** Pflege der Fristen (JGF FL1 15.07. / FL2 31.07. / FRL-NMOB 30.09.); inhaltliche Weiterarbeit im Projekt „2RAT Förderung Radverkehr"

### 2.11 Projekt-Check Radverkehr ⭐
- **Kunde / Partner:** eigen (Tool, Portal) · **von AGFK-SL beauftragt** (Pauschale bei Übergabe, Zahlung ausstehend – siehe 1.5)
- **Zweck:** „Wer muss an den Tisch?" – laienfreundlicher Wegweiser auf Basis der **AGFK-Zuständigkeitslandkarte**: 3-Schritte-Wizard (Vorhaben → Lage → Sonderfälle, ~9 Falltypen von Radweg über Fahrradstraße bis Schulweg) → liefert Federführung, einzubindende Stellen, Prüfpunkte und einen **kopier-/downloadbaren Projektvermerk**. Fahrradstraße/-zone-Logik nach § 12 StVZustG. Verlinkt auf die übrigen Portal-Tools. Datengrundlage: AGFK-SL (Stand 06/2026).
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/projekt-check.html`)*
- **Status:** live (Portal-Tool, im Dashboard als Einstiegs-Tool erstgereiht) · erstes beauftragtes Tool 🎉 · **Patch 27.07.2026 deployed & live verifiziert (byte-identisch):** Rollentrennung Bau-/Tiefbauamt (Baulastträger) gegenüber Bauhof/Betriebshof (Umsetzung), Kontaktblock an die Zuständigkeiten angeglichen (derselbe Neunkirchen-Fehler steckte auch hier), LfS-Kontaktbox ergänzt, Stand vereinheitlicht
- **Soll Referenzprojekt werden** – dafür nötig: Freigabe zur Nennung der AGFK-SL, Bildschirmfotos, Zitate aus der Testrunde, Fortbestand des 2Rat-Hinweises in der Fußzeile
- **Version-2-Themen (nicht beauftragt, geparkt):** Freitextfeld „Vorhaben / Standort" für den Projektvermerk · Verknüpfung mit dem GeoPortal Saarland beim Zusatzfaktor „fremde Grundstücke" · schlanke Kartenansicht auf OSM-Basis. **Ausgeschlossen:** ZORA (Login, räumlich begrenzter Nutzungsvertrag, personenbezogene Daten) und eingebettete Google-Maps-Ansicht (Datenschutz)
- **Bekannte Schwächen:** keine Versionsnummer im Kopf (als einziges Werkzeug) · Kommunen-, Kreis- und Kontaktdaten liegen doppelt in Projekt-Check und Zuständigkeiten – jede Behördenänderung kostet zwei Commits, in der Pflege einkalkulieren
- **Nächster Schritt:** Versionsnummer vergeben; Pflege bei Änderung der AGFK-Datengrundlage · ⚠️ fachliche Letztabnahme durch AGFK-bezahlten externen Prüfer (v. a. § 12 StVZustG) **noch offen** → Voraussetzung für Übergabe + Abrechnung

### 2.12 Karten-Prototyp „Kommune per Klick"
- **Kunde / Partner:** eigen (Experiment)
- **Zweck:** Leaflet/OSM-Prototyp – Kommune per Klick auf der Karte wählen. Liegt in `kunden/`, ist aber **nicht** im TOOLS-Array (nicht im Dashboard sichtbar).
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/karte-prototyp.html`)*
- **Status:** Experiment / Prototyp
- **Nächster Schritt:** **Nicht löschen** – ist der naheliegende Baustein für den Kartenwunsch aus der RAD-Lab-Testrunde (→ 2.11 Version-2-Themen). Entscheidung an das Gespräch über die Pflegevereinbarung koppeln.

### 2.13 RAD-Lab (Beta-Test-Programm)
- **Kunde / Partner:** ausgewählte Tester aus Armins Umfeld
- **Zweck:** Qualitätssicherung vor breiter Vermarktung – ausgewählte Tools werden an bekannte Personen verteilt, die sie auf Herz und Nieren prüfen. Getestet werden: Fördermittel-Finder, Zuständigkeiten, Projekt-Check (Lizenz „RAD-Lab", `target:"test"`).
- **Status:** läuft – Testzugänge am **11.07.2026 an 10 Personen aus 6 Kommunen + 1 privat** verschickt (u. a. Wadgassen als frischer Referenzkunde eingeladen; Namensliste → Tool-Portal-Projekt, nicht öffentlich) · 19.07.: Tool-Umfang final auf 3 Werkzeuge reduziert, deployed & live verifiziert · Testrunden-Einladung erstellt (Fokus: Fachtest Projekt-Check im Zusammenspiel mit Zuständigkeiten + Fördermittel-Finder – Methode zur Zuständigkeitsklärung Radverkehr Saarland)
- **Rückmeldungen 27.07.2026:** zwei ausführliche Rückmeldungen eingegangen und vollständig abgearbeitet (drei Werkzeuge betroffen: Zuständigkeiten v17, Vergabe-Assistent v3, Projekt-Check). Trefferquote hoch – ein gemeldeter Punkt war sachlich unzutreffend (EU-Vergaberecht bei 250.000 € Bau), hat aber eine echte Verständlichkeitslücke aufgedeckt.
- **Nächster Schritt:** Freigabe zum Zitieren der Rückmeldungen einholen (→ 2.11 Referenzprojekt); RAD-Lab-Code-Wert in Passwortmanager dokumentieren (Doku-Lücke); weiteres Feedback einsammeln bis 30.09.2026; danach Lizenz-Zeile entfernen; zweite Testrunde entscheiden

---

# 3️⃣ QGIS-Plugins & Planungs-Werkzeuge

### 3.1 QGIS-Plugin „Radverkehrsplaner ANALYSE"
- **Kunde / Partner:** intern (Eigenentwicklung)
- **Zweck:** Maßnahmenblatt-Generator. VwV-StVO-2025-Update vorbereitet – beide Anordnungswege werden automatisch je nach Straßentyp erzeugt.
- **Status:** stabil (Update vorbereitet)
- **Nächster Schritt:** Beim nächsten QGIS-Auftrag: VwV-Begründungslogik integrieren **+ ERA-Konsistenz-Check** (Abgleich mit RadPlan v3.2 / Zuständigkeiten v16)

### 3.2 QAD-basierte Entwurfsplanung
- **Kunde / Partner:** intern (LP2-Werkzeug)
- **Zweck:** Detail- und Markierungspläne mit QAD-Plugin auf WMS-Grundlagen Saarland (DOP20rgb, DGK).
- **Status:** vorbereitet
- **Nächster Schritt:** Erstanwendung an kurzer Straße testen (Turnerstraße oder Schulstraße)

### 3.3 Begründungsgenerator VwV-StVO 2025
- **Kunde / Partner:** intern (HTML-Tool, perspektivisch für Kommunen/andere Planer)
- **Zweck:** Browser-Tool zur Erzeugung rechtssicherer Fahrradstraßen-Begründungen aus Straßenparametern inkl. Förderprognose 75 % / 95 %.
- **Status:** läuft (Prototyp v0.2)
- **Nächster Schritt:** Beim nächsten QGIS-Auftrag: Prüflogik verfeinern **+ ERA-Konsistenz-Check** (wie 3.1)

### 3.4 VwV-StVO 2025 – Maßnahmen-Übersicht
- **Kunde / Partner:** intern → jetzt Portal-Tool *(`Werkzeuge/kunden/vwv-stvo-2025.html`)*
- **Zweck:** Interaktive HTML-Wissensbasis aller VwV-Neuerungen mit Alt-Neu-Vergleich.
- **Status:** live (als Tool im Werkzeuge-Portal eingebunden) · **Update 19.07.2026 deployed:** Rechtsgrundlagen Fahrradstraße/-zone, § 45 Abs. 1i StVO · Umfang: 13 Maßnahmen in 4 Kategorien, je mit Rechtsgrundlage, Randnummern, fertigem Begründungstext und drei Textgeneratoren (Ordnungsamt / Rat / Bürger)
- **Änderungsvorschläge v3 (noch nicht beauftragt, Durchsicht 27.07.2026):** Maßnahme **Bussonderfahrstreifen mit Radverkehrsfreigabe** fehlt – gehört zur selben Reform (Wegfall der 20-Busse-Mindestgrenze, Radverkehr im Benehmen mit den Verkehrsunternehmen zulassen) und ist bei engen Hauptstraßen oft die einzige realistische Lösung · Maßnahme **Gehwegparken** fehlt (BVerwG-Urteil vom 06.06.2024, in die VwV übernommen) · **Fassungsdatum im Kopf ergänzen** (StVO-Novelle 11.10.2024, VwV-StVO rechtskräftig 10.04.2025) · optional Schulstraßen als Praxishinweis beim Verkehrsversuch
- **Nächster Schritt:** Pflege bei VwV-Änderungen

### 3.5 Inkscape-Planrahmen-Vorlage A1/A2/A3
- **Kunde / Partner:** intern (wiederverwendbar)
- **Zweck:** SVG-Planrahmen im 2Rat-Design für QGIS-Drucklayouts, skalierbar.
- **Status:** abgeschlossen
- **Nächster Schritt:** —

---

# 4️⃣ Apps & Digitale Produkte

### 4.1 Velomeld / Radwegemelder
- **Kunde / Partner:** eigen (Kernprodukt)
- **Zweck:** Bürger-App, öffentliche Karte und Dashboard für anonyme Radwege-Meldungen – Kerntechnologie aller Kommunen-Einsätze.
- **Repos:** github.com/2Rat/velomeld · github.com/2Rat/velomeld-pro
- **Status:** läuft
- **Nächster Schritt:** Repo-Split abschließen; Status-Management für Meldungen einführen

### 4.2 RadPlan Pro
- **Kunde / Partner:** eigen (Profi-Tool)
- **Zweck:** GPS-Felderfassung für Planer mit ERA-Konformitätscheck via Claude API. PWA, Daten nur lokal (localStorage), KI-API mit User-eigenem Anthropic-Key.
- **Repo:** github.com/2Rat/radplan-pro *(privat)* · **Live:** radplan-pro.netlify.app
- **Status:** läuft · **v3.2 (12.07.2026)** – Regelwerks-Hierarchie Saarland (ERA maßgeblich, MuLöS BW nur ergänzend), DTV→Kfz/h-Umrechnung im KI-Prompt, Tempo bis 100 (außerorts), max_tokens 2000, Datenschutz auf Netlify korrigiert. Impressum-Mail ✓ erledigt. · 19.07.: **bereinigte Version** (neuer Login, localStorage-Überlauf-Schutz), Zugang rotiert · 19.07.: **KI-Analyse auf JSON-first-Pipeline umgestellt** (Whitelist-Validierung, editierbares Feld „Fachliche Bewertung"), EXIF-GPS/Datum-Bugs behoben, **Bericht-Paket-Export** (JSON inkl. Fotos) – **deployed, Testphase läuft**
- **Festlegung:** Das KI-Feld heißt in allen Dokumenten immer **„Fachliche Bewertung"**; bei fachlich falscher KI-Analyse wird das Feld vor Export vollständig überschrieben (KI liefert Entwurf, Verantwortung bleibt beim Planer)
- **Begleit-Skill:** Claude-Skill `radplan-bericht` erstellt & paketiert – erzeugt DOCX-Berichte aus dem Bericht-Paket (Ortstermin / Maßnahmenblätter / Hybrid; 2Rat- und Neutral-Modus); Karten dort aktuell Platzhalter, Testphase
- **Nächster Schritt:** Testphase abschließen (Feldtest inkl. Probe-KI-Analyse mit DTV-Wert); danach: Import-Button für Bericht-Paket, KI-Prompt-Erweiterung (Klassifikation Strecke/Querung/Knoten), Karten-Workflow klären; Linien-Erfassung verfeinern

### 4.3 Schulweg-Detektive
- **Kunde / Partner:** Jugendpflege Kirkel + 2Rat (Technik)
- **Zweck:** Gesamtwerk – DSGVO-konforme PWA + Play-Store-App (v1.2.1.0), Web-Auswertungskarte v2, Erklärfilm, Info-Doku, Begleitmaterial.
- **Repo:** github.com/2Rat/schulweg-check
- **Status:** live
- **Nächster Schritt:** Bis Sept. 2026: Android-Entwicklerbestätigung für PWA-APK prüfen; Erklärfilm-Verlinkung von Hauptseite

### 4.4 Bauhof-App
- **Kunde / Partner:** eigen (Nebenprodukt)
- **Zweck:** Standalone-PWA für Inventar- und Aufgabenverwaltung im Bauhof.
- **Repo:** github.com/2Rat/bauhof-inventar · **Live:** bauhof-2rat.netlify.app
- **Status:** live (funktional ruhend)
- **Nächster Schritt:** —

---

# 5️⃣ Marketing & Website

### 5.1 2rat.org Website
- **Kunde / Partner:** eigen
- **Zweck:** Außendarstellung 2Rat – Produktseiten, Kontakt, Kampagnenboxen.
- **Repo:** github.com/2Rat/2Rat.github.io
- **Status:** läuft (Pflege)
- **Nächster Schritt:** —

### 5.2 Radwegemelder-Ergebnis-Cockpit
- **Kunde / Partner:** eigen (öffentliche Produkt-Ausgabe)
- **Zweck:** Ergebnis-Ansicht (Login-geschützt), gespeist vom Radwegemelder-Dashboard. Projekt-Kacheln pro Kommune. Eng gekoppelt an Vorhaben 4.1.
- **URL:** `2rat.org/cockpit.html`
- **Status:** live
- **Nächster Schritt:** —

### 5.3 Fahrradfrühling-Film „Speichenerwachen"
- **Kunde / Partner:** eigen (Marketing-Asset)
- **Zweck:** Animierter Awareness-Kurzfilm, eingebettet auf 2rat.org.
- **Status:** live
- **Nächster Schritt:** Bei Bedarf MP4-Konvertierung via OBS Studio

### 5.4 Persönliche Kommandozentrale
- **Kunde / Partner:** eigen (Büro-intern)
- **Zweck:** Privates HTML-Cockpit mit Schnellzugriff auf alle Claude-Projekte, Web-Tools, Repos, Fristen und Wartet-auf-Liste. SHA-256-Login, 30-Tage-Session, QR-Code-Funktion je Kachel.
- **Zugang:** Code → Passwortmanager · **am 19.07.2026 sicherheitsbereinigt und Zugang rotiert** (alter Code ungültig); Kurz-URL `2rat.org/cmd/` als Weiterleitung live
- **URLs:** `2rat.org/cmd` · `2rat.org/Werkzeuge/privat/`
- **Status:** live
- **Nächster Schritt:** Bei Status-Änderungen Datei-Update; Fristen mit diesem Verzeichnis synchron halten

---

# 6️⃣ Infrastruktur

### 6.1 GitHub-Organisation `2Rat` – Repo-Übersicht
- **Kunde / Partner:** intern
- **Zweck:** Zentrale Code-Infrastruktur (Tools, Plugins, Apps, Website).
- **URL:** github.com/2Rat
- **Status:** aktiv
- **Nächster Schritt:** Repo-Struktur sauber halten

| # | Repository | Sichtbarkeit | Bezug |
|---|---|---|---|
| 1 | `2Rat/2Rat.github.io` | öffentlich | Website · Cockpit · Kommandozentrale · Portal + alle Portal-Tools |
| 2 | `2Rat/velomeld` | – | 4.1 Bürger-App |
| 3 | `2Rat/velomeld-pro` | – | 4.1 Profi-Variante |
| 4 | `2Rat/radplan-pro` | privat | 4.2 RadPlan Pro |
| 5 | `2Rat/bauhof-inventar` | – | 4.4 Bauhof-App |
| 6 | `2Rat/schulweg-check` | – | 4.3 Schulweg-Detektive |
| 7 | `2Rat/umzugsplan` | – | *(privat/Test)* |

---

# 7️⃣ Büro-intern & Behörden

### 7.1 2Rat Büroverwaltung / Stammdatendokument
- **Kunde / Partner:** intern
- **Zweck:** Claude-Projekt „BÜRO 2Rat" mit Stammdaten, Vorlagen, Projekt-Register. Logo liegt vor (`Logo_2Rat_clean__1_.png`).
- **Offizielle Büro-E-Mail:** `fahr2rat@gmail.com` · **Anschrift:** Ritter-von-Hagen-Str. 13, 66822 Lebach
- **Status:** im Aufbau
- **Nächster Schritt:** Steuernummer / IBAN eintragen; einheitliche Briefkopf-DOCX-Vorlage erstellen (offen)

### 7.2 Steuer / Finanzamt-Status freiberuflich
- **Kunde / Partner:** Finanzamt
- **Zweck:** Bestätigung als freischaffender Planer (§ 18 EStG, ohne USt.).
- **Status:** offen
- **Nächster Schritt:** Freiberuflich-Bestätigung abwarten; Steuernummer eintragen

### 7.3 Rundfunkbeitrag Betriebsstätte
- **Kunde / Partner:** ARD/ZDF/DR – Az 651 028 117 5
- **Zweck:** Pflichtanmeldung; voraussichtlich beitragsfrei nach Ziff. 1.3 (Büro in Privatwohnung).
- **Status:** abgeschlossen (Anmeldung 20.04.2026)
- **Nächster Schritt:** Bescheid abwarten

---

# 8️⃣ Archiv / Verworfen

### 8.1 QGIS-Plugin „Radverkehrsplaner CONSTRUCT"
- **Status:** verworfen (zu instabil, ersetzt durch QAD)

---

# 9️⃣ Claude-Projekt-Landkarte

| Claude-Projekt | Behandelte Vorhaben | Rolle |
|---|---|---|
| **Projektübersicht 2Rat** | Pflege und Fortschreibung **dieses Verzeichnisses** – zentrale Statusübersicht aller Vorhaben. Hier laufen alle 📮-Meldungen aus den Werkstatt-Projekten ein. | **HUB** |
| **BÜRO 2Rat** | Zentrales Büro- und Steuerungsprojekt: Stammdaten, Vorlagen, Steuer, Standardtexte · 1.4 Radherbst-Kampagne · Geschäftsinterna (Preise, Strategie, Rechtliches, Session-Notizen) – **bleiben dort, nicht ins öffentliche Verzeichnis!** | Büro & Vertrieb |
| **Hostenbach** | 1.1 · 3.2 QAD · 3.5 Planrahmen | Kundenprojekt |
| **2Rat Radwegemelder Webseite Dashboard** | 4.1 · 1.2 · Supabase | Produkt-Hauptprojekt |
| **Schulweg-Detektive** | 4.3 | Kooperation Kirkel |
| **Plugin-Entwicklung (ANALYSE)** | 3.1 · 3.3 Begründungsgenerator | Werkzeugentwicklung |
| **2Rat Werkzeuge / Tool-Portal** | 2.1–2.10 · 3.4 · 1.5 AGFK | Tool-Vertrieb |
| **2RAT Förderung Radverkehr** | Förder-Wissensbasis · JGF-Fristen · Zuarbeit zu 2.10 | Förderberatung |
| **2rat.org Website** | 5.1 · 5.2 · 5.3 · 5.4 | Marketing |
| **Mobilitätsstationen Wadgassen** | eigenes Kundenprojekt | Kundenprojekt |
| **RadPlan Pro** (Cowork) | 4.2 RadPlan Pro · Skill `radplan-bericht` | App-Entwicklung |
| **Kirkel-Projekte** (Bauhof · Castle Race · Bike and Ride) | 4.4 u. a. | Arbeit Gemeinde Kirkel |

> **Regel:** Vor jedem Arbeiten kurz prüfen, in welchem Projekt man ist. Verzeichnispflege → „Projektübersicht 2Rat" · Kaufmännisches und Administratives → „BÜRO 2Rat" · Werkzeugarbeit → „2Rat Werkzeuge / Tool-Portal". Tools → Tool-Portal · Radwegemelder → Kernprodukt · Förderfragen → Förderung-Projekt.

---

# 🔟 URL-Verzeichnis

### Webseiten & Tools

| Ressource | URL |
|---|---|
| 2Rat Website | www.2rat.org |
| Werkzeuge-Portal (Login) | www.2rat.org/Werkzeuge |
| Tool-Dateien (Vollversionen) | www.2rat.org/Werkzeuge/kunden/ *(6 Tools + Karten-Prototyp)* |
| AGFK-Varianten (geplant) | www.2rat.org/Werkzeuge/agfk-sl/ *(noch leer)* |
| Freemium-Demos (ohne Code) | www.2rat.org/demo/ |
| **Kommandozentrale** | **www.2rat.org/cmd** |
| Radwegemelder-Ergebnisse | www.2rat.org/cockpit.html |
| Velomeld (Bürger-App) | 2rat.org/velomeld/#home |
| RadPlan Pro | radplan-pro.netlify.app |
| Bauhof-App | bauhof-2rat.netlify.app |
| Schulweg-Detektive (PWA) | 009aj.github.io/schulweg-check/ |
| Schulweg-Detektive (Play Store) | play.google.com/store/apps/details?id=de.zweirat.schulwegdetektive |
| Schulweg-Erklärfilm | www.2rat.org/schulweg-film.html |

### Kontakte

| Ressource | Adresse |
|---|---|
| **E-Mail Büro (offiziell)** | **fahr2rat@gmail.com** |
| Anschrift | Ritter-von-Hagen-Str. 13, 66822 Lebach |
| AGFK-SL | geschaeftstelle@agfk-sl.de |

---

# 1️⃣1️⃣ Fristen

| Datum | Kontext | Aktion |
|---|---|---|
| ~~15.07.2026~~ | Förderung (JGF FL1) | Skizzen-Frist **verstrichen** – Ausgang nachtragen |
| **31.07.2026** | Förderung (JGF FL2) | Antrags-Frist – nur junge Menschen bis 25, Raumbezug Bildungs-/Jugendeinrichtungen! |
| **Anfang Aug 2026** | 1.4 Radherbst-Kampagne | Versand (Flyer-Datum aktualisieren → Test → Batches) |
| **25.08.2026** | 1.4 Radherbst-Kampagne | Rückmelde-Frist der Kommunen |
| **01.09.–15.10.2026** | 1.4 Radherbst-Kampagne | Aktionszeitraum (EMW 16.–22.09.) |
| **30.09.2026** | Förderung (FRL-NMOB) | Jahres-Stichtag |
| **30.09.2026** | 1.5 AGFK-SL | Kennenlern-Tools laufen ab (`toolExpires`) → vorher Upsell-Gespräch |
| **30.09.2026** | 2.1 Tool-Portal | RAD-Lab-Testrunde endet (→ 2.13) – Lizenz-Zeile entfernen |
| **Sep 2026** | 4.3 Schulweg-Detektive | Android-Entwicklerbestätigung für PWA-APK prüfen |
| **15.05.2027** | 1.5 AGFK-SL | Lizenz „AGFK Saarland" läuft ab → Verlängerung |
| **27.05.2027** | 1.5 AGFK-SL | Lizenz „AGFK Honorarkraft" läuft ab |

| **Anfang 2028** | 2.9 Vergabe-Assistent | Neue EU-Schwellenwerte einpflegen (aktuelle Werte gelten bis 31.12.2027) |

**Geklärt 19.07.:** AGFK-Code (neue Lizenz bis 15.05.2027) · Wadgassen-Pilot (abgeschlossen) · Wadern (ruht, nachhaken) · Demo-Code (Freemium ohne Code, geklärt)

**Geklärt 27.07.:** Kontaktdaten der Straßenverkehrsbehörden geprüft (Neunkirchen korrigiert) · EU-Schwellenwerte 2026/27 im Vergabe-Assistenten bereits aktuell · Kartenwunsch aus der Testrunde eingeordnet (ZORA und Google-Maps-Embed ausgeschlossen, GeoPortal Saarland als Ersatz)

**Ohne festes Datum:** Gespräch mit der AGFK-SL nach der Urlaubszeit – Nutzungsrechte Projekt-Check, Pflegevereinbarung, Lizenzmodell übrige Werkzeuge (Grundlage: Eckpunktepapier vom 27.07.2026)

---

# 1️⃣2️⃣ Statusverteilung

| Status | Anzahl | Vorhaben |
|---|---|---|
| **läuft / live / produktiv / stabil / aktiv** | 22 | 1.5, 2.1, 2.2, 2.3, 2.4, 2.7, 2.9, 2.10, **2.11**, **2.13**, 3.1, 3.3, 3.4, 4.1, 4.2, 4.3, 4.4, 5.1, 5.2, 5.3, 5.4, 6.1 |
| **teils läuft** | 1 | 1.1 *(LP1 bezahlt ✓ · LP2 ungewiss)* |
| **abgeschlossen** | 4 | **1.2**, 2.8, 3.5, 7.3 |
| **vorbereitet** | 3 | 1.4, 2.6 *(Demo-Konzept)*, 3.2 |
| **in Entwicklung / im Aufbau** | 2 | 2.5, 7.1 |
| **Experiment / Prototyp** | 1 | 2.12 |
| **ruht** | 1 | 1.3 |
| **offen** | 1 | 7.2 |
| **verworfen** | 1 | 8.1 |

---

# 1️⃣3️⃣ Zugänge & Codes

*Diese Datei liegt im **öffentlichen** Repo – deshalb hier keine Klartext-Codes. Alle Code-Werte: → Passwortmanager (KeePassXC/Bitwarden).*

| Zugang | Code-Wert | Gültig bis / Status |
|---|---|---|
| **Kommandozentrale** (`2rat.org/cmd`) | → Passwortmanager *(Wert vermutlich im Chat des Tool-Portal-Projekts – übertragen!)* | **rotiert 19.07.2026** (alter Code ungültig) |
| **„2Rat intern"** (Portal, Vollzugang) | → Passwortmanager *(= Admin-Code aus 05/2026)* | im Array bis 2099 · **aktiv** ✓ |
| AGFK Saarland (Portal) | → Passwortmanager | **15.05.2027** · Projekt-Check dauerhaft, übrige 4 Tools bis 30.09.2026 |
| AGFK Honorarkraft (Portal) | → Passwortmanager | **27.05.2027** · 5-Tool-Suite |
| RAD-Lab (Portal, Beta-Test → 2.13) | → Passwortmanager *(Wert dort noch nachtragen!)* | 30.09.2026 · danach Lizenz-Zeile entfernen |
| Demo Tool-Portal | *(deaktiviert)* | am 24.06.2026 auskommentiert (Altlast ohne `tools`-Filter) |
| Cockpit (`cockpit.html`) | → Passwortmanager | — |
| RadPlan Pro | → Passwortmanager *(Wert vermutlich im Chat des RadPlan-Pro-Projekts – übertragen!)* | **rotiert 19.07.2026** |

**Passwortmanager-Verweise:** Gmail · Supabase (Velomeld) · Netlify · GitHub-Token · Anthropic API-Key · kundenspezifische Cockpit-Codes (via Hash-Generator erzeugt, extern abgelegt)

---

# 🛠 Pflegeanleitung – die 3 Regeln

1. **Eine Datei, eine Wahrheit – und die liegt auf GitHub.** `Werkzeuge/privat/projektverzeichnis.md` im Repo `2Rat/2Rat.github.io` ist die einzige gültige Fassung. Claude liest zu Sitzungsbeginn die raw-URL: `https://raw.githubusercontent.com/2Rat/2Rat.github.io/main/Werkzeuge/privat/projektverzeichnis.md`. Im Projektwissen liegt **keine** Kopie (veraltet sonst).
2. **Updates immer über Claude, immer komplett.** „Claude, Vorhaben X ist jetzt Y" → Claude holt die Live-Version, patcht, liefert die komplette Datei → Armin committet. Auch 📮-Meldungen aus anderen Claude-Projekten laufen so ein – dieses Dokument ist der zentrale Ablageplatz, die anderen Projekte sind Werkstätten.
3. **Wöchentlicher Blick auf 🔥 AKUT.** Der Block oben ist das Erste, was man sieht. Fristen erledigt → raus. Neues Dringendes → rein. Wenn AKUT länger als 8 Zeilen wird: aufräumen. **Keine Klartext-Codes in diese Datei** – das Repo ist öffentlich.
4. **Geschäftsinterna bleiben draußen.** Preise, Vertriebsstrategie, Rechtliches, Kundeninterna → nur im Projekt „BÜRO 2Rat". Ins zentrale Verzeichnis wandern ausschließlich **Status + Fristen + Verweis** – nie Inhalte.

---

*2Rat – Büro für Radverkehrsplanung · Stand: 27.07.2026*

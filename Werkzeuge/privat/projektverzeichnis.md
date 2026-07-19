# 2RAT – Büro für Radverkehrsplanung
*Armin Jung · Radverkehrsplaner EIPOS · www.2rat.org*

---

# 2RAT – Gesamt-Projektverzeichnis

**Stand:** 19.07.2026
**Anzahl Vorhaben (konsolidiert):** 36
**Quellen:** Fassung 05.05.2026 · Tool-Updates 12.07.2026 (RadPlan v3.2, Zuständigkeiten v16) · Förderung-Projekt · 📮 Meldung Tool-Portal 19.07.2026 (Accessibility-Deployment) · **Live-Repo-Analyse 19.07.2026** (Portal-index, LICENSES, projekt-check, karte-prototyp)

> **Lebendiges Arbeitsdokument – EINZIGE gültige Fassung.** Diese Datei lebt im Repo **`2Rat/2Rat.github.io`** unter `Werkzeuge/privat/projektverzeichnis.md`. Claude holt sich zu Sitzungsbeginn die Live-Version von GitHub (raw-URL) – das Projektwissen enthält keine Kopie mehr. Update-Workflow: Claude liefert die komplette Datei neu → Armin committet. Fertig.

---

# 🔥 AKUT – Das zählt jetzt

| Wann | Was | Wo |
|---|---|---|
| ~~15.07.2026~~ **abgelaufen** | JGF FL1 – Skizzen-Frist verstrichen, Ausgang nachtragen (Skizze eingereicht?) | Förderung-Projekt |
| **31.07.2026 (12 Tage!)** | JGF FL2 – Antrags-Frist | Förderung-Projekt |
| **30.09.2026** | FRL-NMOB Jahres-Stichtag **+ AGFK-Kennenlern-Tools laufen ab (Upsell-Chance!)** **+ RAD-Lab-Testrunde endet** | Förderung / Tool-Portal |
| wartet | AGFK-Logo → dann `agfk-sl/`-Tool-Varianten erstellen (Routing steht bereits) | Tool-Portal |

**Status nachziehen (Ausgang hier nicht dokumentiert):**
Wadgassen `date_to` (31.05.) · Wadern Rats-Sitzung (Mai)
**Geklärt 19.07.:** AGFK-Code → neue Lizenz bis 15.05.2027 aktiv ✓ · Demo-Code → am 24.06. bewusst deaktiviert ✓ · Admin-Code → **aktiv** als „2Rat intern"-Lizenz (Hash identisch, im Array bis 2099 verlängert) ✓ – veralteten Kommentar im Array bei Gelegenheit löschen

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
- **Kunde / Partner:** Gemeinde Wadgassen (Christian Schnadinger)
- **Zweck:** Gesamtprojekt – LP1 (Konzept Hauptachse Schulstraße → Weberstraße → Turnerstraße, 13 Maßnahmenblätter, Kostenschätzung ~205.200 €) ✓ · Klimabeirat-Präsentation ✓ · LP1-Rechnung 4.714 € · LP2-Angebot 5.214 € offen.
- **Status:** teils läuft (LP1 abgeschlossen · LP2 offen · Rechnung läuft)
- **Nächster Schritt:** Geldeingang LP1 prüfen; Entscheidung zu LP2-Beauftragung abwarten / nachfassen

### 1.2 Radwegemelder-Pilot Wadgassen
- **Kunde / Partner:** Gemeinde Wadgassen
- **Zweck:** Erste Saarland-Pilotkommune mit echter Bürgerbeteiligung – Referenzprojekt für 52-Kommunen-Akquise.
- **Status:** Laufzeit-Status prüfen (`date_to` war 31.05.2026)
- **Nächster Schritt:** Klären: verlängert oder beendet? Bei Ende: Konzept-Check-Auswertung (siehe 2.4)

### 1.3 Radverkehrskonzept Stadt Wadern
- **Kunde / Partner:** Stadt Wadern (M. Vorreiter)
- **Zweck:** Umsetzungsbegleitung zum bestehenden RVK plus Radwegemelder als niederschwelliger Vorlauf.
- **Status:** ruht
- **Nächster Schritt:** Ergebnis der Mai-Rats-Sitzung nachtragen; ggf. nachhaken

### 1.4 52-Kommunen-Outreach Saarland
- **Kunde / Partner:** intern (Vertriebskampagne)
- **Zweck:** Systematische Ansprache aller saarländischen Kommunen mit Radwegemelder + Konzept-Check, Wadgassen als Referenz.
- **Status:** vorbereitet
- **Nächster Schritt:** Anschreiben „Radsaison 2026" gemäß Excel-Liste rausschicken

### 1.5 AGFK-SL Kunde (Tool-Lizenzierung) 🎉
- **Kunde / Partner:** AGFK-SL (Irene & Nicole, geschaeftstelle@agfk-sl.de)
- **Zweck:** Erste kommerzielle Tool-Lizenzierung – **erfolgreich konvertiert:** Projekt-Check **beauftragt & bezahlt** (dauerhafte Lizenz). Übrige 4 Tools (Fördermittel-Finder, Zuständigkeiten, VwV-StVO 2025, Vergabe-Assistent) als Kennenlern-Zugang befristet bis **30.09.2026**.
- **Lizenzen im Portal:** „AGFK Saarland" bis 15.05.2027 · „AGFK Honorarkraft" bis 27.05.2027 (5-Tool-Suite)
- **Status:** läuft (zahlender Kunde)
- **Nächster Schritt:** Vor 30.09.2026 Upsell-Gespräch zu den Kennenlern-Tools; nach AGFK-Logo: `agfk-sl/`-Varianten erstellen

---

# 2️⃣ Tools & Werkzeuge-Portal
*Alle unter: www.2rat.org/Werkzeuge · aktuell 5 Tools im Portal*

### 2.1 Werkzeuge-Portal (Login & Lizenzverwaltung)
- **Kunde / Partner:** eigen (Infrastruktur)
- **Zweck:** Passwortgeschütztes Portal auf GitHub Pages (`Werkzeuge/index.html`). **Architektur seit 06–07/2026:** zentrales `TOOLS`-Array (6 Tools) + `PATHS`-Routing in Varianten-Ordner (`kunden/` = Vollversionen · `agfk-sl/` = AGFK-Fassungen, noch leer · `demo/` = Trial) + `LICENSES` mit `target` (Ordner-Variante), `tools`-Filter (Sichtbarkeit pro Kunde) und `toolExpires` (Ablauf pro Einzeltool). Neue Kundenlizenz = eine Zeile im Array.
- **Repo:** github.com/2Rat/2Rat.github.io *(Ordner `Werkzeuge/`, Tools in `Werkzeuge/kunden/`)*
- **Status:** läuft / produktiv · **Accessibility-Politur (7 Dateien) am 19.07.2026 deployed & verifiziert – Live-Stand = gepatchter Stand**
- **Nächster Schritt:** veralteten Array-Kommentar zur intern-Lizenz löschen; nach AGFK-Logo: `agfk-sl/`-Varianten befüllen

### 2.2 Zuständigkeiten Radverkehr Saarland
- **Kunde / Partner:** eigen (Tool, lizenzpflichtig)
- **Zweck:** Interaktive Entscheidungshilfe zur Bestimmung der zuständigen Behörde (Gemeinde / Landkreis / Regionalverband / Land-LfS) nach StVO/SaarlStrG.
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/zustaendigkeiten.html`)*
- **Status:** live · **v16 (12.07.2026)** – Fahrradstraße auf ERA-Werte korrigiert (4,00 m Fahrgasse statt alter MuLöS-2016-Wert 4,10 m), MuLöS BW als „ergänzend, im Saarland nicht verbindlich" gekennzeichnet
- **Nächster Schritt:** Pflege bei VwV-Änderungen; Update als Pflege-Nachweis an AGFK-SL

### 2.3 Fördermittel-Finder (FRL-NMOB-Rad-Fuß)
- **Kunde / Partner:** eigen (Tool, lizenzpflichtig)
- **Zweck:** Entscheidungshilfe zur Förderkulisse für Rad- und Fußverkehrsmaßnahmen mit Praxis-Hinweisen pro Fördergegenstand.
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/foerdermittel-finder.html`)*
- **Status:** live
- **Nächster Schritt:** Aktualisierung bei neuer FRL-Fassung

### 2.4 Konzept-Check
- **Kunde / Partner:** eigen (Service-Erweiterung)
- **Zweck:** Bürgermeldungen werden gegen kommunale RVK-Maßnahmen abgeglichen und liefern eine priorisierte Handlungsempfehlung.
- **Status:** läuft (Tool live)
- **Nächster Schritt:** Nach Wadgassen-Ende: PDF-Maßnahmentabellen importieren, Abgleich rechnen, Bericht für Gemeinderat

### 2.5 Mängelmelder
- **Kunde / Partner:** eigen (Tool-Portal)
- **Zweck:** Niederschwelliges Meldetool für Mängel an Radinfrastruktur, wird in Tool-Portal integriert.
- **Status:** in Entwicklung
- **Nächster Schritt:** Funktionsumfang & Datenablage finalisieren

### 2.6 Demo- und Trial-Versionen
- **Kunde / Partner:** eigen (Vertrieb)
- **Zweck:** Demo mit gesperrter Praxis-Box als Kaufanreiz; Trial über `target:"demo"` + befristete Lizenz.
- **Status:** Alter Demo-Code am **24.06.2026 bewusst deaktiviert** (Altlast: gab Vollzugang ohne `tools`-Filter). Neues Demo-Konzept über Portal-Architektur möglich (Lizenz mit `tools`-Filter + `demo/`-Ordner).
- **Nächster Schritt:** Bei Bedarf: `demo/`-Ordner befüllen + neuen Demo-Code MIT `tools`-Filter anlegen

### 2.7 Hash-Generator (Admin-Tool)
- **Kunde / Partner:** intern
- **Zweck:** Lokales HTML-Werkzeug zur Erzeugung von SHA-256-Hashes für neue Kundenzugänge; nicht veröffentlicht. Kunden-/Cockpit-Codes werden hierüber erzeugt und extern abgelegt.
- **Status:** läuft
- **Nächster Schritt:** —

### 2.8 Lizenzkonzept-Dokument
- **Kunde / Partner:** intern
- **Zweck:** DOCX mit 2RAT-Briefkopf, dokumentiert Lizenzbedingungen und Konditionen für die Tool-Nutzung.
- **Status:** abgeschlossen
- **Nächster Schritt:** —

### 2.9 Vergabe-Assistent Saarland
- **Kunde / Partner:** eigen (Tool, Portal)
- **Zweck:** Entscheidungshilfe zu Vergabeverfahren für Kommunen nach Vergabeerlass Saarland 2025.
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/vergabe-assistent.html`)*
- **Status:** live (Portal-Tool)
- **Nächster Schritt:** Pflege bei Erlass-Änderungen

### 2.10 Förderrichtlinien & Förder-Matcher
- **Kunde / Partner:** eigen (Tool, Portal)
- **Zweck:** Übersicht der Förderrichtlinien (FRL-NMOB-Rad-Fuß, Bundesaufruf JGF u. a.) mit Matcher zur Zuordnung Maßnahme → Fördertopf.
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/foerderrichtlinien.html`)*
- **Status:** live (Portal-Tool)
- **Nächster Schritt:** Pflege der Fristen (JGF FL1 15.07. / FL2 31.07. / FRL-NMOB 30.09.); inhaltliche Weiterarbeit im Projekt „2RAT Förderung Radverkehr"

### 2.11 Projekt-Check Radverkehr ⭐
- **Kunde / Partner:** eigen (Tool, Portal) · **beauftragt & bezahlt von AGFK-SL** (dauerhafte Lizenz, siehe 1.5)
- **Zweck:** „Wer muss an den Tisch?" – 3-Schritte-Wizard (Vorhaben → Lage → Sonderfälle, ~9 Falltypen von Radweg über Fahrradstraße bis Schulweg) → liefert Federführung, einzubindende Stellen, Prüfpunkte und einen **kopier-/downloadbaren Projektvermerk**. Verlinkt auf die übrigen Portal-Tools. Datengrundlage: AGFK-SL (Stand 06/2026).
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/projekt-check.html`)*
- **Status:** live (Portal-Tool, im Dashboard als Einstiegs-Tool erstgereiht) · erstes fremdfinanziertes Tool 🎉
- **Nächster Schritt:** Pflege bei Änderung der AGFK-Datengrundlage

### 2.12 Karten-Prototyp „Kommune per Klick"
- **Kunde / Partner:** eigen (Experiment)
- **Zweck:** Leaflet/OSM-Prototyp – Kommune per Klick auf der Karte wählen. Liegt in `kunden/`, ist aber **nicht** im TOOLS-Array (nicht im Dashboard sichtbar).
- **Repo:** github.com/2Rat/2Rat.github.io *(`Werkzeuge/kunden/karte-prototyp.html`)*
- **Status:** Experiment / Prototyp
- **Nächster Schritt:** Entscheiden: ausbauen (z.B. als Einstieg für Projekt-Check/Zuständigkeiten) oder löschen

### 2.13 RAD-Lab (Beta-Test-Programm)
- **Kunde / Partner:** ausgewählte Vertraute aus Armins Umfeld (Tester)
- **Zweck:** Qualitätssicherung vor breiter Vermarktung – ausgewählte Tools werden an bekannte Personen verteilt, die sie auf Herz und Nieren prüfen. Aktuell: Fördermittel-Finder, Zuständigkeiten, Projekt-Check (Lizenz „RAD-Lab", `target:"test"`).
- **Status:** läuft (Testrunde bis 30.09.2026)
- **Nächster Schritt:** Feedback der Tester einsammeln und in die Tools einarbeiten; nach 30.09. Lizenz-Zeile aus dem Array entfernen; entscheiden, ob eine zweite Testrunde folgt

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
- **Status:** live (als Tool im Werkzeuge-Portal eingebunden)
- **Nächster Schritt:** Pflege bei VwV-Änderungen

### 3.5 Inkscape-Planrahmen-Vorlage A1/A2/A3
- **Kunde / Partner:** intern (wiederverwendbar)
- **Zweck:** SVG-Planrahmen im 2RAT-Design für QGIS-Drucklayouts, skalierbar.
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
- **Status:** läuft · **v3.2 (12.07.2026)** – Regelwerks-Hierarchie Saarland (ERA maßgeblich, MuLöS BW nur ergänzend), DTV→Kfz/h-Umrechnung im KI-Prompt, Tempo bis 100 (außerorts), max_tokens 2000, Datenschutz auf Netlify korrigiert. Impressum-Mail ✓ erledigt.
- **Nächster Schritt:** Feldtest inkl. Probe-KI-Analyse mit DTV-Wert; Linien-Erfassung verfeinern

### 4.3 Schulweg-Detektive
- **Kunde / Partner:** Jugendpflege Kirkel + 2RAT (Technik)
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
- **Zweck:** Außendarstellung 2RAT – Produktseiten, Kontakt, Kampagnenboxen.
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
- **Zugang:** Code → Passwortmanager (gültig bis 31.12.2028)
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

### 7.1 2RAT Büroverwaltung / Stammdatendokument
- **Kunde / Partner:** intern
- **Zweck:** Claude-Projekt „2RAT Büro" mit Stammdaten, Vorlagen, Projekt-Register. Logo liegt vor (`Logo_2Rat_clean__1_.png`).
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
| **2RAT Büro** *(dieses Projekt)* | Büroverwaltung, Stammdaten, **dieses Verzeichnis**, Steuer, Standardtexte | **HUB** |
| **Hostenbach** | 1.1 · 3.2 QAD · 3.5 Planrahmen | Kundenprojekt |
| **2Rat Radwegemelder Webseite Dashboard** | 4.1 · 1.2 · Supabase | Produkt-Hauptprojekt |
| **Schulweg-Detektive** | 4.3 | Kooperation Kirkel |
| **Plugin-Entwicklung (ANALYSE)** | 3.1 · 3.3 Begründungsgenerator | Werkzeugentwicklung |
| **2Rat Werkzeuge / Tool-Portal** | 2.1–2.10 · 3.4 · 1.5 AGFK | Tool-Vertrieb |
| **2RAT Förderung Radverkehr** | Förder-Wissensbasis · JGF-Fristen · Zuarbeit zu 2.10 | Förderberatung |
| **2rat.org Website** | 5.1 · 5.2 · 5.3 · 5.4 | Marketing |
| **Mobilitätsstationen Wadgassen** | eigenes Kundenprojekt | Kundenprojekt |
| **Kirkel-Projekte** (Bauhof · Castle Race · Bike and Ride) | 4.4 u. a. | Arbeit Gemeinde Kirkel |

> **Regel:** Vor jedem Arbeiten kurz prüfen, in welchem Projekt man ist. Tools → Tool-Portal · Radwegemelder → Kernprodukt · Förderfragen → Förderung-Projekt.

---

# 🔟 URL-Verzeichnis

### Webseiten & Tools

| Ressource | URL |
|---|---|
| 2RAT Website | www.2rat.org |
| Werkzeuge-Portal (Login) | www.2rat.org/Werkzeuge |
| Tool-Dateien (Vollversionen) | www.2rat.org/Werkzeuge/kunden/ *(6 Tools + Karten-Prototyp)* |
| AGFK-Varianten (geplant) | www.2rat.org/Werkzeuge/agfk-sl/ *(noch leer)* |
| Demo-Ordner | www.2rat.org/Werkzeuge/demo/ |
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
| **30.09.2026** | Förderung (FRL-NMOB) | Jahres-Stichtag |
| **30.09.2026** | 1.5 AGFK-SL | Kennenlern-Tools laufen ab (`toolExpires`) → vorher Upsell-Gespräch |
| **30.09.2026** | 2.1 Tool-Portal | RAD-Lab-Testrunde endet (→ 2.13) – Lizenz-Zeile entfernen |
| **Sep 2026** | 4.3 Schulweg-Detektive | Android-Entwicklerbestätigung für PWA-APK prüfen |
| **15.05.2027** | 1.5 AGFK-SL | Lizenz „AGFK Saarland" läuft ab → Verlängerung |
| **27.05.2027** | 1.5 AGFK-SL | Lizenz „AGFK Honorarkraft" läuft ab |

**Überholte Fristen – Ausgang nachtragen:** Wadgassen `date_to` 31.05. · Wadern Mai-Sitzung
**Geklärt 19.07.:** AGFK-Code (neue Lizenz bis 15.05.2027) · Demo-Code (deaktiviert 24.06.)

---

# 1️⃣2️⃣ Statusverteilung

| Status | Anzahl | Vorhaben |
|---|---|---|
| **läuft / live / produktiv / stabil / aktiv** | 23 | 1.2*, 1.5, 2.1, 2.2, 2.3, 2.4, 2.7, 2.9, 2.10, **2.11**, **2.13**, 3.1, 3.3, 3.4, 4.1, 4.2, 4.3, 4.4, 5.1, 5.2, 5.3, 5.4, 6.1 *(1.2: Laufzeit prüfen)* |
| **teils läuft** | 1 | 1.1 |
| **abgeschlossen** | 3 | 2.8, 3.5, 7.3 |
| **vorbereitet** | 3 | 1.4, 2.6 *(Demo-Konzept)*, 3.2 |
| **in Entwicklung / im Aufbau** | 2 | 2.5, 7.1 |
| **Experiment / Prototyp** | 1 | 2.12 |
| **ruht** | 1 | 1.3 |
| **offen** | 1 | 7.2 |
| **verworfen** | 1 | 8.1 |

---

# 1️⃣3️⃣ Zugänge & Codes

*Diese Datei liegt im **öffentlichen** Repo – deshalb hier keine Klartext-Codes. Alle Code-Werte: → Passwortmanager (KeePassXC/Bitwarden). Merkhilfe: alle 2RAT-eigenen Codes laufen bis 31.12.2028.*

| Zugang | Code-Wert | Gültig bis / Status |
|---|---|---|
| **Kommandozentrale** (`2rat.org/cmd`) | → Passwortmanager | 31.12.2028 |
| **„2Rat intern"** (Portal, Vollzugang) | → Passwortmanager *(= Admin-Code aus 05/2026)* | im Array bis 2099 · **aktiv** ✓ |
| AGFK Saarland (Portal) | → Passwortmanager | **15.05.2027** · Projekt-Check dauerhaft, übrige 4 Tools bis 30.09.2026 |
| AGFK Honorarkraft (Portal) | → Passwortmanager | **27.05.2027** · 5-Tool-Suite |
| RAD-Lab (Portal, Beta-Test → 2.13) | → Passwortmanager | 30.09.2026 · danach Lizenz-Zeile entfernen |
| Demo Tool-Portal | *(deaktiviert)* | am 24.06.2026 auskommentiert (Altlast ohne `tools`-Filter) |
| Cockpit (`cockpit.html`) | → Passwortmanager | — |
| RadPlan Pro | → Passwortmanager | — |

**Passwortmanager-Verweise:** Gmail · Supabase (Velomeld) · Netlify · GitHub-Token · Anthropic API-Key · kundenspezifische Cockpit-Codes (via Hash-Generator erzeugt, extern abgelegt)

---

# 🛠 Pflegeanleitung – die 3 Regeln

1. **Eine Datei, eine Wahrheit – und die liegt auf GitHub.** `Werkzeuge/privat/projektverzeichnis.md` im Repo `2Rat/2Rat.github.io` ist die einzige gültige Fassung. Claude liest zu Sitzungsbeginn die raw-URL: `https://raw.githubusercontent.com/2Rat/2Rat.github.io/main/Werkzeuge/privat/projektverzeichnis.md`. Im Projektwissen liegt **keine** Kopie (veraltet sonst).
2. **Updates immer über Claude, immer komplett.** „Claude, Vorhaben X ist jetzt Y" → Claude holt die Live-Version, patcht, liefert die komplette Datei → Armin committet. Auch 📮-Meldungen aus anderen Claude-Projekten laufen so ein – dieses Dokument ist der zentrale Ablageplatz, die anderen Projekte sind Werkstätten.
3. **Wöchentlicher Blick auf 🔥 AKUT.** Der Block oben ist das Erste, was man sieht. Fristen erledigt → raus. Neues Dringendes → rein. Wenn AKUT länger als 8 Zeilen wird: aufräumen. **Keine Klartext-Codes in diese Datei** – das Repo ist öffentlich.

---

*2RAT – Büro für Radverkehrsplanung · Stand: 19.07.2026*

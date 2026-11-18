# 📮 Meldungen-Eingang – 2Rat-Projektverzeichnis

Eingangskorb für 📮-Meldungen aus den Werkstatt-Projekten.
Werkstatt-Projekte hängen hier **nur unten an** (eine Meldung = ein Block).
Das HUB-Projekt „Projektübersicht 2Rat" arbeitet die Meldungen in
`projektverzeichnis.md` ein und leert danach den Bereich unter „Offen".

Regeln (Repo ist öffentlich):
- Keine Klartext-Zugangscodes.
- Keine Preise, Zahlungsstände, Vertriebsstrategie, Rechtliches, Kundeninterna → Projekt „BÜRO 2Rat".
- Nur: Status · Frist · Verweis.
- Schreibweise „2Rat".

Format je Meldung:

```
### JJJJ-MM-TT · <Werkstatt-Projekt> · <Vorhaben-Nr., falls bekannt>
- Was: …
- Status neu: …
- Frist: … (oder „—")
- AKUT: ja/nein
```

---

## Offen

### 2026-11-16 · Werkzeuge Radverkehr Saarland (AGFK-SL) · —
- Was: Projekt-Check v42 und Zuständigkeiten v75 – die Lage aus der Zählstelle (innerorts/außerorts) wird nur noch als Vermutung angezeigt und nicht mehr vorausgewählt; auf benannten Hauptstraßen mit Tempo 50 oder weniger lautet der Vorschlag Ortsdurchfahrt. Anlass: falsche Angabe „außerorts, amtlich“ in einer Ortsdurchfahrt (agfk-werkzeuge 0ab91e5).
- Status neu: live seit 16.11.2026; offen: Zebrastreifen-Erkennung im Repo 2Rat/vwv-stvo
- Frist: 25.11.2026 (Online-Einführung, 14 Uhr)
- AKUT: nein

### 2026-11-16 · Werkzeuge Radverkehr Saarland (AGFK-SL) · —
- Was: Projekt-Check v43, Zuständigkeiten v76 und VwV-StVO v54 – ersetzt die Meldung von heute zu v42/v75. Die Ortslage (innerorts/außerorts) kommt jetzt aus Tempo und Bebauung an der Stelle statt aus der Zählstelle; in OSM markierte Querungen ohne Ampel werden als Zebrastreifen erkannt; der Lückenschluss zählt nur noch Tempo-30-Abschnitte der Hauptstraße selbst; außerhalb des Saarlands macht der Standort-Check keine saarländischen Zuständigkeitsaussagen mehr (agfk-werkzeuge 8d66c48, vwv-stvo 879fb12).
- Status neu: live seit 16.11.2026; Zebrastreifen-Erkennung damit erledigt
- Frist: 25.11.2026 (Online-Einführung, 14 Uhr)
- AKUT: nein

### 2026-11-16 · Werkzeuge Radverkehr Saarland (AGFK-SL) · —
- Was: Das Werkzeug „Zuständigkeiten“ heißt jetzt „Maßnahmen und Zuständigkeiten“ (Titel, Kachel, Verweise, Vermerk, So geht's, Datenschutz, Beispielbild); Dateiname zustaendigkeiten.html unverändert. Stände: Projekt-Check v44, Maßnahmen und Zuständigkeiten v77, Fördermittel-Finder v21, Vergabe-Assistent v18, VwV-StVO v55 (agfk-werkzeuge 4e458aa, vwv-stvo b070554).
- Status neu: live seit 16.11.2026; offen: Name auf agfk-sl.de und im Entwurf zum Deutschen Fahrradpreis nachziehen
- Frist: 25.11.2026 (Online-Einführung, 14 Uhr)
- AKUT: nein

### 2026-11-17 · BÜRO 2Rat · 7.2
- Was: Vorhaben 7.2 heißt jetzt „Steuer / Gewerbe-Status“ (statt „Finanzamt-Status freiberuflich“). 2Rat ist Gewerbebetrieb; Gewerbe bei der Stadt Lebach angemeldet am 03.09.2026 (Beginn der Tätigkeit 01.01.2024, Nebenerwerb); IHK-Mitgliedschaft mit Schreiben vom 10.11.2026 bestätigt.
- Status neu: abgeschlossen (bisher „offen“)
- Frist: ca. 10.01.2027 (Rückmeldung an die IHK, Formulare)
- AKUT: nein

### 2026-11-18 · Werkzeuge / Tool-Portal (AGFK) · Fahrradpreis 2027
- Was: Teilnahmebedingungen 2027 geprüft – AGFK-SL ist teilnahmeberechtigt (Einreicherin muss vom Verein ermächtigt sein). Frist 09.11.–16.12.2026, Verleihung nach dem NRVK Berlin, neue Pflichtangabe „Verwendung des Preisgelds", eingereichtes Material (Texte, Screenshots, Logos) wird unbefristet nutzbar und ist nicht vertraulich. Bewerbungsentwurf liegt vor; Armin füllt das Formular gemeinsam mit Irene aus. Offen: Jury-Zugang hinter dem Zugangsschutz, Ermächtigung.
- Nachtrag 08.11.: AGFK-Fassung VwV-StVO ohne PWA (v23: kein Manifest, kein Service Worker, kein Installieren-Knopf); Kontaktzeile „Zugang oder Rückmeldung" an die Geschäftsstelle auf der Übersicht (ee8eb94). Netlify-Zugangsschutz bleibt; Wiedereingabe löst der Browser-Passwortspeicher.
- Status neu: Bewerbung in Vorbereitung, Frist 16.12.2026
- Frist: 16.12.2026 Bewerbung Fahrradpreis
- AKUT: nein

### 2026-11-18 · Werkzeuge / Tool-Portal (AGFK) · Auslieferung
- Was: Maßnahmen und Zuständigkeiten v79 – Straßenart kommt aus dem eingebauten OSM-Auszug, wenn die Online-Abfrage ausbleibt (nur Wohn-/Nebenstraßen und Wege); Vermerk-Kopf trägt den neuen Namen. VwV-StVO v57 – Abmelde-Skript (sw.js) löscht alte Offline-Kopien aus der Zeit vor dem 08.11., damit alle den aktuellen Stand sehen. Commits: agfk-werkzeuge 6f91d7f, 2fdd949; vwv-stvo 61104a3 – gepusht.
- Status neu: live (Auslieferung über Netlify nicht gesondert nachgeprüft)
- Frist: 25.11.2026 Online-Einführung
- AKUT: nein

### 2026-11-18 · Werkzeuge / Tool-Portal (AGFK) · Auslieferung
- Was: Maßnahmen und Zuständigkeiten v80 – Straßenart bei Wohn- und Nebenstraßen kommt immer aus dem eingebauten OSM-Auszug (wie im Projekt-Check); die Online-Abfrage ergänzt nur noch Radwege und Routen. Commit agfk-werkzeuge 1cb23a8 – gepusht.
- Status neu: live (Auslieferung über Netlify nicht gesondert nachgeprüft)
- Frist: 25.11.2026 Online-Einführung
- AKUT: nein

### 2026-11-18 · Werkzeuge / Tool-Portal (AGFK) · Auslieferung
- Was: Projekt-Check v46 (Zuständigkeit an Bundes-/Landstraßen im Ergebnis nur noch einmal), Maßnahmen und Zuständigkeiten v81, Fördermittel-Finder v22, VwV-StVO v58. In allen Werkzeugen: „Landstraße I./II. Ordnung“ statt „Landesstraße 1./2. Ordnung“; Broschüre des MUKMAV (05/2023) durchgehend als „Empfehlung des Landes“, keine Aussage mehr zur Bindung im Förderverfahren (Festlegung Armin 18.11.). So geht's: Beispielbild VwV-StVO neu. Commits agfk-werkzeuge 216513f, 81cd641, 60e3bd5, 7307765; vwv-stvo 9508be3, e64a14e und Folgecommit – gepusht.
- Offen: übrige Beispielbilder in So geht's gegen den neuen Stand prüfen; Bezeichnung im Geodaten-Bündel von RadPlan Pro an der Quelle ändern.
- Status neu: live (Auslieferung über Netlify nicht gesondert nachgeprüft)
- Frist: 25.11.2026 Online-Einführung
- AKUT: nein

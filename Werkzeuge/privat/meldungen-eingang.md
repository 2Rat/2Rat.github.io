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


### 2026-10-26 · Tools Zuständigkeit/Fördermittel (AGFK-Werkzeuge) · 2.15
- Was: Nicole (AGFK-SL) hat geantwortet: Link-Seite ist https://agfk-sl.de/arbeitshilfen-fachinformationen/ (neuer Tab), Passwort kommt per WhatsApp. Rücklink „Zurück zur AGFK-SL" in index.html eingebaut, Datei zum Hochladen geliefert. Geprüft: VwV-StVO-Tool im Hauptrepo (v11) lädt Karte/Geodaten lokal – Repo agfk-werkzeuge kann privat werden.
- Status neu: Rücklink geliefert, Upload durch Armin offen; Auftragsannahme steht noch aus (Angebot gültig bis 31.10.); 27.10. Netlify Pro + Passwort + Repo privat; 02.11. Freischaltung + Rechnung.
- Frist: Repo privat 27.10. · Freischaltung 02.11.
- AKUT: nein

### 2026-10-26 · Tools Zuständigkeit/Fördermittel (AGFK-Werkzeuge) · 2.15
- Was: Umstellung vorgezogen und erledigt: Rücklink live (Deploy 9:38), Netlify-Team auf Pro, Passwort der AGFK-SL in Netlify gesetzt (Production + Previews), Repo agfk-werkzeuge privat, Test-Deploy 9:53 erfolgreich. GitHub Pages 2rat.org/agfk-werkzeuge/ damit beendet.
- Status neu: Seite läuft passwortgeschützt unter werkzeuge.agfk-sl.de. Offen: Cookie-Satz in datenschutz.html, claude.md aus dem Deploy nehmen, Auftragsannahme Irene (Angebot bis 31.10.), 02.11. Freischaltung + Rechnung.
- Frist: Freischaltung 02.11.
- AKUT: nein

### 2026-10-27 · VwV-StVO 2Rat (App) · neues Vorhaben
- Was: VwV-StVO-Tool (v12) als installierbare Web-App (PWA) für die Fahrradkommunalkonferenz Düsseldorf am 03.11.2026. Eigenes privates Repo 2Rat/vwv-stvo, Netlify-Site vwv-stvo-2rat.netlify.app (kein Passwort, Vorführfassung „Beispiel Saarland“), offline nutzbar außer Karte. Auf Android getestet: Installation, Offline, Karte laufen.
- Status neu: live, Vorführung 03.11. Eigene Domain (vwv.2rat.org) und Zielgruppe (AGFK-Erweiterung 2027 / andere Länder) offen – Entscheidung nach der Konferenz.
- Frist: 03.11.2026 Konferenz
- AKUT: nein

### 2026-10-27 · VwV-StVO 2Rat (App) · Zugang
- Was: Entscheidung Armin: App nicht offen, sondern personalisierter, befristeter Zugang per signiertem Link (v13 live). Lokaler Generator vwv-zugang-generator.html (privater Schlüssel, nur bei Armin) erzeugt Link + QR + WhatsApp, Standard-Ablauf 30.11.2026, Liste mit CSV-Export. Ohne/abgelaufenen Link nur Hinweis mit Kontakt. Armin hat Dauerzugang.
- Status neu: Vorführung 03.11. Düsseldorf mit Links für Interessenten; Nachfassen bis 30.11. Cloudflare Access als Dauerlösung nach der Konferenz prüfen.
- Frist: 30.11.2026 Ablauf Konferenz-Links
- AKUT: nein

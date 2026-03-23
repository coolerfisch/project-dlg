# DLG Präsentation — Startanleitung

## So starten (WICHTIG — nicht direkt öffnen!)

Browser blockieren Audio wenn HTML direkt geöffnet wird.
Deshalb muss ein lokaler Webserver gestartet werden:

### Windows
→ Doppelklick auf **START_SERVER.bat**
→ Browser öffnet sich automatisch

### Mac
→ Doppelklick auf **START_SERVER.command**
→ Falls Sicherheitswarnung: Rechtsklick → Öffnen
→ Browser öffnet sich automatisch

### Manuell (alle Systeme)
```
python3 START_SERVER.py
```
→ Browser öffnen: http://localhost:8765/DLG_Kickoff.html

---

## Sprachausgabe
- **Helmut** (ElevenLabs) spricht automatisch — 18 MP3s im audio/ Ordner
- **s21.mp3** fehlt noch → fällt auf Katja zurück
- Auto-Weiter: Folie wechselt automatisch nach Sprachende
- Einstellungen: ⚙️ Button unten rechts

## Dateien
```
DLG_Praesentation/
├── DLG_Kickoff.html      ← Präsentation
├── audio/
│   ├── s1.mp3            ← Intro (Helmut)
│   ├── s3.mp3 - s19.mp3  ← Folien
│   └── s21.mp3           ← TODO: noch generieren
├── START_SERVER.bat      ← Windows
├── START_SERVER.command  ← Mac
├── START_SERVER.py       ← Python
└── AUDIO_TEXTE.md        ← Texte für s21.mp3
```
